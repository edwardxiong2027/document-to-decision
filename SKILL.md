---
name: document-to-decision
description: Turn long documents into a decision brief without losing the caveats, owners, or exact references. Use when: A meeting or decision is buried inside a report, policy, or packet.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Document to Decision

Turn long documents into a decision brief without losing the caveats, owners, or exact references.

## When to use

A meeting or decision is buried inside a report, policy, or packet.

## Workflow

1. Identify the decision the reader must make.
2. Extract only relevant claims and cite page or section.
3. Separate requirements, recommendations, and open questions.
4. Produce options, tradeoffs, and a decision-ready summary.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Read the attached document for this decision: [decision]. Return: a 5-line brief, relevant requirements with page/section references, options and tradeoffs, risks, unresolved questions, and a recommended next step. Quote only short exact phrases. Distinguish what the document says from your interpretation. If a detail is absent, write “not specified.” Do not invent page numbers or obligations.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
