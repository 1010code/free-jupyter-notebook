# free-jupyter-notebook

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/1010code/free-jupyter-notebook/master)

## 線上免費 Jupyter Notebook 資源一覽
今天會介紹四個我的口袋名單，放心每一個服務都是免費的～ 如果平時在外面沒隨身攜帶自己的筆電但想展示你的程式可以透過以下資源來存取你的Code，超方便！
- Google Colaboratory
- Microsoft Azure
- Kaggle
- mybinder (與GitHub專案連動)

## 1. Kaggle
Kaggle 是一個數據建模和數據分析競賽平台，你可以不定時在上面看到許多競賽，也可以看到許多公司將他們未解決的資料集公開分享給各位讓大家一起來解決。除此之外 Kaggle 使用者也可以公開分享自己的 kernel 讓大家參考你的程式，幸運的話你可以在這裡挖到寶。
註冊成功後會看到此畫面(隨著時間可能頁面會稍微長得不一樣)，點選左邊欄 Notebooks 就可以看到自己的程式以及他人分享的程式。點選右上角 New Notebook 即可建立一個新的專案，這裡你可以選擇 R 語言或 Python。
新建一個新的 NoteBook這邊我提供一個簡單線性回歸的範例，各位可以直進入此連結 Copy and Edit 到自己的帳號中。 傳送門

## 2. Google Colaboratory
我們都簡稱 Colab。這個平台是 Google 所維護的服務，他會與你的 Google Drive 連動，這也意味著你得程式碼將會備份在雲端硬碟中。基本上你只要打開雲端硬碟在安裝 Chrome 的相關套件就可以使用了～
這裡我也提供一個範例程式，各位可以跟著下面步驟並Fork到自己的雲端硬碟中。
傳送門
若是初次使用的讀者，此時若沒看到 Google Colaboratory 的選項表示你的電腦尚未安裝插件。接著點選更多應用程式來下載。
之後會彈出一個視窗，在搜尋欄打上 colab 就會跳出相關插件。點進去後點擊安裝來下載應用(PS.以上步驟要在Google Chrome瀏覽器下完成)。
安裝完成後點選使用「Google Colaboratory」開啟。開啟後就會看到一個範例程式，因為這支程式是儲存在我的雲端硬碟中，若你想執行的話點選 File → Save a copy in Drive 將程式複製到你的雲端硬碟中。
如果你的專案需要使用到GPU的話可以點選 Runtime → Change runtime type。點擊進去設定後即可使用 GPU 或 TPU。

## 3. Microsoft Azure
微軟的 Azure Notebooks 目前還愛處於開發測試階段，或許還不是很穩，不過我們還是可以觀望。他的優點在於他能夠直接跟 GitHub 的專案連動，版本控制對工程師可說是非常重要的一環，大家應該沒忘記微軟早在 2018 年宣布收購 GitHub 的消息吧！
各位可以參考範例：傳送門
打開後應該會是 tree 結構的 Notebook，如果想換成下圖這樣的編輯環境可以在網址後面的 /tree 改成 /lab 就會跟下圖一樣了。由於現在還屬於測試階段，僅提供各位一個雲端服務的參考。日後發布正式版有多功能我會再詳細介紹他。

## 4. mybinder
mybinder 跟微軟的 Azure 有點異曲同工之妙。mybinder 主要是可以貼上 GitHub 的專案網址，接著他會透過 Docker 建立一個虛擬映像幫你在此平台上建立一個虛擬環境。他是免費的服務，But…但是！許多套件你要自行安裝例如 sklearn、OpenCV、TensorFlow……等。此服務比較適合在當你開發一個新的演算法並放在 GitHub 上，且需要提供一個測試環境給使用者做 live demo。個人不推薦在上面直接開發。
以上四個免費雲平台都可以讓開發者在網路上自由的開發，當然免費的多少少些不便之處以及使用上限制。不過我們能有效地善用網路資源的確可以減少我們在開發上的負擔！
