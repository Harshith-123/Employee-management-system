Employee Management System
Overview
The Employee Management System is a desktop application built using Python and Tkinter. It enables you to manage employee records and leave entries, visualize data with graphs, and maintain CSV-based databases for employee details and leave records. The system supports adding, editing, and deleting employee information as well as processing leave applications.

Features
Employee Management:

Add new employee records.

Edit existing employee details.

Delete employee records.

Leave Management:

Record leave applications.

Calculate leave balances.

Display leave details.

Data Visualization:

Generate pie, bar, line, and scatter charts using Matplotlib.

CSV-Based Storage:

Employee data is saved in empmanage.csv.

Leave records are maintained in leaves.csv.

Monthly attendance data is stored in 2020-21.csv.

Technologies Used
Programming Language: Python 3.x

GUI Library: Tkinter

Data Handling: Pandas, CSV module

Data Visualization: Matplotlib

Numerical Operations: NumPy

Date & Time: datetime, calendar

Prerequisites
Before running the application, ensure you have the following installed:

Python 3.x:
Download from python.org.
Note: Tkinter is bundled with most Python installations. For Linux, you might need to install it separately (e.g., using sudo apt-get install python3-tk).

Required Python Packages:
Install the following packages using pip:

bash
Copy
pip install pandas matplotlib numpy
The standard libraries (tkinter, csv, datetime, and calendar) are included with Python.

Installation & Setup
Clone the Repository:

bash
Copy
git clone git@github.com:Harshith-123/Employee-management-system.git
cd Employee-management-system
Project Files:

Main Script: ELMS_CSV.py
This is the primary file that launches the application.

CSV Files:

empmanage.csv – Employee details (will be created automatically if not present).

leaves.csv – Leave records (will be created automatically if not present).

2020-21.csv – Monthly data (will be created automatically if not present).

(Optional) Create a Virtual Environment:

bash
Copy
python -m venv venv
Activate the virtual environment:

Windows:

bash
Copy
venv\Scripts\activate
macOS/Linux:

bash
Copy
source venv/bin/activate
Running the Application
You can run the application using your terminal or via Visual Studio Code:

Using the Terminal
Open your terminal in the project directory.

Run the main script:

bash
Copy
python ELMS_CSV.py
Using Visual Studio Code
Open the Project Folder:
Open VS Code and load the Employee Management System project folder.

Run the Application:

Open the integrated terminal (Ctrl+` ).

Run:

bash
Copy
python ELMS_CSV.py
Alternatively, set up a VS Code launch configuration to run and debug the application.

Usage Instructions
Launch the Application:
Running the application opens a GUI window with the title "Employee Management System".

Navigate the Interface:

Home Page:
Contains buttons to access the employee management section.

Employee Management:

Use the provided buttons to add, edit, or remove employee records.

Fill out the form fields to enter employee details such as ID, name, designation, date of joining, qualifications, experience, salary, Aadhaar number, and PAN card details.

Leave Management:

Navigate to the leave management section (if implemented) to process leave applications.

The system calculates the number of days, leave entitlement, leaves availed, and balance.

Data Visualization:

Generate different types of charts (pie, bar, line, scatter) to visualize employee data and leave details.

Saving & Loading Data:

The application uses CSV files to save data automatically.

If the CSV files (empmanage.csv, leaves.csv, and 2020-21.csv) are not present, the application creates them with the appropriate headers.

Troubleshooting
Tkinter Issues:
Ensure that Tkinter is properly installed. On Linux systems, you may need to install it separately.

Module Not Found Errors:
Verify that all required packages (pandas, matplotlib, numpy) are installed. Use pip install as mentioned in the prerequisites.

CSV File Issues:
If you experience errors related to CSV files, check the file permissions and ensure that the files are not open in another program.

Contributing
Contributions are welcome! If you’d like to contribute to this project:

Fork the repository.

Create a feature branch:

bash
Copy
git checkout -b feature/YourFeature
Commit your changes:

bash
Copy
git commit -am 'Add new feature'
Push to your branch:

bash
Copy
git push origin feature/YourFeature
Open a Pull Request and describe your changes.
