# 比特币源代码阅读


*作者*: AlexTan

*CSDN*: [AlexTan_](http://blog.csdn.net/alextan_) 

*E-Mail* : [alextanbz@gmail.com](mailto:alextanbz@gmail.com)



- 代码版本：bitcoin-0.1，[windows安装下载链接](http://forum.360bchain.com/?PostBackAction=Download&AttachmentID=7)

- 代码里面添加了注释，方便阅读学习，会保持更新的！有什么不懂的也可以发邮箱提问哦，看到会及时回复的。

- 注：bitcoin0.1公钥私钥相关处理是调用的openSSL，已上openSSL调用文档(pdf文件)。
- 新阅读的同学，建议先从CTransaction开始看，先理一下数据结构，再看一下流程（也就是从发起转账开始，一直到交易被打包进区块，主要函数是从SendMony()到CreateTransaction()，注释里写得比较清楚。然后可以看挖矿，打包交易，再到网络通信p2p那一块儿，公钥私钥这些要提前看，提前了解，可以结合代码加pdf文档。
