Port Scanner in Python

Overview
This Python script is a simple port scanner that checks whether specific ports are open or closed on a target machine. The script uses the socket library to attempt to connect to ports and determine their status.



Features :
Scan Specific Ports: You can specify the number of ports to scan.
Port Status Output: The script will output whether a port is open or closed.


Port Scanner in Python
Overview
This Python script is a simple port scanner that checks whether specific ports are open or closed on a target machine. The script uses the socket library to attempt to connect to ports and determine their status.

Features :
Scan Specific Ports: You can specify the number of ports to scan.
Port Status Output: The script will output whether a port is open or closed.
How It Works
Socket Connection:
The script creates a socket connection to each port of the target machine.
Timeout Handling:
It checks for timeout or errors to determine if the port is closed.
User Input:
The user is prompted to enter a target IP address and the number of ports to scan.

License
This project is licensed under the MIT License.


