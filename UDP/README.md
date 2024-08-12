# Netcat UDP Command Example

This section describes the usage and purpose of the command `nc -u 127.0.0.1 5500` using `netcat`, a versatile networking utility.

## Overview

`netcat` (often abbreviated as `nc`) is a powerful networking tool capable of reading from and writing to network connections using the TCP or UDP protocols. It is commonly used for tasks such as port scanning, transferring files, and network debugging.

The command `nc -u 127.0.0.1 5500` is used to establish a connection to a specific network address and port using the UDP protocol.

## Command Breakdown

- `nc`: This is the command for netcat, the tool being utilized.

- `-u`: This option specifies that the UDP protocol should be used. By default, netcat uses TCP, but with the `-u` flag, the connection will be established using UDP.

- `127.0.0.1`: This is the IP address of the target host. `127.0.0.1` is the loopback address, which refers to the local machine. It is commonly used for testing and development purposes.

- `5500`: This is the port number to which netcat will connect on the target host. Port numbers range from 0 to 65535, and in this command, `5500` is the specified port.

## Usage

To use this command, open a terminal and enter:

```bash
nc -u 127.0.0.1 5500
```
