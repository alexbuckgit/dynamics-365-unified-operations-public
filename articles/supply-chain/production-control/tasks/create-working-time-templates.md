--- 
title: Create working time templates
description: Working time templates define the working hours throughout a week and are used to generate working times for a period of time.
author: johanhoffmann
ms.author: johanho
ms.topic: how-to
ms.date: 08/29/2018
ms.custom:
ms.reviewer: kamaybac 
ms.search.form: OpResLifeCycleManagementWorkspace, WorkTimeTable, WorkTimeCopyDayDialog, WorkPeriodTemplate
---

# Create working time templates

[!include [banner](../../includes/banner.md)]

Working time templates define the working hours throughout a week and are used to generate working times for a period of time. This procedure shows you how to define a working time template using working time scheduling properties for categorizing working time intervals. You can walk through this procedure in demo data company USMF, or using your own data.

1. Go to **Workspaces > Resource lifecycle management**.
1. Select **Working time templates**.

## Create working time template

1. Select **New**.
1. In the **Working time template** field, type a value.
1. In the **Name** field, type a value.
1. Expand the **Monday** section.
1. Select **Add**.
1. In the **From** field, enter a time.
    * Specify the time when work begins in the morning.  
1. In the **To** field, enter a time.
    * Specify the time when workers break for lunch.  
1. Select **Add**.
1. In the **From** field, enter a time.
    * Specify the time when work resumes after lunch.  
1. In the **To** field, enter a time.
    * Specify the end of the work day.  

## Replicate working times to all week days

1. Select **Copy day**.
    * Copy the working times definitions from Monday to Tuesday.  
1. Select **OK**.
1. Select **Copy day**.
    * Copy the working times definitions from Monday to Wednesday.  
1. In the **To weekday** field, select an option.
1. Select **OK**.
1. Select **Copy day**.
    * Copy the working times definitions from Monday to Thursday.  
1. In the **To weekday** field, select an option.
1. Select **OK**.
1. Select **Copy day**.
    * Copy the working times definitions from Monday to Friday.  
1. In the **To weekday** field, select an option.
1. Select **OK**.

## Define time slots for special operations

1. Expand the **Friday** section.
1. In the list, find and select the desired record.
1. In the **Property** field, enter or select a value.
1. In the list, find and select the desired record.
1. In the **Property** field, enter or select a value.

## Mark weekend days as closed for pickup

1. Expand the **Saturday** section.
1. Select *Yes* in the **Closed for pickup** field.
1. Expand the **Sunday** section.
1. Select *Yes* in the **Closed for pickup** field.


[!INCLUDE[footer-include](../../../includes/footer-banner.md)]