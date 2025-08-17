# Local LLM Showcase (Ollama + LangChain)

Demonstrating hands-on experience building local AI agents using Ollama and LangChain—no cloud, just pure code.

---

##  Video Walkthrough  
Watch the step-by-step setup: **Build Local Free AI: Ollama + LangChain**  
▶  https://youtu.be/3VQdn6X9veM :contentReference[oaicite:1]{index=1}

---

##  Code Repository  
All code used in the demo:  
- [PoaiOllama GitHub Repo](https://github.com/matinict/PoaiOllama)

---

##  Project Highlights

- **Offline-first AI**: Builds LLM-powered assistants locally using Ollama.
- **LangChain integration**: Seamlessly connects LLM with LangChain frameworks.
- **Model flexibility**: Supports local models like DeepSeek-R1, Llama3, and more.
- **Tools ready**: Ideal for prototyping agents, RAG, or private deployments.

---

##  Quick Setup (from the demo)

```bash
# Install Ollama
curl -fsSL https://ollama.com/install.sh | sh

# Download a model
ollama pull llama3:latest

# Run locally with LangChain
# (See code in PoaiOllama repo)
