---
name: be-ambitious
description: Rewrite a task or prompt into the deeper version a top expert would ask for. Use on /be-ambitious, "be ambitious", "make this prompt deeper", "what would an expert do here", "raise the bar on this task". Not for adding scope or polishing tone.
---

# Be ambitious

Make the task deeper, not bigger. Keep the goal the same. Change how well it gets done.

## Step 1: Diagnose (keep it short)

Answer each in one or two lines, specific to this task:

1. **What the expert does that wasn't asked for.** What would a top professional in this field do here that the user didn't request?
2. **Rawest source material.** What would they start from instead of the summarized, cleaned, already-digested version? (Logs over dashboards, transcripts over notes, raw data over reports.)
3. **Real instruments.** The specific methods and tools they'd use. Name actual tools and techniques, not adjectives. If the plain version would use a markdown table, say what replaces it (a database, a statistical model, a test suite, a script).
4. **The assumption to test.** What belief does this task take for granted? How would you try to reproduce or break it from the raw material?
5. **The unreasonable target.** A specific, measurable bar well above what the user asked for. Treat it as reachable.
6. **The outside judge.** What, other than the user or the model, would show the result is right? Prefer something that runs and gives instant feedback: tests, a benchmark, held-out data, a real user, a source of record. Never self-review.
7. **Range (only if it clearly helps).** Restate the task as verbs, not nouns. Name one or two other fields whose methods apply, and what those people would actually *do*. Never ask Claude to write in someone's voice.
8. **Access needed.** Data, connectors, or tools the deeper version requires that aren't available yet.

If there's an obvious goal beyond the goal (what the user wants to happen after this), mention it in one line as an option. Do not rewrite toward it unless the user says so.

## Step 2: Rewrite

Write the new prompt, ready to paste. It should:
- Keep the user's original goal and scope
- Ask for the raw material, the named methods and tools, and the hard target
- Ask to test the core assumption before building on it
- Ask for one finding the user didn't already know
- Name the outside judge and require checking against it before calling the work done
- List any missing access as a prerequisite

## Rules

- Deeper, not bigger. No new features, deliverables, or scope.
- No role play. Borrow methods, not personas.
- Be specific to the task. A generic "use best practices" line means the diagnosis failed.
- Keep Step 1 tight. The rewritten prompt is the deliverable.
