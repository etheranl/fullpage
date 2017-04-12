# fullpage
simple fullpage plugin

[demo](http://imhaoran.wang/fullpage)
## 使用方法
1. 引入
`<script src="your_path/q-fullpage.js"></script>`
2. 初始化
```JavaScript
new FullPage({
  element: document.querySelector('#fullpage'),  //对应的dom节点
  duration: '1s',   //动画时间
  onLeave(next){
    console.log(next);   //下一页的index
  }   //离开时触发
})
```

3. 其它

请自行设置节点高度为100% -。-

## License
 WTFPL (Do What the Fuck You Want To Public License)
 
## Inspired
- [FullPage.js](https://github.com/alvarotrigo/fullPage.js)
- [FrankFang](https://github.com/FrankFang)
