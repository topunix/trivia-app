# Full Stack Trivia App

![trivia](https://user-images.githubusercontent.com/833824/82157851-df0a7980-9851-11ea-8b0d-a79c7763789d.jpg)

## Introduction

Udacitrivia is a fun trivia app that can be used for team-building activities.

This trivia app offers the following features:

1. **Question Display**: Users can view trivia questions categorized by topic, with the option to display the question, category, difficulty, and hide/show the answer.
2. **Question Management**: Questions can be added or deleted, with each new question requiring both the question and its corresponding answer text.
3. **Search Functionality**: A search feature allows users to find questions based on specific text queries.
4. **Game Mode**: Users can play a quiz game where questions are randomized either from all categories or from a specific category, adding a fun and engaging element to the experience.

## About the Stack

### Backend

The `./backend` directory contains a Flask and SQLAlchemy server. The app.py file defines the endpoints and references models.py for the DB and SQLAlchemy setup. 

### Frontend

The `./frontend` directory contains a complete React frontend to consume the data from the Flask server. 

[View the README.md within ./frontend for more details.](./frontend/README.md)
