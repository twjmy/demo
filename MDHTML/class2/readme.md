---
tags: 從HTML到MarkDown
title: MarkDown 簡介與基礎語法
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

# <span style="font-size:15%">[從HTML到MarkDown/](/@NCHUIT/mdhtml)</span><span>MarkDown簡介與基礎語法</span>
> [name=VJ][time= 110,10,26]

----

:::spoiler <h2 style="display:inline">目錄</h2> {state=open}

[ToC]
+ 投影片：https://hackmd.io/@NCHUIT/mdhtml2
+ 網頁：https://hackmd.io/@NCHUIT/mdhtml
+ ::: spoiler 參考: [HackMD](https://hackmd.io/features-tw?both)
    {%hackmd features-tw %}
    :::
+ ::: spoiler 參考: [Github](https://gist.github.com/billy3321/1001749662c370887c63bb30f26c9e6e)
    {%gist billy3321/1001749662c370887c63bb30f26c9e6e %}
    :::
    
:::

---

## 環境

### HackMD: hackmd.io

### GitHub: github.io

----

## 主要用途

簡化HTML: 標題

```html
<h1>標題一</h1>
<h6>標題六</h6>
```

MarkDown

```
#標題一
######標題六
```

---

## 基礎語法

### **粗體** *斜體* ++底線++ ~~刪除線~~ ==標記文字==

```
**粗體** *斜體* ++底線++ ~~刪除線~~ ==標記文字==
```

:::spoiler 練習: ***~~我沒辦法全都要~~***
```html=!
***~~我沒辦法全都要~~***
```
:::

----

### 無序清單、有序清單、待辦事項(?)
```
- 無序清單項1
- 無序清單項2
1. 有序清單項1
2. 有序清單項2
- [x] 待辦事項1
- [ ] 待辦事項2
```
- 無序清單項甲
- 無序清單項乙
1. 有序清單項甲
2. 有序清單項乙
- [x] 待辦事項甲
- [ ] 待辦事項乙

----

### 分隔線 `<hr>`

```
<hr>
---
----
```

```
<style>
hr{display:none}
</style>
```

```
---
tags: 從HTML到MarkDown
title: MarkDown 簡介與基礎語法
description: 從HTML到MarkDown1-講義簡報-資訊社主題社課
image: 'https://i.imgur.com/1Q6Rm96.png'
slideOptions:
 loop: true
 theme: Black (default) - White - League - Sky - Beige - Simple
Serif - Blood - Night - Moon - Solarized
---
```

----

### 超連結

```html=!
[超連結](https://www.google.com "標題文字！") 
```
[超連結](https://www.google.com "標題文字！")

----

### 插入圖片

```
![](https://網址 "標題文字" =寬x高)
```

[![](https://www.kindpng.com/picc/m/254-2547396_javascript-html-css-logo-hd-png-download.png "HTML5 JS CSS3" =500x)](https://www.kindpng.com/picc/m/254-2547396_javascript-html-css-logo-hd-png-download.png "標題文字！")

:::spoiler 練習: 圖片超連結
```html=!
[![](https://www.kindpng.com/picc/m/254-2547396_javascript-html-css-logo-hd-png-download.png "HTML5 JS CSS3" =500x)](https://www.kindpng.com/picc/m/254-2547396_javascript-html-css-logo-hd-png-download.png)
```
:::

----

### 表格

```
| 欄位標題A | 欄位標題B | 欄位標題C |
| ---------:|:---------:| --------- |
|    欄位A1 |  欄位B1   | 欄位C1    |
|    欄位A2 |  欄位B2   | 欄位C2    |
```

| 欄位標題A | 欄位標題B | 欄位標題C |
| ---------:|:---------:| --------- |
|    欄位A1 |  欄位B1   | 欄位C1    |
|    欄位A2 |  欄位B2   | 欄位C2    |

----

### 引用區塊

```
> 引用區塊也可以是巢狀的喔...
>> ...可以多層次的使用...
> > > ...或是用空白隔開 
```

> 引用區塊也可以是巢狀的喔...
>> ...可以多層次的使用...
> > > ...或是用空白隔開 

----

```
> 您可以使用以下語法，表明自己的 **姓名、時間與顏色** 並與其他的引用區塊做區別
> [name=ChengHan Wu] [time=Sun, Jun 28, 2015 9:59 PM] [color=#907bf7]
> > 也支援巢狀引用區塊喔！
> > [name=ChengHan Wu] [time=Sun, Jun 28, 2015 10:00 PM] [color=red]
```

> 您可以使用以下語法，表明自己的 **姓名、時間與顏色** 並與其他的引用區塊做區別
> [name=ChengHan Wu] [time=Sun, Jun 28, 2015 9:59 PM] [color=#907bf7]
> > 也支援巢狀引用區塊喔！
> > [name=ChengHan Wu] [time=Sun, Jun 28, 2015 10:00 PM] [color=red]

----

### 程式碼

```
行內 `程式碼`
```

行內 `程式碼`

程式碼區塊

````
```javascript
var foo = function (bar) {
  return bar++;
};
console.log(foo(5));
```
````

```javascript
var foo = function (bar) {
  return bar++;
};
console.log(foo(5));
```

----

```python=
print "hello"
```

----

### 嵌入

![](https://i.imgur.com/QSh8zWB.png =200x) ![](https://i.imgur.com/zrcLTBF.png)

----

### Youtube
```
{%youtube 1G4isv_Fylg %}
```

----


警告區塊
---
:::success
耶 :tada:
:::

:::info
這是訊息 :mega:
:::

:::warning
注意 :zap:
:::

:::danger
喔不 :fire:
:::

----

:::spoiler 點選顯示更多內容
找到我了！ :stuck_out_tongue_winking_eye:
:::

:::spoiler {state="open"} 預設展開摺疊內容
找到我了！ :stuck_out_tongue_winking_eye:
:::

<details><summary>實聯制</summary>
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeSdsx_EHjL3VdxKxe3gnUWgmW9GWFWkyoEk-ywRuThMW1XBQ/viewform?embedded=true" width="640" height="640" frameborder="0" marginheight="0" marginwidth="0">載入中…</iframe>
</details>


---

:::spoiler 實聯制
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeSdsx_EHjL3VdxKxe3gnUWgmW9GWFWkyoEk-ywRuThMW1XBQ/viewform?embedded=true" width="640" height="640" frameborder="0" marginheight="0" marginwidth="0">載入中…</iframe>
:::

---

:::spoiler 回饋單
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSc8o6Q5o6z5Wm3uXkIPDg5ko2FbGOy_tay8IvYL8Qt9qjzYjw/viewform?embedded=true" width="640" height="640" frameborder="0" marginheight="0" marginwidth="0">載入中…</iframe>
:::