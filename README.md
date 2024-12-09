# Task Logger Application

The Task Logger is a Python-based desktop application that allows users to log their tasks periodically. It displays a popup every 30 minutes, prompting the user to input their current task, which is then recorded in an Excel file for later reference.

## Features
- **Automated Task Prompt:** Displays a popup every 30 minutes.
- **Excel Logging:** Logs tasks into an Excel file (`task_log.xlsx`), organized by date and time.
- **Simple UI:** Easy-to-use interface with clear prompts.
- **Efficient Tracking:** Automatically creates and manages a structured Excel file.

## Requirements
- Python 3.7 or later
- Required Python libraries:
  - `tkinter` (pre-installed with Python)
  - `openpyxl`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/task-logger.git

2. Navigate to the project directory:
`cd task-logger`

3. Install dependencies:
`pip install openpyxl`


## Usage
Run the application:

Using the Python script: `python popup_task_logger.py`
Using the provided batch file: Double-click on `Task Logs Start.bat` (Windows users only).

A popup will appear every 30 minutes, prompting you to input your task. Enter your task and click "OK" to save it.

Tasks are saved in the task_log.xlsx file in the same directory. The file is organized by date and time slots (in 30-minute intervals).

## File Structure
`popup_task_logger.py`: Main application script.
`Task Logs Start.bat`: Windows batch file for easy script execution.
`task_log.xlsx`: Excel file created automatically to store logged tasks.

## Customization
- Modify the time interval for popups by changing the time.sleep(60*30) line in the popup_task_logger.py script. 
- For example: `time.sleep(60*15)  # Popup every 15 minutes`
- Change the Excel file name by updating the EXCEL_FILE variable.

  ## Contributing
Feel free to fork the repository, create issues, or submit pull requests to improve the project.

## License
This project is licensed under the MIT License.

 
---

### HOW_TO_USE.md

# How to Use the Task Logger Application

Follow these steps to set up and use the Task Logger application:

## Prerequisites
- Ensure Python 3.7 or later is installed on your system.
- Install the required Python library:
  ```bash
  pip install openpyxl```

## Running the Application

1. Using Python Script:
 - Open your terminal or command prompt.
 - Navigate to the project directory.
 - Execute the script using:
 - `python popup_task_logger.py`

2. Using Batch File (Windows):
  - Double-click on the `Task Logs Start.bat` file to run the application.

## Logging Tasks
- A popup will appear every 30 minutes prompting you to input your current task.
- Enter your task in the input box and click "OK".
- A confirmation message will appear once your task is saved.

## Accessing Task Logs
- Open the task_log.xlsx file in the project directory to view logged tasks.
- The Excel file is structured as follows:
- The first row contains time slots (e.g., 00:00, 00:30, ...).
- The first column contains dates (e.g., 2024-12-09).
- Logged tasks are stored in the corresponding date and time slot cell.
















