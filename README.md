javascript随手记

1-javascript函数的几种写法。

常见写法:
function Test(){
alert("test");
}
调用:Test()

匿名函数：
var test=function(){
alert("test");
}
调用:test(); 
写法3：
(function () {   
alert('test'); 
})();

写法4：
var Test = {
test1:function(){
alert('test1');
}
,test2:function(){
alert('test2');
}
}
使用：var t = Test.test1();

写法5：
var Test = function(){};
Test.prototype={
test1:function(){
alert('test1');
}
,test2:function(){
alert('test2');
}
}
使用：var t = new Test();
t.test2(); 



2-js自执行函数的几种不同写法的比较
