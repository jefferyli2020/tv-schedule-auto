# tv-schedule-auto

自动抓取电视节目表（含五星体育）并生成 XMLTV 格式节目单。

- 使用电视猫接口获取精确节目；
- 替换 live.fanmingming.cn 中的五星体育内容；
- 每日在 GitHub Actions 中定时运行；
- 输出为 `最终_e.xml`，可供 IPTV 或节目导入使用。
