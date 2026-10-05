# llm-context-optimizer

`llm-context-optimizer` is a lightweight utility designed to preprocess, clean, and format raw text contexts before submitting them to Large Language Models (LLMs) such as Claude.

## Features
- **Text Normalization:** Strips redundant whitespace and redundant newlines.
- **Markdown Structuring:** Wraps input content inside clean Markdown blocks ready for prompt injection.
- **Context Analytics:** Computes character, word, and line counts.

## Usage
```bash
python main.py -f example.txt -t "Source Code Context"
