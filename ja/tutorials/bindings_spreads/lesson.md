コンポーネントや要素が不定の数の属性を受け入れる場合、それらを個別に渡すのではなく、オブジェクトとして渡す方が理にかなっている場合があります。これは、DOM 要素をコンポーネントでラップする場合に特に当てはまり、デザインシステムを作る際にはよくあることです。

これには、スプレッド演算子 `...` を使用します。

不定の数のプロパティを持つオブジェクトを渡すことができます:

```jsx
<Info {...pkg} />
```