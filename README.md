# Salesforce-Data-Management-Project-Import-Export-and-Update-Using-Dataloader.io
This project showcases my hands-on experience with Salesforce data management using **Dataloader.io**. It was completed as part of the **Trailhead module: "Import and Export with Data Management Tools"**, where I learned how to seamlessly handle CSV imports, exports, updates, and mapping in Salesforce.

# 🔄 Salesforce Data Management Project: Import, Export, and Update Using Dataloader.io

## 📌 Project Overview

This project showcases my hands-on experience with Salesforce data management using **Dataloader.io**. It was completed as part of the **Trailhead module: "Import and Export with Data Management Tools"**, where I learned how to seamlessly handle CSV imports, exports, updates, and mapping in Salesforce.

---

## 🚀 Key Tasks Performed

### 📥 1. **Data Export**
- Exported a list of **Accounts** from Salesforce using **Dataloader.io**
- Verified field values including Account Name, ID, and Site (blank)

### 📄 2. **Data Preparation**
- Opened both:
  - The **Account Exports** file (from the previous step)
  - The **Account Site file** (provided as reference)
- Copied and pasted the **Account Site** data into the **Site** column of the exported file
- Saved the new file as: `Updated Account Site Import.csv`

### 🔄 3. **Data Update Using Dataloader.io**
- Created a **new import task** in Dataloader.io
- Selected **Update** for the **Account** object
- Uploaded `Updated Account Site Import.csv`
- Mapped fields correctly, verified the mappings
- Executed the update task and confirmed:
  - ✅ **11 Successes**, ❌ **0 Errors**

---

## 🔍 4. **Verification via List View in Salesforce**
- Navigated to **Sales App** → **Accounts**
- Created a custom List View: `Accounts Modified Today`
- Applied filters:
  - `Last Modified Date` = Today
  - `Account Site` ≠ [blank]
- Verified that all 11 updated accounts now include their **Account Site** data

---

## 🧠 Key Learnings

- How to use **Dataloader.io** for full data lifecycle: Export → Modify → Update
- How to manipulate and clean Salesforce data using Excel/CSV
- Creating **custom List Views** in Salesforce to validate bulk updates
- Importance of **field mapping** and **data accuracy** in real-world Salesforce operations

---

## 🛠 Tools Used

- Salesforce CRM
- Dataloader.io
- Excel / Google Sheets
- Custom List Views

---

## 📚 Trailhead Module Reference

> **Module:** [Import and Export with Data Management Tools](https://trailhead.salesforce.com/)

---

## 📈 Outcome

Successfully updated 11 Account records in Salesforce by importing new Site information using **Dataloader.io** — with zero errors and complete field mapping. This project demonstrates practical admin-level skills in Salesforce data management and validation.

---

## 🏷 Tags

`#Salesforce` `#DataLoader` `#CRM` `#DataImport` `#DataUpdate` `#Trailhead` `#AdminSkills` `#NoCode` `#ExcelToSalesforce` `#LearningInPublic`

