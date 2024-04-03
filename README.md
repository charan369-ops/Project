# Project :  Port Scanner 

Introduction:
This is a simple Python3 port scanner designed to scan for open ports on a given IP address. It accepts port ranges to search for and can be executed both as a standalone script or through a command-line interface.

Features:

Scans for open ports on a specified IP address.
Accepts port ranges to search for.
Command-line interface for ease of use.
Usage:

1) Standalone Script:
   Build the executable using Pyinstaller: pyinstaller --onefile PortScan.py.
   Execute the generated executable.
2) Command-Line Interface (CLI):
   Run the script using Python3:
objective : python3 PortScan-CLI.py IP_ADDRESS START_PORT END_PORT
Environment variables can be used to shorten the command as desired.

3) To Do:
GUI implementation.
Support for scanning based on hostnames.

Acknowledgments:
Thanks to the Python community for providing valuable resources and support.
Portions of the code may have been inspired by or adapted from various online tutorials, forums, and documentation.
