## 1. 简介
ChatPuppyNFT是Web3聊天应用ChatPuppy的NFT。

该NFT在以太坊上发行，可在Opensea上交易，也可以将NFT跨链到币安智能链上进行高频交易。

## 2. 首页
https://chatpuppy.com

## 3. Mint盲盒
在浏览器中通过小狐狸钱包连接到以太坊主网，并确保账户内有至少`0.15ETH`

网址：https://chatpuppy.com/mint

* 盲盒价格：`0.08ETH`

* Gas费约：`0.0085ETH`

* 注：以太坊Gas价格按`50GWei`估算，以太坊Gas价格会随着网络拥挤程度变化，通过https://ethgasstation.info/查询最新Gas价格

## 4. 开盲盒
盲盒购买成功后，等待约1分钟左右（网络同步确认时间），打开网址：https://chatpuppy.com/account， 点击`Mystery Boxes`。

可以看到购买的盲盒，点击`Unbox`按钮，开盲盒。

* Gas费约：`0.028ETH`

## 5. 上传NFT的Metadata并设置tokenURI
盲盒打开后，得到NFT，点击`Save to tokenURI`，将该NFT的属性上链。如果不进行这一步，在Opensea上无法同步metadata，无法看到NFT图片以及属性。

* Gas费约：`0.006ETH`

## 6. 到Opensea上销售
购买的盲盒以及开启后的盲盒，都可以到Opensea上销售。

打开 https://chatpuppy.com/account， 点击`SELL ON OPENSEA`。

注意：如果需要在Opensea上看到NFT图像，必须首先同步`metadata`，方法如下图：

![](https://tva1.sinaimg.cn/large/e6c9d24egy1h15za0y3u1j218w0u0jtz.jpg)

首次在Opensea上挂单，需要支付Registry费用，

* Gas费约：`0.02ETH`

## 7. 将NFT从以太坊跨链到BSC

在首页点击`Send To BSC`，会打开网页： https://portalbridge.com/#/nft
（参考附录的《NFT跨链教程》操作）

注：如果NFT跨链到了BSC，则原来在Opensea上挂的价格失效，同时因为在以太坊链上，该NFT已经托管在合约里，所以在Opensea上看到的所有人为虫洞跨链的托管账号。

* Gas费约：`0.0105ETH`

## 8. 在BSC上交易
从以太坊跨到BSC上的NFT，在浏览器中连接小狐狸钱包，切换到`BSC网络`，可以在`account`页面看到。点击`Sell`按钮，设定CPT价格，在钱包中签名后，上架。

自己上架的NFT可以在`Marketplace`的`My Listed NFTs`中看到，其他人上架的NFT可以在`Marketplace`的`Onsale NFTs`中看到。


## 9. 将NFT从BSC跨链到以太坊
参考附录的《NFT跨链教程》

---
## 附：《NFT跨链教程》

网址：https://portalbridge.com/#/nft

### 1- 选择网络
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzfe1qroj20yo0u0wgg.jpg)

### 2- 切换至以太坊钱包
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzfoix6aj20q814otb6.jpg)

### 3- 选择NFT
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzgxbcexj21cs04e74a.jpg)

![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzjyhzl3j20w20h4jt3.jpg)

### 4- 查看将要跨链的NFT
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzlsesfmj20w80u0afl.jpg)

### 5- 选择目标链
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzn4tj8wj21d40km0u7.jpg)

### 6- 钱包连接目标链
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xznzktc3j20ke0xwq4p.jpg)

连接后，出现如下：
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzsvav99j21d00matbt.jpg)

#### 注意：
* 需要确保目标链上的钱包地址有足够的目标链上的代币。

* *目标链的地址必须与原链地址相同。*

### 7- 点击NEXT，在钱包里切回到原链
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0xzzet3f3j21ci0eejtr.jpg)

### 8- 点击Transfer按钮，授权合约使用NFT
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0y00tju9nj20q814oq65.jpg)


### 9- 开始跨链操作
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0yvnz61gfj21cm0ky0vx.jpg)

一共有15步，大概需要2分钟。

### 10- 切换到目标链，将NFT提现到目标链
![](https://tva1.sinaimg.cn/large/e6c9d24egy1h0yvs9i44vj21cm0ayaay.jpg)




