---
layout: post
title: OpenAI Gym チュートリアル
tags: [Implementation]
permalink: implementation/2020-05-17-openai-gym
---

## 概要
強化学習は，意思決定と運動制御に関係する機械学習分野の一つです．複雑で不確実な環境において，エージェントが目標達成する方法をどのように学習するかを研究しています．しかし，論文中で使用される環境の標準化が進んでいない問題があります．報酬関数や行動集合等の問題定義の微妙な違いが，タスクの難易度を大きく変える可能性があり，発表された研究の再現や異なる論文の結果の比較が困難になります．Gymライブラリは強化学習アルゴリズムを開発するための環境を集めたもので，先の問題を解決する標準的な学習環境として広く利用されています．これらの環境には共有インターフェースがあり，一般的なアルゴリズムを書くことができます． また，エージェントの構造については何も仮定しておらず，任意の数値計算ライブラリ (e.g., PyTorch, TensorFlow) と互換性があります．

## 目的
- 強化学習開発ツールキットであるGymの使い方を学ぶ．
- 強化学習アルゴリズムの実装セットであるStable Baselinesのモデルを利用する．

## 実施期間・日時
場所: オンライン (Zoom) \
日時: 2020年5月17日13時 - 15時

## 参考資料
[OpenAI Gym Official Page](https://gym.openai.com/)