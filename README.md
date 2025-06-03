# 🧠 Python Code Generator with DeepSeek-R1-Distill-Qwen-1.5B

This project provides a web-based interface for generating Python code snippets using the `deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B` model. It allows users to input tasks in natural language and receive clean, executable Python code — without any explanation or extra formatting.

Built using:
- [Gradio](https://gradio.app) for the web UI
- [Hugging Face Transformers](https://huggingface.co/docs/transformers) for loading and using the LLM
- Python regex for extracting code blocks

---

## 🚀 Features

- **Clean Python code only**: Model is prompted to return *only code*.
- **Example prompts**: Select predefined tasks to see how it works.
- **Customizable generation**: Adjust `temperature`, `top_p`, and `max_new_tokens`.
- **Web-based UI**: Powered by Gradio, works in Jupyter, Colab, or local environments.
- **Detailed README**: Includes setup instructions, usage guidelines, examples, and explanation of prompt engineering strategies.

---

## 🛠️ Installation

1. Clone the repository or copy the code into your environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
