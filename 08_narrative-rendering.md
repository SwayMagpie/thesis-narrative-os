# 08_narrative-rendering.md  
Thesis-Narrative OS — Narrative Rendering Specification

## 1. Definition of Narrative Rendering

Narrative Rendering is the final stage of the OS,  
where the following structural components are integrated and  
**converted into natural language**:

- World Model  
- Fact Log (external change)  
- Subjective Expression (internal change)  
- Event Update (Value Vector transitions)  
- Emotion Dynamics  
- World Consistency  

Narrative Rendering is not “story creation.”  
It is the **natural‑language output of the internal computation**  
performed in all previous stages.

In essence:



\[
Narrative = \text{Rendered log of Value Vector transitions}
\]



---

## 2. Functional Role of Narrative Rendering

Narrative Rendering serves several structural functions:

- **Makes Value Vector transitions readable as a narrative**  
- **Integrates Fact Log and Subjective Expression into a coherent sequence**  
- **Presents Event Updates as a Narrative Trajectory**  
- **Converts Emotion Dynamics into interpretable emotional content**  
- **Ensures the final output respects World Consistency**

Narrative Rendering is the OS’s **presentation layer**.

---

## 3. Structural Composition of Narrative Rendering

Narrative Rendering integrates three layers:

### 3.1 External Layer  
- World Model  
- Fact Log  
- World Consistency  

### 3.2 Internal Layer  
- Value Vector  
- Subjective Expression  
- Emotion Dynamics  

### 3.3 Update Layer  
- Event Update  
- Narrative Trajectory (sequence of Value Vector changes)

These layers are combined and expressed in natural language.

---

## 4. Computational Model of Narrative Rendering

Narrative Rendering can be expressed as:



\[
Narrative = h(World, FactLog, SubjectiveExpression, Event, Emotion, Consistency)
\]



Important properties:

- **Narrative Rendering does not generate new information**  
- **It only transforms existing structural data into natural language**

This makes Narrative Rendering a deterministic transformation  
of previously computed values.

---

## 5. Narrative Rendering and LLMs

Narrative Rendering is a stage that can be **delegated to an LLM**.

Reasons:

- All necessary structural data is already computed  
- Rendering is a transformation task, not a creative one  
- LLMs excel at natural‑language generation  
- The OS is designed to provide structured inputs  
  that an LLM can easily convert into narrative form

Thus, delegating Narrative Rendering to an LLM  
is a natural and efficient design choice.

---

## 6. Freedom in Narrative Rendering

While the OS defines the **structure**,  
the **expression style** is entirely up to the creator.

Free components include:

- writing style  
- tone  
- narrative voice (first‑person, third‑person, etc.)  
- tense  
- descriptive density  
- emotional coloration  
- pacing  
- level of detail  

The OS defines **what must be rendered**,  
but not **how it should be written**.

---

## 7. Necessary Conditions for Narrative Rendering

Narrative Rendering is valid only when:

- Fact Log and Subjective Expression are consistent  
- Event Updates form a coherent sequence  
- Emotion Dynamics are reflected in the output  
- World Consistency is maintained  

If these conditions are not met,  
the narrative is considered structurally broken.

---

## 8. Out‑of‑Scope (Non‑Structural Elements)

This chapter defines **only the structural aspects** of Narrative Rendering.  
The following are intentionally excluded:

- how to write prose  
- how to evoke emotion in readers  
- how to choose narrative style  
- how to dramatize events  
- how to structure scenes  
- personal value systems or creative judgments  

These belong to the creator’s internal model  
and are not part of the OS specification.

