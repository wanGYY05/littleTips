1、(js默认为false的：false,undefined,空字符串)
   (let是块状作用域，var是函数作用域)
   (形如"（function(){}）()"的函数，叫做自执行函数)
2、（a为局部变量，b的声明（var）没有写，默认为全局变量；）
   （"use strict"这句话即严格执行的意思，有了它，不用var声明变量就会报错）
3、(闭包作用：闭包可以用在许多地方。它的最大用处有两个，一个是可以读取函数内部的变量，另一个就是让这些变量的值始终保持在内存中。)
   (伪数组：是一个有length属性的对象)
   (怎样将对象转成数组call,apply)
4、a=1;b=a;b=2;=====>a=2,b=2;此情况是因为b是a的引用，遇此种情况相同的还有数组和对象，改变这种问题的方法
5、1、js中new操作符：(http://www.cnblogs.com/andyliu007/archive/2012/07/27/2795415.html)
   2、try-catch函数
      try {
      //执行的代码，其中可能有异常。一旦发现异常，则立即跳到catch执行。否则不会执行catch里面的内容
      } catch {
      //除非try里面执行代码发生了异常，否则这里的代码不会执行
      } finally {
      //不管什么情况都会执行，包括try catch 里面用了return ,可以理解为只要执行了try或者catch，就一定会执行 finally
      }
6、call()与apply()
7、js中的this总结(https://gold.xitu.io/entry/57981b1879bc44006654bd62)(in a word:谁调用指向谁)
8、声明一个构造函数，人有age，name,like.还有play(即function)；iframe标签（状态码：401没登录403登录没权限  )
9、翻转字符串；数组元素去重和统计个数
10、promise:
   三种状态
   1:进行时(pedding)->  2成功(resolved)->2,3二者不可能相互转换
                        3失败(reject)
   声明
   var a=new Promise();
   //回调函数：function sum(a,v,callvack){a+b;callback()}
   //变量提升：a=12;a的作用域全局
   let a=1;
   let promise=new Promise(callback(resolve,reject)=>{if(a>0){resolve();}else{reject()}});//Promise括号中的参数是一个callback函数
   promise.then(()=>{正确时执行的函数}).catch()//错误的时候执行catch
11、
12、
13、
14、
15、
16、
17、
18、
19、
20、DOM是对元素操作的BOM是对浏览器操作的比如LocalStorage就是
事件
跨域：iframe








