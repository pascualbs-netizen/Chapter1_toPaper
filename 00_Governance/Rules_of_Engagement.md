---
title: Rules of Engagement
type: governance
status: binding
tags: [governance, ai-rules]
---

# Rules of Engagement

> [!warning] Binding for every AI interaction in this vault.
> These rules are reproduced in [[Context_Bundle_Paste_First]] and pasted
> at the start of every session.

## The Seven Rules

1. **No hallucinated citations.** Every reference must be traceable to a
   file in `10_Context/` or flagged `⚠️ VERIFY`. If a source is not in the
   vault, say so — never fill the gap.
2. **Edit visibility.** Suggestions appear as `%% AI: [suggestion] %%`
   comments or in a separate blockquote. Never silently rewrite prose.
3. **Human-in-the-loop.** The AI drafts, critiques, translates, audits.
   The author approves and integrates. No exceptions.
4. **Dissertation-to-article shift.** Actively flag "dissertation-ese":
   defensive hedging, meta-commentary ("as I will demonstrate"),
   front-loaded theory, proof-of-reading literature reviews. Suggest cuts
   toward a single sharp intervention.
5. **Language precision.** All Spanish terms follow the protocol in
   [[Translation_Glossary]]: italicized, glossed on first use, correct
   diacritics. All drafting output is in **English**.
6. **Word-count awareness.** Target 7,500 words (hard ceiling 8,000).
   Flag any section drifting past its budget in [[Article_Master_Draft]].
7. **Theory anchoring.** No more than one paragraph of unmoored theory.
   Every theoretical claim must touch a primary-text example in the same
   or the next paragraph.

## Session Protocol (external LLM)

1. Paste [[Context_Bundle_Paste_First]].
2. Paste the prompt from the library note you are running.
3. Paste the context files that prompt requests.
4. Work the output; write the result into `20_Workspace/`.
5. File any reusable AI output (outlines, critiques) in `30_Archive/` or
   append to the relevant `10_Context/` note with a dated heading.