<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=620&lines=Hobbyist,+mostly+tinkering;ComfyUI+launcher+%C2%B7+OpenAI-compatible+gateways;Python+%C2%B7+PyQt6+%C2%B7+Shell" alt="Typing SVG" />

**chengzige7813** · 写代码是下班之后的事。做出来的东西先自己用，顺手了才放上来。

</div>

## What I'm tinkering with

- **给自己的 ComfyUI 找个清净的入口**：每次开它都要翻命令行历史、记那几个参数，干脆写了个启动器。模型走国内镜像下，插件安装避开 GitHub 抽风的那阵。没什么技术含量，胜在不用再想。
- **一个 OpenAI 兼容的转发层**：手上上游不止一家，接口各写各的。统一成一个入口之后，换服务商只改配置，客户端不用动。坑一半在平台——模板要求的文件和实际启动方式经常对不上，最后干脆让 `bin/start.sh` 说所有话。
- **翻别人的 system prompt**：好奇这些 agent 到底被怎么约束的。读多了有个感觉，写得好的像交接文档：先讲背景，再讲哪儿不能碰，最后才讲要求；写得差的只有一句「你是一个专业的……」。遇到有意思的 fork 一份存着。

## Out in the open

长期就这一个，其余还在本地长草。

| 项目 | 是什么 | 用的 |
| --- | --- | --- |
| [magpie-cloud](https://github.com/chengzige7813/magpie-cloud) | 京东云 DevCloud 上跑 magpie 转发，把上游模型服务暴露成 OpenAI 兼容接口。启动逻辑全在 `bin/start.sh`，平台模板塞的那几个文件其实不参与运行 | Shell · 云容器 |

有问题开 issue，能修的会修，回得可能不快。

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,qt,bash,git,github,githubactions,linux&perline=12" alt="Tech stack" />
</p>

Python 写得最多；PyQt6 是把命令行包成窗口时的默认选择；Shell 只写到能跑起来的程度。

## Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chengzige7813/chengzige7813/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/chengzige7813/chengzige7813/output/github-snake.svg" alt="Contribution snake" />
</picture>
