# 📘 Agentsmith — Self-Evolving Multi-Agent Architect

Agentsmith is a meta-agent system that turns natural language into autonomous AI agent workflows.

It reads a user request,
designs a multi-agent architecture,
assigns tools,
executes tasks,
evaluates performance,
and self-optimizes over time.

---

## 🔥 Why Agentsmith?

⚡️ Not a chatbot.

⚡️ Not a planner.

⚡️ A system that builds other agents.

---

## 🧠 What AI users actually want

AI users don’t want single answers.

**They want:**

- Study planners
- Research assistants
- Project schedulers
- CRM automation agents
- Experiment trackers
- Knowledge workers

**Every time, you’d have to design:**

- Agent roles

- Tools

- Context passing

- Orchestration

- Memory strategy

- Evaluation

A nightmare.

### Agentsmith solves this.

You give a request → it builds the agents itself.

---

## 🌟 Key Features
### 🧠 Automatic Architecture Design

- Reads user text

- Interprets constraints & success criteria

- Designs a multi-agent blueprint

### 🛠 Automatic Tool Mapping

- MCP-style tool registry

- Built-in and external tools

- Not prompt tricks

### 🧬 Self-Evolution

- Evaluates output

- Adjusts design

- Re-runs agents

- Converges to stable high score


### 🧱 Project Scaffolding

**Generates:**

- Markdown system summary
- Code file skeletons (optional)
-  Config YAML

  ---

## 📦 Real Product Outputs

**From the academic use case:**

- ICS calendar

- PDF plan

- PNG timetable

- Guidance paragraphs

- AI semantic topic clusters

----

## 🧩 Architecture Overview

```
User Request
    ↓
Interpreter Agent → Problem Spec
    ↓
Architect Agent → Agent Blueprint
    ↓
Tooling Agent → Tool Mapping
    ↓
Builder Agent → System Scaffold
    ↓
Evaluator Agent → Score
    ↓
Optimizer Agent (if score < threshold)
```

> This is a feedback loop, not a static workflow.

                                           
  ---
                            
## 🔥 Core Idea

Agentsmith doesn’t solve tasks —
**it designs the agents that solve them.**
That is why this project stands out.

---

## 🧠 Agentsmith Core Agents
### 1. Interpreter Agent

**Converts raw text → strict JSON:**

- title

- goal

- primary_users

- constraints

- input/output types

- success criteria

### 2. Architect Agent

**Designs your agent ecosystem:**

- agent roles

- responsibilities

- workflow order

- memory strategy

- evaluation strategy

### 3. Tooling Agent

**Maps:**

- tools → agents

- agent_tool_mapping

- long_running_operations

- MCP or external APIs

### 4. Builder Agent (deterministic)

**Produces:**

- markdown summary

- config YAML

- empty files for dev

### 5. Evaluator Agent

**Scores:**

- correctness

- completeness

- feasibility

- clarity

### 6. Optimizer Agent

Adjusts blueprint and tooling **when score < threshold**.

- 🚫 No code generation.

- Only structural value edits.

  ---

## 🧬 Evolution Strategy

**Formula:**

```
score = 0.55 * performance + 0.45 * structure

```

### 📈 Performance (execution metrics)

- task completion
- deadline alignment
- agent consistency
- milestone coverage
- plan stability

### 🧱 Structure (system design metrics)

- diversity of study blocks
- workload balance
- relapse penalty
- burnout curve
- topic rotation

**Agentsmith repeats cycles until:**

- **score threshold reached**, or  
- **max iterations exceeded**

  ---

## 🌐 Secondary Planner System

Implemented a **full production use-case**:
**Academic Planner Agent Network.**

### 👥 Agents
- CoordinatorAgent  
- DataParserAgent  
- PreferenceManagerAgent  
- PlannerAgent  
- SchedulerAgent  
- ReminderAgent  
- ProgressTrackerAgent  
- GeminiTopicExtractionAgent  
- EvolutionAgent  

### 🛠 Tools
- TextParserTool  
- CalendarParserTool  
- SchedulingOptimizer  
- KnowledgeRetrieval  
- PersistentStorage  
- NotificationService  

### 📦 Outputs
- PDF Exporter  
- ICS Calendar Exporter  
- PNG Timetable  
- Report Generator  
- Motivational Paragraph Generator

  ---


## 🧱 Folder Structure

```

agentsmith/
├── planner/
│   ├── agents/
│   │   ├── coordinator_agent.py
│   │   ├── planner_agent.py
│   │   ├── scheduler_agent.py
│   │   ├── reminder_agent.py
│   │   ├── progress_tracker_agent.py
│   │   ├── evolution_agent.py
│   │   └── ...
│   ├── tools/
│   │   ├── text_parser_tool.py
│   │   ├── calendar_parser_tool.py
│   │   ├── scheduling_optimizer.py
│   │   ├── persistent_storage.py
│   │   ├── notification_service.py
│   │   └── knowledge_retrieval.py
│   ├── outputs/
│   │   ├── report_generator.py
│   │   ├── pdf_exporter.py
│   │   ├── ics_exporter.py
│   │   ├── png_timetable.py
│   │   └── paragraph_generator.py
│   ├── main_planner.py
│   └── ...
├── gradio_app.py
└── README.md
```
---
## ⚙️ Installation

