---
title: "データ基盤に SRE の指標を持ち込む — Dagster のメタデータ DB から可用性 (availability / MTTR / MTBF) を出す"
url: "https://engineering.meetsmore.com/entry/2026/09/09/120000"
date: "2026-09-09"
author: "meetsmore"
feed_url: "https://engineering.meetsmore.com/feed"
---
こんにちは、株式会社ミツモアでデータエンジニアをしている酒井です。 ミツモアのデータチームでは、Dagster + dbt でデータパイプラインを運用しています。障害対応そのものは日々回っているのですが、「先月このパイプラインは何時間止まっていたのか」「慢性的に不安定なのはどれか」といった問いに数字で答えられない状態が続いていました。 そこで、Web サービスの SRE でおなじみの availability / MTTR / MTBF を、データパイプラインに応用して測るようにしてみました。ちなみにデータ基盤の信頼性を SRE 的に扱う考え方として DRE (Data Reliability…
