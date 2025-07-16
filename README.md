# Agentic AI - Resume Evaluation Systems

This repository contains two AI-powered resume evaluation systems that demonstrate different approaches to automated resume screening and candidate response generation.

## 📁 Projects Overview

### 1. Resume - Evaluation (LangGraph Implementation)
A sophisticated resume evaluation system built using **LangGraph** and Google's Generative AI that provides intelligent workflow routing and automated candidate responses.

**Key Features:**
- **LangGraph-based workflow** for complex resume evaluation logic
- **State management** for tracking evaluation progress
- **Conditional routing** based on qualification assessment
- **Automated response generation** with personalized messages
- **Secure API key management** with environment variables

**Technologies Used:**
- LangGraph
- LangChain
- Google Generative AI (Gemini)
- Python-dotenv

### 2. Resume - validator (CrewAI Implementation)
A multi-agent system using **CrewAI** that employs specialized agents for resume evaluation and response writing, demonstrating collaborative AI workflows.

**Key Features:**
- **Multi-agent architecture** with specialized roles
- **Resume Evaluator Agent** for technical skill assessment
- **Reply Writer Agent** for professional communication
- **Collaborative task execution** between agents
- **AI/ML job fit evaluation** with detailed reasoning

**Technologies Used:**
- CrewAI
- LangChain Community
- Google Generative AI (Gemini)
- Python-dotenv

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Google API key for Generative AI

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/muralidharan-1708/Agentic---AI.git
   cd Agentic---AI
   ```

2. **Get Google API Key**
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a new API key
   - Copy the API key for the next step

3. **Configure Environment Variables**
   
   For each project folder, create a `.env` file:
   ```
   GOOGLE_API_KEY=your_google_api_key_here
   ```

4. **Choose Your Implementation**
   - Navigate to either `Resume - Evaluation/` for LangGraph implementation
   - Or `Resume - validator/` for CrewAI implementation
   - Follow the specific setup instructions in each folder

## 📋 Project Comparison

| Feature | LangGraph Implementation | CrewAI Implementation |
|---------|-------------------------|----------------------|
| **Architecture** | State-based graph workflow | Multi-agent collaboration |
| **Complexity** | Advanced conditional routing | Simpler agent-task model |
| **Use Case** | Complex evaluation workflows | Straightforward screening |
| **Agents** | Single AI model with states | Multiple specialized agents |
| **Output** | Structured state transitions | Sequential task execution |

## 🔒 Security

- API keys are stored in `.env` files (excluded from version control)
- `.gitignore` files ensure sensitive information stays local
- Environment variable validation included in both implementations

## 🎯 Use Cases

These systems are ideal for:
- **HR departments** looking to automate initial resume screening
- **Recruiters** wanting consistent evaluation criteria
- **Startups** needing scalable hiring processes
- **Learning projects** exploring agentic AI workflows

## 🤝 Contributing

Feel free to contribute by:
- Adding new evaluation criteria
- Implementing additional AI frameworks
- Improving response generation quality
- Adding more comprehensive testing

## 📄 License

This project is open source and available under the MIT License.

---

**Note:** Both implementations serve as educational examples of different agentic AI approaches. Choose the one that best fits your use case and complexity requirements.