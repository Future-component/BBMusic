# BBMusic
> 音频插入

## Example
[Demo地址:https://future-component.github.io/BBMusic/example/index.html](https://future-component.github.io/BBMusic/example/index.html)

## 实例
依赖样式
```html
<link rel="stylesheet" href="./assets/index.css">
```

依赖jQuery
```js
<script src="https://cdn.bootcss.com/jquery/3.3.1/jquery.js"></script>
<script src="../index.js"></script>
```

初始化
```js
var bbMusic = new BBMusic('music');
bbMusic.init();
```

初始化参数
```js
{
  autoPlay: true,
  poster: './assets/cover.jpg',
  name: '爱上幼儿园',
  author: '张庭',
  src: './assets/1.mp3',
}
```