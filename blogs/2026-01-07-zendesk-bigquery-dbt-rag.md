---
title: "ZendeskのヘルプページをBigQueryとdbtでお手軽RAG構築"
url: "https://engineering.meetsmore.com/entry/2026/01/07/183018"
date: "2026-01-07"
author: "meetsmore"
feed_url: "https://engineering.meetsmore.com/feed"
---
ミツモアでAI関連の開発を担当している増田（@xmasudahiroto）です。 最近、社内でZendeskのヘルプページの記事をRAG化し、MCP経由でAIエージェントから利用可能にする開発を行いました。今回は、既存のデータ基盤であるdbtとBigQueryを活用し、短期間でRAGを構築した際の手順を共有します。 背景と課題 ミツモアでは顧客対応にZendeskを導入しており、プロダクトの仕様をまとめたヘルプページもZendeskのArticle機能で運用しています。 開発中のAIエージェントにおいて、「プロダクトの仕様に基づいた正確な回答」や「FAQを参照した回答」をさせたいという要望があ…
