# Hospital Management System

The Hospital Management System is a Python-based application that provides an interactive graphical interface for managing patient records, including data on medications, admission, discharge dates, and necessary precautions. This system is built using the tkinter library for GUI, with data stored locally in a JSON file for ease of use and persistence.

## Features

Add Patient Records: Easily add patient details, including name, medication, admission and discharge dates, and specific precautions.

Delete Records: Select and delete patient records as needed.

View Patient Records: Display a list of all added records in a structured, sortable format using a tree view.

## Installation

To install and run the application, make sure you have Python 3 installed. You’ll need the following Python libraries, most of which are built-in:

tkinter: For creating the GUI.
uuid: For generating unique IDs for each patient record.
datetime: For handling dates.

```bash
pip install tkinter
```

## Usage
To run the application, execute the guiproject.py script:
```python
python guiproject.py
```

## User Interface

Add Patient Record: Enter details in the input fields and click Add Record to save patient information.

Delete Selected: Select a record from the list and click Delete Selected to remove it.

Patient Records List: View all patient records in a structured table with columns for each detail.

Example Code Snippet
Here’s a quick overview of how to add a patient record programmatically:
```bash
# Add a new patient record
name = "John Doe"
medicine = "Paracetamol"
admit_date = "15-10-2024"
discharge_date = "20-10-2024"
precaution = "Take rest and drink fluids"
```
# Data Storage
Patient records are stored in patient_records.json in the same directory as the application, enabling data persistence. You can delete this file to reset all records.
# File Structure
```bash
HospitalManagementSystem/
├── guiproject.py                # Main application code
└── patient_records.json         # JSON file storing patient records
```
# Output

![Output](https://github.com/user-attachments/assets/c75f9c59-d923-4252-bfaa-403975a671ba)
