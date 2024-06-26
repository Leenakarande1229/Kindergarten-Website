Microsoft-Future-Ready-Talent-Virtual-Internship-Project

Project Title: Kindergarten Website

Problem Statement:

The "Kindergarten Website" project aims to develop an intuitive online platform tailored for parents and guardians, providing comprehensive information about kindergarten programs, faculty, and enrollment procedures. This project addresses the need for a user-friendly and informative website to enhance communication and engagement between the kindergarten and its community.

Problem Context:

The purpose of chat bots is to support and scale business teams in their relations with customers. It could live in any major chat applications like Facebook Messenger, Slack, Telegram, Text Messages. Chatbot applications streamline interactions between people and services, enhancing customer experience. At the same time, they offer companies new opportunities to improve the customers engagement process and operational efficiency by reducing the typical cost of customer service. This project is focussed on building a custom chatbot that will be your fundamental step of the learning curve of building your own professional chatbots. But you must be tired of the weird chat bots out there in the world which are made for business purposes? In this project, we would be building an extensive Chatbot service, to which you can talk. And talking to a chatbot would not be business driven. It would just be casual conversations. Collaborating with these types of APIs is very much critical as in today's world the popular chatbots do much more than simply having a data-driven conversation; to supplement additional user-oriented features.

Azure Services Used:

Azure Core Services

1.Azure Virtual Machine:

Azure Virtual Machines (VMs) are on-demand, scalable computing resources provided by Microsoft Azure. They enable you to run virtualized Windows or Linux servers in the cloud. Here are some key points about Azure Virtual Machines

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/d828ca0d-5cfb-4242-b0ae-4f18365d8a26)



2.Azure Monitor CPU Alert:

Creating a CPU usage alert in Azure Monitor involves several steps. Azure Monitor allows you to set up alerts based on various metrics, including CPU usage. Below is a general guide on how to create a CPU usage alert using Azure Monitor

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/c0b280ae-7cd4-4683-b33e-d98d8b0fa344)



3.Azure Network Security Group:
Network Security Groups (NSGs) act as virtual firewalls in Azure, controlling inbound and outbound traffic to Azure resources. They allow or deny traffic based on rules defined by users, such as source and destination IP addresses, ports, and protocols. NSGs provide an additional layer of security by filtering traffic at the network level, helping to protect Azure resources from unauthorized access and malicious attacks.

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/037805ef-b436-4f0a-a64a-c8e7376d6a65)


By configuring Network Security Groups to deny HTTP ports, we restrict inbound traffic on those ports, effectively preventing any HTTP traffic from reaching the designated Azure resources. This action enhances security by blocking potential threats and unauthorized access attempts targeting the HTTP protocol.




4.Azure AI Services

What is a Microsoft Azure QnA Maker Service?

QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications. QnA Maker does not store customer data. All customer data (question answers and chat logs) is stored in the region the customer deploys the dependent service instances in. For more details on dependent services see here. This documentation contains the following article types: • The quickstarts are step-by-step instructions that let you make calls to the service and get results in a short period of time. • The how-to guides contain instructions for using the service in more specific or customized ways. • The conceptual articles provide in-depth explanations of the service's functionality and features. • Tutorials are longer guides that show you how to use the service as a component in broader business solutions. When to use QnA Maker • When you have static information - Use QnA Maker when you have static information in your knowledge base of answers. This knowledge base is custom to your needs, which you've built with documents such as PDFs and URLs. • When you want to provide the same answer to a request, question, or command - when different users submit the same question, the same answer is returned. • When you want to filter static information based on meta-information - add metadata tags to provide additional filtering options relevant to your client application's users and the information. Common metadata information includes chit-chat, content type or format, content purpose, and content freshness. • When you want to manage a bot conversation that includes static information - your knowledge base takes a user's conversational text or command and answers it. If the answer is part of a pre-determined conversation flow, represented in your knowledge base with multi-turn context, the bot can easily provide this flow.

After you publish your knowledge base, a client application sends a user's question to your endpoint. Your QnA Maker service processes the question and responds with the best answer.

Problem’s Primary Goals

• Setting up a chatbot that can order your requirements ( kindergarten programs, admissions, schedules, and activities).

• Using a QnA Maker Bot service to build Kindergarten website chatbot.

• Having a real-world chatbot, to which you can chat like you chatting to a real person and solve your problems.

Input

For input source i use a Editorial custom question and answer type.

Output

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/ca88db1a-f963-4938-a6e9-898b98211de2)

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/e60d39bd-de7f-42b8-94b6-ce842f24c24b)


Microsoft Azure Bot Framework Architecture(Resource visualizer)

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/0ba8ba76-1b10-44f0-ae2a-d5bb80a21017)


Microsoft Azure QnA Maker Development Cycle

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/44528c72-9221-485b-8448-5f704cd62176)



Life Cycle of a Conversational Bot

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/f9803acb-54a9-41e0-93cd-571146a90257)


