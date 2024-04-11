# [mxd's EPG](https://epg.imxd.top/)
* 基于`Python3`及`Django4`的节目表数据抓取及发布系统
* 网站地址:[mxd's EPG](https://epg.imxd.top/)
* 您也可以新建Issues！

# ✨部署戳这里→[部署教程、常见问题](https://app.mxdyeah.top/docs/epg/epgbuild.html)
# 使用、部署前必读→[教程必读页](https://app.mxdyeah.top/docs/epg/epgread.html)

# 预览图&实际效果图👇

![Crawl](https://res.mxdyeah.top/picture.jsp/markdown/epg/crawl.png)

![RunImage](https://res.mxdyeah.top/picture.jsp/markdown/epg/run.jpg)

# 主要功能

- 从网上抓取各来源的节目表信息并生成[XMLTV](http://wiki.xmltv.org/)格式文件，导入[Perfect Player](https://blog.mxdyeah.top/mxdyeah_blog_post/29.html)等APP直接载入节目表信息。
- 后台配置频道获取列表及抓取日志。
- 抓取失败时自动更换来源。
- 各数来源提供节目表的频道获取。
- 提供向外发布的接口。
- 使用nginx+uwsgi+MYSQL，**普通电脑经长期测试，一天DIYP接口访问量可千万以上！**

# 节目表来源

- 电视猫
- 搜视
- 央视
- 中数
- 台湾宽频
- 中华电信
- 香港有线宽频caletv
- 台湾四季电视
- 香港有线宽频i-cable
- 香港NOWTV
- 香港无线电视
- 北京卫视
- 广东卫视
- 香港卫视
- viutv
- 川流TV
- myTVSUPER

# 需求

- requests
- django
- BeautifulSoup

