\# Document Intelligence Platform



\*\*Top 15 / 1000+ Registrations — Appian AI Hackathon\*\*



A multimodal GenAI pipeline for transforming unstructured PDFs and images into structured, schema-compliant JSON records through OCR, document classification, PII detection and information extraction.



\---



\## Problem Statement



Organizations routinely process large volumes of unstructured documents containing critical information such as names, addresses, identifiers, dates and financial records. Manual extraction is often slow, error-prone and difficult to scale across heterogeneous document formats.



This project aims to automate document understanding and convert unstructured records into machine-readable structured data.



\---



\## Features



\* OCR-based text extraction from PDFs and images

\* Automated document classification

\* PII detection and sensitive information identification

\* Structured information extraction using GenAI

\* Schema-constrained JSON generation

\* Validation and consistency checking pipeline



\---



\## System Architecture



```text

PDF / Image

&#x20;     │

&#x20;     ▼

&#x20;OCR Extraction

&#x20;     │

&#x20;     ▼

Document Classification

&#x20;     │

&#x20;     ▼

&#x20;  PII Detection

&#x20;     │

&#x20;     ▼

Information Extraction

&#x20;     │

&#x20;     ▼

&#x20;Schema Validation

&#x20;     │

&#x20;     ▼

&#x20;Structured JSON

```



\---



\## Technology Stack



\### AI \& LLMs



\* Groq API

\* Vision Language Models (VLMs)

\* Prompt Engineering



\### Backend



\* Python

\* Pydantic

\* JSON Schema Validation



\### Processing



\* OCR

\* Document Parsing

\* Structured Output Generation



\---



\## Key Components



\### Document Classification



Automatically categorizes incoming documents into predefined document classes for downstream processing.



\### PII Detection



Identifies and extracts sensitive information including names, addresses, identification numbers and contact information.



\### Information Extraction



Uses schema-guided prompting to extract relevant entities and generate structured outputs.



\### Validation Layer



Ensures generated outputs conform to predefined schemas and consistency constraints before final export.



\---



\## Example Output



```json

{

&#x20; "document\_type": "Invoice",

&#x20; "invoice\_number": "INV-1024",

&#x20; "date": "2025-01-01",

&#x20; "vendor": "ABC Pvt Ltd",

&#x20; "amount": 4500

}

```



\---



\## Results



\* Ranked among the \*\*Top 15 teams from 1000+ registrations\*\* in the Appian AI Hackathon.

\* Built a complete 6-stage document processing pipeline integrating OCR, classification, extraction and validation.

\* Generated structured, schema-compliant JSON outputs from diverse unstructured document formats.



\---



\## Future Improvements



\* Support additional document categories

\* Confidence scoring for extracted fields

\* Human-in-the-loop verification

\* Multi-document workflows

\* Deployment as a scalable document processing service



\---



\## Team



Developed as part of the Appian AI Hackathon.



