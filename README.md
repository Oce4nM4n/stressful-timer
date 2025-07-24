# Question Timer Application
=====================================

A simple command-line based application that helps you track the time spent on each question.

## Features
------------

*   Starts and stops the timer using the spacebar key.
*   Automatically logs the elapsed time to a CSV file (`Question-Log.csv`).
*   Allows you to mark each question as correct or incorrect (yes/no/n/a).

## Usage
-----

### Prerequisites
-------------------

Make sure you have Python 3 installed on your system.

### Installation
---------------

1.  Run `pip3 install -r requirements.txt` in the terminal to install the required packages.
2.  Navigate to the project directory using the command `cd /path/to/project/directory`.

### Running the Application
---------------------------

To start the timer application, run the following command:

```bash
python3 main.py
```

## Controls
------------

*   **Spacebar**: Toggles the timer on and off. Pressing it again indicates you've finished a question.
*   **q**: Quits the application.

## Logging
---------

The elapsed time for each question is automatically logged to `Question-Log.csv`. You can view this file by opening it in any CSV editor or spreadsheet software.

### Example Log File Format
---------------------------

| Question | Time | Correct |
| --- | --- | --- |
| 1         | 30                    | yes                |
