# LLMs Guide

**Everything you need to know about Large Language Models — without the PhD. Practical, visual, and business-focused.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Model Comparison 2025

| Model | Context | Strengths | Best For |
|---|---|---|---|
| GPT-4o | 128K | Multimodal, general | Everyday tasks |
| o3 / o4 | 200K | Deep reasoning, math | Complex problems |
| Claude 3.5 Sonnet | 200K | Writing, coding | Analysis, code |
| Gemini 2.5 Pro | 1M | Multimodal, Google | Research, docs |
| Llama 3 70B | 128K | Open source | Local deployment |
| Mistral 7B | 32K | Efficient, fast | High volume |

## How LLMs Work (Simple)

1. **Tokenization** — Text split into tokens (words/subwords)
2. **Embedding** — Tokens converted to vectors
3. **Attention** — Each token attends to all others
4. **Prediction** — Next token selected by probability
5. **Output** — Tokens decoded back to text

## Cost Optimization

1. **Right-size the model** — Use cheaper model for simple tasks
2. **Cache responses** — Don't re-call for identical inputs
3. **Compress prompts** — Remove redundant context
4. **Batch requests** — OpenAI Batch API: 50% cheaper
5. **Local models** — Free inference for private data

## Handling Hallucinations

- Ask model to cite sources for every fact
- Use temperature=0 for factual tasks
- Add self-verification step ('Check your answer')
- Use RAG to ground answers in retrieved documents
- Cross-reference with multiple sources

---

Part of the [Real-World AI Skills Ecosystem](https://github.com/saitejabandaru-in)
