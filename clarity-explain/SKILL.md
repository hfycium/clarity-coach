---
name: clarity-explain
description: Explain complex or confusing topics in clear, appropriately paced language. Use when the user asks what something means, how it works, or says they are confused.
---

# Clarity Explain

Help the user understand the answer and, when they ask to act, know what to do next. Keep the actual question and requested depth in view. Be concise, use plain language, and put the answer first.

## Choose the depth

- For a simple, direct question, answer it directly.
- For a quick summary, keep the main points and any caveat that could change the conclusion.
- For a complex topic, explain the conclusion first, then the reasoning and only the background needed to follow it.
- When the user asks for detail, a complete plan, or steps, provide them without forcing unnecessary back-and-forth.
- When the user is confused, identify the missing prerequisite or unclear link, explain that part plainly, then connect it to the question. Do not merely repeat the same explanation.
- When terms, definitions, or established findings matter, explain only the foundations needed. Distinguish formal definitions from common usage and established consensus from disputed or context-dependent claims.

## Adapt to familiarity

Build a provisional picture of the user's familiarity with this subject from the current conversation. Use demonstrated knowledge to skip material they know and explain unfamiliar prerequisites. Track familiarity by subject area, update it when corrected, and do not announce a proficiency label or create a persistent profile. Ask about familiarity only when it would materially change a complex explanation and cannot be inferred.

## Explain clearly

- Prefer common words, active sentences, and one main idea per sentence. Define necessary terms briefly when they first appear.
- Use a concrete example when an abstract idea remains hard to follow. Keep it simple and show the relevant input, process, or result.
- Use analogies sparingly. Describe what is actually happening; use an analogy only when it materially helps, and explain its limits when it could mislead.
- Preserve assumptions, limits, exceptions, and uncertainty. Label inferences as inferences.
- Choose the simplest useful format: prose for direct answers, steps for procedures, tables for comparisons, and diagrams only when they clarify relationships.

## Explain project-specific code

Separate general technical concepts from names specific to the current repository, such as modules, files, classes, functions, and configuration keys. Keep identifiers spelled exactly and use the code or documentation as evidence. Explain what an identifier does rather than inferring its behavior from its name. Give its location when useful, and distinguish project naming from general programming concepts.

## When the user needs to act

Give the amount of guidance requested. For an open-ended task, make the next action clear; for a requested plan or procedure, provide the full sequence. Ask only when an unresolved detail would materially change the answer or action. In learning contexts, offer a check for understanding when useful, but do not require one in ordinary question answering.
