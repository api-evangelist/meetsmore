---
title: "Slackからの依頼でPR作成まで自律的に行うデータエンジニアリングAIエージェント「でんじろう」の設計"
url: "https://engineering.meetsmore.com/entry/2026/01/29/193733"
date: "2026-01-29"
author: "meetsmore"
feed_url: "https://engineering.meetsmore.com/feed"
---
ミツモアでAI関連の開発を担当している増田（@xmasudahiroto）です。 社内でデータエンジニアリング業務を支援するAIエージェント「でんじろう」を開発・運用しています。今回は、Slackからの依頼やエラー通知をトリガーに、自律的にコード修正からPR作成まで行うエージェントの設計思想と実装のポイントを共有します。 「でんじろう」とは 「でんじろう」は、ミツモアのデータエンジニアリングチームで運用しているAIエージェントです。主な役割は、dbtを使ったデータパイプラインの保守・修正作業の自動化です。Slackでの依頼やエラー通知を受けて、コードの修正からPull Request作成、Sl…
