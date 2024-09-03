# Network Analyzer

Network Analyzer is a Python-based GUI application that captures and analyzes network packets. It displays real-time information such as source and destination IP addresses, hostnames, protocols, and more. The tool allows users to filter network traffic by specific protocols like TCP, UDP, and ICMP.

## Features

- **Real-Time Packet Capture**: Captures ongoing network traffic and displays it in a user-friendly table format.
- **Protocol Filtering**: Users can filter the captured packets based on specific protocols (TCP, UDP, ICMP) or choose to capture all protocols.
- **Hostname Resolution**: Automatically resolves and displays the hostname corresponding to the source and destination IP addresses.
- **Full-Screen Mode**: The application runs in full-screen mode for better visibility and usability.
- **User-Friendly GUI**: Built with `tkinter`, the application provides a simple and intuitive graphical interface.

## Requirements

- Python 3.x
- `scapy` library
- `tkinter` (included with most Python installations)

## Installation

1. **Clone the repository**:
  
# Install the required Python libraries:


    pip install scapy

# Usage

  Run the application:

  sudo python3 pentestanalyzer.py

  Note: Root privileges are required to capture network packets.

  Select the protocol:
        Choose the desired protocol from the drop-down menu at the top of the GUI (e.g., TCP, UDP, ICMP, or ALL).

  Start capturing packets:
        Click the "Start Capture" button to begin capturing and analyzing network traffic.

  View captured packets:
        The table will display the source and destination IP addresses, hostnames, and protocol for each captured packet in real-time.
