# eScanX

**Version:** 1.0.1  
**Author:** Harjit Singh  
**Email:** [mbmaster.pc@gmail.com](mailto:mbmaster.pc@gmail.com)   
**Date:** 02 November 2025  

---

## 📘 Overview

**eScanX PDF Document Analyzer** is a Windows-based desktop utility designed to scan, extract, fix-rotation and analyze PDF documents — including both **searchable** and **scanned image-based** PDFs.

The app leverages **Python-powered OCR and text-processing** libraries to perform high-accuracy keyword extraction, and integrates seamlessly with a modern **.NET WinForms** interface for easy operation.

---

## 💡 Key Features

- 🔍 **PDF Text Extraction** — Handles both text-based and image-based PDFs.
- 📄 **Page Rotation Correction** — Auto correct page rotation.
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
    - `PyPDF2` — PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files.
  - Optional Tools:
    - `ghostscript` — Required for PDF rendering and compression.
    - `qpdf` — Used internally by `ocrmypdf` for PDF optimization.

---

## 🖥️ User Interface

🛡️ Note:
If Windows shows a Defender SmartScreen warning (“Windows protected your PC”), click More info → Run anyway.
This happens because the app is unsigned.
For permanent removal, use the digitally signed build or install the included certificate.

<img width="400" height="350" alt="win_warn" src="https://github.com/user-attachments/assets/40f6aa70-dda1-46c6-ae06-49a812b4159c" />

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

**🔗 Download Link**

Below link to download the software msi setup:

https://drive.google.com/file/d/1D_NDEp8i2P63KNe13yiRouKfOXc-Aj_7/view?usp=drive_link

---

## 🧾 Change Log

**Version 1.0.1** — *02 November 2025*
- Initial release.
  

---


## 📷 Screenshots:

**Menu/Settings:**

<img width="700" height="754" alt="1_1" src="https://github.com/user-attachments/assets/cf11c5f0-7b75-4198-aab1-9a38ef2fc7b9" />

**Search Result Console:**

<img width="700" height="166" alt="2" src="https://github.com/user-attachments/assets/5ea1f5aa-d35e-4cf9-906f-c98cabce2e75" />

**OCR Conversion Result Console:**

<img width="700" height="477" alt="3" src="https://github.com/user-attachments/assets/65a0d2c6-e506-454b-b753-9c9df9e28232" />

**Multipe Files Selection:**

<img width="700" height="229" alt="4" src="https://github.com/user-attachments/assets/9da20f10-b839-4181-a84f-79fd019e06ec" />

---

## ⚙️ License
This project is free to use for personal or professional testing purposes.  
However, **no liability** is accepted for any damage, data loss, or equipment issues resulting from its use.

---
