# Chat with SQL Database using LangChain and Streamlit

This project is an interactive web application that allows users to chat with a SQL database (SQLite or MySQL) and retrieve data insights in a conversational way. Using LangChain agents, the app translates natural language queries into SQL, making database interactions simple and efficient.

## 🚀 Features
- **Supports Multiple Databases:** Choose between SQLite and MySQL.
- **Conversational Interface:** Chat directly with your database using natural language.
- **LangChain Integration:** Uses advanced AI agents to interpret and respond to queries.
- **Streamlit Web App:** Clean and user-friendly interface.
- **Dynamic MySQL Connection:** Connect to your own MySQL database by entering credentials.

## 🛠 Technologies Used
- **Python 3.9+**
- **Streamlit**: For building the web application.
- **LangChain**: For creating SQL query agents.
- **SQLite**: Lightweight local database.
- **MySQL**: Remote database support.
- **SQLAlchemy**: ORM for connecting databases.
- **ChatGroq (Llama3-8b-8192)**: LLM for natural language understanding.

## 💡 How It Works
1. **Choose a Database:**
   - SQLite (local)
   - MySQL (remote)
2. **For MySQL:** Enter host, user, password, and database name.
3. **Provide API Key:** For the Groq model.
4. **Start Chatting:** Ask questions and get real-time data from the database.

## 🖥️ Setup and Installation
```bash
# Clone the repository
git clone https://github.com/Aadi-stack/CHAT-SQL.git
cd CHAT-SQL

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

## 🧑‍💻 Usage
- Select the database you want to connect with.
- If MySQL is selected, provide the required credentials.
- Enter your Groq API key.
- Start querying your database in natural language.

## 🌐 Live Demo
Check out the live version of the project here: [Streamlit Web App](https://chat-sql-4kbce95ehwurkzbkrgjg6m.streamlit.app/)

## 📂 Project Structure
```
CHAT-SQL/
|-- app.py
|-- student.db
|-- requirements.txt
```

## 🤝 Contributing
Feel free to fork this repository, make changes, and submit a pull request. Suggestions and improvements are always welcome!


