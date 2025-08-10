# ChatGPT Process Guide

## TL;DR
A **repeatable, context-driven workflow** for using ChatGPT as a **development, documentation, and planning partner** — ensuring outputs are **clear**, **GitHub-ready**, and **aligned with long-term goals** while supporting sustainable AI usage.

---

## 🧭 Purpose
This guide defines a **sustainable method** for collaborating with ChatGPT across software development, planning, writing, and research.  
It builds on proven patterns and aligns with the **Effective AI Usage** philosophy:
- AI as a **thinking partner**, not a replacement.
- Outputs that are **high-quality and reusable**.
- Processes that prevent **over-reliance and skill erosion**.

---

## 1. **Define the Objective Clearly**
- Start with a **short, explicit** statement of what you want.
- For **technical tasks**: include stack, constraints, and known requirements.
- For **creative work**: define tone, style, and audience.
- For **research**: note what you already know and what needs clarification.

**Example:**
> Draft a README for a Spring Boot project with PostgreSQL. Include setup instructions, tech stack, and project purpose.

---

## 2. **Context First, Prompt Second**
- Provide **relevant background** before the question.
- Reference **previous outputs** if building on them.
- For long-term projects, **remind ChatGPT of prior decisions** (architecture, licensing, naming conventions).

**Example:**
> We’re building Primordial Rise — a modular simulation game. You already have the MVP.md from last week. Now, draft the authentication flow diagram.

---

## 3. **Ask for Structured Markdown**
- Use **single pairs of triple backticks** for markdown and code blocks (avoids nested formatting issues).
- Specify headings, bullet points, and consistent style for GitHub docs.
- Favor **modular, reusable sections** for multi-repo use.

---

## 4. **Iterate in Small, Focused Steps**
- Avoid generating large documents in one go.
- Use a **three-step refinement loop**:
  1. Initial draft.
  2. Adjust tone, formatting, or details.
  3. Merge with prior context.
- Give **clear revision instructions**:
> Keep section headings, but expand the examples.

---

## 5. **Integrate with Existing Repositories**
Use ChatGPT to:
- Draft new repo files (`README.md`, `MVP.md`, `PLANNING.md`).
- Suggest repo descriptions and release notes.
- Write LICENSE and COPYRIGHT sections aligned with your model.

Save outputs **directly into GitHub** and version control them for future reference.

---

## 6. **Leverage for Planning & Strategy**
- Draft RFCs and architecture docs.
- Create feature roadmaps and prioritization lists.
- Compare monetization and licensing strategies.
- Define “Definition of Done” for releases.

Keep documents **versioned** to track how decisions evolve.

---

## 7. **Technical Implementation Support**
- Generate boilerplate code (Spring Boot, Python, LibGDX, etc.).
- Break down complex technical concepts.
- Suggest testing and validation strategies.

**Important:** Always **review, adapt, and test** generated code before committing.

---

## 8. **Bias Toward Clarity & Reusability**
- Keep public docs **concise and professional**.
- Use **templates** for recurring doc types:
  - READMEs
  - MVP definitions
  - Architecture docs
  - Licensing files
- Keep tone **consistent** across projects.

---

## 9. **Refine Over Time**
- Return to ChatGPT with your edits for **further refinement**.
- Use past outputs as a **style reference**.
- Archive outdated drafts but keep them accessible.

---

## 10. **Patterns That Work Best**
- **Context-rich prompts** – Explain *why* you’re asking.
- **Markdown-first mindset** – Outputs ready for GitHub with minimal edits.
- **Atomic tasks** – Small, self-contained deliverables.
- **Consistent language** – Avoid tone mismatches.
- **Memory-aware sequencing** – Build on prior decisions, avoid rework.

---

## 📌 Alignment with Effective AI Usage
This process:
- Works with **`chatgpt_as_communication_platform.md`** to keep prompts and outputs constructive and empathetic.
- Complements **`avoiding_cognitive_atrophy.md`** by encouraging independent thinking before AI engagement.
- Fits into a **sustainable AI usage framework** that scales across projects and teams.

---
