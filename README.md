# NAMASTE–ICD11 FHIR Terminology Microservice  

A lightweight **FHIR R4–compliant terminology microservice** that integrates **NAMASTE codes (Ayush)** with **WHO ICD-11 (TM2 + Biomedicine)**.  
It enables **dual coding** for traditional medicine and biomedicine in EMRs, supporting **interoperability, analytics, and insurance claims** while complying with **India’s 2016 EHR Standards**.  

---

## 🚀 Features  

- **Dual Mapping (Core)**  
  - Maps **NAMASTE ↔ ICD-11 TM2 & Biomedicine** codes  
  - Generates **FHIR CodeSystem + ConceptMap**  
  - Stores both codes in **FHIR ProblemList** for EMRs  

- **FHIR-Compliant APIs**  
  - Auto-complete value-set lookup  
  - Translation API (**NAMASTE ↔ ICD-11**)  
  - FHIR Bundle upload with dual-coded encounters  

- **Security & Compliance**  
  - **OAuth 2.0 with ABHA tokens**  
  - **Audit trails & metadata** (ISO 22600, SNOMED CT, LOINC)  

---

## 🔥 Value-Added Extensions  

- 🤖 **AI-Assisted Mapping** – Suggests ICD-11 equivalents for NAMASTE codes without direct mappings.  
- 🌐 **Multi-Lingual Search** – Lookup in **Hindi, Sanskrit, Tamil** + WHO ICD-11 multilingual support.  
- 🔄 **Real-Time Sync** – Auto-refreshes mappings using WHO ICD-API & FHIR Subscriptions.  
- 📶 **Offline-First Mode** – Local caching for **low-bandwidth/rural clinics**.  

---

## 🏥 Why This Matters  

- Enables **clinicians** to record **Ayush + biomedical diagnoses together**.  
- Powers **insurance claims** under **ICD-11 rules**.  
- Supports **Ministry of Ayush** with **real-time morbidity analytics**.  
- Goes beyond compliance → **future-proof, clinician-friendly, and inclusive**.  

---

