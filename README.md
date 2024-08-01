# UDP DoS Script

## Overview

`UDP-DoS-Script` is a Perl script designed to simulate UDP network traffic for educational and research purposes.

**IMPORTANT:** This tool is intended for use in a controlled environment and must only be used on networks and systems for which you have explicit authorization.

## Features

- Sends UDP packets to a specified IP and port.
- Can operate on a specific port or random ports.
- Allows for the specification of the duration of the simulation.

## Prerequisites

- **Perl**: Ensure you have Perl installed on your system. You can check this by running `perl -v` in your terminal.
- **Network Access**: Permission to test against the target network or system.

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/scoxfield/UDP-DoS-Script.git
cd UDP-DoS-Script
```

## Usage

Run the script with the required arguments:

```bash
perl scoxfield.pl <target_ip> <target_port> <duration>
```

## Arguments

`<target_ip>`: The IP address of the target machine (e.g., 192.168.1.10).

`<target_port>`: The target port number (e.g., 80). Use 0 for random ports.

`<duration>`: Duration in seconds to run the simulation (e.g., 30). Use 0 to run indefinitely until manually stopped.

#Example
```bash
perl scoxfield.pl 192.168.1.10 80 30
```

This command sends UDP packets to the IP 192.168.1.10 on port 80 for 30 seconds.

## Important Considerations
Authorization Required: Ensure you have explicit permission to use this script on the target system.
Legal Compliance: Use of this tool must comply with applicable laws and regulations in your area.
Network Impact: This script can generate significant traffic; use it responsibly and monitor network performance.

## Disclaimer
This script is provided "as is" for educational and research purposes only. The authors and contributors disclaim all warranties and shall not be liable for any damages arising from its use. Users assume all responsibility and risk.

## Disclaimer of Liability
No Warranty: The authors and contributors disclaim all warranties, including but not limited to warranties of merchantability, fitness for a particular purpose, and non-infringement.
Assumption of Risk: Users assume all responsibility and risk for the use of this script. The authors and contributors shall not be liable for any damages arising from its use.
No Support: The script is provided without support, maintenance, or updates. Use it at your own risk.
