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

## Usage

1. Run the chatbot application:
   ```bash
   streamlit run src/app.py

2. Open your browser at the provided URL.

3. Enter your query in the input field and receive responses from the Ollama model. All queries and responses will be stored in MongoDB.

## Examples

### Example 1:
User Query: "What is the capital of France?"
Response: "The capital of France is Paris."

### Example 2:
User Query: "Explain quantum mechanics."
Response: "Quantum mechanics is a branch of physics that studies the behavior of matter and energy at the atomic level..."

## Project Structure
```bash
project-name/
│
├── README.md            # Documentation
├── requirements.txt     # Project dependencies
├── src/                 # Source code
│   ├── app.py           # Main Streamlit application
│
└── .gitignore           # Ignored files
```
## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
- Streamlit — for providing a simple web application framework.
- Ollama — for their powerful language model.
- MongoDB — for a reliable database solution.
