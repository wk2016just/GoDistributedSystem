# GoDistributedSystem
master节点认为每个输入文件对应1个map任务(这个任务至少调用好多次doMap函数）
sort，这里的sort指的是将相同的key／value对存入一个数组中，结果像这样{"he", "1", "1", "1"...}....（从doReduce函数的描述和mapF的参数得到的）

zhihu sort  https://www.zhihu.com/question/35999547/answer/65443663
引用 https://my.oschina.net/chai2010/blog/161384
文件  http://www.jb51.net/article/58142.htm
fatal http://www.bubuko.com/infodetail-166782.html
defer http://blog.csdn.net/eclipser1987/article/details/12089271
file stat http://www.widuu.com/archives/01/921.html

go rune  http://www.golangtc.com/t/528cc004320b52227200000f


ioutil.readFile可以直接读取文件

waitgourp
http://ifeve.com/go-concurrent-waitgroup/

lab1
http://www.jianshu.com/p/bfb4aee7a827

http://blog.csdn.net/bysui/article/details/52128221


defer:http://blog.csdn.net/eclipser1987/article/details/12089271

http://studygolang.com/articles/7548
