# Incubyte_TestCases
Manual QA assessment for Incubyte – Gmail Compose test cases in Excel (Traditional &amp; BDD format)
# 📧 Gmail Compose – QA Test Cases
### Incubyte Software Craftsperson Assignment

---

## 📌 Overview

This repository contains manual test cases written as part of the **Incubyte Software Craftsperson hiring assignment**.

The objective was to test the **Compose function in Gmail** by sending an email with:
- **Subject:** `Incubyte`
- **Body:** `QA test for Incubyte`

---

## 📁 Repository Structure

```
├── Gmail_Compose_TestCases_Incubyte.xlsx   # All test cases (Traditional + BDD)
└── README.md                               # Project documentation
```

---

## 🧪 What's Covered

### ✅ Traditional Test Cases
| Field | Detail |
|---|---|
| Format | TC ID / Scenario / Pre-conditions / Steps / Test Data / Expected Result / Actual Result / Status |
| Positive TCs | 12 |
| Negative TCs | 10 |
| **Total** | **22** |

### 🥒 BDD-Style Test Cases (Gherkin)
| Field | Detail |
|---|---|
| Format | Given / When / Then |
| Positive TCs | 10 |
| Negative TCs | 9 |
| **Total** | **19** |

---

## 🔍 Scenarios Covered

### Positive Scenarios
- Open Gmail Compose window
- Enter valid recipient, subject (`Incubyte`), and body (`QA test for Incubyte`)
- Send email successfully and verify in Sent folder
- Save email as Draft and reopen to send
- Send with CC and BCC recipients
- Minimise and restore compose window with data intact
- Subject field accepting up to 255 characters
- Special characters in subject field

### Negative Scenarios
- Send without a recipient (To field empty)
- Send without a subject (empty subject prompt)
- Send without a body (empty body prompt)
- Invalid email format in To field
- Non-existent email address (bounce-back)
- Discard compose – email not saved to Drafts
- Access Compose while logged out
- Subject with only whitespace treated as empty
- Extremely long body text handling

---

## 🛠️ Tools & Format

| Item | Detail |
|---|---|
| Test Style 1 | Traditional (Manual Test Cases) |
| Test Style 2 | BDD / Gherkin |
| Deliverable Format | Microsoft Excel (.xlsx) |
| Application Tested | Gmail – Compose Function |

---

## 👤 Author

**Submitted by:** MonishkumarN
**Role Applied For:** QA Engineer (Manual Testing) 
**Company:** Incubyte  
**Date:** May 2026
