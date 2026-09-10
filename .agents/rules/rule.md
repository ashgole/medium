---
trigger: always_on
description: Antigravity workspace rules for Medium articles, code conventions, and UI components
---

# Medium Workspace Rules

These guidelines apply exclusively to this workspace for creating technical articles, posts, and documentation.

---

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
  - Keep paragraphs short (maximum 3–4 sentences).
  - Use bullet points, bold text for key ideas, and clean vertical whitespace.
  - Make it engaging, easy to read, and memorable.

---

## 3. Mandatory Article Structure: What, When, Why, Example

Every technical article or documentation file must strictly follow this exact 4-part structure:

### 1. What

- **What is it?** A straightforward, jargon-free explanation.
- Set the scene with a relatable real-world hook or analogy to build instant intuition.

### 2. When

- **When to use it**: Specific real-world scenarios, stages of a project, and practical use cases.
- **When NOT to use it**: When it causes unnecessary overhead, over-engineering, or when an alternative approach is better.

### 3. Why

- **Why does it matter?** Why was it created, and what specific pain point or bottleneck does it solve?
- Under-the-hood engine mechanics (how the browser, runtime, or cloud service handles it).
- Clear breakdown of pros, cons, and performance trade-offs.

### 4. Example

- Concrete, realistic, copy-paste runnable code or architecture examples.
- Progressive difficulty: start with a minimal clear demo, then show a production-grade implementation.
- Explicit comparison between bad and good approaches:
  - `// ❌ Anti-pattern / What to avoid`
  - `// ✅ Recommended approach / Best practice`
- Visual aid: include ASCII diagrams, flowcharts, or Mermaid diagrams to illustrate data flow or lifecycle.

---

## 4. General Workspace Standards

1. **Preserve Integrity**: Retain existing comments, docstrings, and logic unless explicitly requested to modify them.
2. **File Paths & Links**: Always format file references as clickable Markdown links (e.g., `[filename](file:///path/to/file)`).
3. **Verification**: Always inspect files and verify code correctness before concluding tasks.
