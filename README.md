## Chat-with-your-code

This project is a chatbot for your github repo that allows users to interact with their repo using the OpenAI Large Language Model (LLM). It uuses a Streamlit app to provide a user-friendly chat interface.

### Features
Users can enter their OpenAI key and the name of their GitHub repository.
The repository is then cloned, chunked and embedded. Langchain is used to build a QA retriever so users can chat with their code. 
The chat interface allows users to ask questions and interact with the codebase.
Usage

To use this codebase chatbot, follow these steps:

1. Clone the repository:

```git clone https://github.com/Arnab-m1/chat-with-codebase.git```

2. Install the required dependencies:

```pip install -r requirements.txt```

3. Set your environment variables in the `.env` file
* Get your OpenAI API Key and add it here
* Set up a free account on [Deeplake](https://www.deeplake.ai) and store the API key 

3. Run the Streamlit app:

```streamlit run main.py```


Access the chat interface by opening your web browser and navigating to http://localhost:8501.

Enter your OpenAI key and the name of your GitHub repository in the provided input fields.

The codebase will be chunked and embedded, and the chat interface will be displayed.

Ask questions or provide instructions using natural language, and the chatbot will respond accordingly.

### Future Improvements
* Integrate with external tools and services to provide more advanced codebase analysis and insights.

### Acknowledgements
This project was inspired by the power of OpenAI's Language Models, Langchain and the need for a more interactive and user-friendly codebase analysis tool.


