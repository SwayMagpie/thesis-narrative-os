# 05_fact-log.md  
Thesis-Narrative OS — Fact Log Specification

## 1. Definition of the Fact Log

A Fact Log is a **structural record of external state transitions** within the narrative world.

Within the OS, three layers are explicitly separated:

- **Fact Log** — external change  
- **Subjective Expression** — internal change  
- **Event Update** — the intersection of external and internal change  

A Fact Log is not a “story description.”  
It is the **minimal external-state information required for an Event Update to be valid**.

---

## 2. Functional Role of the Fact Log

The Fact Log serves several structural functions:

- **Provides the external basis for an Event Update**  
- **Ensures that Value Vector updates are grounded in external change**  
- **Maintains World Consistency**  
- **Defines the “path” between milestones (events)**  

The Fact Log is the **external causal structure** that supports internal updates.

---

## 3. Relationship Between Fact Log and Events

Within the OS, the following relationship holds:

- **Fact Log = external change**  
- **Subjective Expression = internal change**  
- **Event = intersection of the two (Value Vector Update)**  

An Event cannot exist without a Fact Log.  
The Fact Log is the **external evidence** that justifies the update.

---

## 4. Structure of a Fact Log

A Fact Log consists of the following components:

### 4.1 External State Before  
The state of the external world prior to the event.

### 4.2 External State After  
The state of the external world after the event.

### 4.3 State Transition  
The difference between the two states.

### 4.4 Causal Link  
A structural explanation of how the external change  
supports or enables the Value Vector update (ΔValueVector).

The Fact Log describes **how the world changed**,  
not how the scene is dramatized.

---

## 5. Fact Logs Between Milestones

Once milestones (events) are determined,  
the creator records:

**the external changes that occur between the previous event and the next event.**

From an OS perspective:

- Milestones (required updates) are structurally determined  
- Fact Logs (the path between them) are flexible  
- However, they must satisfy World Consistency  

A Fact Log is the **structured representation of the “path”**  
between two required updates.

---

## 6. Fact Log and World Consistency

Fact Logs are tightly linked to World Consistency.

World Consistency requires:

- external changes do not contradict each other  
- Value Vector updates are explainable through external change  
- subjective expressions do not conflict with external facts  
- the world’s rules remain intact  

Thus, the Fact Log is the **external-side requirement**  
for maintaining consistency while updating Value Vectors.

---

## 7. Difficulty of Fact Log Design

Fact Log design is one of the most delicate parts of the OS.

Reasons include:

- larger ΔValueVector requires proportionally meaningful external change  
- EventIntensity must be consistent with the Fact Log  
- World Consistency must be preserved  
- subjective expression must align with the external state  

The OS provides the structure,  
but **which dimensions change and by how much**  
is left to the creator’s internal judgment.

---

## 8. Out‑of‑Scope (Non‑Structural Elements)

This chapter defines **only the structural aspects** of Fact Logs.  
The following are intentionally excluded:

- how to invent events or scenes  
- how to dramatize external changes  
- how much external change to include  
- how to design worldbuilding  
- how to choose the “right” Fact Log  
- any personal value system or creative judgment  

These depend on the creator’s internal model  
and are not part of the OS specification.
