# 新版配置说明
# 
# 配置修改
### 图片转移
```
 /common/gameIcon/wap/xbb => /common/gameIcon/wap/bb   /xbb里面的全部图片转移到/bb
 
 /common/gameIcon/wap/agsx => /common/gameIcon/wap/ag
 
 /common/gameIcon/wap/bbsx => /common/gameIcon/wap/bg
 
```
### 图片名称修改 所以第三方游戏logo名称都改为 logo.png


```
/common/gameIcon/wap/ky/KY_CARD.png   KY_CARD.png 改 logo.png 

/common/gameIcon/wap/le/FG_CARD.png   FG_CARD.png 改 logo.png

/common/gameIcon/wap/lc/lc_card.png   lc_card.png 改 logo.png

/common/gameIcon/wap/jdb/jdb.png      jdb.png 改 logo.png

/common/gameIcon/wap/cq9/cq9.png      cq9.png 改 logo.png

/common/gameIcon/wap/xsj/xsj.png      xsj.png 改 logo.png

/common/gameIcon/wap/mg/MG_EGAME.png  MG_EGAME.png 改 logo.png  

/common/gameIcon/wap/ag/AG_EGAME.png  AG_EGAME.png 改 logo.png 

/common/gameIcon/wap/bb/bbin.png      bbin.png 改 logo.png

/common/gameIcon/wap/bg/BG_FISH/png   BG_FISH.png 改 logo.png  
```

### 首页快捷功能代码替换
```
[
  {
    "name": "充值/提款", 
    "icon": "{IconDomain}/common/gameIcon/cztk.png",
    "single": "Recharge"
  },
  {
    "name": "投注记录",
    "icon": "{IconDomain}/common/gameIcon/tzjl.png",
    "single": "GameReportList"
  },
  {
    "name": "优惠活动",
    "icon": "{IconDomain}/common/gameIcon/yhhd.png",
    "single": "Activity"
  },
  {
    "name": "在线客服",
    "icon": "{IconDomain}/common/gameIcon/zxkf.png",
    "single": "Service"
  }
] 
```

