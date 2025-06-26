# Simple Calendar Application – Capgemini Assignment

## Project Overview

This project is a lightweight calendar and appointment scheduling tool built using Python in Jupyter Notebook. The goal is to allow users to manage events with a focus on simplicity, time zone handling, and file-based data storage. The application meets all specified requirements using only core Python and Jupyter widgets—no external frameworks or databases.

---

## 1. Approach and Design

The project is designed with clarity and usability in mind, using an object-oriented Python structure and a Jupyter Notebook interface. Two main classes drive the logic:

- **Event Class**: Represents individual events with a title, start time, and end time.
- **CalendarApp Class**: Manages the list of events with methods to add, delete, view events, and suggest available time slots.

The interface is built using `ipywidgets` to allow user-friendly interaction with forms, dropdowns, and buttons directly within a notebook environment.

Key design decisions include:
- File-based JSON storage instead of a database, making the solution lightweight and portable.
- Time zone selection and AM/PM formatting for real-world usability.
- Automatic input validation to prevent overlapping events.

---

## 2. Key Files and Folders


- **Calendar.ipynb**: Contains all code, user interface, and interactive widgets.
- **Calendar_App_Presentation.pptx**: Gives a visual walkthrough of the project’s structure, approach, and features.

---

## 3. Process to Run, Test, and Verify

### How to Run:
1. Open the `Calendar.ipynb` file using **Jupyter Notebook** or **Google Colab**.
2. Run all cells to initialize the UI.
3. Enter event details (title, date, start time, end time, timezone) and use the buttons to interact with the app.

### How to Test:
- Use the “Add Event” button to create new events.
- Use the “View Events” and “Remaining Today” buttons to list scheduled events.
- Use the “Next Slot” and “All Free Slots” buttons to check available time ranges.
- Use the “Delete Event” button to remove events.

The system provides live feedback in the notebook and stores all data automatically in the `calendar.json` file.

---

## 4. Test Data and Seed Data

- The application automatically generates and updates the `calendar.json` file upon usage.
- Test events can be added manually using the form in the notebook.
- The file persists data across sessions, allowing you to close and reopen the app with saved events intact.

If you wish to pre-load test events, you can insert them into the `calendar.json` file before running the notebook. The structure is simple and readable, allowing easy editing if needed.

---

## Summary

This project satisfies all the requirements of the Capgemini programming assignment:

- Allows adding, deleting, and viewing events
- Prevents time overlaps
- Suggests available time slots
- Supports AM/PM input and time zone selection
- Uses local file storage instead of a database
- Built with pure Python and Jupyter widgets
- Comes with documentation and presentation

---

**Author**: Keerthana Vemuganti  
**Submitted for**: Capgemini Programming Assignment – 2025
