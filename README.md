# End-to-End Individual Case Safety Report (ICSR) Processing Simulation

## 📌 Project Overview
This project serves as an end-to-end hands-on simulation of the clinical data processing workflow performed by a Pharmacovigilance (PV) Specialist. It demonstrates technical execution across case intake validation, MedDRA dictionary hierarchy coding, chronological safety narrative synthesis, and international regulatory metadata mapping (xEVMPD framework).

The case simulates a spontaneous post-marketing adverse event report involving a severe cutaneous reaction (Toxic Epidermal Necrolysis) secondary to antibiotic exposure.

## ⚙️ Technical Skills & Competencies Demonstrated
* **ICSR Triage & Validity Verification:** Auditing raw, unstructured source documents to confirm the 4 mandatory regulatory criteria (Identifiable Patient, Identifiable Reporter, Suspect Drug, and Adverse Event).
* **MedDRA Dictionary Coding (LLT to PT to SOC):** Standardizing verbatim clinical signs, diagnostic findings, medical histories, and drug indications into precise hierarchies.
* **ICH-Compliant Clinical Narrative Architecture:** Drafting comprehensive, chronological medical summaries tracking patient timeline, seriousness criteria, dechallenge outcomes, and causality assessments according to GVP standards.
* **Regulatory Compliance Mapping:** Constructing data entry matrices aligned with the European Medicines Agency (EMA) xEVMPD and SPOR/IDMP medicinal data tracking frameworks.
* **Corporate Communication:** Executing internal cross-functional case escalation briefs modeled on enterprise database routing operations.

## 📂 Repository Structure & Components

### 1. `1_Case_Triage_and_Narrative.docx` (Microsoft Word)
Contains the operational breakdown of the raw intake clinic notes, the validated 4-point triage checklist confirming reportability, and the finalized multi-paragraph safety narrative formatted for enterprise safety database injection.

### 2. `2_MedDRA_and_Product_Matrix.xlsx` (Microsoft Excel Workbook)
A multi-tab database processing matrix structured as follows:
* **Tab 1: MedDRA Coding Matrix:** Demonstrates verbatim-to-database translation, mapping clinical inputs directly across Lowest Level Terms (LLT), Preferred Terms (PT), and corresponding System Organ Classes (SOC).
* **Tab 2: Regulatory Product Info:** Simulates an xEVMPD electronic product data entry record tracking localized unique product identifiers, generic substance codes (SMS IDs), pharmaceutical dosage structures, and routes of administration.

---
*Note: This repository represents an independent portfolio project constructed to demonstrate functional readiness for enterprise pharmacovigilance applications (such as Oracle Argus Safety workflows) within global Contract Research Organizations (CROs).*
# ICSR_Processing_MedDRA_Coding
An end to end simulation of the ICSR data processing workflow,showcasing triage validation,MedDRA dictionary hierarchy coding, chronological safety narrative synthesis,and  regulatory metadata mapping aligned with xEVMPD/IDMP Standards.
