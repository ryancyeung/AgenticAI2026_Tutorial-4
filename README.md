# AgenticAI2026_Tutorial-4: Errors, Reliability, & Coordination

Code for Tutorial 4 of the [Fall School on Agentic AI in Science 2026](https://ai-for-science.org/).

## **Usage**

Requires Python >=3.11.

**VS Code:**
1. Create a virtual environment in the project folder:
   ```bash
   python3 -m venv .venv
   ```
2. Install the requirements into it:
   ```bash
   .venv/bin/pip install -r requirements.txt
   ```
3. Choose `.venv` as the kernel in VS Code. Use `.env.example` as a template for generating your `.env` file: fill in your API keys and put it next to the notebook.

**Colab:**
1. Add `OPENROUTER_API_KEY`, `LANGFUSE_PUBLIC_KEY`, `LANGFUSE_SECRET_KEY` and `LANGFUSE_BASE_URL` in Secrets (key icon in the left sidebar) and turn on Notebook access for each one.
2. Optionally, you can upload `requirements.txt` next to the notebook. If you don't, the install cell falls back to its built-in package list.

## **Authors and Acknowledgment**

Authors:
* [Ryan Yeung](https://ryancyeung.github.io)

## **License**

This project is licensed under the [MIT License](LICENSE).