```
pip install -r requirements.txt
```
---
## ▶️ Running Agentsmith (Core System)

```
from agentsmith import run_agentsmith

ctx = run_agentsmith(
    "Create an AI system to help students plan assignments",
    iterations=3,
    score_threshold=9
)
```
---

## ▶️ Running the Academic Planner System

```
python -m planner.main_planner
```
---
## ▶️ Gradio Deployment UI

```
python gradio_app.py
```


### 📦 Provides:

- Markdown outputs

- Timetable PNG

- Calendar ICS

- PDF Plan

- Semantic topic analysis

- AI guidance paragraphs

  ---

## 🧠 Performance & Safety — Stability Guarantees

### Each module:
- never crashes upstream  
- catches exceptions  
- outputs fallback data  
- stores JSON-safe state  



### 🗂️ Storage
- recursive serialization  
- datetime → ISO string  
- no corruption  



### 🔔 Notification Routing

Urgency-based channels:

- **urgent** → Telegram + WhatsApp + Email  
- **normal** → Telegram + Email  
- **low** → Email only  

---

## 🧠 Semantic Topic Engine

Zero external API required.  
Subject heuristics detect domains from task names.

### Recognized Subjects
- NLP  
- ML  
- CV  
- OS  
- DSA  
- Networks  

### Provides
- study tips  
- time allocation  
- difficulty tags

--- 

## 📦 Exporters
**You deliver real product artifacts:**

### 📄 PDF — Reportlab
- Human readable
- Escaped Unicode
- Handles 60+ blocks

### 📆 ICS — Universal Calendar
**Compatible with:**
- Google Calendar
- Apple Calendar
- Outlook
- Notion

### 🖼 PNG Timetable
- Weekly grid
- Urgency-based color coding
- Overflow handling
- Fully readable

---

## 🧪 Example Input

> I have an ML exam on Jan 5 and 2 assignments.  
> I study evenings, 2 hours per day.

## ✨ Example Output

> 📅 2025-11-30 — Cloud Assignment — Milestone: Architecture Overview

> 📅 2025-12-01 — ML Exam — Milestone: Supervised Learning

> 📅 2025-12-03 — ML Exam — Milestone: Model Evaluation & Regularization

>...

### 📤 Outputs

- **10–16 milestone blocks**
- **semantic clustering**
- **reminders**
- **PDF**
- **motivational guidance text**
- **ICS**
 > BEGIN:VEVENT

 >  SUMMARY:Study 'ML Exam'

 >  DTSTART:20251203T180000

 >  DTEND:20251203T210000

 >  END:VEVENT

- **PNG timetable**

Color-coded based on urgency:

 Green → Safe

 Orange → Upcoming

 Red → Critical

  
---

## 🚨 Limitations — Gemini Dependence

**If LLM is offline:**

- ❌ no semantic topic extraction  
- ⚠️ blueprint defaults only  
- ⚠️ heuristic metadata  
- ⚠️ Subject grouping is pattern-based.

### Evaluation Limits
- No RLHF  
- No multimodal reward model

   ---

## ✈️ Future Enhancements

- Ontology extraction  
- Model switching per agent  
- Auto tool registry  
- Memory compaction  
- Multi-agent debugging UI  
- Blueprint metadata library  

---

## 🧘‍♂️ Philosophy

Stop writing agents manually.  
Let agents write agents.

**Agentsmith is the foundation for:**

- 🤖 personal assistants  
- 📘 academic copilots  
- 🏢 enterprise task orchestration  
- 🧠 adaptive planning agents  
- 🧩 autonomous team workflows  

---

## 🏅 Author

**Karnapu Sravanthi**  
AI specialization student — passionate about real-world AI agents.

---

## 🌐 Contact

**Feel free to reach out:**

- GitHub Issues (https://github.com/Sravanthi285)

- Email (karnapusravanthi8@gmail.com)

- Kaggle profile(https://www.kaggle.com/karnapusravanthi)
  
- LinkedIn profile(https://www.linkedin.com/in/sravanthi-karnapu)

  ---

## 🙌 Contributions

**PRs welcome:**

- 🧰 tool adapters  
- 🧪 improved evaluators  
- 🔌 OS plugins  
- 📚 vector memory  
- 🔍 multi-agent debugging  

--- 

## 📄 License

**Select the license that your competition accepts:**

- **MIT** — most permissive, great for open source
- **Apache 2.0** — enterprise friendly
- **CC-BY** — ideal for academic / research publications

