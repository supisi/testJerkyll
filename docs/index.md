---
layout: default
---

# ISIQuiz

![](icon.ico)


## Overview

ISIQuiz is a secure examination application developed using AutoHotkey v2.0. It is designed to create a controlled environment for administering quizzes or exams by restricting internet access, monitoring system activity, and ensuring the integrity of the testing process.

## Features

- **User Authentication**: Prompts users to enter their name before starting the quiz.
- **Internet Control**: Disables network adapters to prevent online access during the exam.
- **Screenshot Capture**: Automatically takes screenshots at regular intervals to monitor activity.
- **Tray Menu Management**: Provides a system tray interface for easy access and exit options.
- **Recurring Task Setup**: Ensures the application runs continuously in the background.
- **Exam File Extraction**: Automatically extracts and sets up necessary exam files.
- **Exit Handling**: Cleans up system settings and deletes temporary files upon exit.

## Installation

1. **Requirements**:
   - [AutoHotkey v2.0](https://www.autohotkey.com/) installed on your system.

2. **Setup**:
   - Clone or download the repository to your desired location.
   - Ensure all included scripts (`funcs.ahk`, `utils_funcs.ahk`) are present in the same directory as `ISIQuiz.ahk`.
   - Run the `ISIQuiz.ahk` script using AutoHotkey v2.0.

## Usage

1. **Starting the Application**:
   - Double-click the `ISIQuiz.ahk` script to launch the application.
   - Enter your name in the prompted input box and click "OK" to begin the exam.

2. **During the Exam**:
   - Internet access will be disabled to ensure a secure testing environment.
   - Screenshots will be taken periodically to monitor activity.
   - Use the system tray menu to access the "Exit" option if necessary.

3. **Exiting the Application**:
   - Click "Exit" in the system tray menu.
   - Upon exit, internet access will be restored, and temporary files will be deleted.

## Configuration

- **Archive Settings**:
  - Configure archive names and passwords in the `isi_config.ini` file located in the `ISIConfig` directory.

- **USB Key**:
  - Set the authorized USB key ID in the `isi_config.ini` to allow safe exit upon detection.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Disclaimer

ISIQuiz is intended for authorized examination purposes only. Misuse of this application may lead to disciplinary actions.
