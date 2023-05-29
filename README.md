# Exercise Tracker

This is a simple application to track exercises and participants.

## Features

- Add participants and assign them a UUID
- Add exercises (name, duration, date) and assign them to a participant
- View total exercise duration for a participant

## Endpoints

### `/api/participants`

- `POST` Add a participant
- `GET` Get all participants

### `/api/participants/<id>`

- `GET` Get a participant by ID

### `/api/exercises`

- `POST` Add an exercise
- `GET` Get all exercises

### `/api/participants/<id>/logs`

- `GET` Get exercise logs for a given participant ID

## Running

- Install dependencies: `npm install` 
- Run the app: `npm start` 
- App runs on port `3000`
