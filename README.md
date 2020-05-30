# Agg_SubLink 自用订阅转换规则
~~其实是缝合怪~~
## 食用指南
1、建议自己fork一份，部分策略组注释掉了，按需求开启即可；**综合版规则未来可能会将各种奇奇怪怪的策略组缝合进去，不需要的可以选择默认或者自新注释掉**

2、不需要节点名称rename以及普通用户可以用Lite版规则。**Lite版规则并不代表使用的规则条数减少，仅精简策略组的分配逻辑**，规则中“轻度使用”策略组代表一般不需要大流量传输，只需要稳定连接的国外需代理网站；“重度使用”策略组则主要包含Onedrive、国外流媒体等需大流量传输网站。**建议“轻度使用”策略组选用“专线切换”，“重度使用”策略组选用“中继切换”**；或“轻度使用”中选用“自动选择”或“专线切换”，“重度使用”中选用可供自由选择节点的“低倍节点”。如无特殊需求（如需要日本或英国或台湾节点解锁某些网站），仅需要选择第一种方式即可。

## 主要更新
Update: 05-30 简化Lite版规则策略组

Update: 05-26 支持了yoyu pro套餐节点订阅;去除neuk订阅

Update: 04-26 支持了n3ro与neukssr标准套餐节点订阅


参考了[subconverter文档](https://github.com/tindy2013/subconverter/blob/master/README-cn.md#%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6)、[n3ro专用规则](https://raw.githubusercontent.com/SNSLogty/pixiv-hosts-1/master/n3roclash.txt)、[ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)、[rename n3ro 节点](https://github.com/shenwei101623/subconverter_ini)
