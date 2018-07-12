# 編輯快捷鍵及常用快捷鍵

Yu Writer 的快捷鍵經過反覆推敲和設計，快捷鍵的組合通常有規律可循，因此很容易記住這些快捷鍵。熟悉一些快捷鍵能讓你的寫作過程更順手。

你可以點擊應用程序的主菜單，在那裏可以查看各個功能的快捷鍵。

> 注：macOS 系統比裏 Windows/Linux 系統多了一個 `Command` 鍵，為簡單起見，下面以 macOS 系統來介紹快捷鍵。如果沒有特別註明，一般 `Command` 鍵對應着 Windows/Linux 系統之下的 `Ctrl` 鍵，比如 `Command + C` 對應的是 `Ctrl + C`。

## 設置文字格式的快捷鍵

設置文字粗體、斜體、下劃線的快捷鍵分別為 `Command+B`、`Command+I`、`Command+U`，在不同的情況下按這些快捷鍵會有不同的作用：

* 如果當前沒有選中任何文字，這時按下這些快捷鍵會自動錄入一對符號，比如按下 `Command+B` 會自動錄入 `****`，同時光標被移到符號中間，此時輸入文字會被表示為粗體；
* 如果當前已選中一些未設置格式的文字，這時按下這些快捷鍵會把選中的文字前後加上相應的格式符號；
* 如果當前光標位於已設置格式的文字之中的任意位置，無論是否選中文字，這時按下這些快捷鍵會取消相應的格式。比如有粗體文字 `**Hello World**`，光標處於第一個星號和最後一個星號之間的任意位置，此時按下 `Command+B` 會讓前後所有星號消失，文字變成 `Hello World`。

簡單來説，這些快捷鍵同時具有 “自動錄入格式符號”、“設置格式” 和 “取消格式” 的作用。

 > 跟一般的文字處理軟件不同，如果要取消格式，你不需要事先把格式文字選中，只需把光標放在格式文字之中任意位置，再按相應的快捷鍵即可。

另外還有設置刪除線、標記高亮以及行內代碼（Inline Code）的快捷鍵，分別為 `Command+S`、`Command+M`、`Command+C`。

## 設置標題的快捷鍵

* 使用 `Command+1` 到 `Command+6` 快捷鍵設置當前行成為 1 級到 6 級標題。
* 使用 `Command+反引號` 快捷鍵設置當前行成為當前級別的標題。
* 當光標位於行尾時，使用快捷鍵 `Alt+Enter` 設置當前行成為當前級別的標題。
* 使用 `Shift+Command+反引號` 快捷鍵將當前標題轉成普通段落文字，即取消標題。

### 更改標題級別的快捷鍵

當光標處於標題的任意位置時，使用 `Tab` 和 `Shift+Tab` 鍵分別增加或降低標題級別，

Yu Writer 能正確決定標題是採用 Setex 風格還是 Atx 風格，比如某篇文檔使用 Setex 風格設置 2 級標題，則當你在某行文字按下 `Command+2` 快捷鍵或者使用 `Tab` 鍵從 1 級標題降低為 2 級標題時，它會自動採用 Setex 風格。

## 插入鏈接代碼的快捷鍵

使用 `Command+K` 可以快速插入鏈接代碼 `[link title](https://)`，並且 `link title` 初始處於被選中狀態。

> 你可以使用 `Tab` 鍵，`Shift+Tab` 或者 `Enter` 鍵讓光標在鏈接標題和鏈接目標之間跳轉。

該快捷鍵在不同的情況下有不同的作用：

* 如果光標位於鏈接代碼文字之中的任意位置，按 `Command+K` 會取消鏈接，只保留鏈接標題；
* 如果先選中普通文字再按 `Command+K`，則選中的文字會自動成為鏈接代碼當中的鏈接標題。
* 如果光標處於一個普通 URL 文字之內，這時再按  `Command+K`，則 URL 會自動被填進鏈接代碼當中的鏈接目標位置。

## 插入圖片代碼的快捷鍵

使用 `Command+G` （在 Windows/Linux 系統裏是 `Ctrl+M`）可以快速插入圖片代碼 `[image title](https://)`，並且 `image title` 初始處於被選中狀態。

該快捷鍵的其他作用同插入鏈接代碼的快捷鍵，所以這裏就不再贅述了。

## 插入列表項、有序列表項、任務列表項的快捷鍵

快捷鍵分別為 `Command+L`、`Shift+Command+L` 和 `Command+T`，在不同的情況下按這些快捷鍵會有不同的作用：

