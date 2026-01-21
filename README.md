# LangGraph Agent Test on GCP


This repository contains a proof-of-concept implementation for building and testing AI agents using **LangGraph** within a **Google Cloud Platform (GCP)** environment. The core logic is encapsulated in a Jupyter Notebook, demonstrating how to create stateful, cyclic agent workflows.

## 📄 Repository Contents

* `AI_Agents_Revamped.ipynb`: The main notebook containing the agent logic, graph definitions, and execution flow.
* `README.md`: Project documentation.

## 🚀 Overview

The goal of this project is to explore the capabilities of **LangGraph** (a library by LangChain) to build reliable, stateful multi-agent systems. Unlike standard linear chains, LangGraph allows for cyclical flows, making it ideal for agentic behaviors like loops, retries, and human-in-the-loop interactions.

### Key Features
* **Stateful Graph Execution**: Manages agent state across multiple steps.
* **GCP Integration**: Designed to run with Google Cloud services (likely Vertex AI or Gemini API).
* **Cyclic Workflows**: Demonstrates how agents can loop back to previous states (e.g., for self-correction).

## 🛠️ Technology Stack

* **Language**: Python 3.x
* **Frameworks**:
    * [LangGraph](https://github.com/langchain-ai/langgraph)
    * [LangChain](https://github.com/langchain-ai/langchain)
* **Infrastructure**: Google Cloud Platform (GCP)
* **Environment**: Jupyter Notebook

## 📋 Prerequisites

To run the notebook, ensure you have the following:

1.  **Python Environment**: Python 3.9+ recommended.
2.  **GCP Credentials**: A valid Google Cloud project with necessary APIs enabled (e.g., Vertex AI API).
3.  **API Keys**: If using Gemini or OpenAI models, ensure your API keys are configured in your environment variables.

## 🔧 Installation & Usage

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/felixyustian/langgraph_agent_test.git](https://github.com/felixyustian/langgraph_agent_test.git)
    cd langgraph_agent_test
    ```

2.  **Install Dependencies**
    You will likely need the following packages (install them inside the notebook or via terminal):
    ```bash
    pip install langgraph langchain langchain-google-genai google-cloud-aiplatform jupyter
    ```

3.  **Launch the Notebook**
    ```bash
    jupyter notebook AI_Agents_Revamped.ipynb
    ```

4.  **Run the Cells**
    Follow the step-by-step instructions in the notebook to initialize the graph and run the agent.

## 📄 License

This project is distributed under the **GPL-3.0 License**. See the `LICENSE` file for more details.
