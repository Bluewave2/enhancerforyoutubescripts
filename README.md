# Enhancerforyoutubescripts
Scripts for 
Enhancer for Youtube


## Center youtube controls under player in theather mode (instead of left align)
> Code: Gets stylesheet index 0, adds rule that centers control flexbox.
```javascript
var sheet = window.document.styleSheets[0];
sheet.insertRule('ytd-watch-flexy[flexy]:not([full-bleed-player][full-bleed-no-max-width-columns]) #columns.ytd-watch-flexy { justify-content: center; }', sheet.cssRules.length);
```
-------
