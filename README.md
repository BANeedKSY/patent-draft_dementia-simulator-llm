# Structural Emulation of Dementia Dynamics via LLM Context & Parameter Constraints

An architectural design and patent specification draft for simulating dementia thought and dialogue processes (short-term memory loss, disorientation, and confabulation) by controlling Large Language Model (LLM) context size and decoding parameters, rather than prompt-based roleplay.

---

## 📌 Abstract & Core Concept

Conventional AI dementia simulators rely on prompt engineering (e.g., instructing the model to "act like a patient with dementia and pretend to forget"). However, because the LLM still retains the actual history within its context buffer, its outputs often display calculated, unnatural meta-awareness.

This project introduces a **structural emulation paradigm**:
1. **Physical Context Limitation**: Forced FIFO trimming and attenuation of orientation tokens directly simulate short-term memory and orientation loss.
2. **Decoding Parameter Tuning**: Elevating $Temperature$ and $Top-P$ under context-deprived states causes the model to generate plausible yet fictitious narratives based solely on the latest tokens—reproducing **genuine confabulation (取り繕い行動)**.
3. **BPSD & Episodic Flashbacks**: Triggering emotional state switches via negative user feedback and injecting non-continuous long-term memories via RAG (Vector DB).

---

## 📄 Repository Structure

- `README.md` - English Overview & License Policy
- `README_JA.md` - 日本語版概要・特許出願権譲渡のご案内
- `docs/patent_specification.md` - Patent Specification Draft (Japanese)
- `docs/figure.pdf` - System Architecture & Process Flow Diagrams (Fig 1–4)

---

## 🏛️ Public Domain & Patent Transfer Notice

This technology concept and patent specification draft are intentionally disclosed to the public to foster open innovation in healthcare, digital therapeutics, and caregiver training (e.g., Humanitude learning).

### For Enterprises, R&D Teams, and Institutions:
If your organization wishes to **exclusively commercialize or patent** this architecture, the right to file the patent (Patent Application Right) can be transferred under a formal agreement **within 1 year of this public disclosure** (pursuant to Article 30 of the Japanese Patent Act: *Exceptions to Lack of Novelty of Invention*, and equivalent international Grace Period regulations), subject to reasonable terms and expenses.

If no entity acquires the exclusive rights within this 1-year window, the architecture will permanently remain in the Public Domain for unrestricted societal use.

---

## 👤 Author & Contact

- **Author**: A fake Banksy, BANeedKSY
- **ORCID**: [0009-0004-3755-0716](https://orcid.org/0009-0004-3755-0716)
- **Role**: Independent AI & Cognitive Systems Researcher
- **Contact**: Please reach out via GitHub Issues or Direct Message on social platforms for inquiries regarding research collaboration or patent right transfer.