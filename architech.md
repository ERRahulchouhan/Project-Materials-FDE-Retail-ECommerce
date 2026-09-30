# Tools and Their Uses

| Tool | Used for |
|---|---|
| PostgreSQL | Main relational database for users, orders, returns, policies, and audit records. |
| Redis | Caching, pub/sub messaging, and the backing service for background jobs. |
| arq | Processing queued background jobs with Python workers. |
| SQLAlchemy | Connecting to and querying PostgreSQL from Python. |
| Alembic | Managing ordered database schema migrations. |
| Next.js | Web application framework for the shop and reviewer dashboard. |
| React | Building the web application interface. |
| Auth.js | Managing frontend authentication sessions. |
| Keycloak | User login, roles, and agent service identities. |
| FastAPI | Backend HTTP API and WebSocket updates. |
| LangGraph | Orchestrating the multi-step AI review workflow. |
| Bifrost | Routing AI model requests and handling provider fallback and telemetry. |
| Groq | Hosted AI model provider. |
| OpenAI | Hosted AI model provider. |
| ContextForge | Gateway that controls agent access to tools. |
| MCP tools server | Providing database-backed tools to agents. |
| Open Policy Agent (OPA) | Enforcing authorization and automated decision rules. |
| Qdrant | Vector database for searching return-policy documents. |
| scikit-learn | Training and running the customer behavior risk model. |
| CLIP | Comparing return photos with product reference images. |
| AI-image detector | Identifying signals that an image may be AI-generated. |
| MinIO | Object storage for product and return photos. |
| HashiCorp Vault | Storing and providing application secrets. |
| MailHog | Capturing email locally during development. |
| Langfuse | Tracing AI prompts, responses, token use, cost, and latency. |
| Prometheus | Collecting application and infrastructure metrics. |
| Grafana | Displaying metrics dashboards and alerts. |
| ClickHouse | Storing Langfuse observability data. |
| Docker Compose | Running the local application and supporting services. |