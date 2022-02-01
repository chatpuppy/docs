## gun空间
* public：任何人都可以增删改查
* User：只有owner可以更改，注意owner不是项目方或数据库维护账号。
* Frozen：只能添加，不能更改或删除

## 安装与初始化
### 浏览器安装
```
# ES6
import Gun from "gun/gun";
peers = [
    "http://localhost:8765/gun",
    // Community relay peers: https://github.com/amark/gun/wiki/volunteer.dht
    "https://www.raygun.live/gun",
    "https://gunmeetingserver.herokuapp.com/gun",
    "https://gun-us.herokuapp.com/gun",
    "https://gun-eu.herokuapp.com/gun",
    // My own relay peer
    // "https://phrassed.com/gun",
  ];
const gun = new Gun({peers});

// attaching gun to window for testing purposes
window.gun = gun;
```

### 节点安装
```
const Gun = require("gun");
const server = require('http').createServer().listen(8080);
const gun = Gun({web: server});
```

## 用法
### get
```
var item = gun.get('keyName');
```

### set

### 创建用户
```
user = gun.user(); 
user.create(alias, pass, callBackFun, opt)
```
返回
```
{
    ok: 0,
    pub: 'fe4...ee3' //public key of the user that was just created
}
```