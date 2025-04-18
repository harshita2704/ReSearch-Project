ReSearch Project: Merging Search and Reasoning via Reinforcement Learning
📘 Paper Source
Title: ReSearch: Integrating Search and Reasoning with Reinforcement Learning for Large Language Models
Authors: Baichuan Inc., University of Edinburgh, Zhejiang University
Summary:
This work presents the ReSearch framework that enhances large language models by incorporating external search into multi-step reasoning processes through reinforcement learning. A unique strategy, Group Relative Policy Optimization (GRPO), is proposed to guide the timing and method of search during reasoning.

📦 Official Repository
GitHub: Agent-RL/ReSearch
The official repo offers scripts, training workflows, retriever components, GRPO algorithm implementation, and pre-trained examples for ReSearch.

🧠 Project Aim
The primary goals of this project are:
To comprehend and summarize the key contributions of the ReSearch framework
To explore and replicate experiments provided in the official repository
To implement and interact with the ReSearch architecture through code
To share major insights, experimental observations, and potential future directions

🔧 Core Implementation Steps
Run baseline experiments as outlined in the paper
Learn and integrate GRPO within RL workflows
Assess the model's interactive reasoning and retrieval capability
Construct a functional training loop and deploy the retriever interface

📊 Project Deliverables
1. Functional Implementation
Executed and verified core modules
Complete setup using Python, PyTorch, FlashRAG, FastAPI
PPO-based training utilizing GRPO logic

2. Technical Report
Detailed reinforcement learning configuration
Explanation of GRPO: estimation using groups, no critic involved
Evaluation metrics and experiment outcomes

3. Presentation Slides
Problem statement, framework overview, and experiment breakdown
Key challenges encountered and decisions taken
Observations on the model’s behavior and effectiveness

🗣️ Key Discussion Topics
Comparison:
RAG: Retrieval-augmented but with limited reasoning depth
SFT: Needs supervision with step-by-step reasoning labels
ReSearch: Unsupervised and learns via exploration and feedback

Future Applications:
Integrate external tools like calculators or code runners
Use live retrieval APIs for dynamic reasoning
Develop LLM agents capable of reflecting on their own outputs

🧪 Datasets & Benchmarks
HotpotQA
MuSiQue
2WikiMultiHopQA
Bamboogle

🤝 Contributors
Harshita Poojari

📌 License
This project draws inspiration from the official ReSearch implementation and follows the MIT License.
