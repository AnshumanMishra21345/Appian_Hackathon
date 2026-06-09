# Document Intelligence Platform

> Top 15 among 1000+ registrations in the Appian AI Hackathon

A GenAI-powered workflow for converting unstructured PDFs and images into structured, schema-compliant JSON records using OCR, vision-language models and validation-driven extraction pipelines.

## Overview

Organizations process large volumes of invoices, forms, IDs and reports containing critical information. Manual extraction is slow, error-prone and difficult to scale.

This project automates document understanding by combining OCR, classification, PII detection and structured information extraction into a unified pipeline capable of generating machine-readable JSON outputs.

## Architecture

```text
PDF / Image
     │
     ▼
 OCR Extraction
     │
     ▼
Document Classification
     │
     ▼
  PII Detection
     │
     ▼
Information Extraction
     │
     ▼
 Schema Validation
     │
     ▼
 Structured JSON
```

## Features

* OCR-based text extraction from PDFs and images
* Automated document classification
* PII detection and sensitive information identification
* Structured information extraction using GenAI models
* Schema validation and consistency checking
* Generation of structured JSON records

## Tech Stack

### AI & LLMs

* Groq API
* Vision Language Models (VLMs)
* Prompt Engineering

### Backend

* Python
* Pydantic
* JSON Schema Validation

### Processing

* OCR
* Document Parsing
* Structured Output Generation

## Key Statistics

* 6-stage document processing pipeline
* 3 dedicated AI modules
* 10+ validation and consistency checks
* Top 15 finish among 1000+ registrations

## Example Output

```json
{
  "document_type": "Invoice",
  "vendor": "ABC Pvt Ltd",
  "invoice_number": "INV-1024",
  "date": "2025-01-01",
  "amount": 4500
}
```

## Results

* Ranked among the Top 15 teams out of 1000+ registrations in the Appian AI Hackathon.
* Automated conversion of unstructured documents into schema-compliant JSON records.
* Developed an end-to-end GenAI workflow integrating OCR, extraction and validation components.

## Future Work

* Support additional document categories
* Confidence scoring for extracted fields
* Human-in-the-loop validation
* Batch document processing
* Cloud deployment and API integration

```
```
