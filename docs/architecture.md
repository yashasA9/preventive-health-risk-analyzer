# System Architecture

The Preventive Health Risk Analyzer is built using a multi-stage AI pipeline.

## Components Overview

1. User Input Layer
   - Collects health indicators and user queries

2. Risk Analyzer
   - Extracts risk-related features from input

3. Risk Classifier
   - Computes overall risk level
   - Generates preventive guidance

4. RAG-based Q&A Module
   - Retrieves relevant health guidelines
   - Generates grounded responses using IBM Granite models

## Design Principles
- Modular architecture
- Explainable AI outputs
- Prevention-first healthcare approach
- Reduced hallucination via RAG
