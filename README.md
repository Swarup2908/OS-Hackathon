
# **File Management GUI Application**

### **Description**
This project is a Python-based **Graphical User Interface (GUI)** application designed for performing basic file management tasks. Leveraging the power of the **tkinter** library, it offers an interactive interface where users can easily **create**, **open**, **save**, and **manage text files**. The application is designed to be intuitive, user-friendly, and effective for handling essential file operations directly within the GUI.

---

## **Features**
- **Create New File**: Create a new text file and save it to a specified location.
- **Open File**: Browse and open an existing text file for viewing or editing.
- **Save File**: Save changes made to the currently opened file.
- **File Listing**: Display a list of all files in a specified directory for easy navigation.
- **Error Handling**: Robust exception handling with user-friendly notifications.

---

## **Technologies Used**
- **Python**: Core programming language.
- **tkinter**: Library for designing the graphical interface.
- **os**: Module for interacting with the file system.
- **tkinter.messagebox**: Provides pop-up notifications and error messages.
- **tkinter.filedialog**: Enables browsing and selecting files or directories.

---

## **How to Use**
### **Prerequisites**
- Python 3.x installed on your system (tkinter is included with the standard Python distribution). 
- No additional libraries required.

### **Steps to Run the Application**
1. Clone or download the repository to your local machine.
2. Navigate to the project directory.
3. Run the script using the following command:

   ```bash
   python TeamRasmalai_P1.py
   ```

4. Use the GUI to perform file management tasks:
   - **Create a File**: Click the **"Create File"** button to create a new file.
   - **Open a File**: Use the **"Open File"** button to browse and edit existing text files.
   - **Save Changes**: Save changes by clicking the **"Save File"** button.
   - **View Files**: Browse files in a directory using the file list section.

---

## **Project Structure**
- **Main Script**: Contains the GUI logic and core functionality for file operations.
- **Key Functions**:
  - `create_file()`: Creates a new text file.
  - `open_file()`: Opens an existing text file for editing.
  - `save_file()`: Saves the current file.
  - `update_file_list()`: Refreshes the list of files displayed in the GUI.

---

## **Screenshots**
(*Add screenshots here to visually illustrate the GUI layout and functionalities.*)

---

## **Future Enhancements**
1. **Support for additional file formats** (e.g., `.csv`, `.json`).
2. **Search functionality** to locate files within a directory.
3. **Modern UI styling** using `ttk` or custom themes.
4. **Dark Mode** support for better user experience.

---

## **Contribution**
We welcome contributions! Please follow these steps to contribute:
1. Fork the repository.
2. Make your improvements.
3. Submit a pull request with a detailed explanation of your changes.

---

## **License**
This project is licensed under the **MIT License**. For more details, see the [LICENSE](LICENSE) file.

---