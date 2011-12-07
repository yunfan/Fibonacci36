
测试各种编程语言运行Fibonacci36所需的执行时间来衡量编程语言函数调用效率，其中Fibonacci函数要采用如下形式实现（不用通项公式。。。-_-!）：
fib(n){
	if(n<2)
		return 1;
	else return fib(n-2)+fib(n-1);
}

可以使用time命令来测试运行时间，如time node fib.js 36

C、java等编译型语言需要自己先编译

归功与V8引擎，node.js表现很出色，测试结果合情理，但是也会出人意料。

困，碎觉去鸟。。。


PS: 我这里增加的 forth的实现 fib.4th

在我台式机上跑速度惊人，不过需要请原作者在原机器上跑一次

考虑到原作者的机器是mac 可以在这里下载 forth的环境 http://www.forth.com/swiftforth/version.html
