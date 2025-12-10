## Financial Analysis Multi-Agent System
This project builds a Financial Analysis Multi-Agent System (MAS) designed for financial decision support.
The system uses NANDA multi-agent architecture with full A2A (Agent-to-Agent) communication, allowing agents to collaborate, exchange financial insights, and perform automated risk evaluation workflows.

This MAS demonstrates how multiple intelligent agents can share context, assess financial data, and support decision-making through distributed problem solving.

## 📁 Project Structure
streamlined-adapter/        # Core adapter enabling A2A + MCP communication
demo.py                     # End-to-end demo for financial decision support
demo_agents.sh              # Script to launch all agents locally
deploy-to-linode-test.sh    # Deployment script for cloud testing on Linode
my-nanda-agents-config.json # Local agent configuration for registration
test.py                     # Unit tests for agent communication
DEMO GUIDE.md               # Step-by-step running guide
ALY6980_Bibliography.docx   # Literature and source references
README.md                   # Project documentation (this file)

## 🚀 Project Objective
“Build a financial analysis multi-agent system for financial decision support, with full A2A communication.”

The system demonstrates how:

Multiple agents cooperate

Agents analyze financial data

Agents pass risk information

An adapter transforms and routes MCP contexts

Decision support emerges through agent collaboration

## 🧠 System Overview

Our MAS includes domain-specific financial agents:

Agent	Description
Risk Assessment Agent	Computes risk score, evaluates financial indicators
Finance Analysis Agent	Retrieves financial information and trends
Streamlined Adapter	Enables A2A communication + MCP translation
Demo Controller Agent	Orchestrates the workflow end-to-end

The architecture supports:

✔ Distributed decision-making
✔ Real-time A2A context sharing
✔ Extensible finance-domain agent collaboration
## 🔄 A2A Communication Workflow

Finance Agent retrieves stock or financial data

Sends information to the Risk Assessment Agent

Risk Agent computes:

Volatility

Financial ratios

Overall risk score

Decision Support Output returned through A2A

Streamlined Adapter ensures correct routing + MCP formatting

This models how real financial systems evaluate multiple factors via distributed services.

## ▶️ How to Run the Project
1. Install Dependencies
pip install -r requirements.txt

2. Start All Local Agents
bash demo_agents.sh

3. Run Financial Decision Support Demo
python demo.py

4. Cloud Deployment (Linode)
bash deploy-to-linode-test.sh

## 🧪 Testing A2A and Agent Logic
Run communication tests:
python test.py

Test individual agent behavior:
python demo.py --agent risk

## 📚 Documentation

DEMO GUIDE.md — Instructions for running agents and A2A workflow

Bibliography.docx — Academic and research references
