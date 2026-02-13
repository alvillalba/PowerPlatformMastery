# Project 1: Employee Directory Canvas App

## 📋 Overview

Create a simple Canvas App that displays employee information from a SharePoint list. This project helps you understand Canvas Apps, data connections, and basic UI controls.

## 🎯 Learning Objectives

- Create a Canvas App from scratch
- Connect to SharePoint as a data source
- Use Gallery controls to display data
- Implement search functionality
- Understand app sharing

## 📚 Prerequisites

- Power Apps license (free Developer plan works)
- Access to SharePoint (or use sample data)
- Basic understanding of Power Apps interface

## 🛠️ Step-by-Step Instructions

### Step 1: Prepare Data Source

1. Create a SharePoint list named "Employees" with these columns:
   - **Title** (Single line of text) - Employee Name
   - **Department** (Choice: IT, Sales, HR, Finance)
   - **Email** (Single line of text)
   - **Phone** (Single line of text)
   - **Photo** (Hyperlink or Picture)

2. Add 5-10 sample employees to the list

### Step 2: Create Canvas App

1. Go to [Power Apps](https://make.powerapps.com)
2. Click **+ Create** → **Canvas app from blank**
3. Name it "Employee Directory"
4. Choose **Phone** layout
5. Click **Create**

### Step 3: Connect to SharePoint

1. In the left panel, click **Data** → **+ Add data**
2. Search for "SharePoint"
3. Select **SharePoint**
4. Choose your site and select the "Employees" list
5. Click **Connect**

### Step 4: Add Gallery Control

1. Click **Insert** → **Gallery** → **Vertical**
2. Resize the gallery to fill most of the screen
3. In the gallery's **Items** property, enter: `Employees`
4. The gallery will automatically display your data

### Step 5: Customize Gallery Layout

1. Select the gallery
2. In the **Layout** dropdown, choose **Title, subtitle, and body**
3. Customize the fields:
   - **Title1**: `ThisItem.Title` (Employee Name)
   - **Subtitle1**: `ThisItem.Department` (Department)
   - **Body1**: `ThisItem.Email` (Email)

### Step 6: Add Search Functionality

1. Insert a **Text input** control above the gallery
2. Name it `SearchBox`
3. Update the gallery's **Items** property to:
   ```
   Search(Employees, SearchBox.Text, "Title", "Department", "Email")
   ```

### Step 7: Add Detail Screen

1. Click **+ New screen** → **Blank**
2. Add labels to display:
   - Employee Name
   - Department
   - Email
   - Phone
3. Add a **Back** button that navigates to the previous screen

### Step 8: Connect Gallery to Detail Screen

1. Select the gallery
2. Set **OnSelect** property to:
   ```
   Navigate(DetailScreen, ScreenTransition.Fade)
   ```
2. Pass selected item data to detail screen

### Step 9: Test and Publish

1. Click **Play** (▶) to test the app
2. Test search functionality
3. Test navigation to detail screen
4. Click **File** → **Save**
5. Click **Publish** → **Publish this version**

## ✅ Success Criteria

- [ ] App displays employee list from SharePoint
- [ ] Search functionality works
- [ ] Can navigate to detail screen
- [ ] App is published and accessible

## 🔗 Related Resources

- [Canvas App Documentation](https://learn.microsoft.com/power-apps/maker/canvas-apps/)
- [SharePoint Connector](https://learn.microsoft.com/connectors/sharepointonline/)
- [Gallery Control](https://learn.microsoft.com/power-apps/maker/canvas-apps/controls/control-gallery)

## 💡 Next Steps

- Add filtering by department
- Add image display for employee photos
- Implement edit functionality
- Add form validation

---

**Estimated Time**: 1-2 hours  
**Difficulty**: ⭐⭐ (Beginner)

