# Anthropic API Introduction

To follow along with the demos, first complete the following steps:

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/pluralsight-cloud/anthropic-api-introduction.git
    ```

2. Change into the directory and open Visual Studio Code

    ```bash
    cd anthropic-api-introduction
    code . --reuse-window
    ```

3. Initialize a new environment and install the required packages

    ```bash
    uv init
    uv venv
    uv add anthropic python-dotenv ipykernel
    ```

4. Create a `.env` file in the root of the project and add your Anthropic API key

    ```env
    ANTHROPIC_API_KEY=your_api_key_here
    ```

5. Open the Jupyter Notebook file for the clip you want to follow-along with and select the appropriate kernel (the environment you just created).
