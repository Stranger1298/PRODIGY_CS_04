## Keylogger 

This Python script utilizes the `pynput` library to create a simple keylogger. It captures key presses and logs them to a file named `keylog.txt`.

### Requirements
- Python 3.x
- `pynput` library (can be installed via `pip install pynput`)

### How to Use
1. Install the required libraries by running `pip install pynput`.
2. Copy the provided code into a Python file (e.g., `keylogger.py`).
3. Run the script with Python (`python keylogger.py`).
4. The keylogger will start capturing key presses immediately.
5. To stop the keylogger, press `Ctrl + C`.
6. The logged keys will be saved to a file named `keylog.txt`.

### Handling Exceptions
- The script includes error handling to catch exceptions that may occur during key logging.
- If there are errors during key logging, such as failure to retrieve the character corresponding to a key press, an error message will be printed to the console, and the script will continue running.

### Notes
- This script captures all key presses, including special keys like function keys and modifier keys (e.g., Shift, Alt).
- The logged keys are stored in plain text format in `keylog.txt`.
- Be aware of legal implications before using this script, as capturing keystrokes without consent may be illegal in certain jurisdictions.

### Troubleshooting
- If the script doesn't run, ensure that Python is installed and the `pynput` library is correctly installed.
- If there are errors during execution, check the console output for any error messages.
- If encountering issues, refer to the documentation of `pynput` for additional support.
