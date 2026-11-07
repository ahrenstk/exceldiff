# exceldiff 📊

> **.xlsx, .ods & .csv easily compared – 100% in your browser. The comparison is provided without guarantee.**

`exceldiff` is a lightweight, pure frontend tool that runs completely in your browser. It allows you to easily compare two spreadsheets or CSV files directly based on definable primary keys.

---

![exceldiff-de](https://raw.githubusercontent.com/ahrenstk/exceldiff-de/main/exceldiff-de.jpg)

## ✨ Features

- **Multi-Format Support:** Compares `.xlsx` (Excel), `.ods` (OpenDocument), `.csv`, and `.txt` files.

- **Smart Key Detection:** Automatic detection of the best possible (including composite) primary key when loading files.

- **Primary Key Matching:** Determine yourself which columns should serve as the unique key for row matching.

- **Visual Differentiation:** Changes, added rows, and deleted entries are clearly highlighted in color.

- **Cell and Row Highlighting:** Double-click to highlight entire columns or rows in color for better orientation.

- **Interactive Column Handling:** Columns can be moved (← →), individually hidden or shown (− / +), or sorted directly in the browser.

- **Filter and Search Functions:** Integrated live search and dynamic, searchable column dropdown filters for large datasets.

- **Date Standardization:** Optional automatic detection and unification of various date formats (e.g., DD.MM.YYYY, MM/DD/YYYY to YYYY-MM-DD).

- **Flexible Encoding & Delimiters:** Supports switching between UTF-8 and ANSI encoding, as well as handling custom column delimiters.

- **Duplicate Cleaning:** A tool to consolidate duplicates in the first file with adjustable separators.

- **Advanced Views:** Quick switching between comparison mode, showing only File 1 or File 2, and showing only changed rows.

- **Interactive HTML Export:** Exported HTML results remain fully interactive – including search, sorting, column moving, and filtering directly within the exported file.

- **CSV Export:** Fast export of the cleaned text or CSV data.

- **100% in Browser:** Your data never leaves your computer at any time.

- **External JavaScript Libraries:** Built directly into the code and are therefore not reloaded from CDNs (customizable).

---

## 📦 Used Libraries & Licenses

This project uses the following open-source libraries (each under the MIT License):

1. **read-excel-file** (v9.x) – For reading Excel spreadsheets.

2. **PapaParse** (v5.4.1) – For fast parsing of CSV and text files.

3. **fflate** (v0.8.3) – For unpacking `.ods` archives.

4. **tXml** (v6.0.0) – For parsing XML content in ODS files.

---

## 📄 License

This project is licensed under the **MIT License**. Further details can be found in the source code.
