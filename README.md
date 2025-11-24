# pdf-invoice-processor

# 📄 PDF Invoice Processor - Professional

A lightweight, offline desktop application for automating common PDF invoice tasks — built with Python and Tkinter.

> ✨ No internet required. No cloud. No API keys. Just drag, click, and done.

---

## 🚀 Features

### 1. Split Invoices
Break a single multi-page PDF into individual invoice files — perfect for archiving or emailing separately.

### 2. Merge PDFs
Combine multiple PDF invoices into one file based on criteria like:
- Monthly grouping
- Vendor name
- Custom folder structure

### 3. Extract Text (OCR)
Use optical character recognition to extract text from scanned or image-based PDFs:
- Output as plain `.txt` (raw text)
- Output as structured `.json` (with line items, metadata, coordinates)
- Adjustable DPI quality for better accuracy


## 👥 Perfect for

- **Freelancers** managing recurring client invoices  
- **Small accounting teams** processing vendor bills without expensive software  
- **Developers** looking for a modular, hackable PDF/OCR toolkit  
- **Educators or researchers** extracting data from scanned financial documents  
- **Privacy-conscious users** who avoid cloud-based PDF services  

---

## 🖥️ How to Use

1. Download the latest release or clone the repo.
2. Run `python main.py` (requires Python 3.8+).
3. Select your desired operation from the sidebar.
4. Browse files/directories, adjust settings, and click the action button.

---

## 🛠️ Tech Stack

- **GUI**: Tkinter (native, cross-platform)
- **PDF Handling**: PyPDF2, pdfplumber, pdf2image
- **OCR**: pytesseract (Tesseract OCR engine)
- **Cross-Platform**: Works on Windows, macOS, Linux

---

## 📥 Download & Contribute

🔗 [Download Latest Release](https://github.com/yourusername/pdf-invoice-processor/releases)  
💡 Found a bug? Want a new feature? Submit an issue or PR!

---

> Developed by Suhail Asghar — because everyone deserves tools that make boring tasks disappear.
