# Enterprise AI Agent & RAG Engineering Portfolio 🤖🚀

A production-grade portfolio showcasing **Autonomous AI Agents**, **Multi-Agent Systems**, **Retrieval-Augmented Generation (RAG)** architectures, and **Model Fine-Tuning (LoRA)** engineered using Python, LangChain, ChromaDB, and PyTorch.

---

## 📌 Executive Architecture & Engineering Concepts

This repository demonstrates advanced LLM orchestration, structured grounding, and production patterns:
* **Multi-Agent Control Routing**: Central controller-based orchestration enforcing strict schema constraints (Pydantic v2) to avoid infinite feedback loops.
* **Retrieval-Augmented Generation (RAG)**: Hybrid vector retrieval leveraging ChromaDB, sentence-transformer embeddings (ll-MiniLM-L6-v2), and semantic caching layers.
* **Structured Output Enforcement**: Validating LLM function calling and JSON schemas for deterministic integration with enterprise microservices.
* **Parameter-Efficient Fine-Tuning (PEFT)**: Task-specific domain adaptation using Low-Rank Adaptation (LoRA) on custom domain datasets.

---

## 📂 Featured Production Systems & Notebook Workflows

### 1. 🚀 [Darby — Multi-Agent Career & Learning Platform](./Darby_(Find_your_path_in_tech).ipynb)
* **Type**: Flagship Multi-Agent Architecture
* **Stack**: Python, LangChain, ChromaDB RAG, Tavily Search
* **Technical Scope**: Coordinates 6 specialized agents (Intent, RAG, Web Research, Recommendation, Critic, Response Agent) via a central orchestrator.

### 2. 💬 [Full-Stack AI Agent Chat Web Application](./AI_Agent_Chat_Web_Application_(End_to_End).ipynb)
* **Type**: Interactive Agent Notebook
* **Technical Scope**: End-to-end full-stack agent UI integration, session memory management, and dynamic tool invocation handling.

### 3. 📧 [Automated GenAI Email Assistant with Tools](./Automated_Generative_AI_Email_Assistant_with_Tools.ipynb)
* **Type**: Autonomous Tool-Calling Agent
* **Technical Scope**: Email parsing, intent classification, external tool integration for scheduling, and automated draft generation.

### 4. 📊 [Collaborative AI Report Generator](./Collaborative_AI_Report_Generator_(Multi_Agent_System).ipynb)
* **Type**: Multi-Agent Research System
* **Technical Scope**: Hierarchical multi-agent research framework where researcher agents fetch data and writer agents synthesize structured Markdown reports.

### 5. 🛍️ [E-Commerce Customer Support & Sales Agent](./E_Commerce_Customer_Support_&_Sales_AI_Agent.ipynb)
* **Type**: Customer Interaction Workflow
* **Technical Scope**: Autonomous product recommendation pipeline utilizing catalog lookup, sentiment analysis, and interactive intent handling.

### 6. 🧠 [Context-Aware Dynamic Memory Chat Assistant](./Context_Aware_Chat_Assistant.ipynb)
* **Type**: Long-Term Memory Assistant
* **Technical Scope**: Dynamic conversation history tracking, context summarization, and long-term user profile extraction.

### 7. 📚 [LangChain RAG Architecture Pipeline](./LangChain_RAG.ipynb)
* **Type**: Vector Retrieval Pipeline
* **Technical Scope**: Document ingestion pipeline, text chunking strategies, vector index creation, and context-grounded response generation via LangChain.

### 8. 🔍 [Native RAG System Architecture](./RAG_System.ipynb)
* **Type**: Low-Level RAG Implementation
* **Technical Scope**: Custom RAG implementation without high-level wrappers, managing similarity search calculations and prompt context insertion manually.

### 9. 🎯 [Structured Output Workflow](./Structured_Output.ipynb.ipynb)
* **Type**: Function Calling & Validation
* **Technical Scope**: Enforcing strict JSON outputs from LLMs for downstream service integration, error recovery, and schema validation.

### 10. ⚡ [Parameter-Efficient Fine-Tuning (LoRA)](./FineTuning.ipynb)
* **Type**: PEFT / Model Adaptation
* **Technical Scope**: Fine-tuning open-source LLMs using HuggingFace peft and itsandbytes to adapt model responses to specific domain instructions.

### 11. ⚙️ [Core AI Agent Patterns & Reasoning Loops](./AI_Agent.ipynb)
* **Type**: Agent Fundamentals
* **Technical Scope**: Demonstrates core ReAct loops, prompt decomposition, and decision execution frameworks.

---

## 🛠️ Technical Stack & Tools

* **Core Language**: Python 3.11+
* **Frameworks & Libraries**: LangChain, PyTorch, Pydantic v2
* **Vector DB & Embeddings**: ChromaDB, Sentence-Transformers (ll-MiniLM-L6-v2)
* **LLM Providers & Fine-Tuning**: Google Gemini API, HuggingFace PEFT / LoRA
* **Web Search & Connectors**: Tavily API, REST APIs, SQLite
