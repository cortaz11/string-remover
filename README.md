# String Remover (strm.py)

A simple GUI tool to remove or overwrite strings in the memory of a running process using its PID, address, and length. Built with PyQt5 and pymem.

## Features
- Remove/overwrite memory at a given address in a process
- Easy input for PID, address, and length

## Requirements
- Python 3.7+
- [PyQt5](https://pypi.org/project/PyQt5/)
- [pymem](https://pypi.org/project/pymem/)

## Installation
1. Install Python 3.7 or newer from [python.org](https://www.python.org/downloads/).
2. Install dependencies

## How to Use
1. Run the script:
   ```bash
   python strm.py
   ```
2. In the GUI:
   - **PID**: Enter the process ID of the target process (decimal or hex, e.g., `1234` or `0x4d2`).
   - **Address**: Enter the memory address to overwrite (decimal or hex, e.g., `0x7FFDE000`).
   - **Length**: Enter the number of bytes to overwrite (e.g., `10`).
3. Click **Remove** to perform the operation. The tool will attempt to overwrite the specified memory region with zero bytes.

(Windows only)
