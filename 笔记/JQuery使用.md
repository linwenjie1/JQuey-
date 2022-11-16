如何使用JQuery？
    1.导入JQuery文件
    2.写一个入口函数
            一.$(document).ready(function(){  })    
            二.$(function(){ })
            三.JQuery与unload执行时机不同和
                JQuery在dom树加载完成后执行（先）
                unload在所有资源及外部链接加载完后执行  
    3.使用JQuery选择器操作它（属性，样式，文本）