# RAG from Scratch to Production: Notebooks

A 20-episode, notebook-per-concept walkthrough of a production
[RAG chatbot](https://github.com/JakkulaMahendhar/rag-chatbot) (FastAPI · ChromaDB ·
BM25 · CrossEncoder reranking · Gemini/Ollama), from first principles to deployment. Each notebook runs on its own in Colab (free Gemini key) or
locally with Ollama.

| # | Episode | Notebook |
|---|---|---|
| 1 | Why RAG? Watching an LLM fail on your data, then fixing it | [01_why_rag.ipynb](notebooks/01_why_rag.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/01_why_rag.ipynb) |
| 2 | Architecture: one request, end to end | [02_architecture.ipynb](notebooks/02_architecture.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/02_architecture.ipynb) |
| 3 | Parsing PDF / DOCX / TXT | [03_parsing.ipynb](notebooks/03_parsing.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/03_parsing.ipynb) |
| 4 | Chunking strategies | [04_chunking.ipynb](notebooks/04_chunking.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/04_chunking.ipynb) |
| 5 | Embeddings | [05_embeddings.ipynb](notebooks/05_embeddings.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/05_embeddings.ipynb) |
| 6 | Vector DB with ChromaDB | [06_vector_db.ipynb](notebooks/06_vector_db.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/06_vector_db.ipynb) |
| 7 | Keyword search with BM25 | coming soon |
| 8 | Hybrid search | coming soon |
| 9 | Query enhancement | coming soon |
| 10 | Reranking with a CrossEncoder | coming soon |
| 11 | The reranker threshold bug | coming soon |
| 12 | Context engineering | coming soon |
| 13 | Prompt building for grounded answers | coming soon |
| 14 | Swappable LLMs: Gemini vs Ollama | coming soon |
| 15 | Hallucination guard | coming soon |
| 16 | Evaluating RAG | coming soon |
| 17 | FastAPI, streaming, background worker | coming soon |
| 18 | Auth, rate limiting, access control | coming soon |
| 19 | Postgres, Alembic, Docker | coming soon |
| 20 | CI/CD and deployment | coming soon |

## Run locally

```bash
pip install -r requirements.txt
jupyter notebook notebooks/
```

Set `GEMINI_API_KEY` (free at https://aistudio.google.com/apikey), or run
[Ollama](https://ollama.com) with `ollama pull llama3.1` and
`export LLM_PROVIDER=ollama`.

## Follow the series

- LinkedIn: [@MahendharJakkula](https://www.linkedin.com/in/mahendhar-jakkula/)
- Instagram: [@codingwithmahi](https://instagram.com/codingwithmahi)
