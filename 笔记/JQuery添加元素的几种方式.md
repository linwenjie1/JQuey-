1     
父类引用：
        Object.append('元素');    
                1.添加到父类元素中最后一个
                2.如果该元素是已存在的，则进行剪切操作
        Object.prepend('元素')
                1.添加到父类元素中第一个
                2.如果该元素是已存在的，则进行剪切操作

兄弟节点引用：
        siblings.before('元素')
                1.添加到兄弟节点的前面    
        siblings.after('元素')
                1.添加到兄弟节点的后面   

子类引用：
        chlidren元素.appendTo('a');   
                1.chlidred元素添加到为a父元素的子元素中最后一个
                  