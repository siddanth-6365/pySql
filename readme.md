# MySQL Python Chatbot with Groq, Mistral AI

Welcome to the GitHub repository for our tutorial on building a natural language SQL chatbot using Groq! This project guides you through the development of a chatbot that can interpret natural language queries, generate SQL queries, and fetch results from a SQL database, all in an intuitive and user-friendly way. It utilizes Streamlit GUI for an enhanced interaction experience.

🟡 This repository serves as supporting material for the [YouTube video tutorial](https://youtu.be/YqqRkuizNN4).

## Features
- **Natural Language Processing**: Uses Groq to interpret and respond to user queries in natural language.
- **SQL Query Generation**: Dynamically generates SQL queries based on the user's natural language input.
- **Database Interaction**: Connects to a SQL database to retrieve query results, demonstrating practical database interaction.
- **Streamlit GUI**: Features a user-friendly interface built with Streamlit, making it easy for users of all skill levels.
- **Python-based**: Entirely coded in Python, showcasing best practices in software development with modern technologies.

## Brief Explanation of How the Chatbot Works

The chatbot works by taking a user's natural language query, converting it into a SQL query using Groq, executing the query on a SQL database, and then presenting the results back to the user in natural language. This process involves several steps of data processing and interaction with the Groq API and a SQL database, all seamlessly integrated into a Streamlit application.

Consider the following diagram to understand how the different chains and components are built:

![Chatbot Architecture](./docs/mysql-chains.png)

For a more detailed explanation and a step-by-step guide, refer this other video: [YouTube video tutorial](https://youtu.be/9ccl1_Wu24Q).

For a more detailed explanation and a step-by-step guide, refer to the [YouTube video tutorial](Chat with MySQL Database with Python | LangChain Tutorial).

## Installation
Ensure you have Python installed on your machine. Then clone this repository:

## make sure to have a python virtual environment and then install the dependencies.
## refer `.env.example` for the environment variables, get the API keys from the following links:
- [Groq](https://console.groq.com/keys)

```bash
git clone [repository-link]
cd [repository-directory]
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Create your own .env file with the necessary variables, including your GROQ API key:

```bash
GROQ_API_KEY=[your-GROQ-api-key]
```

## Usage
To launch the Streamlit app and interact with the chatbot:

```bash
streamlit run app.py
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---
