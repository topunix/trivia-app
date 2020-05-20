# Full Stack Trivia

![trivia](https://user-images.githubusercontent.com/833824/82157851-df0a7980-9851-11ea-8b0d-a79c7763789d.jpg)

## Introduction

Udacity is invested in creating bonding experiences for its employees and students. A bunch of team members got the idea to hold trivia on a regular basis and created a webpage to manage the trivia app and play the game.

The full stack trivia application must:

1) Display questions - both all questions and by category. Questions should show the question, category and difficulty rating by default and can show/hide the answer. 
2) Delete questions.
3) Add questions and require that they include question and answer text.
4) Search for questions based on a text query string.
5) Play the quiz game, randomizing either all questions or within a specific category. 

This trivia app will give you the ability to structure plan, implement, and test an API - skills essential for enabling applications to communicate with others. 

## About the Stack

### Backend

The `./backend` directory contains a Flask and SQLAlchemy server. The app.py file defines the endpoints and references models.py for the DB and SQLAlchemy setup. 

### Frontend

The `./frontend` directory contains a complete React frontend to consume the data from the Flask server. 

Pay special attention to the data the frontend is expecting from each API response to help you understand how to format your API. 

[View the README.md within ./frontend for more details.](./frontend/README.md)
