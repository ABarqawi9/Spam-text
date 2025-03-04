# Message Spammer

## Table of Contents
- [Description](#description)
- [Features](#features)
- [How to Use](#how-to-use)
- [Customization](#customization)
- [Future Enhancements](#future-enhancements)

## Description
This Python script automates message sending using the `pyautogui` library. It reads text from a file (`message.txt`) and sends each line as a separate message. This can be useful for automated messaging or testing input fields.

## Features
- **Automated Typing:** The script types and sends each line from the text file.
- **Delay Mechanism:** A short delay before execution allows users to switch to the desired application (e.g., a chat window).
- **File-Based Input:** Messages are read from `message.txt`, making it easy to customize.

## How to Use
1. Open a text file (`message.txt`) and enter the messages, each on a new line.
2. Run the script using a Python interpreter.
3. Quickly switch to the target application (e.g., a chat window) within 4 seconds.
4. The script will automatically type and send each line from the file.

## Customization
You can modify the script to:
- **Change the delay time** by adjusting `time.sleep(4)`.
- **Modify the file path** if the text file is located elsewhere.
- **Change the key press behavior** by replacing `'enter'` with another key (e.g., `'tab'` or `'space'`).

## Future Enhancements
- **GUI Interface:** Add a simple UI to configure message delay and file selection.
- **Loop Control:** Allow users to send messages multiple times.
- **Safe Mode:** Implement a stop mechanism to prevent accidental excessive spamming.
- **Custom Keybinding:** Let users choose which key to press after each message.
