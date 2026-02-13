# Project 2: Automated Email Notification Flow

## 📋 Overview

Create a Power Automate flow that automatically sends email notifications when a new item is added to a SharePoint list. This project teaches you about automated flows, triggers, and actions.

## 🎯 Learning Objectives

- Create an automated cloud flow
- Use SharePoint triggers
- Configure email actions
- Understand flow conditions
- Test and monitor flows

## 📚 Prerequisites

- Power Automate license (free plan works)
- Access to SharePoint
- Office 365 email account

## 🛠️ Step-by-Step Instructions

### Step 1: Prepare SharePoint List

1. Create a SharePoint list named "Support Tickets" with columns:
   - **Title** (Single line of text)
   - **Status** (Choice: New, In Progress, Resolved)
   - **Priority** (Choice: Low, Medium, High)
   - **AssignedTo** (Person)
   - **Description** (Multiple lines of text)

2. Add a few sample tickets

### Step 2: Create Automated Flow

1. Go to [Power Automate](https://make.powerautomate.com)
2. Click **+ Create** → **Automated cloud flow**
3. Name it "Notify on New Support Ticket"
4. Search for "SharePoint" in triggers
5. Select **When an item is created**
6. Click **Create**

### Step 3: Configure SharePoint Trigger

1. Select your **Site Address**
2. Select **List Name**: "Support Tickets"
3. Click **Show advanced options** (optional)

### Step 4: Add Condition

1. Click **+ New step**
2. Search for "Condition"
3. Select **Condition** control
4. Configure:
   - **First value**: `Priority` (from dynamic content)
   - **Condition**: **is equal to**
   - **Second value**: `High`

### Step 5: Add Email Action (If High Priority)

1. In the **If yes** branch:
   - Click **Add an action**
   - Search for "Send an email"
   - Select **Send an email (V2)** or **Office 365 Outlook**
2. Configure email:
   - **To**: Your email address (or use dynamic content)
   - **Subject**: `High Priority Ticket: [Title]`
   - **Body**: 
     ```
     A new high-priority support ticket has been created:
     
     Title: [Title]
     Priority: [Priority]
     Status: [Status]
     Assigned To: [AssignedTo]
     Description: [Description]
     ```

### Step 6: Add Another Email (If Not High Priority)

1. In the **If no** branch:
   - Add another **Send an email** action
   - Configure with different subject: `New Support Ticket: [Title]`

### Step 7: Save and Test

1. Click **Save**
2. Go to your SharePoint list
3. Create a new item with **Priority = High**
4. Check your email for notification
5. Create another item with **Priority = Low**
6. Verify different email was sent

### Step 8: Monitor Flow Runs

1. Go to **My flows**
2. Click on your flow
3. View **Run history**
4. Check for successful runs
5. Review any errors if present

## ✅ Success Criteria

- [ ] Flow triggers when new item is created
- [ ] Condition correctly identifies high priority
- [ ] Email sent with correct information
- [ ] Flow runs successfully without errors

## 🔗 Related Resources

- [Automated Flows](https://learn.microsoft.com/power-automate/getting-started)
- [SharePoint Triggers](https://learn.microsoft.com/connectors/sharepointonline/)
- [Condition Control](https://learn.microsoft.com/power-automate/use-expressions-in-conditions)

## 💡 Next Steps

- Add approval action for high-priority tickets
- Send notifications to Teams channel
- Add delay actions
- Create flow for item updates

---

**Estimated Time**: 1 hour  
**Difficulty**: ⭐⭐ (Beginner)

