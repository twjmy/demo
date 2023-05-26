---
tags: 從HTML到MarkDown
title: HTML 簡介與基礎語法
description: 從HTML到MarkDown1-講義簡報-資訊社主題社課
image: 'https://i.imgur.com/1Q6Rm96.png'
slideOptions:
 loop: true
 theme: simple
---

<style>
hr{display:none}
section h1 span{font-size:40%}
section h1,section h2,section h3,section h4,section h5,section h6,section p,section blockquote
{color:#656c73!important}section a{color:#337ab7!important}section img{border:0!important}</style>

# <span style="font-size:20%">[從HTML到MarkDown/](/@NCHUIT/mdhtml)</span><span>HTML 簡介與基礎語法</span>
> [name=VJ][time= 110,10,19]

----

:::spoiler <h2 style="display:inline">目錄</h2> {state=open}

[ToC]
+ 投影片：https://hackmd.io/@NCHUIT/mdhtml1
+ 網頁：https://hackmd.io/@NCHUIT/mdhtml

:::

----

## 迷思

----

### </>

首先，HTML 不是**程式**語言，而是**標記**語言。
~~Progarm~~ **Code**

----

![](https://i.imgur.com/ysHmDCB.png)

---

## [HTML](https://zh.wikipedia.org/wiki/HTML)
<table><tr><td><b>H</b>yper<b>T</b>ext <b>M</b>arkup <b>L</b>anguage (超文本標記語言)，縮寫：HTML，是一種用於建立網頁的標準<b>標記語言</b>。<br>瀏覽器可以讀取HTML檔案，並將其彩現成<b>視覺化</b>網頁。<br><h6>HTML描述了一個網站的結構語意隨著線索的呈現，使之成為一種標記語言而<em>非程式語言</em>。</h6></td><td><img src='https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/HTML.svg/800px-HTML.svg.png'></td></tr></table>

----

![](https://i.imgur.com/YuFRPHe.png)

----

![](https://i.imgur.com/VIIXQD2.png)

----

### FB 社團 - 發文

![](https://i.imgur.com/1IA2NE0.png)

----

### [網絡論壇](https://zh.wikipedia.org/wiki/%E7%BD%91%E7%BB%9C%E8%AE%BA%E5%9D%9B) - 發帖
![](https://i.imgur.com/igw3RE3.png)

----

### [巴哈姆特哈啦區](https://forum.gamer.com.tw/) - 發文

![](https://i.imgur.com/2eE3yf1.png)

### 巴哈姆特攻略百科 - 發文/編輯

![](https://i.imgur.com/IdXjeEH.png)

----

### 巴哈姆特我的小屋 - 創作

![](https://i.imgur.com/hNTDIwb.png)

---

## [HTML 元素](https://zh.wikipedia.org/wiki/HTML%E5%85%83%E7%B4%A0)

HTML 中，一個 HTML 元素是 HTML 檔案(或訊息)的一個基本組成單元。HTML 檔案採用採用**樹狀結構**安排 HTML 元素。
常見的 HTML 元素有**標題**、**段落**、**連結**、**列表**、**嵌入媒體**等等。

----

### 例子(標題)

段落 [連結](https://google.com) <span style="color:red">紅色</span> ==標記==

+ 清單項目**甲**
+ 清單項目*乙*

1. 列表項目***甲***
2. 列表項目~~乙~~

> 引言

![](https://i.imgur.com/HviOatP.png "圖片")

----

### 動動手: 檢查方法1 - 選單>檢查

Chrome ![](https://i.imgur.com/Utx18BP.png =200x) Edge ![](https://i.imgur.com/5TQdPUX.png =200x)

:::info
🕹快捷鍵: 在 Chrome 或 Edge 瀏覽器中按下 `F12` 或 `Ctrl`+`Shift`+`I` 可以在 `Elements` 頁面檢視所有 HTML 元素。
:::

----

### 動動手: 檢查方法2 - 選取工具
Chrome ![](https://i.imgur.com/u7MUrsr.png =250x) Edge ![](https://i.imgur.com/JIuGjD4.png =250x)

:::info
🕹快捷鍵: 在 Chrome 或 Edge 瀏覽器中按下 `Ctrl`+`Shift`+`C` 可以直接啟動選取模式。
:::

![](https://i.imgur.com/gLDmcZD.png)

---

## `*.html` 基礎框架

```html=
<html>
  <head>
    <title>網頁標題</title>
    <meta name="description" content="網頁描述">
    <link rel="icon" href="https://hackmd.io/favicon.png">
    <!--以及更多-->
  </head>
  <body>
    我才是一般內文
    <!--網頁內容-->
  </body>
</html>
```
`<head>`內的都不需要用`</*>`關起來

----

![](https://i.imgur.com/AkdrT2T.png)

----

![](https://i.imgur.com/vXQD0T3.png) ![](https://i.imgur.com/uf17vtm.png)


---

## <small>[HTML Tag](https://www.w3schools.com/tags/default.asp) `<tag>...</tag>`</small>
==很多==，特別又想用的要自己找，下面介紹常用的

![](https://i.imgur.com/gwN1YXm.png)

----

### 一般內文

我不是一般內文
![](https://i.imgur.com/uYPYGYT.png)

----

![](https://i.imgur.com/93TF1CK.png =75%x)

----

### 段落 [`<p>`](https://www.w3schools.com/tags/tag_p.asp)

```html=!
<p>我是第一段</p>
<p>我是第二段</p>
```

<p>我是第一段</p>
<p>我是第二段</p>

----

![](https://i.imgur.com/HVNacF2.png)

### 段內換行 [`<br>`](https://www.w3schools.com/tags/tag_br.asp)

\*不用`</br>`
```html=!
<p>段內<br>換行</p>
```

<p>段內<br>換行</p>

----

![](https://i.imgur.com/VOP7Ivb.png) ![](https://i.imgur.com/UDwdHhK.png) ![](https://i.imgur.com/ng3cBy2.png)

### 置中/右/左
`style="text-align:center/right/left"`
```html=!
<p style="text-align:center">置中文字</p>
<p style="text-align:right">置右文字</p>
<p style="text-align:left">置左文字</p><!--預設-->
```
<p style="text-align:center">置中文字</p>
<p style="text-align:right">置右文字</p>
<p style="text-align:left">置左文字</p>

----

![](https://i.imgur.com/aDFKCQA.png) ![](https://i.imgur.com/b0I2M5P.png) ![](https://i.imgur.com/AqoYJnG.png) 

----

### 標題 [`<h1><h2>...<h6>`](https://www.w3schools.com/tags/tag_hn.asp)

預設只有到h6，想新增就[自己來](https://stackoverflow.com/questions/14908463/how-to-make-new-heading-tag-numbers-such-as-h7-h8-etc)

```html=!
<h1>標題一</h1>
<h2>標題二</h2>
<h3>標題三</h3>
<h4>標題四</h4>
<h5>標題五</h5>
<h6>標題六</h6>
```

<h4>標題四</h4><h5>標題五</h5><h6>標題六</h6>

----

:::spoiler 練習: 試試將 ***任一標題*** 置中
```html=!
<h4 style="text-align:center">置中標題四</h4>
```
<h4 style="text-align:center">置中標題四</h4>
:::

----

![](https://i.imgur.com/T3EY710.png) ![](https://i.imgur.com/L7FtQ1n.png) ![](https://i.imgur.com/qeMmNGg.png) ![](https://i.imgur.com/HtjgCJY.png)

### **粗體** *斜體* ++底線++ ~~刪除線~~

[`<B>`](https://www.w3schools.com/tags/tag_b.asp) [`<I>`](https://www.w3schools.com/tags/tag_i.asp) [`<U>`](https://www.w3schools.com/tags/tag_u.asp) [`<S>`](https://www.w3schools.com/tags/tag_s.asp)

```html=!
<b>粗體</b> <i>斜體</i> <u>底線</u> <s>刪除線</s>
```

<b>粗體</b> <i>斜體</i> <u>底線</u> <s>刪除線</s>

:::spoiler 練習: <b><i><u><s>我全都要</s></u></i></b>
```html=!
<b><i><u><s>我全都要</s></u></i></b>
```
:::

----

### 段內區塊 `<span>` & 文字顏色 [`style="color:*"`](https://www.w3schools.com/cssref/css_colors.asp)

```html=!
<p><span style="color:blue">藍色</span>
 <span style="color:red">紅色</span></p>
```

<p><span style="color:blue">藍色</span> <span style="color:red">紅色</span></p>

----

![](https://i.imgur.com/1a2q59v.png)

### 首行縮排
`style="text-indent:*"`
```html=!
<p style="text-indent:2em">如果沒有到第二行就看不出來(?)補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字</p>
```
<p style="text-indent:2em">如果沒有到第二行就看不出來(?)補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字補字</p>

----

![](https://i.imgur.com/wvRTh7a.png) ![](https://i.imgur.com/xOvp9vy.png) ![](https://i.imgur.com/khDck8Q.png)

----

![](https://i.imgur.com/0hkINGd.png)

### 無序清單`<ul>`

預設是實心圓點，其他符號可以在這找，有兩種方法:
1. [`type="circle/disc/square"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul#attr-type)
2. [`style="list-style-type:'*'"`](https://www.w3schools.com/cssref/pr_list-style-type.asp)

可以直接把符號打在\*的地方

----

```html=!
<ul style="list-style-type:'🙏'">
<li>項目一</li><li>項目二</li><li>項目三</li>
</ul>
```

<ul style="list-style-type:'🙏'">
<li>項目一</li><li>項目二</li><li>項目三</li>
</ul>
<ol>
<li>項目一</li><li>項目二</li><li>項目三</li>
</ol>

```html=!
<ol type="1/a/A/i/I">
<li>項目一</li><li>項目二</li><li>項目三</li>
</ol>
```

----

![](https://i.imgur.com/26aJiNA.png =x350)

### 有序清單`<ol>`

1. [`type="1/a/A/i/I"`](https://www.w3schools.com/tags/att_ol_type.asp)
2. [`style="list-style-type:'*'"`](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_list-style-type_all)

----

![](https://i.imgur.com/Scl5t51.png) ![](https://i.imgur.com/0mBvnt7.png) ![](https://i.imgur.com/agTlaUn.png)

### 超連結 [`<a>`](https://www.w3schools.com/tags/att_a_href.asp)

```html=!
<a href="https://www.google.com" target="_blank">超連結</a>
<a href="https://www.google.com">我沒有 target="_blank"</a> 
```
<a href="https://www.google.com" target="_blank">超連結</a> <a href="https://www.google.com">我沒有<code>target="_blank"</code></a> 

----

### 插入圖片 [`<img>`](https://www.w3schools.com/tags/tag_img.asp)
\*不用`</img>`
```html=!
<img src="https://<網址>" title="提示文字"
 width="寬度(單位:像素)" height="高度(單位:像素)">
```

<img src="https://www.kindpng.com/picc/m/254-2547396_javascript-html-css-logo-hd-png-download.png" width="500" title="HTML5 JS CSS3">

----

![](https://i.imgur.com/QSh8zWB.png =200x) ![](https://i.imgur.com/zrcLTBF.png)

----

### 嵌入 `<iframe>`

```html=!
<iframe src="https://<網址>"
 width="寬度(單位:像素)" height="高度(單位:像素)">載入中…</iframe>
```

----

<iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Fit.nchu%2Fposts%2F5119600108056280&show_text=true&width=500" width="500" height="659" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">載入中…</iframe>

----

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeSdsx_EHjL3VdxKxe3gnUWgmW9GWFWkyoEk-ywRuThMW1XBQ/viewform?embedded=true" width="640" height="640" frameborder="0" marginheight="0" marginwidth="0">載入中…</iframe>

----

### [`<table>`](https://www.w3schools.com/html/html_tables.asp)

```html=!
<table>
    <thead>
        <td>欄位標題A</td><td>欄位標題B</td>
    </thead>
    <tbody>
        <tr><td>欄位A1</td><td>欄位B1</td></tr>
        <tr><td>欄位A2</td><td>欄位B2</td></tr>
    </tbody>
</table>
```

<table>
    <thead>
        <td>欄位標題A</td><td>欄位標題B</td>
    </thead>
    <tbody>
        <tr><td>欄位A1</td><td>欄位B1</td></tr>
        <tr><td>欄位A2</td><td>欄位B2</td></tr>
    </tbody>
</table>

----

### `<div>`

---

## 補充

----

### [HTTP](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)

**H**yper**T**ext **T**ransfer **P**rotocol(超文本傳輸協定)，是全球資訊網絡數據通信的基礎。

### [HTTPS](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%AE%89%E5%85%A8%E5%8D%8F%E8%AE%AE)

**H**yper**T**ext **T**ransfer **P**rotocol **S**ecure，是一種透過計算機網路進行安全通訊的傳輸協定。**HTTPS**經由**實聯制**進行通訊，但利用SSL/TLS來加密封包，更安全。

----

![](https://miro.medium.com/max/875/0*s2u2kEx-8rAhxGaW)

----

### 請求與回應

HTTP 的基本運作方式就像上圖一樣，我們開啟網頁、或在網頁上做特定的操作的時候，其實都是在向伺服器發送請求(`request`)，而伺服器則會對應 `request` 給予我們回應(`response`)。

回應(`response`)的主要內容就是 ==HTML==。

----

### [![](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Html5_css3_styling.svg/225px-Html5_css3_styling.svg.png =60x) CSS](https://www.w3schools.com/css/default.asp)

剛剛放在`<tag *>`開頭旁邊`style="*"`可一次寫完，但要指定哪些`<tag>`套用是門學問，像下面這樣。
另外也可以存成`*.css`檔使用，`<style>`就可以拔掉

```html=
<style>
section h1,section h2,section h3,
section h4,section h5,section h6,
section p{
    color:#656c73 !important
}
section a{
    color:#337ab7 !important
}
section img{border:0!important}
hr{display:none}
</style>
```

----

### [![](https://www.clipartmax.com/png/middle/470-4707396_javascript-icon-html-css-js-icons.png =60x) JavaScript](https://www.w3schools.com/js/default.asp)

這才叫程式(Program')語言，讓使用者可以跟網頁互動，對資料進行流程控制等操作。

----

可以直接在觸發動作時使用

```html=!
<button onclick="this.style='display:none';window.print()">Print this page</button>
```

也可以在網頁開啟時就跑起來

```html=!
<html>
<body>

<p></p>

<script>
document.getElementsByTagName("p")[0].innerHTML="Hello world";
</script>

</body>
</html> 
```

也可以存成`*.js`，`<script>`就可以拔掉
```html=!
<script src="myScript1.js"></script>
```

----

### [伺服器](https://developer.mozilla.org/zh-TW/docs/Learn/Common_questions/What_is_a_web_server)

「網路伺服器」（web server）可以指軟體、也可以指硬體、還可以指它們共同運作的狀態。

存放網路伺服器軟體(如phpMyAdmin)、網站檔案（如`*.html`、`*.css`、`*.js`）的電腦。

它會連上網際網路（Internet）並能和其他連上網的設備做物理數據交換。

----

###  [![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/320px-PHP-logo.svg.png =10%x) PHP](https://www.w3schools.com/php/default.asp)

全稱：「PHP：Hypertext Preprocessor」，即「PHP：超文字預處理器」，是一種開源的通用電腦手稿語言。PHP的應用範圍相當廣泛，尤其是在網頁程式的開發上並**可嵌入HTML中使用**。

```php=!
<?php
     echo 'Hello World!';
?>
```

需存成`*.php`，只能在伺服器上跑

----

### [SQL](https://www.w3schools.com/sql/default.asp)
SQL（Structured Query Language:結構化查詢語言）是一種特定目的程式語言，用於管理關聯式資料庫管理系統（RDBMS），或在關係流資料管理系統（RDSMS）中進行流處理。[MySQL?](https://kknews.cc/zh-tw/code/abzrm56.html) [phpMyAdmin?](https://zh.wikipedia.org/wiki/PhpMyAdmin)

```sql
SELECT 學號, 姓名 FROM 社員名單;
```
![](https://i.imgur.com/08vEzDc.png)

[SQL你的Google試算表](https://www.wfublog.com/2016/11/google-4-sql.html)

----

社員名單:
|    學號    |  姓名  ||    學號    |  姓名  |
|:----------:|:-----:|-|:----------:|:-----:|
| 41#####020 | 談ｏｏ || 41#####134 | 簡ｏｏ |
| 41#####140 | 白ｏｏ || 41#####014 | 李ｏｏ |
| 41#####027 | 廖ｏｏ || 41#####006 | 黃ｏｏ |
| 41#####057 | 吳ｏｏ || 41#####041 | 賴ｏｏ |
| 41#####004 | 吳ｏｏ || 41#####031 | 詹ｏｏ |
| 41#####120 | 江ｏｏ |

----

### ![](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg =15%x ) MarkDown

```=!
# 標題1
## 標題2
- 無序清單
1. 有序清單
**粗體**	
*斜體*	
~~刪除線~~
```

這投影片跟網頁就是用 MarkDown 寫的

---

| 實聯制<br><small>~(因應防疫務必簽到)~</small> | 入社表單 |
| :---: | :---: |
| [![](https://i.imgur.com/o5kwHyy.png =260x)](https://forms.gle/bghmKYxjc9v7m9WE8) | [![](https://i.imgur.com/tChibID.jpg =260x)](https://reurl.cc/q1keqn) |

---

:::spoiler 實聯制
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeSdsx_EHjL3VdxKxe3gnUWgmW9GWFWkyoEk-ywRuThMW1XBQ/viewform?embedded=true" width="640" height="640" frameborder="0" marginheight="0" marginwidth="0">載入中…</iframe>
:::

---

:::spoiler 回饋單
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSc8o6Q5o6z5Wm3uXkIPDg5ko2FbGOy_tay8IvYL8Qt9qjzYjw/viewform?embedded=true" width="640" height="640" frameborder="0" marginheight="0" marginwidth="0">載入中…</iframe>
:::