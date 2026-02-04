✨ Folder Fairy
Folder Fairy is a lightweight desktop assistant for labour brokers, site agents, and anyone who wrangles piles of certificates, CVs, and medical files. It automatically organizes and audits your document folders so you don’t have to.

🧾 What it does
🔍 Finds SA ID numbers in certificate files (PDF/TXT/Image with OCR)

📝 Prefixes every file in a folder with the correct ID for consistency

🖼️ Converts images → PDFs so all documents have a standard format

📑 Detects split documents (e.g. CV page1.pdf, CV page2.pdf) and reports merge candidates

📊 Keeps logs (ems_prefix_log.csv, merge_report.csv) for compliance & auditing

🚀 Why use it
Saves hours of manual renaming and checking

Reduces human error in compliance-heavy industries

Friendly GUI, no coding required

Designed for South African labour broker workflows

📂 Typical Workflow
Select one or more site folders in the GUI

Folder Fairy scans, renames, converts, and audits automatically

Review logs/ems_prefix_log.csv and logs/merge_report.csv for results

Done ✅

🛠️ Tech
Python 3.10+

pdfminer.six (text extraction)

Pillow + pytesseract (image/OCR support)

PyPDF2 (PDF operations)

tkinter (desktop GUI)