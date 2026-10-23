---
title: "ネットワーク隔離したDev Containerを作り安全にClaude Codeを本番環境に繋げる"
url: "https://engineering.meetsmore.com/entry/2026/08/18/161129"
date: "2026-08-18"
author: "meetsmore"
feed_url: "https://engineering.meetsmore.com/feed"
---
ミツモアでAI関連の開発を担当している増田（@xmasudahiroto）です。 Claude Codeをチームで本格的に使い始めると、いかにAIエージェントを自律的に動かしつつ、同時にセキュリティを担保するか、について考える必要が出てきます。ミツモアでも、Claude Codeの実行環境として、Anthropicが公式リポジトリで公開しているDev Containerの実装を参考に、ネットワーク隔離した環境を作成したので、それについて紹介したいと思います。 https://code.claude.com/docs/ja/devcontainer この記事では、まずClaude Codeの運用…
