# css3-dialog

标签（空格分隔）： 弹框 dialog

---

不同的浏览器有都有各自有别于其它浏览器的弹框alert和confirm，如果想让网站在不同的浏览器上展示相同的弹框，那就别用浏览器自带的，可以通过插件定义自己独特的弹框。
css3-dialog就是一个基于css3的弹框插件，使用时不用引入其它框架，只需要在页面引入js和css即可。注意，本插件的引用dialog.js的script标签一定要放在body标签里面或后面，不能放在head标签里。如下为使用弹框的方法：

    //msg是弹框显示的信息，callback是一回调函数，表示点击弹框中的确定按钮后需要执行的事件，可为空
    alertMsg(msg, callback);
    //同上
    confirmMsg(msg, callback);
    
本插件的样式可自行在dialog.css中修改，默认样式如图所示：![此处输入图片的描述][1]

具体效果请看demo：[点击此处查看demo][2]


  [1]: https://raw.githubusercontent.com/lunyong/css3-dialog/master/img/alert.png
  [2]: http://lunyong.github.io/demo/css3-dialog/