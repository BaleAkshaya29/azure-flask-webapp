#  Azure Flask WebApp

A simple Flask web application built using Python and deployed on [Render.com](https://render.com/) as a cloud project for showcasing my cloud computing and DevOps skills.

##  Tech Stack

- Python 3
- Flask
- Gunicorn (for production-ready deployment)
- Render (for cloud hosting)
- Git & GitHub (for version control and CI/CD)

##  Features

- Minimal Flask web server with Jinja templating
- Render.com deployment with auto-deploy from GitHub
- Lightweight and beginner-friendly structure
- Demonstrates practical use of cloud-based web hosting

##  Project Structure

azure-flask-webapp/
├── app.py # Main Flask app file
├── requirements.txt # Python dependencies
├── render.yaml # Render deployment configuration (if used)
├── README.md # Project documentation
└── templates/
└── index.html # HTML template file

##  How to Deploy on Render

1. Clone this repo
2. Add a `requirements.txt` file
3. Use `gunicorn app:app` as the start command
4. Push to GitHub and connect your repo to Render

##  How to Run Locally

```bash
# Clone the repository
git clone https://github.com/BaleAkshaya29/azure-flask-webapp.git

cd azure-flask-webapp

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

Then open your browser and visit http://127.0.0.1:5000.

Live Deployment
This app is live and deployed via Render: https://azure-flask-webapp.onrender.com

Deployment Steps (Render.com)
Connect GitHub repository to Render.

Set Build Command:

nginx
Copy
Edit
pip install -r requirements.txt
Set Start Command:

nginx
Copy
Edit
gunicorn app:app
Choose Free Plan.

Enable auto-deploy from the master branch.

Learning Outcome
Practical cloud deployment without needing an Azure subscription

Confidence in working with real-world CI/CD and deployment workflows

Hands-on with version control, web development, and cloud hosting

License
This project is licensed under the MIT License.

Author
Akshaya Bale
https://github.com/BaleAkshaya29
1. Update Your README.md
Make your project look more polished on GitHub by including:

markdown
Copy
Edit

