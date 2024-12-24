# OS Detection Tool
A Python script to detect the operating system of a machine based on the TTL value
obtained via the `ping` command.
## Features
- Detects whether a machine is running **Linux** or **Windows** based on its TTL value.
- Validates user input for IP address format.
- Ensures the script is run with superuser privileges.
- Provides detailed error messages for better debugging.
## Usage
To use this tool, follow these steps:
1. Make sure you have Python 3 installed.
2. Run the script with the following command:
```bash
sudo python3 os-detection.py <IP_ADDRESS>
```
Replace `<IP_ADDRESS>` with the target IP.
## Example
```bash
$ sudo python3 os-detection.py 192.168.1.1
IP: 192.168.1.1 | TTL: 64 | Operating System: Linux
```
## Requirements
- Python 3.x
- Root privileges
- Access to the `ping` command on your system.
## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open a
pull request.
