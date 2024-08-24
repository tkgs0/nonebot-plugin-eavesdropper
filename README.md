<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://raw.githubusercontent.com/tkgs0/nbpt/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://raw.githubusercontent.com/tkgs0/nbpt/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-eavesdropper

_✨ NoneBot 应声谲 ✨_

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/tkgs0/nonebot-plugin-eavesdropper.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-eavesdropper">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-eavesdropper.svg" alt="pypi">
</a>
<a href="https://www.python.org">
    <img src="https://img.shields.io/badge/python-3.9+-blue.svg" alt="python">
</a>
<a href="https://nonebot.dev">
    <img src="https://img.shields.io/badge/nonebot-2.3.1+-red.svg" alt="nonebot">
</a>

</div>

## 📖 介绍

转发指定会话消息给SUPERUSER

## 💿 安装

**nb-cli安装, 包管理器安装  二选一**

<details>
<summary>使用 nb-cli 安装 (暂未支持)</summary>

在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-eavesdropper

</details>

<details>
<summary>使用包管理器安装</summary>

在 nonebot2 项目的插件目录下, 打开命令行,

**根据你使用的包管理器, 输入相应的安装命令**

<details>
<summary>pip</summary>

    pip install nonebot-plugin-eavesdropper

</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-eavesdropper

</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-eavesdropper

</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-eavesdropper

</details>

打开 bot项目下的 `pyproject.toml` 文件,

在其 `plugins` 里加入 `nonebot_plugin_eavesdropper`

    plugins = ["nonebot_plugin_eavesdropper"]

</details>
</details>

## 🎉 使用

### 指令表

```
  监听私聊 qq qq1 qq2 ...
  监听群聊 qq qq1 qq2 ...
  监听私聊 all
  监听群聊 all
  取消监听私聊 qq qq1 qq2 ...
  取消监听群聊 qq qq1 qq2 ...
  取消监听私聊 all
  取消监听群聊 all

  查看监听列表

  传话私聊 qq XXXXXX
  传话群聊 qq XXXXXX
```