How to build a bot

Azure Bot Service and the Bot Framework offer an integrated set of tools and services to facilitate the building process. Choose your favorite development environment or command line tools to create your bot. SDKs exist for C#, Java, JavaScript, Typescript, and Python. We provide tools for various stages of bot development to help you design and build bots.

Plan

As with any type of software, having a thorough understanding of the goals, processes and user needs is important to the process of creating a successful bot. Before writing code, review the bot design guidelines for best practices and identify the needs for your bot. You can create a simple bot or include more sophisticated capabilities such as speech, natural language understanding, and question answering.

Build

Your bot is a web service that implements a conversational interface and communicates with the Bot Framework Service to send and receive messages and events. Bot Framework Service is one of the components of the Azure Bot Service and Bot Framework. You can create bots in any number of environments and languages.

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/b15a9f20-e12c-4a79-8960-33117fae337d)



Test

Bots are complex apps with a lot of various parts working together. Like any other complex app, this can lead to some interesting bugs or cause your bot to behave differently than expected. Before publishing, test your bot. We provide several ways to test bots before they are released for use: • Test your bot locally with the emulator. The Bot Framework Emulator is a stand-alone app that not only provides a chat interface but also debugging and interrogation tools to help understand how and why your bot does what it does. The Emulator can be run locally alongside your in-development bot application. • Test your bot on the web. Once configured through the Azure portal your bot can also be reached through a web chat interface. The web chat interface is a fantastic way to grant access to your bot to testers and other people who do not have direct access to the bot's running code.

Publish

When you are ready for your bot to be available on the web, publish your bot to Azure or to your own web service or data center. Having an address on the public internet is the first step to your bot coming to life on your site, or inside chat channels.

Connect

Connect your bot to channels such as Facebook, Messenger, Kik, Slack, Microsoft Teams, Telegram, text/SMS, and Twilio. Bot Framework does most of the work necessary to send and receive messages from all these different platforms - your bot application receives a unified, normalized stream of messages regardless of the number and type of channels it is connected to. For information on adding channels, see channels topic.

Evaluate

Use the data collected in Azure portal to identify opportunities to improve the capabilities and performance of your bot. You can get service-level and instrumentation data like traffic, latency, and integrations. Analytics also provides conversation-level reporting on user, message, and channel data.

Decision Making Between LUIS and QnA Maker

When to use the QnA Maker?

If your organization has lots of static questions and answers), take advantage of out of the box features of QnA Maker. Upload your static questions and answers into QnA Maker Portal, and your application can call QnA API to search for questions asked by the user on the front-end application and return the response.

When to use the LUIS?

If you would like to design the application which needs to extract the information from the user’s questions and further process their intents, then use the LUIS.

Process

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/8532903d-0cd5-4bb9-b396-7428442053ea)



Task 1

Create a Resource Group on Azure

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/0997d431-304d-4c4e-9475-933a1501fab9)



Task2

Create a Language Service on Azure

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/06374c78-f253-4736-8c20-562788bfa3db)



Task3

Create a Knowledge Base on Azure

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/08a4ae4b-c874-462e-ba50-3f27952fc475)


Task4

Create an App Service on Azure

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/14bd1a4f-9434-4ec6-bf5f-b263ba6b9acd)



Task5

Create a Web App Bot on Azure

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/568f413d-e131-499f-812c-53f94383617d)


Task6

Testing my Bot on Azure

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/d2dab22b-413b-4814-a57c-cd9b526c114c)
![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/9d690a60-899d-45bd-9637-b441f3461473)



Expected Outcome

By the end of this milestone, you would be having a working chatbot system that solve your problems about  kindergarten programs, admissions, schedules, and activities etc.

Working Live Project Display

Description:

Here i am attaching the final working website's screenshot for the reference.

![image](https://github.com/Leenakarande1229/Kindergarten-Website/assets/158479285/41f31f23-6f9a-419f-b4f5-baea453ef3c2)



Technologies / Tools Used

• Microsoft Azure QnA Maker Service and cognitive service

• Git Hub

• Azure Storage account and App Service

• Azure Virtual Machine and Network Security Group

• Microsoft Visual Studio

URLs
Drive video URL: https://drive.google.com/file/d/1oYhmGOCHORODkSPrf1YS3mFWbVr-lOe-/view?usp=sharing

PDF File With ScreenShoots and explanation about project : https://drive.google.com/file/d/1JKuM4UP4UnmeVvCe8D5_bfDqf6ezmk8A/view?usp=sharing

working project URL: https://leenakarande1229.github.io/Kindergarten-Website/

Azure Account ID: leena190524@mccmulund.ac.in

Acknowledgements

My sincere thanks, to Microsoft for an impressive QnA Maker service on MS Azure Cloud to make the chatbot development easy. Sincere appreciation to Team of Future Ready Talent who supported and encouraged us to work on this project.
