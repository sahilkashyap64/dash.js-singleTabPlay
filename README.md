# dash.js-singleTabPlay
# Single browser tab video play


## Lib used
 index.html   [Credits to Hasan Alibegić](https://github.com/halibegic)
| Lib | Version | Use|
| ------ | ------ |-----|
| dash.all.min.js | ^v3.1.2 | to play dash file|
| dash.mss.min.js | ^v3.1.2 | to play smooth streaming file|
| ControlBar.js |  | to show seek bar and quality control|
| duel.js | ^v1.2.7 | to interact with tabs|

##  Dual.js.

  - [Dual.js](https://github.com/studentIvan/dueljs)
  - Your active tab act as Master and all the other tab changes to  Slave
  - Mainly used for communucating with neighbouring tabs

## Using Dual.js to limit the player from being played on other tab.

  - Using dash.js player event  to see in video is playing ,
  - and if it get's played on neighbouring tab, 
  - broadcast to stop all the other player instance in other tabs
  
  ## [Test Player](https://sahilkashyap64.github.io/dash.js-singleTabPlay)
 - Open test player in multiple tabs
 - And try playing them
   
   
