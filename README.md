Project Title: File Management GUI Application
Description
This project is a Python-based GUI application designed for basic file management tasks. It leverages the tkinter library to create an interactive interface where users can create, open, save, and manage text files. The application is user-friendly and provides essential features for handling text files directly within the GUI.

Features
* Create New File: Allows users to create a new text file and save it to a specified location.
* Open File: Enables users to browse and open an existing text file for viewing or editing.
* Save File: Facilitates saving changes made to the currently open file.
* File Listing: Displays a list of all files in a specified directory, making navigation easy.
* Error Handling: Includes robust mechanisms to handle exceptions and notify users with appropriate error messages.

Technologies Used
* Python: Programming language used for development.
* tkinter: Library used to create the graphical user interface.
* os: For interacting with the file system.
* tkinter.messagebox: For displaying notifications and error messages.
* tkinter.filedialog: For browsing and selecting files or directories.

How to Use
Prerequisites
Ensure Python 3.x is installed on your system. No additional libraries are required as tkinter is included with the standard Python distribution.
Steps to Run the Application
1. Clone or download the repository to your local machine.
2. Navigate to the project directory.
3. Run the script using the command: python TeamRasmalai_P1.py
4. 
5. Use the GUI to perform file management tasks:
    * Create a File: Click the "Create File" button to create a new file.
    * Open a File: Use the "Open File" button to browse and edit existing text files.
    * Save Changes: Save your changes by clicking the "Save File" button.
    * View Files: Use the file list section to browse files in a directory.

Project Structure
* Main Script: Contains the GUI logic and core functionality for file operations.
* Functions:
    * create_file(): Creates a new text file.
    * open_file(): Opens an existing text file for editing.
    * save_file(): Saves the current file.
    * update_file_list(): Refreshes the list of files displayed in the GUI.

Screenshots
(Add screenshots here to illustrate the GUI layout and functionalities.)

Future Enhancements
* Add support for additional file formats (e.g., .csv, .json).
* Implement a search functionality for files within a directory.
* Enhance the UI with modern styling (e.g., using ttk or custom themes).
* Provide support for dark mode.

Contribution
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
