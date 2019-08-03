# WeChat-first-app
A very basic WeChat app

# Here are some notes I took:
https://workshop.wechatdevelopers.com/
* IDE	
* developers.weixin.qq.com - official docs

## Important files

* Index.wxml
* App.js
   * Note can be typescript or javascript
* Wxml: 	Weixin html 
* wxss: 	Weixin css 

## WXML to corresponding HTML tag
* ```<view>``` ->	```<div>```
* ```<navigator>``` ->	```<a>```
* ```<image>``` ->	```<img>```
* ```<text>``` ->	```<p>```
* ```<block>``` ->	No rendering, but can accept control

### App.wxss
* Applies to all
* Has .container element
* Each page also has a .wxss file that will dictate the style of the related .wxml
* Background image - must be hosted online and loaded using .banner -> background-image
