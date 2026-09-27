# import とパッケージ階層を表すピリオドの使い方

パッケージは，Python のコードをまとめたもので，モジュール（Pythonのファイル）の集まりです．

Python では，`import` 文を使って他のパッケージ（自分で書いたもの，標準ライブラリ，サードパーティライブラリなど）を読み込むことができます．
パッケージにアクセスする時は，パッケージ名の後に `.` をつけて，パッケージ内の関数や変数にアクセスします．
```python
import math
print(math.sqrt(2))
```
標準ライブラリは，Python に同梱されているパッケージで，ドキュメントに[リスト](https://docs.python.org/3/library/)されています．

長いライブラリ名は，`as` を使って自分で短縮名を決められrます．誰でも使うような有名な短縮名があります．
```python
import numpy as np
import pandas as pd
print(np.array([1, 2, 3]))
print(pd.DataFrame({'width':[1, 2,3]})
```

パッケージは階層的にサブパッケージに分類されており，`.`で区切ることで，階層の一部分だけを読み込むことが可能です．このピリオドは，メンバーを参照するための演算子とは異なります．
```python
import os.path
print(os.path.cwd()) # 現在のディレクトリを表示
```

`from a_package import b_module` のように書くと，`a_package.b_module` を `b_module` という名前で使えるようになります．
```python
from urllib import parse
parse.urlparse('https://example.com/path')

from urllib.parse import urlparse
urlparse('https://example.com/path')
```