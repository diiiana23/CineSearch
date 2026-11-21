# CineSearch
Proiect BDNV 2026–2027 | T7 — Motor de căutare semantică în descrieri de filme

**Descriere**

CineSearch va permite căutarea filmelor pornind de la o descriere în limbaj natural a poveștii dorite. Sistemul va identifica filme relevante pe baza sensului descrierilor, nu doar prin potrivirea exactă a cuvintelor.

**Obiective**

- Importarea unui set de date cu filme și descrierile acestora.
- Generarea de embeddings și stocarea lor împreună cu metadatele.
- Implementarea și compararea căutării după cuvinte-cheie, semantice și hibride.
- Compararea căutării vectoriale exacte cu cea aproximativă.
- Analizarea regăsirii top-k și a căutării după un prag de similaritate.
- Integrarea unui LLM pentru rezumarea rezultatelor regăsite.
- Evaluarea relevanței rezultatelor și a timpilor de răspuns.

**Tehnologii propuse**
- Python
- MongoDB Atlas Vector Search
- SentenceTransformers
- Ollama
- Streamlit (de exemplu)
