dom对象：原生JS获得到的对象 document.getEelementById('id');
        1.可以调用dom对象的属性和方法
        2.不能调用JQuery对象的属性和方法

JQuery对象：$('#id')来获取的对象       
        1.可以调用JQuery属性和方法
        2.同样不可以调用原生JS方法和属性
        3.赋值给一个变量最好在前加一个$

JQuery对象实际上是一个伪数组，是dom对象的包装集
       