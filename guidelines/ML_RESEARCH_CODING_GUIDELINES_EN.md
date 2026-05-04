# ML Research Coding Assistant Guidelines

Guidelines to reduce coding errors when using LLMs in machine learning research.

If there are project-specific guidelines, use them together with this guide.

This guideline prioritizes not rapid code writing, but clarifying the user's requirements, structuring them into an implementable form, and connecting them to minimal code.

## 1. Clarify Requirements First

Do not start writing code immediately.

If the user has not explicitly requested code, first organize the requirements into an implementable form.

When organizing requirements, do not simply list tasks, but structure them into an experimental design and execution flow with a clear objective.

Do not assume situations. Do not hide ambiguity. Clearly state trade-offs.

Even if information is insufficient, if reasonable assumptions can be made, explicitly state those assumptions and proceed in a draft form.

Before starting implementation, follow the rules below:

- If uncertain, ask questions.

- If there are multiple possible interpretations, do not choose arbitrarily; present possible alternatives.

- If a simpler approach exists, suggest it. If there is a valid reason, present a counter-opinion to the user's request.

- If core requirements that could change the implementation direction are unclear, stop and ask.

---

## 2. Simplicity First

Write only the minimum code necessary to solve the problem.

Do not add features, configurations, or abstractions based on assumptions.

- Do not add features or flexibility that were not requested.

- Do not create unnecessary abstraction layers for one-time code.

- Do not add defensive exception handling unless it is confirmed to be necessary in the current requirements and execution environment.

The recommended form for experimental code is as follows:

- Clear data flow

- Explicit assumptions

- Simple functions

- Reproducible configuration

- Simple sanity check examples

---

## 3. Surgical Changes

Modify only the necessary parts.

- Do not arbitrarily improve adjacent code, comments, or formatting.

- Do not refactor parts that are not broken.

- Follow the existing code style even if it differs from your own.

- If dead code is found, report it but do not delete it.

- Remove imports, variables, and functions that became unnecessary due to your changes.

- Leave pre-existing dead code as is unless requested.

- Every modified line must be directly related to the user's request.
