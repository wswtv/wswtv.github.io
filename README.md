<p align="center"><img alt="wswtv.github.io" src="https://wswtv.github.io/logo.png"></p>
<h1 align="center"> ✯ 大家可直连访问的电视/广播图标库与相关工具 ✯ </h1>
<h3 align="center">🔕 永久免费 直连访问 完整开源 不断完善的台标 支持IPv4/IPv6双栈访问 🔕</h3>
---

## 🤹‍♂️使用方法:


### ⛓️创建您的m3u订阅链接：
 - 下载 `demo.m3u` 空白示例文件并使用文本编辑软件打开。
   - [https://wswtv.github.io/tv/m3u/demo.m3u](https://wswtv.github.io/tv/m3u/demo.m3u)

 - 参考下方示例代码将`可用的CCTV1节目源`替换为您当地可用的直播源链接，依此类推逐个替换。

```
#EXTM3U x-tvg-url="https://wswtv.github.io/e.xml"
#EXTINF:-1 tvg-id="CCTV1" tvg-name="CCTV1" tvg-logo="https://wswtv.github.io/tv/CCTV1.png" group-title="央视",CCTV-1 综合
可用的CCTV1节目源
此处省略...
```

 - 将编辑完成的m3u文件上传到您的Github仓库。
 - 为您的Github仓库开启Pages。
 - 通过播放器订阅您的m3u链接。

> 关于Github Pages：[https://docs.github.com/en/enterprise-cloud@latest/pages/quickstart](https://docs.github.com/en/enterprise-cloud@latest/pages/quickstart)

## 🛠️工具
- 📆**EPG接口地址**：
  -  [https://wswtv.github.io/e.xml](https://wswtv.github.io/e.xml)
- 🏞️**Bing每日图片**：
  -  [https://fanmingming.com/bing](https://fanmingming.com/bing)
- 🎞️**m3u8下载工具**：
  -  [https://wswtv.github.io/m3u8](https://wswtv.github.io/m3u8)
- 🆕**TXT转M3U格式**：
  - [https://wswtv.github.io/txt2m3u](https://wswtv.github.io/txt2m3u)
- 📄**在线M3U转TXT**：
  - Demo🔗 [https://fanmingming.com/txt?url=https://live.fanmingming.com/tv/m3u/ipv6.m3u](https://fanmingming.com/txt?url=https://live.fanmingming.com/tv/m3u/ipv6.m3u)
- 🌐**M3U8 Web Player**:
  - Demo🔗 [https://wswtv.github.io/player/?vurl=https://0472.org/hls/cctv13.m3u8](https://wswtv.github.io/player/?vurl=https://0472.org/hls/cctv13.m3u8)
