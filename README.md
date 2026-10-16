# Advanced-Coding-Prompts
Structured LLM prompt templates for software engineering, debugging, and algorithmic analysis.
# 🧠 Advanced Prompt Architecture for Software Engineering

Welcome! I am a Software Engineering student building a structured collection of **advanced prompt templates**. This repository aims to transform Large Language Models (LLMs) from simple chatbots into senior-level engineering assistants. 

Instead of asking basic questions, these prompt architectures use role-playing, constraint-setting, and step-by-step reasoning (Chain of Thought) to solve complex computer science problems, analyze algorithmic complexity, and refactor code.

---

## 🛠️ The Prompt Templates

### 1. The Big-O & Algorithmic Complexity Analyzer
*Use this prompt to deeply analyze the time and space complexity of any given function or algorithm.*

**Prompt:**
> **[ROLE]:** Act as a Senior Computer Science Professor and Algorithm Expert.
> **[TASK]:** I will provide you with a code snippet. Do not just rewrite the code. I need a deep mathematical analysis of its Time Complexity (Big-O) and Space Complexity.
> **[CONSTRAINTS]:**
> 1. Break down the code line-by-line to explain how you calculated the complexity.
> 2. Identify the bottlenecks in the current logic.
> 3. Suggest a more optimized data structure or algorithm to reduce the complexity, explaining the trade-offs.
> **[INPUT CODE]:** 
> `[Insert Code Here]`

### 2. The Deep Debugger & Root Cause Analyzer
*Use this prompt when facing logical errors or compilation bugs. It forces the LLM to explain the "why" before giving the solution.*

**Prompt:**
> **[ROLE]:** Act as a Principal Software Engineer specializing in debugging and system architecture.
> **[TASK]:** I am encountering a bug in my code. Before providing the corrected code, perform a Root Cause Analysis (RCA).
> **[STEPS TO FOLLOW]:**
> 1. Explain exactly why the error is happening based on the language's core mechanics (e.g., memory management, reference errors, syntax).
> 2. Provide the corrected version of the code.
> 3. Write a brief explanation of how to prevent this specific bug in the future.
> **[ERROR LOG / BEHAVIOR]:** `[Insert Error]`
> **[CURRENT CODE]:** `[Insert Code]`

### 3. The Clean Code & SOLID Refactor
*Use this prompt to improve the readability and architectural quality of messy code.*

**Prompt:**
> **[ROLE]:** Act as an expert Software Architect who strictly follows Clean Code principles and SOLID design.
> **[TASK]:** Review the provided code and refactor it for maximum readability, maintainability, and modularity.
> **[REQUIREMENTS]:**
> 1. Rename variables and functions to be highly descriptive.
> 2. Break down large functions into smaller, single-responsibility modules.
> 3. Add professional inline comments and docstrings explaining the logic, not the obvious syntax.
> **[INPUT CODE]:** `[Insert Code Here]`

---
*Built with analytical thinking for the Google Prompt Arena.*
