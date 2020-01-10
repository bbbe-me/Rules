# 老伙计加速器客户专用规则
该规则主体部分来自其他开源项目，老伙计做了一些适配和优化，目前仅支持 Quantumult , 具体优化如下：<br><br>

老伙计网站走代理<br>
屏蔽 YouTube APP 广告<br>
Apple TV+ 流媒体通过代理访问避免直连卡顿影响观看体验<br>
iCloud 与照片相关应用通过代理访问避免直连加载过慢导致卡顿<br>
FaceTime 视频聊天直连效果比走代理好，所以 FaceTime 设置为直连。<br>
Spotify 设置为直连避免频繁掉线，只测试了付费版，免费版没测试不知道好不好用。<br><br>

该规则老伙计自用且都实测过，如有修改意见建议请通过你知道的沟通渠道联系我们。

# 使用说明
1、打开 Quantumult 软件，进入设置 - 分流、链接阻止、HTTP复写（ 清空这三项里面的规则，全部都删除掉。 ）<br><br>

2、进入设置 - 订阅（ 在订阅里添加规则 ）<br>
2.1、点击右上角加号 - 选择分流 - 名称随便输入，链接复制下面的链接并保存：<br>
https://github.com/bbbe-me/Rules/raw/master/Quantumult/Quantumult.conf<br>
2.2、点击右上角加号 - 链接阻止 - 名称随便输入，链接复制下面的链接并保存：<br>
https://github.com/bbbe-me/Rules/raw/master/Quantumult/Quantumult_URL.conf<br><br>

3、在刚添加的分流和链接阻止两个规则那里向左滑动 - 点击增加，就可以把规则添加进去了，后期更新向左滑动 - 点击替换即可完成更新。
