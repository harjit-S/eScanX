# eScanX

**Version:** 1.0.1
**Author:** Harjit Singh  
**Date:** November 2025  

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

## ⬇️ Software Download Link:
All required runtime binary (python) are included in setup, There is no need to install any additional software/lib.

**⚙️ System Requirements & Visual C++ Redistributable**

if ❌ OCR failed: Unable to extract pages from PDF, This issue can occur on older versions of Windows (especially Windows 10 builds) that don’t include all the modern system DLLs required by Poppler and Ghostscript components used for OCR.

  **To fix this:**
  -  Go to your installation directory: C:\Program Files\eScanX\
  -  Find and run: vc_redist.x64.exe
  -  Complete the installation and restart the application.  
💡 Tip: This redistributable ensures all required runtime DLLs are present. The installer continues even if this step fails, but OCR or PDF extraction may not work until it’s installed.

**🔗Link**
https://drive.google.com/file/d/1Yfdldzj4RCoI74DiDblC33GwcH4eYrF2/view?usp=drive_link


---


## 📷 Screenshots:

**Menu/Settings:**

<img width="700" height="683" alt="1" src="https://github.com/user-attachments/assets/d900aa86-82dc-4e6c-8a67-5d41bfd72c92" />

**Search Result Console:**

<img width="700" height="166" alt="2" src="https://github.com/user-attachments/assets/5ea1f5aa-d35e-4cf9-906f-c98cabce2e75" />

**OCR Conversion Result Console:**

<img width="700" height="477" alt="3" src="https://github.com/user-attachments/assets/65a0d2c6-e506-454b-b753-9c9df9e28232" />

---

