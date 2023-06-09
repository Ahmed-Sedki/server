# Reverse Shell Server

This repository contains code for a reverse shell server, which allows remote access to client systems. It receives a connection from the client, enabling execution of commands on the client's machine. This code is for demonstration and educational purposes and should be used responsibly.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

1. **Reliable Transmission**: The data sent and received using this server ensures reliability through the use of JSON for encoding and decoding.

2. **File Upload and Download**: The server can upload and download files to and from the client.

3. **Command Execution**: The server can execute shell commands on the client machine.

4. **Clear and Concise Console Output**: The console output is clear and concise, making it user-friendly.

## Installation

This script is written in Python. Therefore, Python should be installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

1. Clone this repository:
```bash
git clone https://github.com/Ahmed-Sedki/server.git
```
2. Navigate to the cloned repository:
```bash
cd server
```

## Usage

Replace `'192.168.1.12'` and `5555` in the `sock.bind(('192.168.1.12', 5555))` line with your server's IP address and port number, respectively.

To run the script, use the following command:

```bash
python server.py
```

The server will start listening for incoming connections. Once a client is connected, you can interact with the client's machine.

**Note**: This script should only be used for legal and ethical purposes. The creator of this script is not responsible for any misuse.

## Contributing

Contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
