
# Portuguese Immigrants – Immigration Status Project

This project displays the current status of 955 Portuguese immigrants to the Hawaiian Kingdom.

## Purpose

The goal of this project is to track and document the immigration records for Portuguese immigrants to the Hawaiian Kingdom. Descendants and researchers can view this list to identify individuals and contribute missing information.

## Features

- **Color-coded Status column**:
  - **Still searching** (light blue)
  - **Info Received** (light green)
- **Searchable and sortable table**
- **Progress bar** (Styled version only)
- **Submit Information button** for community input

## Files

- `IMMIGRANT_STATUS_FINAL_STYLED.html`  
  Full-featured version with Progress Bar, search, pagination, and status tracking.

- `IMMIGRANT_STATUS_FINAL_PRINT.html`  
  Print-friendly version: all names on one page, no Progress Bar, no pagination.

- `README.md`  
  Project description and usage notes.

- `FINAL_PROJECT_CHECKLIST.md`  
  Summary of project status.

---

## **IMPORTANT — How to UPDATE the table (Step-by-step)**

When you receive new information and want to mark a name as "Info Received":

1️⃣ Open the HTML file (`IMMIGRANT_STATUS_FINAL_STYLED.html`) in a text editor (such as **Notepad++**, **VS Code**, or even basic Notepad).

2️⃣ Use the editor’s **Search** function to locate the person’s name.

3️⃣ You will find a row that looks like this:

```html
<td class="status-cell still-searching">Still searching</td>
```

4️⃣ Change that row to:

```html
<td class="status-cell info-received">Info Received</td>
```

5️⃣ Save the file.

6️⃣ Open `IMMIGRANT_STATUS_FINAL_STYLED.html` in your browser.  
✅ The **Progress Bar** will update automatically — no need to touch the script.

✅ You can also use the table’s built-in **Search box** to filter and see only "Info Received" names.

---

## **IMPORTANT — How to PRINT "Info Received" names for GRANT REPORTS (every 3 months)**

**DO NOT generate a new file — just use the STYLED version (easy and fast!).**

1️⃣ Open `IMMIGRANT_STATUS_FINAL_STYLED.html` in Chrome (or your favorite browser).

2️⃣ In the table’s **Search box** (top right), type:

```
Info Received
```

3️⃣ The table will automatically filter to display only names marked as "Info Received."

4️⃣ Press:

- **Ctrl+P** (Windows)  
- **Cmd+P** (Mac)  

5️⃣ In the Print window, choose **Save as PDF** (recommended), or print on paper.

✅ This is the EASIEST way to generate a report for your grant every 3 months.

---

## **Why use this method**

- You do not need to modify the PRINT version every time.  
- You do not need to regenerate the table.  
- The STYLED version handles this perfectly — with Search + Print.

✅ This saves time and ensures your Progress Bar stays correct!

---

## Author

**Kahealani Martins Curammeng, Psy.D.**  
Portuguese Heritage Immigration Research Project  
[https://www.portugueseheritageproject.com](https://www.portugueseheritageproject.com)

---

Thank you for helping preserve the history of Portuguese immigrants to Hawaiʻi! 🌺

---
