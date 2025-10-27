# Class Timetable

This project is a simple, static HTML page that displays a weekly university/college class schedule.

The schedule is presented in a clean, table-based layout. It is color-coded by subject and includes details like class periods, timings, subjects, faculty initials, and room locations.

---

## Features

* **Weekly View:** Displays the full schedule from Monday to Friday.
* **Detailed Slots:** Includes 8 periods plus a lunch break, with specific timings for each.
* **Color-Coded:** Uses inline `bgcolor` attributes to visually distinguish different subjects.
* **Merged Cells:** Utilizes `colspan` to correctly format classes and labs that span multiple periods.
* **Static & Portable:** It's a single HTML file that can be opened in any web browser without needing a server.

---

## How to Use

1.  Save the code as an HTML file (e.g., `timetable.html`).
2.  Open the file directly in any web browser (like Google Chrome, Firefox, or Safari).
3.  The timetable will be displayed.

---

## Customization

You can easily edit the HTML file in any text editor (like VS Code, Notepad, or Sublime Text) to update:
* Subjects, faculty, and room numbers by changing the text within the `<td>` (table data) cells.
* Timings in the `<th>` (table header) cells.
* Colors by changing the `bgcolor` hex-code values (e.g., `bgcolor="#F4CCCC"`).

---

## Technology Used

* **HTML5:** The entire structure is built with standard HTML table elements (`<table>`, `<tr>`, `<th>`, `<td>`).
* **Inline Styling:** Uses legacy `bgcolor` and `align` attributes for basic styling and layout.
