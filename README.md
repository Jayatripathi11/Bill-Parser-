# Bill-Parser
🧾 Billing Receipt to Text Converter using OCR & Streamlit
This project is a Streamlit-based web application that allows users to upload multiple billing receipts (in image or PDF format) and automatically extract key information such as:

📅 Date of purchase

💰 CGST and SGST values

🧾 Total amount

The extracted data is then displayed and can be exported as a CSV file for further use in analytics or accounting.

🚀 Features
Upload and process multiple receipts at once

Automatically handles different formats and keywords using smart regex and AI-assisted logic

Supports PDF and image formats

Extracted fields include:

Date

CGST

SGST

Total Amount

Download extracted data as CSV

Built with Python, pytesseract, OpenCV, and Streamlit

📦 Tech Stack
Python 3.x

Streamlit

pytesseract (Tesseract OCR)

OpenCV

PIL (Pillow)

pdf2image

dateutil

pandas
