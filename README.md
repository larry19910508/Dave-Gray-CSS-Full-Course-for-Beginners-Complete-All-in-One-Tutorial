成果:商店網站
![image](https://hackmd.io/_uploads/Hymk8928p.png)
![image](https://hackmd.io/_uploads/ryTJ89hLp.png)
![image](https://hackmd.io/_uploads/rJogU92Up.png)
![image](https://hackmd.io/_uploads/HyU-UqnL6.png)
![image](https://hackmd.io/_uploads/HyxzL9hU6.png)
![image](https://hackmd.io/_uploads/B1y785nUa.png)

成果:表格
![image](https://hackmd.io/_uploads/BJhNYNdLT.png)

成果:上表單
![image](https://hackmd.io/_uploads/HkHADPuU6.png)

成果:
![image](https://hackmd.io/_uploads/ryJos_dUp.png)

成果:側欄表單
![image](https://hackmd.io/_uploads/rJYIcYdI6.png)

成果:區塊
![image](https://hackmd.io/_uploads/r1nk82K8p.png)

成果:網頁布局
![image](https://hackmd.io/_uploads/SJkFK6tU6.png)

成果:標題
![image](https://hackmd.io/_uploads/ByToo0F8p.png)

成果:dark模式變色
![image](https://hackmd.io/_uploads/BkeUb7sUT.png)

成果:CSS3-動畫效果
![image](https://hackmd.io/_uploads/SJTv74jIa.png)
![image](https://hackmd.io/_uploads/BJGaO4jLp.png)

![n4R2E7O-Ngo-HD](https://hackmd.io/_uploads/BJYMDcnLp.jpg)

# Intro
1. **總時長與章節結構:** 影片總時長超過11小時，包含24個教學，這些教學相互關聯，就像書的不同章節。
   - *中文:* 影片概述，總時長超過11小時，包含24個教學，這些教學相互關聯，就像書的不同章節。

2. **教學資源與GitHub:** 影片中提到的相關連結皆可在描述中找到，並已整理到GitHub資源中。
   - *中文:* 教學資源集結，所有相關連結都集結在GitHub資源中，位於影片描述中。

3. **作者自我介紹:** 影片作者是Dave Gray，是這些CSS教學的創作者。觀眾可訂閱其YouTube頻道，追蹤Twitter，也有購買咖啡的方式支持作者。
   - *中文:* 作者介紹，影片作者是Dave Gray，提供CSS教學。觀眾可訂閱他的YouTube頻道，追蹤Twitter，也可以透過購買咖啡來支持作者。

CSS概念解釋**
1. **CSS的含義:** CSS是層疊樣式表（Cascading Style Sheets）的縮寫，是一種用於描述文件呈現風格的樣式表語言。
   - *中文:* CSS解釋，CSS是層疊樣式表（Cascading Style Sheets）的縮寫，用於描述文件的呈現風格。

**關鍵字與專業術語:**
1. **CSS教學 (CSS tutorials)**
2. **影片資源 (Video resources)**
3. **GitHub**
4. **作者 Dave Gray**
5. **YouTube頻道 (YouTube channel)**
6. **Twitter**
7. **層疊樣式表 (Cascading Style Sheets or CSS)**
# Chapter 1: Start Here
** HTML與CSS關係說明**
1. HTML與CSS的比較: HTML被視為建築物的基礎和結構，而CSS則負責外觀和裝飾，就像是油漆、地毯和壁紙。 

2. HTML和CSS之比喻: HTML是建築物的結構和基礎，而CSS則是裝飾和外觀的元素。 

3. 開始寫CSS之前的工具: 使用Chrome瀏覽器和Visual Studio Code作為整合開發環境，以建立HTML和CSS文件。 

** CSS應用方式**
1. 外部樣式表: 透過`link`元素連結外部樣式表（style.css），使CSS樣式被應用到HTML文件。 

2. 內部樣式表: 在HTML文件中使用`style`元素，將CSS樣式內嵌至文件內，影響該文件中的元素。 

3. 行內樣式: 直接在HTML元素中使用`style`屬性，即行內樣式，影響指定元素的樣式。 

** CSS規則及樣式驗證**
1. CSS規則概念: CSS規則由選擇器、屬性和屬性值構成，選擇器指定影響的元素，屬性和屬性值定義該元素的樣式。 

2. CSS規則集: 整個CSS規則被稱為規則集，或簡稱為規則，其中包含選擇器、屬性和屬性值。 

3. CSS樣式驗證: 使用W3C的CSS驗證服務，確保CSS文件符合語法規範，並避免錯誤。 

4. CSS規則與驗證比對: 對比MDN（Mozilla Developer Network）提供的CSS規則解析，加深對CSS規則的理解。 

**專業術語和關鍵字:**
HTMLHTML
CSS(CSS)
基礎(foundation)
結構(structure)
外觀(appearance)
裝飾(decoration)
建築物(building)
整合開發環境(integrated development environment)
外部樣式表 (external style sheet)
內部樣式表(internal style sheet)
行內樣式(inline style)
選擇器(selector)
屬性(property)
屬性值(property value)
規則(rule set)
W3C(W3C)
語法規範(syntax specifications)
錯誤(errors)
MDN(MDN)
規則解析(rule parsing)

# Chapter 2: Selectors

** 關於CSS選擇器的介紹**
今天我們將學習有關CSS選擇器的一切。我們將使用CSS選擇器，並且有三個最常見的層次。

** 元素選擇器的應用**
首先是元素選擇器，我們以`body`元素為例。雖然頁面上只有一個`body`元素，但這將影響所有元素，因為其他元素繼承了`body`的樣式。

** 類別選擇器的使用**
接下來是類別選擇器，例如`gray`類。這允許我們選擇一組元素並套用相同的樣式，使代碼更有組織性。

** ID選擇器的特殊性**
最後是ID選擇器，我們使用了一個名為`second`的ID。ID應該在HTML文檔中是唯一的，但通常不建議在CSS中使用ID選擇器。

** CSS的層級關係和繼承**
CSS是層層疊加的，稱為層級關係。這意味著CSS從頂部向下應用樣式，而後定義的樣式將覆蓋先前的樣式。繼承是另一個概念，子元素繼承父元素的屬性，例如字體大小。

**專業術語和關鍵字:**
1. HTML (Hypertext Markup Language)
2. CSS (Cascading Style Sheets)
3. 元素選擇器 (Element Selector)
4. 類別選擇器 (Class Selector)
5. ID選擇器 (ID Selector)
6. 層級關係 (Hierarchy)
7. 繼承 (Inheritance)
8. 樣式 (Style)
9. 選擇器特殊性 (Selector Specificity)
10. 重要性標誌 (`!important`)
11. 疊加 (Cascading)
12. 組織性代碼 (Organized Code)

![image](https://hackmd.io/_uploads/H1YCwxDLa.png)
![image](https://hackmd.io/_uploads/rycR9gvLp.png)



# Chapter 3: Colors
** CSS顏色的介紹**
我們正在學習有關CSS顏色的知識。在Visual Studio Code的左側，我們有代碼編輯器，右側是我們的網頁。這是一個基本的網頁，使用Live Server擴展，當我們在CSS中進行更改並保存時，我們將立即在網頁中看到變化。頁面包括一個h1標題和三個文章，每個文章都有自己的h2標題和段落。

** 設置背景顏色**
讓我們首先了解如何設置背景顏色。使用“background-color”屬性，Visual Studio Code會立即顯示顏色名稱列表，有140種HTML顏色名稱。我們可以選擇顏色名稱，例如“blue”或使用十六進制碼。背景顏色的選擇應考慮對比度和可讀性。

** 文字顏色的設置**
接下來，我們學習如何設置文字顏色，使用“color”屬性。我們可以選擇顏色名稱，例如“black”或使用RGB或十六進制碼。選擇適合的文字顏色以確保與背景對比度足夠並提高可讀性。

** 其他設置方式**
除了使用“background-color”和“color”，我們還可以使用簡寫形式的“background”來同時設置多個屬性。此外，我們學到了RGB和RGBA的使用，以及十六進制碼的表示方式，其中十六進制具有更簡潔的總結形式。

** 顏色選擇的工具**
我們介紹了Visual Studio Code的內置顏色選擇器，但還有一些在線工具，如coolers.co和WebAIM對比度檢查器。這些工具可以幫助我們選擇配色方案，並確保網頁顏色符合可讀性和無障礙性標準。

**關鍵字和專業術語:**
1. 層疊樣式表 (CSS - Cascading Style Sheets)
2. Visual Studio Code
3. Live Server
4. 標題元素 (h1, h2)
5. 背景顏色屬性 ("background-color")
6. 文字顏色屬性 ("color")
7. 紅綠藍色彩模式 (RGB - Red, Green, Blue)
8. RGBA色彩模式 (RGBA - Red, Green, Blue, Alpha)
9. 十六進制碼 (Hexadecimal)
10. 對比度 (Contrast)
11. coolers.co (調色板生成器)
12. WebAIM (Web Accessibility In Mind)
13. 可讀性 (Readability)
14. 無障礙性 (Accessibility)

# Chapter 4: Units & Sizes

1. **介紹CSS單位及VS Code與Chrome的使用環境：**
   在這個教學中，使用了Visual Studio Code（VS Code）和Chrome瀏覽器，通過實際演示來介紹CSS的常見單位。頁面包含一個H1標題和一個段落，使用Live Server擴充套件實時顯示CSS變更。

2. **絕對長度單位 - 像素（px）：**
   教學開始介紹絕對長度單位，其中像素是最常見的。像素用於設置元素的固定大小，但在字體大小方面使用像素可能不是最佳選擇，特別是考慮到用戶設置的情況。

3. **相對單位 - rem（root em）：**
   接著介紹相對單位“rem”，它相對於根元素字體大小。這是安全的相對單位，因為總是參考根元素，通常是瀏覽器預設的字體大小。

4. **相對單位 - em：**
   比較了“em”和“rem”兩種相對單位。強調了“rem”對於確保相對性的安全性，而“em”相對於元素自身字體大小，可能導致意外的字體放大。

5. **相對單位 - ch（character width）：**
   介紹了“ch”相對單位，它用於測量元素字體中字符0的寬度，常用於確定一行中可以容納多少個字符。

6. **CSS重置及DevTools使用：**
   討論了使用CSS重置來清除預設樣式，以更好地理解和應用CSS單位。同時，演示了DevTools的使用，查看瀏覽器默認樣式和進行元素檢查。

7. **相對單位 - vw（視口寬度）和vh（視口高度）：**
   最後介紹了“vw”和“vh”這兩種相對單位，分別表示視口寬度和視口高度。示範了如何使用這兩種單位，並提到使用“100vw”可能導致水平滾動條的問題，建議使用“min-height: 100vh”來確保body高度不低於視口高度。

**關鍵字和專業術語：**

1. CSS單位 - CSS units
2. 像素 - Pixels (px)
3. 相對單位 - Relative units
4. rem（根em） - rem (root em)
5. em - em
6. ch（字符寬度） - ch (character width)
7. CSS重置 - CSS reset
8. DevTools - DevTools
9. 視口寬度 - Viewport width (vw)
10. 視口高度 - Viewport height (vh)
11. Live Server擴充套件 - Live Server extension
12. Visual Studio Code（VS Code） - Visual Studio Code (VS Code)

# Chapter 5: Box Model

1. 在這個教學中，我們先回顧了之前的代碼，並利用Live Server擴充套件實時顯示CSS變更。這讓我們能夠立即在網頁中看到CSS變更的效果。

2. 接下來，我們深入了解CSS盒模型。CSS中的一切都被視為盒子，而盒模型由內到外分為內容（content）、內邊距（padding）、邊框（border）和外邊距（margin）。

3. 我們使用DevTools工具來視覺化查看盒模型。通過選擇元素，我們可以清楚地看到內容、內邊距、邊框和外邊距的各個區塊。

4. 透過CSS reset，我們可以重置瀏覽器默認樣式，並將所有元素的邊距和內邊距設置為零，以便更好地控制樣式。

5. 我們深入研究了CSS邊框屬性，包括邊框寬度、樣式和顏色。同時，我們使用了簡寫形式和個別設置邊框的各個屬性。

6. 接著，我們介紹了`outline`屬性，它與`border`不同，不佔據空間，但可以用來提供額外的輔助樣式。

7. 最後，我們實際演示了如何將一個方形盒子轉換為圓形。通過設置`border-radius`為寬度和高度的一半，我們成功地創建了一個圓形。

**關鍵字和專業術語：**

1. CSS盒模型 (CSS Box Model)
2. Live Server擴充套件 (Live Server extension)
3. DevTools工具 (DevTools)
4. 內容、內邊距、邊框、外邊距 (Content, Padding, Border, Margin)
5. CSS reset (CSS重置)
6. 邊框屬性：寬度、樣式、顏色 (Border properties: Width, Style, Color)
7. 簡寫形式 (Shorthand)
8. `outline`屬性 (Outline property)
9. `border-radius` (邊框半徑)
![image](https://hackmd.io/_uploads/ryu_eBP8T.png)

# Chapter 6: Typography
1. **文本和字型基本設定：**
   - 透過CSS，文本排列和呈現的方式可以進行調整。
   - `body` 元素被選取，設定了`padding`為25%。同時，使用`rem`單位設定了`font-size`，參照瀏覽器的預設字型大小。

2. **文字颜色設定：**
   - 透過 `color` 属性，文字的颜色可以被設定。在這個例子中，文字顏色設定為紫色，後來被移除。

3. **文本修飾設定：**
   - 透過 `text-decoration` 属性，可以控制文本的修飾效果，包括 `underline`、`overline` 和 `line-through`，也可以使用 `none` 移除修飾。

4. **文字轉換：**
   - 使用 `text-transform` 属性，可以控制文字的轉換效果，包括 `capitalize`、`lowercase` 和 `uppercase`。

5. **文字對齊：**
   - 使用 `text-align` 属性，可以控制文字在元素中的對齊方式，包括 `left`、`right` 和 `justify`。

6. **首行縮進：**
   - 透過 `text-indent` 属性，可以對首行進行縮進，使用 `em` 單位。

7. **行高和字距：**
   - 使用 `line-height` 属性，調整了行高。
   - 使用 `letter-spacing` 和 `word-spacing` 属性，分別控制字母和單詞之間的距離。

8. **字體粗細和風格：**
   - 使用 `font-weight` 属性，控制字體的粗細，可以設定數值或使用詞語如 `bold` 和 `lighter`。
   - 使用 `font-style` 属性，控制字體的風格，包括 `italic` 和 `oblique`。

9. **字體系列：**
   - 使用 `font-family` 属性，指定字體系列，可以使用瀏覽器默認的通用字體系列，也可以使用外部字體，如Google Fonts提供的 `Roboto`。

10. **引入Google Fonts：**
    - 透過在HTML的`head`中引入Google Fonts的 `link` 或在CSS中使用 `@import`，可以導入外部字體。在此例中，使用了Roboto字體。

11. **簡單的HTML結構：**
    - HTML 包含一個 `body`，裡面有一個 `header` 和一個 `main` 元素，包含了標題、段落，以及一個簡單的表單。

**關鍵字：**
1. **排版 (Typography):** 文字的排列和呈現方式。
2. **CSS (層疊樣式表):** 一種樣式表語言，用於描述HTML或XML文檔的外觀和格式。
3. **字體大小 (Font Size):** 字體的大小，使用 `rem` 單位參照瀏覽器的預設字體大小。
4. **字體系列 (Font Family):** 一組相似風格的字體，可以使用通用字體系列或外部字體，如Google Fonts。
5. **行高 (Line Height):** 行與行之間的距離。
6. **字母間距 (Letter Spacing):** 字母之間的距離。
7. **單詞間距 (Word Spacing):** 單詞之間的距離。
8. **文本修飾 (Text Decoration):** 文本的裝飾效果，如 `underline`、`overline` 和 `line-through`。
9. **文字轉換 (Text Transform):** 改變文字的轉換效果，如 `capitalize`、`lowercase` 和 `uppercase`。
10. **文本對齊 (Text Align):** 控制文本在元素中的對齊方式，如 `left`、`right` 和 `justify`。

**專業術語：**
1.**相對單位 Rem：** 根據瀏覽器根元素的字體大小，是一種相對單位。

2.**谷歌字體 Google Fonts：** 由Google提供的免費字體服務，可透過網頁引入外部字體。

3.**網頁安全字體 Web Safe Fonts：** 通用字體系列，通常不需從外部源安裝，以確保在不同平台上的一致性。

4.**無襯線字體 Sans Serif：** 字體風格中沒有襯線的特徵，常見於網頁和數位媒體。

5.**襯線字體 Serif：** 字體風格中帶有襯線的特徵，常見於印刷和書籍排版。

6.**導入 Import：** 在CSS中使用的 @import 語句，用於導入外部文件，如字體。

7.**斜體 Italic：** 字體風格的一種，使文字呈現為傾斜形狀。

8.**斜體強化 Oblique：** 比 italic 更強烈的字體傾斜效果。

9.**字體堆疊 Font Stack：** 在CSS中，定義一系列字體，以確保即使某些字體不可用，也有替代的選擇。

10.**行縮進 Line Indentation：** 使用 text-indent 調整首行縮進的效果。

11.**刪除線 Line Through：** 透過 text-decoration 設定，將線穿過文字。

12.**單詞間距 Word Spacing：** 使用 word-spacing 調整單詞之間的距離。

13.**字母間距 Letter Spacing：** 使用 letter-spacing 調整字母之間的距離。
成果:
![image](https://hackmd.io/_uploads/ByKt9BPLa.png)

# Chapter 7: Styling Links

1. Visual Studio Code 開啟，擁有基本樣式，包括填充、字體大小、字體家族和字體堆疊。
2. 引入 Google Fonts，提供字體服務，並有文件樹中的 index.html 和其他基本 HTML 文件。

3. 風格調整，包括文本裝飾、遊標設置、顏色設定和標題/焦點/活動等擴展的樣式。
4. 超連結的默認風格：下劃線、未訪問為藍色、訪問後為紫色。
5. 超連結擁有不同的狀態：未訪問、懸停、訪問、活動、焦點。
6. 介紹了擴展的樣式，如懸停、訪問、焦點的偽類，以及遊標的語義值。

**關鍵字和專業術語**

1. **偽類 (Pseudo-class):** CSS 中用於選擇元素的特殊狀態的選擇器，如 `:hover`、`:visited`、`:active`。
2. **遊標 (Cursor):** 指標在網頁上的圖標，可用於指示與超連結、按鈕等互動元素的交互。
3. **文本裝飾 (Text Decoration):** CSS 屬性，用於控制文本的裝飾效果，如下劃線、刪除線等。
4. **偽元素 (Pseudo-element):** CSS 中用於選擇元素的特殊部分或位置的選擇器，如 `::before`、`::after`。
5. **字體堆疊 (Font Stack):** 在 CSS 中定義一系列字體，以確保即使某些字體不可用，也有替代的選擇。
6. **透明度 (Opacity):** 顏色或元素的透明度，可以使用 CSS 的 `opacity` 屬性或 RGBA、HSLA 顏色表示。
7. **焦點 (Focus):** 表示當前焦點元素的狀態，通常用於提高網頁的可訪問性。
8. **懸停 (Hover):** 表示滑鼠懸停在元素上的狀態，常用於改變元素的外觀，如超連結的顏色。
9. **訪問 (Visited):** 表示已訪問過的超連結的狀態，常用於區別已經查看過的頁面。
10. **活動 (Active):** 表示當前正在進行交互的元素的狀態，例如按下鼠標左鍵時的狀態。


# Chapter 8: List Styles
1. **HTML結構和基本CSS設置：**
   - HTML中包含一個頁首標籤（h1）、主區塊（main）和兩個文章元素（article）。第一個文章元素包含一個有序列表（ordered list），第二個文章元素包含一個無序列表（unordered list）。
   - 初始CSS樣式包括引入Google Fonts中的Roboto字體，以及對主體（body）添加一些基本樣式，例如內邊距和字體大小設置為2rem。

2. **有序列表（Ordered List）的樣式設定：**
   - 使用`list-style-type`屬性，可以指定有序列表的樣式，例如使用小寫字母、羅馬數字等。
   - 可以使用`start`屬性指定有序列表的起始值，也可以使用`reversed`屬性反向計數。
   - 使用`list-style-position`屬性控制列表標記的位置，預設為`outside`，但有些瀏覽器可能預設為`inside`。

3. **無序列表（Unordered List）的樣式設定：**
   - 類似有序列表，使用`list-style-type`屬性可以指定無序列表的樣式，如方形、圓形等。
   - 使用`list-style-position`屬性控制列表標記的位置，特別是在進行文本居中對齊時可能需要調整。

4. **`list-style-image`和Shorthand樣式：**
   - 使用`list-style-image`屬性可以為列表標記指定圖片，同時可以使用Shorthand方式同時設定多個列表樣式屬性。

5. **複寫和嵌套列表樣式：**
   - 可以使用CSS複寫已經定義的樣式，並使用`nth-child`擬類選擇器來單獨樣式化特定的列表項目。
   - Pseudo element

6. **Pseudo Element: Marker（標記）：**
   - 引入了擬元素（pseudo element）`::marker`，用於控制列表項目標記的樣式。
   - 可以設定標記的顏色、字體、大小等屬性，也可以透過`content`屬性添加額外的內容。

7. **使用`value`屬性指定有序列表的起始值：**
   - 可以使用HTML的`value`屬性為有序列表指定起始值，這對於特定場景可能有用。

這段代碼中還提及了一些進階樣式設置，如更改字體、調整大小、添加內容等。其中，`::marker`擬元素的使用相對較新，用於調整列表標記的樣式和內容。

# Chapter 9: Mini Project

### HTML 結構：
- `index.html` 包含了一個 `<header>`、`<main>` 元素，`<main>` 中有兩個 `<article>`，分別包含有序列表和無序列表。
- 有序列表使用 `<ol>`，無序列表使用 `<ul>`，分別具有 `<h2>` 標題。

### CSS 起始碼：
- 引入了 Google Fonts 中的 Roboto 字體，並在 `<body>` 中設定了字體大小和一些內邊距。
- 使用 Live Server 擴充套件，可即時在瀏覽器中查看對CSS的更改。

### 有序列表（Ordered List）樣式：
- `list-style-type` 屬性可設定列表樣式，包括數字、字母、羅馬數字等。
- 可透過 `start` 屬性指定起始數字，以及 `reversed` 屬性實現倒序顯示。

### 無序列表（Unordered List）樣式：
- 仍使用 `list-style-type` 屬性，可選擇不同的符號，如圓點、方塊等。
- `list-style-position` 屬性用於控制標記位置，預設為 `outside`。

### `nth-child` 與樣式覆寫：
- 使用 `nth-child` 可選擇指定位置的列表項目，如奇數、偶數，進行樣式設定。
- 透過選擇器覆寫，可以針對特定列表項目進行樣式修改。

### 擴充列表標記（Marker）：
- 引入 `::marker` 擴充標記，可自定義標記的樣式、內容、大小等。
- 透過 `content` 屬性，可以在標記中插入文本或其他內容，也能使用SVG等格式。

### `value` 屬性：
- 可以在 `<ol>` 中使用 `value` 屬性，指定起始數字，不受列表項目內容的影響。

### 其他補充：
- 可以使用 `font-awesome` 或 SVG 圖像來代替標記，提升設計的多樣性。
- 演示了使用 Live Server 擴充套件，使CSS更改即時反映在瀏覽器中。
- 介紹了 `list-style` 的簡寫方式，同時設定多個列表樣式相關屬性。

**關鍵字與專業術語：**
- 有序列表（Ordered List） 
- 無序列表（Unordered List） 
- `list-style-type` 屬性 `list-style-type` Property
- `list-style-position` 屬性  `list-style-position` Property
- `nth-child` 擬似類別  `nth-child` Pseudo-class
- `::marker` 擬似元素  `::marker` Pseudo-element
- `value` 屬性  `value` Attribute
- SVG 圖像  SVG Image
- `font-awesome` 圖標庫  Font Awesome Icon Library
- Live Server 擴充套件  Live Server Extension

成果:
![image](https://hackmd.io/_uploads/BJhNYNdLT.png)

# Chapter 10: Display
這個專案是一個針對初學者的小型 CSS 練習項目，透過在 Visual Studio Code 中開啟一個包含 HTML 和 CSS 的起始文件，展示了如何應用之前學到的 CSS 技術。以下是一些詳細的整理：

1. **HTML 結構：**
   - HTML 文件包含了一個 `<nav>` 元素，裡面包含一個 `<h2>` 標題和一個無序列表 (`<ul>`)，列表內有幾個 `<li>` 項目，每個項目包含一個錨點連結 (`<a>`)。同時，文件底部有一個段落含有一個不在列表中的連結。

2. **CSS Reset：**
   - 使用了一個小型的 CSS 重置，將一些默認樣式歸零，確保開始時的一致性。具體設置了 `margin: 0;`、`padding: 0;`、`box-sizing: border-box;`。

3. **Body 樣式：**
   - 對 `<body>` 標籤應用了一些樣式，包括一個 `margin-top` 以及設定字體。

4. **Nav 樣式：**
   - 對 `<nav>` 標籤添加邊框、邊框半徑、最大寬度，使其居中顯示。

5. **H2 標題樣式：**
   - 對 `<h2>` 標題應用了填充和背景顏色，同時修正了邊框半徑以匹配 `<nav>` 的外觀。

6. **無序列表樣式：**
   - 通過設置 `list-style-type: none;`，隱藏了無序列表的默認符號。
   - 對每個 `<li>` 項目設置了上邊框，以提供視覺分隔。

7. **錨點樣式：**
   - 使用了不同的擬似類別，包括 `:link`、`:visited`、`:hover`、`:focus`，設定了文字修飾和顏色。

8. **Display 屬性：**
   - 引入了 `display: block;` 屬性，將錨點 (`<a>`) 轉換為區塊元素，使其擁有 100% 寬度。

9. **最後一個列表項目樣式：**
   - 使用 `:last-child` 擬似類別選擇器，選擇最後一個列表項目，設置了邊框半徑，以使其與其他項目區分。

**關鍵字：**
1. CSS（Cascading Style Sheets）
2. Visual Studio Code
3. HTML（Hypertext Markup Language）
4. 無序列表（Unordered List）
5. 邊框（Border）
6. 邊框半徑（Border Radius）
7. 擬似類別（Pseudo-classes）
8. Display 屬性（Display Property）
9. 塊級元素（Block-level Elements）
10. 重置（Reset）
11. Roboto 字體（Roboto Font）
12. Live Server 擴充套件（Live Server Extension）
13. 鏈接（Links）
14. 列表項目（List Items）
15. 框模型（Box Model）

**專業術語：**
1. **CSS 重置（CSS Reset）：** 用於覆蓋不同瀏覽器的默認樣式，確保一致性開始的 CSS 重置技術。

2. **框模型（Box Model）：** 指 HTML 元素的佈局模型，由內容、內邊距、邊框和外邊距組成。

3. **擬似類別（Pseudo-classes）：** CSS 選擇器，允許根據元素的狀態或位置選擇元素，例如 `:hover`、`:focus`、`:last-child`。

4. **Display 屬性（Display Property）：** CSS 屬性，用於指定元素應該生成的框的類型，例如 `block`、`inline`。

5. **塊級元素：** 生成一個框，獨立占據一行，可以包含內聯和其他塊級元素。

6. **字體排印：** 對文本進行排印的過程，包括字體大小、行高、字形等。

7. **Live Server：** Visual Studio Code 的擴充套件，提供即時預覽和自動刷新功能。

8. **Roboto 字體：** 一種由 Google 設計的開源無襯線字體。

9. **邊框半徑：** 指定框的邊角半徑，使其呈現圓角效果。

10. **擬似元素：** CSS 中的虛構元素，如 `::before` 和 `::after`，用於在元素的內容前後插入生成的內容。
    
成果:
![image](https://hackmd.io/_uploads/HkHADPuU6.png)

<br>
# Chapter 11: Floats

## 簡介
CSS Columns（CSS 列）是一種用於創建多欄佈局的技術，讓網頁內容能夠以多欄的形式呈現，而不僅僅是傳統的單欄式呈現。這提供了更靈活的網頁設計選項，特別適用於大量文本內容的情境。

## 關鍵概念

### 1. `column-count` 屬性
- **定義列數**：設定一個元素中顯示的列數，決定內容被分佈到多少列中。

### 2. `column-width` 屬性
- **定義列寬**：設定每一列的寬度，確保列的寬度是固定的，而不是自動適應容器。

### 3. `column-gap` 屬性
- **定義列間距**：設定列之間的間距，控制不同列之間的間隙大小。

### 4. `column-rule` 屬性
- **定義列規則**：設定在列之間繪製的垂直線，可以指定線的寬度、顏色和樣式。

### 5. `column-span` 屬性
- **合併列**：允許某些元素橫跨多列，使其跨足多個列。

## 詳細分析

### 1. 基本的多欄佈局
- 使用 `column-count` 和 `column-width` 可以指定基本的多欄佈局，例如設定 `column-count: 2;` 可以使內容分為兩列。

### 2. 控制列之間的間距
- 使用 `column-gap` 能夠控制不同列之間的間距，確保版面整齊，提升可讀性。

### 3. 垂直線與列規則
- 透過 `column-rule` 屬性，可以在不同列之間添加垂直線，進一步區分各列，使版面更具視覺層次。

### 4. 跨列顯示
- 使用 `column-span` 屬性，可以讓特定元素橫跨多列，提供更靈活的版面呈現方式。

### 5. 響應式佈局
- 利用媒體查詢（Media Queries）結合 CSS Columns，實現在不同螢幕尺寸下的自適應多欄佈局。

## 關鍵字

1. **`column-count`** - 列數屬性
2. **`column-width`** - 列寬屬性
3. **`column-gap`** - 列間距屬性
4. **`column-rule`** - 列規則屬性
5. **`column-span`** - 合併列屬性
6. **多欄佈局** - 使用 CSS Columns 創建的多欄式網頁版面
7. **媒體查詢** - 在不同螢幕尺寸下調整網頁樣式的技術
8. **響應式設計** - 以應對不同螢幕大小和設備的方式調整設計的方法

## 專業術語

1. **Multi-column Layout** - 多欄佈局技術
2. **Columnar Design** - 列式設計
3. **Responsive Layout** - 響應式佈局
4. **Media Queries** - 媒體查詢技術
5. **Column Spanning** - 列合併，讓元素跨足多列
6. **Vertical Line** - 垂直線，指 `column-rule` 中在列之間繪製的線
7. **Viewport Width Unit** - 視口寬度單位，以視口寬度為基準的相
# Chapter 12: Columns
這段程式教學主要在介紹如何在網頁中使用CSS的`column`屬性來實現文字的分欄效果。以下是詳細的重點整理：

1. **建立HTML頁面：**
   - 在HTML中，建立了一個基本的頁面結構，包括引入Google Fonts的Roboto字型。
   - 使用Emmet縮寫生成了五個包含Lorem Ipsum文本的段落。
   - 創建一個`<section>`元素作為前四個段落的容器，並為其添加`.columns`的類別。
   - 在其中一個段落外添加了一個單獨的段落。

2. **CSS樣式：**
   - 在CSS中，定義了`.columns`類別，設置了`column-count`屬性，將文本分為四列。
   - 使用`column-width`屬性設置每列的最小寬度為250像素。
   - 使用`column-rule`屬性設置列之間的分隔線樣式。
   - 使用`column-gap`屬性設置列之間的間距。
   - 使用簡潔的`columns`屬性同時設置`column-count`和`column-width`。
   - 添加`no-wrap`類別，使用`white-space: nowrap`屬性，防止特定元素內文本斷行。

3. **引入特殊符號：**
   - 使用HTML Unicode字符代碼引入特殊字符，如左右引號和長破折號（em dash）。

4. **引入其他樣式：**
   - 設置`margin-top`為零，以解決段落間的頂部間距問題。
   - 將`break-inside`屬性設置為`avoid`，以防止元素在分欄時被分割。
   - 使用`column-span: all`將元素跨足所有列。

5. **解決特定性問題：**
   - 注意到對`p`元素的`margin-top`設置不起作用，解決方法是使用`.columns p`的特定性更高。
   - 使用`.columns .quote`以確保樣式適用於指定的元素。

6. **調整段落間距：**
   - 理解CSS的「margin collapsing」概念，並解決第一個段落頂部間距的問題。

7. **避免文字斷行：**
   - 使用`white-space: nowrap`防止特定元素內文本的斷行。

8. **其他考慮：**
   - 注意`break-before: column`可能導致在單列模式下元素縮小的問題，最好謹慎使用。
   - 使用`break-inside: avoid`和`break-before: column`在特定情況下避免元素分割。

9. **Unicode字符：**
   - 左引號：`&#8220;` 或 `&ldquo;`
   - 右引號：`&#8221;` 或 `&rdquo;`
   - 長破折號：`&#8212;` 或 `&mdash;`

這個教學以實際案例演示了如何使用CSS的`column`屬性創建分欄效果，同時解釋了一些與特定性、斷行、間距和Unicode字符相關的概念。

* 關鍵字和專業術語
1. **CSS屬性與值：**
   - `column-count`
   - `column-width`
   - `column-rule`
   - `column-gap`
   - `column-span`
   - `white-space`
   - `break-inside`
   - `break-before`

2. **HTML元素與屬性：**
   - `<section>`
   - `class` 屬性
   - `<p>` 元素
   - `&nbsp;` (non-breaking space)

3. **Unicode字符和HTML實體：**
   - 左引號：`&ldquo;` 或 `&#8220;`
   - 右引號：`&rdquo;` 或 `&#8221;`
   - 長破折號：`&mdash;` 或 `&#8212;`

4. **特定性：**
   - 樣式特定性
   - `.class` 選擇器
   - `element` 選擇器
   - 複合選擇器

5. **CSS Box Model：**
   - `margin-top`
   - `padding`
   - `text-align`

6. **Responsive Web Design：**
   - 響應式網頁設計
   - 頁面斷點

7. **其他術語：**
   - Emmet縮寫
   - Lorem Ipsum
   - Margin Collapsing

8. **開發工具：**
   - Visual Studio Code
   - DevTools

9. **其他注意事項：**
   - CSS Reset
   - Shorthand 語法
   - Web Page Resizing

10. **CSS Flexbox 和 Grid（提及未來教學內容）：**
    - Flexbox 布局
    - Grid 布局
成果:
![image](https://hackmd.io/_uploads/ryJos_dUp.png)

# Chapter 13: Position
這段教學內容主要涵蓋了CSS中的`position`屬性，以及其各種值（`static`、`absolute`、`relative`、`fixed`、`sticky`）的應用。以下是重點整理、補充、以及提取的關鍵字和專業術語：

### 重點整理：

1. **`position`屬性：**
   - `static`：預設值，元素在正常文檔流中。
   - `absolute`：相對於最近的已定位（非`static`）祖先元素，若無則相對於視窗。
   - `relative`：相對於元素在正常文檔流中的位置。
   - `fixed`：相對於視窗，並且不隨捲動而移動。
   - `sticky`：相對於最近的包含塊和視窗的交叉點。

2. **使用`position`實例：**
   - `position: absolute;`：結合`top`、`left`等屬性移動元素的位置。
   - `position: relative;`：相對於自身位置進行移動。
   - `position: fixed;`：固定在視窗中，不隨捲動而移動。
   - `position: sticky;`：在特定條件下固定，通常用於頁面導航。

3. **`z-index`屬性：**
   - 控制元素的堆疊順序，數字越大越在上層。

4. **`scroll-behavior`屬性：**
   - `scroll-behavior: smooth;`：啟用平滑捲動效果。

### 補充：

1. **視窗與元素的關係：**
   - `static`元素參考整個視窗。
   - `absolute`、`fixed`元素參考最近的已定位祖先，若無則參考視窗。
   - `relative`元素相對於自身位置。
   - `sticky`元素在正常文檔流中表現為`relative`，但在滾動超過特定點後變為`fixed`。

2. **適用場景：**
   - `position: absolute;` 可用於創建浮動元素。
   - `position: fixed;` 常用於製作頁面導覽欄。
   - `position: sticky;` 適用於需要在滾動時保持可視性的元素。

### 提取關鍵字和專業術語：

1. **關鍵字：**
   - 定位（Positioning）
   - 正常文檔流（Normal Flow）
   - 堆疊順序（Stacking Order）
   - 平滑捲動（Smooth Scrolling）
   - `z-index`
   - `scroll-behavior`
   - 包含塊（Containing Block）

2. **專業術語：**
   - 堆疊上下文（Stacking Context）
   - 定位上下文（Positioning Context）
   - 捲動條（Scrollbar）
成果:
![image](https://hackmd.io/_uploads/rJYIcYdI6.png)

# Chapter 14: Flexbox
**CSS Flexbox 基礎知識：重要概念和屬性**

### HTML 結構
- 包含六個帶有 "class='box'" 的 div 元素，每個都有獨特的編號（1-6）。
- 主容器（container）包含這六個 div，形成垂直堆疊的區塊元素。

### CSS 重置和樣式
- 使用 Google Fonts 的 Roboto 字體。
- 對 body 進行 CSS 重置，實現統一樣式。
- 容器樣式：最大寬度、最小高度、邊距和邊框。
- 盒子樣式：最小寬度、最小高度、背景顏色、文本顏色、字體大小和內邊距。

### Flex 容器
1. 將 `display: flex;` 應用於容器。
2. 將 div 排列方式從垂直改為水平。

### Justify Content 屬性
- 調整 flex 子項的水平對齊。
- 值：`flex-start`、`flex-end`、`center`、`space-around`、`space-between`、`space-evenly`。

### Align Items 屬性
- 調整 flex 子項的垂直對齊。
- 值：`flex-start`、`flex-end`、`center`。

### Flex Direction 屬性
- 定義主軸的方向。
- 值：`row`（默認）、`column`、`row-reverse`、`column-reverse`。

### Flex Wrap 屬性
- 控制 flex 子項是否應該換行為多行。
- 值：`nowrap`（默認）、`wrap`、`wrap-reverse`。

### Align Content 屬性
- 在存在多行時（與 `flex-wrap` 一起使用）對行進行對齊。
- 值：與 `justify-content` 相似的值。

### 個別 Flex 子項
1. **Flex Basis（基礎大小）**
   - 設置 flex 子項的初始大小。
   - 可以是絕對值或百分比。

2. **Flex Grow（增長因子）**
   - 控制 flex 子項的增長能力。
   - 較高的值表示更多的增長。

3. **Flex Shrink（收縮因子）**
   - 控制 flex 子項的收縮能力。
   - 較高的值表示更多的收縮。

4. **Order（順序）**
   - 指定 flex 子項的順序。
   - 默認順序為 0。

### Flex 屬性的簡寫
- 使用 `flex` 簡寫：`flex-grow`、`flex-shrink`、`flex-basis`。
- 示例：`flex: 2 2 40%;`。

### Order 屬性
- 控制 flex 子項的順序。
- 值：整數（正、負或零）。

### 練習和資源
- 推薦互動學習：[Flexbox Froggy](https://flexboxfroggy.com/)。
- 強化 Flexbox 概念的挑戰。

### 關鍵詞
1. **彈性盒模型（Flexbox）**
2. **主軸對齊（Justify Content）**
3. **交叉軸對齊（Align Items）**
4. **彈性盒方向（Flex Direction）**
5. **彈性盒換行（Flex Wrap）**
6. **行對齊（Align Content）**
7. **基礎大小（Flex Basis）**
8. **增長因子（Flex Grow）**
9. **收縮因子（Flex Shrink）**
10. **順序屬性（Order Property）**
成果:
![image](https://hackmd.io/_uploads/r1nk82K8p.png)


# Chapter 15: Grid Layout
這段程式碼是一個CSS Grid Layout的教學，主要介紹了使用CSS Grid的基本概念和屬性。以下是這段程式碼的詳細重點：

1. **Grid Container設定：**
   - `display: grid;`：將主要容器（main element）設為grid布局。
   - `grid-auto-flow: row;` or `grid-auto-flow: column;`：自動配置子元素的排列方式，可選擇行或列。
   - `grid-template-columns`：定義列的寬度，可以使用固定值（如px）或分數（fraction units）。
   - `grid-template-rows`：定義行的高度，同樣可以使用固定值或minmax函數。

2. **Grid Items的設定：**
   - 使用`grid-column-start`、`grid-column-end`、`grid-row-start`、`grid-row-end`來指定子元素在grid中的位置。
   - 使用`repeat()`簡化定義重複的列或行。
   - `grid-gap`：設定列和行之間的間距（gutter）。
   - `row-gap`和`column-gap`：分別設定行和列之間的間距。

3. **Grid Line的解釋：**
   - 利用`grid-column-start`和`grid-column-end`，以及`grid-row-start`和`grid-row-end`來指定網格線的起始和結束位置。
   - Grid的網格線是從1開始的，可使用分數或固定值。

4. **命名Grid Areas：**
   - 使用`grid-template-areas`為每個區域命名，並在子元素中使用`grid-area`指定區域名稱。
   - 可以使用命名區域更容易理解和維護複雜的頁面佈局。

5. **Nested Grids：**
   - 在Grid內部可以嵌套另一個Grid，形成層次化的布局結構。
   - 可以使用`place-content`和`place-items`簡化對齊和佈局內部Grid中的內容。

6. **遊戲推薦：**
   - 提到了一個CSS Grid的學習遊戲，[Grid Garden](https://cssgridgarden.com/)，這是一個互動式學習工具，可以通過遊戲挑戰來熟悉CSS Grid。
**關鍵字和專業術語：**

1. **CSS 網格布局（CSS Grid Layout）：**
   - 一種用於設計和控制網頁元素二維布局的CSS布局方式。

2. **網格容器（Grid Container）：**
   - CSS Grid布局中的主要元素，可以透過 `display: grid;` 進行定義。

3. **網格項目（Grid Item）：**
   - 網格容器中的子元素，受到網格布局的影響。

4. **網格線（Grid Line）：**
   - 在CSS Grid中形成的水平和垂直線，用於定義網格布局的行和列。

5. **網格間距（Grid Gap）：**
   - 定義網格行和網格列之間的間隙，可以使用 `grid-gap`、`row-gap` 和 `column-gap`。

6. **網格模板列（Grid Template Columns）：**
   - 用於定義網格容器中的列寬度的屬性。

7. **網格模板行（Grid Template Rows）：**
   - 用於定義網格容器中的行高度的屬性。

8. **網格區域（Grid Area）：**
   - 用於定義網格中一個區域的名稱，可用於命名區域布局。

9. **網格自動流（Grid Auto Flow）：**
   - 指定在網格容器中如何自動分配網格項目的排列方式，可以是row或column。

10. **分數單位（Fraction Units）：**
    - 在CSS Grid中使用的一種特殊單位，用來表示相對於可用空間的佔比。

11. **定位內容（Place Content）：**
    - 一種簡化屬性，同時設置 `align-content` 和 `justify-content`，用於定位網格內容的位置。

12. **嵌套網格（Nested Grids）：**
    - 在網格容器中嵌套另一個網格容器，形成層次化的網格布局。

13. **網格花園（Grid Garden）：**
    - 一個教學遊戲，用於學習和熟悉CSS Grid布局。
成果:
![image](https://hackmd.io/_uploads/SJkFK6tU6.png)

# Chapter 16: Images

**1. 簡介：**
   - 教學目標：學習使用CSS美化前景圖片和背景圖片。
   - 涵蓋主題：前景圖片、背景圖片、CSS Reset、字型引入、百分比寬度、自適應高度、圖片最小寬度、圖片形狀、工具類別等。

**2. 開始：**
   - 起始HTML和CSS：基本HTML頁面，引入Google字型為Nanito，設定CSS Reset和一些基本樣式。

**3. 前景圖片：**
   - 在HTML中加入一個範例區塊（section）和一個段落（paragraph），內含一個自動引入的圖片（pat1.png）。
   - 設定圖片寬度、高度（200x200）以及圖片位置。
   - 強調圖片寬度使用百分比，讓圖片具有響應性。

**4. 圖片樣式調整：**
   - CSS設定區塊樣式，包括區塊距離、圖片寬度為25%，高度自適應、最小寬度、邊框設定等。
   - 解釋將圖片設定為`display: block;`的原因，以消除圖片下方的空白。

**5. 背景圖片：**
   - 創建新的區塊（section）並給予類別`hero`。
   - 在該區塊中使用`figure`元素，包含一個帶有類別的圖片和`figcaption`元素。
   - 設定圖片的寬度、高度、最小寬度、邊框，並使圖片呈現圓形。
   - 優化圖片選擇，強調選擇大於顯示尺寸的原則。

**6. 背景圖片樣式調整：**
   - 設定`hero`區塊的樣式，包括底部邊框、內邊距、flexbox布局。
   - 增加文字的顯著性，使其更突出可見。

**7. 背景圖片更換：**
   - 更換背景圖片為不同主題，如風景、地圖等。
   - 設定`background-repeat`，使圖片不重複或僅在水平或垂直方向重複。
   - 使用`background-size`設定為`cover`，讓圖片自適應填滿容器。

**8. 文字顯著性提升：**
   - 調整`h1`文字的顏色，使用`aliceblue`替代標準白色。
   - 強調選擇文字顏色以確保在不同背景下的可讀性。

**9. 圖片最佳化注意事項：**
   - 提及圖片最佳化的重要性，包括適當的圖片尺寸、格式和壓縮。
   - 建議總是使用高於實際顯示尺寸的圖片，避免因放大而模糊。
**10. **文字陰影效果：**
   - 將文字添加陰影效果，使其在頁面上更為突出。
   - 使用`text-shadow`屬性，設定X軸、Y軸的偏移值，模糊度（blur）和陰影顏色。
   - 例如：`text-shadow: 2px 2px 5px black;`

**11. **背景線性漸變（Linear Gradient）：**
   - 使用`linear-gradient`創建一個背景漸變效果，可以指定多個顏色和方向。
   - 指定起始和結束顏色，以及漸變方向，如`to left`表示從右至左。
   - 例如：`background: linear-gradient(to left, steelblue, purple, white);`

**12. **背景圖片（Background Image）：**
   - 使用`background-image`屬性設置背景圖片。
   - 透過`url`指定圖片路徑，如`url('../image/bubbles.jpg')`。
   - 例如：`background-image: url('../image/bubbles.jpg');`

**13. **背景大小（Background Size）：**
   - 使用`background-size`設定背景圖片的大小，可以是百分比或具體數值。
   - 例如：`background-size: 100%;`

**14. **背景重複（Background Repeat）：**
   - 使用`background-repeat`指定背景圖片的重複方式，如`no-repeat`表示不重複。
   - 例如：`background-repeat: no-repeat;`

**15. **背景位置（Background Position）：**
   - 使用`background-position`設定背景圖片的位置，可以是具體的坐標或指定方向。
   - 例如：`background-position: right center;`

**16. **背景樣式總和（Background Shorthand）：**
   - 使用`background`縮寫屬性總和設定背景樣式，包括背景顏色、背景圖片、重複方式、位置等。
   - 例如：`background: repeat-y right center url('../image/bubbles.jpg'), no-repeat linear-gradient(to left, steelblue, white);`

8. **文字轉換（Text Transform）：**
   - 使用`text-transform`設定文字轉換，將文字轉換為大寫。
   - 例如：`text-transform: uppercase;`

9. **背景遮罩（Background Clip）：**
   - 使用`-webkit-background-clip`實現背景遮罩效果，將背景圖片裁剪成文字形狀。
   - 需要結合`color`屬性，使文字透明度影響背景。
   - 例如：`-webkit-background-clip: text; color: transparent;`

這些屬性和效果的組合使得文本具有背景圖片的裁剪效果，同時達到了漸變、重複、陰影等視覺效果。整體而言，這是一個展示CSS背景樣式功能的綜合範例。
**專業術語和關鍵詞：**

1. **前景圖片（Foreground Image）：**
   - 定義：網頁中呈現在前景的圖片，即與其他內容一同顯示在使用者畫面上的圖片。

2. **背景圖片（Background Image）：**
   - 定義：網頁的背景中所顯示的圖片，通常在其他內容之後呈現，為整體風格和設計提供視覺元素。

3. **CSS Reset：**
   - 定義：一種CSS樣式重置技術，用於消除不同瀏覽器之間的默認樣式差異，確保開發者可以從一個統一的起點開始設計網頁。

4. **MDN（Mozilla Developer Network）：**
   - 定義：由Mozilla提供的開發者資源平台，提供關於Web技術的詳細文檔、指南和教學資源。

5. **響應性（Responsive）：**
   - 定義：網頁或應用程式能夠根據設備的不同尺寸和螢幕解析度進行適應和呈現，以提供更好的使用者體驗。

6. **Flexbox：**
   - 定義：CSS的排版模型之一，用於簡化和更有效地設計和排列容器中的子元素。

7. **百分比寬度（Percentage Width）：**
   - 定義：使用百分比值設定元素的寬度，相對於其包含元素的百分比。

8. **圖片最小寬度（Min Width）：**
   - 定義：設定圖片最小寬度，確保圖片在不失真的情況下總是具有最小的寬度。

9. **工具類別（Utility Classes）：**
   - 定義：在CSS中，指的是為特定風格或樣式目的而設計的簡短且可重複使用的類別，用於提高開發效率。

10. **背景重複（Background Repeat）：**
   - 定義：設定背景圖片是否重複顯示，包括`no-repeat`（不重複）、`repeat`（全方向重複）、`repeat-x`（水平方向重複）、`repeat-y`（垂直方向重複）等。

11. **背景尺寸（Background Size）：**
   - 定義：控制背景圖片在元素內的大小和適應方式，包括`cover`（填滿元素）、`contain`（完全包含在元素內）等。

12. **文字可讀性（Text Legibility）：**
   - 定義：確保文字在不同背景下清晰可見的能力，需要考慮文字顏色和背景之間的對比度。

13. **圖片最佳化（Image Optimization）：**
   - 定義：使用各種技術和工具來減小圖片文件大小，提高網頁載入速度，同時保持圖片的高質量。

14. **色彩對比度（Color Contrast）：**
   - 定義：文字和背景之間的色彩對比度，影響文字的可讀性和視覺吸引力。

15. **字型引入（Font Import）：**
   - 定義：在網頁中引入外部字型，以擴充網頁的字型選擇，提供更多設計選項。
### 關鍵字(Keywords):

1. **文字陰影效果**
2. **線性漸變 (Linear Gradient)**
3. **背景圖片 (Background Image)**
4. **背景大小 (Background Size)**
5. **背景重複 (Background Repeat)**
6. **背景位置 (Background Position)**
7. **背景樣式總和 (Background Shorthand)**
8. **文字轉換 (Text Transform)**
9. **背景遮罩 (Background Clip)**
10. **透明度 (Opacity)**
11. **HSL色彩模式**
12. **CSS縮寫屬性**
13. **text-shadow 屬性:** 用於添加文字陰影效果，指定X軸、Y軸的偏移值、模糊度和陰影顏色。
14. **linear-gradient:** 一種CSS函式，用於創建線性漸變的背景，可以指定多個顏色和漸變方向。
15. **background-image 屬性:** 用於設置元素的背景圖片。
16. **background-size 屬性:** 用於設置背景圖片的大小，可以是百分比或具體數值。
17. **background-repeat 屬性:** 用於設置背景圖片的重複方式，如no-repeat表示不重複。
18. **background-position 屬性:** 用於設定背景圖片的位置，可以是具體的坐標或指定方向。
19. **background 屬性總和:** 使用一個簡化的CSS屬性，同時指定背景顏色、背景圖片、重複方式、位置等。
20. **text-transform 屬性:** 用於設定文字的轉換效果，如轉換為大寫。
21. **-webkit-background-clip 屬性:** 一個CSS屬性，用於指定背景的裁剪方式，配合`text`值實現文字背景遮罩。
22. **Opacity 透明度:** 衡量物體的透明程度，可以用於設定文字或背景的透明度。
23. **HSL色彩模式:** 一種表示顏色的方式，包括色調（Hue）、飽和度（Saturation）、亮度（Lightness）。
24. **CSS縮寫屬性:** 使用單一屬性縮寫表示多個相關的CSS屬性，例如`background`縮寫了多個背景相關的屬性。
成果:
![image](https://hackmd.io/_uploads/ByToo0F8p.png)

# Chapter 17: Media Queries
這段教學涵蓋了CSS Media Queries的使用，以及如何根據特定特性和參數來修改網頁的外觀，主要以瀏覽器視窗寬度為例。以下是這段教學的詳細重點整理：

### HTML 部分：

1. 在 `<head>` 區塊中使用了 `<meta>` 標籤，設定了`viewport`，其中 `width=device-width` 表示視窗寬度將與裝置寬度一致，`initial-scale=1.0` 表示初始縮放比例為1.0。

2. 使用 Visual Studio Code 的快速產生 HTML 骨架的功能，並自動包含了 `viewport` 相關的設定。

### CSS 部分：

1. **基本 CSS：**
   - 引入 Google Fonts 中的 Nenito 字型。
   - 使用 CSS Reset 進行基本樣式重置。
   - 使用 `font` 縮寫屬性一次性設定字型大小和字型家族。

2. **Media Queries 語法：**
   - Media Query 語法示例：`@media screen and (min-width: 576px) { /* styles here */ }`
   - 常見的 Media Type: `screen`, `all`, `print`, `speech`。
   - 常見的條件：`min-width`, `max-width`, `orientation`, `min-aspect-ratio`。
   - 使用邏輯運算符如 `and` 來組合多個條件。

3. **Breakpoints 與樣式變更：**
   - 定義了四個主要的 Breakpoints 分別為 Small, Medium, Large, Extra Large。
   - 針對每個 Breakpoint 設定了不同的背景顏色和字型大小，以及特定元素的 `display` 屬性變更。
   - 演示了如何在不同裝置或視窗寬度下，根據條件應用不同的樣式。

4. **DevTools 的使用：**
   - 使用 DevTools 進行網頁元素的檢查和修改。
   - 啟用 Responsive 模式，模擬不同裝置的螢幕寬度和高度。
   - 實際演示了 Breakpoints 在不同設備上的應用效果。

5. **補充說明：**
   - 解釋了 Media Query 的語法，包括 Media Type、條件、Breakpoints 等。
   - 提到了 CSS Frameworks（Bootstrap, Tailwind）使用的一些常見 Breakpoints 值，以及不同 Frameworks 之間的差異。
   - 強調了在 Responsive Design 中，通常採用 Mobile First 的設計理念，即由小裝置開始設計，再逐漸擴展至大型裝置。
### 關鍵字：

1. **CSS 媒體查詢 - CSS Media Queries**
2. **視口 - Viewport**
3. **響應式設計 - Responsive Design**
4. **斷點 - Breakpoints**
5. **行動裝置優先設計 - Mobile First Design**
6. **開發者工具 - DevTools**
7. **HTML 元標籤 - HTML Meta Tag**
8. **CSS 重置 - CSS Reset**
9. **字型簡寫屬性 - Font Shorthand Property**
10. **Flex 容器 - Flex Container**
11. **Flexbox - Flexbox（彈性盒子）**
12. **粘性定位 - Position Sticky**
13. **徑向漸層 - Radial Gradient**
14. **Bootstrap（前端框架） - Bootstrap**
15. **Tailwind CSS（前端框架） - Tailwind CSS**
16. **寬高比 - Aspect Ratio**
17. **方向 - Orientation**
18. **響應式網頁設計 - Responsive Web Design**

### 專業術語：

1. **媒體類型 - Media Type**
2. **邏輯運算符 - Logical Operators**
3. **層疊 - Cascade**
4. **響應式元標籤 - Responsive Meta Tag**
5. **CSS 框架 - CSS Frameworks**
6. **視口單位 - Viewport Units**
7. **CSS 框架斷點 - CSS Framework Breakpoints**
8. **彈性盒子方向 - Flex Direction**
9. **CSS 簡寫屬性 - CSS Shorthand Properties**
10. **網格佈局 - Grid Layout**
11. **顯示屬性 - Display Property**
12. **行動裝置 - Mobile Devices**
13. **CSS 過渡效果 - CSS Transition**
14. **CSS 框架指南 - CSS Framework Guidelines**
15. **CSS 框架網格系統 - CSS Framework Grid System**
16. **網頁開發最佳實踐 - Web Development Best Practices**
17. **Visual Studio Code（程式碼編輯器） - Visual Studio Code**
18. **Markdown（輕量標記語言） - Markdown**
19. **HTML 骨架 - HTML Skeleton**
20. **Chrome 開發者工具 - Chrome DevTools**
成果:
![image](https://hackmd.io/_uploads/ryLmp5qUa.png)

# Chapter 18: Card Project

### HTML 部分：

1. **標題和內容設定：**
   - 標題改為 "CSS Mini Project: Profile Cards"。
   - 主要內容包括製作員工個人資料卡片的 CSS 小項目。

2. **頁面結構：**
   - 標題改為 "Our Staff"。
   - 在 `<nav>` 中添加員工的連結。
   - 在 `<main>` 中添加 `<article>` 元素，每個員工一個，包含圖片、名字和簡介。
   - 在 `<footer>` 中添加版權信息。

### CSS 部分：

1. **基本設定：**
   - 使用 CSS reset 進行基本樣式重置。
   - 設定圖片的 `display: block`，`max-width: 100%`，`height: auto` 以保持響應性。

2. **媒體查詢（Media Queries）：**
   - 使用媒體查詢在不同尺寸下應用不同的樣式。
   - 定義了四個媒體查詢：小屏幕、中等屏幕、大屏幕、極大屏幕。

3. **主要樣式設定：**
   - 使用 Flexbox 進行排版，實現響應式設計。
   - 設定字體、背景、顏色、間距等基本樣式。
   - 在 `<nav>` 中設定連結樣式，並使用 `justify-content: space-evenly` 達到平均分配連結的效果。

4. **卡片設計：**
   - 使用 `.card` 類別設定卡片樣式，包括寬度、邊框、背景色、邊框半徑等。
   - 調整圖片樣式，設定邊框和邊框半徑，使其呈現圓形。
   - 在 `.card figcaption` 中設定字體大小、粗體等樣式。

5. **媒體查詢內的樣式修改：**
   - 在不同媒體查詢下，調整主要樣式和卡片樣式，以適應不同的螢幕尺寸。
   - 根據媒體查詢進行排版、字體大小、卡片寬度等方面的調整。

6. **Smooth Scroll 功能：**
   - 在 HTML 元素上設置 `scroll-behavior: smooth` 實現平滑捲動效果。

7. **HTML Entity 和 Unicode：**
   - 使用 HTML Entity `&copy;` 表示版權符號。

### 關鍵字和專業術語：
- CSS迷你項目-CSS Mini Project 
- 媒體查詢（Media Queries） - Media Queries
- Flexbox - （靈活盒模型）Flexbox
- 響應式設計 - Responsive Design
- CSS Reset - CSS 重置
- HTML 實體 - HTML Entity 
- 平滑滾動 - Smooth Scroll 
- Calc 函數 - Calc function 
- 卡片設計 - Card Design
- 響應式圖片 - Responsive Images
- 字體大小 - Font Size
- 顏色設定 - Color Setting
- 邊框半徑 - Border Radius
- 媒體查詢內的樣式修改 - Style Modification in Media Queries
- Flex 布局 - Flex Layout
- 選擇器 - Selectors
- VS Code 擴展 - VS Code Extensions
- h1、nav、main、article、footer、figure、figcaption、img、p 元素 - h1、nav、main、article、footer、figure、figcaption、img、p Elements
- 字體縮寫Font Shorthand
- Normalize.css（樣式重置工具）Normalize.css 
成果:
![image](https://hackmd.io/_uploads/rymb3s5LT.png)

# Chapter 19: Pseudo
這段文字主要講解了CSS的pseudo selectors，包括pseudo classes和pseudo elements的使用。以下是這段文字的分段落，以及其中提到的一些關鍵字和專業術語：

**1 簡介pseudo classes和pseudo elements**
這段文字介紹了CSS中的pseudo classes和pseudo elements，並提到了它們的區別。pseudo classes用於選擇處於特定狀態的元素，而pseudo elements則類似於在文檔中添加了新的HTML元素。示例中展示了pseudo classes的應用，包括選擇不同狀態的連結。

**2 使用`:is` pseudo selector**
這部分示範了使用`:is` pseudo selector，它選擇了所有指定的選擇器，使代碼更加簡潔，避免了重複的選擇器。

**3 使用`:any-link` pseudo class**
這部分示範了使用`:any-link` pseudo class，它選擇了所有的鏈接（包括未訪問和已訪問的）。這樣的選擇器可以使代碼更簡潔。

**4 使用`:not` pseudo class**
在這一部分，介紹了`:not` pseudo class的應用，用於選擇不滿足指定條件的元素。在示例中，用它來檢查是否所有的圖片都有`alt`屬性，並且對未滿足條件的元素應用樣式。

**5 使用`:nth-child` pseudo class**
這部分講解了`:nth-child` pseudo class的使用，用於選擇某個元素的特定兄弟元素。示例中展示了如何選擇特定順序的卡片元素，並對其應用樣式。

**6 pseudo elements的應用**
這一部分轉向講解pseudo elements的應用，包括`:before`和`:after`。示例中展示了如何在元素內部添加額外的內容，比如在名字後面添加表情符號。

**7 使用`:first-letter`和`:first-line` pseudo elements**
在這一段，講解了`:first-letter`和`:first-line` pseudo elements的應用。示例中展示了如何應用這些pseudo elements來樣式化名字的第一個字母或第一行文字。

**關鍵字和專業術語:**
- 偽類（pseudo classes）
- 偽元素（pseudo elements）
- `:is` 偽選擇器
- `:any-link` 偽類
- `:not` 偽類
- `:nth-child` 偽類
- `:before` 偽元素
- `:after` 偽元素
- `:first-letter` 偽元素
- `:first-line` 偽元素
- 特定性（specificity）
- 後代選擇器（descendant selector）
- 
# Chapter 20: Variables
這段文字主要講解了在CSS中使用變數（CSS variables）的優勢，以及如何定義和應用這些變數。以下是這段文字的分段落，以及其中提到的一些關鍵字和專業術語：

**1 引入CSS變數的重要性**
這段文字開頭介紹了CSS變數的重要性，特別是在大型項目中使用相同的顏色代碼多次的情況。提到如果不使用變數，當需要修改顏色時，必須在整個項目中尋找和更改每個實例，而使用變數則只需在一處進行修改。

**2 定義和使用CSS變數**
接下來的段落中，介紹了如何在CSS中定義變數，並使用`:root`擴展了全域作用範圍，使這些變數在整個項目中生效。示例中展示了定義背景顏色的變數，以及如何在CSS中使用這些變數。

**3 CSS變數的多樣應用**
在這一段，講解了使用CSS變數的多樣應用，包括應用在不同元素的背景、寬度、邊框半徑、字體大小等屬性。同時，提到了在變數定義中使用`var`函數的方式。

**4 適應夜間模式的CSS變數**
最後一段中，介紹了如何利用媒體查詢（media query）和`prefers-color-scheme`屬性實現夜間模式（dark mode）。示例中重新定義了暗色調的顏色變數，使網頁可以在夜間模式和白天模式之間切換。

**關鍵字和專業術語:**
- CSS變數（CSS variables）
- `:root` pseudo class
- 變數定義（Variable definition）
- `var` 函數
- 全域作用範圍（Global scope）
- 媒體查詢（Media query）
- `prefers-color-scheme` 屬性
- 夜間模式（Dark mode）
<hr>
快捷鍵: Crtl + Shift + L 相同全選
<hr>
成果:
![image](https://hackmd.io/_uploads/rkcWRyiL6.png)

# Chapter 21: Functions

1. 今天我們將深入研究CSS函數，我們的起始代碼類似上一課的結束代碼。讓我們快速檢視HTML結構。在右側的頁面上，有一個H2標題、一個段落和一個在主要元素中的區塊元素內的鏈接。先前的div元素已被註釋掉。CSS保持不變，使用了顏色函數和圖像函數。


2. CSS函數包括顏色函數，如RGB、HSL和HWB，以及圖像函數，如徑向漸變、線性漸變、用於CSS變數的var和用於將圖像加載到背景位置的url。文本提到有許多CSS函數，將提供一個指向MDN頁面的鏈接，其中列出了所有CSS函數。本課的焦點是一些常用的數學函數。


3. 介紹了`min`函數。當前字號為1.5rem，相當於24像素。然後，`min`函數應用於字號，使用絕對值（2.25rem）和相對值（3vh）。`min`函數選擇兩者中的最小值。通過調整視口高度進行演示，以顯示字號的變化。


4. 接下來，介紹了`max`函數。與`min`類似，它使用絕對值（1.75rem）和相對值（3vh）。`max`函數選擇兩者中的較大值。同樣，演示涉及調整視口高度以顯示字號變化。


5. 討論了使用`min`和`max`函數的限制和注意事項。強調應該有一個絕對值和一個相對值。解釋了在字體中使用視口高度單位的優勢。


6. 介紹了`clamp`函數，作為`min`和`max`的替代品。它允許指定最小值、理想值和最大值。演示展示了根據視口高度調整字號的效果。


7. 應用`clamp`函數創建了一個小字號（`fs-sm`）。對區段和附註進行了額外的樣式設置，並使用媒體查詢實現了響應式設計。


8. 通過示例介紹了一個工具提示，使用自定義屬性（`data-tooltip`）和`::before`虛擬元素。針對鏈接的懸停和焦點效果，演示了各種CSS屬性，包括`filter`和`hue-rotate`。


9. 課程轉向Grid。將現有的flex屬性註釋掉，建立了一個新的網格布局。使用`repeat`和`minmax`函數定義了網格列。使用`min`函數調整了gap屬性。


10. 對CSS進行了額外的調整，包括將網格項目的寬度和高度屬性註釋掉。在主元素中添加了內邊距以實現間距。


11. 通過調整視口大小來檢視網格佈局的行為，提到了適應佈局的媒體查詢的重要性。

### 關鍵詞和專業術語：
- **CSS函數 (CSS Functions)**
- **HTML結構 (HTML Structure)**
- **顏色函數（RGB、HSL、HWB）(Color Functions: RGB, HSL, HWB)**
- **圖像函數（徑向漸變、線性漸變、var、url）(Image Functions: Radial Gradient, Linear Gradient, var, url)**
- **數學函數 (Mathematical Functions)**
- **視口單位 (Viewport Units)**
- **`min`函數 (`min` Function)**
- **`max`函數 (`max` Function)**
- **絕對值和相對值 (Absolute and Relative Values)**
- **`clamp`函數 (`clamp` Function)**
- **響應式設計 (Responsive Design)**
- **媒體查詢 (Media Queries)**
- **工具提示 (Tooltip)**
- **自定義屬性（`data-tooltip`）(Custom Attribute: `data-tooltip`)**
- **虛擬元素（`::before`）(Pseudo-element: `::before`)**
- **`filter`屬性 (`filter` Property)**
- **`hue-rotate`屬性 (`hue-rotate` Property)**
- **網格佈局 (Grid Layout)**
- **`repeat`函數 (`repeat` Function)**
- **`minmax`函數 (`minmax` Function)**
- **gap屬性 (`gap` Property)**
- **CSS屬性（內邊距、寬度、高度）(CSS Properties: Padding, Width, Height)**
- **CSS變換、過渡和動畫 (CSS Transforms, Transitions, and Animations)**
成果:
![image](https://hackmd.io/_uploads/BkeUb7sUT.png)

# Chapter 22: Animations
這段程式碼是一個 CSS 動畫的範例，主要展示了使用 transforms、transitions、和 animations 的基本概念。以下是對這段程式碼的分段解釋：

1. **HTML 結構：**
   在 `index.html` 檔案中，有一個 `main` 元素，其中包含三個 `div`，每個 `div` 都有一個 `squares` 的類別。最後一個 `div` 有一個 `animate` 的類別。每個 `div` 包含一個不同的表情符號。

2. **CSS 基本設定：**
   - 引入 Google 的 Nunito 字型。
   - 進行基本的 CSS 重置。
   - 設定 HTML 的字型大小和應用匯入的 Nunito 字型。
   - 設定 `body` 的最小高度為 100 視窗單位高度，使用 flex 顯示，排列方式為 column。
   - 設定 `main` 元素，使其在 `body` 內彈性增長，同時內容使用 flex 顯示，排列方式為 column，並且居中對齊。
   - 設定 `main` 元素中的 `div`，使其具有寬高為 200 像素的正方形，有一像素的黑色實線邊框，並使用 `display: grid` 屬性，以便輕鬆置中內容（表情符號）。

3. **CSS Transform 屬性：**
   - 使用 `:first-child` 選擇器選取第一個 `div`，並將其背景顏色設為 "dodgerblue"。
   - 使用 `:nth-child(2)` 選擇器選取第二個 `div`，並將其背景顏色設為 "yellow"。
   - 使用 `:last-child` 選擇器選取最後一個 `div`，並將其背景顏色設為 "limegreen"。
   - 展示了 `transform` 屬性的使用，以進行平移操作，分別使用 `translateX` 和 `translateY`。
   - 展示了使用 `translate` 的總體平移效果，同時指定 x 和 y 軸的值，並展示了不同的單位（百分比和 rim）。

4. **過渡效果 (Transitions)：**
   - `transition` 屬性：CSS 中用於定義元素在狀態變化時的平滑過渡的屬性。
   - `transition-property`：指定應用過渡效果的 CSS 屬性。
   - `transition-duration`：指定過渡效果的持續時間。
   - `transition-delay`：指定過渡效果的延遲時間。
   - `transition-timing-function`：指定過渡效果的時間函數，控制過渡的速度。

5. **偽類選擇器 (Pseudo-class Selectors)：**
   - `:first-child`：選擇某元素的第一個子元素。
   - `:last-child`：選擇某元素的最後一個子元素。
   - `:hover`：選擇某元素在滑鼠懸停時的狀態。

6. **CSS 單位 (Units)：**
   - `deg`：度數的 CSS 單位，通常用於旋轉效果。
   - `rem`：相對於根元素字體大小的 CSS 單位。

7. **字體 (Font)：**
   - `Nunito`：由 Google 提供的字型，通常透過引入到網頁中應用。

8. **彈性盒模型 (Flexbox)：**
   - `display: flex`：在 CSS 中用於創建彈性容器，實現內部子元素的靈活佈局。


9. **CSS 屬性 (CSS Properties)：**
   - `background-color`：元素的背景顏色。
   - `color`：文字顏色。

10. **CSS 選擇器 (CSS Selectors)：**
   - `header`、`:hover`、`:focus-within`：選擇標頭、懸停狀態和焦點在其中的狀態。
   - `.menu-icon`、`:before`、`:after`：選擇菜單圖標、其前綴和其後綴。

11. **CSS3 2D 轉換 (CSS3 2D Transformations)：**
   - `translate`、`rotate`、`scale`：用於2D變形的CSS3屬性。

12. **CSS3 3D 轉換 (CSS3 3D Transformations)：**
    - `rotateX`、`rotateY`、`rotateZ`：用於3D旋轉的CSS3屬性。

13. **CSS3 動畫 (CSS3 Animations)：**
    - `@keyframes`：定義動畫中的關鍵幀。
    - `animation`：應用動畫的總體屬性，包括名稱、持續時間、時間函數和延遲。


關鍵詞和專業術語：

1. **變形 Transforms：**
   - `transform` 屬性：在 CSS 中用於對元素進行變形。
   - `translateX` 和 `translateY`：`transform` 的函數之一，用於實現元素的水平和垂直平移。

2. **CSS 重置 CSS Reset：**
   - 用於重置瀏覽器默認樣式的 CSS 規則，以確保跨瀏覽器一致性。

3. **彈性盒模型 Flexbox：**
   - `display: flex`：在 CSS 中用於創建彈性容器，使其內部的子元素能夠更靈活地佈局。

4. **視窗單位 Viewport Units：**
   - `vh`（視窗高度）：以視窗高度為單位的 CSS 單位。
   - `vw`（視窗寬度）：以視窗寬度為單位的 CSS 單位。

5. **Nunito 字型：**
   - 一種由 Google 提供的字型，透過引入應用於網頁。

6. **偽類選擇器 Pseudo-class Selectors：**
   - `:first-child`：選擇某元素的第一個子元素。
   - `:nth-child(n)`：選擇某元素的第 n 個子元素。
   - `:last-child`：選擇某元素的最後一個子元素。

7. **過渡效果 Transition：**
   - 用於在元素狀態變化時平滑過渡的 CSS 屬性。

8. **動畫效果 Animation：**
   - 用於定義元素的動畫效果的 CSS 屬性。
   - `@keyframes`：定義動畫的關鍵幀。
   - 
9. **過渡效果 (Transition Effects)：**
   - `transition`：定義元素在狀態變化時的平滑過渡的 CSS 屬性。
   - `transition-property`：應用過渡效果的 CSS 屬性。
   - `transition-duration`：過渡效果的持續時間。
   - `transition-delay`：過渡效果的延遲時間。
   - `transition-timing-function`：過渡效果的時間函數，控制過渡的速度。

10. **偽類選擇器 (Pseudo-class Selectors)：**
   - `:first-child`：選擇第一個子元素。
   - `:last-child`：選擇最後一個子元素。
   - `:hover`：當滑鼠懸停在元素上時應用的狀態。

11. **CSS 單位 (Units)：**
   - `deg`：度數的 CSS 單位，通常用於旋轉效果。
   - `rem`：相對於根元素字體大小的 CSS 單位。

12. **字型 (Font)：**
   - `Nunito`：由 Google 提供的字型，透過引入到網頁中應用。

13. **彈性盒模型 (Flexbox)：**
   - `display: flex`：用於創建彈性容器，實現內部子元素的靈活佈局。

14. **CSS 屬性 (CSS Properties)：**
   - `background-color`：元素的背景顏色。
   - `color`：文字顏色。

15. **CSS 選擇器 (CSS Selectors)：**
   - `div`：選擇所有 `<div>` 元素。
   - `div:hover`：當滑鼠懸停在 `<div>` 元素上時應用的樣式。

10. **CSS3 2D 轉換 (CSS3 2D Transformations)：**
   - `translate`、`rotate`、`scale`：用於2D變形的CSS3屬性。

11. **CSS3 3D 轉換 (CSS3 3D Transformations)：**
    - `rotateX`、`rotateY`、`rotateZ`：用於3D旋轉的CSS3屬性。

12. **CSS3 動畫 (CSS3 Animations)：**
    - `@keyframes`：定義動畫中的不同階段。
    - `animation`：應用動畫的總體屬性，包括名稱、持續時間、時間函數和延遲。
成果:
![image](https://hackmd.io/_uploads/SJTv74jIa.png)
![image](https://hackmd.io/_uploads/BJGaO4jLp.png)

# Chapter 23: Organization
這段教學內容主要涵蓋CSS的組織和命名規則，特別是BEM（Block Element Modifier）命名法。以下是分段的中文回答：

1. **團隊規則與組織原則：**
   在開發專案時，應該遵循所在團隊已經確立的CSS檔案組織模式。這樣做是因為作為初學者的你可能是新進開發者，最好跟隨團隊的模式，以免造成混亂。

2. **使用註釋創建標題或分隔標籤：**
   在CSS中使用註釋來創建標題或分隔標籤，以方便日後迅速找到特定區塊的程式碼。這包括標題、變數、樣式、和區塊等。

3. **屬性排序：**
   屬性的排序通常以字母順序進行，這有助於快速查找特定屬性。可以使用Visual Studio Code的排序功能，通常是按下`Ctrl+P`，輸入`sort lines ascending`，即可按字母順序排列所選的屬性。

4. **BEM 命名法：**
   BEM是一種常見的命名法，其中BEM代表「Block Element Modifier」。它將CSS類別分為區塊（Block）、元素（Element）和修改器（Modifier）。區塊是一個独立的可重複使用的組件，元素是區塊的一部分，而修改器則用於調整區塊或元素的外觀。

5. **應用 BEM 命名法：**
   在實際代碼中，以區塊開始，如 `.button`，然後使用兩個底線表示元素，例如 `.button__icon`。如果要對區塊或元素進行修改，使用兩個減號，如 `.button--large`。這樣的命名法有助於組織和維護代碼。

6. **修改器的應用：**
   修改器用於對區塊或元素進行增量樣式更改。在HTML中，可以將修改器額外應用到類別中，以簡單地改變元素的外觀。

7. **選擇器的特殊性：**
   使用BEM命名法可以保持選擇器的特殊性，這有助於避免CSS樣式的衝突。在特殊性方面，使用類別選擇器比使用元素和類別組合的選擇器更具優勢。

**關鍵詞和專業術語：**

1. **CSS (層疊樣式表):**
   層疊樣式表是一種用於描述文檔樣式（包括字體、顏色、間距等）的樣式表語言，它與HTML一同用於網頁的外觀和格式。

2. **BEM (Block Element Modifier):**
   BEM是一種CSS命名法，將樣式類別分為區塊（Block）、元素（Element）和修改器（Modifier）。這有助於組織和管理CSS代碼。

3. **特殊性 (Specificity):**
   在CSS中，特殊性是指選擇器被應用到元素時的優先級。使用類別選擇器（如`.class`）有助於保持特殊性的一致性。

4. **註釋 (Comments):**
   在代碼中使用註釋，以便標記和解釋代碼的不同部分，提高代碼的可讀性。

5. **排序 (Sorting):**
   在CSS屬性中進行排序，通常以字母順序排列，有助於提高代碼的可讀性。可以使用編輯器功能進行自動排序。

6. **特定項目 (Selectors):**
   在CSS中，選擇器是用來選擇要樣式化的HTML元素的模式。BEM使用特定的類別選擇器來確保樣式的一致性。

7. **元素 (Element):**
   在BEM中，元素是區塊的一部分，表示區塊內的特定元素，使用兩個底線表示（`__`）。

8. **區塊 (Block):**
   在BEM中，區塊是可重複使用的獨立組件，用於包裝相關的元素。區塊使用單一底線表示（`_`）。

9. **修改器 (Modifier):**
   在BEM中，修改器是用於調整區塊或元素外觀的樣式變化。使用兩個減號表示（`--`）。

10. **特殊性計算器 (Specificity Calculator):**
    用於計算CSS選擇器特殊性的工具，幫助開發人員理解樣式適用的優先級。

11. **命名慣例 (Naming Convention):**
    遵循特定模式和約定的標識方式，BEM是一種常見的CSS命名慣例。

12. **樣式衝突 (Style Conflicts):**
    在CSS中，樣式衝突發生在兩個或多個樣式規則之間存在衝突，可能導致預期之外的外觀。
成果:
![image](https://hackmd.io/_uploads/Byh6mHiUa.png)

# Chapter 24: Final Project
這段文字描述了一個CSS初學者課程的最終項目，該項目旨在將基本的HTML網站轉變為具有響應式設計的現代網站。以下是對文本的分段和提取的關鍵字和專業術語：

1. - 描述希望提供的建議和組織CSS的期望效果。
- 提到將應用一些CSS技巧到即將進行的最終項目中。

2. - 歡迎學生參與CSS初學者課程的最終項目。
- 提到在HTML初學者課程中構建的簡單網站，該網站提供了CSS的基礎。

3. - 引入最終項目的開始，介紹初始代碼的結構，並建議下載初始代碼。
- 提到從HTML初學者課程結尾的完整網站，並準備將其轉變為響應式現代網站。

4. - 描述初始代碼中包含的HTML頁面和圖片文件夾結構。
- 提到將刪除一些較小的圖片，以及保留一些大圖片的原因。

5. - 提到HTML頁面中的meta標記，包括一個缺失的viewport標記。
- 引入“viewport” meta標記，並解釋其作用是實現響應式設計。

6. - 描述在“about.html”頁面中添加新的HTML文件。
- 提到將初始代碼中的“about”內容抽象出來，創建新的“about.html”頁面。

7. - 引入BEM（Block Element Modifier）命名慣例，用於CSS類的命名。
- 提到將應用特定的類別，如“header”和“hero”，以更好地組織CSS。

8. - 在“index.html”中應用BEM類，包括“header”和“hero”類。
- 描述對“hero”區域的修改，包括更換圖片和應用新的CSS類。

9. - 描述將頂部兩個部分（標題和hero區域）在所有HTML文件中重複應用的計劃。

10. 在上述代碼中，教程的作者提到了將菜單調整為 about 頁面的步驟。
11. 接著作者提到將頁面標題更改為 "Little Taco Shop"，而不再是 "Welcome to the Little Taco Shop"。
12. 隨後，作者針對 about 頁面中的 hero section 進行了一些更改，包括更換圖片和標題。
13. 文章提到使用了 BEM（Block Element Modifier）命名慣例，以及一些 HTML 和 CSS 的基本結構。
14. 作者開始編寫 CSS，並在一開始引入了從 Google Fonts 獲取的兩種字體，分別是 "Fugaz One" 和 "Nunito"。
15. 作者使用了 CSS reset 以及一些常見的全域樣式，例如將所有圖片設為 block，以實現響應式圖片。
16. 進一步，文章提到定義了一些 CSS 變數，如字體、字體大小和顏色。
17. 文章中還介紹了一些實用的 CSS 類別，例如將元素移出屏幕的 "off screen"，禁止文本換行的 "no wrap" 以及文本居中的 "center"。
18. 最後，作者開始應用一般樣式，並在 HTML 元素上設置了一些屬性，如背景色和滾動行為。
19. 在這一部分中，作者繼續設計網頁的樣式，並應用了一些基本的 CSS 選擇器和屬性。
10. 透過使用 CSS 變數，作者能夠輕鬆地調整字體、顏色等屬性，提高代碼的可讀性和可維護性。
21. 作者使用了一些實用的 CSS 類別，例如 off-screen、no-wrap 和 center，以方便在不同部分應用一致的樣式。
22. 導入了 Google Fonts 以獲取特定字體，同時使用了 BEM 命名慣例來組織 CSS 類別。
23. 通過應用樣式到 HTML 和 Body 元素，使整個頁面呈現出一致的風格，並實現了一些視覺效果，如線性漸變背景和陰影效果。
24. 作者注重使用 CSS 變數和結構化的代碼，以提高代碼的可維護性和可讀性。

25. 在這一部分中，作者開始設計網頁的標頭（header）部分，使用 BEM 命名慣例來組織和命名 CSS 類別。
26. 透過 CSS 變數的使用，作者能夠更靈活地調整顏色、背景等屬性，以提高代碼的可讀性和可維護性。
27. 定義了一些新的 CSS 變數，如 header-bg-color（標頭背景顏色）、header-color（標頭文字顏色）、nav-bg-color（導航背景顏色）等。
28. 使用了一些基本的樣式，如設置標頭為粘性定位、對齊標題文字居中、添加陰影效果等。
29. 通過應用樣式到標題（h1）、導航（nav）、和無序列表（unordered list）等元素，實現了一致的設計風格。
30. 討論了為什麼創建額外的變數，即使它們的顏色值可能相同，以便未來實現暗黑模式等主題時能夠更靈活地調整。
31. 作者在這一部分討論了網頁頭部（header）的設計，並提到了先前學到的製作動態移動版頭部的技巧，但由於這個專案的規模較小，只有四個頁面和四個連結，因此選擇不應用該技巧，以保持簡潔。
32. 對於標題部分的調整，作者刪除了 "Welcome to the" 的文字，只保留 "Little Taco Shop"，以簡化標題的內容。
33. 介紹了一個用於樣式化主視覺區域（hero section）的新 CSS 變數，包括 hero-bg-color（主視覺區域的背景顏色）和 hero-color（主視覺區域文字的顏色）。
34. 應用了一些基本的樣式，如 padding、letter spacing、text shadow，以及絕對定位和動畫效果，以實現標題的特殊效果。
35. 介紹了 CSS 中的動畫（animation）和 keyframes 的使用，並創建了一個名為 "show welcome" 的動畫，用於實現標題的下拉和出現效果。

36. 作者在這一部分進行了對網頁的底部（footer）進行樣式設計，使其固定在頁面底部，顏色與頭部（header）保持一致，同時添加了一些內邊距（padding）和文字居中的樣式。
37. 運用 CSS 變數，使得底部的背景色和文字顏色可以輕松保持一致性。
38. 在樣式中使用了 `position: sticky` 屬性，以確保底部在頁面滾動時保持在底部。
39. 對於主元素（main）的樣式，作者複製了底部的標題樣式，應用於主元素的標題，同時添加了一些內邊距。
40. 運用 `scroll-margin-top` 和 `margin` 屬性確保主要內容在滾動時不會被頁面頂部標題擋住，同時保證良好的頁面布局。
41. 作者在這部分介紹了對網頁不同部分（about、contact、hours）進行樣式設計的過程，包括使用 BEM 命名法為元素添加類別，以及應用不同的樣式屬性，如 `margin`、`padding`、`border-radius` 等。
42. 特別提到了在表單設計中的一些樣式，包括對標籤（label）、輸入框（input）、文本區域（textarea）、按鈕（button）等元素進行樣式設計，使其更具可讀性和視覺吸引力。
43. 介紹了使用 CSS 變數（`var`）的優勢，以及在維護樣式一致性方面的作用。
44. 引用了 MDN 上的資源，強調在使用 Grid 佈局時避免標記平坦化的危險，並解釋了這個概念。
45. **表格結構問題：**
   - 引入了在使用CSS Grid時處理表頭和表格數據的問題。
   - 提到了不希望移除表的語義標記，但需要使其適應Grid。

46. **解決方案：**
   - 引入了`display: contents`屬性，使元素的子元素在視覺上表現得像它們是直接的父元素的子元素。
   - 解釋了如何使用這一特性，特別是在表格的`thead`、`tbody`和`tfoot`元素上。

47. **展示了不推薦的方法：**
   - 演示了不推薦的將表格轉換為網格的方法，即使用`div`和添加大量類的方式。

48. **`display: contents`的瀏覽器支持：**
   - 引用了“caniuse.com”上關於`display: contents`的信息，表明它在大多數主流瀏覽器中得到了廣泛支持。

49. **HTML結構更新：**
   - 更新HTML代碼，將特定的類應用於表格元素，以便更好地與CSS Grid集成。

50. **CSS Grid樣式應用：**
   - 應用了`display: grid`以及`grid-template-columns`屬性，將表格轉換為網格結構。
   - 定義了各個網格區域的名稱，使用`grid-area`屬性。

51. **應用類和樣式：**
   - 創建了具有語義命名的類，如`menu`, `header`, `item`, `cr` (crunchy), `sf` (soft), `cs` (chips and salsa)等。
   - 將這些類應用於相應的表格單元格，以便更好地控制樣式。

52. **HTML元素和頁面結構：**
   - `<time>`元素：HTML5中的時間元素，用於表示日期和時間。
   - `<script>`元素：HTML中用於引入JavaScript代碼的標簽。
   - `id`屬性：HTML中用於唯一標識元素的屬性。
   - `class`屬性：HTML中用於為元素指定一個或多個類的屬性。

53. **CSS樣式：**
   - `display: grid`：CSS屬性，用於將元素變為網格容器。
   - `font-weight`：CSS屬性，用於設置字體的粗細。
   - `border`屬性：CSS屬性，用於設置元素邊框。
   - `padding`：CSS屬性，用於設置元素的內邊距。
   - `margin`：CSS屬性，用於設置元素的外邊距。
   - `color`：CSS屬性，用於設置文本顏色。
   - `background-color`：CSS屬性，用於設置背景顏色。
   - `var()`：CSS函數，用於引用自定義屬性值（變量）。

54. **JavaScript代碼：**
   - `const`：JavaScript關鍵字，用於聲明一個常量。
   - `document`對象：JavaScript中表示整個HTML文檔的對象。
   - `getElementById()`方法：通過元素的ID獲取頁面中的元素。
   - `Date`對象：JavaScript中用於處理日期和時間的內置對象。
   - `setAttribute()`方法：用於設置元素的屬性值。
   - `textContent`屬性：JavaScript中用於獲取或設置元素的文本內容。

55. **動畫效果：**
   - `@keyframes`：CSS規則，用於創建動畫序列。
   - `animation`屬性：CSS屬性，用於指定動畫的名稱、時長等。

56. **響應式設計：**
   - `@media`查詢：CSS中用於根據不同的媒體設備或條件應用樣式的規則。
   - `min-width`：媒體查詢中的條件，指定屏幕寬度的最小值。

57. **其他關鍵字：**
   - `defer`：用於`<script>`標簽的屬性，表示腳本將在文檔解析完成後執行。

**關鍵字和專業術語：**
1. 響應式設計（Responsive Design）
2. HTML
3. CSS
4. BEM（Block Element Modifier）命名慣例
5. Meta標記
6. 視窗（Viewport）
7. HTML文件
8. 圖片文件夾（Image Folder）
9. 代碼組織（Code Organization）
10. 主區段（Hero Section）
11. 標題（Header）
12. 圖片區（Figure）
13. Alt 屬性（Alt Attribute）
14. 類別（Class）
15. CSS 類別（CSS Classes）
16. 基本網站（Basic Website）
17. 元素（Element）
18. 標籤（Tag）
19. 屬性（Attribute）
20. 元資料（Meta Data）
21. 視窗（Viewport）
22. 網頁抽象（Abstraction）
23. 代碼結構（Code Structure）
24. 文件夾結構（Folder Structure）
25. 命名慣例（Naming Convention）
26. 響應式圖片（Responsive Image）
27. HTML頭部（Head Section）
28. HTML主體（Body Element）
29. 水平線（Horizontal Rule）
30. 屏幕讀取器（Screen Reader）
31. BEM（Block Element Modifier）命名慣例
32. CSS reset
33. Google Fonts
34. 響應式設計
35. CSS 變數
36. 全域樣式
37. HTML 元素
38. Scroll Behavior
39. 字體大小
40. Off screen
41. No wrap
42. Center
43. 基本結構
44. 預處理器
45. 元素選擇器
46. Clamp function
47. Box sizing
48. 單位（rem、viewport units）
49. 線性漸變（Linear Gradient）
50. HTML 頁面行為
51. CSS 複合選擇器
52. 單位（hexadecimal code、pixels）
53. 瀏覽器兼容性
54. 布局模型
55. HTML 屬性
56. 元件化
57. 媒體查詢
58. 字型屬性
59. HTML 元素屬性
60. Pseudo elements
61. **CSS Reset（CSS 重置）：** 一種用於覆蓋瀏覽器默認樣式的 CSS 代碼，確保在不同瀏覽器上獲得一致的顯示效果。
62. **BEM（Block Element Modifier）命名慣例：** 一種用於組織和命名 CSS 類的約定，提高代碼的可讀性和可維護性。
63. **CSS 變數：** 允許在 CSS 中定義和重複使用值的標識符。
64. **Google Fonts：** Google 提供的免費字體服務，允許開發者在其網站中使用不同風格的字體。
65. **Responsive Design（響應式設計）：** 一種網頁設計方法，確保網站在不同設備和螢幕尺寸上都能提供最佳的使用體驗。
66. **Pseudo Classes（虛擬類別）：** CSS 中的一種選擇器，用於選擇元素的特定狀態，如:hover（懸停）、:active（點擊時）等。
67. **HSLA（Hue, Saturation, Lightness, Alpha）：** 一種定義顏色的方式，除了色相、飽和度和亮度外，還包括 alpha 通道，表示透明度。
68. **Box Shadow（框陰影）：** CSS 屬性，用於在元素周圍添加陰影效果。
69. **HTML 元素：** HyperText Markup Language（超文本標記語言）中的構建塊，用於創建網頁的結構和內容。
70. **Body 元素：** HTML 中的主體元素，包含網頁的主要內容。
71. **Sticky Positioning（粘性定位）：** CSS 定位方式之一，使元素在滾動時保持在屏幕的特定位置。
72. **BEM（Block Element Modifier）命名慣例：** 一種用於組織和命名 CSS 類的約定，提高代碼的可讀性和可維護性。
73. **CSS 變數：** 允許在 CSS 中定義和重複使用值的標識符。
74. **Background Color（背景顏色）：** HTML 元素的背景顏色，可以透過 CSS 設置。
75. **Font Weight（字體粗細）：** CSS 屬性，用於設置字體的粗細程度，如 normal（常規）或 bold（粗體）。
76. **Box Shadow（框陰影）：** CSS 屬性，用於在元素周圍添加陰影效果。
77. **Display Flex（彈性盒模型）：** CSS 屬性，用於將元素設置為彈性容器，實現靈活的布局。
78. **Gap（間距）：** CSS 屬性，用於設置彈性容器中子元素之間的間距。
79. **List Style Type（列表樣式類型）：** CSS 屬性，用於設置列表項目的樣式，如 none（無樣式）、disc（實心圓點）等。
80. **Justify Content（內容對齊）：** CSS 屬性，用於在主軸上對齊彈性容器中的子元素。
81. **Animation（動畫）：** CSS 屬性，用於創建在元素上應用的動畫效果。
82. **Keyframes（關鍵幀）：** CSS 屬性，用於定義動畫的各個階段，指定在不同時間點上元素的樣式。
83. **Skew（傾斜）：** CSS 屬性，用於將元素在水平或垂直方向上傾斜一定角度。
84. **Transform（變形）：** CSS 屬性，用於在元素上應用 2D 或 3D 轉換效果，如平移、旋轉、縮放等。
85. **Scale（縮放）：** CSS 變形的一種，用於按照指定比例進行元素的縮放。
86. **Absolute Positioning（絕對定位）：** CSS 定位方式之一，使元素相對於其最近的已定位父元素（如果存在）或文檔的視口進行定位。
87. **Padding（內邊距）：** CSS 屬性，用於設置元素內容區域與邊框之間的距離。
88. **Letter Spacing（字母間距）：** CSS 屬性，用於設置字母之間的空間距離。
89. **Text Shadow（文字陰影）：** CSS 屬性，用於在文本周圍添加陰影效果。
90. **Opacity（不透明度）：** CSS 屬性，用於設置元素的透明度，取值範圍從 0（完全透明）到 1（完全不透明）。
91. **Footer（底部）：** 網頁的底部區域，通常包含頁腳（footer）內容，如版權信息等。
92. **Position: Sticky（固定定位）：** CSS 屬性，用於將元素相對於視口固定在某個位置，通常在頁面滾動時保持在屏幕上方或下方。
93. **Padding（內邊距）：** CSS 屬性，用於設置元素內容區域與邊框之間的距離。
94. **Var（CSS 變數）：** CSS 中用來聲明和使用變數的語法，通常用於存儲重複使用的值。
95. **Margin（外邊距）：** CSS 屬性，用於設置元素與其周圍元素之間的空間。
96. **Scroll-margin-top（滾動邊距頂部）：** CSS 屬性，用於設置在滾動時元素頂部的外邊距，以確保元素顯示在視口中的特定位置，而不被其他元素擋住。
97. **BEM 命名法：** 一種用於為 HTML 和 CSS 中的類別和樣式命名的方法，有助於提高代碼的可讀性和可維護性。
98. **Grid 佈局：** CSS 中的佈局方式，使用網格（grid）來定義和控制頁面的結構，提供更靈活的設計選項。
99. **標記平坦化：** 在編寫 HTML 時，確保結構是平面的，而不是嵌套太深，以確保更好的可讀性和可維護性。
100. **CSS 變數（`var`）：** CSS 中用於聲明和使用變數的語法，有助於在整個樣式表中保持一致性。
101. **MDN：** Mozilla 開發者網（Mozilla Developer Network），提供 Web 開發相關的資源、文檔和參考。
102. **`display: contents`：**
   - 使元素的子元素在視覺上表現得像它們是直接的父元素的子元素的CSS屬性。

103. **CSS Grid：**
   - 一種用於網頁布局的CSS模塊，提供了更靈活的網格布局系統。

104. **BEM（Block Element Modifier）：**
   - 一種CSS類命名約定，用於創建清晰、模塊化和可維護的樣式。

105. **`grid-template-columns`：**
   - CSS屬性，定義網格列的大小、數量和/或名稱。

106. **`grid-template-areas`：**
   - CSS屬性，定義網格區域的布局。

107. **`display: grid`：**
   - CSS屬性，用於將元素變為網格容器。

108. **`grid-area`：**
   - CSS屬性，用於指定元素在網格容器中的位置。

109. **`var(--highlight-color)`：**
   - 使用CSS變量的方式，允許通過變量名引用顏色值。

110. **`font-weight: bold`：**
   - CSS屬性，用於設置字體的粗細。

110. **`height: 100%`：**
    - CSS屬性，將元素的高度設置為其父元素的百分比。

102. **`margin-bottom`：**
    - CSS屬性，設置元素的下外邊距。
103. **HTML元素：**
   - `<time>`：HTML5中表示時間的元素。
   - `<script>`：HTML中用於引入JavaScript代碼的標簽。
   - `id`屬性：HTML中用於唯一標識元素的屬性。
   - `class`屬性：HTML中用於為元素指定一個或多個類的屬性。

104. **CSS樣式：**
   - `display: grid`：將元素變為網格容器的CSS屬性。
   - `font-weight`：設置字體的粗細的CSS屬性。
   - `border`：設置元素邊框的CSS屬性。
   - `padding`：設置元素的內邊距的CSS屬性。
   - `margin`：設置元素的外邊距的CSS屬性。
   - `color`：設置文本顏色的CSS屬性。
   - `background-color`：設置背景顏色的CSS屬性。
   - `var()`：引用自定義屬性值（變量）的CSS函數。

105. **JavaScript代碼：**
   - `const`：聲明常量的JavaScript關鍵字。
   - `document`對象：表示整個HTML文檔的JavaScript對象。
   - `getElementById()`：通過元素的ID獲取頁面中的元素的JavaScript方法。
   - `Date`對象：處理日期和時間的JavaScript內置對象。
   - `setAttribute()`：設置元素的屬性值的JavaScript方法。
   - `textContent`屬性：獲取或設置元素的文本內容的JavaScript屬性。

106. **CSS動畫：**
   - `@keyframes`：創建動畫序列的CSS規則。
   - `animation`屬性：指定動畫的名稱、時長等的CSS屬性。

107. **響應式設計：**
   - `@media`查詢：根據不同的媒體設備或條件應用樣式的CSS規則。
   - `min-width`：媒體查詢中指定屏幕寬度最小值的條件。




