# Nmap
task1
# Nmap Usage Guide


A brief description of what this project does and who it's for

## Overview
Nmap (Network Mapper) is an open-source tool for network exploration and security auditing.It helps in discovering hosts and services on a computer network by sending packets and analyzing the responses.

## Version Information
- *Nmap Version*: 7.97
- *Platform*: i686-pc-windows-windows
- *Compiled with*:
  - nmap-liblua version 5.4.7
  - openssl version 3.0.16
  - nmap-libssh2 version 1.11.1
  - nmap-libz version 1.3.1
  - nmap-libpcre2 version 10.45
  - Npcap version 1.82
  - nmap-libdnet version 1.18.0
- *Available nsock engines*: iocp, poll, select

## Scanning Example
### Syntax


## command Explanation
1. -sS: This option enables a TCP SYN scan, which is fast and stealthy.

2. <target_ip>: Replace with the target IP address (e.g., 192.168.231.223).

3. -oN <output_file>: This option allows you to save the scan results to a file in normal format.

## Output Interpretation
PORT: The port number that was scanned.

STATE: Indicates whether the port is open or closed.

SERVICE: The service running on the open port.

## API Reference




| Port | State     | Service               |
| :-------- | :------- | :------------------------- |
| 135/tcp | open | msrpc |
|  139/tcp| open  |  netbios-ssn|
|445/tcp  |open | microsoft-ds|
|2869/tcp | open  |icslap|
|3306/tcp| open|  mysql|
|7070/tcp| open|  realserver|




