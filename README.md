
# How to trace LangGraph

1. Go to https://smith.langchain.com/
2. Sign in and generate an API key
3. Install dependencies

    ```console
    pip install -U langchain langchain-openai
    ```

4. Add the keys to your project's `.env` file

    ```console
    LANGSMITH_API_KEY=<your-api-key>
    LANGCHAIN_TRACING_V2=true
    LANGCHAIN_PROJECT=<project-name>
    OPENAI_API_KEY=<your-openai-api-key>
    ```

