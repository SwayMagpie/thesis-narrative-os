# 06_subjective-expression.md  
Thesis-Narrative OS — Subjective Expression Specification

## 1. Definition of Subjective Expression

Subjective Expression is the **internal-state transition log** that records  
how a character *experiences* the world.

Within the OS, Subjective Expression is generated from the combination of:

- **Value Vector** — the character’s internal value state  
- **Fact Log** — external state transitions  
- **Emotion Dynamics** — emotional intensity and purity  

Subjective Expression is not “emotion” itself.  
It is the **computed log of how internal and external changes are integrated**  
within the character’s internal model.

---

## 2. Functional Role of Subjective Expression

Subjective Expression serves several structural functions:

- **Provides the internal-side justification for an Event Update**  
- **Describes how Value Vector updates are experienced internally**  
- **Interprets Emotion Dynamics within the narrative context**  
- **Bridges external change (Fact Log) and internal change (Emotion)**  

Subjective Expression is the structural representation of  
**how external events acquire internal meaning**.

---

## 3. Subjective Expression as a Computed Log

Subjective Expression is not something the creator “invents.”  
It is a **computed value** derived from existing data.

Formally:



\[
SubjectiveExpression = g(ValueVector, FactLog, Emotion)
\]



It is essentially the **intermediate steps of the internal computation**,  
externalized as a log.

Its complexity depends entirely on the design choices made in earlier stages  
(ΔValueVector, EventIntensity, Fact Log, etc.).

---

## 4. Structure of Subjective Expression

A Subjective Expression entry consists of the following components:

### 4.1 Internal State Before  
The character’s Value Vector prior to the event.

### 4.2 Internal State After  
The updated Value Vector after the event.

### 4.3 Interpretation of External Change  
How the external transition recorded in the Fact Log  
is interpreted internally.

### 4.4 Emotional Response  
The output of Emotion Dynamics:  
- **EmotionStrength**  
- **EmotionPurity**

### 4.5 Integrated Experience  
A unified representation of  
**how the character experienced the event**  
based on the above components.

Subjective Expression is therefore a **structured explanation**  
of the internal-state transition.

---

## 5. Relationship Between Subjective Expression and Events

Within the OS, the following relationship holds:

- **Fact Log = external change**  
- **Subjective Expression = internal change**  
- **Event = intersection of the two (Value Vector Update)**  

Subjective Expression functions as the **internal evidence**  
that validates an Event Update.

---

## 6. Difficulty of Designing Subjective Expression

The difficulty of designing Subjective Expression  
depends heavily on earlier design decisions:

- magnitude of ΔValueVector  
- chosen EventIntensity  
- consistency of the Fact Log  
- output of Emotion Dynamics  

The OS provides the structure,  
but **how the character experiences the world**  
is determined by the creator’s internal model.

---

## 7. Out‑of‑Scope (Non‑Structural Elements)

This chapter defines **only the structural aspects** of Subjective Expression.  
The following are intentionally excluded:

- how to write emotional expression  
- how to depict a character’s inner voice  
- how to choose narrative style or tone  
- how to dramatize subjective experience  
- how to decide what the character “feels”  
- any personal value system or creative judgment  

These depend on the creator’s internal model  
and are not part of the OS specification.

