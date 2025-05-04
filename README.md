# Personal RAG Application

A retrieval-augmented generation (RAG) system for personal knowledge management and question answering.

## Features
- Document ingestion for PDF/TXT/DOCX files
- Vector search capabilities
- Natural language question answering
- Local LLM integration
- Conversation history tracking

## Installation
```bash
git clone [repository-url]
cd personal-rag
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Configuration
Create `.env` file:
```env
OPENAI_API_KEY=your_api_key
EMBEDDING_MODEL=text-embedding-3-small
LLM_MODEL=gpt-4-1106-preview
```

## Project Structure
```
personal-rag/
├── data/               # Processed documents
├── documents/          # Original files to ingest
├── src/                # Application code
│   ├── retrieval/      # Vector search components
│   ├── generation/     # LLM integration
│   └── processing/     # Document preprocessing
└── tests/              # Unit tests
```

## License
MIT License