# PL-900 Practice Questions - Part 2

This document contains **64 additional practice questions** (Questions 65-128) for the PL-900 certification, continuing from [Part 1](./PRACTICE-QUESTIONS.md).

**Total Questions in Part 2**: 64 (Questions 65-128)  
**Total Questions Combined**: 128 questions across both parts

## 📚 Source

**Video Course**: Microsoft Certified: Power Platform Fundamentals (PL-900) Exam Practice Questions  
**Additional Resources**: [Official Practice Assessment](https://learn.microsoft.com/es-es/credentials/certifications/power-platform-fundamentals/?practice-assessment-type=certification)

> **Note**: These are practice questions for study purposes. Always refer to official Microsoft Learn resources for the most current exam content.

---

## 📝 How to Use This Document

1. **Complete Part 1 First**: Review [Part 1](./PRACTICE-QUESTIONS.md) (Questions 1-64) before starting Part 2
2. **Practice**: Answer questions without looking at answers first
3. **Review**: Understand why each answer is correct
4. **Identify Weak Areas**: Focus additional study on topics where you struggle
5. **Take Official Assessment**: Use the official Microsoft practice assessment for final preparation

---

## 🎯 Practice Questions (65-128)

### Question 65: Business Rules and Process Flows
**Scenario**: A travel company plans to use the Power Platform to create tools that help travel agents book customer travel. You need to recommend solutions for the company.

**Requirements and Answers**:
- If a customer is traveling with a person under the age of 18, a field must display to collect date of birth for the under 18 traveler only: **Business rule**
- Ensure that all travel agents use the same process with all customers: **Business process flow**
- Send a confirmation email to customer after reservations are complete: **Power Automate**

**Key Concept**: Business rules validate data and show/hide fields. Business process flows guide users through consistent processes. Power Automate handles automated communications.

---

### Question 66: Desktop Flow Loops
**Scenario**: A developer is building multiple desktop flows with Power Automate and many flows involve repeating large sets of tasks. Which loop action should the developer use to repeatedly iterate a block of actions?

**Options**:
- A. Exit loop
- B. Loop condition
- C. Next loop
- D. For each

**Answer**: **D. For each**

**Key Concept**: For each loop action iterates over items in a list, data table, or data row, allowing a block of actions to be executed repeatedly.

---

### Question 67: Power Apps Types for Business Challenges
**Scenario**: A company plans to use Power Platform to build apps which address specific business challenges. You need to recommend the appropriate types of Power Apps to use.

**Scenarios and Answers**:
- Field technicians need a mobile app to capture the location and the image of defective products: **Canvas app**
- Sales representatives need to see different views and dashboards in the sales app: **Model-driven app**

**Key Concept**: Canvas apps are ideal for mobile data capture with custom UI. Model-driven apps provide structured views and dashboards for business data.

---

### Question 68: Chatbot Single Sign-On
**Scenario**: A data administrator wants to configure end-user authentication for a chatbot created in the company's Teams. The chatbot should be able to silently sign the user in. Which authentication field must be provided to enable single sign-on (SSO)?

**Options**:
- A. Client secret
- B. Token exchange URL
- C. Token URL template
- D. Scope list delimiter

**Answer**: **B. Token exchange URL**

**Key Concept**: The token exchange URL is the only option that allows SSO to work. It allows the bot to intercept the login card request when attempting to log the user in.

---

### Question 69: Power Platform Tools for Business Tasks
**Scenario**: A rapidly growing company provides Office 365 licenses for all employees. The company wants to empower users to build apps, automate business processes, and analyze data without requiring expertise or development skills.

**Tasks and Answers**:
- Build automatic workflows that access multiple data sources: **Power Automate**
- Create custom apps that address specific business needs: **Power Apps**
- Design insightful data visualizations: **Power BI**

**Key Concept**: Power Platform provides low-code/no-code solutions for automation, app development, and data visualization.

---

### Question 70: Power Automate Data Operations
**Scenario**: A data engineer is configuring Power Automate data operations and wants to save strings of data for easy repetition while building a flow. Which data operation will best address this need?

**Options**:
- A. Data operation compose action
- B. Data operation join action
- C. Data operation select action
- D. Data operation filter array action

**Answer**: **A. Data operation compose action**

**Key Concept**: The compose action allows you to save and reuse data values throughout your flow.

---

### Question 71: Admin Centers for Power Apps
**Scenario**: A company uses Power Apps. You need to perform administrative tasks for the company. Which admin center should you use?

**Requirements and Answers**:
- To create user accounts for Power Apps: **Azure Active Directory**
- To assign the environment maker role to a user: **Power Apps admin center**

**Key Concept**: User accounts are created in Azure AD, while Power Apps-specific roles are managed in the Power Apps admin center.

---

### Question 72: Power BI App Release Stages
**Scenario**: A team lead manages the release of a new app that the team built in Power BI and needs to review which promotion stages the app can go through before being released publicly. Which stage indicates the app is now available for testing publicly?

**Options**:
- A. Workspace
- B. Testing
- C. Pre-production
- D. Production

**Answer**: **C. Pre-production**

**Key Concept**: Workspace and testing stages are still internal. Pre-production is publicly available but not fully released.

---

### Question 73: Measuring Software Usage
**Scenario**: A large retail company implements Power Apps, Microsoft Flow, and the Common Data Service. The board of directors wants to measure the report usage of the software. You need to recommend a tool to determine software usage.

**Options**:
- A. Microsoft Intune
- B. Azure Stream Analytics
- C. Power Platform Analytics
- D. Dynamics 365 Product Insights

**Answer**: **C. Power Platform Analytics**

**Key Concept**: Power Platform Analytics usage report provides total app launches and daily active users across all apps in the environment.

---

### Question 74: Shareable Data Connections
**Scenario**: A data engineer is working with data sources but needs to share the configured connections across work devices. Which connections for a data source can be shared across devices or between users? (Choose three)

**Options**:
- A. Collections
- B. Tables
- C. SQL Server
- D. Dropbox

**Answer**: **B, C, and D** (Tables, SQL Server, Dropbox)

**Key Concept**: Collections cannot be shared by definition. Tables, SQL Server, and Dropbox connections can be shared.

---

### Question 75: Power Platform Components
**Scenario**: You need to implement Microsoft business applications along with the Microsoft Power Platform. Which three Microsoft products are part of the Power Platform?

**Options**:
- A. Power Apps
- B. Azure Active Directory
- C. Power Automate
- D. Azure Machine Learning
- E. Power BI

**Answer**: **A, C, and E** (Power Apps, Power Automate, Power BI)

**Key Concept**: Power Platform uses Power Apps, Power BI, and Power Automate to customize, extend, and build apps for your business.

---

### Question 76: Approval Types - Single Person Review
**Scenario**: A security administrator uses Power Automate to build out approval types, allowing security team members to quickly approve timesheets and leave requests. If the security team wants to require only a single person's review to grant a leave request, which approval type is most efficient?

**Options**:
- A. Approve or reject, first to respond
- B. Approve or reject, everyone must approve
- C. Custom responses, wait for all responses
- D. Custom responses, wait for one response

**Answer**: **A. Approve or reject, first to respond**

**Key Concept**: With the "approve or reject, first to respond" approval type, assigned approvers are given two options (approve or reject). Approval or rejection by any approver completes the request.

---

### Question 77: Dataverse Entity Ownership
**Scenario**: You create a user-owned custom entity by using Common Data Service. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- You can change the entity ownership from user to organization owned: **No**
- You can create a business rule for a custom entity that can be used in a flow: **Yes**

**Key Concept**: Common Data Service supports two types of record ownerships: Organization owned and user or team owned. This choice happens at the time the entity is created and can't be changed.

---

### Question 78: Automated Messages in Model-driven Apps
**Scenario**: A developer is building a model-driven app but wants it to be focused on delivering automated messages to users. What logic component should the developer configure to ensure users can receive notifications about changes?

**Options**:
- A. Flows
- B. Business rules
- C. Actions
- D. Workflows

**Answer**: **A. Flows**

**Key Concept**: Power Automate (flows) is a cloud-based service that lets you create automated workflows between apps and services to get notifications, sync files, collect data, and more.

---

### Question 79: Dynamics 365 Mobile Access
**Scenario**: A company uses Dynamics 365 Sales. The company uses a browser-based app named Sales Hub. You need to ensure that users can access data from mobile devices. Which app should users install?

**Options**:
- A. Dynamics 365 Remote Assist
- B. Dynamics 365 Finance
- C. Dynamics 365 Business Central
- D. Dynamics 365 for phones

**Answer**: **D. Dynamics 365 for phones**

**Key Concept**: Use Dynamics 365 for phones and Dynamics 365 for tablets apps for sales, customer service, field service, and other tasks when you are on the go.

---

### Question 80: Scheduled Flows
**Scenario**: An administrator notices that weekly reports, monthly summaries, and other recurring messages and emails are frequently late. The admin team is understaffed as the company rapidly expands and needs an efficient way to manage these processes. Which flow is ideal to efficiently automate these tasks that occur within a set period of time?

**Options**:
- A. Branching flow
- B. Scheduled flow
- C. Instant flow
- D. Automated flow

**Answer**: **B. Scheduled flow**

**Key Concept**: A scheduled flow performs one or more tasks such as sending a reporting email once a day, an hour, or a minute on a day that you specify.

---

### Question 81: Power Apps Version Restoration
**Scenario**: You have a Power Apps app. You create a new version of the app and then publish the new version. A customer goes through the process of restoring the previous version of the app. In the version tab for the app, you will see two versions of the app.

**Options**:
- A. No change is needed
- B. 1
- C. 3
- D. 4

**Answer**: **C. 3**

**Key Concept**: When you restore a previous version, a new version is added to your list.

---

### Question 82: Web Browser Automation
**Scenario**: A data analyst discovers no connectors are available for the process he would like to automate at his organization. He would like to build a custom connector for website automation, but the analyst's experience in web development is limited to basic HTML and stylesheets. Which automation method would be best for the analyst to deploy?

**Options**:
- A. Web browser automation
- B. Custom connector
- C. HTTP connector
- D. Desktop application automation

**Answer**: **A. Web browser automation**

**Key Concept**: Web browser automation is the best answer because it's the only one that can be tailored with minimal knowledge of CSS and HTML. Custom connectors and HTTP connectors require more intensive experience in development.

---

### Question 83: Sharing Power BI Dashboards
**Scenario**: You create a Power BI dashboard that displays data from Dynamics 365 Customer Engagement. You need to share the Power BI dashboard with co-workers. What are three possible ways to achieve the goal?

**Options**:
- A. Create a Power BI workspace and grant co-worker permission
- B. Publish the dashboard as an app to your co-workers
- C. Export the data into Common Data Service for others to manipulate in Power BI
- D. Export the data to Microsoft Excel for co-workers to import and view in Power BI
- E. Embed reports in your company's internal web portal

**Answer**: **A, B, and E**

**Key Concept**: You can share dashboards through workspaces, publish as apps, or embed reports in web portals.

---

### Question 84: On-Premises Data Gateway
**Scenario**: Your company has an on-premises Microsoft SQL Server database that contains legacy sales data. You must display information from the database in a new Power Apps app. You need to establish a secure connection between the database and app. What should you use?

**Options**:
- A. Data source
- B. App
- C. Data gateway
- D. Power Automate

**Answer**: **C. Data gateway**

**Key Concept**: For an on-premises database, identify a data gateway that was shared with you. Specify "connect using on-premises data gateway" and provide the server name, database name, username, and password.

---

### Question 85: Rolling Back Canvas Apps
**Scenario**: A recent update has been made to a Canvas app. The update causes usability issues. You need to roll back the app to a previous version. What should you do?

**Options**:
- A. Restore the previous version of the app
- B. Uninstall the app for all users and reinstall by using the package from a previous version
- C. Deactivate the live app, import the previous version of the app, and then activate the app
- D. Delete the app and create a new app based on the previous version

**Answer**: **A. Restore the previous version of the app**

**Key Concept**: Restore a canvas app to a previous version in Power Apps by opening powerapps.com, clicking on the apps tab, selecting the info icon for the app, clicking the version tab, and then clicking restore for the version you want to restore.

---

### Question 86: Analyze in Excel Option
**Scenario**: You are a district manager for a large retail organization. You train each store manager to use Power BI to track sales and daily sales targets. The store manager remembers learning about the "analyze in Excel" option but cannot find the option in their Power BI dashboard. You need to help the user resolve the issue.

**Options**:
- A. Install the Power BI desktop app
- B. Select the Spotlight button on the dashboard tile
- C. Subscribe to the dashboard and follow the email link
- D. Navigate to the report used by the dashboard

**Answer**: **D. Navigate to the report used by the dashboard**

**Key Concept**: The "analyze in Excel" option is available in reports, not dashboards.

---

### Question 87: Power BI Features Matching
**Scenario**: A company uses Microsoft Excel workbooks to store consolidated sales data. Workbooks are stored on OneDrive for Business. Match each Power BI feature to its requirement.

**Features and Requirements**:
- Enable user-friendly reporting on phones: **Mobile apps**
- Use natural language to query and aggregate data: **Q&A**

**Key Concept**: Power BI mobile apps provide mobile access, while Q&A allows natural language queries.

---

### Question 88: Support Call Metrics Display
**Scenario**: A company plans to display support call metrics on a screen that is visible to all call center staff. You need to recommend solutions to meet the company's requirements.

**Requirements and Answers**:
- Display a chart with incoming calls versus wait time and pin the chart to a dashboard: **Tile**
- Send a specific user a notification when the number of customer support calls waiting is over 20: **Alert**
- Display metrics from different data sets that have related data: **Tree map**

**Key Concept**: Dashboards use tiles for visualizations, alerts for notifications, and tree maps for hierarchical data visualization.

---

### Question 89: Sharing Power BI Dashboards for Collaboration
**Scenario**: You create a Power BI dashboard that displays Common Data Model data. You need to share the Power BI dashboard with co-workers and allow the co-workers to collaborate. What are two possible ways to achieve the goal?

**Options**:
- A. Create a Power BI workspace and grant co-workers permissions
- B. Publish the dashboard as an app to your co-workers
- C. Export the data to Microsoft Excel, make required changes, and then reimport the data
- D. Create a Power Automate flow to export the data into a SQL Server database

**Answer**: **A and B**

**Key Concept**: Workspaces and published apps allow collaboration on Power BI dashboards.

---

### Question 90: Merging Columns in Power BI
**Scenario**: You're using Dynamics 365 Sales. You need to create a Power BI report that includes customer office locations. The city and state columns must be combined to form one column on the report. What should you do?

**Options**:
- A. Use Power Query Editor to merge columns
- B. Import the data
- C. Export data to Microsoft Excel
- D. Create a view

**Answer**: **A. Use Power Query Editor to merge columns**

**Key Concept**: Power Query Editor allows you to transform and merge columns in your data.

---

### Question 91: Mobile App Types
**Scenario**: A company needs to create a series of mobile applications to empower their field engineers to accomplish several tasks with varying degrees of complexity. Match each app type to its definition.

**App Types and Definitions**:
- Quickly create apps for very complex business processes from data in Common Data Service with very little or no code: **Model-driven**
- Create simple apps with a highly customizable user interface layouts: **Canvas**

**Key Concept**: Model-driven apps are data-first and require minimal code. Canvas apps offer flexible UI design.

---

### Question 92: Call Center Metrics Visualization
**Scenario**: A company runs a call center to handle customer support inquiries. The company tracks metrics including the number of incoming calls and call resolution rates. The company wants to display the metrics on a shared screen that is visible to all call center staff. You need to recommend a visualization solution for the company. Which Power Platform feature should you recommend?

**Options**:
- A. AI Builder
- B. Power Automate
- C. Power Apps
- D. Power BI

**Answer**: **D. Power BI**

**Key Concept**: Power BI is designed for data visualization and displaying metrics on shared screens.

---

### Question 93: Power BI Usage Metrics and Subscriptions
**Scenario**: You are a regional sales manager for a large internet retailer. You create a series of Power BI reports and dashboards to help sales associates be more productive and increase sales. Sales are not increasing as expected. You need to determine if the new reports are being used and send emails to sales associates to provide guidance on how to use the reports and dashboards.

**Requirements and Answers**:
- Send an email to the sales associates on a predetermined schedule: **Subscribe**
- Quantify the adoption usage from the sales associates: **Usage metrics**

**Key Concept**: Subscriptions allow scheduled email delivery, while usage metrics track report adoption.

---

### Question 94: Power BI Filter Types
**Scenario**: You are creating Power BI reports. You need to choose which filters you can use for reports. Which three types of filters can you use?

**Options**:
- A. Drill down
- B. Automatic
- C. Database
- D. Manual
- E. External

**Answer**: **A, B, and D** (Drill down, Automatic, Manual)

**Key Concept**: Power BI supports drill down, automatic, and manual filters for reports.

---

### Question 95: Power BI Visualization Statements
**Scenario**: You are building Power BI visualizations for a team. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- Power BI can only retrieve data from up to two different sources for each dashboard: **No**
- Power BI visualizations can be used in canvas apps and model-driven apps: **Yes**
- Power BI can display charts and list boxes on dashboard: **Yes**

**Key Concept**: Power BI can connect to multiple data sources, and visualizations can be embedded in Power Apps.

---

### Question 96: Real-time IoT Data in Power BI
**Scenario**: A manufacturing company uses Internet of Things (IoT) devices to monitor the temperature in different parts of their warehouses. You need to view near real-time information from the IoT devices in Power BI Service dashboard. Which tool should you use?

**Options**:
- A. Scheduled refresh data set
- B. Streaming data set
- C. Content pack data set
- D. Power BI data flows
- E. Quick insights

**Answer**: **B. Streaming data set**

**Key Concept**: Streaming data sets are designed for real-time data visualization from IoT devices and other streaming sources.

---

### Question 97: Duplicating Power BI Report Pages
**Scenario**: You have a Power BI report with a page named "Rev received". The page shows gross revenue received by your company. You want to create an almost identical page that shows net revenue instead of gross revenue. What should you do?

**Answer**: **Duplicate the "Rev received" page and update the duplicate copy**

**Key Concept**: You can duplicate report pages in Power BI to create similar pages with modifications.

---

### Question 98: Secure Distribution of Power BI Reports
**Scenario**: You create a set of dashboards and reports for a project team that combines data from different sources in Power BI. Some of the data is considered sensitive. You need to distribute the dashboard and report securely to the team. What should you create?

**Options**:
- A. A custom data connector
- B. A published app
- C. A Microsoft Flow
- D. A Power BI workspace

**Answer**: **B. A published app**

**Key Concept**: Published apps provide a secure way to distribute dashboards and reports to specific teams with controlled access.

---

### Question 99: Displaying Power BI Charts
**Scenario**: You are creating visuals in Power BI. You create area charts, pie charts, and donut charts that use your company's data. You need to display the charts to others at the company. Which two objects can you add the charts to?

**Options**:
- A. Power BI service
- B. Power BI reports
- C. Power BI desktop
- D. Power BI dashboards

**Answer**: **B and D** (Power BI reports, Power BI dashboards)

**Key Concept**: Charts are added to reports and can be pinned to dashboards for sharing.

---

### Question 100: Power BI Chart Types for Sales Goals
**Scenario**: A company is implementing Power BI to track sales. Each of the company's regions has specific quarterly and yearly sales goals. You need to build a Power BI dashboard for various reporting requirements.

**Requirements and Answers**:
- Show the quarterly sales total to date in relation to the sales goal: **KPIs**
- View the sales trend by month of the sales year to date from all regions: **Line chart**
- View the year-to-date sales as a percentage by region: **Donut**

**Key Concept**: KPIs show progress toward goals, line charts show trends over time, and donut charts show proportions.

---

### Question 101: Power BI Dashboard Functions
**Scenario**: To create a Power BI dashboard, match each option to its function.

**Options and Functions**:
- Ensure that co-workers can see the dashboard: **Share**
- Display data from Microsoft Excel in the dashboard: **Get data**
- Add a report tile to the dashboard: **Pin**

**Key Concept**: Sharing enables collaboration, get data imports data sources, and pinning adds visuals to dashboards.

---

### Question 102: Merging Columns in Power BI Reports
**Scenario**: You are using Dynamics 365 Sales. You need to pull data into a Power BI report for your team. The city and state columns must be combined to form one column on the report. Which function would you use?

**Options**:
- A. Use Power Query to merge columns
- B. Import the data
- C. Export data to Microsoft Excel
- D. Create a view

**Answer**: **A. Use Power Query to merge columns**

**Key Concept**: Power Query Editor in Power BI allows you to merge and transform columns.

---

### Question 103: Mobile Data Capture Solution
**Scenario**: A carpet cleaning company uses Dynamics 365 Sales. The process of entering customer information during on-site sales calls is very complicated. The company wants a simplified screen that allows salespeople to capture the customer's name, phone number, and other information while speaking to the customer. You need to recommend a solution that works on various types of mobile devices.

**Options**:
- A. Microsoft Database
- B. Power Automate
- C. AI Builder
- D. Canvas app
- E. Power BI

**Answer**: **D. Canvas app**

**Key Concept**: Canvas apps provide flexible, mobile-friendly interfaces for data capture on various devices.

---

### Question 104: Power BI Data Sources
**Scenario**: A company using Power Platform is implementing Power BI. The company plans to connect to several data sources and create reports and dashboards. You need to identify the data sources they can connect to. Which two data sources should you use?

**Options**:
- A. Microsoft Excel
- B. Microsoft Database
- C. Microsoft OneNote
- D. Microsoft Word

**Answer**: **A and B** (Microsoft Excel, Microsoft Database)

**Key Concept**: Power BI can connect to Excel files and various database sources, but not directly to OneNote or Word documents.

---

### Question 105: Power BI Role-Level Security
**Scenario**: You create a multi-page Power BI report for an organization. You must enable sales people in the organization to use the report to view data relevant to the sales region only. You need to enable security for the report. What should you use?

**Options**:
- A. Sensitivity labels
- B. Microsoft Azure Active Directory
- C. Microsoft Trust Center
- D. Data loss prevention policies
- E. Role-level security

**Answer**: **E. Role-level security**

**Key Concept**: Role-level security (RLS) with Power BI can be used to restrict data access for given users. Filters restrict data access at the role level, and you can define filters within roles.

---

### Question 106: Power Apps Portal Features
**Scenario**: You are building a Power Apps portal by using the customer self-service template. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- A customer self-service portal supports Azure AD authentication: **No**
- The customer self-service portal has multiple language support: **Yes**
- Customer self-service portal supports web forms: **Yes**

**Key Concept**: Customer self-service portals support multiple languages and web forms, but use different authentication methods than Azure AD.

---

### Question 107: Power BI Dashboard Sharing
**Scenario**: User one creates several Power BI dashboards for a company. User one shares a dashboard with user two who works for another company. User two reports that she is able to view the dashboard. User two forwards the email containing the dashboard sharing link that she received to user three. User three reports that he receives an error message when he selects the link to view the dashboard. User three can view a dashboard that he has created. You need to determine why user 3 receives an error.

**Options**:
- A. User 3 is running an out-of-date version of Power BI and must upgrade to a newer version
- B. User two is signed into a dashboard that must sign out before user 3 can sign in
- C. Forwarding the email does not share the dashboard with user three
- D. User one is signed in using the wrong organizational account for Power BI

**Answer**: **C. Forwarding the email does not share the dashboard with user three**

**Key Concept**: When you share a report or dashboard, the people you share it with can view it, but forwarding the email does not automatically grant access to others.

---

### Question 108: Power BI Report Builder Statements
**Scenario**: A company plans to implement Power BI. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- Power BI Report Builder is the only tool used to create reports to be published to the Power BI service: **No**
- Power BI service can include calculated columns: **No**
- Power BI desktop can include calculated columns: **Yes**

**Key Concept**: Power BI Desktop is used to create reports and can include calculated columns. The service is for viewing and sharing, not creating calculated columns.

---

### Question 109: Single-Page Visualizations
**Scenario**: You are developing reports for a company. You must create visualizations that include the following data: invoices due from a third-party enterprise resource planning system, number of calls made to the client from Microsoft Dataverse, and Microsoft Excel file data. The reports must be displayed in a single page. You need to create the visualizations. What should you use?

**Options**:
- A. Deployment pipelines
- B. Tables
- C. Columns
- D. Dashboards

**Answer**: **D. Dashboards**

**Key Concept**: A Power BI dashboard is a single page, often called a canvas, that tells a story through visualizations from multiple data sources.

---

### Question 110: Pinning Visuals to Dashboards
**Scenario**: You are using the Power BI service to view a visual on a report that has been shared with you. You need to add the visual to a dashboard as a tile. Which action should you perform?

**Options**:
- A. Export data
- B. Pin
- C. Copy
- D. Spotlight

**Answer**: **B. Pin**

**Key Concept**: An entire report page can be pinned to a dashboard, which is called pinning a live tile. Changes made in the report are automatically synced with the dashboard.

---

### Question 111: Power BI Query Editor
**Scenario**: A company manages a chain of retail stores. The company stores a list of retail store names and numbers in one Power BI table. The company stores sales transaction data that includes a transaction ID in another table. The transaction ID includes the store number. You need to show the store name for all retail transactions in all Power BI reports. Which tool should you use?

**Options**:
- A. Query editor
- B. Power BI service
- C. Microsoft Excel data connector

**Answer**: **A. Query editor**

**Key Concept**: Power BI Desktop comes with Query Editor where you can connect to one or more data sources, shape and transform the data to meet your needs, then load the model into Power BI Desktop.

---

### Question 112: Power BI Desktop vs Service
**Scenario**: A company is using Power BI to build visualizations. The company's IT support team needs to know when to install Power BI Desktop on users' computers, and where the Power BI service is enough to perform tasks. You need to recommend solutions for the company.

**Requirements and Answers**:
- To create dashboards: **Power BI service only**
- To create reports: **Power BI desktop or Power BI service**
- To create calculated columns: **Power BI desktop only**
- To configure security: **Power BI desktop or Power BI service**
- To configure sharing: **Power BI service only**

**Key Concept**: Power BI Desktop is needed for advanced features like calculated columns, while the service is sufficient for viewing, sharing, and basic report creation.

---

### Question 113: Power BI Template Apps
**Scenario**: A company creates a Power BI report for vendors to view purchase orders. Vendors must view the report by using their own tenant environments. You need to use a Power BI technology to allow vendors to view the report. What should you use?

**Options**:
- A. Dashboard
- B. Mobile app
- C. Template app
- D. Workspace

**Answer**: **C. Template app**

**Key Concept**: Template apps allow you to distribute Power BI content to users in different tenant environments.

---

### Question 114: Power BI Dashboard Issues
**Scenario**: You create and share two Power BI dashboards with an accountant. You configure the dashboards to update daily. Dashboard A shows a clock when the accountant tries to view the dashboard. Dashboard B displays outdated data. You need to identify the issues for the dashboards.

**Issues and Dashboards**:
- Dashboard A: **Permissions on data set**
- Dashboard B: **Refresh has not run**

**Key Concept**: Clock icons typically indicate permission issues, while outdated data suggests refresh problems.

---

### Question 115: Power BI Desktop and Service Statements
**Scenario**: For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- You can connect to external resources with Power BI Desktop but not with the Power BI service: **No**
- You can build and edit Power BI reports by using Power BI Desktop or the Power BI service: **Yes**
- The only way to distribute a Power BI Desktop report is by sending the PBIX file to others: **No**

**Key Concept**: Both Power BI Desktop and service can connect to external resources. Reports can be published to the service for distribution.

---

### Question 116: Power Apps Portal Error Diagnosis
**Scenario**: You create a Power App portal. When a user signs into the portal, the following error displays: "User not found." You confirm that the user sign-in information is correct. You need to determine the cause of the error. What should you do?

**Options**:
- A. Disable custom error message
- B. Create a custom error message
- C. Enable diagnostic tools in Lifecycle Services
- D. Enable maintenance mode

**Answer**: **C. Enable diagnostic tools in Lifecycle Services**

**Key Concept**: Diagnostic tools in Lifecycle Services help troubleshoot portal authentication and access issues.

---

### Question 117: Power Apps Portal Types
**Scenario**: A company is building a Power Apps portal. You need to select out-of-the-box portal types to meet the company's requirements. Which portal type should you use?

**Requirements and Answers**:
- Collaboratively onboard new suppliers and distributors: **Partner portal**
- Publish a blog post announcing new supplies: **Community portal**

**Key Concept**: Partner portals are for B2B collaboration, while community portals support content publishing and discussions.

---

### Question 118: Power Apps Building Methods
**Scenario**: A user is trying to understand the difference between the various ways apps can be built by using Power Apps. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- You can embed canvas apps in model-driven apps: **Yes**
- A Power Apps portal can use only one data source: **No**
- You must use Power BI to create reports in model-driven apps: **No**

**Key Concept**: Canvas apps can be embedded in model-driven apps. Portals can use multiple data sources. Power BI is not required for model-driven app reports.

---

### Question 119: Mobile SharePoint Upload Solution
**Scenario**: You are designing a Power App solution that allows users to upload a status report directly to the company Microsoft SharePoint project management site from their mobile device. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- You should build a model-driven app in Power Apps: **No**
- You should build a canvas app in Power Apps: **Yes**
- Users must download and run the Power Apps mobile application to use the solution: **Yes**

**Key Concept**: Canvas apps are ideal for mobile data capture and file uploads. Users need the Power Apps mobile app to run canvas apps on mobile devices.

---

### Question 120: GDPR Compliance Features
**Scenario**: A company's customer-facing applications must comply with global data protection regulations (GDPR). You need to recommend actions to help ensure GDPR compliance. Which two features should the company use?

**Options**:
- A. Force a user to update security questions after a specific amount of time
- B. Prompt a user for consent to use their personal data and record the date consented
- C. Block users who are identified as minors
- D. Automatically deactivate a user who has not used the portal in 6 months

**Answer**: **B and C**

**Key Concept**: GDPR compliance requires consent management and protection of minors' data.

---

### Question 121: Creating Mobile Applications - Sequence
**Scenario**: You need to create a mobile application which will allow sales associates to enter customer sales leads. Which four actions should you perform in sequence?

**Actions**:
1. Create a new Power Apps app
2. Add components to the app
3. Save the app
4. Publish the app

**Key Concept**: The correct sequence for creating a Power Apps app is: create, add components, save, then publish.

---

### Question 122: Canvas Apps Visibility Issues
**Scenario**: A company uses Power Apps canvas apps. When a user opens Power App Studio in a browser and selects "Apps I can edit," they do not see an app that they need to modify. You need to determine why the user cannot see the app. What are three possible reasons?

**Options**:
- A. A user selected an incorrect Power Apps environment
- B. A user has not been granted the system customizer role
- C. The user has not been set as the app co-owner
- D. The app has not been shared with the user
- E. The environment does not have Microsoft Dataverse database

**Answer**: **A, C, and D**

**Key Concept**: App visibility depends on environment selection, co-ownership, and sharing permissions.

---

### Question 123: Model-driven App Statements
**Scenario**: You are creating a model-driven app. For each of the following statements, select yes if the statement is true. Otherwise, select no.

**Statements**:
- To add entities to an app, entities are dragged onto the app canvas from the components area: **No**
- View definitions are created in the component area of the app designer: **Yes**
- You must save, validate, and publish your app for others to see the changes: **Yes**

**Key Concept**: In model-driven apps, entities are added through the app designer interface, not by dragging. Changes require save, validate, and publish.

---

### Question 124: Power Apps Security Groups
**Scenario**: A security administrator is creating Power App Security Groups for the team and wants to ensure everyone has the permissions required for their roles without making any compromises. Which of the following is true about security groups within Power Apps?

**Options**:
- A. Individual users can be assigned greater permissions than the group itself
- B. All users must have the same permissions level
- C. Permissions in Power Apps carry over to Power BI
- D. Power App security groups cannot share apps

**Answer**: **A. Individual users can be assigned greater permissions than the group itself**

**Key Concept**: Putting someone in a security group in Power Apps does not restrict their permissions to what's defined by the group. Individual users can have additional permissions.

---

### Question 125: Model-driven App Objects
**Scenario**: A developer is creating a model-driven app but is unclear on which objects are most relevant to his connected data. Which objects should the developer create to only show the data connected to the form?

**Options**:
- A. Main form
- B. Charts
- C. Workflows
- D. Views

**Answer**: **A. Main form**

**Key Concept**: Only the main form shows connected data. Charts, workflows, and views offer other ways to view and interact with connected data.

---

### Question 126: Model-driven App Benefits
**Scenario**: A developer is comparing the Power Apps model-driven approach and canvas apps approach for app solutions. Which choices are the benefits of a model-driven app Power Platform approach?

**Options**:
- A. The user interface is consistent for both desktop and mobile users
- B. The no-code layout is consistent across all apps in the organization
- C. The app's rendering will automatically respond to the user's device
- D. Supports extensive UI design flexibility and customization

**Answer**: **A, B, and C**

**Key Concept**: Model-driven apps are much simpler to use than canvas apps once the data is imported. They provide consistent UI across devices and apps, but are not as customizable as canvas apps.

---

### Question 127: Approval Types - Single Person Review
**Scenario**: A security administrator uses Power Automate to build out approval types, allowing security team members to quickly approve timesheets and leave requests. If the security team wants to require only a single person's review to grant a leave request, which approval type is most efficient?

**Options**:
- A. Approve or reject, first to respond
- B. Approve or reject, everyone must approve
- C. Custom responses, wait for all responses
- D. Custom responses, wait for one response

**Answer**: **A. Approve or reject, first to respond**

**Key Concept**: With the "approve or reject, first to respond" approval type, assigned approvers are given two options (approve or reject). Approval or rejection by any approver completes the request.

---

### Question 128: Web Browser Automation
**Scenario**: A data analyst discovers no connectors are available for the processes he would like to automate at his organization. He would like to build a custom connector for website automation, but the analyst's experience in web development is limited to basic HTML and stylesheets. Which automation method would be best for the analyst to deploy?

**Options**:
- A. Web browser automation
- B. Custom connector
- C. HTTP connector
- D. Desktop application automation

**Answer**: **A. Web browser automation**

**Key Concept**: Web browser automation is the best answer because it's the only one that can be tailored with minimal knowledge of CSS and HTML. Custom connectors and HTTP connectors require more intensive experience in development.

---

## 📊 Summary

This document contains **64 practice questions** (Questions 65-128) covering:

- **Power BI**: ~25 questions (dashboards, reports, sharing, security, data sources)
- **Power Apps**: ~20 questions (canvas apps, model-driven apps, portals, mobile)
- **Power Automate**: ~10 questions (flows, approvals, automation methods)
- **Dataverse & Administration**: ~5 questions (entities, security, admin centers)
- **General Power Platform**: ~4 questions (components, analytics, tools)

---

## 🔗 Related Resources

- **[Part 1: Questions 1-64](./PRACTICE-QUESTIONS.md)**
- **[PL-900 Study Guide](./README.md)**
- **[PL-900 Course Notes](./COURSE-NOTES.md)**
- [Official Practice Assessment](https://learn.microsoft.com/es-es/credentials/certifications/power-platform-fundamentals/?practice-assessment-type=certification)

---

**Last updated**: February 2025

