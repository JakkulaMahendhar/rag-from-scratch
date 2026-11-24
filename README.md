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
| 7 | Keyword search with BM25 | [07_bm25.ipynb](notebooks/07_bm25.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/07_bm25.ipynb) |
| 8 | Hybrid search | [08_hybrid_search.ipynb](notebooks/08_hybrid_search.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/08_hybrid_search.ipynb) |
| 9 | Query enhancement | [09_query_enhancement.ipynb](notebooks/09_query_enhancement.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/09_query_enhancement.ipynb) |
| 10 | Reranking with a CrossEncoder | [10_reranking.ipynb](notebooks/10_reranking.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/10_reranking.ipynb) |
| 11 | The reranker threshold bug | [11_reranker_threshold.ipynb](notebooks/11_reranker_threshold.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/11_reranker_threshold.ipynb) |
| 12 | Context engineering | [12_context_engineering.ipynb](notebooks/12_context_engineering.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/12_context_engineering.ipynb) |
| 13 | Prompt building for grounded answers | [13_prompt_building.ipynb](notebooks/13_prompt_building.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/13_prompt_building.ipynb) |
| 14 | Swappable LLMs: Gemini vs Ollama | [14_swappable_llms.ipynb](notebooks/14_swappable_llms.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/14_swappable_llms.ipynb) |
| 15 | Hallucination guard | [15_hallucination_guard.ipynb](notebooks/15_hallucination_guard.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/15_hallucination_guard.ipynb) |
| 16 | Evaluating RAG | [16_evaluating_rag.ipynb](notebooks/16_evaluating_rag.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/16_evaluating_rag.ipynb) |
| 17 | FastAPI, streaming, background worker | [17_fastapi_streaming_worker.ipynb](notebooks/17_fastapi_streaming_worker.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/17_fastapi_streaming_worker.ipynb) |
| 18 | Auth, rate limiting, access control | [18_auth_rate_limits_access.ipynb](notebooks/18_auth_rate_limits_access.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/18_auth_rate_limits_access.ipynb) |
| 19 | Postgres, Alembic, Docker | [19_postgres_alembic_docker.ipynb](notebooks/19_postgres_alembic_docker.ipynb) · [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JakkulaMahendhar/rag-from-scratch/blob/main/notebooks/19_postgres_alembic_docker.ipynb) |
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
