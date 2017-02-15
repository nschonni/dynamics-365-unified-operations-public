---
# required metadata

title: Create and apply a deployable package
description: This wiki describes the workflow for creating and applying a deployable package.
author: RobinARH
manager: AnnBe
ms.date: 2015-12-11 23 - 50 - 23
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Developer
# ms.devlang: 
# ms.reviewer: 61
ms.search.scope: AX 7.0.0, Operations
# ms.tgt_pltfrm: 
ms.custom: 24211
ms.assetid: a0d1c61a-f6c3-4210-99a0-b45b17c835db
ms.search.region: Global
# ms.search.industry: 
ms.author: shailesn
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0

---

# Create and apply a deployable package

This wiki describes the workflow for creating and applying a deployable package.

Overview of the packaging and deployment process
------------------------------------------------

The following diagram shows the workflow for creating and applying a deployable package. [![Workflow for creating and applying a deployable package](./media/pack1.png)](./media/pack1.png) **Note:** The manual steps that are described in this article will be automated as part of the servicing features that are being developed.

## Create a deployable package
After you have completed the development of the modules, follow these steps to create and upload a deployable package.

1.  In Microsoft Visual Studio, select **Dynamics 365** &gt; **Deploy** &gt; **Create Deployable Package**.
2.  Select the package that contains your model, and then select a location in which to create the deployable package. [![Selecting a package](./media/pack3.png)](./media/pack3.png) [![Selecting a location](./media/pack4.png)](./media/pack4.png)
3.  After a deployable package is created, sign in to Microsoft Dynamics Lifecycle Services (LCS), and then, in your LCS project, click the **Asset Library** tile. [![Asset Library](./media/pack5-1024x430.png)](./media/pack5.png)
4.  Upload the deployable package that you created earlier. [![Uploading a deployable package](./media/pack6-1024x325.png)](./media/pack6.png)

## Apply a deployable package
For information about how to apply a deployable package in an environment, see [Installing a deployable package](install-deployable-package.md).
