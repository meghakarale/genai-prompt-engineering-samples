
# GenAI Prompt Engineering Samples

This repository contains ready-to-run Jupyter notebooks demonstrating prompt engineering techniques using major Generative AI model providers:

- **Cohere (command-r-plus)**
- **OpenAI (GPT-4)**
- **Meta LLaMA (via Hugging Face Transformers)**

Each notebook showcases:
- 🔹 Zero-shot and Few-shot prompting
- 🔹 Structured prompt examples (JSON/XML-style)
- 🔹 Use of system messages and function-style outputs
- 🔹 Text generation, summarization, and completion use cases

---

## Notebooks Included

| Notebook | Description |
|----------|-------------|
| `cohere_prompt_engineering.ipynb` | Uses Cohere's `command-r-plus` model for zero-shot generation |
| `openai_prompt_engineering.ipynb` | Few-shot prompting using OpenAI's GPT-4 model |
| `meta_llama_prompt_engineering.ipynb` | Runs Meta's LLaMA-2 model via Hugging Face Transformers |

---

## Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/genai-prompt-engineering-samples.git
   cd genai-prompt-engineering-samples

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt

3. **Set your environment variables**
   Create a .env file or export them in your terminal:
   ```bash
   export COHERE_API_KEY=your-cohere-key
   export OPENAI_API_KEY=your-openai-key

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook

---
**Notes**
The Meta LLaMA model is accessed via Hugging Face and may require a login/token depending on the model version.

For Cohere and OpenAI, free-tier access is available with limits.
