# MTT CoHack Challenge : [Topic Name]


## Introduction

Welcome to Contoso, a thriving company that prides itself on delivering exceptional customer service. As the company grows, so does the volume of customer inquiries. Most of these inquiries are sent to a central email address, info@contoso.com. Managing and sorting through these emails manually has become a daunting task, leading to delays in responses and decreased customer satisfaction.

## The Challenge

Imagine you are the CEO of Contoso. You recognize the need for a more efficient way to handle customer inquiries. The goal is to ensure that each email reaches the right team quickly, so customers receive timely and accurate responses. To achieve this, you decide to leverage the power of Azure AI Language Custom Text Classification and Power Automate.

## The Solution

Azure AI Language Custom Text Classification is a powerful tool that can analyze the content of incoming emails and categorize them based on their topics. By training the AI model with examples of different types of inquiries, you can teach it to recognize patterns and classify emails accurately.

Once the emails are classified, Power Automate comes into play. This automation tool will take the classified emails and distribute them to the appropriate Teams channels. For example, billing-related inquiries will be sent to the Finance Team channel, while technical support questions will go to the Support Team channel.


## Requirements

- Copilot
- Azure Subscription
- Microsoft 365 Subscription

## Learning Objectives

This hack will help you learn:

- How to use Copilot to create sampla data
- How to train Azure AI Language Custom Text Classification
- How to automate processes using Power Automate

## Success Criteria

### Challenge 1 - sampla data

- 3 different types of e-mails, eech type 10 examples for training
- sample e-mails for testing, including one not related to anothers

### Challenge 2 - Azure AI Custom Text Classification

- You can classifie e-mail content
- You have REST API endpoint and key

#### Resources

- [Quickstart: Custom text classification](https://learn.microsoft.com/en-us/azure/ai-services/language-service/custom-text-classification/quickstart?tabs=multi-classification&pivots=language-studio)

### Challenge 3 - Power Automate

- You run flow using New email event
- You distribute e-mail content based on Custom Text Classification to Teams channels

#### Resources

- [Use the Language service in Power Automate](https://learn.microsoft.com/en-us/azure/ai-services/language-service/tutorials/power-automate)

