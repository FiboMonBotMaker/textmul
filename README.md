# textmul

クソ雑魚な文字列掛け算ツールです

`pip install kusozako-text-multiplication`

```py
from textmul import TextMul
print(TextMul("text")*"text"*2)
# tttetxtteteeexetxtxexxxttttetxtttttetxtteteeexetxtxexxxttttetxtt
```

のように文字列をクロスジョイン結合のような状態で計算したりできます

```py
from textmul import TextMul
print(TextMul("text")**2)
# tttetxtteteeexetxtxexxxttttetxtt
```

べき乗の計算もできますが、計算量が現実的ではないので 5 乗あたりから挙動が怪しいです。
