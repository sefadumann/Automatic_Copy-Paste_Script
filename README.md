# Automatic Copy-Paste Application

These Python scripts automatically paste copied text into a Word document

---

## 1. Copy_Paste.py (Non-GUI Automatic Copy-Paste Script)

This script monitors the clipboard, and each time new text is copied, it automatically pastes it into a Word document. Additionally, it removes line breaks between lines, keeping only single line spacing, and adds a custom separator (`***`) after each entry for clear separation. The resulting document is compact and organized.

### Usage

- Run the script.
- Every time you copy text, it will be automatically saved in `automatic_paste.docx`.
- To stop the process, simply close the script.

---

## 2. Copy_Paste_App.py (Tkinter GUI Automatic Copy-Paste Application)

This application provides the same functionality as the non-GUI script but includes a simple interface built with Tkinter. The user can start and stop the copying process by clicking on the "Start" and "Stop" buttons. Each copied text is automatically formatted and saved in a Word document in the background.

### Usage

- Start the Tkinter interface by running `python <filename.py>`.
- Click on the "Start" button in the interface. The application will save each copied text automatically to `automatic_paste.docx`.
- To stop the process, click the "Stop" button.

---

### Requirements

To run this project, ensure the following Python libraries are installed:
- `pyperclip`
- `python-docx`
- `tkinter` 

>included with the standard Python library
