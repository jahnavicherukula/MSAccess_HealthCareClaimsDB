# Medical Claims Manager (MS Access)

A Microsoft Access database project for managing and auditing medical insurance claims. Designed to demonstrate practical use of tables, forms, queries, reports, and VBA in a real-world healthcare

---

## 📌 Project Overview

**Medical Claims Manager** is a desktop-based application built in **MS Access** to:
- Record patient and provider information
- Log and track claims and claim details
- Manage audits and review actions
- Generate summaries using queries and reports

---

## 🏥 Functional Modules

### 1. **Tables**
- **Patients** – Patient details with insurance info
- **Providers** – NPI, specialty, and contact info
- **Claims** – Claim status, provider, patient, date, claimamount
- **ClaimDetails** – CPT codes, diagnosis, amount
- **AuditLogs** – Tracks flagged, approved, or rejected actions on claims

### 2. **Forms**
- `frmPatientEntry`
- `frmProviderEntry`
- `frmClaimEntry` with subform for `ClaimDetails`
- `frmAuditLogs`


### 3. **Queries**
- `qryClaimAmountUpdate` – Calculates and updates total claim amounts
- `qryClaimStatusUpdate` – Updates claim status post-audit
- `qryClaimSummary` – Combines claim info with patient and provider details

### 4. **Reports**
- `rptClaimSummary`


## ⚙️ Technologies Used
- Microsoft Access (.accdb)
- SQL queries (update, select, aggregate)
- Relational table design with joins

---

## 🧠 Features Implemented
- ✅ Lookup fields for dropdowns (PatientID, ProviderID, Status)
- ✅ Subforms for nested claim details
- ✅ Combo boxes and form controls
- ✅ Auto-calculation of claim totals via queries
- ✅ Report generation using queries

---

## 🔐 Sample Data (Mocked for Testing)
Includes 4–5 sample records for:
- Patients
- Providers
- Claims and ClaimDetails
- AuditLogs

---


