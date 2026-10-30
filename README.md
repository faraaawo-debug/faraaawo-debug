# 👋 Hi, I'm Faraa Awoyemi

🎓 5th-year engineering student at **ESILV** (Paris La Défense), major in **Data & Artificial Intelligence**, with a background in physics  
📍 Currently on an exchange semester at **Asia Pacific University (APU), Kuala Lumpur** (Sept – Dec 2026)  
🔍 Looking for an **internship or VIE starting early 2027**: generative AI, LLMs, RAG, AI agents

I build generative AI applications in Python (RAG, MCP servers, AI agents) and measure how reliable they are.

---

## 🧠 Interests
- AI agents (LangGraph, MCP, tool calling)
- Retrieval-Augmented Generation (RAG)
- Evaluation and reliability of LLM systems

---

## 🛠️ Technical Skills

**Languages:** Python, SQL, C++  
**Generative AI:** LLMs, RAG, AI agents, tool calling, MCP (Model Context Protocol), prompt engineering, LLM-as-a-Judge evaluation  
**Frameworks & APIs:** LangChain, LangGraph, REST APIs (Mistral, Groq), Ollama, Streamlit  
**Libraries:** PyTorch, Hugging Face, Sentence Transformers, spaCy, scikit-learn, Pandas, NumPy  
**Data:** ChromaDB (vector database), SQL, knowledge graphs, RDF, SPARQL  
**Software engineering:** Git, GitHub, pytest, continuous integration, Docker (basics), Claude Code  

---

## 🚀 Featured Projects

### RAG assistant integrated into Claude Desktop (MCP) · [mcp-rag-server](https://github.com/faraaawo-debug/mcp-rag-server)
*Mar – Oct 2026*
- Python MCP server exposing two tools (search, question answering) that the LLM calls through tool calling
- RAG pipeline: ingestion, vector search (ChromaDB), answers with source citations (Mistral API)
- Intent router: a first LLM call identifies the question type and adapts retrieval, or refuses off-topic questions
- Each feature evaluated on the same annotated questions (LLM-as-a-Judge)
- Automated tests (pytest), continuous integration, documentation

**Tools:** Python, MCP, ChromaDB, Sentence Transformers, Mistral API, pytest, GitHub Actions

---

### Knowledge graph (RDF) built from Wikipedia · [knowledge-graph-project](https://github.com/faraaawo-debug/knowledge-graph-project)
*Mar 2026 · project in pairs*
- Knowledge graph built from Wikipedia: entity extraction (spaCy) and Wikidata enrichment, in RDF
- Wikidata entity linking: candidate filtering by type, scoring, and an evidence-based LLM judge
- Natural-language querying: an LLM translates the question into a SPARQL query over the graph

**Tools:** Python, spaCy, RDF, SPARQL, Wikidata, Mistral API

---

### NO₂ time series forecasting · [prediction_NO2_new_delhi](https://github.com/faraaawo-debug/prediction_NO2_new_delhi)
*Dec 2025 · group project*
- Data pipeline: cleaning, merging pollution and weather data (Open-Meteo API), feature engineering
- Compared linear regression, Random Forest (selected) and LSTM; Streamlit app

**Tools:** Python, Pandas, scikit-learn, Random Forest, LSTM, Streamlit

---

### Semantic search on the EU AI Act · [ai-act-semantic-search](https://github.com/faraaawo-debug/ai-act-semantic-search)
*Dec 2025*
- 144-page regulation: overlapping chunking, each passage linked to its article (traceability)
- Embedding model benchmark: **Hit@5 raised from 49% to 76%**, **MRR from 0.36 to 0.61** with a multilingual model

**Tools:** Python, Sentence Transformers, embeddings, Hit@K, MRR

---

## 🌍 Languages
French (native) · English (C1, TOEFL)

---

## 📫 Contact
- 📧 faraa.awoyemi@edu.devinci.fr
- 💼 [LinkedIn](https://linkedin.com/in/faraa-awoyemi-a3b359395)
