# 3WM Mermaid Diagrams

This directory contains standalone Mermaid diagram files for the 3WM AI Document Intelligence system documentation.

## Available Diagrams

### 1. Component Architecture (`3WM-component-architecture.mmd`)
Shows the layered architecture of the system including:
- Frontend Layer (Web UI, CLI Tools)
- API Layer (FastAPI, Auth, Rate Limiting)
- Business Logic (AI Agent, OCR, Field Extraction, etc.)
- Data Layer (PostgreSQL, Redis, Neo4j, Supabase)
- External Services (OpenAI, Anthropic, Search APIs)

### 2. System Workflow (`3WM-system-workflow.mmd`)
Complete system workflow showing:
- Document Upload & Processing flow
- Invoice-specific processing
- Batch processing workflow
- AI Agent (LangGraph) workflow
- Authentication flow
- Neo4j graph operations
- Journal entry prediction
- Infrastructure monitoring
- Supplier enrichment

### 3. State Diagrams (`3WM-state-diagrams.mmd`)
State machines for:
- Document lifecycle states
- Invoice processing states
- AI Agent query states
- User session states
- Batch processor states
- Neo4j transaction states

### 4. Invoice Pipeline (`3WM-invoice-pipeline.mmd`)
Simplified high-level view of the invoice processing pipeline:
- Exchange Online → AI Processing → AccountView

### 5. Confidence Routing (`3WM-confidence-routing.mmd`)
Shows the confidence-based routing decision tree:
- 95-100%: Automatic booking (~85% of invoices)
- 80-94%: Human review (~12% of invoices)
- <80%: Manual entry (~3% of invoices)

## Usage

These diagrams can be:
1. Viewed in any Mermaid-compatible viewer
2. Embedded in Markdown documentation using:
   ```markdown
   ```mermaid
   [paste diagram content here]
   ```
   ```
3. Rendered using the Mermaid CLI tool
4. Integrated into the Mintlify documentation system

## Mermaid Documentation

For more information about Mermaid syntax and features, visit:
- [Mermaid Official Documentation](https://mermaid.js.org/)
- [Mermaid Live Editor](https://mermaid.live/) 