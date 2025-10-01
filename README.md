# AI Agent Summarizer

An AI-powered research assistant built with LangChain + OpenAI API.
It takes any topic/question from the terminal, fetches information from tools (search, Wikipedia, file saving), and outputs a structured summary including sources and tools used.

## ✨ Features
- Summarizes any topic or question entered in the terminal.
- Uses LangChain agents for tool usage.
- Supports OpenAI GPT-4o-mini (can extend to Anthropic Claude).
- Generates a structured JSON response (topic, summary, sources, tools used).
- Saves results to a file via custom tool.

## 🛠️ Tech Stack
- Python 3.10+
- LangChain
- OpenAI API
- Pydantic
- dotenv for API key management

## 🚀 **Setup Instructions**

1. Clone the Repository
  ```bash
  git clone https://github.com/ravish-git/AiAgent.git
  cd <AiAgent>
```
2. Create and Activate Virtual Environment
  python -m venv .venv

    Activate the environment:
    
    On Windows:
    ```bash
    .venv\Scripts\activate
    ```
   
    On Mac/Linux:
    ```bash
    source .venv/bin/activate
    ```

4. Install Dependencies
  ```bash
  pip install -r requirements.txt
  ```

4. Set Up OpenAI API Key
   ```bash
   OPENAI_API_KEY=""
   ```

5. Run
   ```bash
   python main.py
   ```
