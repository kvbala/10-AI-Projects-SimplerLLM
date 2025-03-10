# Getting Started
## Installation
1. Use the below commands on the VSCode Terminal
    ```bash
    python -m venv venv #To create a Virtual Environment
    venv/scripts/activate #Activate the new Virtual environment
    pip install simplerllm #Install SimplerLLM
    ```
2. Create a .env file at the Project root folder to hold the environment values as below
    ```properties
    GEMINI_API_KEY="abcdefgh"
    OPENAI_API_KEY="sk-proj-asdfd"
    ```
## LLM Model names

Sl.No | Provider | Model Name | Model | Type 
--- | --- | --- | --- | ---
1 | Google | GEMINI 2.0 Flash Lite | gemini-2.0-flash-lite | Free
2 | OpenAI | GPT 3.5 Turbo | gpt-3.5-turbo | Priced