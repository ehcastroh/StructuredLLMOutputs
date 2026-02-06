# Structured LLM Output

## Overview

This project implements a structured LLM Output workflow. It demonstrates how structured output can be used for tasks such as data validation and improving trace/span evals.

The repo is structured with:

* A Jupyter Notebook (`structured_llm_ouput.ipynb`) for ideation, design, and experimentation.

* A Python executable (`structured_llm_ouput.py`) for running the chatbot interactively in the terminal.

## Getting Started

1. Install dependencies

  ```python
  pip install -r requirements.txt

  ```
2. Set Antropic API key
  In a `.env` file in the project root:

  ```python
  ANTHROPIC_API_KEY="your_api_key_here"
  ```
3. Run the chatbot (from terminal)
  ```python
  python structured_llm_ouput.py
  ```