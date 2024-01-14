# 2024-01-14 What is a modern app?

## WHY and WHAT

### 私の抱いていた誤解

モダンなアプリって実に抽象的だ、と私は思っていた。何がモダンなんだと。
モダンな家、とか私の大好きなドラマのモダンファミリーのモダン。

そこで、モダンなアプリとは何かを調べてみた。

> A modern application is `an answer to the slow, ponderous, and long release times of monolithic software`</br>
 [What are modern applications and what do they mean for you?](https://www.tmaxsoft.com/what-are-modern-applications-and-what-do-they-mean-for-you/#:~:text=A%20modern%20application%20is%20an,(think%20Uber%20or%20Amazon).)

驚きだ。「最新の技術を使って...」っという書き方はされていない。今までslowだった開発を解決するための手法ってことだそうだ。ある程度 modern application とは何なのかというのは共通認識としてあるのだということだろう。

> Today's modern applications are cloud-native.

といった回答もすぐ見つかる。

もうちょっと調べてみると大体こんな感じだ。

「"モダン"が指すのは、古いアーキテクチャや開発手法から逸脱し、新しい技術やベストプラクティスを採用したアプリケーションのことです。

具体的には、モダンアプリケーションはクラウド上で動作し、コンテナ化されたマイクロサービスアーキテクチャを採用しています。これにより、アプリケーションは柔軟にスケールし、異なる環境で実行できるようになります。」

ちなみに、`AWSは、アプリケーションの設計、構築、管理を継続的に見直し、変化を受け入れ続ける開発戦略のことを「モダンアプリケーション」と呼んでいる`とのことだ。

さて、ここできっと Modern applications の何が嬉しいのかと疑問に思うはずなので次のセクションを見て欲しい。

## Modern App のメリット

### 市場投入を加速

- MVP（Minimum Viable Product：必要最低限の機能を備えたプロダクト）
- MVP開発を採用することで、市場への投入を早めることができ、ユーザーのニーズを探りながら機能改善や追加を繰り返すことができる

### 実験を繰り返せる

- Modular Architecture を採用
- それぞれのコンポーネントを個別に素早く変更できる柔軟性が備わる
- リスクを抑えてコンポーネントごとに実験をできる

### TCOの改善

- TCO (Total Cost of Ownership) is the overall cost of a product or service throughout its life cycle.
- 従量課金モデルのサービス
- AWSに管理を任せたら人件費などメンテナンスコストも削減できる

### 信頼性の向上

- 開発ライフサイクルの中でテストやリリースを自動化することで、ヒューマンエラーのリスクを減らせる
- また、それぞれのサービスに合ったモニタリングや、負荷が高くなった時のスケーリングや、リリースが失敗した時のロールバックなどにも対応できる

以上がメリットとしてあげられるそうだ。

では、どのように modern application を実現するのだろうか。

## Best practices for modern application development

modern application の実現方法は様々だた、共通認識みたいなものはあり、それはベストプラクティスとして紹介されている。

[Best practices for modern application development](https://pages.awscloud.com/rs/112-TZM-766/images/MAD_modern_application_eBook.pdf)

### モニタリング

- アプリケーションを適切に運用するためにはモニタリングが欠かせない

### Serverlessテクノロジーを使う

- 運用作業を自動化
- サーバーを意識せずに、アプリケーションの設計や開発に集中できる

### Release Pipeline の構築

- 自動化せず、プロセスが属人的になるとヒューマンエラーのリスク
- A well-built CI/CD release pipeline makes delivering to production quick, easy, and reliable

### Modular Architecture

- modern application では Modular Architecture という各モジュールを分割し疎結合に組み合わせて実現するアーキテクチャを採用
- Modular Architecture の中にも複数のアーキテクチャがある（例：Monolithic,modular monolith,Microservices）

## 最後に

> What do you need to build a modern application?</br>
If you ask this question to 10 people, you will get 10 different answers but chances are high that the common theme will be "technology"....you need to use Containers, Messaging, NoSQL databases etc. 

とあるように、modern application と言ったら色々な回答がある。そりゃそうだろうし、それが私の思っていた疑問だ。何がモダンなのだと。調べていくうちにわかったのが、modern application の特徴ってうのは「ある程度傾向がある」ということと、それを「実現するための方法もいろいろあるがベストプラクティスの提唱がされている」のでみんなそれに倣おうよ、と言った感じの話だということだ。

ちなみに、来週 AWS Certified Cloud Practitioner の試験を受けようと思っているが先に modern application についてなぜこれを知る必要があるのが学べてよかったと思う。知らないと、なぜこういうテクノロジーがあるのかのモチベーションに共感できない。

## 問題

「modern applicationとはなにですか？」この質問に2分程度で答えなさい。

答えられなければ理解してないぞ..!!

ポイント：

- 「なぜ」に答える
- modern application はあくまで手段
- modern application のメリット
- modern application の実現方法のベストプラクティス

## Ref

- [AWSで実現するモダンアプリケーション入門 〜サーバーレス、コンテナ、マイクロサービスで何ができるのか ](www.amazon.co.jp/dp/4297133261)

- [Modern Application - WHY and WHAT](https://www.linkedin.com/pulse/modern-application-why-what-rajeev-sakhuja)