# AI Disaster Response Commander

An AI-powered disaster response simulation that prioritizes victims, coordinates rescue resources, and replans when situations change.

## 🚨 About the Project

AI Disaster Response Commander is a synthetic disaster-response command system designed to demonstrate how AI agents can support emergency decision-making.

The system simulates a high-severity flood scenario in Green Valley. It analyzes victim conditions, prioritizes people based on urgency, assigns available response resources, requests human approval, executes the response plan in simulation, and replans when resources become unavailable.

> ⚠️ This project is a simulation only. It does not control real drones, rescue teams, emergency services, hospitals, or vehicles. All victims, locations, and operations are synthetic.

## ✨ Key Features

- 🧠 AI-powered disaster situation analysis
- 🚑 Victim prioritization based on urgency and risk
- 🚁 Simulated drone coordination
- 👥 Simulated rescue-team coordination
- 📦 Emergency-kit allocation
- 👨‍✈️ Human approval before response execution
- 📊 Live response monitoring dashboard
- 🔄 Automatic replanning when resources fail
- 🔐 Safety-focused human-in-the-loop workflow
- 💬 Simulated victim communication
- 👁️ Drone-based simulated visual assessment

## 🔄 How It Works

```text
Disaster Situation
        ↓
Situation Analysis
        ↓
Victim Prioritization
        ↓
Resource Assessment
        ↓
Response Plan
        ↓
Human Approval
        ↓
Simulated Execution
        ↓
Situation Monitoring
        ↓
Resource Failure / Change
        ↓
AI Replanning

## 🔄 Main Workflow

1. Disaster situation is loaded.
2. AI analyzes the situation.
3. Victims are prioritized based on urgency and risk.
4. Available drones, rescue teams, and emergency kits are assessed.
5. AI generates a response plan.
6. Human approval is required before execution.
7. The response is executed in simulation.
8. The system monitors the operation.
9. When a resource becomes unavailable, the AI replans the response.

## 🛠️ Technology Stack

- Python
- Strands Agents SDK
- Amazon Bedrock
- React
- TypeScript
- Vite
- Tailwind CSS
- Streamlit
- GitHub

## 🤖 AI Agent

The AI Disaster Response Commander uses the Strands Agents SDK to support disaster-response decision making.

The agent analyzes simulated disaster situations, prioritizes victims, evaluates available resources, creates response plans, explains decisions, requires human approval, and replans when the situation changes.

## 🏗️ Architecture

                 ┌─────────────────────┐
                 │   Command Center    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Strands AI Agent  │
                 └──────────┬──────────┘
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
        Victim Data    Resource Data   Situation Data
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                 ┌─────────────────────┐
                 │  Response Planning  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Human Approval    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Simulation Engine   │
                 └──────────┬──────────┘
                            │
                     Situation Change
                            │
                            ▼
                 ┌─────────────────────┐
                 │     Replanning      │
                 └─────────────────────┘
