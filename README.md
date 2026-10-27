### Hi 👋🏼
AI engineering student at ENSEEIHT · ML engineer at Finary

### 🔨 Now
Four projects on Mistral models, built in public:

- **[SecoursTech](https://github.com/gabrielkpo/secours-tech)**: RAG assistant over official French
  firefighter doctrine. Every answer cites the guide and page; it refuses when the doctrine is
  silent. Ingestion and Postgres index done, retrieval and generation next.
- **[Lifter](https://github.com/gabrielkpo/lifter)**: training coach agent on my own Garmin data
  (LangGraph + Mistral), with human approval before any write. v0.6.0 in production.
- **[Alias](https://github.com/gabrielkpo/alias)**: local PII masking before an LLM call (FR + EN).
  Rules, masking and restoring done, NER model trained (mmBERT-small); combining rules and model
  next.
- **[hpc-inference-sizing](https://github.com/gabrielkpo/hpc-inference-sizing)**: how many GPUs
  to serve Mistral Small 4 (119B MoE) under a latency target, measured with vLLM on a rented
  multi-GPU node. Protocol written, memory model and measurement bench next.

### 🚀 Projects
| Project | What it is | Stack |
|---|---|---|
| [garmin-mcp-remote](https://github.com/gabrielkpo/garmin-mcp-remote) | Self-hosted MCP server that connects Garmin Connect to claude.ai, behind an OAuth 2.1 + PKCE layer, hardened and tested | Python · Docker · nginx · OAuth |
| [Fall-detection](https://github.com/gabrielkpo/Fall-detection) | Fall detection from body pose (MediaPipe + 1D CNN), honestly evaluated (frozen test split, bootstrap intervals), served by an API and an in-browser demo, with drift monitoring | Python · PyTorch · FastAPI · ONNX |
| [video-super-resolution-fsrcnn](https://github.com/gabrielkpo/video-super-resolution-fsrcnn) | School research project: classical upscaling vs sparse coding vs FSRCNN, plus a temporal filter that skips unchanged blocks to save compute | Python · PyTorch · OpenCV |
| [augmented-rag](https://github.com/gabrielkpo/augmented-rag) | Research fork of gbrain: retrieval measured on a real 1,200-page knowledge base, each change kept or dropped on benchmark evidence | TypeScript · Python · Postgres |

### 🧰 Stack
Python · PyTorch · FastAPI · LangGraph · vLLM · PostgreSQL · Docker · GitHub Actions · Git · Linux

### 📫 Contact
[LinkedIn](https://www.linkedin.com/in/gabriel-kpodoh-66464032b/) · [Portfolio](https://e-portfolio-gabriel-kpodoh.vercel.app)
