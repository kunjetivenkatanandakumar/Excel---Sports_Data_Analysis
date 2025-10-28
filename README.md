# 🏅 Sports Data Analysis (Excel Project)

## 📘 Project Overview
This Excel project is based on a business scenario from **XYZ Co Pvt Ltd**, a company that organizes sports events at the international level.  
Countries nominate sportsmen from various departments, and our task is to **systematize the membership roster**, perform **data cleaning**, **data analysis**, and **generate reports** as per business requirements.

The project is divided into **three stages**:
1. **Data Cleaning**
2. **Data Analysis**
3. **Report Generation**

---

## 🧮 STAGE 1: Data Cleaning
In this stage, the focus is on **standardizing** and **formatting** the dataset in the `SPORTSMEN` sheet.

### **Task 1: Standardizing the Dataset**
| Column | Task |
|--------|------|
| Col B | Populate the FULLNAME in format: PREFIX FIRSTNAME LASTNAME (All Uppercase) |
| Col K | Get the COUNTRY NAME (from LOCATION sheet) |
| Col L | Populate the LANGUAGE spoken (from LOCATION sheet) |
| Col M | Generate EMAIL in format: `lastname.firstname@xyz.org` (all lowercase) |
| Col Q | Populate the SPORT LOCATION (from SPORT sheet) |

### **Task 2: Data Formatting**
| Column | Task |
|--------|------|
| Col A | Display MEMBER ID as a 3-digit number (e.g., 001, 002...) |
| Col G | Format BIRTHDATE as `dd mmm yyyy` (e.g., 09 May 1986) |
| Col N | Display WEIGHT with units (e.g., 80 kg) |
| Col S | Format SALARY in thousands (e.g., 87670 → **87.67k**) |

---

## 📊 STAGE 2: Data Analysis
In this stage, data from the `SPORTSMEN` sheet is used for summarization and insights in the `ANALYSIS` sheet.

### **Task 1: Pivot Table Summary**
- Create a Pivot Table at `Range B3`
- Columns: Group by **Gender**
- Rows: Group by **Country**
- Values: Count of candidates by Country and Gender
- Remove Grand Totals

### **Task 2: Excel Functions Summary**
- Create a Summary Table at `Range G4`
- Use Excel functions (Remove Duplicates, Transpose, COUNTIFS)
- Display count of candidates by Country and Gender

---

## 📈 STAGE 3: Generate Report
Final stage to create a **Pivot Table Report** in the `REPORT` sheet.

### **Tasks**
- Create Pivot Table starting at `Range A3`
- Include: MEMBER ID, FULL NAME, EMAIL, GENDER, YEAR OF BIRTH, COUNTRY NAME, LANGUAGE, and SPORT
- Change layout to **Tabular Form**
- Remove expand/collapse buttons and Grand Totals
- Allow user to **filter data by SPORT LOCATION**

---

## 🧠 Key Learnings
- Mastered **Excel data cleaning techniques**
- Created **dynamic pivot tables** for reporting
- Used **text, date, and lookup functions**
- Applied professional formatting and automation in Excel

---

## 🧰 Tools Used
| Tool | Purpose |
|------|----------|
| **Microsoft Excel** | Data Cleaning, Analysis & Reporting |
| **Pivot Tables** | Summarization and reporting |
| **Excel Functions (VLOOKUP, COUNTIFS, TEXT, CONCAT, etc.)** | Data transformation |

---

### ⭐ How to View
1. Download `Sports_Data_Analysis.xlsx`  
2. Open it in Microsoft Excel (2016 or later recommended).  
3. Follow each stage sheet (`SPORTSMEN`, `ANALYSIS`, `REPORT`) for full workflow.  
