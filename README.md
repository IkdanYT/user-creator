# Instant User Creator for Linux

This repository contains a script that allows you to create a user with password and root privileges on a Linux system. It has been tested and is compatible with several popular Linux distributions including Ubuntu, Alpine, Debian and CentOS.

## Warning

Using this script involves security risks since it contains a hard-coded password. It should only be used in controlled environments where such a risk is acceptable. Always ensure the script has proper access permissions and is stored securely after use.

## Usage

To use the script, follow these steps:

1. Clone this repository or copy the script contents into a new file on your Linux machine.
2. Give the script execution permissions using the command: `chmod +x create.sh`.
3. Run the script to create a user. If necessary, use `sudo` to run as another user.

Curl:
```bash
bash <(curl -s https://raw.githubusercontent.com/IkdanYT/user-creator/main/create.sh)
```
Wget:
```bash
wget https://raw.githubusercontent.com/IkdanYT/user-creator/main/create.sh && chmod +x create.sh && ./create.sh
```
