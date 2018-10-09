# Double click to Highlight
This script is based on [双击选中高亮](https://greasyfork.org/zh-CN/scripts/36057-ac-双击选中高亮).

When we using webBrowser to find some solution on some problem, There are too many information it's to hard to grasp the main idea. 


But now you can use double click to the words you select, you can not only highlight the main info, you can quickly find the same info which be selected.


Take Python document as an example, you can do it like this.

![example.png](https://github.com/JustYummy/click2highlight/blob/master/pic/example.png)

There are **five** highlight color on the colorList, If you want you can change the color by youself.   
```javascript
var colorList = ["#FFFF80", "#FF9980", "#FF3380", "#72f94c", "#a65bff"];
```
Because we don't always want to underline to much! So we can just 5 double click 5 times to mark the word.
Still! you can change the number you want.
```javascript
if(countNum > 5){   //change this number to whatever you want. 
  unHighLightAll_Text();
  textSet = "";
  countNum = 0;
}
```

## How to use?
1. Install the Tampermonkey on your web browser on [tampermonkey.net](https://tampermonkey.net)
2. Open the Dashboard and add a new script.
3. Copy the code and paste to the new script.
