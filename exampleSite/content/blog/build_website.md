---                                             
# 以上為分隔線(分隔文件的前置資料與內容)

title: "【課程筆記】 Github 免費架站術 ! 輕鬆打造個人品牌"     # 文章標題
date: 2023-03-13T04:00:00+08:00                            # 文章撰寫時間(日期 T 時間 時區)
draft: false                                               # 是否為草稿

# post thumb(公告擎)
image: "images/build_website/build_website.jpg"            # 文章封面圖片路徑

# meta description(元描述)
description: "Github + Hugo 的架站流程"                     # 文章短簡介

# taxonomies(分類法)
categories:                                                # 類別
  - "Programming Language"                                 # 類別1
tags:                                                      # 標籤
  - "Markdown"                                             # 標籤1
  - "HTML"                                                 # 標籤2
  - "CSS"                                                  # 標籤3

# post type(公告類型)
type: "post"                                # 是否為精選貼文 (featured : 精選 、post : 一般)  

# 以下為分隔線(分隔文件的前置資料與內容)
---


## 壹、 學習動機

隨著年紀增長，學習的範疇也與之增廣。如何記錄所學並展示成果，是成為學習本課程的動機。

而選擇 Github 放置程式碼作品，並透過架設個人網站的方式介紹各項專題，就成為了達成此想法的首要選擇。

> 身為一個工程師，當然要用工程師的方式來展示自己啦 !!!


## 貳、 網站架設流程圖

![](/images/build_website/flow_chart.jpg)


## 叁、 作品成果

