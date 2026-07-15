# ICT 2022 Mentorship Knowledge Graph

> A comprehensive, interconnected knowledge graph of the ICT (Inner Circle Trader) 2022 Mentorship, designed for both **human learning** and **AI-powered reasoning**.

---

## Vision

Most trading notes are written for humans.

This project is written for **both humans and AI agents**.

Every concept is broken into small, interconnected pieces of knowledge that can be traversed like a graph, allowing both traders and Large Language Models (LLMs) to understand the relationships between concepts instead of treating them as isolated notes.

The goal is to build a **second brain** for the ICT 2022 Mentorship.

---

# Why?

The ICT Mentorship contains hundreds of concepts that build upon one another.

Examples:

- Liquidity
- Fair Value Gaps
- Order Blocks
- Draw on Liquidity
- Market Structure
- SMT Divergence
- Power of Three
- Daily Bias
- Institutional Order Flow

Reading these topics individually often misses the bigger picture.

This repository connects every concept together so that understanding naturally emerges from the relationships.

---

# Built For

## Human Learners

- Learn concepts in context
- Follow linked ideas naturally
- Understand relationships instead of memorizing
- Quickly navigate between topics
- Build intuition through interconnected knowledge

---

## AI Agents

This repository is intentionally structured to be AI-friendly.

It can be used as a knowledge base for:

- RAG (Retrieval Augmented Generation)
- Agentic trading assistants
- Personal AI tutors
- Obsidian MCP Servers
- Claude Code
- Cursor
- Roo Code
- OpenAI Agents
- LangGraph
- LlamaIndex
- Knowledge Graph Retrieval
- Vector Databases

Because every concept is atomic and heavily linked, AI agents can traverse the graph and reason over related concepts instead of relying on isolated documents.

---

# Repository Structure

```
.
├── .obsidian/
├── concepts/
├── episodes/
└── ICT-trading.md
```

## concepts/

Individual notes explaining every ICT concept.

Examples:

- Liquidity
- Draw on Liquidity
- Fair Value Gap
- Order Blocks
- Breakers
- Market Structure
- Displacement
- Power of Three
- SMT Divergence
- Daily Bias
- Institutional Order Flow
- Trading Sessions
- Risk Management
- Trading Psychology

Each note contains:

- Definition
- Purpose
- Related Concepts
- Examples
- Charts
- Mentorship References

---

## episodes/

Summaries for each ICT mentorship episode.

Each episode includes:

- Summary
- Major concepts introduced
- Important observations
- Charts
- Links to concepts

---

## ICT-trading.md

The vault homepage.

Acts as the primary navigation hub for the entire knowledge graph.

---

# Knowledge Graph Philosophy

Every note should answer only one question.

Instead of writing large documents, knowledge is decomposed into atomic concepts.

Example:

```
Market Structure
        │
        ▼
Displacement
        │
        ▼
Fair Value Gap
        │
        ▼
Order Block
        │
        ▼
Liquidity
```

Every node links to related nodes.

This creates a graph that both humans and AI systems can navigate efficiently.

---

# Core Topics

- Market Structure
- Liquidity
- Internal Range Liquidity
- External Range Liquidity
- Fair Value Gaps
- Order Blocks
- Breakers
- Mitigation Blocks
- Draw on Liquidity
- Institutional Order Flow
- Premium & Discount
- OTE
- Power of Three
- Judas Swing
- SMT Divergence
- Trading Sessions
- Daily Bias
- Weekly Bias
- Market Narrative
- Risk Management
- Trading Psychology

---

# AI Design Principles

This repository follows several principles to maximize AI usability.

## Atomic Notes

Each note explains one concept.

## Rich Internal Links

Concepts reference related concepts extensively.

## Minimal Duplication

Knowledge is stored once and referenced everywhere else.

## Semantic Relationships

Relationships between concepts are explicit rather than implied.

## Graph Traversal

AI agents can move naturally through the graph using backlinks and links.

## Retrieval Friendly

Small focused notes improve retrieval quality for RAG pipelines.

---

# Example Use Cases

## Learning

A trader asks:

> Why did price reverse?

The graph naturally leads through:

```
Market Structure
↓

Liquidity

↓

Displacement

↓

Fair Value Gap

↓

Order Block

↓

Continuation
```

---

## AI Tutor

An AI mentor can answer:

- Explain liquidity.
- Show concepts related to liquidity.
- Which mentorship episodes discuss liquidity?
- What should I learn before Fair Value Gaps?
- How does Draw on Liquidity relate to SMT?

---

## Trading Assistant

An AI assistant can use the graph to:

- Explain charts
- Identify missing concepts
- Suggest prerequisite reading
- Generate quizzes
- Build learning paths
- Answer ICT questions using graph context

---

# Recommended Software

Designed primarily for:

- Obsidian
- Graph View
- Canvas
- Dataview
- Excalidraw

Can also power:

- MCP Servers
- Vector Databases
- Knowledge Graph Systems
- RAG Pipelines
- AI Coding Agents

---

# Disclaimer

This repository is an educational knowledge base inspired by the ICT 2022 Mentorship.

It is not affiliated with or endorsed by Inner Circle Trader (ICT).

Nothing contained here constitutes financial advice.

---

# Vision

The long-term vision is to create the most complete open knowledge graph of the ICT 2022 Mentorship.

Not merely a collection of notes—but a structured network of knowledge that enables both **people and AI agents** to reason about institutional trading concepts, discover relationships, and accelerate learning.