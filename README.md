# Flask GitHub Actions Demo

This is a simple **Python Flask** project created for learning **GitHub Actions**.

##  Project Goal
- Create a **basic Flask app**
- Run a **GitHub Actions Workflow** to:
  - Install dependencies
  - Test that Flask is installed correctly

##  Run Locally
1. Install **Python 3.11**
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
Run the application:

python app.py


Open your browser and visit:

http://127.0.0.1:5000

🟢 GitHub Actions

Workflow file location:

.github/workflows/python-ci.yml


Triggers on every push to the main branch

Workflow steps:

Checkout code

Setup Python

Install dependencies using pip

Run a simple test to verify Flask installation
