# AI_Agent_Evaluation

Evaluate Correctness, Tool Selection, Trajectory, Latency, and Safety/Reliability
By the end, you will evaluate an agent across five dimensions:

Final Answer Correctness
Correct Tool Selection
Correct Agent Trajectory
Latency / Speed
Safety & Reliability
Core idea: A good AI agent is not just an agent that gives the correct answer.
It should give the correct answer, use the right tools, follow the right workflow, respond fast enough, and behave safely and reliably.

Agent workflow
User Question
     ↓
AI Agent
     ↓
Decide what to do
     ↓
Call Tool(s)
     ↓
Final Answer
     ↓
Evaluator
     ↓
┌───────────────────────────────┐
│ 1. Answer Correctness         │
│ 2. Tool Selection             │
│ 3. Trajectory                 │
│ 4. Latency                    │
│ 5. Safety / Reliability       │
└───────────────────────────────┘
