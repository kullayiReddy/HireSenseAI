# HR-AI-Screening-Sentiment

## Overview
This project automates two critical HR processes using AI and Large Language Models (LLMs):

1. **Resume Screening**  
   An AI-powered tool that evaluates candidate resumes for a Software Engineer role by matching skills, experience, and qualifications against the job description.

2. **Employee Sentiment Analysis**  
   Analyzes employee feedback (surveys, exit interviews) to detect sentiment and predict attrition risk, recommending engagement strategies to improve retention.

---

## Features
- Text extraction from PDF and DOCX resumes.
- Custom prompt engineering for accurate resume fit scoring.
- Sentiment and attrition risk classification from employee feedback.
- Outputs structured JSON results for easy integration.
- Deployment-ready code for Azure AI Studio / Google AI Studio.

---

## Getting Started

### Prerequisites
- Python 3.7 or higher
- `openai` Python package (or Google Vertex AI SDK if using Google AI Studio)
- `pdfplumber` and `python-docx` for resume text extraction
- `pandas` for feedback data processing

Install dependencies:
```bash
pip install openai pdfplumber python-docx pandas
## Colab Link
https://colab.research.google.com/drive/1HVML_67tFR7tWR721R7ho1uZf4Bui36-?usp=sharing
