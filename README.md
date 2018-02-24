# rem实现手机相册自适应
#### 由于1rem = 其设备的宽度，利用这一点，可以加上这一行代码实现自适应
```javascript
 //这里除以3并不适用于所有，需要根据页面的效果做相应的改变
 document.getElementsByTagName("html")[0].style.fontSize = document.documentElement.clientWidth/3 + "px";
```
这样一来，假设屏幕的宽度等于600px, 1rem = 600/3=200px
[rem实现手机相册代码演示](https://github.com/Jennifer1216/rem/edit/master/album/photo.html)
