# pdf-search-and-summary-tool
This Python script automates the process of scanning PDF files within a folder, searching for a specified keyword, and generating a summary of sentences that contain that keyword. The output is saved in a structured CSV file, making it easy to analyze and review large collections of documents.

## 🚀 Features
- 🔍 Extracts full text from multi-page PDF files  
- 🧠 Generates keyword-based summaries from each PDF  
- 📊 Counts keyword occurrences  
- 💾 Saves results (Filename, Keyword Count, Summary) in a CSV  
- ✅ Supports batch processing of multiple PDF files in a folder
  
## 🎯 Use Cases
- Research and literature reviews  
- Legal or financial document scanning  
- Media content filtering  
- Academic or government archives analysis
  
## 🛠 Tech Stack
| Component         | Tool/Library     |
|------------------|------------------|
| Language          | Python 3.x       |
| PDF Processing    | pdfplumber     |
| Text Parsing      | re (regex)     |
| File I/O          | os, csv      |

## 📂 Project Structure
project-folder/
│
├── movie/                  # Folder with input PDF files
├── description.csv         # Output CSV (auto-generated)
└── pdf_summary_tool.py     # Main script file
