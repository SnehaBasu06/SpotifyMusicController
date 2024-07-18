# Music Controller Web App

Welcome to the Music Controller Web App! This application allows users to create and join music rooms where they can collaboratively control music playback.



## Features

- Create a new music room with customizable settings.
- Join an existing music room using a unique room code.
- Control music playback collaboratively with friends.

## Technologies Used

- **Frontend**: React, Material-UI
- **Backend**: Django, Django REST framework
- **Database**: SQLite (default), can be configured to use other databases
- **API**: Spotify Web API for music playback

## Setup Instructions

 
 
# Backend Setup:
Create a virtual environment and activate it:
python3 -m venv env
source env/bin/activate   
# On Windows use `env\Scripts\activate`
# Install backend dependencies:
pip install -r requirements.txt
# Run migrations:
python manage.py migrate
# Start the Django server:
python manage.py runserver
# Frontend Setup:
Navigate to the frontend directory:
cd frontend
# Install frontend dependencies:
npm install
# Start the React development server:
npm dev

