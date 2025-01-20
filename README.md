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

Some Screenshots for the project:

![WhatsApp Image 2025-01-20 at 10 24 32 PM](https://github.com/user-attachments/assets/114d2f3d-884d-4d4a-8608-4690c0d6b507)


![WhatsApp Image 2025-01-20 at 10 24 33 PM (1)](https://github.com/user-attachments/assets/695fe6df-4857-457a-9185-e36088343f6b)


![WhatsApp Image 2025-01-20 at 10 24 32 PM (1)](https://github.com/user-attachments/assets/bdca6824-68f0-4574-956d-adafb6341b46)


![WhatsApp Image 2025-01-20 at 10 24 33 PM](https://github.com/user-attachments/assets/08019822-a553-42d9-a66a-19f8694870ee)


![WhatsApp Image 2025-01-20 at 10 24 35 PM](https://github.com/user-attachments/assets/0884b2dc-eab7-462f-ab20-4ec23370ff3c)


![WhatsApp Image 2025-01-20 at 10 24 34 PM](https://github.com/user-attachments/assets/6302423f-e4ab-4737-a533-c90f2360f6e5)


![WhatsApp Image 2025-01-20 at 10 24 34 PM (1)](https://github.com/user-attachments/assets/8cb293c6-cc37-44b0-a8df-1afdf3089560)


![WhatsApp Image 2025-01-20 at 10 24 35 PM (1)](https://github.com/user-attachments/assets/e43dd11f-3162-4d98-90ae-a93cfb32d2a2)


![WhatsApp Image 2025-01-20 at 10 24 33 PM (2)](https://github.com/user-attachments/assets/eca411b9-3673-4fe3-8c3c-21a9fafe096e)


![WhatsApp Image 2025-01-20 at 10 24 35 PM (2)](https://github.com/user-attachments/assets/f42f69da-b05f-4f8f-addc-946f189e15fd)


![WhatsApp Image 2025-01-20 at 10 24 34 PM (2)](https://github.com/user-attachments/assets/6a8bed75-e8f0-4234-8a22-d63d91b4b635)

