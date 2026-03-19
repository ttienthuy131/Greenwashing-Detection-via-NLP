# Greenwashing-Research

## Overview
Extracts environmental disclosure statements from corporate sustainability reports (PDFs) to enable analysis of ESG communication and greenwashing detection.

## Method
- **PDF Parsing:** Handles two-column layouts and extracts raw text  
- **Data Cleaning & Segmentation:** Cleans text and segments into sentences  
- **Keyword Matching & Classification:**  
  - Maps statements to ESG themes  
  - Labels statements as green practice vs. green communication  
- **Metadata Extraction:** Captures relevant report information for analysis  
- **Output:** Produces structured datasets suitable for disclosure analysis and greenwashing research

## Tools
- **Languages & Libraries:** Python, PyPDF2 / pdfplumber, Pandas, Regex, NLTK  
- **Pipeline Overview:** PDF parsing → Cleaning → Sentence segmentation → Keyword matching → ESG classification → Metadata → Structured dataset

## Next Steps
- Integrate NLP models for advanced greenwashing detection  
- Perform temporal or sectoral analysis of ESG disclosures 
