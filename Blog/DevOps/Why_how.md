# When the WHY is clear, the HOW is easy

Modern Application について調べていたら興味深い記事に出会った。

それはこちらだ

[Modern Application - WHY and WHAT](https://www.linkedin.com/pulse/modern-application-why-what-rajeev-sakhuja)

記事の中でタイトルにもした言葉が紹介されている

> when the WHY is clear, the HOW is easy

今年は「物事は何かについて知っているかどうかということよりも、問題に対してどのように向き合うかということの方が大事なのでは」、というような問いについて考えたいと思っている。曖昧で適当に納得ぜず `Why` を考えて、その上で `How` を導き出したい。これはクライアントと話す時なんかが特にそうだ。「この機能を追加してほしい」と言われて「はい、わかりました。見積もりを出します。」と答えるのは全くもってナンセンス。お客さんが本当に喜ぶのはお客さんが求めているものを一緒になって考えることだ。言われたから言われた通りやりました、というのはプロでもなんでもない。つまり、「この機能を追加してほしい」と言われたら「それはなぜその機能が欲しいと思ったのですか」と Why を探ることが絶対に必要だ。いい仕事をするには「聞いちゃまずいと思ったから、、」なんて事はない。ずかずか聴くべき。相手のことを知りたいから聴くのであって質問されて嫌な思いをするお客さんなんていない。むしろ聞いてあげないほうが「この人は私たちのことに全く無関心なんだな」と思われる。

、、自分に言い聞かすように書いてみた。お客さんのことはもちろんすごく大事だが多人数相手だとまだ慣れていない部分が多く、自分の未熟さを痛感する。

だいぶ話が逸れたが、記事に戻ろう。

記事にはとても気になった問いがいくつかあった。

> Why do we build applications?

に対して、"To meet the needs of the users" と答えておしまいにしない。

> Why should we meet the needs of our users?

と言っても、答えはシンプルだ。記事では例えば "to meet the needs of the business".としている。

ポイントはこの考え方だ。これに乗っ取って次の質問が modern application を考える上で生まれる。

## What do you `need` to build a modern application?

> If you ask this question to 10 people, you will get 10 different answers but chances are high that the common theme will be "technology"....you need to use Containers, Messaging, NoSQL databases etc. This is all good but these are technology decisions that are a means to realize a modern application. In my view one has to focus on 3 aspects.

3つのaspectがあるらしい。

- Continuous & Rapid evolution

> In order to build modern applications you MUST be in a position to evolve, change & improve at a rapid pace.

- Operational excellence

> Amazon EC2 is available for each AWS region with a Monthly Uptime Percentage of at least 99.99%

障害に強いアプリケーションを構築する、障害に備えてチームを準備する。障害をモニタリングする、機械学習などを用いて障害を予測するなどなど、、。

- Organization culture

> Modern applications require a modern mindset

詳しくは元記事を読んでもらいたいが難しい。さらっと読む分にはシンプルで「その通りだ」で納得してしまうが、根底の思いを汲み取ろうとするとまだまだ自分は勉強不足だと痛感する。しかし少なくとも、以下のメッセージからも分かるように「Why」と「How」を意識してテクノロジーに向き合って行く姿勢は忘れないように根底に持ちたい。

> If you have to take ONE message from this article - it is that for building and managing a modern application you need to think beyond technology.