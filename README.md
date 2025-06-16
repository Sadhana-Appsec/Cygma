# Cygma
Protect Knowledge Base

---

A lightweight document uploader and keyword search engine supporting `.pdf`, `.docx`, and image files (`.jpg`, `.jpeg`, `.png`) with OCR (Optical Character Recognition) support.

---

📁 FEATURES
----------
- Upload and manage files via a web interface
- Search by filename or content (including text inside images and PDFs)
- View `.docx` files with inline images
- OCR-enabled keyword matching for scanned documents

========
For MAC:
🛠 SETUP INSTRUCTIONS (cmd - In terminal)
---------------------

1. Install Python dependencies:
   pip install Flask==3.0.2 python-docx==1.1.0 PyMuPDF==1.23.19 Pillow==10.3.0 pytesseract==0.3.10

2. Install Tesseract OCR (required for image-to-text functionality):
    brew install tesseract

3. Directory Structure:
    Cygma-Mac/
    ├── app.py
    ├── files/
    │   └── [uploads + images/]
    ├── static/
    │   ├── style.css
    │   └── images/
    │       ├── logo_photon.svg
    │       └── Cygma_logo.png
    ├── templates/
    │   ├── layout.html
    │   ├── index.html
    │   ├── search.html
    │   └── view_docx.html
    └── requirements.txt  

4. Run the app:
    python app.py / python3 app.py
    Then go to: http://localhost:5000
