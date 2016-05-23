# backbone MVC框架学习笔记

## backbone备忘录

### Backbone.Events(事件)
- **on**：object.on(event, callback, [context])别名: bind
- **off**：object.off([event], [callback], [context])别名: unbind
- **trigger**：object.trigger(event, [*args])
- **once**：object.once(event, callback, [context])
- **listenTo**：object.listenTo(other, event, callback)
- **stopListening**：object.stopListening([other], [event], [callback])
- **listenToOnce**：object.listenToOnce(other, event, callback)


## 参考文献：
[backbone中文手册](http://www.css88.com/doc/backbone/)

## 开发过程中遇到的问题
1、new一个视图时，报错`backbone.js:1133 Uncaught TypeError: Expecting a function in instanceof check, but got undefined`，原因是在加载Backbone之前应先加载jQuery。[参考地址](http://stackoverflow.com/questions/10411736/error-while-creating-a-backbone-js-view-expecting-a-function-in-instanceof-che/10411933)
