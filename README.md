# asstra-offline-study-app
Student's PDFs never leave their machine
Chat model: llama3.2:3b via ollama.chat
Embedding model: nomic-embed-text via ollama.embed
Vector DB: ChromaDB, persisted locally at processed/chroma — good, this is fully offline and needs no extra server.
One thing to flag: ChromaDB by default tries to phone home anonymous telemetry on startup. Not a big deal for a study tool, but for a true "offline" pitch you should disable it.
