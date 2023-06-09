# rails_portfolio

## ■ サービス概要

このサービスは、コンビニエンスストアのスイーツをより楽しく消費するためのものです。
スイーツのカロリーに応じた距離を東海道五十三次の旅路として進んでいきます。
食べたカロリー分の距離を双六のように進みながら、旅行気分を楽しめます。


## ■ユーザーが抱える課題

コンビニスイーツをもっと楽しみながら食べたい
コンビニスイーツの選択肢が多すぎる
カロリーが気になり、食べること自体躊躇してしまう


## ■課題に対する仮説
スイーツ名だけではユーザーは特徴や味の傾向がわかりにくい
スイーツを食べる楽しさよりも、カロリーへの不安が大きい


## ■解決方法

カロリー分だけコースを進むことで、スイーツを食べること自体が楽しくなる。
コンビニ大手３社のスイーツを一元化して表示する。
実際に食べたスイーツを選択し、カロリーを計算する。


## ■メインのターゲットユーザー

スイーツをはじめ、甘いもの好きな人
コンビニをよく利用しているが、スイーツやお菓子はあまり購入していない人


## ■実装予定の機能

未ログインユーザー
- 新規ユーザー登録機能
- ログイン機能
- 利用規約
- プライバシーポリシー

ログインユーザー
- 一覧画面からスイーツの選択ができる
- ユーザーが食べたコンビニスイーツのカロリー応じて、双六のマップ上で距離が進む
- 食べたスイーツを一覧で表示する
- 食べたスイーツをTwitterで共有する
- 進んだ距離を記録する
- ログアウト機能

MVP後
- 食べたスイーツの感想(コメント機能)
- スイーツお気に入り機能
- ユーザー間でのランキングや成果の共有機能
- お気に入りスイーツ機能


## ■なぜこのサービスを作りたいのか？

コンビニエンスストアのスイーツは私自身が大好きであり、
その魅力を多くの人に知ってもらいたいという思いがあります。
コンビニスイーツは手軽に入手でき、多様な種類や美味しさが魅力です。
しかし、カロリーが気になるかたもいます。
カロリーを少し気にしつつ楽しくコンビニスイーツをたべる方法を提供したいと考えました。


## ■スケジュール

企画〜技術調査：6/1 〆切
README〜ER 図作成：6/14 〆切
メイン機能実装：6/15 - 7/31
β 版を RUNTEQ 内リリース（MVP）：8/1 〆切
本番リリース：8月中旬


## ■ 技術選定

- Rails6
- postgresql
- JavaScript
- Bootstrap
- heroku
- スクレイピング（コンビニスイーツデータ）

## ■figma

https://www.figma.com/file/LQcSAi4RL9NgNaRq6sBF74/%E3%81%82?type=design&node-id=0%3A1&t=7iYUfTDqgn6yGsVh-1

