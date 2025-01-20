# Watch E-Commerce Website

## Introduction

This is a *Watch E-Commerce Website* built using *Flask*, a Python web framework. The website allows users to browse, search, and purchase watches online. It includes features such as authentication, product management, and a shopping cart.

## Features

- User authentication (Login/Signup/Logout)
- Admin panel for managing products
- Product listing and detail pages
- Shopping cart functionality
- Secure checkout process
- Responsive design

## Technologies Used

- *Backend:* Flask, Flask-SQLAlchemy, Flask-Login
- *Frontend:* HTML, CSS, JavaScript, Bootstrap
- *Database:* SQLite / MySQL (Configurable)

## Installation

1. *Clone the Repository*
bash
 git clone https://github.com//NayanSharmra/WATCH-E-commerce-website
 cd watch-ecommerce


2. *Create a Virtual Environment*
bash
 python -m venv venv
 source venv/bin/activate  # On Windows use `venv\Scripts\activate`


3. *Install Dependencies*
bash
 pip install -r requirements.txt


4. *Set Up Environment Variables*
Create a .env file and add:
ini
 FLASK_APP=app.py
 FLASK_ENV=development
 SECRET_KEY=your_secret_key_here
 DATABASE_URL=sqlite:///site.db  # Change for production


5. *Initialize the Database*
bash
 flask db init
 flask db migrate -m "Initial migration."
 flask db upgrade


6. *Run the Application*
bash
 flask run


7. *Access the Website*
Open a browser and go to: [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Project Structure

watch-ecommerce/
│-- app.py
│-- database.py
│-- model.py
│-- templates/
│-- static/
│-- venv/
│-- .env
│-- requirements.txt
│-- README.md


## Deployment

1. *Configure Production Settings* (Update config.py for production)
2. *Use Gunicorn (For Linux Hosting)*
bash
 gunicorn -w 4 -b 0.0.0.0:8000 app:app

3. *Deploy on Platforms like Heroku, AWS, or Digital Ocean*

## Contributing
Feel free to contribute by creating issues or submitting pull requests.

## License
This project is licensed under the MIT License.
