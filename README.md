# Relevance Scoring and Rerankers

This lab explores retrieval quality improvements for a RAG workflow using:
- metadata filtering
- LLM-based relevance scoring
- cross-encoder reranking
- simple manual evaluation

The main work is in the notebook `relevance_scoring_rerankers.ipynb`.

## Files

- `relevance_scoring_rerankers.ipynb`: step-by-step lab notebook covering loading, chunking, embeddings, retrieval, reranking, filtering, and evaluation
- `lab_summary.md`: short narrative summary of the lab outcome
- `resources/`: source materials used in the lab
- `resources/trustworthy_ai.pdf`: PDF document used as a retrieval source
- `resources/podcast.m4a`: full podcast audio source
- `resources/podcast_small.m4a`: compressed podcast audio source used when file-size constraints apply

## How to run

1. Create a `.env` file at the repository root with your OpenAI API key:
   ```bash
   OPENAI_API_KEY=your_key_here