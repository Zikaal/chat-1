# Chatbot with Ollama and MongoDB Integration

## Description
This project is a browser-based chatbot application powered by the Ollama LLM. It allows users to interact conversationally while storing all queries and responses in MongoDB for efficient retrieval and management.

---

## Features
- Browser-based chat functionality using Streamlit.
- Integration with the **Ollama** large language model.
- Storage of user queries and responses in **MongoDB**.
- Modular and extensible codebase for future enhancements.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- **Ollama LLM** installed locally 
- A running instance of **MongoDB** 

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/project-name.git
   cd project-name

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate      # macOS/Linux
   venv\Scripts\activate         # Windows

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Configure environment variables:
Create a .env file in the root directory and add the following:
   ```arduino
   OLLAMA_API_URL=http://localhost:11434
   MONGODB_URI=mongodb://localhost:27017

5. Ensure that Ollama and MongoDB are running:
Start the Ollama server:
   ```bash
   ollama serve
Verify that MongoDB is running on the specified URI.

