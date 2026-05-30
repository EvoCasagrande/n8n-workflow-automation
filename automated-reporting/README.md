# 📄 Invoice Data Extraction Workflow (n8n)

## 🚀 What this automation does

Automatically processes supplier invoice PDFs, extracts key invoice data using AI, and saves the structured information into Google Sheets — reducing manual data entry and improving operational efficiency.

## ⚙️ How it works

1. A new invoice PDF is uploaded to a Google Drive folder
2. The workflow downloads the file and extracts the PDF text
3. An IF condition checks whether the invoice requires OCR processing
4. If OCR is needed, the file is converted and processed using AI vision/OCR
5. If OCR is not needed, the extracted text is sent directly to OpenAI
6. OpenAI extracts the relevant invoice information in a structured format
7. The extracted data is validated and formatted using JavaScript nodes
8. The information is appended automatically to Google Sheets
9. The processed file is moved to the correct Google Drive folder
10. Errors and exceptions are handled to avoid breaking the workflow

## 🧠 Key features

* Automatic invoice processing from PDF files
* OCR and non-OCR processing paths
* AI-powered data extraction with OpenAI
* Conditional logic to handle different invoice formats
* JavaScript data cleaning and formatting
* Automatic Google Sheets integration
* File organization in Google Drive
* Error handling for failed or incomplete extractions

## 💼 Business value

* Saves time on manual invoice data entry
* Reduces human errors when copying invoice information
* Centralizes supplier invoice data in Google Sheets
* Improves control over received invoices
* Makes accounting and administrative workflows faster
* Allows the business to scale invoice processing without extra manual work

## 🎯 Ideal for

* Small and medium businesses
* Accounting teams
* Administrative departments
* Companies that receive supplier invoices by PDF
* Businesses that need structured invoice data in spreadsheets

## 🛠 Tech stack

* n8n
* Google Drive
* Google Sheets
* OpenAI
* OCR processing
* JavaScript
* APIs / HTTP Requests

## 🖼 Workflow preview

See screenshot included in this repository.

## 📩 Want this for your business?

I can build custom automation workflows to extract, process, validate, and organize business data from documents, emails, PDFs, CRMs, forms, and other sources.

Contact me to discuss your automation needs.
