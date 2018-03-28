# test-test
测试
addEventListener的三个参数（事件名，要执行的函数，布尔值（可选）），
布尔值默认为false，执行冒泡机制，布尔值为true时执行捕获机制，浏览器会优先执行捕获机制
阻止冒泡的发生：event.stopPropagation()；并不会阻断函数的继续运行。
