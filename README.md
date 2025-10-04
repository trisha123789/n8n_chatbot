# n8n_chatbot
Basic n8n Chatbot 🤖

This is a very simple chatbot built using n8n
.
It listens for incoming messages via a webhook and responds with predefined replies.

🚀 Features



Predefined responses for "Hello" and "Bye"

Default fallback message for unknown inputs

Can be easily extended with more keywords or AI integrations

📦 Requirements

n8n
 (self-hosted or cloud)

⚙️ Setup

Open your n8n dashboard.

Go to Workflows → Import → Paste JSON.

Paste the chatbot JSON provided in this repo.

Save and activate the workflow.

▶️ Usage


Request Body:

{ "message": "Hello" }


Responses:

"Hello" → "Hi there! 👋 How can I help you today?"

"Bye" → "Goodbye! 👋 Have a great day!"

Anything else → "Sorry, I didn’t understand that. 🤔"

🔮 Next Steps

Add more keywords & responses

Connect to Slack/Telegram/Discord

Add AI (OpenAI, Gemini, etc.) for smart replies

👉 Super lightweight, great for beginners learning n8n automation.
