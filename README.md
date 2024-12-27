# Fake Virus Scripts

This repository contains two harmless scripts that simulate a "virus" for fun purposes only. These scripts are meant for educational and entertainment purposes and do not cause any harm to the system. They simply open multiple windows or display humorous messages.

## Files Included

### 1. `virusfake.bat`
- **Platform**: Windows
- **Description**: This batch script opens multiple command prompt windows continuously, displaying a humorous message.
- **Usage**:
  1. Save the script as `virusfake.bat`.
  2. Double-click the file to run it on a Windows system.
  3. Stop the script by opening Task Manager (`Ctrl + Shift + Esc`) and ending all Command Prompt tasks.

- **Code Example**:
  ```bat
  @echo off
  title Virus Giả Lập Vui
  :loop
  start cmd /c "echo Ahihi bạn bị hack rồiiii & pause"
  goto loop
  ```

### 2. `virusfake.sh`
- **Platform**: Linux / macOS
- **Description**: This Bash script opens multiple terminal windows continuously, displaying a humorous message.
- **Usage**:
  1. Save the script as `virusfake.sh`.
  2. Grant execution permissions using:
     ```bash
     chmod +x virusfake.sh
     ```
  3. Run the script:
     ```bash
     ./virusfake.sh
     ```
  4. Stop the script by pressing `Ctrl + C` in the terminal or using a system monitor to kill all terminal processes.

- **Code Example**:
  ```bash
  #!/bin/bash
  while true; do
      gnome-terminal -- bash -c "echo 'Ahihi bạn bị hack rồiiii!'; sleep 3"
  done
  ```

## Disclaimer
- These scripts are purely for fun and should only be executed on your personal system.
- Do not use these scripts on someone else’s system without their explicit permission.
- Misusing these scripts may result in unintended consequences or breaches of ethical guidelines.

## License
This project is licensed under the MIT License. Feel free to modify and share it responsibly!
