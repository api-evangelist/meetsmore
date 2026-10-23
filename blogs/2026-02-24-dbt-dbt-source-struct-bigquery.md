---
title: "dbtでメタデータ管理を完結させる！dbt sourceのメタデータをSTRUCT型カラムやポリシータグも含めBigQueryに連携する方法"
url: "https://engineering.meetsmore.com/entry/2026/02/24/150247"
date: "2026-02-24"
author: "meetsmore"
feed_url: "https://engineering.meetsmore.com/feed"
---
ミツモア データグループの酒井です。データ分析基盤の構築や運用を担当しています。 今回はdbt sourceのメタデータをBigQueryに連携させる方法をご紹介します。 メタデータは重要です。 データ量が増え続ける中、メタデータが適切に管理されていないと、各テーブルやカラムの意味を把握するのが困難になり、データ活用の効率が大きく低下します。 特にミツモアではAIツールであるtext2SQLを内製しており、この精度を上げる為にもメタデータの効率的な管理が必要になります。 ミツモアのデータ分析基盤ではBigQueryをデータウェアハウスとして、データ変換ツールにdbt coreを使用しています。…
