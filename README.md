📬 Gmail + Groq AI Chat Assistant
This is a lightweight project that connects to your Gmail, fetches recent emails, and allows you to ask questions about them using Groq’s DeepSeek LLM.
It’s built in Python using Jupyter Notebook with a simple UI powered by ipywidgets.

🔍 What It Does
Fetches email content from your Gmail account

Lets you ask AI questions about your latest email

Cleans and decodes email content

Uses Groq’s DeepSeek model to respond intelligently

Works entirely inside a Jupyter Notebook

🚀 How to Run
Clone this repository

Install dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Add your Gmail OAuth credentials:

Save as client_secret.json

Place in the root folder

Add your Groq API key in a .env file:

ini
Copy
Edit
GROQ_API_KEY=your_key_here
Start the notebook:

css
Copy
Edit
jupyter notebook main.ipynb
Authenticate Gmail and start chatting with AI about your inbox.

🛠 Tech Stack
Python

Gmail API

Groq LLM (DeepSeek)

Jupyter Notebook

ipywidgets

python-dotenv


👨‍💻 Author
Made with curiosity by Gopinath M
