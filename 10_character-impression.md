# 10_character-impression.md  
Thesis-Narrative OS — Character Impression Model  
A lower-level module that formalizes character impression formation at first appearance.

This module defines how a character becomes memorized by the reader using  
the **impression vector \( I \)** and the **threshold \( \theta \)**.  
It serves as a structural foundation for character generation within the OS.

---

## 1. Definition of Impression Strength \( I \) (Vector Model)

A character’s impression is represented as a weighted sum of  
six feature vectors \( f_k \).



\[
I = \sum_{k=1}^{6} w_k \cdot f_k
\]



- \( f_k \): feature intensity (0–1)  
- \( w_k \): importance weight of each feature

---

## 2. Six Feature Vectors That Constitute Impression

| Dimension | Description | Symbol |
|----------|-------------|--------|
| Scene | Connection to scene archetype | \( f_{\text{scene}} \) |
| Value | Value → action reflection | \( f_{\text{value}} \) |
| Reaction | Consistency of reaction patterns | \( f_{\text{reaction}} \) |
| Contrast | Contrast with other characters | \( f_{\text{contrast}} \) |
| Role | Clarity of narrative role | \( f_{\text{role}} \) |
| First | Strength of first appearance | \( f_{\text{first}} \) |

These six dimensions form a **universal cognitive feature space**  
based on how humans memorize characters.  
They do not change across genres.

---

## 3. Definition of Impression Threshold \( \theta \)

The minimum impression strength required for the reader  
to recognize and retain a character’s name.



\[
I \ge \theta
\]



- Depends on reader cognitive load  
- In entertainment fiction, **the work must ensure the threshold is exceeded**

---

## 4. OS Rule for Introducing a New Character

A new character’s first appearance must satisfy:



\[
w_{\text{scene}} f_{\text{scene}}
+ w_{\text{value}} f_{\text{value}}
+ w_{\text{reaction}} f_{\text{reaction}}
+ w_{\text{contrast}} f_{\text{contrast}}
+ w_{\text{role}} f_{\text{role}}
+ w_{\text{first}} f_{\text{first}}
\ge \theta
\]



This is the **OS-level rule for character introduction**.

---

## 5. OS-Level Algorithmic Rules

### ● Rule 1: At least one strong feature must appear in the first scene



\[
\max(f_k) \ge \alpha
\]



- \( \alpha \): minimum value for a “strong impression” (e.g., 0.7)  
- A character must have **one sharply defined feature**

---

### ● Rule 2: Multiple weak features do not accumulate meaningfully



\[
\sum_{k=1}^{6} f_k < \theta \quad \Rightarrow \quad \text{not memorized}
\]



- Stacking weak features is ineffective  
- A **single strong spike** is required

---

### ● Rule 3: Names bind only after the impression exceeds the threshold



\[
\text{NameBind} =
\begin{cases}
1 & (I \ge \theta) \\
0 & (I < \theta)
\end{cases}
\]



- A name functions as a **hash key** for the impression  
- If the impression is weak, the name does not attach

---

## 6. Final Algorithm for Introducing a New Character

1. **Design the first appearance scene**  
2. **Evaluate the six feature vectors \( f_k \)**  
3. **Compute impression strength \( I \)**  
4. **Compare with threshold \( \theta \)**  
5.  
   - \( I \ge \theta \): the reader memorizes the name  
   - \( I < \theta \): the character is not retained

---

## 7. Why the Feature Dimensions Are Universal Across Genres

Because:

- Human character memory mechanisms **do not change by genre**  
- The six dimensions reflect **cognitive universals**

What changes by genre is **the type of stimulus**, not the feature space.

### Examples by genre
- Horror → fear stimulus  
- Romantic comedy → intimacy & distance  
- Battle/action → value conflict & physical action  
- Mystery → reasoning behavior & logical clarity  

**Feature dimensions are universal; stimuli are genre-dependent.**


