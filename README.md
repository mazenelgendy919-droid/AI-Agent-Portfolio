# Enterprise AI Agent & RAG Engineering Portfolio 🤖🚀

A production-grade portfolio showcasing **Autonomous AI Agents**, **Multi-Agent Systems**, **Retrieval-Augmented Generation (RAG)** architectures, and **Model Fine-Tuning (LoRA)** using Python, LangChain, FastAPI, ChromaDB, and PyTorch.

---

## 🏗️ Core Engineering Concepts & System Architecture

* **Multi-Agent Orchestration**: Controller-routed workflow management preventing agent-to-agent feedback loops via strict schema validation.
* **Retrieval-Augmented Generation (RAG)**: Hybrid context grounding utilizing ChromaDB vector store, semantic similarity embeddings (ll-MiniLM-L6-v2), and semantic caching layers.
* **Structured Output Enforcement**: Pydantic v2 schema validation for deterministic LLM tool calling and API parsing.
* **Parameter-Efficient Fine-Tuning (PEFT)**: Task-specific model adaptation using Low-Rank Adaptation (LoRA) on custom domain datasets.
* **Dynamic Web & API Connectors**: Real-time context expansion via Tavily Search API, GitHub API, and custom function routing.

---

## 📂 Production Systems & Agent Workflows

### 1. 🚀 [Darby — Multi-Agent Career & Learning Platform](./Darby)
* **Architecture**: Full-Stack Multi-Agent Production Architecture
* **Stack**: FastAPI, React (LTR/RTL), ChromaDB RAG, Tavily Search, SQLite
* **Technical Scope**: Coordinates 6 specialized agents (Intent, RAG, Web Research, Recommendation, Critic, Response Agent) using a central orchestrator and strict Pydantic models.

### 2. 💬 Full-Stack AI Agent Chat Application
* **File**: [AI_Agent_Chat_Web_Application_(End_to_End).ipynb](./AI_Agent_Chat_Web_Application_(End_to_End).ipynb)
* **Technical Scope**: End-to-end full-stack agent UI integration, session memory management, and asynchronous tool invocation handling.

### 3. 📧 Automated GenAI Email Assistant Agent
* **File**: [Automated_Generative_AI_Email_Assistant_with_Tools.ipynb](./Automated_Generative_AI_Email_Assistant_with_Tools.ipynb)
* **Technical Scope**: Intelligent email parsing, intent classification, external tool integration for scheduling, and automated draft generation.

### 4. 📊 Collaborative Multi-Agent Report Generator
* **File**: [Collaborative_AI_Report_Generator_(Multi_Agent_System).ipynb](./Collaborative_AI_Report_Generator_(Multi_Agent_System).ipynb)
* **Technical Scope**: Hierarchical multi-agent research framework where researcher agents fetch data and writer agents synthesize structured Markdown reports.

### 5. 🛍️ Autonomous E-Commerce Support & Sales Agent
* **File**: [E_Commerce_Customer_Support_&_Sales_AI_Agent.ipynb](./E_Commerce_Customer_Support_&_Sales_AI_Agent.ipynb)
* **Technical Scope**: Product recommendation pipeline utilizing product catalog lookup, sentiment analysis, and interactive intent handling.

### 6. 🧠 Context-Aware Dynamic Memory Assistant
* **File**: [Context_Aware_Chat_Assistant.ipynb](./Context_Aware_Chat_Assistant.ipynb)
* **Technical Scope**: Dynamic conversation history tracking, context summarization, and long-term user profile extraction.

### 7. 📚 LangChain RAG System Architecture
* **File**: [LangChain_RAG.ipynb](./LangChain_RAG.ipynb)
* **Technical Scope**: Document ingestion pipeline, text chunking strategies, vector index creation, and context-grounded response generation via LangChain.

### 8. 🔍 Native RAG & Vector Database Pipeline
* **File**: [RAG_System.ipynb](./RAG_System.ipynb)
* **Technical Scope**: Custom RAG implementation without high-level wrappers, managing similarity search calculations and prompt context insertion manually.

### 9. 🎯 Structured Output & Schema Enforcement Workflow
* **File**: [Structured_Output.ipynb](./Structured_Output.ipynb)
* **Technical Scope**: Enforcing strict JSON outputs from LLMs for downstream service integration, error recovery, and data validation.

### 10. ⚡ Parameter-Efficient Fine-Tuning (LoRA)
* **File**: [FineTuning.ipynb](./FineTuning.ipynb)
* **Technical Scope**: Fine-tuning open-source LLMs using HuggingFace peft and itsandbytes to adapt model responses to specific domain instructions.

---

## 🛠️ Technical Stack & Ecosystem

* **Core Language**: Python 3.11+
* **Frameworks & Libraries**: FastAPI, LangChain, PyTorch, Pydantic v2
* **Vector DB & Embeddings**: ChromaDB, Sentence-Transformers (ll-MiniLM-L6-v2)
* **LLM Providers & Fine-Tuning**: Google Gemini API, HuggingFace PEFT / LoRA
* **Web Search & Connectors**: Tavily API, REST APIs, SQLite
