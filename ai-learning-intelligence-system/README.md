# AI Learning Intelligence System
## Adaptive Study Assistant with Knowledge Gap Detection

A production-style RAG (Retrieval Augmented Generation) pipeline that 
transforms personal study notes into an intelligent learning assistant. 
Built with ChromaDB, sentence-transformers, and Groq LLaMA 3.1.

---

## What makes this different from ChatGPT

| Feature | ChatGPT | This System |
| Knowledge base size | Limited by context window | Unlimited via ChromaDB |
| Data privacy | Sent to OpenAI servers | Runs locally |
| Persistence | Lost after session | Stored in ChromaDB |
| Gap detection | None | Automatic confidence scoring |
| Quiz generation | Manual prompting | Automatic from knowledge base |
| Topic tracking | None | Full learning dashboard |
