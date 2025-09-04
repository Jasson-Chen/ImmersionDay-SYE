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
├── Agentcore-Experiment/
│   ├── agentcore-browser-use/
│   │   ├── app_reviews_agentcore_simple.py
│   │   ├── requirements.txt
│   │   └── run_browser_use.ipynb
│   └── agentcore-quick-start/
│       ├── images/
│       ├── agentcore-quick-start.ipynb
│       └── requirements.txt
├── Medical-Agents-Experiment/
│   ├── images/
│   ├── document_processor.py
│   ├── main.py
│   └── medical_coding_tools.py
├── Strands-Agents-Experiment/
│   ├── fundamental-multi-agents-experiment/
│   │   ├── 01-agent-as-tool/
│   │   │   ├── images/
│   │   │   ├── agent-as-tools.ipynb
│   │   │   ├── agents-as-tools-interleaved.ipynb
│   │   │   └── requirements.txt
│   │   ├── 02-swarm-agent/
│   │   │   ├── images/
│   │   │   ├── requirements.txt
│   │   │   └── swarm.ipynb
│   │   └── 03-graph-agent/
│   │       ├── images/
│   │       ├── graph.ipynb
│   │       └── requirements.txt
│   ├── fundamental-tools-experiment/
│   │   ├── 01-using-mcp-tools/
│   │   │   ├── images/
│   │   │   ├── mcp-agent.ipynb
│   │   │   └── requirements.txt
│   │   └── 02-custom-tools/
│   │       ├── images/
│   │       ├── custom-tools-with-strands-agents.ipynb
│   │       └── requirements.txt
│   └── strands-quick-start/
│       ├── images/
│       └── strands-quick-start.ipynb
└── README.md
```

## Folder Structure

### Agentcore-Experiment/
Experiments with AWS Bedrock AgentCore framework
- **agentcore-browser-use/**: Browser automation agent implementation
- **agentcore-quick-start/**: Getting started guide and examples

### Medical-Agents-Experiment/
Medical domain-specific agent implementations
- Document processing and medical coding tools

### Strands-Agents-Experiment/
Experiments with AWS Strands Agents framework
- **fundamental-multi-agents-experiment/**: Multi-agent patterns and architectures
  - **01-agent-as-tool/**: Using agents as tools in workflows
  - **02-swarm-agent/**: Swarm-based agent coordination
  - **03-graph-agent/**: Graph-based agent workflows
- **fundamental-tools-experiment/**: Tool integration patterns
  - **01-using-mcp-tools/**: Model Context Protocol (MCP) tools integration
  - **02-custom-tools/**: Custom tool development
- **strands-quick-start/**: Getting started with Strands Agents