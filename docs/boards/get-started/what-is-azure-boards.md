---
title: What is Azure Boards? Tools to manage software development projects.  
titleSuffix: Azure Boards
description: Learn about the Agile tools Azure Boards provides. 
ms.custom: boards-get-started, contperf-fy22q2
ms.subservice: azure-devops-new-user
ms.assetid:  
ms.author: chcomley
author: chcomley
ms.topic: overview
monikerRange: '<= azure-devops'
ms.date: 03/17/2023
---

# What is Azure Boards?

[!INCLUDE [version-lt-eq-azure-devops](../../includes/version-lt-eq-azure-devops.md)]

Azure Boards is a standalone service within the Azure DevOps suite that helps teams plan, track, and discuss work across the entire software development process. It provides a flexible, customizable platform for managing work items, such as user stories, bugs, tasks, and issues, so you can track your work item's progress throughout the development lifecycle. 

Azure Boards supports agile methodologies, including [Scrum and Kanban](#implement-agile-scrum-and-kanban-processes). It provides a range of features and integrations to help teams [collaborate](../../cross-service/cross-service-overview.md) and stay organized with [dashboards, reports](#configure-dashboards-and-power-bi-reports), and notifications.

If you're ready, [sign up and invite your teammates](sign-up-invite-teammates.md). If you want more information, see the [benefits of using Azure Boards](#benefits-of-using-azure-boards), later on in this article.
 
## Use Azure Boards hubs

You can track work in Azure Boards using default or customized work item types and standard system fields, and manage those work items with interactive backlogs, boards, lists, and calendar views. You can access various functions within each hub in Azure Boards, as shown in the following table.

|Azure Boards hub  |Functions  |
|---------|---------|
|[**Work items**](../work-items/view-add-work-items.md)    | Access lists of work items based on specific criteria, such as those assigned to you, ones you follow, and work items you viewed or updated.        |
|[**Boards**](../boards/kanban-quickstart.md) | View work items as cards and update their status through drag-and-drop, similar to physical sticky notes on a whiteboard. Use this feature to implement Kanban practices and visualize work flow for a team.        |
|[**Backlogs**](../backlogs/create-your-backlog.md)    | view, plan, order, and organize work items, including using a product backlog to represent your project plan and a portfolio backlog to group work under features and epics.        |
|[**Sprints**](../sprints/assign-work-sprint.md)   | access your team's filtered view of work items based on a specific sprint or iteration path. Assign work to a sprint using drag-and-drop from the backlog. Interact with a backlog list or card-based taskboard to implement Scrum practices.        |
|[**Queries**](../queries/view-run-query.md)  | Generate custom work item lists and perform various tasks, such as triage work, make bulk updates, and view relationships between work items. Queries also allow for creating status and trend charts that can be added to dashboards.        |
|[**Delivery Plans**](../plans/review-team-plans.md)   | Management teams can view deliverables and track dependencies across multiple teams in a calendar view. Delivery plans support tasks such as viewing up to 15 team backlogs, custom portfolio backlogs and epics, and work that spans several iterations. Users can add backlog items to a plan, view rollup progress of features and epics, and dependencies between work items.        |

:::image type="content" source="media/about-boards/boards-hubs.png" alt-text="Screenshot showing hubs in Azure Boards menu.":::

## Connect Azure Boards to GitHub

Connect Azure Boards with GitHub repositories to link GitHub commits, pull requests, and issues to work items. Use GitHub for software development and Azure Boards to plan and track work. Quickly open linked GitHub commits, pull requests, or issues from the Kanban board. For more information, see [GitHub & Azure Boards](../github/index.md).   

## Implement Agile, Scrum, and Kanban processes  

Azure Boards supports software development processes with default process models. Each process includes a set of work item types with a natural hierarchy.
 
:::row:::
   :::column span="2":::
   [**Basic**](../get-started/plan-track-work.md) provides the simplest model that tracks work through Issues, Tasks, and Epics. 
   :::column-end:::
   :::column span="2":::
   :::image type="content" source="../get-started/media/about-boards/basic-process-epics-issues-tasks-2.png" alt-text="Conceptual image of Basic work item types":::  
   :::column-end:::
:::row-end:::
:::row:::
   :::column span="2":::
   [**Agile**](../work-items/guidance/agile-process.md) supports Agile planning methods (learn more about Agile methodologies at the
   [Agile Alliance](https://www.agilealliance.org/)), including Scrum,
   and tracks development and test activities separately. This process works great if you want to track user stories and
   (optionally) bugs on the Kanban board, or track bugs and tasks on the taskboard.  
   :::column-end:::
   :::column span="2":::
   :::image type="content" source="../work-items/guidance/media/ALM_PT_Agile_WIT_Artifacts.png" alt-text="Agile work item types":::  
   :::column-end:::
:::row-end:::
:::row:::
   :::column span="2":::
   [**Scrum**](../work-items/guidance/scrum-process.md) tracks work using product backlog items (PBIs) and
   bugs on the Kanban board or viewed on a sprint taskboard.
   
   This process supports the Scrum methodology as defined by the [Scrum organization](https://www.scrum.org/)
   :::column-end:::
   :::column span="2":::
   :::image type="content" source="../work-items/guidance/media/ALM_PT_Scrum_WIT_Artifacts.png" alt-text="Scrum work item types":::  
   :::column-end:::
:::row-end:::
:::row::: 
   :::column span="2":::
   [**Capability Maturity Model Integration** (CMMI)](../work-items/guidance/cmmi-process.md) supports a framework for process improvement and an auditable record of decisions. With this process, you can track requirements, change requests, risks, and reviews.
   This process supports [formal change management activities](../work-items/guidance/cmmi/guidance-background-to-cmmi.md). 
   :::column-end:::
   :::column span="2":::
   :::image type="content" source="../work-items/guidance/media/ALM_PT_CMMI_WIT_Artifacts.png" alt-text="CMMI work item types":::  
   :::column-end:::
  :::row-end:::
 

## Configure dashboards and Power BI reports 

Dashboards provide teams with customized views for status updates, progress tracking, and trend analysis. Teams can share information and improve workflows with flexible and tailored dashboard options.

:::image type="content" source="media/about-boards/dashboard.png" alt-text="Screenshot of Azure Boards, Dashboards":::   

Use Power BI to create customized reports based on Analytics service queries for quantitative analysis of project data. For more information, see [About dashboards, charts, reports, & widgets](../../report/dashboards/overview.md) and [What is the Analytics service?](../../report/powerbi/what-is-analytics.md).


## Gain visibility through end-to-end traceability

With Azure Boards, you gain the advantage of full integration with the Azure DevOps platform. Azure DevOps is designed to provide end-to-end traceability, tracking work from requirements to deployment. You gain insight at each step of decisions made and software deployed. Some of the traceability tasks supported include: 
 
- Create a branch from a requirement
- Create a pull request of updated branch
- Validate the pull request using a build pipeline
- Create and run inline tests on requirements
- Merge the pull request into the main, default branch
- Deploy changes into production with deployment status to Azure Boards
- Monitor and report on requirements traceability

For more information about these features, see [End-to-end traceability](../../cross-service/end-to-end-traceability.md) and [Cross-service integration and collaboration overview](../../cross-service/cross-service-overview.md).

<a id="scale" />

## Support independent, autonomous teams 

A team in Azure Boards is a group of project members who work in a specific product area represented by hierarchical paths called **Area Paths**. Define teams by their name, members, and area paths and are essential for configuring Boards, Backlogs, Sprints, and Delivery Plans in Azure Boards. For more information, see [About teams and Agile tools](../../organizations/settings/about-teams-and-settings.md). 

:::image type="content" source="../../organizations/settings/media/agile-tools/agile-tools-team-assets.png" alt-text="Conceptual image of team tools":::   


Azure Boards integrates with popular chat tools such as [Microsoft Teams](../integrations/boards-teams.md) and [Slack](../integrations/boards-slack.md) through ChatOps. It also offers extensions that add new capabilities to your projects and can be found in the [Azure DevOps Marketplace](https://marketplace.visualstudio.com/azuredevops). These extensions can help with planning and tracking work items, sprints, scrums, and other project management tasks, as well as collaboration among team members. 

## Benefits of using Azure Boards

The following table lists some of the benefits of using Azure Boards.

|Benefit |Details  |
|---------|---------|
|Start simply, scale as you grow     | Azure Boards offers predefined work item types for tracking features, user stories, bugs, and tasks, making it easy to start using your product backlog or Kanban board. It supports different Agile methods, so you can implement the method that suits you best. Additionally, you can add teams as your organization grows to give them the autonomy to track their work as they see fit.        |
|Use visual, interactive tools     | Visual tools help teams quickly see and share progress with [Kanban boards](../boards/kanban-quickstart.md), [product backlogs](../backlogs/create-your-backlog.md), [built-in scrum boards and planning tools](../sprints/scrum-overview.md), and [delivery plans](../plans/review-team-plans.md).        |
|Customize easily   |Easily configure and customize Kanban boards, taskboards, and delivery plans through the user interface, as well as add [custom fields, work item types, and portfolio backlogs](../../organizations/settings/work/inheritance-process-model.md).         |
|Use built-in social tools and communication   |  Work item forms provide built-in discussion that you can use to capture questions, notes, and communication as they occur. With this feature, you can maintain a history of what a team decides on any particular work item. You can quickly bring a team member or an entire team into the conversation [by using @mentions](../../organizations/notifications/at-mentions.md).        |
|Capture information, generous cloud storage   | Work items are designed to track all the information you need to track. You can edit in rich text, drag and drop inline images, and add larger attachments. You can add attachments up to 60 MB and as many as 100 attachments. Also, you can link work items within a hierarchy or by simple related links. Each work item form maintains a history of changes, so you can review what changed, who made the change, and when.        |
|Find what you need quickly and get notified of changes   | Azure Boards provides easy-to-use tools to help you quickly find specific work items as your project grows. You can follow work items to monitor updates and changes, use pivot views to show work items assigned to you, use the query engine to filter work items based on any field, and use ad-hoc search with quick inline filters. You can also personalize your alerts for work items that are assigned to you or have been changed.        |
|Monitor status and progress with built-in dashboards and analytics     | With Azure Boards, you gain access to many tools to generate reports to support tracking status and trends. By using [configurable dashboards](../../report/dashboards/dashboards.md), you can add one or more widgets. You configure widgets to display the information and data you want, such as the following bug burndown widget. Along with dashboards, you have access to the [Analytics service](../../report/powerbi/what-is-analytics.md). This service is optimized for fast read-access and server-based aggregations. By using [Analytics views](../../report/powerbi/what-are-analytics-views.md) and [Power BI](../../report/powerbi/what-are-analytics-views.md), you can create highly sophisticated reports on the project data of interest.          |
|Integrate with Office  | Project managers who want to use familiar tools can import and export work item queries to and from Microsoft Office Excel or import and export work items using .csv files. For more information, see [Bulk import or update work items using CSV files](../queries/import-work-items-from-csv.md) or [Bulk add or modify work items with Excel](../backlogs/office/bulk-add-modify-work-items-excel.md)|
|Extend functionality    |  You can gain even greater functionality by adding Marketplace extensions, many of which are free. An extension is an installable unit that adds capabilities to Visual Studio, Azure DevOps Services, or Visual Studio Code. You can find extensions within these products or in the [Visual Studio Marketplace](https://marketplace.visualstudio.com/azuredevops), Azure DevOps tab. Also, by using the [REST API](/rest/api/azure/devops/index), you can create your own extensions or tools to integrate with Azure DevOps Services.|
|Get updates via a mobile browser   |  It's easy to stay on top of changes as they occur, using the [mobile browser](../../project/navigation/mobile-work.md), you can be notified and respond to changes made to work items.   |
|Start for free |You can start for free and add up to five free users and unlimited [stakeholders](../../organizations/security/get-started-stakeholder.md).  |

For more information, see our Training module, [What is Azure Boards?](/training/modules/choose-an-agile-approach/3-what-is-azure-boards)

## Related articles

- [Best tool to add, update, and link work items](../work-items/best-tool-add-update-link-work-items.md)
- [Configure and customize Azure Boards](../configure-customize.md)
- [The DevOps journey at Microsoft](https://azure.microsoft.com/solutions/devops/devops-at-microsoft/)
- [Agile culture](../plans/agile-culture.md)  
- [Practices that scale](../plans/practices-that-scale.md)  
- [About teams and Agile tools](../../organizations/settings/about-teams-and-settings.md)
