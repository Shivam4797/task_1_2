TASK_1 

XML to Excel Converter
This code is an XML to Excel converter that allows you to convert an XML file to an Excel file. It is designed to extract data of SHORT-NAME, DEFINATION-REF of the containers and sub-containers of the arxml file. It uses tkinter to create a simple GUI for selecting the input XML file and specifying the output Excel file location.

Installation
To use this code, please follow the steps below:

Clone this repository using git clone https://github.com/username/repo.git or download the source code as a zip file and extract it to your local machine.
The file is packed with all dependencies.
Run the code by executing the main file Xml_Handler/xml_handler.exe
Usage
The xml_to_excel.py script can be run from the command line with the following optional arguments:

-xml or --xml_path: The path of the input XML file.
-xlsx or --excel_path: The path of the output Excel file.
Alternatively, you can run the code using the GUI interface by running the xml_handler_gui.py file.

When running the GUI interface, you can select the input XML file and output Excel file location using the Browse buttons. Once you have selected the files, click the Convert button to start the conversion process. You can view the progress of the conversion using the progress bar.

If you need help, you can click the ? button to open a help window with more information about the code.

Logging
This code uses Python's built-in logging module to log events and errors. By default, log messages are saved to a file called xml_to_excel.log in the same directory as the main file. You can also view log messages in the console if you set the logging level to DEBUG.

Features 
Converts an XML file to an Excel file.
Provides a GUI for selecting the input XML file and specifying the output Excel file path.
Supports browsing and selecting the input XML file using the file dialog.
Supports browsing and selecting the output Excel file path using the file dialog.
Uses the pandas module for converting the XML data to a pandas DataFrame and then saving it as an Excel file.
Provides a command line interface for using the script.
Provides a progress bar for indicating the progress of the conversion process.
Provides a help button for displaying information about the script.
Logs messages to both a file and the console.
Provides detailed error messages in case of any exceptions or errors.

TASK_2

String Converter GUI and CLI
This is a Python GUI and CLI application that converts a string of at least 3 words into a new string where the first letter of each word and every alternate letter is capitalized. The application is built using the tkinter library.

Prerequisites
Python 3.7.9
tkinter module (usually comes pre-installed with Python)
The executable is packed with all executables
Usage
To use the application, simply run the following command in your terminal:
CLI Mode
run exe with -i , --input "Hi i am shivam", This takes the string in inverted commas.
The application window will open. Enter a string of at least 3 words in the input box and click the "Convert" button. The converted string will be displayed in the output box.

If you need help, click the "?" button in the bottom right corner to display a help message.

Functionality
The application contains the following components:

A title label
An input box for the user to enter a string
A "Convert" button to convert the string
A "?" button to display help
An output box to display the converted string
If the user enters an invalid input (empty input or a string with less than 3 words), an error message will be displayed. If the input is valid, the application will convert the input string and display the converted string in the output box.

The application also logs all successful and failed conversion attempts in a file named "string_converter.log".

License
This code is released under the MIT License.
