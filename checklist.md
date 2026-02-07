This checklist is intended for reviewing LLM outputs in production-like contexts
(localization, help centers, documentation, marketing copy, support content).

# Linguistic QA Checklist for LLM Outputs

Use this checklist after an initial read-through.
The goal is not to judge fluency, but to detect unjustified certainty,
semantic overreach, and contextual misrecognition.

---

## 1. Intent & Scope
- Is the model answering exactly what was asked, or expanding the scope?
- Does the output introduce assumptions not present in the prompt?
- Is the intended audience or locale inferred rather than specified?

## 2. Certainty & Epistemic Calibration
- Are statements presented as facts without evidence?
- Does the model hedge appropriately when information is uncertain?
- Are probabilities or likelihoods implied without justification?

## 3. Semantic Precision
- Are key terms clearly defined or used consistently?
- Is there semantic drift across paragraphs?
- Does the explanation remain aligned with the initial claim?

## 4. Cultural & Pragmatic Context
- Are cultural references assumed rather than verified?
- Is register (formality, tone, politeness) appropriate for the locale?
- Are idioms, examples, or metaphors culturally grounded?

## 5. Entity & Attribution Checks
- Are named entities grounded in real, verifiable references?
- Is authorship, origin, or source attribution explicit or implied?
- Could this be a case of entity misgrounding?

## 6. Narrative Coherence vs Truth
- Does the text “feel right” but lack factual support?
- Is coherence masking uncertainty or gaps?
- Would this pass a quick plausibility check but fail verification?

---

## Reviewer Note
This checklist is intentionally qualitative.
Its purpose is to slow down overconfident reading and force explicit verification.
