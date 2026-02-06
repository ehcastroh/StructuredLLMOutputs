# Structured LLM Output

## Overview

This project implements a structured LLM Output workflow. It demonstrates how structured output can be used for tasks such as user-input, data and  LLM-ouput validation, as well as improving trace/span evals.

The repo is structured with:

* A Jupyter Notebook (`pydantic_user_input_validation.ipynb`) for ideation, design, and experimentation related to user-input validation and error handling

* A Jupyter Notebook (`pydantic_llm_response_validation.ipynb`) for ideation, design, and experimentation related to LLM-output validation and error handling

## Getting Started

1. Install dependencies

  ```python
  pip install -r requirements.txt

  ```
2. Set Antropic API key
  In a `.env` file in the project root:

  ```python
  ANTHROPIC_API_KEY="your_api_key_here"
  OPENAI_API_KEY="your_api_key_here"
  ```
3. Run the chatbot (from terminal)
  ```python
  python structured_llm_ouput.py
  ```