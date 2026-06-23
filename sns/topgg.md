---
title: TopGG通知
description: TopGGでのVote通知の設定方法
published: true
date: 2026-06-23T08:18:56.432Z
tags: topgg, sns
editor: markdown
dateCreated: 2026-06-23T08:18:56.432Z
---

# TopGG通知
TopGG通知を使用することで、TopGGにてサーバーメンバーがVoteを行ったときに自動でメッセージを送信させることができます。

## Voteされたときに通知する
以下の手順で、Voteされたときに通知することができます。
1. `/sns topgg set` コマンドを実行し、WebhookURLをコピーする
2. TopGGのWebhook設定に、WebhookURLを入力し、APIKeyをコピーします。
3. 「APIKeyを入力する」ボタンをクリックし、APIKeyとメッセージを入力し、送信する
4. ここまでうまくいけば、TopGGでVoteした際にメッセージが送信されるはずです。

## Voteされたときのメッセージの変数
TopGGでVoteされたときのメッセージには以下の変数が使用できます。
| 変数名 | 説明 | 例　|
| ---- | ---- | ---- |
| `{user}` | ユーザーのメンションを埋め込みます。 | @サメちゃん |