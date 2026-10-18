# 居家工具 · 交互原型与产品方案

三个可直接用浏览器打开的单文件 Demo，无构建、无依赖、离线可用。

## 1. 蓝牙智寻便签 · App 原型

`smart-tag-app.html`

防丢便签的移动端 App 交互原型：设备列表、BLE 绑定流程、响铃查找、双向寻物、防丢提醒、家庭共享、丢失模式、地图、设置。

- 用模拟引擎驱动距离 / RSSI / 电量，状态与提醒按真实规则联动
- 数据存在浏览器 localStorage，刷新不丢
- 支持直达链接：`#detail=d1`、`#map`、`#me`、`#settings`、`#add`

## 2. 蓝牙智寻便签 · 系统架构页

`bluetooth-tag-site.html`

四层架构（硬件 / 移动端 / 云端 / 外部服务）的产品介绍与架构说明。

## 3. 居家家电简易排查助手 · 产品方案

`appliance-triage-plan.html`

家电故障自查工具的产品方案：用户描述现象，输出「哪里出问题、为什么故障、建议怎么做」三段式结论，覆盖空调 / 洗衣机 / 热水器 / 冰箱四类家电。

---

## 怎么用

直接双击 HTML 文件，或在仓库的 **Settings → Pages** 里开启 GitHub Pages，用浏览器在线打开。

开启 Pages 后访问：

```
https://<用户名>.github.io/<仓库名>/smart-tag-app.html
https://<用户名>.github.io/<仓库名>/bluetooth-tag-site.html
https://<用户名>.github.io/<仓库名>/appliance-triage-plan.html
```
