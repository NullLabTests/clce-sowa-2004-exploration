# Common Logic Controlled English (CLCE) – Sowa 2004 Draft

A readable transcription and starter exploration of John F. Sowa's February 2004 draft:  
**Common Logic Controlled English** – an English-like syntax for full first-order logic (FOL) with equality, sets, sequences, and integers.

Goal: Make CLCE accessible again for study, especially in **AI / knowledge representation** research (symbolic AI, neurosymbolic systems, explainable AI, ontology engineering, controlled natural languages for LLMs).

## Why this matters in 2026 AI research
CLCE was ahead of its time: a human-readable surface syntax that compiles cleanly to FOL / conceptual graphs.  
Usefulness score: **7.5/10**  
- Strong for: KR foundations, semantic parsing, verifiable reasoning chains, prompt-to-logic translation  
- Weaker for: modern modalities, plurals, tenses (no native support)  
- High potential: extend it to bridge symbolic logic ↔ LLMs (e.g., CLCE → structured output validation)

Original draft source: http://www.jfsowa.com/clce/specs.htm

## Quick start examples (in examples/basic.clce)
Every cat is on a mat.  
If some person x is the mother of a person y, then y is a child of x.  
For every prime number x, there is a prime number greater than x.

See docs/CLCE-draft-2004.md for the full transcribed text.

## Next steps / contributions welcome
- Add a simple CLCE → FOL / CGIF parser (Python / Prolog)
- Map examples to modern tools (OWL, SPARQL, LangChain structured output)
- Add conceptual graph visuals
- License ideas: CC-BY-SA 4.0 for transcription

Fork → PR → let's revive this!
