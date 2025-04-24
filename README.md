**Port-scanner**
A port scanner in bash script is a program that uses the bash shell to scan ports on a target IP address. In addition to identifying if a system is online and which ports are open, port scanners can also identify the applications listening to particular ports and the operating system of the host. It checks for open ports in the range from 1 to 65535 and prints a message if a port is open.

**To use this Port Scanner**
Clone this repository to your local machine:
sudo git clone https:https://github.com/AaronSVarghese/bashport
cd port-scanner/
Make sure you have execute permissions for the script:
sudo chmod +x port_scanner.sh
**Usage**
./port-scanner.sh [IP]
Example:
Bash-Script port_scanner.sh 192.168.1.1
