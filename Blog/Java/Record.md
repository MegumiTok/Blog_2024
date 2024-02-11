# Record - Java16以降

## ポイント

recordクラスの生成されるコードは、イミュータブルな性質を持っています。イミュータブルなクラスは、一度生成されたインスタンスの状態を変更することができないため、そのクラスのインスタンスに対して setter を持っていません。

- immutable
- フィールドが `private final`であり、オブジェクトが immutable となる
- コンストラクタ、toString、equqls、hashCode 各メソッドが自動実装

## 背景

> Passing immutable data between objects is one of the most common, but mundane tasks in many Java applications.

> Commonly, we write classes to simply hold data, such as database results, query results, or information from a service.</br>
In many cases, this data is immutable, since immutability ensures the validity of the data without synchronization.

参考：[Immutable Objects in Java](https://www.baeldung.com/java-immutable-object#benefits-of-immutability)

> Since the internal state of an immutable object remains constant in time, we can share it safely among multiple threads.

> We can also use it freely, and none of the objects referencing it will notice any difference, we can say that immutable objects are side-effects free.

とりわけ DDD を考えるにあたって VO は immutable でありたい。

