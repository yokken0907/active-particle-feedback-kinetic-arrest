# v0.3.1 統合改訂版のお知らせ

このリポジトリには、旧版のABPモデル論文本体と v0.2.0-v0.2.6 監査結果を統合した改訂稿を追加しています。

`paper/integrated_v0_3_1/APFKA_integrated_model_audit_synthesis_v0_3_1.pdf`

旧版はモデル・数式・基礎診断が厚く、v0.3.0補遺は監査と主張境界が強い文書でした。v0.3.1統合改訂版は、その両方を統合した推奨読者向け文書です。

---

# v0.3.0 統合補遺のお知らせ

このリポジトリには、主張限定された v0.3.0 統合補遺を追加しています。

`paper/addendum_v0_3_0/APFKA_noise_assisted_annealing_frustration_boundary_addendum_v0_3_0.pdf`

本補遺は、v0.2.0-v0.2.6 監査系列を、reduced active-particle surrogate の診断結果として固定するものです。文明理論、社会システムの検証、群衆制御手法、実験active matter検証、または普遍的kinetic-arrest定理としては読まないでください。

Repository URL: https://github.com/yokken0907/active-particle-feedback-kinetic-arrest

ライセンス: source-defined Evaluation-Only Notice。Zenodoでは CC-BY-NC-4.0 ではなく、other/source-defined license 系を使用してください。

---

# 能動粒子系における情報フィードバック制御・運動停止・ノイズ誘起アニーリング

このリポジトリは、以下のAI支援独立研究論文に対応するGitHub配置用フォルダである。

**Kinetic Arrest and Noise-Induced Annealing in Active Particle Systems with Information Feedback Control**

著者: 吉村圭司（Independent Researcher）  
状態: GitHub-ready paper companion archive v0.1.1-public-gate

## 簡易分類フォルダ名

**能動粒子系・情報フィードバック制御の非平衡相転移理論**

## 位置づけ

この研究は、Active Brownian Particle（ABP）系に、粒子が保持する内部属性の局所分散を減らす情報フィードバック制御項を導入し、非平衡定常系における運動停止、感受率ピーク、空間相関、ノイズ誘起アニーリングを調べる数理・数値プロトタイプである。

## 中心的解釈

この論文の主張は、「ノイズが常に秩序を壊す」という単純な見方ではなく、競合相互作用とfeedback controlを持つ非平衡系では、適度なノイズがmetastable domainからの脱出を助け、長距離相関を回復させる場合がある、というものである。

## 技術的ビジュアル案内

初めて本リポジトリを見る技術的関心のある読者向けに、ブラウザだけで開ける技術的ビジュアル案内ページを同梱しています。

`docs/technical_visual_orientation/index.html`

このページは、active-particle feedback kinetic-arrest / noise-induced-annealing logic をプロジェクト固有の観点から整理する補助資料です。本リポジトリにおける mission variable は material design certification、experimental active-matter validation、または device deployment ではなく、reduced active-particle system における persistent arrest、feedback-assisted escape、noise-assisted annealing、order-parameter recovery、artifact-like control effects を strict simulation/provenance boundary の下で識別する modeled kinetic-arrest / noise-induced-annealing diagnosis です。

また、このページでは active-particle simulation state channels、mobility / order diagnostics、feedback and noise channels、artifact-audit discipline、reconstructed-public-reproducer provenance caution、evidence hierarchy、リポジトリ閲覧順、および claim boundary を短く整理しています。主要な図解セクションには replay control を付けており、静的テンプレートではなく診断ロジックを段階的に確認できます。

このページは説明補助であり、active-particle simulation を実行するものではありません。実験的 material system、material design、device deployment、industrial process readiness、安全認証、または実機検証を示すものでもなく、論文本体、source materials、figures、または専門家による独立評価を置き換えるものでもありません。

## 主張しないこと

本リポジトリは、以下を主張しない。

- 実験active matterでの検証
- 生物・社会システムでの検証
- 文明制御理論
- 群衆制御・swarm control技術
- 普遍的相転移の証明
- kinetic arrestの厳密証明
- production-ready simulation package

## 現在の状態

これはpaper companion archiveであり、仮想環境、実験active-matterデータセット、または工学的制御実装ではない。

## PUBLIC-GATE-0 status

判定: `PASS-WITH-MINOR-PUBLICATION-FIXES-A10-ACTIVE-PARTICLE-PUBLIC-GATE-0`  
公開版: `v0.1.1-public-gate`  
分類: 能動粒子系・情報フィードバック制御の非平衡相転移理論

このリポジトリは、A10 Evidence-Lock Protocol型の公開前監査により、主張境界・非主張事項・manifest整合性・GitHub/Zenodo/Jxiv方針を固定した public-gate 版である。


## Zenodo-safe metadata handling

Zenodo DOI 付与時の metadata validation conflict を避けるため、この pre-DOI release では root 直下の有効な `CITATION.cff` を意図的に外している。

ドラフト引用メタデータは以下に退避している。

`docs/citation_metadata/CITATION_DRAFT_pre_doi.cff`

## Source-material consistency note

checkfix 監査の結果、以前同梱されていた source-material directory には、この論文が必要とする ABP information-feedback simulation ではなく、stochastic Optimal Velocity traffic/STT ring-road material が含まれていることを確認した。そのため、この不一致素材は GitHub/Zenodo 公開本体から除外した。

したがって本 release は、完全な one-command reproduction-code package ではなく、paper companion archive / public documentation package として引用・参照する。

## 再構成されたABP公開再現スクリプト

当初の同梱 source_materials には、このABP論文ではなく STT/交通流リング道路シミュレーション素材が混入していたため、公開版では除外しました。
本パッケージでは、論文本文のモデル記述と図の診断量に基づき、Figure 1 / Figure 2 相当のCSVと図を生成する再構成版スクリプトを追加しています。

```bash
python scripts/abp_feedback_public_reproducer.py
```

これは元の探索コードのビット単位復元ではなく、論文診断量レベルの公開再現パスです。
