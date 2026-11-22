# exceldiff 📊

> **Easily compare .xlsx, .ods & .csv files – 100% locally in your browser. This tool is provided as-is without warranty.**

`exceldiff` is a lightweight, pure frontend tool that runs entirely in your web browser. It allows you to quickly and easily compare two spreadsheets or CSV files based on primary keys.

**English Version:** `exceldiff.html`  
**German Version:** `exceldiff-de.html`  

*You can change the active language inside the code at `class App static Config`. Feel free to contribute new languages by adding them to `class App static Translations`.*

---

![exceldiff](https://raw.githubusercontent.com/ahrenstk/exceldiff/main/exceldiff.jpg)

## 🚀 Quick Start & Offline Use

Since this tool does not require any backend server, you can launch it locally on your computer in a matter of seconds:

1. **Download the ZIP**, **clone the repository**, or **directly download** `exceldiff.html` or `exceldiff-de.html` 
2. **Open** the `exceldiff.html` or `exceldiff-de.html`file in your preferred web browser (Chrome, Firefox, Edge, Safari, ...).
3. **That's it!** You can now use the tool entirely offline without any active internet connection.

---

## 🔒 100% Privacy & Security

* **No Server Uploads:** Your sensitive spreadsheet data never leaves your computer. All calculations and comparison processes are executed purely within your browser's local memory.
* **No Third-Party CDNs:** All required JavaScript libraries are bundled directly within the source code. No scripts or resources are loaded from external servers (like jsDelivr or Google) when opening the tool.
* **No Cookies & No Tracking:** The tool does not store cookies or local storage tracking data, and no web analytics are performed.

---

## ✨ Features

- **Multi-Format Support:** Compare `.xlsx` (Excel), `.ods` (OpenDocument), `.csv`, and `.txt` files.
- **Smart Key Detection:** Automatically detects the best possible primary key (including composite keys) upon loading your files.
- **Custom Primary Keys:** Define which columns should serve as the unique key for matching rows.
- **High-Performance Virtual Scrolling:** Smoothly handle and scroll through huge datasets by rendering only visible elements in the browser.
- **Visual Differences:** Modifications, added rows, and deleted entries are clearly highlighted using intuitive color schemes.
- **Row & Column Highlighting:** Double-click any row or column to highlight it for better visual guidance.
- **Interactive Column Handling:** Move columns on the fly (← →), toggle their visibility (− / +), or sort them directly in the browser.
- **Filtering & Search:** Built-in live search and dynamic, searchable column dropdown filters to handle large datasets easily.
- **Date Standardization:** Optionally auto-detect and unify various date formats (e.g., `DD.MM.YYYY` or `MM/DD/YYYY` into `YYYY-MM-DD`).
- **Flexible Encoding & Delimiters:** Swap between UTF-8 and ANSI encoding, and handle custom column delimiters.
- **Customize & Exclude Delimiters:** Configure column-, value- and duplicate-delimiter within the settings or exclude them in the app directly.
- **Duplicate Clean-up:** Consolidate duplicates in your first file using adjustable delimiter symbols.
- **Advanced Views:** Toggle instantly between standard comparison view, File 1 only, File 2 only, only showing modified rows, or hiding identical columns entirely.
- **HTML Export:** Exported comparison results remain fully interactive—including search, sorting, column rearranging, and filtering directly within the exported file.
- **CSV Export:** Fast and clean export of your cleaned text or CSV data.

---

## 📦 Bundled Libraries & Licenses

This project uses the following open-source libraries (each under an MIT License), which are integrated directly at the end of the source code:

1. **read-excel-file** (v9.x) – For reading Excel spreadsheets - [https://gitlab.com/catamphetamine/read-excel-file](https://gitlab.com/catamphetamine/read-excel-file)
2. **PapaParse** (v5.4.1) – For fast parsing of CSV and text files - [https://github.com/mholt/PapaParse](https://github.com/mholt/PapaParse)
3. **fflate** (v0.8.3) – For decompressing `.ods` archives - [https://github.com/101arrowz/fflate](https://github.com/101arrowz/fflate)
4. **tXml** (v6.0.0) – For parsing XML contents within ODS files - [https://github.com/TobiasNickel/tXml](https://github.com/TobiasNickel/tXml)


---

## 📄 License

This project is licensed under the **MIT License**.
