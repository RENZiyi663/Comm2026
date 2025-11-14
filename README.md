# Comm2026

This repository contains course materials and lab exercises for Comm2026, focusing on using AI agents to process and analyze research data.

## Overview

The course demonstrates how to use AI coding assistants to write Python programs for data processing, text analysis, and report generation. The labs progress from simple data manipulation to complex text analysis and synthesis tasks.

## Lab Structure

### Lab 1: Word Count Analysis
**Objective:** Learn to ask AI agents in natural language to write and run simple Python programs.

**Task:**
- Add word count for each abstract in a research dataset
- Process a CSV file containing research paper abstracts
- Add a new column indicating the word count for each abstract
- Output the enhanced CSV file

**Files:**
- Input: `demo/lab1/input/AI_mental_health.csv`
- Script: `demo/lab1/word_count.py`
- Output: `demo/lab1/output/AI_mental_health_with_wordcount.csv`

**What we learn:** Basic interaction with AI coding assistants to automate simple data processing tasks.

---

### Lab 2: Screen and Synthesize Studies
**Objective:** Write Python programs to process large numbers of text files and produce written reports.

**Task:**
- Identify studies that use Generative AI (Large Language Models such as ChatGPT, Gemini, DeepSeek, Claude, LLaMA, etc.)
- Add a column in the CSV to indicate the Generative AI technology used
- Generate a narrative report documenting how AI tools are used in the first 20 studies
- Output both an enhanced CSV and a markdown report

**Files:**
- Input: `demo/lab1/input/AI_mental_health.csv` (shared with Lab 1)
- Script: `demo/lab2/screen_and_synthesize.py`
- Output: 
  - `demo/lab2/output/AI_mental_health_with_genai.csv`
  - `demo/lab2/output/GenAI_Usage_Report.md`

**What we learn:** Advanced text processing, pattern matching, and automated report generation using AI assistants.

---

### Lab 3: Open-Ended Exploration
**Objective:** Independent exploration of using AI assistants for data analysis and processing.

**Task:**
- Students search and download CSV files containing research paper titles and abstracts
- Explore different ways to use AI coding assistants to analyze and process the data
- Apply skills learned in Labs 1 and 2 to new datasets
- Experiment with custom analysis tasks and report generation

**Files:**
- Input: `demo/lab3/input/` - Students provide their own CSV files
- Output: `demo/lab3/output/` - Results of their exploration

**What we learn:** Independent problem-solving, applying AI assistant skills to new contexts, and creative exploration of data analysis possibilities.

---

## Additional Tools

### PDF to Markdown Converter
A utility script to convert PDF documents to Markdown format while preserving content and structure.

**Location:** `demo/PDF2md/`

**Files:**
- `pdf_to_markdown.py` - Python script for PDF to Markdown conversion
- `instructions.md` - Instructions for using the converter
- Example outputs: Converted markdown files from PDF sources

**Usage:** The script uses PyMuPDF (fitz) to extract text from PDFs and format it as Markdown, with automatic detection of section headings and proper paragraph formatting.

---

## Project Structure

```
Comm2026/
├── demo/
│   ├── lab1/          # Word count analysis
│   ├── lab2/          # Generative AI screening and synthesis
│   ├── lab3/          # Open-ended exploration lab
│   └── PDF2md/        # PDF to Markdown conversion utility
└── Practice/          # Practice exercises (mirrors demo structure)
```

---

## Requirements

- Python 3.x
- pandas
- PyMuPDF (fitz) - for PDF processing
- Standard Python libraries (os, re, etc.)

---

## Getting Started

1. Clone this repository
2. Install required dependencies: `pip install pandas pymupdf`
3. Navigate to the lab directory you want to run
4. Execute the Python script: `python3 <script_name>.py`

---

## Learning Outcomes

Through these labs, students learn:
- How to effectively communicate with AI coding assistants
- Python programming for data processing and text analysis
- Automated report generation and documentation
- Working with CSV files and structured data
- Text pattern matching and keyword detection
- File I/O and data manipulation
