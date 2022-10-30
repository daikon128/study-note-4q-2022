# 2022-10-28
## bashのテキスト操作
ctrl + a 最初
ctrl + e 最後
meta + 矢印 単語飛ばし

練習用サンプル
```bash
curl -XGET http://localhost:8080
```

## React stateとライフサイクル(途中)
https://ja.reactjs.org/docs/state-and-lifecycle.html
次はここから
https://ja.reactjs.org/docs/state-and-lifecycle.html#using-state-correctly

## audioタグ(流し読み)
https://developer.mozilla.org/ja/docs/Web/HTML/Element/audio

# 2022-10-29
## What's wrong with atomic design?
linkedin.com/pulse/whats-wrong-atomic-design-james-ecclestonk

*A button is considered to be an atom and when combined with other elements like an input field it will create a form which is considered to be a molecule.*
*They are both navigational tools that should sit somewhere in the same group but in Atomic Design they are split based on their complexity. It would make more sense to organise components into groups based on their functionality.*

atomicデザインにおける欠点は複雑さによって分割されている点。機能別で分けた方がより理にかなっている
また読み直す

# 2022-10-30
design systemにキャプチャ機能を追加
使っているカスタムタグ名から、ブラウザの該当ページをハイライト
みたいなものができたら便利そう

## atomic designに関する疑問
atomicデザインは複雑さによって分割とあるが、機能+複雑さで分けられないだろうか？
デザインシステムがあるならばその欠点を解消できるのではなかろうか？
そもそものatomic designの思想を知らないので調べてみる

https://bradfrost.com/blog/post/atomic-web-design/
what is atomic designの手前まで
終始、デザインシステムの話しかしていない。
あくまで、体系的にデザインシステムを構築するための方法として、
原子から世の中のものが構成されているように、インターフェースの基本要素に分解して
組み上げられることを述べている。

what is atomic designの章が各要素(atom, molecules and more)の説明だったため一旦飛ばす。
あくまでデザインシステムの構成方法として述べている。

以下がいろんなデザパタを例にあげてて面白い
https://zenn.dev/mutex_inc/articles/beca85dd7fdcae

