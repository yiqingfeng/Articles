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