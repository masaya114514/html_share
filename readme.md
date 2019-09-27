# Markdown サンプル

2019.09.27 SHIMADA Masaya

## 1. にゃーん

Markdownは基本的には普通のテキストです
「#」は見出し。htmlでいうところの`<h1>`とかに対応。

### 1.1 にゅーん

ソースコードを綺麗に書ける。シンタックスハイライトできる

```C
#include <stdio.h>
int main(int argc, char *args[])
{
    printf("Hello, world!\n");
    return 0;
}
```

***

## 2. にょーん

数式がすごくきれい(こなみ)
$$
e^{i\theta}=\cos(\theta)+i\sin(\theta)
$$
インラインでも$\cos(0)=0$みたいに書けます
_latex_ 記法です

### 2.1 ｳﾋｰ

__強調__ とか、~~打消し~~とかも書ける

- リスト1
- リスト2

|  | Markdown | Word |
|:-|:-|:-|:-|
|動作|軽量|うんち|
|メーカ|Microsoft|Microsoft|
> __Markdownはいいぞ。__
> _SHIMADA MASAYA_ (1998~3000)

## 参考文献

1. [メモ書きやドキュメント作成に便利な「Markdown記法」を使ってみよう](https://www.asobou.co.jp/blog/bussiness/markdown)

1. [世界最強の神獣使い〜外れスキル【デコイ】の力で寄ってきたのは神獣達だったので、一緒に仲良く暮らします〜](https://ncode.syosetu.com/n0934ft/)
