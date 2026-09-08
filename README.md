# Invoice Reporting Automation with UiPath

A TripleTen AI Automation portfolio project that uses RPA, document understanding, and generative AI to automate invoice data extraction, validation, and reporting.

## Business Problem

Manual invoice review and data entry can be time-consuming, inconsistent, and difficult to scale. This project automates extraction, validation, due-date filtering, AI-generated purchase descriptions, and reporting for invoices due by a specified deadline.

## Solution

The UiPath workflow:

1. Reads invoices from a Google Drive folder.
2. Extracts invoice number, supplier, due date, and total amount using UiPath Document Understanding.
3. Applies a 0.70 confidence threshold to validate extracted data.
4. Flags low-confidence fields for manual review.
5. Uses generative AI to create a concise purchase description of 15 words or fewer.
6. Filters qualifying invoices by due date.
7. Writes validated records to Google Sheets.
8. Logs exceptions for quality review.

## Tech Stack

* UiPath Web Studio
* UiPath Document Understanding
* UiPath GenAI Content Generation
* Google Drive
* Google Sheets
* OCR and document extraction
* Confidence-score validation

## Testing Results

* Achieved 98%+ extraction accuracy during project testing.
* Processed invoices in approximately 10 seconds per document.
* Used a 0.70 confidence threshold to flag low-confidence extractions for review.
* Confirmed that only qualifying invoices were written to the Google Sheets output report.

## Project Documentation

Project case study and sanitized screenshots will be added here.

## Future Improvements

* Add monitoring and dashboards for throughput and exception trends.
* Support additional document types, including purchase orders and receipts.
* Add approval workflows for high-value invoices.
* Expand support for multiple supplier folders and multi-language invoices.

## Author

Lesley Colon  
AI Automation Specialist  
[LinkedIn](https://www.linkedin.com/in/lesleycolon)


## Project Documentation

[View the invoice automation case study](./docs/invoice-reporting-automation-case-study.pdf)



\## Note



This is a TripleTen portfolio project built with hypothetical business data for demonstration and learning purposes.

