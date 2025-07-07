📬 Gmail + Groq AI Chat Assistant
This is a personal side project I built that combines Gmail, AI, and a bit of clever UI using Jupyter Notebook widgets.

The idea is simple:

"What if I could ask questions about my emails like I'm chatting with an AI?"

So I built it — this project connects to your Gmail inbox, fetches real email content, and lets you chat with Groq’s DeepSeek model to understand, summarize, or ask anything about those emails.

It’s like ChatGPT for Gmail — but lightweight, private, and fully in your control.

✨ What it Can Do
🔍 Search your Gmail using natural language (with AI help)

📬 Fetch actual email subjects and content

🧹 Clean & decode raw email data into plain readable text

💬 Ask Groq anything about the latest email (e.g., “What’s the summary?” or “Is this urgent?”)

🧠 Uses DeepSeek LLM from Groq via their blazing-fast API

🧰 Simple Jupyter Notebook UI using ipywidgets

💻 Tech Stack
Python (of course)

Gmail API (OAuth2-based)

Groq API (DeepSeek model)

Jupyter Notebook

ipywidgets for input/output chat flow

dotenv for secret handling

🚀 How to Run It (for real)
1. Clone the repo
bash
Copy
Edit
git clone https://github.com/Gopinathm07/gmail-ai-chatbot.git
cd gmail-ai-chatbot
2. Install the dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Add your Gmail client secret
Create OAuth credentials from Google Cloud

Download the client_secret.json

Place it in the root folder

4. Add your Groq API Key
Create a .env file

Add this inside:

ini
Copy
Edit
GROQ_API_KEY=your_groq_key_here
Make sure you have:

bash
Copy
Edit
pip install python-dotenv
5. Run the Notebook
bash
Copy
Edit
jupyter notebook main.ipynb
It’ll authenticate your Gmail, fetch recent emails, and open up a chat input where you can ask AI about what’s in your inbox.
