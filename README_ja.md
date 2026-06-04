# Active Particle Feedback Kinetic Arrest (APFKA)

**現在の公開版:** `v0.3.2-public-landing-and-metadata-refresh`  
**Project website:** https://yokken0907.github.io/active-particle-feedback-kinetic-arrest/  
**Repository:** https://github.com/yokken0907/active-particle-feedback-kinetic-arrest

APFKAは、能動粒子フィードバック系における kinetic-arrest 様挙動、noise-assisted annealing window、feedback geometry、frustration boundary、rescue-stability、persistent hard boundary を、低次元toy-model / reduced-surrogate の範囲で診断するための claim-bounded リポジトリアーカイブです。

この v0.3.2 は、v0.3.1統合版の理論内容を拡張するものではなく、**公開入口・GitHub Pages・検索導線・メタデータ・claim boundary表示を整えるための刷新版**です。

## 推奨本文

最初に読むべきPDFは以下です。

- `paper/integrated_v0_3_1/APFKA_integrated_model_audit_synthesis_v0_3_1.pdf`

この統合版は、初期のABP風モデル原稿と v0.2.0-v0.2.6 の監査シーケンスを統合し、モデル式と再構成診断を保持しつつ、解釈をモデル内部の診断・失敗境界・救済安定性に限定しています。

## 主張境界

本リポジトリは、以下のように読むべきです。

> 検証済みtoy-model内における active-particle feedback surrogate の kinetic-arrest様挙動、noise-assisted annealing、feedback geometry、frustration boundary、rescue-stability、persistent hard boundary の診断アーカイブ。

本リポジトリは、以下を主張しません。

- 実験active matterでの検証、
- material design認証、
- デバイス・コロイド・ロボット・swarm-control の実装準備、
- 生物・社会システムの検証、
- 文明論・群衆制御・公共政策への適用、
- universal kinetic-arrest theorem、
- 相転移の形式的証明、
- 完全な流体力学理論、
- production-readyなシミュレーション／制御パッケージ。

本アーカイブでの “information feedback control” は、**低次元能動粒子toy-model内の数理的フィードバック項**を意味します。現実の行動制御、群衆制御、公共政策、材料設計、工学的安全認証済み制御器として読んではいけません。

## GitHub Pages

Pages設定は以下です。

```text
Settings -> Pages -> Build and deployment
Source: Deploy from a branch
Branch: main
Folder: /docs
```

想定URL:

```text
https://yokken0907.github.io/active-particle-feedback-kinetic-arrest/
```

## ライセンス

ライセンスはリポジトリ内の `LICENSE` および `LICENSE_EVALUATION_ONLY.txt` に従います。Zenodoでは `other-open` / source-defined / license-in-repository 相当を選択してください。
