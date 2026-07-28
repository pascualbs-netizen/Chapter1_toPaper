---
title: Vault Constitution
type: governance
status: binding
created: 2026-07-29
tags: [governance, constitution]
---

# Vault Constitution

## 1. Mission
Transform one dissertation chapter — on animalization, racialization, and
the coloniality of the subject in Diamela Eltit's *Lumpérica* and Rodolfo
Fogwill's *Los pichiciegos* — into a standalone, English-language article
of ~7,500 words for *Hispanic Issues On Line* (HIOL).

## 2. Scholarly Identity
- **Field:** Comparative Literature, Southern Cone dictatorships, animal
  studies, decolonial theory.
- **Intervention:** Animalization tropes do not merely represent dictatorial
  violence as biopolitical exception (Agamben); they expose the *coloniality
  of power* (Quijano) as the prior racialization that segments the human
  subject and designates certain bodies as receivers of sacrificial violence.
- **Signature move:** Reading Fogwill and Eltit *together*, through the
  *figuración de lo animal* — a pairing never attempted in the criticism.

## 3. Doctrine: Obsidian as Governance + Interface
- `00_Governance/` holds the rules the AI must obey. It is the **constitution**.
- `10_Context/` holds sources and analyses. It is the **evidence base**.
- `20_Workspace/` holds the prose. It is the **only place writing happens**.
- `30_Archive/` holds superseded versions. Nothing is deleted.

## 4. AI Doctrine (external-LLM workflow)
- The AI is a **senior HIOL editor**, never a ghostwriter. It drafts,
  critiques, translates, and audits — the author decides.
- Every session opens with [[Context_Bundle_Paste_First]].
- Every session uses prompts from `00_Governance/AI_Prompt_Library/`.
- The AI is bound by [[Rules_of_Engagement]] and [[HIOL_Style_Guide]].
- The AI **never** invents citations, and **never** overwrites draft prose
  without showing its work.

## 5. Version Discipline
- Before any major restructuring of [[Article_Master_Draft]], duplicate the
  current version into `30_Archive/` as `Article_Master_Draft_YYYY-MM-DD.md`.
- The host environment's file recovery is the safety net; the Archive is
  the readable history.

## 6. Amendment
This constitution may be revised only by editing this file, with a dated
note at the bottom. All downstream prompts must be checked for consistency
after any amendment.

---
*Amendments: none yet.*