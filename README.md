# 📋 Callbox Role Assessment Tool

A web-based internal tool designed to streamline applicant evaluation during interviews at Callbox. This system helps interviewers assess candidate qualifications and automatically suggest suitable roles based on their input.

---

## 🚀 Project Overview

The Role Assessment Tool is used during interviews to collect and analyze applicant data. It simplifies the decision-making process for interviewers by recommending three possible job positions that match the applicant’s profile. These recommendations are stored for HR and interviewers to review, helping ensure consistent and data-driven hiring decisions.

---

## 🧩 Features

- **Applicant Form**  
  Collects key information from candidates including:
  - Personal Information  
  - Educational Background  
  - Qualifications  
  - Technical Skills  
  - Industry Experience

- **Automated Role Matching**  
  After submission, the system analyzes the applicant's input and suggests three potential roles that are currently open at Callbox.

- **Private Results**  
  Role suggestions are visible only to the interviewer—not to the applicant.

- **Google Form Integration**  
  Final results are uploaded via Google Apps Script to a designated Google Form, allowing HR and other interviewers to access and review them later.

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend Logic:** JavaScript (Client-side analysis)  
- **Integration:** Google Apps Script for Google Form submission

---

## 📦 How It Works

1. Interviewer opens the Role Assessment Tool during the interview.  
2. Applicant fills out the form with their details.  
3. The system processes the input and determines three matching roles.  
4. These results are sent to a Google Form using Apps Script.  
5. HR and interviewers can view the results in the Google Form response sheet.

---

## 🔒 Access Control

- Applicants do **not** see the role suggestions.  
- Only interviewers and HR personnel have access to the Google Form results.

---

## 📌 Notes

- This tool is intended for internal use only.  
- Role matching logic can be customized based on evolving company needs.  
- Make sure to update the Google Form ID and field mappings in `appsScript.gs` before deployment.
