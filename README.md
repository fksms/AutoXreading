# Xreading自動化ツール（JavaScript利用）

<br>

## 準備
通信環境が良好な場所で以下を実行してください。<br>
まず「F12」キーを押して開発者ツールを開きましょう。<br>
また、xreading.comからのポップアップを許可しておきましょう。


![準備](https://github.com/daianjibetu/Images/blob/master/AutoXreading/preparation.png)

<br><br>
## 読書時間稼ぎ
Reading画面で、「delay.js」の中身を全てコンソールに張り付けて「Enter」キーを押してください。タブが大量に生成されます。一定時間経過後、タブが自動的に閉じるので何も触らず待機してください。


![読書時間稼ぎ](https://github.com/daianjibetu/Images/blob/master/AutoXreading/delay.png)


読書時間の調整には
```javascript
var tabs = 60; //開くタブの数    
var time = 60; //待機時間[sec]
```
を調整してください。

<br><br>
## 最後まで読み飛ばし
Reading画面で、「skip.js」の中身を全てコンソールに張り付けて「Enter」キーを押してください。ページを自動的に送ります。最終ページになるまで待機してください。


![最後まで読み飛ばし](https://github.com/daianjibetu/Images/blob/master/AutoXreading/skip.png)

<br><br>
## 自動解答
Quiz画面で、「solve.js」の中身を全てコンソールに張り付けて「Enter」キーを押してください。タブがいくらか生成されます。一定時間経過後、タブが自動的に閉じるので何も触らず待機してください。


![自動解答](https://github.com/daianjibetu/Images/blob/master/AutoXreading/solve.png)
