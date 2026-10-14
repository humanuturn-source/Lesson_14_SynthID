# Install Instructions

## Step 1: Install Ollama & Pull Local Models

Install Ollama to host your models locally, then pull Google DeepMind’s Gemma 4

1.	Install Ollama:
⚬	macOS / Linux: Download from ollama.com or run:

    ```bash
    brew install ollama
    ```
⚬	Windows: Download and run the setup installer from ollama.com.

2.	Pull the Local Gemma 4 & 2 Models:
Open your terminal and run:

    ```bash
    ollama pull gemma4
    ```

## Step 2: Create a Python Virtual Environment

Keep your dependencies isolated by creating a clean virtual environment:

    ```bash
    # 1. Navigate to your project folder
    cd ai_app

    # 2. Create the virtual environment
    python3 -m venv venv

    # 3. Activate the virtual environment
    # macOS / Linux:
    source venv/bin/activate

    # Windows (PowerShell):
    # .\venv\Scripts\Activate.ps1
    ```

## Step 3: Install dependencies

```bash

    pip install Flask requests fastmcp reportlab
```
  

## Step 4: Source documents 

    Copy source code from GitHub repository

## Step 5: Run the application

```bash
python3 app.py

```









