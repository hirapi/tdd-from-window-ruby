[車窓からのTDD](http://objectclub.jp/technicaldoc/testing/stack_tdd.pdf)のコードを勉強用にRubyで書き直したものです。


仕様（上記PDFより）

```
・isEmpty()でスタックが空の場合、true。それ以外 false を返す。
 boolean isEmpty()
・size()でスタックのサイズを取得する。
 int size()
・push()で引数の値をスタックの一番上に積む。
void push(int value)
・pop()でスタックの一番上の値を取り除く。
void pop()
スタックが空の場合、java.util.EmptyStackException が発生する
・top()でスタックの一番上の値を取得する。
 int top()
スタックが空の場合、java.util.EmptyStackException が発生する 
```

`isEmpty()`だけRubyぽく`empty?()`に変えてあります。
