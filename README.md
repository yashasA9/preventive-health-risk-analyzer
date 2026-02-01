#  Preventive Health Risk Analyzer

An AI-powered preventive healthcare system built using IBM watsonx.ai, Langflow, and Retrieval Augmented Generation (RAG).

This project analyzes user health indicators, classifies risk levels, provides preventive guidance, and supports follow-up Q&A grounded in verified health documents.

---

##  Problem Statement
AI-Based Preventive Health Risk Assessment System

---

##  System Architecture

The solution uses a **modular multi-model architecture**:

### Model 1 — Risk Analyzer
- Extracts key health indicators from user input
- Identifies potential health risk factors

### Model 2 — Risk Classifier & Guidance
- Classifies risk into Low / Medium / High
- Provides preventive lifestyle recommendations

### Model 3 — RAG-based Follow-up Q&A
- Uses Retrieval Augmented Generation
- Answers health-related queries using verified documents
- Reduces hallucination by grounding responses in knowledge sources

---

##  Technology Stack
- IBM watsonx.ai
- IBM Granite Foundation Models
- Langflow (DataStax)
- Needle Vector Store
- Retrieval Augmented Generation (RAG)

---
