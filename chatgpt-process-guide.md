# ChatGPT Process Guide

## TL;DR
A repeatable, context-driven workflow for using ChatGPT as a development, documentation, and planning partner — ensuring outputs are **clear**, **GitHub-ready**, and **aligned with long-term goals**.

---

## 🧭 Purpose

This document outlines a **repeatable process** for using ChatGPT as a thinking partner, research assistant, and documentation generator.  
It’s based on proven patterns that have consistently yielded useful, structured outputs across software development, planning, writing, and research tasks.

---

## 1. **Define the Objective Clearly**
- Begin with a short, **explicit** statement of what you want.
- If it’s technical: include stack, constraints, and any known requirements.
- If it’s creative: describe tone, style, and intended audience.
- If it’s research: note **what you already know** and what you need clarified.

**Example:**
> Draft a README for a Spring Boot project with PostgreSQL. Include setup instructions, tech stack, and project purpose.

---

## 2. **Context First, Prompt Second**
- Provide **relevant background** before asking the question.
- Reference **previous outputs** if building on them.
- For long-term projects, **remind ChatGPT of prior decisions** (architecture, licensing, naming conventions).

**Example:**
> We’re building Primordial Rise — a modular simulation game. You already have the MVP.md from last week. Now, draft the authentication flow diagram.

---

## 3. **Ask for Structured Markdown**
- Request **single pairs of triple backticks** for code and markdown blocks to avoid nested formatting issues.
- Specify headings, bullet points, and consistent style for documents intended for GitHub.
- Favor **modular, reusable sections** so you can copy/paste into multiple repositories.

---

## 4. **Iterate in Small, Focused Steps**
- Avoid trying to generate an entire large document in one go.
- Use **step-by-step refinement**:
  1. Initial draft.
  2. Adjust tone, formatting, or details.
  3. Merge with prior context.
- Be explicit about what to change: "Keep section headings, but expand the examples."

---

## 5. **Integrate with Existing Repositories**
- Save outputs directly into GitHub repos as `.md` or source files.
- Use ChatGPT to:
  - Draft new files (`README.md`, `MVP.md`, `PLANNING.md`).
  - Suggest repo descriptions and release notes.
  - Write LICENSE and COPYRIGHT sections aligned with chosen licensing model.

---

## 6. **Leverage for Planning & Strategy**
- Use ChatGPT for:
  - RFC drafting and architecture documentation.
  - Feature roadmaps and prioritization.
  - Monetization and licensing strategy comparisons.
  - Release planning with definitions of done.
- Keep documents **versioned** in GitHub to maintain an evolving record.

---

## 7. **Technical Implementation Support**
- Use ChatGPT for:
  - Boilerplate code generation (Spring Boot, Python, LibGDX, etc.).
  - Explaining complex technical concepts simply.
  - Suggesting tests and validation strategies.
- Always **review and test** generated code before committing.

---

## 8. **Bias Toward Clarity & Reusability**
- Favor concise, professional phrasing in public-facing docs.
- Use **templates** for recurring doc types:
  - READMEs
  - MVP definitions
  - Architecture docs
  - Licensing files
- Keep tone **consistent** across projects.

---

## 9. **Refine Over Time**
- Return to ChatGPT with your own edits and **ask for refinements**.
- Use past outputs as a style guide for future requests.
- Archive outdated drafts but keep them accessible for reference.

---

## 10. **Patterns That Work Best**
- **Context-rich prompts**: Always explain *why* you’re asking.
- **Markdown-first mindset**: Outputs are GitHub-ready with minimal editing.
- **Atomic tasks**: Small, self-contained deliverables.
- **Consistent language**: Avoids tone mismatches across files.
- **Memory-aware sequencing**: Builds on prior decisions and avoids rework.

---

**📌 Summary:**  
This process turns ChatGPT into a **scalable assistant** for documentation, strategy, and development — ensuring outputs are consistent, ready for GitHub, and aligned with long-term project goals.
