# mod-for-wargame-red-dragon
 
# 软件基本使用
https://bbs.3dmgame.com/thread-4176597-1-1.html
## 文档和工具和单位手册
https://github.com/fengmao31/mod-for-wargame-red-dragon
# 修改翻译名称
https://forums.eugensystems.com/viewtopic.php?t=45689
ZZ_Win.dat文件中条目修改英文
localisation / us / unites

# 修改单位属性
https://forums.eugensystems.com/viewtopic.php?t=42266
https://bbs.3dmgame.com/thread-4176597-1-1.html
https://docs.google.com/document/d/1K05usXGGFscO79LK_yC8S6Vxa8kJX8oqG2SHBEw2iak/edit#
## 注意事项：
**可以完成的事情**
模型、皮肤、数值可以修改
**不可以完成的事情**
模型无法替换
单位无法新建，也就是单位总数受限。只能使用旧的和部分废弃的单位替换，并汉化文件修改新名字
# 修改单位国家

https://tieba.baidu.com/p/6209519622

但单位属性里面修改国家**MotherCountry**，军械库可以在对应国家显示了，但是前哨战牌组含此卡会无法出兵进入观战。

这是因为跨红蓝阵营，在左边栏里搜索**TShowRoomDeckSeriqlizer**，找到后双击**pactunitids**这一项。参考列表里的单位新增一个同等类型的条目，编号顺延一个编号。

单位旗帜**texture mother country for interface**不用修改，改了军械库会崩溃。

方法二，把一个已有单位全面替换成另一个单位。比如**J7**变成**F16**

# 恢复被官方放弃并隐藏的单位
https://tieba.baidu.com/p/6615337227

81>459ShowInMenu 第一项右False改成Ture。
81>438 modules >TypeUnit,将TypeUnit这一项随便套用一个没有被取消的同等类型单位的值就行了。

比如被隐藏的69II和80II，因为属性过于相近，被舍弃。

单位所属类型希哈值：（位置在81 > 相应单位 > 465UnitTypeTokens）
陆战队 23B8605ED9380000 装甲5C76718B57360E00
摩托化 5E767965E3000000 空降0BB7685ED9380000
机械化 8BD43C9757360E00 支援 DAD77965E3000000

# 系列前置单位
单位属性里面条目下拉框选择一个就好，军械库会同一行显示。





