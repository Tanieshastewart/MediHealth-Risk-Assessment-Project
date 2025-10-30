
# 🏥 MediHealth Clinic – NIST Cybersecurity Risk Assessment Project

## 📘 Overview
This project demonstrates a **NIST Cybersecurity Framework (CSF)** based **Risk Assessment** for a fictional healthcare organization — *MediHealth Clinic*.  
It evaluates cybersecurity risks, maps them to NIST CSF functions, and provides recommendations to strengthen security and ensure **HIPAA compliance**.

---

## 🏢 Company Profile
**Name:** MediHealth Clinic  
**Industry:** Healthcare (Outpatient and Telehealth Services)  
**Size:** 150 employees across 3 locations  
**Systems:** EHR, patient portal, cloud storage, and medical devices  
**Regulations:** HIPAA, HITECH, NIST SP 800-53  

---

## ⚙️ Framework Used
**NIST Cybersecurity Framework (CSF)**  
1. **Identify (ID)** – Inventory, risk assessment, and governance  
2. **Protect (PR)** – Access controls, encryption, awareness training  
3. **Detect (DE)** – Monitoring, anomaly detection, alerts  
4. **Respond (RS)** – Incident response plan, communication strategy  
5. **Recover (RC)** – Backup, restore, post-incident review  

---

## 🔍 Risk Assessment Summary

| Asset | Threat | Vulnerability | Impact | Likelihood | Risk Level | Recommended Control |
|--------|---------|---------------|---------|-------------|-------------|---------------------|
| EHR System | Ransomware | Unpatched software | High | High | Critical | Regular patching, EDR deployment, daily backups |
| Patient Portal | Unauthorized Access | Weak passwords | High | Medium | High | MFA, password policy enforcement |
| Workstations | Malware Infection | Unrestricted internet access | Medium | High | Medium | Network segmentation, web filtering |
| Cloud Storage | Data Breach | Misconfigured permissions | High | Medium | High | Access review, encryption, audit logging |
| Medical Devices | Lateral Movement | Outdated firmware | Medium | Medium | Medium | Network isolation, device patching schedule |
| Employees | Phishing | Lack of training | High | High | Critical | Phishing simulations, quarterly training |

---

## 🧭 Key Documents in This Repository
| File | Description |
|------|-------------|
| **Risk_Assessment_Matrix.xlsx** | Detailed list of risks, likelihood, and mitigation measures |
| **Incident_Response_Plan.pdf** | Framework and procedures for handling incidents |
| **Policy_Templates/HIPAA_Security_Policy.txt** | Example of an internal security policy aligned with HIPAA |
| **README.md** | Main project documentation |

---

## 🧰 Tools & References
- NIST Cybersecurity Framework v1.1  
- NIST SP 800-30 Risk Assessment Guide  
- CIS Controls v8  
- Excel for risk matrix  
- ReportLab for documentation PDF  

---

## 🚀 Recommendations
- Implement **Zero Trust Architecture**
- Enforce **MFA** on all systems
- Conduct **Quarterly Penetration Testing**
- Continue **Employee Cybersecurity Training**
- Perform **Annual Risk Assessments**

---

## 🧑‍💻 Author
**Taniesha Stewart**  
CompTIA Security+ | IBM Cybersecurity Analyst | ISC2 Certified  
🔗 [LinkedIn](www.linkedin.com/in/taniesha-stewart-00872133b)  

---

## 📂 Suggested Folder Structure for GitHub
```
MediHealth_Risk_Assessment_Project/
│
├── README.md
├── Risk_Assessment_Matrix.xlsx
├── Incident_Response_Plan.pdf
│
└── Policy_Templates/
    └── HIPAA_Security_Policy.txt
```

---

**Purpose:** This repository is for educational and professional portfolio demonstration only. No real patient data is used.
