# LangGraph Chatbot

A conversational AI chatbot built using **LangGraph**, **LangChain**, and **Hugging Face**. The chatbot maintains conversation context, supports memory through checkpointing, and demonstrates graph-based workflow orchestration for LLM applications.

## Features

* AI-powered conversational chatbot
* Stateful conversations using LangGraph
* Persistent chat memory with SQLite
* Hugging Face LLM integration
* Modular and extensible architecture
* Optional LangSmith tracing and monitoring

## Technologies Used

* Python
* LangGraph
* LangChain
* Hugging Face
* SQLite


## Installation

### Clone the Repository

```bash
git clone https://github.com/yk47/LangGraph-Chatbot.git
cd LangGraph-Chatbot
```

### Create and Activate a Virtual Environment

```bash
python -m venv myenv
```

Windows:

```bash
myenv\Scripts\activate
```

Linux/macOS:

```bash
source myenv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Configuration

Create a `.env` file in the project root:

```env
HUGGINGFACEHUB_API_TOKEN=your_huggingface_token
LANGCHAIN_API_KEY=your_langsmith_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=LangGraph-Chatbot
```

## Run the Chatbot

```bash
streamlit run streamlit_frontend.py
```

## Example Conversation

```text
You: Hello

Bot: Hi! How can I assist you today?

You: What is LangGraph?

Bot: LangGraph is a framework for building stateful AI applications using graph-based workflows.
```

## Project Structure

```text
LangGraph-Chatbot/
│
├── app.py
├── requirements.txt
├── .env
├── chats.db
├── README.md
└── checkpoints/
```

## Learning Outcomes

This project demonstrates:

* Building chatbots with LangGraph
* Managing conversation state
* Integrating Hugging Face models
* Persisting chat history
* Creating graph-based AI workflows

## Author

Yash Karnik

GitHub: https://github.com/yk47


