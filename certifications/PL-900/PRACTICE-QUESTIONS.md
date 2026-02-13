# PL-900 Practice Questions - Part 1

This document contains **64 essential practice questions** (Questions 1-64) for the PL-900 certification, organized in numerical order. These questions cover the most important topics likely to appear on the exam.

**Total Questions in Part 1**: 64 (Questions 1-64)  
**Part 2 Available**: [Questions 65-128](./PRACTICE-QUESTIONS-2.md)  
**Total Questions Combined**: 128 questions across both parts

## 📚 Source

**Video Course**: Microsoft Certified: Power Platform Fundamentals (PL-900) Exam Practice Questions  
**Additional Resources**: [Official Practice Assessment](https://learn.microsoft.com/es-es/credentials/certifications/power-platform-fundamentals/?practice-assessment-type=certification)

> **Note**: These are practice questions for study purposes. Always refer to official Microsoft Learn resources for the most current exam content.

---

## 📝 How to Use This Document

1. **Study First**: Complete the Microsoft Learn Path before attempting these questions
2. **Practice**: Answer questions without looking at answers first
3. **Review**: Understand why each answer is correct
4. **Identify Weak Areas**: Focus additional study on topics where you struggle
5. **Take Official Assessment**: Use the official Microsoft practice assessment for final preparation

---

## 🎯 Practice Questions (1-64)

### Question 1: Power BI Components
**Scenario**: A company plans to create an information portal that managers can use to view critical information about their teams. You need to recommend the type of Power BI components that the company should use.

**Requirements**:
- Display data from a Microsoft Excel workbook that has multiple worksheets into one chart
- Display the top departmental goal metrics and alert users which specific threshold targets are met
- Display sales charts that can be filtered by region

**Answer**:
- **Report** - For displaying data from Excel workbook with multiple worksheets
- **Dashboard** - For displaying top departmental goal metrics with alerts
- **Report** - For displaying sales charts with filtering capabilities

**Key Concept**: Dashboards are for high-level metrics and alerts. Reports are for detailed data visualization with filtering.

---

### Question 2: Sharing Power BI Reports
**Scenario**: You are a sales representative. You create a Power BI report to visualize data from a Microsoft Excel workbook. Users need to be able to view and share the report. Which two actions should you perform?

**Options**:
- A. Pin the report to a dashboard
- B. Export the data
- C. Publish the dashboard
- D. Share the dashboard

**Answer**: **A and D**
- Pin the report to a dashboard
- Share the dashboard

**Key Concept**: To share reports, you need to pin them to a dashboard and then share the dashboard.

---

### Question 3: Model-driven vs Canvas Apps
**Scenario**: A developer is comparing the Power Apps model-driven approach and canvas approach. Which choices are benefits of a model-driven Power App approach? (Choose three)

**Options**:
- A. The user interface is consistent for both desktop and mobile users
- B. The no-code layout is consistent across all apps in the organization
- C. The apps rendering will automatically respond to the user's device
- D. Supports extensive UI design flexibility and customization

**Answer**: **A, B, and C**

**Key Concept**: Model-driven apps provide consistent UI across devices and organizations, with automatic responsive rendering. Canvas apps offer more UI flexibility.

---

### Question 4: Filtering in Power BI
**Scenario**: You need to display sales orders greater than a specific threshold in a Power BI report. What should you use?

**Options**:
- A. Filter
- B. Power Query
- C. Common Data Service
- D. Connector

**Answer**: **A. Filter**

**Key Concept**: Filters are used to display data that meets specific criteria in Power BI reports.

---

### Question 5: Administrator Analytics
**Scenario**: A system administrator would like to view analytic reports that show relationships between the number of times an app has been used and how many times that same app has been shared. Which administrator analytic report should the administrator use?

**Options**:
- A. A usage report
- B. A location report
- C. A service performance report
- D. A connectors report

**Answer**: **D. A connectors report**

**Key Concept**: A connectors report displays individual connectors and relevant data within Power Apps, and also shows data like how many times apps have been shared and accessed.

---

### Question 6: Canvas Apps in Teams
**Scenario**: A company plans to build Canvas apps that will be used within Microsoft Teams. You need to identify the platform based on the design considerations.

**Requirements**:
- Limit the number of rows to less than 1 million that can exist for an application in Teams
- Ensure that professional developers have as many features available as possible such as API access, plugins and more when developing applications for use within Teams

**Answer**:
- **Dataverse for Teams** - For limiting rows to less than 1 million
- **Dataverse** - For professional developers with API access and plugins

**Key Concept**: Dataverse for Teams has a 2GB capacity limit. Dataverse provides full features for professional developers.

---

### Question 7: Dataverse Modeling
**Scenario**: You're implementing a solution for an animal hospital. The animal hospital must contact owners regarding their pets. You need to model the owner and pet object information by using Microsoft Dataverse. The solution must minimize the amount of customization required.

**Data**: Owner's first name, owner's last name, owner's email address, owner's date birth, pet name, pet breed, pet owner

**Answer**:
- Owner object: **Standard Dataverse table**
- Pet object: **Custom Dataverse table**
- Owner's email address: **Column**
- Reference a pet record as belonging to an owner record: **Relationship**

**Key Concept**: Use standard tables when possible, custom tables for specific business needs, columns for attributes, and relationships to link entities.

---

### Question 8: Power BI Dashboard
**Scenario**: A data administrator wants to use Power BI to help managers quickly grasp key metrics in a single platform. What would a data administrator want to create to monitor at a glance some of the more important data visualizations?

**Options**:
- A. Workspace
- B. Database
- C. Data flow
- D. Dashboard

**Answer**: **D. Dashboard**

**Key Concept**: Dashboards are where buttons and flows can be pinned, allowing managers to quickly be updated on important information.

---

### Question 9: AI Builder Models
**Scenario**: A company is evaluating AI Builder. Which statements are true about AI Builder models? (Choose all that apply)

**Options**:
- A. AI Builder models are pre-trained and ready to interpret business data immediately
- B. Pre-built AI Builder models exist for both Power Automate and Power Apps

**Answer**: **Both statements are true**

**Key Concept**: AI Builder provides pre-trained models that are ready to use immediately, and these models are available for both Power Automate and Power Apps.

---

### Question 10: UI Controls for Text Display
**Scenario**: A data administrator wants to efficiently pull data for Power Apps. The admin's primary concern is that the user interface displays text in a particular way. Which UI control should be selected to display text from a single row of connected data?

**Options**:
- A. Form
- B. Gallery
- C. Data card
- D. Label

**Answer**: **A. Form**

**Key Concept**: Forms are powerful controls that, once connected to a data source, allow users to fill out data to be sent to the data source and display data from a single row.

---

### Question 11: Custom Connectors
**Scenario**: A coworker is creating an app in Power Apps and needs to automatically synchronize data from an external source. The coworker is unable to locate a suitable Microsoft-approved connector template in AppSource. What should you recommend?

**Options**:
- A. Create a custom connector
- B. Ask the outside source to send you the data once a week
- C. Use Power Automate to connect to the database
- D. Open a ticket with Microsoft and request a new connector
- E. Use Microsoft Azure Service Bus

**Answer**: **A. Create a custom connector**

**Key Concept**: If you don't find a suitable connector in the 250+ predefined connectors, you can create a custom connector. A custom connector is a wrapper around a REST API.

---

### Question 12: Power BI Slicers
**Scenario**: In Power BI, which component is ideal for displaying frequently used or important filters on the report canvas for quicker access?

**Options**:
- A. Q&A visuals
- B. Slicers
- C. Top N analysis
- D. Statistical summaries

**Answer**: **B. Slicers**

**Key Concept**: Slicers are ideal for displaying frequently used filters on the report canvas for quicker access and eliminate the need to open a drop-down list.

---

### Question 13: Data Visualization Methods
**Scenario**: A data analyst wants to use Power BI's data visualization features to discover relationships between different quarterly targets. Which method should be used to check whether one measure meets a target defined by another measure?

**Options**:
- A. Combo chart
- B. Decomposition tree
- C. Funnel chart
- D. Gauge chart

**Answer**: **A. Combo chart**

**Key Concept**: A combo chart combines a column chart and a line chart, allowing quick comparison of data and checking if one measure meets a target.

---

### Question 14: Sharing Chatbots
**Scenario**: You create a Power Virtual Agents chatbot. You need to share the bot with other team members so they can try out the bot before you share the bot with customers. What should you use?

**Options**:
- A. Demo website
- B. Live production website
- C. Test chat feature

**Answer**: **A. Demo website**

**Key Concept**: Demo website allows team members to try out the bot before sharing it with customers.

---

### Question 15: Flow Actions Order
**Scenario**: A developer is trying to build a Power Automate flow, but it's currently broken. The developer has placed actions that pull data from Dropbox before an action that emails team members the Dropbox data. What step does the developer need to complete to make the flow functional?

**Options**:
- A. Move the action that uses Dropbox outputs after the email action
- B. Create a new flow
- C. Trigger the flow from a different point
- D. Place the action that uses Dropbox outputs before the email action

**Answer**: **D. Place the action that uses Dropbox outputs before the email action**

**Key Concept**: Any action that interprets an output from a data source needs to come after the source has actually sent out the data. Actions must be in the correct order.

---

### Question 16: Dataverse for Data Linking
**Scenario**: You are a sales manager for a large retail organization. You are creating a Power Apps app that will display customer product purchase information from your old point of sale system and need to link those sales to the customer accounts and product sales in Dynamics 365 Commerce. What should you use?

**Options**:
- A. Microsoft Dataverse
- B. Business process flow
- C. Entity metadata
- D. Business role

**Answer**: **A. Microsoft Dataverse**

**Key Concept**: Microsoft Dataverse (formerly Common Data Service) is used to link and integrate data from different sources.

---

### Question 17: AppSource Testing
**Scenario**: A developer is exploring available Power Apps in the AppSource library and has identified a few different marketing apps that may be useful. The developer wants to be able to test them with users on his team. Which AppSource app listing action allows for a testing simulation with real users and data?

**Options**:
- A. Free trial
- B. Test drive
- C. Get it now
- D. Contact me

**Answer**: **A. Free trial**

**Key Concept**: Free trial allows testing with real users and data. Test drive is limited to a curated experience and doesn't allow real user participation.

---

### Question 18: Custom Site Map
**Scenario**: You want to create a Power Apps app that allows you to define a custom site map. What should you do?

**Answer**: Navigate to the Power Apps portal and create a **model-driven app**.

**Key Concept**: Model-driven apps allow you to define custom site maps for navigation.

---

### Question 19: Model-driven App Objects
**Scenario**: A developer is creating a model-driven app but is unclear on which objects are most relevant to his connected data. Which object should the developer create to only show the data connected to the form?

**Options**:
- A. Main form
- B. Charts
- C. Workflows
- D. Views

**Answer**: **A. Main form**

**Key Concept**: Only the main form shows connected data. Charts, workflows, and views offer other ways to view and interpret connected data.

---

### Question 20: Video Streaming in Power Apps
**Scenario**: You are a retail director for a large clothing company. Each week you use the corporate YouTube channel to create a video that highlights new initiatives and goals for retail operations. You need to design a Power Apps app that streams the video to internal users. Which objects should you use?

**Answer**:
- Implement the Power Apps app: **Model-driven**
- Use drag and drop to add a video to the app: **Control**
- Apply consistent company colors to the app: **Theme**

**Key Concept**: Model-driven apps use controls for media, and themes for consistent styling.

---

### Question 21: Tool Matching
**Scenario**: Match each tool to its task.

**Tasks and Answers**:
- Automate workflows: **Power Automate**
- Trigger an action from an event: **Power Automate**
- Create a custom mobile data entry screen: **Power Apps**

**Key Concept**: Power Automate is for automation and workflows. Power Apps is for creating custom applications.

---

### Question 22: Power Automate Audit Logs
**Scenario**: A Power Platform administrator is reviewing various administrative tasks and often confuses the admin centers when trying to track down specific tasks. Which portal should the administrator access to view Power Automate audit logs?

**Options**:
- A. Security and Compliance Center
- B. Microsoft 365 Admin Center
- C. Power Platform Admin Center
- D. Microsoft Power Pages (formerly Power Apps Portal)

**Answer**: **A. Security and Compliance Center**

**Key Concept**: The Security and Compliance Center is where Power Automate audit logs can be found. Power Platform Admin Center enables environment management and viewing Power Apps and Power Automate admin analytics.

---

### Question 23: AI Builder Text Classification
**Scenario**: A business is evaluating AI Builder. Which actions can you perform? (Select yes if the statement is true, otherwise select no)

**Statements**:
- You can use the text classification model in AI Builder to retrieve text and perform sentiment analytics for ServiceNow incidents: **Yes**
- You can tag Instagram posts that mention your new product: **Yes**
- You can send results about the number of mentions of your new product in Instagram to Power BI for inclusion on a dashboard: **Yes**

**Key Concept**: AI Builder text classification can be used for sentiment analysis and can integrate with Power BI.

---

### Question 24: Publishing Chatbots
**Scenario**: A developer wants to publish all of her new Power Virtual Agents chatbots at once, but remembers there are limitations when publishing bots in new environments. How long after creating the first chatbot in a new environment can the developer create subsequent bots?

**Options**:
- A. Up to 15 minutes
- B. Up to an hour
- C. Up to 24 hours
- D. Immediately

**Answer**: **A. Up to 15 minutes**

**Key Concept**: The developer only needs to wait 15 minutes after publishing the first chatbot before publishing others.

---

### Question 25: Business Rules and Process Flows
**Scenario**: A travel company plans to use the Power Platform to create tools that help travel agents book customer travel. You need to recommend solutions for the company.

**Requirements and Answers**:
- If a customer is traveling with a person under the age of 18, a field must display to collect date of birth for the under 18 traveler only: **Business rule**
- Ensure that all travel agents use the same process with all customers: **Business process flow**
- Send a confirmation email to customer after reservations are complete: **Power Automate**

**Key Concept**: Business rules validate data and show/hide fields. Business process flows guide users through consistent processes. Power Automate handles automated communications.

---

### Question 26: Desktop Flow Loops
**Scenario**: A developer is building multiple desktop flows with Power Automate and many flows involve repeating large sets of tasks. Which loop action should the developer use to repeatedly iterate a block of actions?

**Options**:
- A. Exit loop
- B. Loop condition
- C. Next loop
- D. For each

**Answer**: **D. For each**

**Key Concept**: For each loop action iterates over items in a list, data table, or data row, allowing a block of actions to be executed repeatedly.

---

### Question 27: AI Builder Model Types
**Scenario**: A manufacturing company is evaluating AI Builder. You need to select AI Builder models to address specified requirements.

**Requirements and Answers**:
- Identify products without labels or serial numbers: **Object detection**
- Identify customers who might not pay their invoices on time: **Prediction**

**Key Concept**: Object detection identifies objects in images. Prediction models predict outcomes based on historical data.

---

### Question 28: Event-based Triggers
**Scenario**: When a developer designing triggers in Power Automate wants to deploy an event-based trigger, which trigger type should the developer use?

**Options**:
- A. A trigger for automated flows
- B. A trigger for instant flows
- C. A trigger for manual flows
- D. A trigger for scheduled flows

**Answer**: **A. A trigger for automated flows**

**Key Concept**: A trigger for automated flows starts a cloud flow that performs one or more tasks automatically after an event triggers it. For example, create a cloud flow that notifies you by email when someone sends a tweet that contains a keyword you specify.

---

### Question 29: Dataverse Features
**Scenario**: A company plans to implement solutions that use Microsoft Dataverse. You need to recommend features to meet the company's needs.

**Requirements and Answers**:
- Validate data across multiple fields and entity regardless of the app used to create data: **Business rules**
- Create visual guides to ensure that users enter data and perform tasks in a consistent manner: **Business process flows**
- Accelerate development by using a standard set of entities for the most common scenarios: **Common data model**

**Key Concept**: Business rules validate data. Business process flows guide users. Common data model provides standard entities.

---

### Question 30: Conversation Nodes
**Scenario**: A developer is building conversation topics of Power Virtual Agents bots and needs to identify opportunities in each conversation to obtain more detail using conditions. Which conversation node allows the developer to add a condition?

**Options**:
- A. Ask a question
- B. Call an action
- C. Show a message
- D. Go to another topic

**Answer**: **A. Ask a question**

**Key Concept**: When you add a node after the trigger phrase node or between message nodes, you can ask a question, call an action, show a message, or go to another topic. Asking a question allows you to add conditions.

---

### Question 31: AI Builder Implementation Steps
**Scenario**: A bank uses Power Platform apps and flows to support business processes. The company would like to use historical client data to predict whether a client's loan application is likely to be approved or rejected. You need to use AI Builder to implement the solution. Which actions should you perform in sequence?

**Answer** (in order):
1. Import data into Common Data Service
2. Export data into AI Builder
3. Train the model
4. Publish the model
5. Use the model in Power Apps or Power Automate

**Key Concept**: AI Builder workflow: Import data → Export to AI Builder → Train → Publish → Use in apps/flows.

---

### Question 32: Power BI Report View
**Scenario**: A data engineer is new to building Power BI sites and not familiar with the limitations of report view, but wants to learn before publishing the site. Which of the following tasks can the data engineer perform in report view without publishing the Power BI site? (Choose three)

**Options**:
- A. Copy and paste visuals between reports
- B. Hide report pages
- C. Change report visualization options
- D. Pin reports and visualizations to a dashboard

**Answer**: **A, B, and C**

**Key Concept**: You cannot pin reports or anything else to a dashboard without publishing. Once the site is published, all of these report view options are available.

---

### Question 33: Power Apps Accessibility
**Scenario**: You are creating a Power Apps app. You want to ensure that the app can be used by individuals who have a vision impairment. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- Power Apps can use a screen reader without the need for a connector: **Yes**
- You can use an accessibility checker for Power Apps apps to check for accessibility violations and provide user interface tips: **Yes**

**Key Concept**: Power Apps supports accessibility features including screen readers and accessibility checkers.

---

### Question 34: Canvas Apps
**Scenario**: In Microsoft Power Apps, which type of application should you use when you want simple drag and drop functionality and the freedom to make your app look exactly how you want it to?

**Options**:
- A. Template
- B. Portals
- C. Canvas
- D. Model-driven

**Answer**: **C. Canvas**

**Key Concept**: Use Canvas apps when you want simple drag and drop functionality and the freedom to make your app look exactly how you want.

---

### Question 35: Microsoft 365 and Dynamics 365 Integration
**Scenario**: What is the benefit of deploying Microsoft 365 and Dynamics 365 apps in the same tenant?

**Options**:
- A. Use Common Data Service to connect to application data
- B. You only need to set up groups in Microsoft 365 for permissions to all data
- C. Users can access both Microsoft 365 and Dynamics 365 by using single sign-on

**Answer**: **A. Use Common Data Service to connect to application data**

**Key Concept**: Deploying in the same tenant allows using Common Data Service to connect application data.

---

### Question 36: Power BI Aggregates
**Scenario**: A data administrator is working with aggregates to combine values in reports in Power BI but can't figure out why only the count function option is available. What is the most likely reason?

**Options**:
- A. The field is actually a measure
- B. The dataset owner has not classified the field as a number
- C. The field has been dropped into a categorical bucket
- D. The field is being used as an axis

**Answer**: **B. The dataset owner has not classified the field as a number**

**Key Concept**: The field that you want to measure must be classified as a number to perform other operations outside of count.

---

### Question 37: Data Synchronization
**Scenario**: A company uses Dynamics 365 Supply Chain Management and Dynamics 365 Finance. User account data must be synchronized between the two systems. You need to ensure that the synchronized data is stored in one place. What should you use?

**Options**:
- A. Azure IoT Central
- B. Azure Active Directory
- C. SQL Server
- D. Microsoft Dataverse

**Answer**: **D. Microsoft Dataverse**

**Key Concept**: Microsoft Dataverse can store synchronized data from multiple systems in one place.

---

### Question 38: Power BI Analysis Tools
**Scenario**: A data analyst wants to use Power BI's analysis tools to help explain fluctuations in sales data between two quarters of the last financial year. Which details should the analyst review to see actual changes in unit sales between the two quarters?

**Options**:
- A. A 100% stacked column chart
- B. A scatter plot
- C. A waterfall chart
- D. A ribbon chart

**Answer**: **C. A waterfall chart**

**Key Concept**: A waterfall chart highlights each unit and shows their actual changes across the period of time whether increased or decreased.

---

### Question 39: Workflow Applications
**Scenario**: A company needs to create several workflows and applications to help streamline their sales operations. You need to determine which applications are appropriate for given scenarios.

**Scenarios and Answers**:
- Create no-code workflows that use different systems: **Power Automate**
- Build no-code mobile applications: **Power Apps**
- Build a mobile application by using Microsoft Dataverse: **Power Apps**

**Key Concept**: Power Automate for workflows. Power Apps for mobile applications, including those using Dataverse.

---

### Question 40: Security Groups
**Scenario**: A security administrator is creating Power Apps security groups for the team and wants to ensure everyone has the permissions required for their roles without making any compromises. Which of the following is true about security groups within Power Apps?

**Options**:
- A. Individual users can be assigned greater permissions than the group itself
- B. All users must have the same permission level
- C. Permissions in Power Apps carry over to Power BI
- D. Power App security groups cannot share apps

**Answer**: **A. Individual users can be assigned greater permissions than the group itself**

**Key Concept**: Putting someone in a security group in Power Apps doesn't restrict their permissions to what's defined by the group.

---

### Question 41: Power Platform Benefits
**Scenario**: A company uses Microsoft 365 and Dynamics 365 Sales. The company does not have any developers on its staff. You need to explain to the executives the benefits of using Power Platform apps. What are two benefits?

**Options**:
- A. Users can send emails from Dynamics 365 Sales to their personal email addresses
- B. Users can create Power Apps to create apps for different departments
- C. Users can use Power Automate to share information between Microsoft 365 and Dynamics 365 Sales
- D. The company can unify all the mobile devices to one vendor

**Answer**: **B and C**

**Key Concept**: Power Platform enables citizen developers to create apps and automate processes without coding expertise.

---

### Question 42: Power BI Desktop vs Service
**Scenario**: A developer is learning how to design a workflow using Power BI Desktop and Power BI Service but is trying to complete tasks that one of the two services cannot support. Which of the following tasks can be executed in both services?

**Options**:
- A. Generating visualizations
- B. Generating paginated reports
- C. Creating modeling data
- D. Creating apps and workspaces

**Answer**: **A. Generating visualizations**

**Key Concept**: Generating visualizations is the only task possible in both services. Paginated reports and apps/workspaces are created in Power BI Service. Modeling data can be generated in Power BI Desktop.

---

### Question 43: AI Builder Models
**Scenario**: A company plans to use AI Builder to help improve business performance. You need to determine which AI models are available for use. Which three types of models can you use?

**Options**:
- A. Linear regression
- B. Prediction
- C. Object detection
- D. Anomaly detection
- E. Text classification

**Answer**: **B, C, and E** (Prediction, Object detection, Text classification)

**Key Concept**: AI Builder provides prediction, object detection, and text classification models among others.

---

### Question 44: Power Automate for Power BI Refresh
**Scenario**: By utilizing which tool can you trigger Power BI data source refreshes based on source data changes and update the dataset using Power BI's API interface?

**Options**:
- A. Power BI Desktop
- B. Power BI.com
- C. ArcGIS
- D. Microsoft Power Automate (Flow)

**Answer**: **D. Microsoft Power Automate (Flow)**

**Key Concept**: By utilizing Power Automate, you can trigger refreshes based on source data changes and update the dataset using Power BI's API interface.

---

### Question 45: Dataverse Requirements
**Scenario**: A company is evaluating Power Platform and has questions about the role that Microsoft Dataverse plays in using Power Apps and Power Automate. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- Model-driven apps require a Microsoft Dataverse database: **Yes**
- A flow instance can only access one Microsoft Dataverse database: **No**
- Canvas apps require a Microsoft Dataverse database: **No**

**Key Concept**: Model-driven apps require Dataverse. Canvas apps do not require Dataverse. Flows can access multiple Dataverse databases.

---

### Question 46: Instant Flows
**Scenario**: A data engineer is building different Power Automate flows and wants to give team members plenty of options, but the team requested a flow that can run with a simple click. Which Power Automate flow type should the data engineer use to allow users to send automated messages with a mouse click?

**Options**:
- A. Business process
- B. Instant
- C. Desktop
- D. Scheduled

**Answer**: **B. Instant**

**Key Concept**: The instant flow is the click-and-go flow. Instant flows allow you to accomplish tasks simply by tapping a button on your mobile device.

---

### Question 47: AI Builder Scenarios
**Scenario**: A company is evaluating ways that they can implement AI Builder. For which two scenarios can you use AI Builder?

**Options**:
- A. Send emails to all users who subscribe to a service
- B. Synchronize data from an external database
- C. Collect data from several data services and deploy a dashboard that shows trending data
- D. Interpret images and perform an action based on the image
- E. Detect patterns in data and predict outcomes

**Answer**: **D and E**

**Key Concept**: AI Builder can interpret images and perform actions, and detect patterns in data to predict outcomes.

---

### Question 48: Dual Write Events
**Scenario**: A data engineer has deployed a Finance and Operations environment and successfully integrated Microsoft Power Platform. He knows many ways to get his Power Platform apps to talk to the Finance and Operations apps and retrieve account information. Which event type should the data engineer configure if the engineer wants local app data to be stored while overlapping data is kept in sync?

**Options**:
- A. Dual write event
- B. Data event
- C. Virtual entities
- D. Business event

**Answer**: **A. Dual write event**

**Key Concept**: The dual write event is the only one that copies data between apps, keeping data in sync.

---

### Question 49: Power BI Data Display
**Scenario**: A company plans to use Power BI to visualize data from business systems. For each of the following statements, select yes if the statement is true, otherwise select no.

**Statements**:
- You can display data aggregates and raw data in a Power BI report: **Yes**
- You can display related data from multiple sources in the same Power BI report: **Yes**

**Key Concept**: Power BI can display both aggregated and raw data, and can combine data from multiple sources in a single report.

---

### Question 50: Accessibility Checker
**Scenario**: A systems administrator would like to use the Power Apps accessibility app checker to ensure her canvas apps are truly accessible. The administrator wants to use the checker to eliminate any potential problems. Which of the following can be checked in the accessibility app checker in Power Apps? (Choose three)

**Options**:
- A. Errors
- B. Warnings
- C. Tips
- D. Logs

**Answer**: **A, B, and C** (Errors, Warnings, Tips)

**Key Concept**: The accessibility checker classifies each issue as an error, a warning, or a tip based on the issue's severity.

---

### Question 51: Power Platform Applications
**Scenario**: A company uses Dynamics 365 Sales. You have the following requirements:
- View analytics on accounts
- The model-driven app must automatically send an approval form to a manager when the purchase price is greater than 10,000
- Create a chatbot for the web page to interact with customers' questions

You must use Microsoft Power Platform to extend the capabilities of Dynamics 365 Sales. Which application should you use for each requirement?

**Answer**:
- View analytics on accounts: **Power BI**
- Automatically send approvals: **Power Automate**
- Create chatbot for web pages: **Power Virtual Agents**

**Key Concept**: Power BI for analytics, Power Automate for approvals, Power Virtual Agents for chatbots.

---

### Question 52: Environment Provisioning
**Scenario**: A user needs to create and provision new production environments as a Power Platform administrator but only holds a Microsoft 365 plan license. Which plan allows users to provision a new production environment?

**Options**:
- A. Dynamics 365 plans
- B. Dynamics 365 team plans
- C. Dynamics 365 trials
- D. Power Apps developer plans

**Answer**: **A. Dynamics 365 plans**

**Key Concept**: A user needs a Dynamics 365 license to create new production environments. The other plans either support creation of a trial environment or do not support environment creation.

---

### Question 53: Security Roles
**Scenario**: A company creates the following Microsoft Power Platform environments to manage a custom model-driven app development: production. You have been granted the system administrator security role to the development environment and a custom security role named project team member to the production environment. For each of the following statements, select yes if the statement is true, otherwise select no.

**Statements**:
- You will not be able to access the app until the system administrator security role is assigned to the app in the development environment: **No**
- You can delete records in the development environment: **Yes**
- You will not be able to access the app until the project team member security role is assigned to the app in the production environment: **No**

**Key Concept**: System administrator role has full access. Security roles must be assigned to access apps in specific environments.

---

### Question 54: Personal Views
**Scenario**: An administrator needs to be able to find personal views within the edit user interface. Which of the following statements is true about model-driven apps?

**Options**:
- A. Personal views cannot be recreated
- B. System and public views cannot be based on personal views
- C. Personal views are found above the system and public views
- D. Public views are not customizable

**Answer**: **C. Personal views are found above the system and public views**

**Key Concept**: Personal views are owned by individuals and only visible to that person unless they share their personal views with others.

---

### Question 55: Separate Environments
**Scenario**: A company currently does not separate testing, development, and production as per standard application lifecycle management protocol. The company uses Power Apps for accounting and sales processes. The company needs to use only one login account per user. The company also must prevent development and testing from impacting production. You need to implement a solution to meet the requirements. Which method should you select?

**Options**:
- A. Separate environments
- B. Separate tenants
- C. Separate Microsoft Azure storage blobs
- D. Separate connectors

**Answer**: **A. Separate environments**

**Key Concept**: To follow application lifecycle management principles, you will need separate environments for app development and production.

---

### Question 56: Third Party Apps
**Scenario**: A system architect plans to deploy certain Power Apps apps to different user groups in his organization and wants to organize the update channels based on what is best for each end user. Which two are examples of Power Apps consuming data from a third party app? (Choose two)

**Options**:
- A. An employee built app pulling data from Twitter
- B. An employee built app exporting business data to Google Analytics
- C. An employee built app syncing data with Dataverse
- D. An employee built app exporting data from a Power Automate app

**Answer**: **A and B**

**Key Concept**: Twitter and Google Analytics are third-party apps. Dataverse and Power Automate are part of Microsoft Power Platform, not third-party apps.

---

### Question 57: On-Premises Data Gateway
**Scenario**: A company is creating a canvas app to track and analyze customers' visits to their retail stores. Data about customers' visits is stored on-premises at each retail store location. The app must display data about customer visits when users launch the app. You need to ensure that the data is available for consumption by the app. Which tool should you use?

**Options**:
- A. Connector
- B. Microsoft Dataverse
- C. Data source
- D. Power Automate
- E. Data gateway

**Answer**: **E. Data gateway**

**Key Concept**: A data gateway is a tool that allows you to connect to on-premises data sources such as the customer visit data stored at each retail store location.

---

### Question 58: Azure Cognitive Services
**Scenario**: A developer is experimenting with Microsoft Power Apps and Azure Cognitive Services to design a better client experience. The developer would like to build an app to simplify the company services. Which Azure Cognitive Service uses natural language understanding to help users more fluidly interact with apps?

**Options**:
- A. Cognitive Service for Decision
- B. Cognitive Service for Vision
- C. Cognitive Service for Language
- D. Cognitive Service for Speech

**Answer**: **C. Cognitive Service for Language**

**Key Concept**: Cognitive Service for Language uses NLU (Natural Language Understanding) to help develop a more conversational tone.

---

### Question 59: Managed Solutions
**Scenario**: For each of the following statements, select yes if the statement is true, otherwise select no.

**Statements**:
- Managed solutions can be used to group multiple Power Platform components together during solution development: **Yes**
- Managed solutions must be used to distribute a Power Platform application on AppSource: **No**
- Managed solutions always protect Power Platform components from editing when components are exported to another environment: **Yes**

**Key Concept**: Managed solutions are used to deploy to any environment that isn't a development environment. You can't edit components directly within a managed solution.

---

### Question 60: Power Apps Portals
**Scenario**: In Microsoft Power Apps, which type of application allows for creation of external-facing websites without needing to understand coding?

**Options**:
- A. Template
- B. Portal
- C. Canvas
- D. Model-driven

**Answer**: **B. Portal**

**Key Concept**: Portals allow for creation of external-facing websites without needing to understand coding.

---

### Question 61: Security Policies
**Scenario**: A company uses Power Platform. You must ensure that users cannot share customers' data with other users. You must also ensure that users cannot connect to data sources unless you grant the user explicit permissions to access a data source. You need to recommend a solution to meet the company's security requirements. Which two types of policies should you recommend?

**Options**:
- A. Office cloud policies
- B. Group policy objects
- C. Environment level policies
- D. Tenant level policies
- E. Present security policies

**Answer**: **C and D** (Environment level policies and Tenant level policies)

**Key Concept**: Environment level and tenant level policies help control data sharing and data source access.

---

### Question 62: Secure Connectors
**Scenario**: A data security administrator is reviewing the different connectors he can use to make data connections in Power Apps. He needs to ensure the connectors he uses are secure and require a user to enter a username and password. Which of the following is the only secure connector that requires a username and password?

**Options**:
- A. Windows authentication
- B. SQL username and password authentication
- C. Azure AD integrated
- D. Open standard authorization

**Answer**: **D. Open standard authorization**

**Key Concept**: Open standard authorization is the only secure connector that requires a username and password. SQL username and password authentication requires a password but it's not secure.

---

### Question 63: Azure Cognitive Services Integration
**Scenario**: A company is evaluating ways to connect Power Platform apps to external services to perform complex activities. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- You can create a canvas app that scans and passes documents using Azure Cognitive Services and then adds the appropriate information to Dynamics 365 Sales: **Yes**
- You can create a canvas app that uses Azure Cognitive Services to read incident records and identify tickets that need to be escalated based on sentiment score: **Yes**

**Key Concept**: Power Apps can integrate with Azure Cognitive Services for document processing and sentiment analysis.

---

### Question 64: Field Technicians Access
**Scenario**: A company needs technicians in the field to access real-time diagnostic data from their smart devices. The company requires a flexible, customizable option for its team. Which Power Platform service would be best for making company data easier to access in the field?

**Options**:
- A. Power Automate
- B. Power BI
- C. Power Virtual Agents
- D. Power Apps

**Answer**: **D. Power Apps**

**Key Concept**: Power Apps is the best answer because it's the only option here that employees would use to create unique ways to access and organize company data depending on their needs.

---

## 📊 Exam Tips

### Question Types
- **Multiple Choice**: Select one correct answer
- **Multiple Answer**: Select all correct answers (usually 2-3)
- **Drag and Drop**: Match items to categories
- **Yes/No**: True/False statements

### Answering Strategy
1. **Read carefully**: Pay attention to keywords like "best", "most appropriate", "primary"
2. **Eliminate wrong answers**: Process of elimination helps
3. **Watch for "all that apply"**: Some questions require multiple answers
4. **Time management**: 45 minutes for ~40-45 questions (~1 minute per question)

### Common Topics
- Business value of Power Platform components
- Differences between Canvas and Model-driven Apps
- Power BI components (Dashboards vs Reports)
- Flow types (Automated, Instant, Scheduled)
- Environment administration and DLP policies
- Connectors and data sources
- Dataverse features and capabilities
- AI Builder models and use cases

---

## 🔗 Additional Practice Resources

### Official Resources
- [Microsoft Practice Assessment](https://learn.microsoft.com/es-es/credentials/certifications/power-platform-fundamentals/?practice-assessment-type=certification) ⭐
- [Official Study Guide](https://learn.microsoft.com/es-es/credentials/certifications/resources/study-guides/pl-900) ⭐
- [Exam Sandbox](https://aka.ms/examdemo) - Try the exam interface

### Study Materials
- [Microsoft Learn Path](https://learn.microsoft.com/training/powerplatform/power-platfundamentals)
- [Course Notes](./COURSE-NOTES.md) - Additional study materials

---

## ✅ Preparation Checklist

Before taking the exam:
- [ ] Completed Microsoft Learn Path
- [ ] Reviewed all 64 practice questions in Part 1
- [ ] Reviewed all 64 practice questions in [Part 2](./PRACTICE-QUESTIONS-2.md) (Questions 65-128)
- [ ] Understand why each answer is correct
- [ ] Taken official practice assessment (80%+)
- [ ] Reviewed weak areas
- [ ] Familiar with exam interface (sandbox)
- [ ] Ready for exam!

---

## 🔗 Continue to Part 2

**[📘 Part 2: Questions 65-128](./PRACTICE-QUESTIONS-2.md)** - Additional 64 practice questions covering advanced topics and scenarios.

---

**Remember**: Practice questions help you understand the exam format and identify weak areas. Always combine with official Microsoft Learn resources for comprehensive preparation.

**Last updated**: February 2025
