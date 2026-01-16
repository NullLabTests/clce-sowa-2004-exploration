# Common Logic Controlled English (CLCE) – Sowa 2004 Draft Exploration

Transcription, examples, and notes on John F. Sowa's 2004 draft of **Common Logic Controlled English** — a controlled natural language that reads like English but translates cleanly to first-order logic (FOL), conceptual graphs (CGIF), etc.

**Live repo**: https://github.com/NullLabTests/clce-sowa-2004-exploration

## Why revive CLCE in 2026 AI research?
CLCE is a human-readable syntax for precise logic — perfect for bridging symbolic KR and modern LLMs (e.g., structured outputs, verifiable reasoning, neurosymbolic AI).

**Usefulness score: 7.5/10**  
- High: Ontology engineering, semantic parsing, explainable AI, prompt-to-FOL tools  
- Medium: Lacks native modality/plurals/tenses — but extensible  
- Potential: CLCE → LangChain / LlamaIndex structured chains, or validation of LLM logic

Original draft: http://www.jfsowa.com/clce/specs.htm

### Key Example: "A cat is on a mat"
Conceptual graph display form (from Sowa's examples):

![Cat on a mat conceptual graph](assets/tombstone-belief-graph.gif?raw=true)  
*(Belief/tombstone variant — classic illustration style)*

Another classic nested/context example:

![Cat happy pet graph](assets/cat-happy.gif?raw=true)  
*From "If a cat is on a mat, then it is a happy pet"*

Type hierarchy example (useful for ontologies):

![Type hierarchy graph](assets/type-hierarchy.gif?raw=true)

## Contents
- `docs/CLCE-draft-2004.md` → full transcribed draft excerpt  
- `examples/basic.clce` → sample sentences  
- `assets/` → conceptual graph images for illustration  

## Next Steps / Contribute
- Add a Python/Prolog parser stub for CLCE → FOL  
- More examples (e.g., "Mary gives a dog a very juicy steak")  
- Integrate with modern tools (OWL export, LLM prompt templates)  

Fork/PR welcome! License: CC-BY-SA 4.0 (for transcription + additions)
