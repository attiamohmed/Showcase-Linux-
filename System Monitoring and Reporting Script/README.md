# System Info Report Script for Linux

This Bash script collects system information, examines CPU load, memory utilization, and disk usage, records the report to "system_info_report.log," creates an archive file, and displays a menu for user interaction.

## Description

This script is designed to run on Linux systems and provides the following functionality:

- Gathers system information, including hostname, operating system, kernel version, CPU information, total memory, and disk usage.
- Logs the system report to "system_info_report.log" for reference.
- Checks CPU load, memory usage, and disk usage and displays warnings if they exceed predefined thresholds.
- Creates a compressed archive ("system_info_report.tar.gz") of the log file for easy storage and sharing.
- Offers a user-friendly menu for user interaction and script execution.

## Usage

To use this script on your Linux system, follow these steps:

1. Clone this repository to your local machine or download the script file.

2. Make sure you have the necessary permissions to execute the script. You can set it using the `chmod` command:
   ```bash
   chmod +x system_info_report.sh
3. Open a terminal and navigate to the directory where the script is located.
4. Run the script using the following command:
   ./system_info_report.sh
5. You will be presented with a menu containing options to generate a system report, create an archive, or exit the script.
6. Follow the prompts and make selections based on your needs.

## Contributing
Contributions are welcome! If you have any suggestions or improvements for this script, feel free to open an issue or create a pull request.

## Author
Mohamed Attia
