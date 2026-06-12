# 🧠 Quizzler App

A GUI-based quiz application built with Python and Tkinter that allows users to answer True/False questions while tracking their score in real time.

## Features

* Interactive graphical user interface using Tkinter
* True/False question format
* Score tracking
* Instant feedback for answers
* Question management using Object-Oriented Programming
* Clean and user-friendly interface
* Modular project structure

## Project Structure

```text
QuizzlerApp/
│
├── images/
│   ├── true.png
│   ├── false.png
│   └── ...
│
├── OutputScreenshots/
│
├── data.py
├── question_model.py
├── quiz_brain.py
├── ui.py
├── main.py
└── README.md
```

## Technologies Used

* Python 3
* Tkinter
* Object-Oriented Programming (OOP)

## Components

### data.py

Stores the quiz question data.

### question_model.py

Defines the Question class used to create question objects.

### quiz_brain.py

Handles quiz logic, score calculation, question progression, and answer checking.

### ui.py

Manages the graphical user interface and user interactions.

### main.py

Entry point of the application that launches the quiz.

## How It Works

1. Quiz questions are loaded from the data source.
2. Questions are displayed one at a time.
3. Users answer using the True or False buttons.
4. The application validates the answer.
5. Feedback is displayed immediately.
6. The score updates automatically.
7. The quiz ends after all questions have been answered.

## Concepts Practiced

* Classes and Objects
* Encapsulation
* Modular Programming
* GUI Development with Tkinter
* Event Handling
* Application State Management

## Run the Project

```bash
python main.py
```

## Screenshots

Screenshots of the application can be found in the `OutputScreenshots` folder.

## Learning Outcome

This project helped me gain hands-on experience with Python GUI development, event-driven programming, and Object-Oriented Programming principles while building a complete desktop application.

## Project Source

Developed as part of a Python Bootcamp course and recreated for learning and portfolio development.
