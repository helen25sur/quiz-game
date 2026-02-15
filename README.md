# Quiz Game (Python)

A simple console-based quiz game built with Python.  
The program asks multiple-choice or true/false questions and tracks the user's score.

This project was created as part of my Python learning journey and demonstrates basic object-oriented programming and program structure.

---

## Features

- Question and answer logic
- Score tracking
- Object-oriented structure
- Separate modules for data, logic, and models
- Console interaction

---

## Project Structure

  ```quiz-game/
  │
  ├── main.py # Entry point of the program
  ├── data.py # Question data
  ├── question_model.py # Question class
  ├── quiz_brain.py # Quiz logic and game flow
  └── README.md
```

---

## How It Works

1. Questions are stored in `data.py`
2. Each question is converted into a Question object
3. `QuizBrain` controls the game logic
4. The user answers questions in the console
5. The final score is displayed at the end

---

## How to Run

Make sure you have Python installed (Python 3 recommended).

Run the game:

```bash
python main.py
```


## Learning Goals
This project demonstrates:

  - Python modules and imports

  - Classes and objects

  - Separation of concerns

  - Basic CLI interaction

  - Program flow control
