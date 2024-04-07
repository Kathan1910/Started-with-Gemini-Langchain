# Gemini Applications Repository

## Overview

This repository contains a series of Streamlit applications designed to demonstrate the integration with Google's Generative AI services, specifically using the Gemini Pro model. These applications provide a user-friendly interface for submitting questions and receiving responses from the AI model.

## Applications

- `app.py`: A basic Streamlit app that initializes the Gemini Pro model and displays responses to user input.
- `app2.py`: An enhanced version that includes handling of chat history and uses environment variables for configuration.
- `app3.py`: Similar to `app2.py` but with session state management to maintain chat history across sessions.
- `app4.py`: Focuses on formatting the AI's responses using Markdown for a better display in the Streamlit app.

## Jupyter Notebook

- `gemini.ipynb`: A Jupyter notebook that provides a detailed walkthrough of setting up and calling the Gemini Pro model within a Python environment, showcasing different ways to interact with the model.

## Setup and Installation

1. Clone the repository.
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up your `.env` file with the necessary environment variables (`GOOGLE_API_KEY`).

## Running the Applications

To run any of the Streamlit applications, use the following command:

```bash
streamlit run app_name.py
```