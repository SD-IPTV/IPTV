# SDU-IPTV-PRO

本项目汇集了山东联通、山东移动及山东电信三大运营商的 IPTV 内网直播源，并针对各地市用户收视习惯对频道顺序进行了本地化排列，方便不同地区用户快速使用。


## 📁 文件说明
> 说明：文件名前缀 `SDU` / `SDM` / `SDT` 分别对应 山东联通、山东移动 与 山东电信。

### 🌐 通用版本
| 文件名 | 说明 | 订阅链接 |
| ------ | ---- | -------- |
| SDM-Unicast.m3u | 山东移动单播源（m3u8版） | [[订阅](https://gh-proxy.org/https://github.com/wanghe1108/IPTV/blob/main/SDM-Unicast-Rtsp.m3u)](文件的在线直链地址) |
| SDM-Unicast.m3u | 山东移动单播源（RTSP版） | [[订阅](https://gh-proxy.org/https://github.com/wanghe1108/IPTV/blob/main/SDM-Unicast-Rtsp.m3u)] |
| SDT-Unicast.m3u | 山东电信单播源（通用版） | [订阅](文件的在线直链地址) |




 使用方法
将以下任意链接复制到常见的 IPTV 播放壳（如 酷9、云影空蒙、IPTV Pro、APTV、mytv 等）的 EPG 设置（注意格式是xml）中即可使用：

版本说明	EPG 地址
无节目描述版	https://gh-proxy.org/https://raw.githubusercontent.com/sggc/SD-EPG/refs/heads/main/EPG/sggc.xml.gz
含节目描述版	https://gh-proxy.org/https://raw.githubusercontent.com/sggc/SD-EPG/refs/heads/main/EPG/sggc-desc.xml.gz
suming 维护版	https://gh-proxy.org/https://raw.githubusercontent.com/sumingyd/xml/refs/heads/main/epg.xml
