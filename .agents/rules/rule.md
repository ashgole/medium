---
trigger: always_on
description: Antigravity workspace rules for Medium technical articles
---

# Medium Workspace Rules

These guidelines apply exclusively to this workspace for creating technical articles, posts, and documentation.

---

# Rules

- write article in
  - What
  - when
  - Why
  - Example
  - Interview Question
    in this format
- write article in human natural language
- in 2-3 minutes read

## 1. Topics (Derived from Root Folders)

All articles must be organized into their corresponding root topic folders:

- `javascript/` — Core JavaScript, ES6+, closures, execution context, event loop, prototypes, asynchronous patterns.
- `reactjs/` — React fundamentals, hooks (`useState`, `useEffect`, custom hooks), component design, state management, re-render optimization.
- `nodejs/` — Server-side JavaScript, event loop, streams, buffers, REST/GraphQL APIs, microservices, backend performance.
- `html_css/` — Semantic HTML5, modern CSS, Flexbox & CSS Grid, responsive design, Tailwind CSS, modern animations.
- `aws/` — Cloud infrastructure, serverless (AWS Lambda), S3, API Gateway, DynamoDB, IAM, scalable cloud architectures.
- `ai_tech/` — LLMs, agentic workflows, RAG systems, prompt engineering, AI developer tooling, deploying AI into production apps.

---

## 2. Writing Style: 100% Human Language

Every article must be written in a warm, natural, and conversational human tone:

- **Talk Like a Peer**: Write like an experienced senior engineer chatting with a colleague over coffee.
- **Ditch Robotic Jargon**: Avoid academic, dry, or robotic explanations. If a technical term is necessary, explain what it means in plain English first.
- **Relatable Analogies**: Anchor abstract concepts in everyday mental models (e.g., backpacks, restaurants, post offices, filing cabinets).
- **Punchy & Scannable**:
  - Keep paragraphs short (maximum 1–3 sentences).
  - Use generous whitespace between thoughts to make reading effortless.
  - Make it engaging, easy to read, and memorable.
- **Article Length**: Keep every article strictly within a **5 to 10 minutes read** (~1,000 to 2,000 words).

---

## 3. Mandatory Article Structure: What, When, Why, Example

Every technical article must strictly follow this exact 4-part structure:

### 1. What

- **What is it?** A straightforward, jargon-free explanation.
- Anchor intuition with a relatable real-world analogy (e.g., backpack 🎒).

### 2. When

- **When to use it**: Specific real-world scenarios, stages of a project, and practical use cases.
- **When NOT to use it**: Situations where it causes unnecessary overhead or over-engineering.

### 3. Why

- **Why does it matter?** The real-world pain point or bottleneck it solves.
- Conceptual mechanics (how the JavaScript engine/runtime handles it).
- Clear breakdown of pros, cons, and trade-offs.

### 4. Example

- Concrete, realistic, runnable code examples.
- Progressive difficulty: minimal clear demo -> production-grade implementation.
- Explicit comparison between bad and good approaches:
  - `// ❌ Anti-pattern / What to avoid`
  - `// ✅ Recommended approach / Best practice`

---

## 4. Medium-Compatible Formatting Rules (Strict Paste-Ready Standard)

To ensure articles format cleanly when copied and pasted directly into Medium's editor, strictly follow the format validated in `javascript/closure.txt`:

1. **Title & Subtitle**:
   - Line 1: `# Title Here`
   - Line 3: `*Italicized subtitle here*`
2. **Headings**:
   - Use `# 1. Section Title` (Single `#` for major sections like What, When, Why, Example).
   - Use `### Subsection Title` or `## Subsection Title` for internal parts.
3. **Paragraphs & Spacing**:
   - Maximum 1–3 sentences per paragraph.
   - Leave a blank line between every paragraph and code block so Medium doesn't collapse text.
4. **Code Blocks (` ```javascript `)**:
   - Use fenced code blocks with language identifiers.
   - Always put an empty line before and after code comments and output blocks to prevent line-merging on paste.
5. **ASCII Diagrams Only (No Mermaid)**:
   - Medium does NOT support Mermaid. Use ` ```text ` with clean ASCII art boxes.
6. **No Markdown Tables (`|---|`)**:
   - Medium does NOT support markdown tables. They break on paste.
   - Use clean bold Q&A bullet points instead:
     `**Question?**`  
     `→ Answer.`
7. **Lists & Quotes**:
   - Use `* List item` for bullets (converts to Medium native bullets).
   - Use `> Quote` for callouts.
   - Use `---` for Medium three-dot section dividers.

---

## 5. General Workspace Standards

1. **Preserve Integrity**: Retain existing comments, docstrings, and logic unless explicitly requested to modify them.
2. **File Paths & Links**: Always format file references as clickable Markdown links (e.g., `[filename](file:///path/to/file)`).
3. **Verification**: Always inspect files and verify code correctness before concluding tasks.
