ID Card Eligibility Checker
This is a simple Python GUI application built using Tkinter that checks if a person is eligible for an ID card based on their age and document availability.

Features
Enter your age.

Confirm if you have the required documents (yes/no).

Click a button to check eligibility.

Displays:

Eligibility status (Eligible / Not Eligible).

Additional messages depending on age or missing documents.

Requirements
Python 3.x

Tkinter (comes pre-installed with Python standard library)

How to Run
Clone the repository or download the id_card_checker.py file.

Open a terminal (or command prompt) and navigate to the project directory.

Run the following command:

bash
Copy
Edit
python id_card_checker.py
This will launch the GUI window.

Application Flow
Eligible:
If the person is between 18 and 60 years old and has the required documents.

Not Eligible:

If the person is younger than 18, the app shows how many years are left.

If the person is older than 60, the app shows how many years over the limit they are.

If the person doesn't have the required documents, it displays a relevant message.

Invalid Input:
If the entered age is not a number, an error message is shown.

Screenshots

Input	Result
Age: 18
Documents: yes	Eligible: "You are just eligible!"
Age: 16
Documents: yes	Not Eligible: "You are 2 years too young."
Age: 65
Documents: yes	Not Eligible: "You are 5 years above the limit."
Age: 20
Documents: no	Not Eligible: "You don't have required documents."
Code Structure
IdCardChecker class:

Initializes the Tkinter window and its widgets.

Handles user input and checks eligibility.

check_eligibility method:

Core logic to validate age and document status.

run method:

Runs the Tkinter main loop.
License
This project is licensed under the MIT License.
