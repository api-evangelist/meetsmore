---
title: "50超のworkflowを抱えるDagster × dbt プロジェクトのディレクトリ構成と設計パターン"
url: "https://engineering.meetsmore.com/entry/2026/06/26/103841"
date: "2026-06-26"
author: "meetsmore"
feed_url: "https://engineering.meetsmore.com/feed"
---
はじめに こんにちは、株式会社ミツモアでデータエンジニアをしている酒井です。 ミツモアのデータチームでは、Digdag + dbt で運用していたデータパイプラインを Dagster + dbt へ移行しました。Dagster は日本語の記事自体がまだ少なく、特に運用レベルの実装パターンに踏み込んだものは見つかりにくかったため、サンプルの一つになればと思い本記事を書きました。 本記事では、ミツモアのデータチームが運用しているDagsterプロジェクトを題材に、 ディレクトリをどう切っているか Definitions をどうマージしているか dbt / リソース / スケジュールをどこにどう置い…
