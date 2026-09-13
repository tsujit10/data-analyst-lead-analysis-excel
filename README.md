# 📊 Data Analyst Intern – Lead Data Analysis

## 📌 Project Overview

This project was completed as part of a **Data Analyst Intern Research & Lead Data Analysis Task**.

The objective was to transform raw lead data into structured, meaningful analysis using **Microsoft Excel**, identify data-quality issues, analyze lead and conversion performance, and create a simple dashboard for business insights.

---

## 🎯 Objectives

- Clean and validate raw lead data
- Identify duplicate student records
- Analyze counsellor performance
- Analyze lead status and follow-ups
- Calculate overall conversion rate
- Calculate conversion rates by:
  - Counsellor
  - Course
  - Lead Source
- Analyze course-wise and state-wise lead performance
- Identify top courses and states by lead volume
- Create a simple analytical dashboard
- Document assumptions and methodology

---

## 🛠️ Tools Used

- **Microsoft Excel**
  - Data Cleaning
  - Excel Formulas
  - COUNTIF / COUNTIFS
  - IF
  - INDEX / MATCH
  - AGGREGATE / LARGE
  - Sorting & Filtering
  - Conditional Formatting
  - Charts
  - Dashboard
- **AI assistance**
  - Formula development
  - Analytical structuring
  - Validation and interpretation of results

---

## 🧹 Data Cleaning & Quality Checks

The raw dataset was reviewed and cleaned before analysis.

### Cleaning performed

- Standardized course names by removing unnecessary spaces
- Validated State/Country values
- Validated Counsellor names
- Validated Lead Status
- Validated Chat/Call Status
- Validated Lead Source
- Flagged suspicious or placeholder student names for review
- Preserved questionable records instead of deleting them

### Records flagged for review

The following student names were flagged as potential data-quality issues:

- Hdhdbhd
- Anonymous
- Test
- sdfgsdfg

These records were **not deleted** so that the original dataset remained complete.

---

## 🔍 Duplicate Analysis

Duplicates were identified using **Student Name only**, as specified in the task.

| Record Type | Count |
|---|---:|
| Total Records | 66 |
| Duplicate Records | 30 |
| Unique Records | 32 |
| Review Records | 4 |

Duplicate records were flagged rather than removed.

All analysis was performed using the complete **66-record dataset**.

---

## 👥 Counsellor Analysis

The dataset contains leads handled by five counsellors:

- Rahul
- Anjali
- Priya
- Arun
- Sneha

### Best-performing counsellor

**Anjali** recorded the highest conversion rate:

**2 conversions / 16 leads = 12.50%**

---

## 💬 Chat / Call Analysis

The actual Chat/Call Status categories in the dataset were analyzed, including:

- Fee details shared
- Interested in admission
- Asked for college options
- Wrong/unclear requirement
- Call back tomorrow
- Interested - follow up
- Requested course details
- Not reachable
- Need eligibility check
- Application initiated

Follow-ups were identified using the following definition:

> Lead Status = Follow-up  
> **OR** Chat/Call Status = Call back tomorrow  
> **OR** Chat/Call Status = Interested - follow up

---

## 📈 Conversion Analysis

### Overall Performance

| Metric | Result |
|---|---:|
| Total Leads | 66 |
| Converted Leads | 6 |
| Overall Conversion Rate | 9.09% |

### Conversion Rate Formula

```text
Conversion Rate = Converted Leads / Total Leads × 100
