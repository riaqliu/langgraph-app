
# How to Setup LANGGRAPH Studio

1. Install LangGraph CLI

    ```console
    pip install -U "langgraph-cli[inmem]" langsmith openai
    ```

2. Create a LangGraph APP

    ```console
    mkdir langgraph-server && cd langgraph-server
    langgraph new ./ --template react-agent-python
    ```

3. Install Dependencies

    ```console
    pip install -e .
    ```

4. Create a `.env` file and put your keys there.

    ```console
    LANGSMITH_API_KEY=<your-api-key>
    LANGCHAIN_TRACING_V2=true
    LANGCHAIN_PROJECT=<project-name>
    OPENAI_API_KEY=<your-openai-api-key>
    ```

5. Launch the server

    ```console
    langgraph dev
    ```

Alternatively, you can just view the documentation [here](https://docs.smith.langchain.com/) and [here](https://langchain-ai.github.io/langgraph/tutorials/langgraph-platform/local-server/).
