# 📝 AI Answer Evaluation & Improvement Assistant — Project Proposal

A proposal for a Generative AI assistant that **marks a student's written answer against exam-style criteria, explains what's missing, and rewrites it into a stronger answer** — using a hybrid agentic design that combines the *Tool-Based* and *Reflection* patterns.

![Agentic AI](https://img.shields.io/badge/Agentic_AI-Tool_%2B_Reflection-6D5BBA?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

## Problem

Students rarely get quick, detailed feedback on practice answers, and faculty don't have time to mark every draft. Existing tools fix grammar and spelling but don't judge conceptual accuracy, structure or completeness the way an examiner does.

## Proposed solution

A student pastes an answer, picks the subject and total marks, and gets back:

- **Marks** per criterion and a final score
- **Strengths and weaknesses**
- **Missing points**
- **An improved version** of the answer

### Hybrid agentic design

| Pattern | Role |
|---|---|
| **Tool-Based** | Python rule-based tools check length, match keywords, detect intro/body/conclusion, and allocate marks |
| **Reflection** | The LLM reviews its own evaluation, finds weak explanations, and rewrites the answer in a refined academic style |

### Example marking scheme (10-mark question)

| Criterion | Marks |
|---|---|
| Concept accuracy | 4 |
| Explanation depth | 3 |
| Structure & flow | 2 |
| Language clarity | 1 |

### Architecture

`Streamlit UI → Controller → Tool-based evaluation layer → Reflection agent → Output (marks, feedback, improved answer)`

**Planned stack:** Python · Gemini API · Streamlit · GitHub

## Repository contents

| File | Description |
|---|---|
| `Project Idea Proposal.pdf` | Full proposal: problem, objectives, design patterns, workflow, architecture, cost analysis |

## Team

Dakshraj Singh Chandawat · Tejas Pebam · Laishram Ritikumar Singh
Generative AI & Agentic AI Winter Program, BCA Semester IV, Alliance University

---
**Dakshraj Singh Chandawat** · [GitHub](https://github.com/DakshrajKurki) · [LinkedIn](https://www.linkedin.com/in/dakshraj-singh-chandawat-0a6349314)
