# Talat Zehra Ali

**Software engineer · C++ and Python · search, backend systems, and applied machine learning**

B.S. Computer Science, Oregon State University (2026).

I build software to understand the details behind it: how retrieval systems rank documents, how concurrent services handle state, and how models fit into real applications. These repositories include source code, tests, run instructions, and notes on the implementation's limitations.

## Projects

### [AtlasSearch](https://github.com/Alita41/atlassearch) — Search and information retrieval

A C++17 inverted index with BM25 ranking, top-K retrieval, and trie autocomplete, exposed through a Python API. Includes Redis caching, PostgreSQL metadata, optional multilingual-E5/FAISS hybrid search, and a synthetic 100K-document benchmark.

### [DevLens](https://github.com/Alita41/devlens) — Repository knowledge assistant

Indexes local files and GitHub repository content, including issues and pull-request descriptions. Provides source-cited answers and issue triage through a CLI and FastAPI service. The default retriever uses deterministic feature hashing; FAISS and OpenAI generation are optional. GitHub access is read-only.

### [NovaKV](https://github.com/Alita41/novakv) — Concurrent storage service

A single-node C++17 key-value server with TCP connections, sharded locking, TTL, an LRU cache, and a checksummed write-ahead log. Includes recovery tests, checkpoint compaction, and a reproducible client-side benchmark.

### [EdgeVision](https://github.com/Alita41/edgevision) — Edge computer vision

An OpenCV pipeline for sign-region proposals, object tracking, and multi-frame event confirmation, with SQLite event history and a FastAPI monitoring dashboard. Includes an optional TensorFlow Lite classification path, training/evaluation scripts, and a runnable synthetic demo.

## Tools and languages

C++ · Python · JavaScript · SQL · Linux · Docker · FastAPI · Flask · PostgreSQL · Redis · FAISS · OpenCV · TensorFlow Lite

## Links

[Portfolio](https://alita41.github.io/profile-website/) · [LinkedIn](https://www.linkedin.com/in/talat-zehra-ali-36394a257)
