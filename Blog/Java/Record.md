# Record - Java16以降

## ポイント

- immutable
- フィールドが `private final`であり、オブジェクトが immutable となる
- コンストラクタ、toString、equqls、hashCode 各メソッドが自動実装

## 背景

> Passing immutable data between objects is one of the most common, but mundane tasks in many Java applications.

> Commonly, we write classes to simply hold data, such as database results, query results, or information from a service.</br>
In many cases, this data is immutable, since immutability ensures the validity of the data without synchronization.

参考：[Immutable Objects in Java](https://www.baeldung.com/java-immutable-object#benefits-of-immutability)

とりわけ DDD を考えるにあたって VO は immutable でありたい。