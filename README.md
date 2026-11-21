# Course Agent Design Pattern

## Agentic Design Patterns

This course repository is dedicated to **Asma Mestaysser** and presents practical examples, notebooks, and learning materials for the **Agentic Design Patterns** book by **Antonio Gulli**.

## Book Information

- **Title:** _Agentic Design Patterns: A Hands-On Guide to Building Intelligent Systems_
- **Author:** Antonio Gulli
- **LinkedIn:** [Antonio Gulli](https://www.linkedin.com/in/searchguy/)
- **Pre-order:** [Amazon](https://www.amazon.com/Agentic-Design-Patterns-Hands-Intelligent/dp/3032014018/)
- **Charity:** All author royalties are donated to Save the Children.
- **Table of Contents:** [Google Docs](https://docs.google.com/document/d/1rsaK53T3Lg5KoGwvf8ukOUvbELRtH-V0LnOIFDxBryE/edit)
- **Course Resources:** [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1Y3U3IrYCiJ3E45Z8okR5eCg7OPnWQtPV)

## Course Attribution

**Course repository and educational adaptation:** Asma Mestaysser

- **GitHub:** [@asmamest](https://github.com/asmamest)
- **LinkedIn:** [Asma Mestaysser](https://www.linkedin.com/in/asmamestaysser/)

The original book and its intellectual authorship remain attributed to Antonio Gulli. This repository is an independent course project created for learning and applying the book's agentic design patterns.

## About the Course

Agentic design patterns are reusable approaches for solving recurring problems in intelligent-agent systems. This course explores how AI agents can chain prompts, route tasks, execute work in parallel, reflect on results, use tools, plan actions, collaborate, retain memory, communicate, and operate safely.

The material combines conceptual explanations with hands-on Python notebooks. The examples use several frameworks, including Google ADK, LangChain, LangGraph, CrewAI, MCP, Pydantic, and related AI services.

## Learning Goals

By completing this course, learners should be able to:

- Understand the core components of an agentic system.
- Identify where a design pattern is appropriate.
- Implement agents with LLMs, tools, memory, and structured workflows.
- Compare framework-specific implementations of the same pattern.
- Add validation, guardrails, evaluation, and recovery behavior.
- Design maintainable systems for real-world agentic applications.

## Chapter Coverage

| Chapter | Pattern | Key topics |
|---|---|---|
| 1 | Prompt Chaining | Sequential workflows and structured JSON examples |
| 2 | Routing | Dynamic task selection with Google ADK and LangChain |
| 3 | Parallelization | Concurrent agent and task execution |
| 4 | Reflection | Iterative improvement and validation loops |
| 5 | Tool Use | External tools, code execution, and AI-powered search |
| 6 | Planning | Goal decomposition and deep-research workflows |
| 7 | Multi-Agent | Agent coordination, delegation, loops, and parallel/sequential collaboration |
| 8 | Memory | Session state, memory services, and LangGraph |
| 9 | Adaptation | Agent learning and evolutionary optimization |
| 10 | MCP | MCP clients and servers, filesystem tools, and Google ADK |
| 11 | Goal Setting | Iterative progress toward explicit goals |
| 12 | Exception Handling | Fallback and recovery strategies |
| 13 | Human-in-the-Loop | Human review and customer-support workflows |
| 14 | Knowledge Retrieval | RAG with Google Search, LangChain, and Vertex AI |
| 15 | Inter-Agent Communication | A2A protocols, agent cards, and streaming requests |
| 16 | Resource-Aware Optimization | Cost, search, and resource-aware execution |
| 17 | Reasoning | Chain-of-thought prompts, code, search, and self-correction |
| 18 | Guardrails | Tool validation, safety prompts, and practical safeguards |
| 19 | Evaluation | Response evaluation and LLM-as-a-Judge |
| 20 | Prioritization | Task ranking and project-management examples |
| 21 | Exploration and Discovery | Agent-based experimentation and discovery |

## Appendices

The repository may include:

- Advanced prompting techniques
- Agentic AI from graphical interfaces to real-world environments
- Pydantic examples
- Agentic framework overviews
- AgentSpace and CLI agent examples
- Reasoning engines
- Coding agents

## Repository Structure

Notebook filenames follow this convention:

```text
Chapter_XX_Topic_(Variant).ipynb
Appendix_<Name>.ipynb
```

Each chapter may contain multiple notebooks for different frameworks or implementation strategies.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/asmamest/agentic-design-patterns.git
cd agentic-design-patterns
```

### 2. Create a Python Environment

Python 3.11 or later is recommended.

```bash
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

Activate it on Linux or macOS:

```bash
source .venv/bin/activate
```

### 3. Install Jupyter

```bash
python -m pip install --upgrade pip
pip install jupyter notebook ipykernel
```

Additional notebook-specific dependencies may be required. Review each notebook before running it.

### 4. Configure API Credentials

Some notebooks require API keys for model providers or external services. Set those credentials using environment variables and never commit secrets to this repository.

Example:

```bash
GOOGLE_API_KEY=your_api_key
OPENAI_API_KEY=your_api_key
ANTHROPIC_API_KEY=your_api_key
```

### 5. Launch Jupyter

```bash
jupyter lab
```

Alternatively:

```bash
jupyter notebook
```

Open a chapter notebook and run the cells from top to bottom.

## How to Use the Notebooks

1. Read the surrounding chapter concept.
2. Open the notebook and inspect the setup cells.
3. Configure any required API credentials locally.
4. Run the notebook step by step.
5. Change prompts or parameters and observe the result.
6. Compare the different framework implementations when more than one is provided.

## Frameworks and Technologies

Depending on the notebook, the course may use:

- Google ADK
- LangChain and LangGraph
- CrewAI
- OpenAI APIs
- Google Gemini and Vertex AI
- Model Context Protocol
- Pydantic
- Jupyter
- Python

Framework APIs may change over time. Use each implementation as a starting point and verify it against the official framework documentation.

## Contributing

Contributions are welcome. When proposing changes:

- Keep notebook names consistent.
- Preserve the original book attribution.
- Attribute course additions to Asma Mestaysser.
- Remove credentials and private data before committing.
- Use clear commit messages and focused pull requests.
- Describe the framework or chapter covered in the pull request.

## License

See [LICENSE](LICENSE) for the repository license terms.

## Credits

- **Original Book Author:** Antonio Gulli
- **Course Repository and Attribution:** Asma Mestaysser

---

_A hands-on course for understanding and building intelligent agentic systems._
