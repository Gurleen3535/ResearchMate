ResearchMate: AI-Powered Research & Knowledge Discovery Assistant

Project Stage: Exploratory Research & Development | In Progress

Overview:
ResearchMate is an ongoing project exploring AI-powered approaches to retrieving, organizing, and ranking academic research papers based on user queries.
The current development focuses on experimenting with academic research APIs, processing paper metadata, exploring semantic search and relevance-ranking techniques, and prototyping vector-based query caching.

Technologies & Tools:
- Programming Language: Python
- Research APIs: Crossref, arXiv, PubMed, Europe PMC, and OpenAlex
- Semantic Search: Sentence Transformers ("all-MiniLM-L6-v2")
- Similarity Measurement: Cosine similarity
- Vector Database: ChromaDB
- Data Processing: JSON and CSV

Current Areas of Development:
- Research API Integration: Exploring multiple academic sources to retrieve research-paper information.
- Metadata Normalization: Converting paper records into a common structure.
- Abstract Recovery: Experimenting with methods to recover missing abstracts when available.
- Duplicate Detection: Identifying duplicate research papers using metadata and title matching.
- Semantic Search: Comparing research questions with paper content using text embeddings.
- Relevance Ranking: Experimenting with a weighted score combining semantic similarity, keyword relevance, and publication recency.
- Query Caching: Prototyping ChromaDB-based storage and similarity matching for previously submitted queries.

Current Progress:
The project is being developed incrementally through separate Python scripts and experimental runs. Individual components are being tested to understand their behavior and identify areas for improvement.
The current query-caching prototype is being explored separately, with further integration into the complete research retrieval pipeline remaining a development goal.

Planned Next Steps:
- Evaluate the quality and coverage of results from different research APIs.
- Improve metadata processing and duplicate detection.
- Test and refine relevance-ranking strategies.
- Integrate query caching with the complete retrieval workflow.
- Evaluate the pipeline using representative research questions.

Project Status:
ResearchMate is an ongoing exploratory project. Its implementation, architecture, and methods may evolve as development and testing continue.
