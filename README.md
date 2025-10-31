# eScanX
# 🧠 eScanX PDF Document Analyzer

**Version:** 1.0.1 
**Author:** Harjit Singh  
**Date:** October 2025  

## Software Download Link:
All required runtime binary (python) are included in setup, There is no need to install any additional software/lib.

https://drive.google.com/file/d/1WGQAcputhkQLbMIOKaD79ZbJ6RXBp43_/view?usp=drive_link

---

## 📘 Overview

**eScanX PDF Document Analyzer** is a Windows-based desktop utility designed to scan, extract, and analyze PDF documents — including both **searchable** and **scanned image-based** PDFs.

The app leverages **Python-powered OCR and text-processing** libraries to perform high-accuracy keyword extraction, and integrates seamlessly with a modern **.NET WinForms** interface for easy operation.

---

## 💡 Key Features

- 🔍 **PDF Text Extraction** — Handles both text-based and image-based PDFs.  
- 🧾 **OCR Conversion** — Converts scanned PDFs into searchable ones using *Tesseract OCR* and *OCRmyPDF*.  
- 📄 **Selective Page Scanning** — Option to process specific pages (start–end range).  
- 🧠 **Keyword Search** — Locate defined keywords, even across noisy or OCR-scanned text.  
- 🎨 **Graphite Professional Theme** — Clean UI with neutral color palette for professional use.  
- 🧾 **Detailed Logs** — Colored runtime logs (Info, Warning, Error) displayed in a console.  

---

## 🧩 Technologies Used

### 🖥️ Front-End (UI)
- **.NET (WinForms)**
  - Handles UI logic, logging, threading, and progress updates.
  - Integrates Python runtime execution.
  - Provides color-coded console output.

### 🐍 Back-End (Python Runtime)
- **Python 3.13+**
- Core Libraries:
  - `pdfplumber` — Extracts text from searchable PDFs.
  - `pdf2image` — Converts PDF pages into images.
  - `pytesseract` — Optical character recognition (OCR).
  - `opencv-python` — Image preprocessing before OCR.
  - `numpy` — Matrix operations and pixel processing.
  - `ocrmypdf` — Converts scanned PDFs into fully searchable documents.
- Optional Tools:
  - `ghostscript` — Required for PDF rendering and compression.
  - `qpdf` — Used internally by `ocrmypdf` for PDF optimization.

---


<img width="727" height="757" alt="1" src="https://github.com/user-attachments/assets/09de9d2e-6661-4c92-8149-1f7dd5b68e86" />

<img width="727" height="755" alt="2" src="https://github.com/user-attachments/assets/9fe795e0-3240-47b2-83cc-3afe0e47b62a" />


