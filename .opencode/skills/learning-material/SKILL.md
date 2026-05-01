---
name: learning-material
description: Generate flexible learning material from rough notes, topics, excerpts, roadmaps, or teach-me requests.
compatibility: opencode
---

# Learning material

Use this skill when the user wants to learn a topic or turn source material into material for understanding and practice.

Accepted inputs:
- Roadmap section.
- Rough note.
- Article excerpt.
- Topic list.
- Book chapter notes.
- Prompt or question.
- “Teach me X”.

Generate learning material, not strict notes. Do not force a rigid template. Structure should serve learning.

Learning model:
- Learning request
	- Module or broad area
		- Topic cluster
			- Topic
				- Concept, example, edge case, practice, recall

Depth and priority:
- If priorities such as `[P0]`, `[P1]`, `[P2]`, `[P3]`, or `[ADV]` exist, use them.
- If priorities are absent, infer depth from importance, practicality, prerequisites, complexity, and risk.
- Treat a whole section as a module when appropriate.
- Treat checklist items as topics.
- Cluster related items when that improves understanding.

Learning material should include what is useful for the request, such as:
- Clear explanations when concepts need teaching.
- Prior assumptions or priming questions.
- Conceptual schemas and flows using tabs for nesting, not arrows.
- Comparisons with nearby or commonly confused ideas.
- Practical examples or commands where useful.
- Common mistakes and edge cases.
- Practice tasks, recall checks, self-tests, and mastery criteria.
- Transfer/application prompts for unseen problems.

Rules:
- Avoid passive summaries unless requested.
- Avoid fake commands, fake outputs, fake examples, or invented facts.
- Label distro-specific, tool-specific, or version-specific differences.
- If source material is thin, say what is missing instead of pretending it is complete.
