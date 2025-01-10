# Invoice Entry Automation
The Invoice Entry Automation project is designed to streamline the process of handling invoices received via email. 
This project automates the extraction of invoice data from PDF attachments, uploads the data into an ERP application, and generates reports in Excel, significantly reducing manual data entry and improving efficiency.

# Key Features
- Email Processing: Automatically reads unread emails in Outlook, filters for invoices, and downloads PDF attachments.
- Data Extraction: Utilizes PDF reading techniques to extract relevant invoice details, including invoice number, item descriptions, quantities, and prices.
- ERP Integration: Uploads extracted data directly into an ERP application, ensuring accurate record-keeping and management.
- Reporting: Generates and updates Excel reports with invoice information, including the number of items and timestamps.

# Packages Used
- UiPath: For building the RPA workflow.
   Make sure to have these UiPath Packages installed : 
  - UiPath.Mail.Activities
  - UiPath.System.Activities
  - UiPath.Excel.Activities
  - UiPath.PDF.Activities
  - UiPath.UIAutomation.Activities
- Microsoft Outlook: To manage and retrieve invoice emails.
- Excel: For reporting and data management.
- PDF Reading Libraries: To extract information from PDF invoices.
  
# Origin
This project idea is part of the Robotic Process Automation (RPA) Specialization on Coursera and is the capstone project number 1. It serves as a practical implementation of RPA concepts learned throughout the course.

# Getting Started
- Ensure you have UiPath Studio and Microsoft Office 365 installed.
- Clone the repository to your local machine.
- Send invoice PDFs to your email account as attachments. 
- Set up your Outlook account for email retrieval.
- Configure paths for PDF storage and Excel file locations.
- Run the automation process to handle invoices.

(In this project's files you will find invoice sample and the ERP Application Order Entry.exe that only needs a double click to be launched)
