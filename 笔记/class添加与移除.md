添加类：
    1.在style样式内定义  .style{}
    2.通过addClass(style style);  //可添加多个

移除类：
    1.removeClass(style style) 可移除多个
    2.如果没参数 removeClass() ，则移除所有的样式   

判断类:
    1.hasClass('style') 判断是否有style类，返回Boolean

切换类：
    1.toggleClass('style');  如果对象有style则删除，否则添加