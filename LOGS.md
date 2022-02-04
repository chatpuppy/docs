## Feb.1
* Whitepaper 0.1
* Imported Smart Contracts and deployed

## Feb.2
* Make a bouty for Chat Dapp on gitcoin.
* Make an order of puppy NFT designing on fiverr.

* https://www.nft-stats.com/collection/pixeldoges
* https://www.nft-stats.com/collection/fastfooddoge
* https://www.nft-stats.com/collection/cryptorayrays-collection
* https://nft.doge-punks.io/

## Feb.3
* Make a bouty for mint/marketplace front pages on gitcoin.

## Feb.4
考虑是否可以从成熟的聊天工具改装?

https://github.com/revoltchat

首页UI风格：https://revolt.chat/, https://chaskiq.io/

https://element.io/ 能否基于element加上NFT功能？放弃gunDB？之前的Riot

Matrix.org

一个较为简单的基于Firebase的聊天室
https://github.com/soumyajit4419/Chatify

聊天UI：https://github.com/Detaysoft/react-chat-elements

https://github.com/yinxin630/fiora 尝试部署

https://github.com/amand33p/les-chat

----------------------------------------------------------------

# 新方案：
## Folk https://github.com/yinxin630/fiora
## Make change: 
### 1- User and account $ 1500
* Change the way of login to metamask signature. No register, password etc.
* User avatar image is choosed from `NFTs` in the user's blockchain account. If there is no `NFT` in the user's account, use the 2nd two characters of the account address or username(if has) as avatar. If there are more than one `NFT`, choosed one by user.
* User can set/change username, then the account address will not shown directly.
* User can set buddyname for the buddy account, but this buddyname can be only seen by the user himself.

### 2- Database $ 1500
* Change database to decentralized database from centralized db like MongoDB or redis. Suggest to use `gunDB`, `obitdb`.

Refer to [a gunDB Chat app](https://github.com/fireship-io/gun-chat)

### 3- functionalities $ 1500
* Searching user by blockchain address.
* `Like`, `Reply`, `Edit`, `Delete` message functionalities like discord.
* Limitation to `non-NFT` user.(See whitepaper)
* `/` functionalities
  * /transfer toAddress tokenAddress amount
  * /balanceOf tokenAddress amount
  * more ERC20, ERC721, ERC1155 standard methods

We can get technical support from the guy who wrote the `fiora` repo.

----------------------------------------------------------------

任务分拆，每个点单独计费。


* 改登录方式为`metamask`,去掉注册，密码设置，密码修改等传统登录方式
* 头像从账户中获取`NFT`,去掉现有的自定义头像功能。如果没有NFT，则使用用户名/账户字母
* 用户可以为自己的账户设置用户名，并保存在gunDB中
* 用户可以为好友设置备注名
* 搜索功能增加搜索链上的`Address`
* 数据库改为`gunDB`
* 增加对`非NFT`用户限制
* 多语言支持

================================================================
Make `fiora` multilanguage supported, and issue a bounty.
