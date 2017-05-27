# 製作步驟

## preface

建議先重設 word，這樣才不會衝到 word 的格式，可以參照 [重設 word 教學](https://support.microsoft.com/zh-tw/help/822005/how-to-reset-user-options-and-registry-settings-in-word)

## Steps

1. 先去[系上網站](https://www.cs.nctu.edu.tw/cswebsite/education/graduate/course)依照系所 下載 畢業相關表格下載 
2. 將 `4. 網路工程研究所論文封面 （表4）` 和 `6. 網路工程研究所論文書名頁 （表6）` 這兩頁貼上
3. 會發覺空白字元的字距怪怪的，到 `段落`->`中文印刷格式`->`選項`->`進階` 把 `調整半形字和全形字的字距比例` 勾起來即可

<img src="../fixtures/adjust-distance-between-character.png" width="400px">

4. 開始建立樣式

建議不要直接修改預設的樣式
用繼承的方式去建立一個新的，再修改比較好
比如說: 標題1 -> 自訂標題1


5. 建立多層次清單

先建立 4 個樣式

- 多層次清單標題1
- 多層次清單標題2
- 多層次清單標題3
- 自訂內文

多層次清單會綁定樣式，所以要建立新的自訂樣式出來
以下是建議的多層次清單架構

1. 多層次清單標題1

自訂內文

1.1. 多層次清單標題2

自訂內文

1.1.1. 多層次清單標題3

6. 產生目錄

再 `參考資料` 功能表依序產生三個目錄

- 目錄
- 圖表目錄
- 表格目錄

要是有更改文字記得要更新目錄

7. 插入頁碼

# 幫圖片或表格標示文字

插入圖片或表格後，到 `參考資料` -> `插入標號` 插入文字

之後用 `參考資料` -> `交互參照` 就可以在文中引用

**注意圖片通常是文字在圖片下面，表格是文字在上**

**記得更新圖表目錄**

<img src="../fixtures/figure.png" width="250px"> <img src="../fixtures/table.png" width="250px">

# 疑難雜症解法

## 表格會跨頁

到 `表格工具` -> `版面配置` -> `內容` -> `列` -> 把 `允許列超越頁分隔線` 取消勾選

<img src="../fixtures/table-cross-page.png" width="250px">
