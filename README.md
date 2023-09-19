# AutoMessageSpammer
License: MIT License

## Description
 This Python script is a simple automation tool designed to send a series of predefined messages from a text file using PyAutoGUI.
 Whether you want to automate sending messages or simulate user interactions, this script can help you achieve your goal.

## Features
- Message Automation: Simulate typing and sending messages from a text file.
- Customizable Delay: Adjust the initial delay to focus on the target chat or input field.
- Abort Functionality: Stop the script by moving the mouse cursor to a corner of the screen.
- Easy to Use: A straightforward script for automating text input tasks.

## How to Use
1. Create a text file named `message.txt` and populate it with the messages you want to send. Each line in the file will be treated as a separate message.

   Example `message.txt`:

2. Run the `AutoMessageSpammer.py` script using a Python interpreter.

3. After a specified initial delay (4 seconds by default), the script will start typing and sending messages from the `message.txt` file to the active chat or input field.

4. To stop the script at any time, quickly move your mouse cursor to one of the screen's corners within the defined abort timeout (5 seconds by default).

## Customization
You can customize the script by adjusting the following parameters in the `AutoMessageSpammer.py` file:

- `time.sleep(4)`: Change the initial delay to give you time to focus on the target chat or input field.

- `text = open('ayh\message.txt')`: Modify the file path to point to your desired message file.

- `pyautogui.FAILSAFE = 5`: Adjust the abort timeout to stop the script by moving the mouse cursor to a corner of the screen.

## Future Enhancements
While this script serves its basic purpose, there are opportunities for future enhancements, such as:

- **Message Formatting:** Allow for more advanced message formatting.
- **User-Friendly Configuration:** Implement a user-friendly configuration file for easy customization.
- **Logging:** Add logging functionality to track sent messages.
- **Error Handling:** Enhance error handling for better resilience.

## Contributing
Contributions to this project are welcome! If you encounter issues, have suggestions for improvement, or would like to add new features, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. For more details, please see the [LICENSE](LICENSE) file.
