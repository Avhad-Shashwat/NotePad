# Notepad Application

A simple Notepad application built using Java Swing. This application includes essential features like save, new, copy, paste, select all, and print options. Additionally, executable files (`.jar` and `.exe`) are provided for easy use.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Downloading the Project](#downloading-the-project)
  - [Running the Application](#running-the-application)
    - [Using the JAR File](#using-the-jar-file)
    - [Using the EXE File](#using-the-exe-file)
- [Usage](#usage)
- [Build Instructions](#build-instructions)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Contact](#contact)

## Features

- **New**: Create a new text document.
- **Save**: Save the current document.
- **Copy**: Copy selected text to clipboard.
- **Paste**: Paste text from clipboard.
- **Select All**: Select all text in the document.
- **Print**: Print the current document.

## Getting Started

### Prerequisites

To run the Notepad application, ensure you have the following installed on your system:

- **Java Runtime Environment (JRE)**: Required to run the `.jar` file.
- **Windows Operating System**: For running the `.exe` file.

### Downloading the Project

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Avhad-Shashwat/NotePad.git
    ```
    or download the ZIP file directly from GitHub and extract it.

2. **Navigate to the project directory**:
    ```sh
    cd NotePad
    ```

### Running the Application

#### Using the JAR File

1. **Ensure JRE is installed**:
    - Open a command prompt or terminal.
    - Check if Java is installed by running:
        ```sh
        java -version
        ```
    - If not installed, download and install from the [Java website](https://www.oracle.com/java/technologies/javase-jre8-downloads.html).

2. **Run the JAR file**:
    ```sh
    java -jar ShashwatNotepad.jar
    ```

#### Using the EXE File

1. **Ensure Windows OS is being used**.

2. **Run the EXE file**:
    - Double-click on `NotepadApp.exe` to start the application.

## Usage

Once the application is running, you can use the menu options or keyboard shortcuts to:

- Create a new document (`File` > `New` or `Ctrl+N`).
- Save the current document (`File` > `Save` or `Ctrl+S`).
- Copy text (`Edit` > `Copy` or `Ctrl+C`).
- Paste text (`Edit` > `Paste` or `Ctrl+V`).
- Select all text (`Edit` > `Select All` or `Ctrl+A`).
- Print the document (`File` > `Print` or `Ctrl+P`).

## Build Instructions

If you want to build the project from the source code:

1. **Ensure you have Java Development Kit (JDK) installed**:
    - Download and install from the [Java website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

2. **Compile the source code**:
    ```sh
    javac -d bin src/*.java
    ```

3. **Create the JAR file**:
    ```sh
    jar cfe ShashwatNotepad.jar MainClass -C bin .
    ```

## Troubleshooting

- **JAR file not running**: Ensure you have the correct version of JRE installed and that your `JAVA_HOME` environment variable is set correctly.
- **EXE file not running**: Make sure you have the necessary permissions to run the executable file on your Windows system.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Contact

For any inquiries or feedback, please reach out to [avhadshashwat@gmail.com](mailto:avhadshashwat@gmail.com).
