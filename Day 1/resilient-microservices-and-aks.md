# Making your microservices resilient

Tip 1: Graceful degredation

## Expect
Expect that your error will actually happen. Make the app in such a way as to degrade when a service is unavilable the rest of the app can continue without issues.

## Retry
Retry calling a few times before failing (set a policy to limit the timeouts) - API could probably come back up or work next time!

## Circuitbreaker
Try to use the circuitbreaker to detect if a node has failed more than n times - such as to stop overloading a struggling service

## Queues
Use queues to handle resliancy between services so that if a service fails, the messages are still pending in the queue. When the service resumes, things will succeed 

Accepting that failure is the norm will hel you sleep better! 

---
# Resources

[Polly for enforcing policies](https://github.com/App-vNext/Polly)