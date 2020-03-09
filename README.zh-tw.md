# 棋牌遊戲介紹

簡介我在 2019/10 ~ 2020/02 所完成的棋牌遊戲

其他語言版本: *[English](https://github.com/curtis567/FFUN_audio/blob/master/README.md)*, *[中文](https://github.com/curtis567/FFUN_audio/blob/master/README.zh-tw.md)*

# 目錄

 * [遊戲種類](#遊戲種類)
    * [百家樂](#百家樂)
      - [玩法規則](#百家樂玩法規則)
    * [萬人炸金花](#萬人炸金花)
      - [玩法規則](#萬人炸金花玩法規則)
    * [龍虎鬥](#龍虎鬥)
      - [玩法規則](#龍虎鬥玩法規則)
    * [萬人牛牛](#萬人牛牛)
      - [玩法規則](#萬人牛牛玩法規則)
  * [共用組件](#共用組件)
    * [遊戲上部區](#遊戲上部區)
    * [遊戲底部區](#遊戲底部區)
    * [選擇下注籌碼區](#選擇下注籌碼區)
    * [重置](#重置)
    * [聲音按鈕](#聲音按鈕)
    * [線上人數](#線上人數)
    * [自訂籌碼](#自訂籌碼)
    * [投注記錄](#投注記錄)
  * [使用資源](#使用資源)

# 遊戲種類

* ## 百家樂
> ## 🖥 [百家樂 影片](https://github.com/curtis567/FFUN_audio/blob/master/movie/BJL.mov)
* <h3>預載畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Preload.png "BJL_Preload")
* <h3>遊戲畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Game_View.png "BJL_Game_View")
* ### <h3>百家樂玩法規則
>> 點數規則(只看撲克牌點數,不看撲克牌花色)
  
| 牌面                        | 點數           
| :-------------:             |:-------------:|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Club2@3x.png" alt="Sample"  width="40" height="50"> ⇢ <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart9@3x.png" alt="Sample"  width="40" height="50">| 依據卡片顯示點數|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50">                     | 1點    |
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Diamond10@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubJ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubQ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartK@3x.png" alt="Sample"  width="40" height="50">        | 0點   |

>> 撲克牌點數總和

|閒二牌合計點數 | (閒家)   | 庄二牌合計點數 |(庄家)       
| :-------------:                  |:-------------:|:-------------:|:-------------:|
|0                                 |必須博牌|0              |必須博牌 |
|1                                 |必須博牌|1              |必須博牌 |
|2                                 |必須博牌|2              |必須博牌 |
|3                                 |必須博牌|3              |若閒家博得第三張牌是 8 點,庄家不得博牌|
|4                                 |必須博牌|4              |若閒家博得第三張牌是 0, 1, 8, 9 點,庄家不得博牌|
|5                                 |必須博牌|5              |若閒家博得第三張牌是 0, 1, 2, 3, 8, 9 點,庄家不得博牌|
|6                                 |不得博牌|6              |若閒家博得第三張牌是 6, 7 點,庄家必須博牌|
|7                                 |不得博牌|7              |不得博牌 |
|8                                 |定勝負|8                |定勝負 |
|9                                 |定勝負|9                |定勝負 |

>> 贏家顯示
 * 畫面(未開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Unopened.png "BJL_Unopened")
 * 畫面(開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Opened.png "BJL_Opened")
 
* ## 萬人炸金花
> ## 🖥 [萬人炸金花影片](https://github.com/curtis567/FFUN_audio/blob/master/movie/ZJH.mov)
* <h3>預載畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Preload.png "ZJH_Preload")
* <h3>遊戲畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Game_View.png "ZJH_Game_View")
* ### <h3>萬人炸金花玩法規則
>> 牌型大小
  
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_Boom@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SJ@3x.png" alt="ZJ_PkGroup_SJ"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_JH@3x.png" alt="ZJ_PkGroup_JH"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SZ@3x.png" alt="ZJ_PkGroup_SZ"  width="80" height="20">
  〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_DZ@3x.png" alt="ZJ_PkGroup_DZ"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_KP@3x.png" alt="ZJ_PkGroup_KP"  width="80" height="20">
  
>> 點數大小

  ```
  A > K > Q > J > 10 > 9 > 8 > 7 > 6 > 5 > 4 > 3 > 2
  ```
  
>> 花色大小

  ```
  ♠︎ > ♥︎ > ♦︎ > ♣︎
  ```
  
| card suit                       | Explanation          
| -------------             |:-------------|
|  <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_Boom@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>三張點數相同的牌; AAA 最大, 222 最小 |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartJ@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartQ@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartK@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SJ@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>三張花色相同的順子; AKQ 最大, A23 最小 |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart6@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart9@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_JH@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>三張花色相同的牌 ; AKJ 最大, 235 最小 |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Spade3@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart4@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Club5@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SZ@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>三張不同花色的順子 ; AKQ 最大, A23 最小 |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Diamond2@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_DZ@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>二張點數相同的牌 ; AAK 最大, 223 最小 |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Spade7@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart10@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubK@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_KP@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>三張點數花色不同的牌 ; AKJ 最大, 532 最小 |

>> 贏家顯示
 * 畫面(未開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Unopened.png "ZJH_Unopened")
 * 畫面(開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Opened.png "ZJH_Opened")
 
* ## 龍虎鬥
> ## 🖥 [龍虎鬥影片](https://github.com/curtis567/FFUN_audio/blob/master/movie/LHD.mov)
* <h3>預載畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Preload.png "LHD_Preload")
* <h3>遊戲畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Game_View.png "LHD_Game_View")
* ### <h3>龍虎鬥玩法規則
>> 點數規則(只看撲克牌點數,不看撲克牌花色)
  
  ```
  K > Q > J > 10 > 9 > 8 > 7 > 6 > 5 > 4 > 3 > 2 > A ;
  K 最大 , A 最小 , 
  ```

>> 贏家顯示
 * 畫面(未開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Unopened.png "LHD_Unopened")
 * 畫面(開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Opened.png "LHD_Opened")
 
* ## 萬人牛牛
> ## 🖥 [萬人牛牛影片](https://github.com/curtis567/FFUN_audio/blob/master/movie/NN.mov)
* <h3>預載畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Preload.png "NN_Preload")
* <h3>遊戲畫面
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Game_View.png "NN_Game_View")
* ### <h3>萬人牛牛玩法規則

>> 牌型
  
| 卡片                        | 解釋           
| :-------------:             |:-------------:|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_N1@3x.png" alt="Sample"  width="80" height="20"> ⇢ <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_N9@3x.png" alt="Sample"  width="80" height="20">| 五張牌中任三張和為10的倍數<br> 剩下二張牌和取個位數即為牛幾  |
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_NN@3x.png" alt="Sample"  width="80" height="20">                     | 五張牌中任三張和為10的倍數剩餘二張牌和也為10的倍數   |
|<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_nonN@3x.png" alt="Sample"  width="80" height="20">       | 五張牌中任三張和都不為10的倍數  |

>> 點數規則

| 牌型                        | 點數           
| :-------------:             |:-------------:|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Club2@3x.png" alt="Sample"  width="40" height="50"> ⇢ <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Diamond10@3x.png" alt="Sample"  width="40" height="50">| 依據卡片顯示點數|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50">                     | 1點    |
|<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubJ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubQ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartK@3x.png" alt="Sample"  width="40" height="50">        | 10點   |

>> 贏家顯示
 * 畫面(未開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Unopened.png "NN_Unopened")
 * 畫面(開啟)
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Opened.png "NN_Opened")
 
# 共用組件

  > ### 遊戲上部區
  >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Navbar.png "NavBar")
```
 ⦿ 功能由 左 -> 右
 
    1️⃣ 離開遊戲回首頁                      
    2️⃣ 遊戲標誌                                       
    3️⃣ 從api取得資料,在計算出倒數計時秒數                          
    4️⃣ 從api取得個遊戲獎期                 
    5️⃣ 遊戲彈窗
```
> ### 遊戲底部區
  >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Footer.png "Footer")
```
 ⦿ 功能由 左 -> 右
 
    1️⃣ 點擊清除購物車金額                       
    2️⃣ 點擊彈出儲值視窗                                      
    3️⃣ 點擊下注
```
 > ### 選擇下注籌碼區
  >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Bet_Chips.png "Bet_Chips")
```
 ⦿ 功能由 左 -> 右
 
    1️⃣ 點擊彈出自訂籌碼視窗                    
    2️⃣ 選擇下注籌碼金額
```
 > ### 重置
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Reset_Bet.png "Reset_Bet")
```
如果購物車裡有金額即可按下清除金額
```
 > ### 聲音按鈕
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Open_Sound.png "Open_Sound")
    ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Open_Effect.png "Open_Effect")
    ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Open_Background_Sound.png "Open_Background_Sound")
    ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Mute.png "Mute")
```
 ⦿ 功能由 左 -> 右
 
    1️⃣ 一開始狀態為播放聲音                      
    2️⃣ 點擊一次時關閉背景音樂開啟音效                                 
    3️⃣ 點擊二次時關閉音效開啟背景音樂                          
    4️⃣ 點擊三次時關閉聲音  
```
> ### 線上人數
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Online_Player.png "Online_Player")
```
每三秒從 api 取得線上人數
```
> ### 自訂籌碼
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Setting_Chips.png "Setting_Chips")
```
選擇五個籌碼金額後按確定即可變更牌面籌碼金額
```
> ### 投注記錄
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Bet_Record.png "Bet_Record")
```
顯示棋牌遊戲是否贏得獎金
```

# 使用資源

| 標題                       | 連結           
| -------------             |:-------------:|
| React.js                  | https://reactjs.org/ |
| redux                     | https://redux.js.org/     |
| styled-components         | https://styled-components.com/     |
| typescript                | https://www.typescriptlang.org/     |
| rxjs                      | https://rxjs-dev.firebaseapp.com/     |
| recompose                 | https://github.com/acdlite/recompose     |
| axios                     | https://github.com/axios/axios      |
| storybook                 | https://storybook.js.org/      |
| gsap                      | https://greensock.com/gsap/      |
| howler-audio-pool         | https://howlerjs.com/      |
