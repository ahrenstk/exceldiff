# exceldiff 📊

> **Compare and analyze .xlsx, .ods & .csv files directly in your browser – fast, privacy-friendly, and with no installation required.**

`exceldiff` is a lightweight, purely client-side web tool designed to compare spreadsheets and CSV files using customizable primary keys.

## ✨ Features

* **Multi-Format Support:** Compare `.xlsx` (Excel), `.ods` (OpenDocument), `.csv`, and `.txt` files seamlessly.

* **Primary Key Matching:** Define custom primary key columns to accurately align rows across files.

* **Visual Diffing:** Highlight modified cells, added rows, and removed entries with clear visual indicators.

* **Search & Filter:** Built-in live search and customizable column filters for large datasets.

* **Deduplication:** Integrated tools to identify and consolidate duplicate entries.

* **Export Options:** Export comparison results to HTML or CSV.

* **100% Client-Side:** Privacy first—your data never leaves your local machine.

## 🚀 Quick Start

Since `exceldiff` is built as a self-contained single-file application, you can run it instantly without any server setup:

1. Download the HTML file or clone this repository.

2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari).

3. Drag and drop your target files into the designated drop zones.

4. Select the primary key column(s) and click **Compare Files**.

## 📦 Libraries & Licenses

This project relies on the following open-source libraries (distributed under the MIT License):

1. **read-excel-file** (v9.x) – Fast parsing for Excel spreadsheets.

2. **PapaParse** (v5.4.1) – Powerful CSV and delimiter text parser.

3. **fflate** (v0.8.3) – High-performance decompression for `.ods` archives.

4. **tXml** (v6.0.0) – Lightweight XML parser for ODS document content.

## 📄 License

Distributed under the **MIT License**. See the source header for details.
