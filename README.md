# Smart Campus Enquiry
## Problem Statement: When a student wants to take admission in a new college he/she faces a lot of issues regarding correct information about the college especially when it comes to government colleges & private colleges in rural areas. During Covid-19 Lockdown students faced many issues; they were unaware & unsure about the information. When students don't get right information by sitting in their homes, they have to travel to college to ask about the information regarding college in college office & senior students who are already studying in college. Students who are already admitted in colleges faces difficulty in getting correct notifications at correct time related to college hostel, holidays, training & placement events, Trainings & internships recommended by college etc. 
## Description: The project is mainly targeted at colleges and the synchronization of all the sparse and diverse information regarding the regular college. In this project we are making a chat bot for students to ask or enquire about college by sitting in their homes. Due to this project students don't have to personally go to college office for the enquiry which will result in minimizing the time required to solve the queries. This project tries to bridge the gap between students, teachers, college administrators and senior students studying in the college. Therefore in the real world scenario, such as college campus, the information in the form of notices, oral communication, can be directly communicated through the android devices and can be made available for the students, teachers directly for their android devices and the maintenance of application will be easier in later future.
## Introduction: Azure Chatbot- Smart Campus is a chatbot which guides students to get information regarding college. For eg. Fee Structure, College essentials, Training etc.
## Technologies Used

- Microsoft Azure

In this project I have taken **Microsoft Azure** as primary technology.
Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. These services and resources include storing your data and transforming it, depending on your requirements. To get access to these resources and services, all you need to have is an active internet connection and the ability to connect to the Azure portal. It was launched on February 1, 2010.
Interestingly, 80 percent of the Fortune 500 companies use Azure services for their cloud computing needs.


In this project, I have used these following **Azure Cognitive Services** into my project:

1. QnA Maker: QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications. QnA Maker doesn't store customer data. All customer data (question answers and chat logs) is stored in the region the customer deploys the dependent service instances in.

2. Knowledge Base: QnA Maker imports your content into a knowledge base of question and answer pairs. The import process extracts information about the relationship between the parts of your structured and semi-structured content to imply relationships between the question and answer pairs. You can edit these question and answer pairs or add new pairs.

3. App Service Plan: An App Service plan defines a set of compute resources for a web app to run. These compute resources are analogous to the server farm in conventional web hosting. One or more apps can be configured to run on the same computing resources (or in the same App Service plan).

4. App Service: Quickly build web apps and APIs in the cloud. Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. You can develop in your favorite language, be it . NET, . NET Core, Java, Ruby, Node.

5. Application Insights: Application Insights is a feature of Azure Monitor that provides extensible application performance management (APM) and monitoring for live web apps. Developers and DevOps professionals can use Application Insights to: Automatically detect performance anomalies. Help diagnose issues by using powerful analytics tools.

6. Search Service: Azure has a unique service offering aptly named “Azure Search”. This is a search-as-a-service cloud solution that lets you add a rich search service to your apps. The search service abstracts the complexities of document retrieval through both a REST API and a . NET SDK.

7. Web App Bot: The Azure Bot resource provides the infrastructure that allows a bot to access secured resources. It also allows the user to communicate with the bot via several channels such as Web Chat.

-Developed a Website using Languages such as HTML & CSS. Framework used is- Bootstrap. I have hosted this website on Replit. Replit is a simple yet powerful online IDE, Editor, Compiler, Interpreter, and REPL. Code, compile, run, and host in 50+ programming languages.

## Background working of Azure Cognitive Services:

![Customer service bot](https://docs.microsoft.com/en-us/gaming/azure/reference-architectures/media/cognitive/cognitive-customer-service-bot.png)

Here, in the above diagram, explains how cognitive services work in background.  
Architecture Services

Azure Bot Service - Azure out-of-the-box solution for building serverless and scalable bots.
Azure Language Understanding (LUIS) - Applies custom machine-learning intelligence to a user's conversational, natural language text to predict overall meaning, and pull out relevant, detailed information.
Azure QnA Maker - Creates a question and answer repository of data based on information you provide.
Azure Application Insights - Optionally used to monitor the customer service bot. It will automatically detect performance anomalies and help understand what users actually do with the bot.

With the help of Azure QnA maker we have created an knowledge base, then this knowledge base is connected to our azure chatbot and this chat bot is then embedded to our Website- Smart Campus --> Client Device sends input to the Bot --> Azure Language understanding understands the client queries and automatically chooses an knowledge base and hence finds the similar answer and sends the output.

## Steps followed: 
Step 1: Created an Azure Resource Group named "Collegeinformation". 

![1](https://user-images.githubusercontent.com/81363651/160895285-a85ed137-9eb0-419e-a762-99347a5c46f5.JPG)


Step 2: Created Azure QnA Maker.

![2](https://user-images.githubusercontent.com/81363651/160895349-d0b13eb0-f68e-4b15-911f-5811d2550841.JPG)


Step 3: Created an Azure Knowledge Base:

![3](https://user-images.githubusercontent.com/81363651/160895394-a4fab88b-ad9a-48a3-aaf8-7d62d2be78c6.JPG)

![4](https://user-images.githubusercontent.com/81363651/160895498-1c2b9554-079b-4f14-9cfb-36c538e028f5.JPG)

 
Step 4: Train the Bot using test feature in Knowledge Base:

![5](https://user-images.githubusercontent.com/81363651/160895558-f312ee53-acc5-483e-a9fb-d39b514ec874.JPG)


Step 5: Publishing the Bot by creating Azure Bot 

![6](https://user-images.githubusercontent.com/81363651/160895630-6e7ab2f4-4e29-41c4-ad58-2c065d210865.JPG)

![7](https://user-images.githubusercontent.com/81363651/160895695-cac68a8e-e6ef-4e46-a320-dfbf4a263400.JPG)

![8](https://user-images.githubusercontent.com/81363651/160895712-50f6f0d8-acc8-492e-9416-c0232172d76b.JPG)


Step 6: Copying the Embedded code and Secret Key to Website source code to enable our chatbot to work

![9](https://user-images.githubusercontent.com/81363651/160895805-b60141e1-3cdb-49ba-91d3-2865de9823e0.JPG)

![10](https://user-images.githubusercontent.com/81363651/160895830-ead1345b-2e43-41e2-a2b1-81c79dba2a21.JPG)


Step 7: Testing on Actual Website if the bot is working or not. 

![11](https://user-images.githubusercontent.com/81363651/160895934-83722994-4844-4b9e-83f9-66d84c983044.JPG)



## Project Link: https://smartcampusenquiry.kirtika-dd.repl.co/


## Project Demo on Youtube: https://youtu.be/GG6w0Qr0fjQ




*This repository contains database of question and answer pairs used in knowledge base for the chatbot, and data of the website.* 







