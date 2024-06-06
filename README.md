# book-info-retrieval
Book Information Retrival System
## Introduction

This project demonstrates the setup and functionality of integrating Microsoft AutoGen and Hugging Face Transformers to create an interactive book information retrieval system. The goal is to show how to set up agents, handle user inputs, and fetch book data from the OpenLibrary API.

## Setup Instructions

### Requirements

- Python 3.8 or higher
- Jupyter Notebook or any Python IDE
- Anaconda Navigator (Optional, for environment management)

### Installation Steps

1. **Clone the Repository (Optional):**
    ```bash
    git clone https://github.com/yourusername/book-info-retrieval.git
    cd book-info-retrieval
    ```

2. **Create a Virtual Environment:**
    ```bash
    conda create -n bookinfo python=3.8
    conda activate bookinfo
    ```

3. **Install Dependencies:**
    ```bash
    pip install transformers requests python-dotenv autogen
    ```

### Configuration

1. **Create a `.env` File:**

    Create a `.env` file in the root of your project directory with the following content:

    ```
   Initialized Autogen with Public API key: On this project using Public APIs to prevent unauthorized access and misuse
    ```

### Using Microsoft AutoGen

**Configure AutoGen with `OAI



