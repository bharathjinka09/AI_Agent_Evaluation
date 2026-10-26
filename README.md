# AI Agent Evaluation

Evaluate Correctness, Tool Selection, Trajectory, Latency, and Safety/Reliability. By the end, you will evaluate an agent across **five key dimensions**:

1. **Final Answer Correctness**
2. **Correct Tool Selection**
3. **Correct Agent Trajectory**
4. **Latency / Speed**
5. **Safety & Reliability**

> 💡 **Core Idea:** A good AI agent is not just an agent that gives the correct answer. It must give the correct answer, use the right tools, follow the right workflow, respond fast enough, and behave safely and reliably.

---

## Agent Workflow

```text
User Question
     │
     ▼
  AI Agent
     │
     ▼
Decide what to do
     │
     ▼
Call Tool(s)
     │
     ▼
Final Answer
     │
     ▼
 Evaluator
     │
     ├─► 1. Answer Correctness
     ├─► 2. Tool Selection
     ├─► 3. Trajectory
     ├─► 4. Latency
     └─► 5. Safety / Reliability
```
