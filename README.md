# Agentic Design Patterns

Hands-on notebooks for learning, implementing, and comparing agentic design patterns.

**Repository:** [asmamest/agentic-design-patterns](https://github.com/asmamest/agentic-design-patterns.git)

## About

This course explores reusable patterns for building AI agents and agent-based systems. The material combines concise implementations with multiple frameworks and provider-specific examples.

The repository contains 21 chapter topics, 56 implementation notebooks under `Chapters/`, and 9 appendix notebooks.

## Repository Structure

```text
COURSE-DESIGN-PATTERNS/
├── Chapters/
│   ├── Chapter_01_Prompt_Chaining_*.ipynb
│   ├── Chapter_02_Routing_*.ipynb
│   ├── Chapter_03_Parallelization_*.ipynb
│   ├── Chapter_04_Reflection_*.ipynb
│   ├── Chapter_05_Tool_Use_*.ipynb
│   ├── Chapter_06_Planning_*.ipynb
│   ├── Chapter_07_Multi_Agent_*.ipynb
│   ├── Chapter_08_Memory_*.ipynb
│   ├── Chapter_09_Adaptation_*.ipynb
│   ├── Chapter_10_MCP_*.ipynb
│   └── Chapter_11_*.ipynb through Chapter_21_*.ipynb
├── Appendix/
│   ├── Appendix_A_Advanced_Prompting_Techniques.ipynb
│   ├── Appendix_B_AI_Agentic_From_GUI_to_Real_world_environment.ipynb
│   ├── Appendix_C_(Code).ipynb
│   ├── Appendix_C_Quick_overview_of_Agentic_Frameworks.ipynb
│   ├── Appendix_D_Building_an_Agent_with_AgentSpace.ipynb
│   ├── Appendix_E_AI_Agents_on_the_CLI.ipynb
│   ├── Appendix_F_Under_the_Hood_Reasoning_Engines.ipynb
│   ├── Appendix_G_Coding_agents.ipynb
│   └── Appendix_Pydantic.ipynb
├── CONTRIBUTING.md
└── README.md
```

## Chapter Index

| Chapter | Topic | Implementations |
|---|---|---|
| 01 | Prompt Chaining | Code, JSON |
| 02 | Routing | Google ADK, LangChain |
| 03 | Parallelization | Google ADK, LangChain |
| 04 | Reflection | ADK, iterative loop, LangChain |
| 05 | Tool Use | CrewAI, code execution, Google Search, LangChain, Vertex AI Search |
| 06 | Planning | Code example, Deep Research API |
| 07 | Multi-Agent Systems | ADK Gemini agent tool, coordinator, loop, parallel, sequential; CrewAI Gemini |
| 08 | Memory | ADK explicit state, output key, in-memory memory, session service; LangChain/LangGraph |
| 09 | Adaptation | OpenEvolve |
| 10 | Model Context Protocol | ADK and FastMCP server/client; filesystem examples |
| 11 | Goal Setting and Monitoring | Iteration |
| 12 | Exception Handling and Recovery | Fallback |
| 13 | Human-in-the-Loop | Customer support |
| 14 | Knowledge Retrieval | RAG with Google Search, LangChain, Vertex AI |
| 15 | Inter-Agent Communication | A2A, agent cards, sync and streaming requests |
| 16 | Resource-Aware Optimization | OpenRouter, code snippets, Google Search |
| 17 | Reasoning | Chain-of-thought prompt, code execution, Google Deep Search, self-correction |
| 18 | Guardrails and Safety | ADK tool validation, LLM guardrail, practical examples |
| 19 | Evaluation and Monitoring | Basic response evaluation, LLM-as-judge |
| 20 | Prioritization | SuperSimplePM |
| 21 | Exploration and Discovery | Agent laboratory |

Open a notebook under [Chapters](./Chapters/) for the implementation and framework-specific examples.

## Appendices

| Appendix | Topic |
|---|---|
| A | Advanced prompting techniques |
| B | Agentic AI from GUI to real-world environments |
| C | Agentic framework code and framework overview |
| D | Building an agent with AgentSpace |
| E | AI agents on the CLI |
| F | Reasoning engines |
| G | Coding agents |
| Pydantic | Pydantic with agentic examples |

Open the supporting material under [Appendix](./Appendix/).

## Frameworks and Tools

The notebooks use or demonstrate:

- Google ADK
- LangChain and LangGraph
- CrewAI
- FastMCP
- Agent2Agent (A2A)
- OpenEvolve
- OpenRouter
- Google Search and Vertex AI
- Pydantic
- Jupyter, Google Colab, and Python

Framework availability and provider requirements vary by notebook.

## Getting Started

### Prerequisites

- Python 3.10 or later
- JupyterLab or Jupyter Notebook
- Provider API credentials where required

### Local Setup

```bash
git clone https://github.com/asmamest/COURSE-DESIGN-PATTERNS.git
cd COURSE-DESIGN-PATTERNS

python -m venv .venv
```

Activate the environment:

```powershell
.venv\Scripts\Activate.ps1
```

```bash
source .venv/bin/activate
```

Install Jupyter and notebook dependencies:

```bash
python -m pip install --upgrade pip
pip install jupyterlab python-dotenv
```

Open Jupyter:

```bash
jupyter lab
```

The notebooks depend on different packages and providers. Install only the packages imported by the notebook you run. The repository does not currently contain a single shared `requirements.txt`.

### Google Colab

Any notebook can be opened in Google Colab. Colab-specific notebooks may require a Google account and access to Google Drive or provider credentials.

### API Credentials

Configure only the credentials used by the selected notebook.

```text
OPENAI_API_KEY=...
GOOGLE_API_KEY=...
ANTHROPIC_API_KEY=...
OPENROUTER_API_KEY=...
```

Do not commit credentials or `.env` files.

## Recommended Learning Order

1. Start with Chapter 01: Prompt Chaining.
2. Continue through Chapters 02 to 07.
3. Add Memory, Adaptation, and MCP from Chapters 08 to 10.
4. Continue through Chapters 11 to 21 in numerical order.
5. Use the appendices as reference material or for broader framework and tooling context.

Compare the framework variants within Chapters 02, 03, 04, 05, 07, 08, 14, and 16 to identify differences in orchestration and execution.

## Notebook Usage

1. Open the notebook.
2. Read the setup cells.
3. Install the imports required by that notebook.
4. Configure credentials only when required.
5. Run the cells in order.
6. Change inputs or prompts and compare the results.

Some MCP, filesystem, agent server, Google ADK, and Deep Research examples require separate local processes or external services.

## Contributing

Read [CONTRIBUTING.md](./CONTRIBUTING.md) before submitting changes.

Contributions should preserve the current folder and notebook naming conventions and should not include credentials or private data.

## Attribution

This educational repository follows and preserves material attributed to Antonio Gulli.

## Author

**Asma Mestaysser**

- GitHub: [@asmamest](https://github.com/asmamest)
- LinkedIn: [Asma Mestaysser](https://www.linkedin.com/in/asmamestaysser/)
