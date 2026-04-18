# 04_emotion-dynamics.md  
Thesis-Narrative OS — Emotion Dynamics Specification

## 1. Definition of Emotion Dynamics

Emotion Dynamics is the structural mechanism within the OS that computes:

- **EmotionStrength** (the intensity of an emotional response)  
- **EmotionPurity** (the clarity and internal coherence of that response)

These values are derived from:

- changes in the character’s Value Vector (ΔValueVector)  
- the intensity of the triggering event (EventIntensity)

In this OS, emotion is defined as an **internally observable change in state**,  
not as an external stimulus.  
Emotion emerges from the **interaction between Value Vector updates and events**.

---

## 2. Core Formula of Emotion Dynamics

Emotion Dynamics is defined by the following expression:



\[
Emotion = f(\Delta ValueVector \times EventIntensity)
\]



Where:

- **ΔValueVector**  
  The magnitude and direction of change in the character’s value state.

- **EventIntensity**  
  A scalar representing the strength of the external change recorded in the Fact Log.

- **EmotionStrength**  
  The resulting emotional intensity.

Emotion is therefore computed as:

**internal change × external magnitude**.

---

## 3. Emotion Purity

Emotion Purity represents the **clarity and internal coherence** of the emotional response.  
Within the OS, it is defined structurally as:



\[
Purity = |\Delta ValueVector|
\]



Emotion Purity reflects:

- **Magnitude of the value shift**  
  How strongly the Value Vector changed.

- **Directional clarity**  
  Whether the update has a coherent direction.

- **Internal origin**  
  Whether the update can be explained as an internal state change  
  rather than noise or arbitrary external influence.

Emotion Purity functions as a structural indicator of  
**narrative “meaning strength” or internal resonance**.

---

## 4. Designing ΔValueVector and EventIntensity

To compute Emotion Dynamics, the system requires:

- which Value Dimensions experience change  
- how large the change is  
- how the change relates to the Thesis  
- how strong the external event is

These decisions depend on the creator’s internal model,  
but the OS provides the following structural requirements:

### 4.1 Structural Requirements for ΔValueVector  
A valid ΔValueVector must specify:

- which dimensions changed  
- the magnitude of the change  
- the direction relative to the Thesis  
- consistency with the external change recorded in the Fact Log

### 4.2 Structural Requirements for EventIntensity  
EventIntensity must:

- represent the magnitude of external change  
- combine with ΔValueVector to determine EmotionStrength  
- be explainable through the Fact Log

Emotion Dynamics is established only when  
**internal change (ΔValueVector) and external change (EventIntensity)**  
are both present and structurally coherent.

---

## 5. Functional Role of Emotion Dynamics

Emotion Dynamics serves several key functions within the OS:

- **Determining narrative force**  
  Larger ΔValueVector produces stronger narrative momentum.

- **Providing input for Subjective Expression**  
  Subjective expressions are generated from EmotionStrength and Purity.

- **Influencing Fact Log design**  
  Larger ΔValueVector requires proportionally meaningful external changes,  
  affecting how Fact Logs must be constructed.

Emotion Dynamics acts as a **core engine**  
that links value updates, events, and subjective experience.

---

## 6. Out‑of‑Scope (Non‑Structural Elements)

This chapter defines **only the structural aspects** of Emotion Dynamics.  
The following are intentionally excluded:

- how to evoke emotion in the audience  
- how to dramatize emotional moments  
- how to choose ΔValueVector values  
- how to set EventIntensity  
- how to design “pleasure” or “impact” in a narrative  
- any personal value system or creative judgment  

These depend on the creator’s internal model  
and are not part of the OS specification.

