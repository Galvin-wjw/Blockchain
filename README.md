# Blockchain
Simulating the Blockchain by python(Flask)

1.blockchain文件实现了区块链类<br/>
2.BChain_flask文件实现了web服务器<br/>

测试指南：<br/>
1.python3 blockchain.py  启动web服务器；默认监听7000端口<br/>
2.使用curl或者浏览器访问 http://URL/mine:7000 进行挖矿操作。 POST方式访问 http://URL/transaction/new:7000 添加一个新交易<br/>
3.请求 http://URL:7000/chain  获取当前链信息<br/>
   ![Alt text](https://github.com//Galvin-wjw/Blockchain/raw/master/Screenshots/Chain.png)