* 光標位於空行，這時按下這些快捷鍵會自動錄入相應類型列表項的開始符號，比如 `*`、 `1.` 和 `* [ ]` 等；
* 光標所在的行已有文字，這時按下這些快捷鍵時會把該行文字自動轉為列表項。Yu Writer 會自動檢測上下文，以補上正確的開始符號，比如上一行是 `3. Hello`，當前行是 `World`，這時按下 `Shift+Command+L` 會讓當前行變為 `4. World`。
* 當前選中多行文字，這時按下這些快捷鍵時會把選中的幾行文字自動轉為列表項。

### 更改任務列表項狀態的快捷鍵

如果當前行是任務列表項，使用快捷鍵 `Shift+Command+T` 可以輪流切換 “完成” 和 "未完成“ 兩種狀態。

## 更改列表項層次級別的快捷鍵

同更改標題級別的快捷鍵。

## 行操作快捷鍵

Yu Writer 提供了基於行為單位的編輯操作，因為一行即一個段落，所以行操作同時也是段落操作。

### 行號的顯示

有時我們在編輯很長的文檔，又或者需要跟別人交流溝通同一個文檔時，通過行號可以精確定位。顯示行號的方法是，在編輯文檔時按下鍵盤的 `Ctrl` 鍵（在 Windows/Linux 系統裏是 `Ctrl + Alt` 鍵），編輯框左側會顯示每一行文字的行號。

### 跳到指定行號

使用快捷鍵 `Ctrl+G` 可以呼出用於輸入行號的彈出窗口，在彈出窗口中輸入行號再按回車就會跳到相應的行，如果輸入例如 `34:12` 這樣的內容，則表示跳轉到第 34 行的第 12 列文字。

### 跳到光標上一次所在的行

Yu Writer 會記錄光標所在行的行號的變化，使用快捷鍵 `Shift+Ctrl+G` 可以跳到之前光標所在的行。

### 上移或下移行

使用快捷鍵 `Ctrl+Command+上箭頭`可以把當前行往上移動一行。使用快捷鍵 `Ctrl+Command+下箭頭` 則可以把當前行往下移動一行。通過上下移動行的快捷鍵，可以很方便地調整行的順序，或者用於調整表格的行的順序。

另外，可以選擇多行文字，然後挪動時將會是幾行文字一起移動。

### 刪除行

使用快捷鍵 `Ctrl+Shift+K` 可以刪除一行或者選中的多行文字。

## 書籤的快捷鍵

TODO

## 標籤頁的快捷鍵

當你同時編輯多個文檔時，這時會打開多個標籤頁，使用下面的快捷鍵可以切換標籤頁：

* `Ctrl+Tab` 切換到下一個標籤頁；
* `Shift+Ctrl+Tab` 切換到上一個標籤頁；
* `Ctrl+1` 到 `Ctrl+9` 切換第 1 個到第 9 個標籤頁。

## Emacs/Bash 風格快捷鍵

這部分的快捷鍵僅在 macOS 系統裏有效，因為在 macOS 系統裏大部分常規的快捷鍵都綁定到 `Command`，所以就空出了 `Ctrl` 鍵。

### 移動光標類

* `Ctrl + A` 移動到行的開頭
* `Ctrl + E` 移動到行的末尾
* `Ctrl + B` 往後移動，同左箭頭
* `Ctrl + F` 往前移動，同右箭頭
* `Ctrl + N` 往下移動，同下箭頭
* `Ctrl + P` 往上移動，同上箭頭
* `Ctrl + Alt + F` 往前移動一個詞，同 `Alt+右箭頭`
* `Ctrl + Alt + B` 往後移動一個詞，同 `Alt+左箭頭`

### 刪除字符類

* `Ctrl + H` 刪除光標之前的字符
* `Ctrl + D` 刪除光標所在位置的字符
* `Ctrl + K` 刪除一行文字光標之後的字符
* `Ctrl + T` 交換光標當前位置以及光標之後的一個字符
* `Ctrl + Y` 粘貼上面刪除掉的字符

## Linux Ternimal 風格的複製粘貼

* 粘貼 `Shift + Ins`
* 複製 `Ctrl + Ins`

## 給手動保存文件強迫症者的快捷鍵

* `Command+S`，按了這個快捷鍵之後會讓文件內容寫入到儲存媒介（硬盤或者 SSD 等）。默認情況下文檔每隔 60 秒會自動寫入一次，當這個快捷鍵被按下之後，則會立即寫入。當然了，兩種操作都是在文件內容發生改變之後才會真正被執行。