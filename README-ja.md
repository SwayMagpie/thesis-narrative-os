# thesis-narrative-os

A thesis‑driven narrative generation OS.  
物語を「価値観の状態遷移」として扱い、  
**テーゼ → 価値観ベクトル → イベント → 事実ログ → 主観表現 → レンダリング**  
の一貫した計算モデルで自然言語の物語を生成するフレームワーク。

---

## Overview

**thesis-narrative-os** は、物語生成を「創作」ではなく  
**価値観の変遷ログをレンダリングする OS 的プロセス**  
として扱うためのフレームワークです。

本プロジェクトは、物語を以下の構造で定義します：

- **Thesis（テーゼ）**  
  物語の中心となる命題。価値関数の方向ベクトル。

- **Value Vector（価値観ベクトル）**  
  キャラクターの内部状態。価値次元の重み。

- **Event（イベント）**  
  価値観が更新される瞬間。主観世界の差分が最大化する点。

- **Fact Log（事実ログ）**  
  外界の状態遷移。イベント成立に必要な客観的事実。

- **Subjective Expression（主観表現）**  
  価値観 × 事実ログ によって生まれる内界の変化。

- **World Consistency（整合性）**  
  外界と内界の両方が成立する世界の構築。

- **Narrative Rendering（物語レンダリング）**  
  上記すべてを束ねて自然言語として出力する工程。

この OS は、  
**「価値観の変遷」そのものを物語として扱う**  
という点で、従来の創作論とは異なる計算モデルです。

---

## Why this exists

物語のアイデアばかり増えて書かない、  
書くのが面倒、  
しかし構造としては理解している。

その状況を解決するために、  
**最短距離で物語を生成するための OS** として設計されました。

頭がないと使えない技術なので、  
公開しても問題ありません。

---

## Repository Structure (planned)
```
/thesis-narrative-os
├── 00_overview.md
├── 01_thesis-model.md
├── 02_value-vector.md
├── 03_event-update.md
├── 04_fact-log.md
├── 05_subjective-expression.md
├── 06_world-consistency.md
├── 07_rendering.md
└── examples/
```


---

## License

This project is released under the MIT License.  
Use it freely. Modify it freely. Break it freely.

---

## Support

If this framework contributed to your thinking or work,  
you can support the author through **GitHub Sponsors**.

Sponsorship is optional and has no effect on access,  
features, or priority.  
It is purely a token of appreciation.