### 首页品牌推荐代码替换
```
 [
  {
    "name": "开元棋牌",
    "icon": "{IconDomain}/common/gameIcon/KY_CARD.png",
    "title": "亚洲第一品牌",
    "p_spell": "棋牌",
    "s_spell": "开元棋牌"
  },
  {
    "name": "5K棋牌",
    "icon": "{IconDomain}/common/gameIcon/5Kyl_logo.png",
    "title": "独家直营棋牌",
    "p_spell": "棋牌",
    "s_spell": "5K棋牌"
  },
  {
    "name": "乐游棋牌",
    "icon": "{IconDomain}/common/gameIcon/FG_logo.png",
    "title": "暴击百万大奖",
    "p_spell": "棋牌",
    "s_spell": "乐游棋牌"
  },
  {
    "name": "AG视讯",
    "icon": "{IconDomain}/common/gameIcon/AGlogo.png",
    "title": "真人博娱首选",
    "p_spell": "真人",
    "s_spell": "AG真人"
  },
  {
    "name": "BG视讯",
    "icon": "{IconDomain}/common/gameIcon/BG_logo.png",
    "title": "直播公平下注",
    "p_spell": "真人",
    "s_spell": "BG真人"
  },
  {
    "name": "BBIN视讯",
    "icon": "{IconDomain}/common/gameIcon/BBIN_EGAME.png",
    "title": "荷官在线发牌",
    "p_spell": "真人",
    "s_spell": "BBIN真人"
  },
  {
    "name": "MG电子",
    "icon": "{IconDomain}/common/gameIcon/MGgame.png",
    "title": "千款街机游戏",
    "p_spell": "电子",
    "s_spell": "MG电子"
  },
  {
    "name": "JDB夺宝电子",
    "icon": "{IconDomain}/common/gameIcon/JDB_CARD.png",
    "title": "瓜分千万大奖",
    "p_spell": "电子",
    "s_spell": "JDB夺宝电子"
  },
  {
    "name": "CQ9电子",
    "icon": "{IconDomain}/common/gameIcon/CQ9_CARD.png",
    "title": "极致游戏体验",
    "p_spell": "电子",
    "s_spell": "CQ9电子"
  },
  {
    "name": "皇冠体育",
    "icon": "{IconDomain}/common/gameIcon/CR_SPORT.png",
    "title": "老牌体育博弈",
    "p_spell": "体育",
    "s_spell": ""
  },
  {
    "name": "沙巴体育",
    "icon": "{IconDomain}/common/gameIcon/SB_SPORT.png",
    "title": "盘口多赔付快",
    "p_spell": "体育",
    "s_spell": ""
  },
  {
    "name": "三昇体育",
    "icon": "{IconDomain}/common/gameIcon/sss.png",
    "title": "全新体育新贵",
    "p_spell": "体育",
    "s_spell": ""
  }
] 

```
### 第三方游戏代码替换
```
注：龙城棋牌大厅名字和大厅图片请自行修改 （仅龙城游戏每个站大厅名字和图片名字不一样）
```
点击下载 [第三方代码](https://cli.vuejs.org/config/).

### 第三方游戏代码简介
```
每个游戏以 { } 为一个主体，添加游戏代码必须放在[]内，每个游戏之间必须用 英文逗号隔开 ',', 如下所示，否者会无法正常运行

例如：
[
	{
		"name": "5K娱乐大厅",                                  //游戏名称 必须加 "" 
		"icon": "/lc/5kcpdt.png",                            //游戏图片 必须加 ""
		"url": "/LcGame/Game.Aspx?KindID=0&amp;Cid={Cid}"    //游戏链接 必须加 "" 
	},  //英文逗号隔开
	
	{
		"name": "黑红梅方",
		"icon": "/lc/n8660.png",
		"url": "/LcGame/Game.Aspx?KindID=8660&amp;Cid={Cid}"
	},
]
```


### 新版图片上传说明
```
请各自下载压缩包 
解压后 将压缩包里所以文件 放在/common 目录下 （不包含压缩文件本身）
例如：
	解压后得到文件 icon、port、bank 、html
	将这些文件放入 /common 目录下
```
点击下载 [【顶级】](https://cli.vuejs.org/config/)
点击下载[【98】](https://cli.vuejs.org/config/)
点击下载[【9B】](https://cli.vuejs.org/config/)
点击下载[【49】](https://cli.vuejs.org/config/)
点击下载[【5K】](https://cli.vuejs.org/config/)
点击下载[【8G】](https://cli.vuejs.org/config/)

### 新图片站点文件说明 
```
/common/port     //会员头像文件  名称格式 avatar_1.png avatar_2.png avatar_*.png

/common/bank     //银行卡logo与背景  
   
/common/html	  //玩法说明 关于我们 等引入页面文件
```

### /common/html下文件说明
```
/common/html/agent_instruction.html    代理说明页面

/common/html/hongbao_rule.html         红包规则页面

/common/html/user_agreement.html       用户购彩协议

/common/html/about_us.html             关于我们页面

/common/html/playDesc                  玩法说明文件
```
### 第三方游戏图片对应路径
```
/common/gameIcon/wap/ky   开元平台
/common/gameIcon/wap/le   乐游平台
/common/gameIcon/wap/lc   龙城平台
/common/gameIcon/wap/jdb  JDB平台
/common/gameIcon/wap/cq9  CQ9平台
/common/gameIcon/wap/xsj  新世界平台
/common/gameIcon/wap/mg   MG平台
/common/gameIcon/wap/ag   AG平台
/common/gameIcon/wap/bb   BB平台
/common/gameIcon/wap/Pg   PG平台
/common/gameIcon/wap/bg   BG平台
/common/gameIcon/wap/ty   体育

```

### Customize configuration
