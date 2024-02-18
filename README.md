# Your Own ChatGPT 🤖 using Langchain

This project allows you to create your own chatbot using Langchain OpenAI’s ChatGPT model. With a simple Streamlit interface, you can interact with the chatbot and see its responses, It also uses buffer memory to remember the previous conversation.

Prerequisites
Python 3.8 (specifically version 3.8 otherwise it would not work)
Install the required packages using pip:
```
pip install -r requirements.txt
```
## Getting Started

Clone this repository to your local machine.
Set up your OpenAI API key by creating a .env file in the project directory and adding your key:
`OPENAI_API_KEY=your_api_key_here`

Run the following command to start the Streamlit app:
```
streamlit run app.py
```
Your browser will automatically pop a tab and shows you the front-end of the application. Here you can interact with the application.
Type your message in the sidebar input field.

- The chatbot will respond with an AI-generated message.
- Conversations are displayed in the main window.

## Notes
The chatbot uses the ChatOpenAI model with a temperature setting of 0 (which makes it more deterministic).
The initial message history includes a system message (“You are a helpful assistant.”).
Feel free to customize and enhance this project to suit your needs! 😊
