# Maiora

OCR-Based Table Extraction from PDFs
Project Overview
This project performs Optical Character Recognition (OCR) on PDF documents to extract tables and structured data, converting them into an Excel file. It utilizes pdfplumber for table extraction and pytesseract for text recognition from images.

Features
Extracts tables from specified PDF pages.
Uses OCR for text extraction when table structures are not detected.
Converts extracted data into an Excel file with proper formatting.


Technologies Used
Python
pdfplumber (for structured table extraction)
pytesseract (OCR for text recognition)
pdf2image (converting PDFs to images)
pandas & openpyxl (data handling and Excel output)
