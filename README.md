🧠 Conversational Chatbot with Groq & LangChain

A mini-project demonstrating AI conversational memory, multi-session chat history, and context-aware responses using Groq Llama 3.1, LangChain’s message history utilities, and dynamic prompt templates.

This notebook shows how to build a chatbot that remembers the user, maintains separate chat sessions, and responds based on previous interactions — just like a real AI assistant.

🚀 Features

🔄 Persistent chat memory using ChatMessageHistory

🗂 Multi-session conversations (session_id based memory)

⚙️ RunnableWithMessageHistory for automatic history injection

🧩 Custom system prompts with ChatPromptTemplate

⚡ Groq Llama 3.1 (8B Instant) for fast inference

🧠 Context-aware responses based on previous messages

🔗 LCEL chaining (prompt → model)

📂 Project Structure
conversational-chatbot/
│── conversational_chatbot.ipynb
│── .env.example
│── requirements.txt
│── README.md
│── .gitignore

🔧 Setup Instructions
1️⃣ Create and fill your .env file:
GROQ_API_KEY=your_groq_api_key_here


(Don’t worry — .env is ignored through .gitignore)

2️⃣ Install the required packages
pip install -r requirements.txt

3️⃣ Run the notebook
jupyter notebook


Open: conversational_chatbot.ipynb

🧪 Example Capabilities
✔ Remembers your name across messages in a session
✔ Forgets your name when a new session_id starts
✔ Responds in different languages when instructed
✔ Maintains structured conversation history automatically
🧠 Tech Stack

Python

LangChain Core

LangChain Groq

RunnableWithMessageHistory

ChatMessageHistory

Groq Llama 3.1

dotenv

🔑 Environment Variables

Included in .env.example:

GROQ_API_KEY=your_groq_api_key_here


👨‍💻 Author

Shehjad Patel
AI Developer | LLMs • LangChain • Groq • Ollama