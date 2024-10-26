---
title: Multiagent Slide
description: 
tags: 
date: 2024-10-23
draft: false
---
## Agent 
Also, known as assistant, copilot, chatbot

![agent](https://images-ext-1.discordapp.net/external/YnuA6NrJtNQd28lQrCRWUCcpI4zs5pC6hVQa_rb7w2E/%3Fe%3D2147483647%26v%3Dbeta%26t%3DNM-fTWai4FS4KUEIDYYWJFcCmkd5StKxWF6WUdMm3bY/https/media.licdn.com/dms/image/v2/D5622AQElKhs20ORRvA/feedshare-shrink_800/feedshare-shrink_800/0/1728817215083?format=webp)

Framework: Langchain, OpenAI assistant.

Note: 
- Think - Through Prompt Engineering/LLM
	- Planning, Reflect, ReAct, CoT, Decomposition
- Communicate 
	- Talk to Human, Talk to another agent
	- Add journal entry to shared memory
- Tools / Act
	- Function or API calling
	- Generate Code and Execute
- Environment

---
![mas](https://arxiv.org/html/2401.03428v1/extracted/5333121/imgs/agent.png)

---
## MAS (Multi-Agentic System)?

![](https://arxiv.org/html/2401.03428v1/extracted/5333121/imgs/multi_agent.png)

note: let's use more than one agent


---

![](https://microsoft.github.io/autogen/0.2/assets/images/autogen_agents-b80434bcb15d46da0c6cbeed28115f38.png)
![autogen](https://amatria.in/blog/images/110-1.png)


---
## Why MultiAgentic System?
- 현재 LLM이 지닌 한계 극복 - Specialized Agent가 Generalized된 Agent보다 어떠한 하나의 분야에서 더 뛰어날수 있음
- Complex Problem Decomposition - 복잡한 시스템을 작게 나눔
- Scalability, Fault Tolerance
- Distributed/Decentralized System
- 다양한 Emerging하는 시스템을 융합시킴 

note: 
Context window is limited, do we need to keep all the context to do a tiny job?
Scalability - Instead of placing all responsibilities to a single agent, if we can assign an agent to only classify if the sentence belongs to happy or unhappy, we can use cheaper model. 

---
## Components

- Agent
	- role-based
	- skill-based
	- Another MAS
	- or, even traditional system 
- Shared Memory
	- Context (or short term memory)
	- External Storage (long term memory)
		- RAG, Metadata DB, ...
- Communication Mechanism
	- Sequential, Group Chat, Nested Chat, ...
	- Coordination, Cooporation, Competition, ...
	- Broadcast, Multicast, Decentralized Communication, ...
- Environment
	- Human, Game, Physical Environment

---
## Agent

Role Based
- Planner, Decision Maker, Group Chat Manager
- Ranker, Guard

Skill Based
- Coding Agent, Code Executer, Code Reviewer
- ToolsUseAgent, Retrieval Agent
- Calculator, Optimizer,

---
## (Emerging) Ecosystem 

- Optimization
	- Prompt Optimization 
	- Workflow Optimization
	- Evolutionary Algorithms
- GraphRAG
- Environment Action
	- Browser (ServiceNow), Desktop (Antropic)

---
## Prompt Engineering
ZeroShot, FewShot, ...
ReAct, Reflect,  

prompt evaluation

prompt optimization

---
## Communication Patterns




---
## RAG Pattern




---

## Long Context



---

## Multimodal

- Image/Vision Understanding, Segmentation
- Object Detection
- Speech Understanding
- Robotics Sensors

---

## Examples

Research Scientist>)