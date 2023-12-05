---
title: "AWS SAA-C03 受験体験記"
emoji: "📚"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["aws", "aws認定試験", "saa"]
published: false
publication_name: "x_point_1"
---

# はじめに

先日 AWS 認定試験である AWS Certified Solutions Architect - Associate 試験 (SAA-C03) を受けました。

合格はしたのですが、決して良い点数とはいえず、勉強法の反省点もあるので、「こうすれば良かったな」ということも含めて記事にしました。

# なぜ SAA 受けるのか

SAA の問題文には「コスト効率を良くしたい」「障害に強くする」「パフォーマンスを上げたい」などといった要件に対して、どのような設計が適切か問われます。
したがって実務に直結する知識が得られると思いました。

> AWS 認定ソリューションアーキテクト – アソシエイトは、幅広い AWS のサービスにわたる AWS テクノロジーに関する知識とスキルを示します。この認定の焦点は、コストとパフォーマンスが最適化されたソリューションの設計にあり、AWS Well-Architected フレームワークに関する深い理解を示します。この認定は、認定された個人のキャリアプロファイルと収益を向上させ、利害関係者やお客様とのやり取りにおける信頼性と自信を高めます。

https://aws.amazon.com/jp/certification/certified-solutions-architect-associate/

また、AWS 経験としては 1 年ほどですが、使ったことがないサービスへの知識が浅かったので、今回で分からないサービスを無くしたいと思いました。

# 勉強方法

使った教材は以下で、勉強期間は 約 3 ヶ月でした。

**1. (模擬試験付き)徹底攻略 AWS 認定 ソリューションアーキテクト − アソシエイト教科書 第 3 版［SAA-C03］対応**

https://amzn.asia/d/8hZ1tMU
おすすめしている人が多く、自分も使用したので紹介しますが個人的には必須ではないかなと思います。
300 ページほどで最初に読んだ内容は忘れてしまっていました・・・。

**2. 【SAA-C03 版】これだけで OK！ AWS 認定ソリューションアーキテクト – アソシエイト試験突破講座**

https://www.udemy.com/course/aws-associate/
概要動画を視聴して、小テスト、模擬試験（3 回分）を解きました。
ハンズオンも含めて視聴すべきだと思いますが、時間の関係上飛ばしました。

**3. 【SAA-C03 版】AWS 認定ソリューションアーキテクト アソシエイト模擬試験問題集（6 回分 390 問）**

https://www.udemy.com/course/aws-knan/
6 回分とありますが、1 つは旧版なので 5 回分解きました。

**4. AWS ソリューションアーキテクト アソシエイト試験 対策動画（YouTube）**

https://www.youtube.com/watch?v=fsz6G45A4H4&t=356s

ここはよく試験に出るので覚えましょう！みたいな感じで言ってくれるので要点をおさえることができました。

## 反省点

### インプットに時間をかけすぎた

知らないサービスも多いので一旦概要をつかもう、と最初の 1 ヶ月は書籍や Udemy でインプットばかりしていました。
しかし初めて模擬試験を解いてみると 40%くらいしか正解できず非常に焦りました。

2 ヶ月目は解説を読み込んで理解できるようしよう、と切り替えるもこちらも時間がかかり模擬試験（Udemy 8 回 + 書籍付属 1 回）を 1 周できたのが試験 10 日前でした。
この時点でまだ正解率が 50~60％で、これはやばい！！！と半泣きになりました。

**早めに模擬試験を 1 周 -> 解説理解 -> 2 周目を解く** という進め方にすればこんなに追い込まれなかったなと反省しました。

必死に解説理解を進めて、試験直前に 2 周目を解くと 8 割以上になりました。

### 模擬試験で出なかったサービスもおさえる

本番で模擬試験であまり触れられていなかったサービス（EKS, DataSync）の問題が続き、頭が真っ白になりました。
模擬試験はほとんどの分野をおさえられていると思いますが、どのサービスも基本的なことは理解できている方が安心だと思いました。

## やってよかったこと

### まとめメモを作る

解説を繰り返し見返すために notion にまとめていました。
こちらを試験本番直前にも見返せたので、最後の追い込みに活用できました。

### 模擬試験は通しで解く

試験は 130 分で 65 問なので時間はそこまでカツカツになりません。
しかし問題文（ときどき選択肢も）が長文なので集中力を鍛えるために通しで解くようにしました。

# 最後に

計画性がなくてちょっと詰め込みすぎた受験体験でしたが、合格できてよかったです！
試験勉強を通して AWS の体系的な知識を得られたので、実務で活かせるようにしたいです。