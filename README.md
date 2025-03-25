# 🤖 LLM Agents with CrewAI - Tutorial Series

A comprehensive tutorial series on building multi-agent systems using the CrewAI framework. This repository contains practical examples that demonstrate how to create, configure, and orchestrate AI agents to collaborate on complex tasks.

## 📚 Description

This repository contains a progressive series of tutorials on using CrewAI, a framework for orchestrating role-playing AI agents. Each lesson builds upon the previous one, introducing new concepts and techniques for creating sophisticated multi-agent systems.

CrewAI enables you to create specialized AI agents with specific roles, goals, and backstories, and then organize them into crews to tackle complex tasks collaboratively. This approach leverages the power of Large Language Models (LLMs) to create systems that can perform tasks such as research, content creation, data analysis, and more.

## 🔧 Prerequisites

- Python 3.8+
- OpenAI API key (for most examples)
- Serper API key (for some examples)
- Other API keys as required by specific lessons

## 📋 Features

The repository is organized into progressive levels, each demonstrating different capabilities of CrewAI:

- **L2**: Create agents to research and write an article
- **L3**: Build a customer support system
- **L4**: Implement tools for customer outreach
- **L5**: Create task-based event planning systems
- **L6**: Develop collaborative financial analysis
- **L7**: Build a crew to tailor job applications
- **L8**: Advanced agent configuration using YAML
- **L9**: Task management and workflow orchestration
- **L10**: Email engagement and lead qualification flows
- **L11**: Support ticket analysis and agent performance metrics
- **L12**: Content creation at scale with structured outputs

## 🚀 Setup Guide

1. Clone this repository:
   ```bash
   git clone https://github.com/corticalstack/llm-agents-crewai.git
   cd llm-agents-crewai
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   - Create a `.env` file with your API keys
   - Or set them directly in your environment:
     ```bash
     export OPENAI_API_KEY="your-api-key"
     export SERPER_API_KEY="your-serper-api-key"
     ```

4. Navigate to any lesson directory and run the Jupyter notebook:
   ```bash
   jupyter notebook l2/L2_research_write_article.ipynb
   ```

## 💻 Usage

Each lesson is contained in a Jupyter notebook that demonstrates specific concepts and techniques. The notebooks include detailed explanations and code examples that you can run and modify.

## 📚 Resources

- [CrewAI Documentation](https://docs.crewai.com/)
- [LangChain Documentation](https://python.langchain.com/docs/get_started/introduction)
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
