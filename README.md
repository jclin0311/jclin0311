### Hi, I'm Jiachun 👋

MSCS student at the University of Pennsylvania, building **AI infrastructure**: RAG pipelines, agent memory, and the backend systems underneath them. Lately I've been contributing fixes to open-source AI projects.

[LinkedIn](https://www.linkedin.com/in/jiachun-lin-680016168/)

---

#### 🔧 Open source

**Merged**

| Project | Contribution |
|---|---|
| [**RAGFlow**](https://github.com/infiniflow/ragflow) ![stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square&label=%E2%98%85) | [#20224](https://github.com/infiniflow/ragflow/pull/20224): Fixed a startup crash in the Ollama embedding and vision models when `OLLAMA_KEEP_ALIVE` uses Ollama's documented duration format (`5m`, `24h`). I centralized keep-alive parsing, made image-description requests honor the setting, and added regression tests. Merged into the `0.27.x` release branch. |

**Bug reports**

- [mem0ai/mem0#7443](https://github.com/mem0ai/mem0/issues/7443): pgvector boolean operator filters (`eq`/`ne`/`in`/`nin`) never matched stored booleans, and `ne`/`nin` returned the rows they should have excluded.
- [infiniflow/ragflow#20223](https://github.com/infiniflow/ragflow/issues/20223): the `OLLAMA_KEEP_ALIVE` crash above, with a reproduction against a real Ollama instance.

---

#### 🛠️ Projects

| Project | What it is | Stack |
|---|---|---|
| [**BankStackAI**](https://github.com/jclin0311/BankStackAI) | Microservices banking platform with an AI layer: core banking services, an MCP tool server, a RAG service and a multi-agent orchestrator. Includes a [runtime walkthrough](https://jclin0311.github.io/BankStackAI/demo.html) that traces a real request hop by hop. | Spring Boot · Kafka · Postgres · Spring AI · Ollama |
| [**Pattern Quiz**](https://github.com/jclin0311/quiz) | Learn to recognize algorithm patterns through multiple-choice quizzes with Socratic explanations, review scheduling and graph-based recommendations. | Next.js · FastAPI · SQLAlchemy · Postgres |
| [**http_search_server**](https://github.com/jclin0311/http_search_server) | Multi-threaded HTTP search server with an inverted index, built for UPenn CIT 5950. | C++ · POSIX sockets |

---

#### 🧰 Tech

**Languages:** Python · Go · Java · C++ · TypeScript
**AI / RAG:** LangChain · LangGraph · RAGFlow · Mem0 · MCP · Ollama · vLLM · pgvector
**Backend & infra:** Spring Boot · FastAPI · Kafka · PostgreSQL · Redis · Docker · Kubernetes · gRPC
