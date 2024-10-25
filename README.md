# Rule-Engine
 This project implements a simple 3-tier rule engine application using Flask, SQLAlchemy, and SQLite. It allows for the creation, combination, and evaluation of rules based on Abstract Syntax Trees (ASTs). The application is designed to efficiently manage and evaluate complex rule sets by representing rules in a structured and interpretable format

 ## Features
- User-friendly interface for entering rules
- Dynamic display of the generated AST
- Error handling for invalid rule input

## Components

1. Backend :  main.py (Flask Python SQLAlchemy)
2. Frontend : rlg.py (Tkinter UI Python)


## Setup

1. Install the required dependencies:
   ```bash
   pip install flask sqlalchemy
   
2. Clone the Repository
   ```bash
   
   
   

Run the Flask application:
```bash
python ui.py

python app.py

## Design Choices
Flask: Chosen for its simplicity and flexibility, making it ideal for quick web application development.
SQLite: Used as the database for its lightweight nature and ease of setup.
Docker: Utilized for containerization, ensuring a consistent development environment across different machines.
Future Enhancements
Attribute Validation: Implement validation for rule attributes to enhance robustness.
User-Defined Functions: Allow users to define custom functions for more complex rule processing.


