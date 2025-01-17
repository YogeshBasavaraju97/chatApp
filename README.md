# Chat App Setup Instructions

## Prerequisites
Ensure you have the following installed:
- **Python**: Version 3.9 or later
- **Redis server**: For managing WebSocket connections
- **Virtual environment tool**: Such as `venv` or `virtualenv`

## Git Installation

### Clone the Repository

- git clone https://github.com/YogeshBasavaraju97/chatApp.git
- cd chatApp


## Create and Activate a Virtual Environment
-  python -m venv venv
-  source venv/bin/activate  # For macOS/Linux
- venv\Scripts\activate     # For Windows

## Install Dependencies
-  pip install -r requirements.txt




## Set Up Environment Variables Create a .env file in the project root and add the following variables:
 - SECRET_KEY=your-django-secret-key
 - DEBUG=True

## Apply Database Migrations
- python manage.py makemigration
-  python manage.py migrate

##  Create a Superuser
- python manage.py createsuperuser


Open your web browser and navigate to:

http://127.0.0.1:8000/
Log in with the superuser credentials or create a new user account.

Start a chat with another user or test the app's features.


Requirements
Below are the key dependencies for the project:

- **Django==5.1.2
- **channels==4.1.0
- **channels-redis==4.2.0
- **daphne==4.1.2
- **redis==5.2.0
- **Refer to the requirements.txt file for a complete list.