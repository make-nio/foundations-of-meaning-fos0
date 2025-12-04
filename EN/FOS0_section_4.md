# 4. The Minimal Necessary Structure of an Ontological Layer (FOS-0)

FOS-0 is not a complete ontology.  
It is the *minimal required substrate* that any advanced AI system must implement to avoid the ontological blind spots described in the failure map.

It is a “Meaning Kernel.”

The purpose of this kernel is not to encode the world, but to encode the **rules that govern how meaning is structured**, regardless of domain.

Below is the minimal set of components.

---

## 4.1 Ontological Types (What Kind of Thing Is This?)

Every entity handled by an AI system must belong to exactly **one** ontological type.  
Mixing types is the root cause of most semantic hallucinations.

The types required at FOS-0 are:

1. **Object** – A concrete, nameable thing (physical or conceptual).
2. **Property** – A describable attribute of an object.
3. **Action/Event** – Something that happens or is done.
4. **Relation** – A link between two entities that has its own identity.
5. **State** – A snapshot configuration of an entity at a moment in time.
6. **Context** – The container of rules that govern interpretation.
7. **Teleology** – The purpose, intention, or goal associated with an entity.

These types are irreducible:  
Removing any of them breaks semantic coherence.

---

## 4.2 Semantic Registers (Which Layer of Meaning Is Being Used?)

All human language operates in parallel “semantic registers.”  
AI models collapse them into one, causing contradictions.

FOS-0 defines five registers:

1. **Literal** – Direct, factual statements.
2. **Analogical** – Comparisons and metaphors.
3. **Symbolic** – Cultural, religious, or archetypal meaning.
4. **Hypothetical** – Conditional, counterfactual, or speculative meaning.
5. **Teleological** – Purpose-driven meaning (why something exists or is done).

Each sentence produced or interpreted by an AI must be tagged with its register.  
No model should mix registers unless doing so intentionally.

---

## 4.3 Temporal Positioning (When Does This Meaning Hold?)

Humans naturally track temporal scopes.  
LLMs do not.

FOS-0 requires the AI to mark:

- **T₀** — the present interpretative frame  
- **T⁻** — historically valid meaning  
- **T⁺** — future-projected meaning  
- **T★** — timeless or axiomatic meaning

This prevents models from merging historical, present, and hypothetical facts into a single undifferentiated claim.

---

## 4.4 Teleological Integrity (Does This Output Preserve Purpose?)

Meaning breaks when an AI contradicts the purpose of a question or instruction.

Teleological Integrity (TI) is the principle that:

> *“Every output must preserve the intention expressed or implied by the user’s input.”*

Examples of violations:
- Answering literally when the user asked symbolically.  
- Offering solutions that contradict user constraints.  
- Providing advice that undermines the user’s stated goal.  
- Collapsing moral/ethical frames without marking the transition.

FOS-0 makes TI a structural rule, not an emergent behavior.

---

## 4.5 Context Boundary Enforcement (Where Does This Meaning Stop?)

LLMs tend to leak context between tasks, domains, or roles.

FOS-0 enforces **hard context boundaries**:

- No cross-context inference without permission.
- No assumption transplanting between domains.
- No reinterpretation of previous roles by default.
- No mixing frames unless explicitly requested.

This restores epistemic discipline.

---

## 4.6 Human-Compatibility Constraints (What Must an AI Never Break?)

To remain aligned with human cognition, an AI must not violate the following constraints:

1. **Ontological clarity** – Never mix types without intent.  
2. **Register coherence** – Speak within the requested semantic layer.  
3. **Teleological fidelity** – Respect the purpose of the user’s request.  
4. **Temporal separation** – Keep historical, present, future, and timeless meaning distinct.  
5. **Boundary integrity** – Never leak context across tasks.

These constraints form the “safety rails” of meaning.

Without them, the model becomes unpredictable.

---

## 4.7 FOS-0 as a Meaning OS Kernel

FOS-0 behaves like an operating system kernel:

- It does not perform reasoning.  
- It **governs the conditions** under which reasoning is allowed.  
- It enforces contracts between representations.  
- It allows specialized modules (domain ontologies) to run safely.  
- It regulates the flow of meaning exactly as a CPU regulates computations.

It is not a “knowledge base.”  
It is **the protocol that prevents meaning corruption**.

Without this layer, scaling parameters only amplifies the underlying error.

With this layer, even smaller models gain coherence.

---

## Summary

FOS-0 defines the minimal structural rules that guarantee:

- type-safe meaning  
- register-aware interpretation  
- temporal separation  
- teleological fidelity  
- context boundary enforcement  

This is the smallest possible scaffolding that makes semantic reasoning **human-compatible**.

