# Keynote presented by Satya Nadella

## Opportunity & Responsibility
- Last years topics
- Greatly relevant and expanded this year
    - Especially around intelligent edge
    - Intelligent edge is shaping the cloud
- Responsibility to avoid Orwellian future

> The most profound technologies are those that disappear. They weave themselves into the fabric of everyday life until they are indistinguishable from it

## The World is becoming a computer
- Computers are everwhere in our life and becoming invisible
- Almost every part of our life is being transformed by our computers
    - By 2020 smart homes will generate *50GB* of data a day
- We have a responsibility to ensure that technology is growing everyone's lives and industries:
    - > Act so that the effects of your action are compatitble with the permanence of genuine human life - Hans Jonas
- We need to develop principles that guide the decisions we make

## 4 Pillars:

### Privacy
- Privacy is a human right
- When we use data we use it to benefit the user
- GDPR - A sound, good resolution
    - Microsoft has put hundreds of engineers in the company to become compliant
- Microsoft works closely with governments to balance the laws and privacy 
    - Interesting that Microsoft defines things like the Cloud Act
- Ensure that customers are in control
### Cybersecurity
- Act with collective responsibility to help keep the world safe
- Microsoft leading effort to help secure elections
- Works with coallition of 34 companies to help global efforts
- The Geneva Convention of the technical revolution
### Ethical AI
- What computers can do and what they *should* do
    - That time has come he says!
- The choices we make must be good choices for our future
- Working to de-bias languages for AI
    - Learning is based on languages that have inherent bias in normal use online
- Create private AIs that can use encrypted data as sources too
    - Working with meidcal and pharma companies

I guess I missed the 4th piller! Sorry about that.

## Microsoft Mission 

> Empower every person and every organization on the planet to achieve more

### Platfrom opportunity

- Microsoft Azure
- Microsoft 365

The inteligent edge and cloud provides ubiquitous computing. 

## Ubiquitous Computing

### Azure is being built as the World's Computer

- More regions than any other cloud
- Building out offerings to create a computer fabric that touches the edge from the cloud

### Azure
- Azure stack used by Chevron to power disconnected oil rigs
- Shlumberger using azure stack in distributed computing
    - Azure stack being on-prem Azure
### Azure IoT Edge
- On-device azure
- Supported on linux and windows
- Announced open sourcing of Azure IoT Edge
- Qualcomm partnerting to create a computer vision toolkit with a new camera
- Train a container on the cloud and then deploy to hardware
- DJI parnerting to create a Windows SDK for DJI and trainable drones using Azure IoT edge

### Azure Sphere
- Brings secure chips, secure OS and secure management service together
- Secures micro-controllers (9 billion / year)
- Follows same programming model and toolchain as Azure

# IoT from Sam george (Director, Azure IoT)
## Azure IoT edge emables azure IoT services to be deployed to devices directly and managed elswhere
- Showed a camera running Azure IoT in a rockwell facility. It runs a docker container with a ML app inside deployed to from Azure. It detected a break in a pipe and the app was able to create a ticket
- DJI is getting Azure IoT to run on their drones. You can deploy the same program to the camera as you can the drone
    - The DJI streamed video over Azure IoTA
    - The video highlighed an anomily in the pipe live and the camera showed a yellow box around it
    - The video was being processed in the cloud but in the future it will be onboard a more powerful drone

# AI
- 2016 AI reached human parity in object recognition
- 2017 AI reached speech recognition human parity
- 2018 January mmachine reading comprehension
- 2018 March machine translation human parity

Azure AI for every developer and every organization is a goal for Microsoft

3 paradigms:
- Scale AI across cloud and edge
- Productive toolchain for AI creators and customization
- Open frameworks and infrastructure

## Azure Cognitive Services
The largest number of cognitive services (speach, vision, machine reading)

The important thing is each service is customizable for your needs,

- Coca-Cola uses computer vision for a marketing program
- NBA uses the semantic search cognitive service
- Twitter uses it for translating every tweet
- Huawei uses Azure AI onboard on phones and a specific device

Announcing speech device SDK for devices to be able to use

Talking about Kinect:
    - It *was* used in gamming :(
    - Learnings from kinect going into holo-lense

Project Kinect for Azure!
    - Making kinect a lot smaller so it can be deployed into machines

## Azure Conversational AI

> Bots are the new apps

Bots will need to be branded through agents. Agents should be able to talk through a suite of personal assistants.

### Launching 100+ new features for the bot framework

- Very customizable
- Easy to select multiple environemnts for the bot (ex. Cortana, skype, etc)


## Azure AI Framework and Tools
- Best Data Estate
    - How we store the data to power the AI
- Best Toolchain
    - Building out how we can work with AI
- Most open
    - Choose whatever framework you like best

### Announced Project Brainwave
Distributed real-time AI (5x lower latency than TPU)
On-cloud and on-edge (on Azure IoT for example)

## Multi-sense, multi-device experiences

Microsoft sees Microsoft 365 as the way to this

- Windows and office combined
- Built for crossing device boundries

Allows the abstraction of the user from the single device (AKA a log in system or Apple's handoff?)

Timeline = Microsoft HandOff except hardware independent. Dependent on being in a Microsoft service

Excel can call azure functions

Microsoft wants Cortana to be able to talk to other digital assistants (Multi-agent)

### Cortana talking to Alexa

Demo of alexa opening cortana (cortana takes over alexa) and cortana opening alexa (alexa takes over cortana)

It's all very cool but unwrapping an assistant through an assistant feels awkward and unlikely to be used. It means building skills in one or the other is exposing you to both.

### Microsoft Graph
- Graph API means the user owns their data and are given the opportunity to *grant* access to data to an application
- Oauth flow enables this
- Apparently github is using it. I've never been prompted by github for access to my graph API. Seems to be more useful in a coroporate environment to me

Launching SaaS apps for office 365 using hololens
    - Microsoft Remote Assist
        - Remote Assist brings an expert to the location
        - Helps eliminate travel
    - Microsoft Layout
        - Create designs with real world context, share and edit with stakeholders live

## Micrsoft Gaming
- Incoming E3 announcement around where Microsoft is taking gaming