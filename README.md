# CV Analyzer — AI Powered

An intelligent CV/Resume analyzer built with Python.
Extracts contact details, skills, locations, and keywords
from any PDF using Google Gemini AI.

## Features
- Contact details extraction (phone, email, links)
- Skills finder grouped by category
- CV summary in structured format
- Location finder
- Keyword search with occurrence count

## Tech Stack
- Python
- PyPDF2 — PDF text extraction
- Google Gemini API — AI-powered analysis
- Google Colab — development environment

## How to Run

### 1. Open in Google Colab
Upload cv_analyser.py to your Colab environment

### 2. Install dependencies
pip install PyPDF2 google-generativeai

### 3. Add your Gemini API key
Get a free key from aistudio.google.com
Add it to Colab Secrets as "my_key"

### 4. Run the program
Upload your CV when prompted and choose a task

## What I Learned
- PDF text extraction with PyPDF2
- Regex pattern design for phone numbers and emails
- Limitations of regex vs AI-based extraction
- Prompt engineering with Gemini API
- Building practical AI-powered tools

## Author
Arun Kumar S
