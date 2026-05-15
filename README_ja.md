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

このページは、Active Particle Feedback の構造、すなわち project mission variable、reduced-model / surrogate としての位置づけ、structured-prior / constrained-evaluation logic、不確実性・stress discipline、evidence hierarchy、リポジトリ閲覧順、および claim boundary を短く整理するための補助資料です。

このページは説明補助であり、simulation を実行するものではありません。プロジェクトの妥当性、実装可能性、商用展開、安全認証、または実験・臨床・産業上の検証を示すものでもなく、論文本体、source/configuration materials、supporting archive materials、または専門家による独立評価を置き換えるものでもありません。

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
