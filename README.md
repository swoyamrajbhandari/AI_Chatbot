#AI_Chatbot

A simple interactive chatbot powered by OpenAI's GPT-3.5 API.  
The chatbot has a quirky personality: it identifies as an egg named **Rufus** and loves to tell jokes. Users can interact with it through the terminal.

---

## Features

- Chat with a humorous AI character with a defined personality.
- Continuously maintains conversation context.
- Runs entirely in the terminal (Node.js required).

---

## Requirements

- Node.js (v16 or higher recommended)
- OpenAI API Key

---

## Installation / Setup

1. **Clone the repository**:

```bash
git clone https://github.com/YOUR_USERNAME/AI_Chatbot.git
cd AI_Chatbot
All necessary packages are already included in node_modules, so you do not need to run npm install.

Set up environment variables:

Create a .env file in the root of the project:

bash
Copy code
cp .env.example .env   # Linux/Mac
copy .env.example .env # Windows
Open .env and add your OpenAI API key:

ini
Copy code
OPENAI_SECRET_KEY=your_openai_api_key_here
Important: Keep .env private. Never share your API key publicly.

Run the chatbot:

bash
Copy code
npm run dev
You will be prompted in the terminal to type messages. The AI will respond and maintain the conversation.

Project Structure
perl
Copy code
AI_Chatbot/
│
├─ index.js            # Main chatbot script
├─ package.json        # Project metadata and dependencies
├─ package-lock.json   # Dependency lock file
├─ node_modules/       # All required Node.js packages
├─ .env.example        # Example environment variables (safe to share)
├─ .gitignore          # Ignored files for Git (e.g., .env)
└─ README.md           # This file
Notes
The chatbot requires a valid OpenAI API key to function. You can obtain one from OpenAI.

Even though node_modules is included, you can still update or add packages using npm install <package>.

Feel free to modify the chatbot’s personality by editing the context variable in index.js.

