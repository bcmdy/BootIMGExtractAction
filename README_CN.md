# BootIMGExtractAction

这是一个用来提取 ROM 内 boot.img / init_boot.img 的 GitHub Action 项目。

---

[English](./README.md) | 简体中文

## 使用方法

1. Fork 本仓库。
2. 在 Actions 界面内，选择 所需提取的img镜像如'boot'、'init_boot'等，并提供 ROM 的下载直链。
3. 点击“Run workflow”并等待流程完成。

**如果遇到 “403 资源访问受限”，请去 Settings-Actions-General-Workflow permissions,将它调整至 “Read and write permissions”**

**本项目仅支持 '卡刷包/Recovery ROM'。**

**请去个人仓库内设置-Secret-Action-Add 以 app_token 为 value 'TMP'为名称 填入保存**

## 其他

特别感谢 [tosasitill](https://github.com/tosasitill) 和 [5ec1cff](https://github.com/5ec1cff)。

本项目依赖于 [payload-dumper](https://github.com/5ec1cff/payload-dumper)。

最后测试通过时间: 2024年5月9日
