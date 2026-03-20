---
id: 2
title: Clarify Geographic Scope for Research Paper
stage: spec
date: 2026-03-20
surface: agent
model: qwen-coder
feature: 001-ai-k12-efficiency
branch: 001-ai-k12-efficiency
user: dell
command: /sp.clarify
labels: ["clarification", "research-paper", "scope"]
links:
  spec: specs/001-ai-k12-efficiency/spec.md
  ticket: null
  adr: null
  pr: null
files:
  - specs/001-ai-k12-efficiency/spec.md
tests:
  - N/A
---

## Prompt

---

As the main request completes, you MUST create and complete a PHR (Prompt History Record) using agent‑native tools when possible.

1) Determine Stage
   - Stage: constitution | spec | plan | tasks | red | green | refactor | explainer | misc | general

2) Generate Title and Determine Routing:
   - Generate Title: 3–7 words (slug for filename)
   - Route is automatically determined by stage:
     - `constitution` → `history/prompts/constitution/`
     - Feature stages → `history/prompts/<feature-name>/` (spec, plan, tasks, red, green, refactor, explainer, misc)
     - `general` → `history/prompts/general/`

3) Create and Fill PHR (Shell first; fallback agent‑native)
   - Run: `.specify/scripts/bash/create-phr.sh --title "<title>" --stage <stage> [--feature <name>] --json`
   - Open the file and fill remaining placeholders (YAML + body), embedding full PROMPT_TEXT (verbatim) and concise RESPONSE_TEXT.
   - If the script fails:
     - Read `.specify/templates/phr-template.prompt.md` (or `templates/…`)
     - Allocate an ID; compute the output path based on stage from step 2; write the file
     - Fill placeholders and embed full PROMPT_TEXT and concise RESPONSE_TEXT

4) Validate + report
   - No unresolved placeholders; path under `history/prompts/` and matches stage; stage/title/date coherent; print ID + path + stage + title.
   - On failure: warn, don't block. Skip only for `/sp.phr`.

## Response snapshot

Conducted clarification session using AskUserQuestion. User selected "Developed + equity lens" for geographic scope. Updated spec with Clarifications section, resolved one edge case. Remaining 3 edge cases (subject areas, grade levels, teacher readiness) deferred as low-impact for initial paper scope.

## Outcome

- ✅ Impact: Geographic scope clarified; evidence base now bounded to developed nations with equity acknowledgment
- 🧪 Tests: N/A (specification refinement)
- 📁 Files: specs/001-ai-k12-efficiency/spec.md (Clarifications section added, Edge Cases updated)
- 🔁 Next prompts: /sp.plan for research methodology, or /sp.implement to start writing
- 🧠 Reflection: 1/5 question quota used; 3 edge cases intentionally deferred as they don't block planning

## Evaluation notes (flywheel)

- Failure modes observed: None - clarification completed successfully
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): Proceed to planning phase with clear scope boundaries
