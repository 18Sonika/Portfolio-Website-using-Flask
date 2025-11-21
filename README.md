Portfolio Website using Flask

A simple and clean personal portfolio website built using Python, Flask, HTML, and CSS.
The website consists of multiple pages such as Home, About, and Contact, with a working contact form and structured Flask routing.
This mini-project is ideal for beginners learning web development with Flask.

🚀 Features

🔥 Flask-based backend

🎨 Clean and responsive HTML/CSS design

📄 Pages:

Home Page

About Page

Contact Page (with POST form handling)

✉️ Contact form that prints user messages to the console

🧩 Uses Flask templates and static files

🗂️ Easy-to-understand folder structure

📁 Project Structure
portfolio_flask/
│── app.py
│── static/
│     └── style.css
└── templates/
      ├── index.html
      ├── about.html
      └── contact.html

🛠️ Technologies Used
Technology	Purpose
Python	Backend logic
Flask	Routing + Template Rendering
HTML	Page structure
CSS	Styling
Jinja2	Template engine used by Flask
⚙️ How to Run the Project Locally
1️⃣ Clone the repository
git clone https://github.com/your-username/portfolio_flask.git

2️⃣ Navigate into the folder
cd portfolio_flask

3️⃣ Install Flask
pip install flask

4️⃣ Run the Flask app
python app.py

5️⃣ Open in browser
http://127.0.0.1:5000/

📌 Flask Routing (app.py Overview)

/ → Home page

/about → About page

/contact → Contact page (supports GET & POST)

On submitting the contact form, user details (name, email, message) will be printed in the terminal/console.

🎯 Learning Outcomes

By completing this project, you will learn:

How to set up Flask project structure

How to create routes in Flask

How to render HTML templates

How to handle GET and POST requests

How to connect templates with backend logic

How to use static files (CSS)

🏁 Conclusion

This portfolio website is a beginner-friendly mini web app built with Flask.
It is simple, clean, and easily customizable for showcasing your personal details, skills, and projects.
