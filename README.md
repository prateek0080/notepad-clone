# Java Notepad Clone

A simple Notepad clone built using Java Swing that replicates basic text editing functionality similar to Microsoft Windows Notepad.

## Features

* Create new text documents
* Open existing .txt files
* Save documents as .txt files
* Print documents
* Basic text editing operations (Copy, Cut, Paste, Select All)
* Modern GUI with menu bar
* About window with system information
* Keyboard shortcuts for all operations

## Requirements

* Java Development Kit (JDK) 8 or higher
* Java Runtime Environment (JRE)

## Project Structure

```
notepad/
├── icons/
│   ├── notepad.png
│   └── windows.png
├── Notepad.java
└── About.java
```

## Installation & Setup

1. Clone this repository:
```bash
git clone [your-repository-url]
```

2. Navigate to the project directory:
```bash
cd notepad
```

3. Compile the Java files:
```bash
javac *.java
```

4. Run the application:
```bash
java notepad.Notepad
```

## Usage

### Menu Options

#### File
* New (Ctrl + N): Create a new document
* Open (Ctrl + O): Open an existing .txt file
* Save (Ctrl + S): Save the current document
* Print (Ctrl + P): Print the current document
* Exit (Ctrl + Esc): Close the application

#### Edit
* Copy (Ctrl + C): Copy selected text
* Paste (Ctrl + V): Paste copied text
* Cut (Ctrl + X): Cut selected text
* Select All (Ctrl + A): Select entire document

#### Help
* About: Display information about the application

### Additional Features

* Line wrap functionality
* Scrollable text area
* File type filtering (only .txt files)
* Modern GUI with Windows-style icons

## Technical Details

* Built using Java Swing framework
* Implements ActionListener for event handling
* Uses JFileChooser for file operations
* Supports custom window icons
* Implements scrollable JTextArea with line wrap

