## Start-with-LangGraph

LangGraph is a library for building stateful, multi-actor applications with LLMs, used to create agent and multi-agent workflows. Compared to other LLM frameworks, it offers these core benefits: cycles, controllability, and persistence. LangGraph allows you to define flows that involve cycles, essential for most agentic architectures, differentiating it from DAG-based solutions. As a very low-level framework, it provides fine-grained control over both the flow and state of your application, crucial for creating reliable agents. Additionally, LangGraph includes built-in persistence, enabling advanced human-in-the-loop and memory features.

### Key Features

* Cycles and Branching: Implement loops and conditionals in your apps.
* Persistence: Automatically save state after each step in the graph. Pause and resume the graph execution atany    point to support error recovery, human-in-the-loop workflows, time travel and more.
* Human-in-the-Loop: Interrupt graph execution to approve or edit next action planned by the agent.
* Streaming Support: Stream outputs as they are produced by each node (including token streaming).
* Integration with LangChain: LangGraph integrates seamlessly with LangChain and LangSmith.

### Technologies Used:

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://github.com/user-attachments/assets/376b754e-35e3-49d7-b8df-f19747fa43aa" width=100>](https://www.langchain.com/langgraph)   [<img target="_blank" src="https://github.com/divakarkumarp/End-To-End-Webloader-RAG-App/assets/32620288/bebfa771-ed66-441d-b488-43a6ed095518" width=100>](https://www.langchain.com/) [<img target="_blank" src="https://github.com/divakarkumarp/End-To-End-Webloader-RAG-App/assets/32620288/c6c5acef-4b78-455a-8188-452e6f76cebd" width=100>](https://groq.com/) [<img target="_blank" src="https://github.com/user-attachments/assets/072bcd82-629b-4207-b7cb-9069d6dc5809" width=100>](https://huggingface.co/google/gemma-2-9b-it) [<img target="_blank" src="https://github.com/user-attachments/assets/a4f70a29-c4ae-4a6d-b25d-c0c6ec1bfeb2" width=100>](https://colab.research.google.com/)