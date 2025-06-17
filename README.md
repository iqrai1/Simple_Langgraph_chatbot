# Chatbot Using LangGraph

This project demonstrates the implementation of a simple chatbot using the **LangGraph** framework. The chatbot integrates with **OpenAI's GPT-4** model to handle conversational queries, offering a dynamic and interactive user experience. The project is implemented in a Jupyter Notebook (`.ipynb`).

## Features

- **State Management**: Uses LangGraph's state graph model to manage the conversation flow.
- **API Integration**: Integrates with external APIs such as OpenAI's GPT-4 model.
- **Environment Configuration**: Loads environment variables using **dotenv** for API keys.

## Technologies

- **Python**: The primary programming language
- **LangGraph**: For managing the flow of conversation through a state machine.
- **OpenAI GPT-4**: For generating natural language responses
- **Groq API**: Additional API integration for enhanced chatbot capabilities.
- **Dotenv**: For loading environment variables.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/chatbot_using_langgraph.git
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root directory with your API keys:
    ```bash
    OPENAI_API_KEY=your_openai_api_key
    GROQ_API_KEY=your_groq_api_key
    ```

4. Open the Jupyter Notebook:
    - Run Jupyter Notebook in your terminal:
      ```bash
      jupyter notebook
      ```
    - Open the `chatbot_using_langgraph.ipynb` file in the Jupyter Notebook interface.

5. Run the notebook cells in order to see the chatbot in action.

## Usage

Once the notebook is set up, run the cells to see the chatbot respond to input via the notebook interface. You can modify the code in the notebook to experiment with different inputs, extend functionality, or integrate the chatbot into a web or mobile interface for more advanced use cases.

