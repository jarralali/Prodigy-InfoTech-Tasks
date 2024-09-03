# Pentest Keylogger

Pentest Keylogger is an advanced GUI-based keylogger designed for educational and ethical penetration testing purposes. It captures keystrokes in real-time and logs them to a file while providing a user-friendly interface to start, stop, and monitor the keylogging process.
Features

    Real-time Keystroke Logging: Captures and displays keystrokes in real-time within the GUI.
    Full-Screen GUI: A user-friendly full-screen interface with the project title "Pentest Keylogger".
    Start/Stop Logging: Allows users to start and stop the keylogger directly from the GUI.
    Log File Management: Saves the logged keystrokes to a timestamped file in a designated directory.
    Minimize and Exit Options: Ability to minimize the application to the system tray or exit gracefully.

# Requirements

    Python 3.6+
    pynput library for capturing keystrokes
    tkinter for the graphical user interface

# Installing Dependencies

You can install the required dependencies using pip:
pip install pynput

# Setup and Usage

    Clone the Repository:


# Run the Application:

# Execute the following command to start the keylogger:


    python keylogger_gui.py

   # Using the Application:
        The GUI will open in full screen with the title "Pentest Keylogger".
        Click "Start Keylogger" to begin capturing keystrokes.
        The keystrokes will be displayed in the text area in real-time and saved to a log file in the files directory.
        Click "Stop Keylogger" to stop the logging.
        Use the "Minimize" button to minimize the application, and the "Exit" button to close the application.

   # Log File Location:

    The keystrokes are saved in the files directory with a filename format of keylog_YYYYMMDD_HHMMSS.txt (e.g., keylog_20240903_153012.txt).

# Ethical Considerations

# Important: This keylogger is intended for ethical use only. It should only be used in environments where you have explicit permission to monitor keystrokes, such as your own devices or for authorized penetration testing purposes. Unauthorized use of keyloggers can be illegal and unethical. Always obtain proper consent before deploying this software.
Disclaimer

The developers of this software are not responsible for any misuse or illegal activity carried out using this keylogger. Use it responsibly and ethically.
