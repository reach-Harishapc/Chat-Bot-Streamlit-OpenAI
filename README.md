# Chat-Bot-Streamlit-OpenAI


## Prerequisites

Before you can run this chatbot, make sure you have the following prerequisites installed:

- Python
- Streamlit
- OpenAI Python SDK
- TOML library

You can install the required libraries using `pip`:

```bash
pip install streamlit openai toml
```

## Getting Started

1. Clone the repository or create a new project directory for this chatbot.

2. Inside your project directory, create a folder named `streamlit`. This folder will contain the `secrets.toml` file where you'll store your OpenAI API key.

3. Obtain an OpenAI API key and place it in the `secrets.toml` file as follows:

    ```toml
    # secrets.toml
    OPENAI_API_KEY = "YOUR_OPENAI_API_KEY_HERE"
    ```

4. Create a Python script (e.g., `app.py`) and paste the provided code into this script.

5. Run the chatbot application using the following command:

    ```bash
    streamlit run app.py
    ```
