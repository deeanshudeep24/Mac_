MAC Changer Program
Description:
This is a Python script for changing the MAC (Media Access Control) address of a network interface on Linux systems using the ifconfig command

Features:
Allows users to specify the interface and the new MAC address.
Verifies if the MAC address change was successful.
Provides feedback and instructions after the MAC address change.\

Prerequisites:
This program is intended for use on Linux systems.
Ensure Python3 is installed.

Usage
To use the MAC changer program, follow these steps:

Clone or download the repository to your local machine. Use the command git clone https://github.com/deeanshudeep24/Mac_address_changer.git
Open a terminal and navigate to the directory containing the script. cd  Mac_address_changer 
Run the script with the following command: 
python3 term_mac_change.py -i [INTERFACE] -m [NEW_MAC_ADDRESS]
Replace [INTERFACE] with the name of the network interface you want to change (e.g., eth0, wlan0) and [NEW_MAC_ADDRESS] with the desired MAC address.
Example:
python3 term_mac_change.py -i eth0 -m 00:11:22:33:44:55

Notes:
Ensure you have administrative privileges to execute the script.
The program may not work on all systems or interfaces. Test it on a non-critical system first.
Use it responsibly and ethically, respecting local laws and regulations.

Author:
This program was written by Deepanshu Deep.
