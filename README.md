# LLM Prompt Optimizer

**LLM Prompt Optimizer** is a system for automatic prompt optimization using evolutionary algorithms. It enables parallel prompt testing across multiple LLMs, tracks prompt version relationships using a graph database, and ensures safe execution in isolated environments via Daytona sandboxes. Supabase handles user authentication, permissions, and workspace management.

---

## Key Features

- Prompt generation and optimization using evolutionary algorithms (Genetic Algorithm - GA)
- Graph-based tracking of prompt mutations and relationships (Neo4j)   
- Parallel and secure prompt evaluation using Daytona sandboxes   
- User and role management via Supabase  
- Visual prompt graph explorer  

---

## How It Works

1. The user submits a base prompt.  
2. The system generates multiple mutations (variations).  
3. Each variation is executed in a Daytona sandbox using the selected LLM model.  
4. Responses are evaluated using fitness functions (relevance, clarity, accuracy, etc.).  
5. The best-performing prompts are selected for the next generation.  
6. All prompt relationships are stored in a graph database.  

---

## Flow Diagram

![LLM Prompt Optimizer Architecture](images/FlowDiagram.png)

---

Project structure and Getting Started details comming soon...
