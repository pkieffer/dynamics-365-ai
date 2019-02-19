---
title: "Profiles | MicrosoftDocs"
description: 
ms.custom: ""
ms.date: 02/21/2019
ms.reviewer: ""
ms.service: "dynamics-365-ai"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: 83200632-a36b-4401-ba41-952e5b43f939
caps.latest.revision: 31
author: "jimholtz"
ms.author: "jimholtz"
manager: "kvivek"
---
# Profiles

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

The **Profiles** page presents consolidated data on each of your customers. Each customer profile is represented by a **Customer Card** tile as shown below.

> [!div class="mx-imgBorder"] 
> ![](media/customer-card-tile.png "Customer Card tiles")

In order to view more customers profiles, move to the next profiles page using the button shown above in red. In our example, there are no additional customers and so there is only a single profiles page.

**Note**: The data that is available in this page is based on the unified Customer Profile entity you have created during the data configuration process. If you didn’t complete  the data configuration process, see the **Configure Data** section.

After selecting a customer tile, you will see additional information on that specific customer. As shown below, that information may include attributes such as **Country**, **Email**, **Address**, and **Phone** that exist in one or more of your data sources.

> [!div class="mx-imgBorder"] 
> ![](media/customer-card-tile-customer-info.png "Customer Card tile customer info")

You can also create custom attributes using the **Measures** page. The following example is the customer **Churn Score** information marked in red below.

> [!div class="mx-imgBorder"] 
> ![](media/customer-card-tile-customer-churn-score.png "Customer Card tile churn score")

## Search for customers

Searching for customers can be done using the **Search** field. Simply type one of the attributes' names to search for customers. This is enabled by the administrator in the **Search, sort & filter** page. Note that the search will be executed only within the Customer Profile entity created during the data configuration process.

If you haven’t gone through both the **Data Manager** and **Data Configuration** processes, visit those process sections first.

> [!div class="mx-imgBorder"] 
> ![](media/customer-card-tile-search.png "Customer Card tile search")

You can also utilize this capability to search for a specific type of information (specific attribute) for a given customer.

> [!div class="mx-imgBorder"] 
> ![](media/customer-card-tile-search2.png "Customer Card tile search")

## Filter customers

Filtering customers can be done via a menu that includes your Customer Profile entity fields as filters. 

First, select **Filter**.

> [!div class="mx-imgBorder"] 
> ![](media/customer-card-tile-filter.png "Customer Card tile filter")

Then, simply check the boxes next to the filters with which to search customers by. Same as for the **Search** field. You will be able to filter only by attributes that exist in your Customer Profile entity and that were defined by the administrator in the **Search, sort & filter** page.

You can remove your saved filters using **Clear filters**.

> [!div class="mx-imgBorder"] 
> ![](media/customer-card-tile-clear-filter.png "Customer Card tile clear filter")