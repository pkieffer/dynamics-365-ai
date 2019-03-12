---
title: "Creating a virtual agent"
description: "Learn how to use the Dynamics 365 Virtual Agent for Customer Service to create a virtual agent."
keywords: ""
ms.date: 2/26/2019
ms.service:
  - "dynamics-365-ai"
ms.topic: article
ms.assetid: 
author: stevesaunders1952
ms.author: stevesaunders1952
manager: shellyha
---

# Creating a virtual agent

You can use the Virtual Agent Designer to create a powerful custom virtual agent. The Virtual Agent Designer makes it easy to create virtual agents that address common support issues. You can design a conversation path that leads each customer to a resolution.

To help get you started and tailor the virtual agent to your specific needs, the Virtual Agent Designer lets you create a virtual agent using built-in industry-specific templates. For example, the Virtual Agent Designer includes a template to help you create a virtual agent for a retail business.

Each template comes with built-in content building blocks containing topics, trigger phrases, and pre-authored conversation paths that are tailored to a specific industry. For example, the Retail template includes a topic that lets you easily communicate store hours to customers.

These industry templates can also be useful as a model for building your own conversations for similar customer-support issues. For more information, see [Work with templates](how-to-templates.md).

## To create a virtual agent

1. If you have not already created a PowerApps environment, create one. You must select an environment when you create your virtual agent.

    For more information about creating a PowerApps environment, see [Creating a PowerApps environment](getting-started-new-environment.md).

2. Open the Virtual Agent Designer in your browser to display the **Create a new bot** screen. Dynamics 365 Virtual Agent for Customer Service supports Chrome (preferred) and Edge browsers.

    If you have already created a virtual agent, you can create a new bot by selecting the **New Bot** icon on the title bar. Then select **New bot**.

   > ![New bot icon](media/new-bot-icon.png)

3. Select the template you want to use, and specify a name and region for the bot.

    In the **Region where your Virtual Agent is stored** drop-down, select the PowerApps environment you created. Then select **Create**.

    > [!NOTE]
    > Do not select the Default environment, which is not currently supported.

    Virtual Agent Designer creates the virtual agent and opens it in the browser.

   > ![Open bot](media/open-bot.png)

Once you have created your virtual agent, you can add topics that represent the customer intents to be addressed by the virtual agent and then deploy it to a web channel. As customers use the virtual agent, you can view analytics information to help you improve it and the overall customer experience.

For more information about creating topics for your virtual agent, see [Creating topics for your virtual agent](getting-started-create-topics.md).

For more information about deploying your virtual agent, see [Deploying your virtual agent](getting-started-deploy.md).

For more information about using analytics information to help you improve your virtual agent, see [Using analytics to improve your virtual agent](getting-started-analytics.md).

For more information about working with the Virtual Agent Designer, see [Working with the Virtual Agent Designer](getting-started-bot-designer.md).

For information about removing your virtual agent from the Virtual Agent Designer environment, see [Deleting a virtual agent](getting-started-delete-bot.md).