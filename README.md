
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
  * [Resources](#resources)

# Games

* ### BJL
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

* ### ZJH
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
  
* ### LHD
* <h3>preload view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Preload.png "LHD_Preload")
* <h3>Games view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/LHD_Game_View.png "LHD_Game_View")
* ### <h3>LHD Rules of play
  
* ### NN
* <h3>preload view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Preload.png "NN_Preload")
* <h3>Games view
>> ![GITHUB]( https://github.com/curtis567/FFUN_audio/blob/master/Image/NN_Game_View.png "NN_Game_View")
* ### <h3>NN Rules of play

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
