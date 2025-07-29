🤖 Flask-Chatbot

A web-based chatbot built using **Python 3.6**, **Flask**, and **ChatterBot**. This project demonstrates a simple chatbot interface powered by machine learning for conversational responses, served via a web application.

---

## 🧠 Tech Stack

- Python 3.6  
- Flask==0.11  
- ChatterBot==0.8.4  
- SQLAlchemy==1.1.11  

---

## 🌐 Project Overview

This project implements a **web interface** for ChatterBot using the **Flask** framework. The chatbot is trained using a basic corpus and can respond to general conversations typed into a simple web UI.

---

## 🛠️ Local Setup

Follow the steps below to run the chatbot locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flask-chatbot.git
   cd flask-chatbot

    Install the required packages:

pip install -r requirements.txt

Train the chatbot:

python train.py

Start the Flask server:

python run.py

Open your browser and navigate to:

    http://localhost:5000/

📂 Project Structure

flask-chatbot/
├── static/           # Static files (CSS, JS)
├── templates/        # HTML templates
├── train.py          # Training script for chatbot
├── run.py            # Flask app runner
├── requirements.txt  # Python dependencies
├── README.md         # Project documentation

📄 License

This source code is free to use. However, ChatterBot itself has its own license, which still applies. You can find it in the LICENSE file or on the official ChatterBot GitHub repository.
