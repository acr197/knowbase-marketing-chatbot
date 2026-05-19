# KnowBase

A chatbot that answers questions about your internal docs and cites exactly where it found the answer.

[Video demo](https://www.youtube.com/watch?v=susAiBKjLE4)

## Features

- Upload PDFs, Word docs, or plain text files and the chatbot indexes them on the spot
- Ask a question in natural language and get a direct answer with inline citations pointing to the source document and passage
- If the answer isn't in the docs, it says so instead of guessing
- Reindex anytime as your document library changes
- Built in 4 prompts from scratch, documented [here](https://chatgpt.com/share/68ed3420-39f0-8000-a0e5-5d955d1a0c0c)

## Tech Stack

- **Python** for all backend logic
- **Streamlit** for the web UI, file uploads, and chat interface
- **FAISS** for fast vector similarity search across document chunks
- **OpenAI** for embeddings and answer generation with citation grounding
- **PyMuPDF** for PDF text extraction

## Privacy

- Runs locally. Your documents stay on your machine.
- No analytics, telemetry, or third-party data sharing.
- OpenAI API calls send only the relevant text chunks needed to answer the query.
