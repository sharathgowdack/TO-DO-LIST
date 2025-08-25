# To-Do List App ✅

This is a small **Flask web app** where you can add and manage your daily tasks.  
I built it as a beginner project to practice Python and Flask.

---

## Features
- Add tasks  
- Mark tasks as done  
- Delete tasks  
- Tasks are saved in a database (they won’t disappear when the server restarts)  

---

## How to run
1. Clone this repo  
   ```bash
   git clone https://github.com/sharathgowdack/TO-DO-LIST.git
   cd TO-DO-LIST
   
2.Create and activate a virtual environment

python -m venv .venv
.venv\Scripts\activate   # On Windows
# or
source .venv/bin/activate   # On Mac/Linux


3.Install the requirements

pip install -r requirements.txt


4.Run the app

  python app.py


5.Open in your browser → http://127.0.0.1:5000

Project files
app.py          # Flask backend
templates/      # HTML pages
static/         # CSS styles
tasks.db        # Database
requirements.txt


