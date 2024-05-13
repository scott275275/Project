Project ReadMe

How to run the program

1 - Ensure you have Python installed on your system.  You can download Python from python.org

2 - Install the required packages by running the following command:  pip install tk

3 - Download the 'Project.py' file.

4 - Open a terminal or command prompt in the directory where 'Project.py' is located

5 - Run the program using the following command:  python Project.py Project_credentials.csv PA3_patient.txt


Description

The Project is a Python program that provides a graphical interface for managing patients, visits, and key statistics in a hospital setting.  It includes functionalities for user authentication, role-based access control, data loading from extern files, logging user actions, and generating key statistics reports.

Important Information

User Roles - The system supports different user roles such as admin, clinician, nurse, and management.  Each role has specific functionalities and access permissions within the system.

Data Loading - The program loads user credentials from a CSV file ('Project_credentials.csv') and patient data from a text file('PA3_patient.txt').  Ensure that these files are formatted correctly to avoid errors during data loading.

Graphical Interface - The program utilizes the Tkinter library for creating a graphical user interface (GUI).  The GUI provides a user-friendly way to interact with the system's functionalities.

Logging - User actions, including login attempts and successful operations, are logged to a log file for auditing purposes.

Generating Statistics - Users with the "management" role can generate key statistics reports.  These reports include trends in insurance types, races, genders, and ethnicities among patients.


Feel free to reach out if you encounter any issues or have questions about using the Project.

Thank you for taking the time to test the project.

https://github.com/scott275275/Project.git
