# LangFlow Flows Repository  

This repository contains various **LangFlow** JSON files representing different AI-powered workflows. These flows can be imported into **LangFlow**, a no-code UI for **LangChain**, to experiment with and modify Large Language Model (LLM) pipelines.  

## 📌 About LangFlow  
[LangFlow](https://github.com/langflow-ai/langflow) is an intuitive, drag-and-drop web interface for prototyping **LangChain** flows. It allows users to:  
- **Visually build** AI workflows using LLMs.  
- **Edit and fine-tune** parameters for prompts, models, and vector stores.  
- **Create and modify** LangChain agents and chains interactively.  
- **Track thought processes** of AI agents in real time.  
- **Export and share** workflows as JSON files.  

---

## 📂 Repository Structure  

```
LangFlow-Flows/
│── Custom_Component/
│    ├── Create List.json
│
│── RAG/
│    ├── LinkedIn Vector Store Rag Updated.json
│    ├── LinkedIn Vector Store Rag.json
│    ├── Linked_SavedItems_Vector Search rag.json
│
│── Sequential_Agent_Source_Retrieval/
│    ├── Sequential_Agent(Vector_rag__source_retrieval).json
│
│── README.md  <-- (You are here)
```

---

## 🚀 How to Import LangFlow JSON Files  

Follow these steps to import any JSON flow into **LangFlow**:  

### **Step 1: Install and Run LangFlow**  
If you haven't installed LangFlow yet, follow these instructions:  

#### **Using pip** (Recommended)  
```bash
pip install langflow
langflow run
```

#### **Using Docker**  
```bash
docker pull ghcr.io/langflow-ai/langflow:latest
docker run -p 7860:7860 ghcr.io/langflow-ai/langflow:latest
```

LangFlow should now be running at `http://localhost:7860`.

---

### **Step 2: Import a JSON Flow**  

1. **Open LangFlow** in your browser at `http://localhost:7860`.  
2. Click on **"Import"** in the LangFlow UI.  
3. Select a `.json` file from this repository (e.g., `RAG/LinkedIn Vector Store Rag.json`).  
4. Click **"Open"** to load the flow.  
5. The flow will appear in the editor—modify, test, and save as needed.  

---

## 🛠️ Contributing  
If you have modifications or improvements to these flows, feel free to fork this repository, update the JSON files, and submit a pull request.  

---

## 📜 License  
This repository is open-source. You are free to use, modify, and distribute the flows under the **MIT License**.  

---

## 🔗 Resources  
- 📖 **LangFlow Docs:** [https://docs.langflow.org](https://docs.langflow.org)  
- 🏗️ **LangChain Docs:** [https://python.langchain.com](https://python.langchain.com)  
- 💬 **Join the Community:** [LangFlow Discord](https://discord.gg/langflow)  
