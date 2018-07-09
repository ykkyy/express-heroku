# express-heroku

## 專案目錄架構

* `.gitignore` 用來告訴 git，哪些檔案不要受到版本管理
* `README.md` 用來編寫你現在看到的這份文件，使用 [markdown](http://markdown.tw/) 格式
* `index.js` 非常簡單的 [express](http://expressjs.com/) 專案
* `package.json` 用來描述這個專案的檔案，包含專案名稱、作者、授權、相依的套件等等的資訊。

## 步驟0. Fork 專案

在這個步驟裡，我們要用一個已經寫好的專案 [exress-heroku](https://github.com/ntu-csie-train/express-heroku)，並按下 Fork 將這個專案複製到自己的 github 帳號底下。

----
* 圖1. 按下 Fork 按鈕
  ![Imgur](http://i.imgur.com/vZzkceL.png)

* 圖2. Fork 進行中
  ![Imgur](http://i.imgur.com/vPeTujp.png)

* 圖3. 專案已經複製一份到你的帳號底下
  ![Imgur](http://i.imgur.com/hRtKI6f.png)


## 步驟1. 建立 Heroku 帳號，並綁定 Github 帳號

在這個步驟裡，我們要新建一個 Heroku 帳號，並把在部署（deploy）設定的地方，選擇使用 Github 專案。

----
* 圖1. 建立一個 Heroku App，名稱可以不填，他會自動產生。
  ![Imgur](http://i.imgur.com/nJe6h2s.png)

* 圖2. 新增 Heroku App 成功後，會出現部署的設定，往下捲的地方可以看到部署的方法有三種，選擇 Github，並選擇專案名稱為 `express-heroku` 的專案，然後按下 `connect`
  ![Imgur](http://i.imgur.com/Bh707e8.png)

* 圖3. 並啟用自動部署，這樣每當 Github 專案有新的更新進入 master 分支之後，Heroku 就會自動更新。因為第一次設定他不會自動發布，所以到手動部署（Manual deploy）區塊的地方，選擇 `master ` 然後按下 `Deploy Branch` ，接著等待他完成部署。
  ![Imgur](http://i.imgur.com/EyLrl6G.png)

* 圖4. 這是按下 `Enable Automatic Deploys` 後的成功畫面。
  ![Imgur](http://i.imgur.com/WuXmP9L.png)

* 圖5. 等待部署中。
  ![Imgur](http://i.imgur.com/5CDaB37.png)

* 圖6. 部署完成，可以點 `view` 這個按鈕來瀏覽網站。
  ![Imgur](http://i.imgur.com/3sK1fnU.png)

* 圖7. 網址為 `https://{App Name}.herokuapp.com` ，也可以在設定頁面找到網址連結。
  ![Imgur](http://i.imgur.com/0DKyzcm.png)