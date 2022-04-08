# Markdown記法 トレーニング

## コードの挿入  

```
x:int = 10
print x
```  

~~~
x:int = 10
print x
~~~  

## コードスパン
### インラインで表示
`print "Hello World"` とインラインで書ける。  

### バッククォートを囲んで表示
`` `バッククォート` `` や ``` ``バッククォート*2`` ``` も記述できる  

開始と終了のバッククォートを囲みたいバッククォートの数n+1と記述すること。  


## リスト(dl, dt, dd)
<dl>
    <dt>1</dt>
    <dd>cat</dd>
    <dt>2</dt>
    <dd>dog</dd>
    <dt>3</dt>
    <dd>bird</dd>
<dt>

## ボールド(strong)
<strong>太字で書ける</strong>

## コード(code)
<code>コードが書ける</code>
    
## リンク(a)
<a href="https://twitter.com/done_vrc">Twitter</a>  
[GitHub](https://github.com/done-san)  

### タイトル付きリンク
[Example](https://www.example.com, "EXAMPLE.COM")

## チェックボックス
- [ ] A
- [x] B
- [ ] C
    
## 引用
> Blockquotes
>
> > 引用は、、、
> > ネストできます

## 水平線
* * * 
***
*****
- - -
---
-----

## テーブル
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| -------    | -------     | -------      |
| -------    | -------     | -------      |
| -------    | -------     | -------      |
| -------    | -------     | -------      |
| -------    | -------     | -------      |
| -------    | -------     | -------      |

    
## 絵文字
\:clap: 拍手

## エスケープ
\# Header 1  
\## Header 2  
\### Header 3  


