# 3WM AI Document Intelligence Documentation

This documentation provides comprehensive guides for the 3WM AI Document Intelligence system by Sky Dust.

## Documentation Structure

```
3wm-project/
├── overview.mdx                 # System overview and introduction
├── getting-started/            # Installation and setup guides
│   ├── installation.mdx        # Detailed installation instructions
│   ├── configuration.mdx       # Configuration reference
│   └── quickstart.mdx         # 5-minute quick start guide
├── features/                   # Core features documentation
│   ├── document-processing.mdx # OCR and extraction pipeline
│   ├── ai-agents.mdx          # AI agent system
│   ├── knowledge-graph.mdx    # Neo4j integration
│   └── vector-search.mdx      # Similarity search
├── api-reference/             # API documentation
│   ├── overview.mdx           # API introduction
│   ├── authentication.mdx     # Auth endpoints
│   ├── upload.mdx            # Document upload
│   ├── agent.mdx             # AI agent queries
│   └── graph.mdx             # Graph operations
├── architecture/              # Technical architecture
│   ├── overview.mdx          # Architecture overview
│   ├── components.mdx        # Component details
│   ├── data-flow.mdx         # Request lifecycle
│   └── security.mdx          # Security implementation
├── deployment/               # Deployment guides
│   ├── overview.mdx         # Deployment options
│   ├── docker.mdx           # Docker deployment
│   ├── kubernetes.mdx       # Kubernetes deployment
│   ├── production.mdx       # Production best practices
│   └── monitoring.mdx       # Monitoring setup
└── guides/                  # Additional guides
    ├── best-practices.mdx   # Best practices
    ├── advanced-usage.mdx   # Advanced features
    └── troubleshooting.mdx  # Common issues
```

## Key Features Documented

1. **Document Processing Pipeline**
   - OCR with DocTR and TrOCR
   - Field extraction and validation
   - Multi-language support
   - Batch processing

2. **AI Agent System**
   - LangGraph orchestration
   - Natural language queries
   - Context-aware responses
   - Custom agent creation

3. **Knowledge Graph**
   - Neo4j integration
   - Vendor relationship mapping
   - Fraud detection patterns
   - Graph analytics

4. **Vector Search**
   - Semantic similarity
   - Duplicate detection
   - Embedding generation
   - Supabase integration

## Technology Stack

- **Backend**: FastAPI (Python 3.11+)
- **AI/ML**: OpenAI GPT-4, LangChain, LangGraph
- **OCR**: DocTR, TrOCR, Tesseract
- **Databases**: PostgreSQL, Neo4j, Supabase, Redis
- **Deployment**: Docker, Kubernetes
- **Monitoring**: Prometheus, Grafana

## Getting Help

- **Documentation**: [docs.skydust.app](https://docs.skydust.app)
- **GitHub**: [github.com/sky-dust-intelligence/3wm](https://github.com/sky-dust-intelligence/3wm)
- **Email**: support@skydust.io

---

*Built with ❤️ by [Sky Dust](https://skydust.io)* 