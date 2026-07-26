# 中国婚礼网站包（小院婚礼 v9）

## 本版更新

- 修复“地图导航”场地图在手机上被裁切、只看到后两张的问题。
- 场地实景、仪式区参考与迎宾区参考改为三张独立响应式图片；手机端会完整显示全部三张。

- 网站不显示婚礼程序单；完整流程保留在独立程序表包。
- “出席回复”已经直接嵌入新人建立的 Microsoft Forms，不再显示网站内建的空白回执表单。
- 宾客可以直接在婚礼网站内填写并提交。
- 若 Microsoft Forms 无法在页面内显示，网站会提供“打开 Microsoft Forms 回执”按钮，改在新页面填写。
- 保留原有的小院婚礼视觉、照片与影片无限轮播、场地信息、百度及高德导航、相册和倒数计时。

## 直接预览

双击 `index.html` 即可预览。由于 Microsoft Forms 是线上服务，预览回执区域时需要连接网络。

正式分享时，请上传整个文件夹，不要只上传 `index.html`。

## 已接入的回执

- 服务：Microsoft Forms
- 公开答题网址：`https://forms.cloud.microsoft/r/uDUBnBgJ24`
- 网站呈现方式：页面内嵌表单，并附新窗口备用按钮

不再需要修改 JavaScript 配置文件。

## 目录说明

- `index.html`：婚礼网站主页，已包含 Microsoft Forms 回执。
- `assets/images`：主视觉与场地图片。
- `assets/gallery`：婚礼相册。
- `assets/marquee`：“邀请你来”照片及影片轮播。
- `MICROSOFT_FORMS_SETUP_GUIDE_ZH_TW.md`：Microsoft Forms 管理与检查说明。
- `MICROSOFT_FORMS_QUESTION_TEMPLATE_ZH_CN.txt`：回执题目备份。

## 上线前检查

1. 使用手机和电脑各打开一次网站。
2. 确认回执表单可以在页面内载入。
3. 点击备用按钮，确认能在新页面打开同一份表单。
4. 用无痕窗口提交一笔测试回复，并在 Microsoft Forms 后台确认收到。
5. 请一位中国大陆亲友使用当地手机网络测试一次。
