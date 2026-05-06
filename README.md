# abc_liecrew_cpp - AtCoder ABC 過去問回答リポジトリ

このリポジトリは、競技プログラミングサイト[AtCoder](https://atcoder.jp/home) の「ABC（AtCoder Beginner Contest）」における過去の自分の回答を整理・管理するためのものです。

- 各コンテストごとにディレクトリを分けて回答を保存しています。
- 主にC++で実装しています（一部他の言語を含む場合があります）。
- コードの見直しや復習、精度向上のために継続的に更新していきます。

## ファイル構成

```
abc_reyobi_cpp/
├── myans_cpp/              # 解答ファイル
│   ├── a/                  # A問題
│   ├── b/                  # B問題
│   └── c/                  # C問題
├── include/
│   └── bits/
│       └── stdc++.h        # ローカル用ヘッダ
├── main.cpp                # メモ・スニペット
├── main2.cpp
└── README.md
```

### ファイル命名規則

| パターン | 例 | 説明 |
|---|---|---|
| `abc{番号}{難易度}.cpp` | `abc451a.cpp` | 基本解答 |
