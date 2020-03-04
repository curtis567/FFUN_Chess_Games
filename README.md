
# Chess Games Introduction

Introduction to the chess games I made in 2019/10 ~ 2020/02

Read this in other languages: *[English](https://github.com/curtis567/FFUN_audio/blob/master/README.md)*, *[中文](https://github.com/curtis567/FFUN_audio/blob/master/README.zh-tw.md)*

# Table of Contents
  
  * [Games](#games)
    * [BJL](#bjl)
      - [Rules](#bjl-rules-of-play)
    * [ZJH](#zjh)
      - [Rules](#zjh-rules-of-play)
    * [LHD](#lhd)
      - [Rules](#lhd-rules-of-play)
    * [NN](#nn)
      - [Rules](#nn-rules-of-play)
  * [Common Component](#common-component)
    * [NavBar](#navbar)
    * [Footer](#footer)
    * [Bet Chip](#bet-chip)
    * [Reset Bet](#reset-bet)
    * [Sound Button](#sound-button)
    * [Online Player](#online-player)
    * [Setting Chips](#setting-chips)
    * [Bet Record](#bet-record)
  * [Resources](#resources)

# Games

* ## BJL 
> ## 🖥 [BJL film](https://github.com/curtis567/FFUN_audio/blob/master/movie/BJL.mov)
* <h3>preload view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Preload.png "BJL_Preload")
* <h3>Games view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Game_View.png "BJL_Game_View")
* ### <h3>BJL Rules of play
>> Rules of number(Don't look at the poker card suit, just look at the points)
  
| card                        | number           
| :-------------:             |:-------------:|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Club2@3x.png" alt="Sample"  width="40" height="50"> ⇢ <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart9@3x.png" alt="Sample"  width="40" height="50">| According to the number on the card|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50">                     | A is one point    |
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Diamond10@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubJ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubQ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartK@3x.png" alt="Sample"  width="40" height="50">        | 10, J, Q, k is zero point   |

>> Poker cards total points

| Bookmaker two cards total points | (Bookmaker)   | Player two cards total points |(Player)       
| :-------------:                  |:-------------:|:-------------:|:-------------:|
|0                                 |Must play card|0              |Must play card |
|1                                 |Must play card|1              |Must play card |
|2                                 |Must play card|2              |Must play card |
|3                                 |Must play card|3              |if Player third poker card is 8 point,the bookmaker no play card |
|4                                 |Must play card|4              |if Player third poker card is 0, 1, 8, 9 point,the bookmaker no play card |
|5                                 |Must play card|5              |if Player third poker card is 0, 1, 2, 3, 8, 9 point,the bookmaker no play card |
|6                                 |No play card|6              |if Player third poker card is 6 or 7 point,the bookmaker must play card |
|7                                 |No play card|7              |No play cards |
|8                                 |Determine the outcome|8              |Determine the outcome |
|9                                 |Determine the outcome|9              |Determine the outcome |

>> Show winner
 * Unopened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Unopened.png "BJL_Unopened")
 * opened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/BJL_Opened.png "BJL_Opened")
 
* ## ZJH
> ## 🖥 [ZJH film](https://github.com/curtis567/FFUN_audio/blob/master/movie/ZJH.mov)
* <h3>preload view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Preload.png "ZJH_Preload")
* <h3>Games view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Game_View.png "ZJH_Game_View")
* ### <h3>ZJH Rules of play
>> Poker card size
  
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_Boom@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SJ@3x.png" alt="ZJ_PkGroup_SJ"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_JH@3x.png" alt="ZJ_PkGroup_JH"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SZ@3x.png" alt="ZJ_PkGroup_SZ"  width="80" height="20">
  〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_DZ@3x.png" alt="ZJ_PkGroup_DZ"  width="80" height="20"> 〉 <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_KP@3x.png" alt="ZJ_PkGroup_KP"  width="80" height="20">
  
>> Point number size

  ```
  A > K > Q > J > 10 > 9 > 8 > 7 > 6 > 5 > 4 > 3 > 2
  ```
  
>> Poker card suit size

  ```
  ♠︎ > ♥︎ > ♦︎ > ♣︎
  ```
  
| card suit                       | Explanation          
| -------------             |:-------------|
|  <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_Boom@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>Three cards with the same points; AAA max, 222 min |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartJ@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartQ@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartK@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SJ@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>Straight Flush of Three cards; AKQ max, A23 min |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart6@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart9@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_JH@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>Flush of Three card ; AKJ max, 235 min |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Spade3@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart4@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Club5@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_SZ@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>Straight of Three card ; AKQ max, A23 min |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartA@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Diamond2@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_DZ@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>Two cards with the same points ; AAK max, 223 min |
<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Spade7@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Heart10@3x.png" alt="Sample"  width="40" height="50"><img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubK@3x.png" alt="Sample"  width="40" height="50">| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJ_PkGroup_KP@3x.png" alt="ZJ_PkGroup_Boom"  width="80" height="20"><br>Three cards with different suits ; AKJ max, 532 min |

>> Show winner
 * Unopened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Unopened.png "ZJH_Unopened")
 * opened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/ZJH_Opened.png "ZJH_Opened")
 
* ## LHD
> ## 🖥 [LHD film](https://github.com/curtis567/FFUN_audio/blob/master/movie/LHD.mov)
* <h3>preload view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Preload.png "LHD_Preload")
* <h3>Games view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Game_View.png "LHD_Game_View")
* ### <h3>LHD Rules of play
>> Rules of number(Don't look at the poker card suit, just look at the points)
  
>> Point number size

  ```
  K > Q > J > 10 > 9 > 8 > 7 > 6 > 5 > 4 > 3 > 2 > A ;
  K Max , A Min , 
  ```

>> Show winner
 * Unopened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Unopened.png "LHD_Unopened")
 * opened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Opened.png "LHD_Opened")
 
* ## NN
> ## 🖥 [NN film](https://github.com/curtis567/FFUN_audio/blob/master/movie/NN.mov)
* <h3>preload view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Preload.png "NN_Preload")
* <h3>Games view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Game_View.png "NN_Game_View")
* ### <h3>NN Rules of play

>> Card type
  
| card                        | Explanation           
| :-------------:             |:-------------:|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_N1@3x.png" alt="Sample"  width="80" height="20"> ⇢ <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_N9@3x.png" alt="Sample"  width="80" height="20">| Sum of any three of the five cards are  multiple of 10,<br> Sum of other two cards and take single digit  |
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_NN@3x.png" alt="Sample"  width="80" height="20">                     | Sum of any three of the five cards and other two cards are  multiple of 10   |
|<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_nonN@3x.png" alt="Sample"  width="80" height="20">       | Sum of any three of the five cards are not a multiple of 10   |

>> Rules of number

| Card type                        | number           
| :-------------:             |:-------------:|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Club2@3x.png" alt="Sample"  width="40" height="50"> ⇢ <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/Diamond10@3x.png" alt="Sample"  width="40" height="50">| According to the number on the card|
| <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/SpadeA@3x.png" alt="Sample"  width="40" height="50">                     | A is one point    |
|<img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubJ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/ClubQ@3x.png" alt="Sample"  width="40" height="50">     <img src="https://github.com/curtis567/FFUN_audio/blob/master/Image/HeartK@3x.png" alt="Sample"  width="40" height="50">        | J, Q, k is ten point   |

>> Show winner
 * Unopened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Unopened.png "NN_Unopened")
 * opened
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Opened.png "NN_Opened")
 
# Common Component

  > ### NavBar
  >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Navbar.png "NavBar")
```
 ⦿ Features left -> right
 
    1️⃣ leave game go to home page                       
    2️⃣ games logo                                       
    3️⃣ countdown from api date                          
    4️⃣ games award number from api date                 
    5️⃣ games dialog
```
  > ### Footer
  >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Footer.png "Footer")
```
 ⦿ Features left -> right
 
    1️⃣ click to clear shopping cart money                       
    2️⃣ click to pop up the stored value dialog                                      
    3️⃣ click to bet amount
```
 > ### Bet Chip
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Bet_Chips.png "Bet_Chips")
```
 ⦿ Features left -> right
 
    1️⃣ click to pop up the select chips dialog                     
    2️⃣ click to select balance of chips
```
 > ### Reset Bet
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Reset_Bet.png "Reset_Bet")
```
If the cart has an amount, you can place a bet once
```
 > ### Sound Button
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Open_Sound.png "Open_Sound")
    ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Open_Effect.png "Open_Effect")
    ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Open_Background_Sound.png "Open_Background_Sound")
    ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Mute.png "Mute")
```
 ⦿ Features left -> right
 
    1️⃣ Play sound in original state                      
    2️⃣ Click once to turn off background music and turn on the sound effect                                     
    3️⃣ Click twice to turn off sound effect and turn on the background music                           
    4️⃣ Three clicks to turn off game sound
```
> ### Online Player
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Online_Player.png "Online_Player")
```
Get Online player data from api every three seconds
```
> ### Setting Chips
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Setting_Chips.png "Setting_Chips")
```
Select five chips and press Confirm
```
> ### Bet Record
 >> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/Bet_Record.png "Bet_Record")
```
Show if the chess game has a prize
```
# Resources

| Title                     | Link           
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
