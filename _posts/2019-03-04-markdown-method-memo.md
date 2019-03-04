---
layout: post
title:  "マークダウン記法のメモ"
categories: [ Jekyll, Markdown ]
image: assets/images/markdown.png
featured: true
---

マークダウン記法を覚えれば、わざわざHTMLのめんどくさいタグでマークアップしないですみます。  
ということで、ぜひ覚えましょう。

<br>
<br>
## 見出し
***
```MarkDown:MarkDown
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6
```
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

<br>
<br>
## リスト
***
```MarkDown:MarkDown
* リスト1
* リスト2
	* ネストもできる
1. 番号付きリスト1
2. 番号付きリスト2
	1. ネストもできる
```
* リスト1
* リスト2
	* ネストもできる

1. 番号付きリスト1
1. 番号付きリスト2
	1. ネストもできる  

<br>
<br>
## 引用
***
```MarkDown:MarkDown
> 引用
>> 二重引用 
```
> 引用  
>> 二重引用  

<br>
<br>
## 飾り文字
***
```MarkDown:MarkDown
*イタッリク体*
**ボールド**
***イタリック体 & ボールド***
~~打ち消し線~~
```
*イタッリク体*  
**ボールド**  
***イタリック体 & ボールド***  
~~打ち消し線~~  

<br>
<br>
## 水平線
***
```MarkDown:MarkDown
↓水平線見本↓
***
---
```
↓水平線見本↓
  
***

---

<br>
<br>
## コード表記
***
```MarkDown:MarkDown
`バッククオートで囲む`

\```Ruby
 puts "バッククオート3つで囲むと"
 puts "ブロックで表記できる"
\```
```
`バッククオートで囲む`

```Ruby
puts "バッククオート3つで囲むと"
puts "ブロックで表記できる"
```

<br>
<br>
### リンク
***
```MarkDown:MarkDown
[インラインリンク](https://twitter.com/bitkangaroo3)

[外部参照リンク][1]

[1]: https://twitter.com/bitkangaroo3 
```
[インラインリンク](https://twitter.com/bitkangaroo3)  

[外部参照リンク][1]

[1]: https://twitter.com/bitkangaroo3  

<br>
<br>
## 表
***
``` MarkDown
| A simple | table |
| with multiple | lines |

|名前|年|都道府県|
|:---|:-:|---:|
|left|senter|right|
|=|=|=|
|フッター1|フッター2|フッター3|
```

| A simple | table |
| with multiple | lines |

<br>

|header1|header2|header3|
|:---|:-:|---:|
|left|center|right|
|=|=|=|
|フッター1|フッター2|フッター3|

<br>
<br>

適宜追加していきます。

<br>
<br>