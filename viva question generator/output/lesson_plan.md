# Agentic AI Systems: Mini Hackathon Lesson Plan

Generated on: 2026-05-07 10:27:28

---

# Learning Objectives
Upon completion of this module, students will be able to:
* Differentiate between traditional chatbots and sophisticated agentic AI systems.
* Design and implement multi-step automations using Python and local tools (Ollama).
* Understand and apply core agent patterns, including the agent loop (plan, act, observe, finish), supervisor-worker delegation, and self-correction.
* Build a functional, local-first AI project that solves a practical problem (e.g., file analysis, data extraction, workflow automation).

## Required Materials
* **Software:** Python 3.x, Ollama, necessary Python libraries (e.g., LangChain components, file handling libraries).
* **Hardware:** Local machine capable of running LLMs (recommended GPU).
* **Resources:** The provided syllabus/lecture materials, sample datasets (CSV, text files), and a structured project template.

## Lecture Flow (2 Weeks)

### Week 1: Foundations and Core Patterns
* **Session 1: Agent Fundamentals (Topics 1 & 2):** Introduction to the agent loop (Plan -> Act -> Observe -> Finish). Deep dive into tool use and local automations. Understanding task, reasoning, and tool agents. Focus on state management and context.
* **Session 2: Resilience and Structure (Topics 3 & 4):** Implementing error recovery, retry loops, and role-based agent patterns (Critic/Reviewer). Practical workshops on file workflows, CSV analysis, and report generation.

### Week 2: Advanced Systems and Project Implementation
* **Session 3: Multi-Agent Orchestration (Topic 5):** Focus on Supervisor-Worker systems. How to delegate tasks, aggregate results, and structure complex, multi-agent projects.
* **Session 4: Advanced Reasoning & Review (Topic 6):** Techniques for structured reasoning, planning before action, and self-checking mechanisms to ensure consistency and accuracy.

## Activities and Practice Tasks
* **Activity 1 (Week 1):** Build a simple file workflow agent that reads a text file, extracts specific information (e.g., dates, names), and outputs a structured JSON report.
* **Activity 2 (Week 1):** Implement a basic CSV analysis agent that takes a CSV file, identifies trends, and generates a summary report, incorporating error handling for missing data.
* **Activity 3 (Week 2):** **Capstone Project:** Teams select a problem (e.g., Resume Ranking Assistant, Research Folder Summarizer) and build a complete, multi-agent system. The system must demonstrate task delegation and structured output generation.

## Assessment Ideas
* **Formative Assessment:** Weekly code reviews focusing on agent loop implementation and error handling. Short quizzes on agent terminology (e.g., difference between agent and chatbot).
* **Summative Assessment (Hackathon):** The final project submission, evaluated on:
    1. **Functionality:** Does the agent successfully solve the intended problem?
    2. **Complexity:** Does it utilize multiple agents/tools/workflows?
    3. **Output Quality:** Is the final generated report accurate, structured, and useful?
    4. **Documentation:** Clarity of the README and explanation of the architecture.

---
Generated locally with AgentKit.
