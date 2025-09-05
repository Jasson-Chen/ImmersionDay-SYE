# ImmersionDay-SYE
This repository is for Immersion Day for SYE

## Training Overview
This immersion day provides hands-on experience with AWS AI agent frameworks through three key areas:
- **AWS Strands Agents**: Master multi-agent architectures and tool integrations
- **AWS Bedrock AgentCore**: Learn to build and deploy production-ready agents
- **Medical AI Agents**: Explore Complex implementations 


## Repository Structure
```
ImmersionDay-SYE/
├── Strands-Agents-Experiment/
│   ├── fundamental-multi-agents-experiment/
│   │   ├── 01-agent-as-tool/
│   │   │   ├── images/
│   │   │   │   └── architecture.png
│   │   │   ├── agent-as-tools.ipynb
│   │   │   ├── agents-as-tools-interleaved.ipynb
│   │   │   └── requirements.txt
│   │   ├── 02-swarm-agent/
│   │   │   ├── images/
│   │   │   │   └── swarm_example.png
│   │   │   ├── requirements.txt
│   │   │   └── swarm.ipynb
│   │   └── 03-graph-agent/
│   │       ├── images/
│   │       │   ├── basic.png
│   │       │   ├── conditional.png
│   │       │   └── parallel.png
│   │       ├── graph.ipynb
│   │       └── requirements.txt
│   ├── fundamental-tools-experiment/
│   │   ├── 01-using-mcp-tools/
│   │   │   ├── images/
│   │   │   │   ├── architecture_2.png
│   │   │   │   ├── architecture_3.png
│   │   │   │   └── architecture.png
│   │   │   ├── mcp-agent.ipynb
│   │   │   └── requirements.txt
│   │   └── 02-custom-tools/
│   │       ├── images/
│   │       │   └── architecture.png
│   │       ├── custom-tools-with-strands-agents.ipynb
│   │       └── requirements.txt
│   └── strands-quick-start/
│       ├── images/
│       │   ├── agent_with_tools.png
│       │   ├── interactive_recipe_agent.png
│       │   └── simple_agent.png
│       ├── requirements.txt
│       └── strands-quick-start.ipynb
├── RAG-Agents-Experiment/
│   ├── images/
│   │   └── architecture.png
│   ├── sample_structured_data/
│   │   ├── order_items.csv
│   │   ├── orders.csv
│   │   ├── payments.csv
│   │   └── reviews.csv
│   ├── sample_unstructured_data/
│   │   └── octank_financial_10K.pdf
│   ├── utils/
│   │   ├── knowledge_base.py
│   │   └── structured_knowledge_base.py
│   ├── 0-prerequisites-structured-kb.ipynb
│   ├── 1-prerequisites-unstructured-kb.ipynb
│   ├── 2-unstructured-structured-rag-agent.ipynb
│   └── README.md
├── Agentcore-Experiment/
│   ├── agentcore-browser-use/
│   │   ├── app_reviews_agentcore_simple.py
│   │   ├── requirements.txt
│   │   └── run_browser_use.ipynb
│   └── agentcore-quick-start/
│       ├── images/
│       │   ├── architecture_local.png
│       │   ├── architecture_runtime.png
│       │   ├── configure.png
│       │   ├── invoke.png
│       │   └── launch.png
│       ├── agentcore-quick-start.ipynb
│       └── requirements.txt
├── README.md
└── requirements.txt

```

## Experiment Description

### Agentcore-Experiment
Experiments with AWS Bedrock AgentCore framework
- **agentcore-browser-use**: Browser automation agent implementation
- **agentcore-quick-start**: Getting started guide and examples

### Medical-Agents-Experiment
Medical domain-specific agent implementations
- Document processing and medical coding tools

### Strands-Agents-Experiment
Experiments with AWS Strands Agents framework
- **fundamental-multi-agents-experiment**: Multi-agent patterns and architectures
  - **01-agent-as-tool**: Using agents as tools in workflows
  - **02-swarm-agent**: Swarm-based agent coordination
  - **03-graph-agent**: Graph-based agent workflows
- **fundamental-tools-experiment**: Tool integration patterns
  - **01-using-mcp-tools**: Model Context Protocol (MCP) tools integration
  - **02-custom-tools**: Custom tool development
- **strands-quick-start**: Getting started with Strands Agents
