# 🧠 AI Apps Collection: Python Code Generator & Image Captioning (Qwen-based)

This repository includes two AI-powered web apps built with Gradio and Hugging Face Transformers:

1. **Python Code Generator** — powered by `deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B`
2. **Image Captioning App** — powered by `Qwen/Qwen-VL-Chat-Int4` with AutoGPTQ quantization

Both applications are optimized for GPU usage and provide user-friendly interfaces with adjustable generation parameters.

---

## 📌 Project 1: Python Code Generator

Generate Python code from plain-language task descriptions using a powerful language model.

### ✅ Features

- Returns **only executable Python code**
- Guided with **prompt examples** to enhance structure
- Parameters: `temperature`, `top_p`, `max_new_tokens`
- Built with [Gradio](https://gradio.app) and Hugging Face Transformers

### 🔧 Installation

Install dependencies using:

```bash
pip install -r text_code_req.txt
pip install -r imag_text_req.txt