李彬華 Github 帳號 : [https://github.com/pinhua0119](https://github.com/pinhua0119)

Pin's Note 個人網站 : [https://pinhua0119.github.io/](https://pinhua0119.github.io/)

![](/images/build_website/home.png)
![](/images/build_website/about.png)
![](/images/build_website/prove.png)

Github 個人網站程式碼 : [https://github.com/pinhua0119/pinhua0119.github.io](https://github.com/pinhua0119/pinhua0119.github.io)

Github 架設網站原始程式碼 : [https://github.com/pinhua0119/build_website_sourse_code](https://github.com/pinhua0119/build_website_sourse_code)


## 肆、 課程心得

本課程在架設網站時，使用大量 HTHL 和 CSS 的程式語法，對於沒有學過前端語言的我，在剛開始著實有些困難。

但也因為本身具備其他程式語言的能力，所以也就很快上手了。

若在未來更熟悉前端語言後，相信也可以將網站做的更精緻。


## 伍、 課程筆記

### 一、 Markdown 語法

#### 1. 內文
* 直接輸入即可。
* 網頁文字換行時，程式碼需空一行。

*Ex.*

Hello World

我是阿柴

#### 2. 標題
* 文字前方加上 # 。
* 標題分為一到六級，依照 # 數量表示，級數越大字體越小。

*Ex.*
#      (#)      一級標題
##     (##)     二級標題
###    (###)    三級標題
####   (####)   四級標題
#####  (#####)  五級標題
###### (######) 六級標題

#### 3. 粗體
* 在需粗體的內文前後方各加上 ** 。

*Ex.*

我是**阿柴**，我喜歡學習。

#### 4. 斜體
* 在需斜體的內文前後方各加上 * 。

*Ex.*

我是阿柴，我喜歡*學習*。

#### 5. 有序序列
* 在需有序序列的內文前方加上數字和小數點並空一格即可 (Ex. 1. ,2. )。
* 在有序序列中，即使前方數字相同， Markdown 也會計算回正確的數字順序。
* 內縮一個有序序列，需在前方輸入四個空白鍵，若需再內縮，則需再輸入四個空白鍵，以此類推。

*Ex1.*
1. Hello World
    1. What is your name ?
        1. How are you ?
2. 我是阿柴 (在程式碼中前方數字輸入為 2. )

*Ex2.*
1. Hello World
1. 我是阿柴 (在程式碼中前方數字輸入為 1. )

#### 6. 無序序列
* 在需無序序列的內文前方加上 * 並空一格即可。
* 內縮一個無序序列，需在前方輸入四個空白鍵，若需再內縮，則需再輸入四個空白鍵，以此類推。

*Ex.*
* Hello World
    * What is your name ?
        * How are you ?
* 我是阿柴

#### 7. 引用
* 在需引用的內文前方加上 > 並空一格即可。

*Ex.*
> Hello World

#### 8. 超連結
* 外部連結 : [想要呈現的文字] (網址)
* 內部連結 : [想要呈現的文字] (/blog/檔案名稱無須副檔名) 

*Ex.*

[pinhua0119 Github](https://github.com/pinhua0119)

[【課程筆記】 Github 免費架站術 ! 輕鬆打造個人品牌](/blog/build_website)

#### 9. 圖片
* 外部連結 : ! [] (圖片網址)
* 內部連結 : ! [] (/images/gallery/檔案名稱含副檔名) 

*Ex.*

![](https://www.rover.com/blog/wp-content/uploads/2019/11/dreamstime_s_146662660.jpg)

![](/images/gallery/sakura.jpg)

#### 10. 單行程式碼
* 語法 : 小引號 + 程式碼 + 小引號
* 單行程式碼可在內文中呈現 

*Ex.*

我是阿柴，我喜歡學習。 ` print(" Hello World ") `

#### 11. 多行程式碼
* 語法 : [三個小引號(可輸入使用的程式語言)] + 需換行 + [程式碼] + 需換行 + [三個小引號]
* 多行程式碼無法在內文中呈現

*Ex.*
```python
print(" Hello World ")
print(" Hello World ")
print(" Hello World ")
```

#### 12. 表格
* 程式碼中第一列為類別，第二列虛線用於隔開類別與內容，第三列(含)以後為內容。

*Ex.*
| Name     | Gender      | Age   |
| -------- |:-----------:| -----:|
| Eric     | male        | 25    |
| Rex      | male        | 23    |
| Emily    | female      | 22    |

#### 13. 插入 YouTube 影片
* 語法 : {{</* youtube 影片序號 */>}}

*Ex.*
{{< youtube w7Ft2ymGmfc >}}

#### 14. 插入 Tweet 貼文
* 語法 : {{</* tweet user="使用者名稱" id="貼文序號" */>}}

*Ex.*
{{< tweet user="github" id="1250092060339773441" >}}


### 二、 HTML 語法

#### 1. `<div>` 、 `<a>` 、 `<img>`

* `<div>` 通常用於包裹和分組 HTML 元素，方便對它們進行樣式設定和操作。

*Ex.*
```HTML
<div>     <!-- <div> 標籤用來包裹一個標題和一段文字，將它們視為一個區塊 -->
  <h1>這是一個標題</h1>
  <p>這是一段文字。</p>
</div>
```

* `<a>` 用於創建鏈接到其他網頁或文件。

*Ex.*
```HTML
<a href="https://www.google.com">Google</a>     <!-- <a> 標籤用來創建一個指向 Google 網站的鏈接，顯示的文字是 "Google" -->
```

* `<img>` 用於向網頁添加圖像。

*Ex.*
```HTML
<img src="https://example.com/image.jpg" alt="一張圖像">     <!-- <img> 標籤用來添加一個圖像到網頁中，使用 src 屬性指定圖像的 URL ，使用 alt 屬性提供圖像的替代文字 -->
```

#### 2. `<div id="card"></div>` 和 `<div class="card"></div>` 的差異。
* `id` 屬性值必須是唯一的，也就是說頁面中不能有兩個元素使用相同的 `id` 屬性值。
* `class` 屬性用在 HTML 中元素指定一個或多個用空格分隔的類名，一個元素可以有多個類名。

*Ex.*
```HTML
 <div id="card">這是一個使用 id="card" 的元素</div>
 <div class="card">這是一個使用 class="card" 的元素</div>
```

#### 3. Bootstrap Grid 功能。
* 一個網格系統，它提供了一種方便的方式來創建響應式網格佈局，可以輕鬆地實現不同大小螢幕的網頁設計。

*Ex.*
```HTML
 <div class="col-sm-6 col-md-3">     <!-- 此例子中每列在小型螢幕上佔據 6 個列寬，在中型螢幕上佔據 3 個列寬。 -->
```


### 三、 CSS 語法

#### 1. `.card{}` 和 `#.card{}` 的差異。
* `.card{}` ： 選取所有 `class="card"` 的 HTML 元素。
* `#.card{}` ： 選取使用了 `id="card"` 的 HTML 元素。

*Ex.*
* 在下面的例子中， `.card{}` 會選取兩個 `<div>` 的元素，並為其設置背景顏色和 padding 屬性。而 `#card{}` 僅選取帶有 `id="card"` 的元素，並為其設置不同的背景顏色和 padding 屬性。
```HTML
 <div class="card">這是一個使用 class="card" 的元素</div>
 <div id="card">這是一個使用 id="card" 的元素</div>
```
```CSS
 .card {
  background-color: #F7CAC9;
  padding: 20px;
 }
 #.card {
  background-color: #A6E7FF;
  padding: 20px;
 }
```

#### 2. `.card .card-title{}` 代表的是甚麼意思 ?
* 表示一個層級關係， `.card .card-title` 表示 `.card-title` 是 `.card` 的子元素，並在 `.card` 的範圍內適用樣式。

*Ex.*
* `.card .card-title` 是 CSS 選擇器，它表示選取所有屬於 `card` 類別的祖先元素中的所有屬於 `card-title` 類別的後代元素，會選取所有具有 `card-title` 類別的元素並設置它們的字體大小和顏色。
```CSS
/* 選取具有 'card-title' 類別的元素 */
.card .card-title {
  font-size: 20px; /* 設置字體大小為20像素 */
  color: #333; /* 設置字體顏色為深灰色 */
}
```


## 陸、 參考資料

Hahow 課程 : [https://hahow.in/courses/5de8fec16117240026540b9c/main?item=5e6edc23024d690024e4086b](https://hahow.in/courses/5de8fec16117240026540b9c/main?item=5e6edc23024d690024e4086b)

Liva Hugo 主題 Demo : [https://demo.gethugothemes.com/liva](https://demo.gethugothemes.com/liva)

Liva Hugo 主題 Github : [https://github.com/gethugothemes/liva-hugo](https://github.com/gethugothemes/liva-hugo)
