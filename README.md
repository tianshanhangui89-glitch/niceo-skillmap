# Niceo 技能图谱 · 数据源

这个仓库给「Niceo 技能图谱」App（Android / Windows）提供在线数据，App 启动或下拉刷新时自动拉取，**更新内容无需重装**。

- 数据：[`data.json`](data.json)（技能、领域、Bot 归属、关键词）
- 网页版（离线单文件）：[`index.html`](index.html)

数据地址（App 会同时尝试，取较新的一份）：
- https://raw.githubusercontent.com/tianshanhangui89-glitch/niceo-skillmap/main/data.json
- https://cdn.jsdelivr.net/gh/tianshanhangui89-glitch/niceo-skillmap@main/data.json （国内镜像）

由 `build.py` 扫描技能自动生成，`publish.sh` 推送。请勿手工编辑 data.json。
