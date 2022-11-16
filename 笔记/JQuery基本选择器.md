JQuery基本选择器类别
        1.id选择器      $('#id')
        2.类选择器      $('.class')
        3.标签选择器    $('标签名')
        4.并集选择器    $('.box,.bxo2')
        5.交集选择器    $('li.current')
JQuery层级选择器    
        1.后代选择器    $('div p')
        2.子代选择器    $('div>p')
JQuery过滤选择器
        1.  :eq(index)        选中下标为index的元素
        2.  :odd              选中下标为奇数的元素
        3.  :even             选中下标为偶数的元素
 JQuery筛选选择器
        1.children('li')  ==$('ul').children('li')      子代选择器
        2.find()                                        后代选择器
        3.siblings()                                    查找兄弟节点
        4.parent()                                      查找父亲
        5.next()                                        下一个兄弟
        5.prev()                                        上一个兄弟