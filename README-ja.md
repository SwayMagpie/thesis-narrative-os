# thesis-narrative-os  
A thesis‑driven narrative generation OS.

物語を「価値観の状態遷移」として扱い、  
**テーゼ → 価値観ベクトル → イベント → 事実ログ → 主観表現 → 整合性 → レンダリング**  
という一貫した計算モデルで自然言語の物語を生成するフレームワーク。

本 OS は、物語生成を「創作」ではなく  
**価値観の変遷ログをレンダリングする OS 的プロセス**  
として扱う。

---

# Overview

thesis-narrative-os は、  
物語を「価値観の変遷」という計算可能な構造として扱うための  
**Narrative Operating System（物語生成 OS）** である。

本プロジェクトは、物語を以下の構造で定義する：

---

## 🧭 Thesis（テーゼ）  
物語の中心となる命題。  
価値関数の方向ベクトル。

## 🧩 Value Vector（価値観ベクトル）  
キャラクターの内部状態。  
価値次元の重みを持つ多次元ベクトル。

## ⚡ Event Update（イベント）  
価値観が更新される瞬間。  
外界と内界の差分が最大化する点。

## 🌐 Fact Log（事実ログ）  
外界の状態遷移。  
イベント成立に必要な客観的事実。

## 💭 Subjective Expression（主観表現）  
価値観 × 事実ログ × 情動 によって生成される  
キャラクターの「世界の経験ログ」。

## 🌍 World Consistency（整合性）  
外界（Fact Log）と内界（主観表現）が  
同時に成立する世界の構築。

## 📝 Narrative Rendering（物語レンダリング）  
上記すべてを束ね、  
**価値観の変遷ログを自然言語として出力する工程**。

---

# Why this exists

- 物語のアイデアばかり増える  
- しかし書くのが面倒  
- 構造としては理解している  
- ならば OS にして LLM に書かせればいい

という発想から生まれた。

本 OS は、  
**「最短距離で物語を生成するための構造化エンジン」**  
として設計されている。

---

# Philosophy

thesis-narrative-os は  
「誰でも使える物語テンプレート」ではない。

扱う概念は：

- 価値次元  
- 状態遷移  
- 情動力学  
- 内部モデル  
- 世界整合性  
- ベクトル更新  
- 構造的イベント

など、抽象度が高い。

**構造で物語を考えられる人向けの OS**  
であり、  
「創作の自動化」「LLM への委譲」を目的とする。

---

# Repository Structure（planned）

```
/thesis-narrative-os
├── 00_overview.md
├── 01_thesis-model.md
├── 02_value-vector.md
├── 03_event-update.md
├── 04_emotion-dynamics.md
├── 05_fact-log.md
├── 06_subjective-expression.md
├── 07_world-consistency.md
├── 08_narrative-rendering.md
├── 09_numeric-extension.md
└── examples/
```

---

# Future Extensions

本 OS は、以下を数値化することで  
**シミュレーション可能な物語生成エンジン**へ拡張できる：

- 価値ベクトル  
- イベント更新量  
- 事実ログの重み  
- 情動強度・純度  
- 主観表現の深度  

これにより、  
物語の「必然性」を数学的に保証する  
数値モデルとして進化可能である。

---

# License

This project is released under the MIT License.  
Use it freely. Modify it freely. Break it freely.

---

# Support

If this framework contributed to your thinking or work,  
you can support the author through GitHub Sponsors.

Sponsorship is optional and has no effect on access,  
features, or priority.  
It is purely a token of appreciation.
