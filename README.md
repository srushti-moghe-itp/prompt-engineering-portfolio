# Prompt Engineering Portfolio

A Jupyter notebook project demonstrating 10+ prompt engineering techniques applied to real tasks across:

- text classification
- summarization
- code generation
- data extraction

This portfolio compares responses from GPT (OpenAI), Claude (Anthropic), and a local Ollama-based model when available.

## Files

- `Prompt_Engineering_Portfolio.ipynb` — main notebook with examples, code, and provider comparisons
- `requirements.txt` — Python dependencies for launching the notebook
- `.gitignore` — ignores notebook checkpoints and environment files

## Usage

1. Create a `.env` file in the repository root with your API keys:

```env
OPENAI_API_KEY=sk-...
GROQ_API_KEY=...
```

2. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

3. Launch the notebook:

```bash
python -m notebook Prompt_Engineering_Portfolio.ipynb
```

> If `ollama` is installed locally, the notebook will attempt to compare results from an Ollama model. If not installed, the notebook will still run and show placeholders.
