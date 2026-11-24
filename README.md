<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=620&lines=Building+tools+that+remove+steps;ComfyUI+launcher+%C2%B7+OpenAI-compatible+gateways;Python+%C2%B7+PyQt6+%C2%B7+Shell" alt="Typing SVG" />

**chengzige7813** · 把每天重复的那几步做成工具：ComfyUI 少碰几次命令行，模型接入少写几套适配。

</div>

## 🔭 Focus

- **ComfyUI 桌面工具**：启动参数、模型下载镜像、插件安装收进一个窗口，装插件的加速与直连该走哪条都写清楚
- **模型接入层**：把不同上游统一成一个 OpenAI 兼容入口，provider 配置写进启动脚本，换环境不用改代码
- **提示词与系统提示**：读各家模型、agent 的系统提示，对比它们怎么划约束边界

## 🧩 Featured Projects

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [ComfyUI-Launcher-Announcements](https://github.com/chengzige7813/ComfyUI-Launcher-Announcements) | ComfyUI 启动器的公开说明与更新页：一键启动、内置国内镜像下载模型、插件安装走 GitHub 加速，并标明哪些请求走镜像、哪些直连 | PyQt6 · Python 3.10+ · Windows |
| [magpie-cloud](https://github.com/chengzige7813/magpie-cloud) | 在京东云 JoyCode DevCloud 上跑 magpie 转发服务，把上游模型服务暴露成 OpenAI 兼容接口。`bin/start.sh` 是唯一启动事实来源，其余脚手架不参与运行 | Shell · 云容器 · OpenAI 兼容 API |

仓库还小，issue 都会看。说清楚「你原本想干什么、卡在哪一步」，比一句「跑不起来」有用得多。

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,qt,bash,git,github,githubactions,linux&perline=12" alt="Tech stack" />
</p>

**桌面端**：PyQt6 · 参数与配置持久化　**接入层**：OpenAI 兼容 API · 反向代理 · 环境变量注入　**日常**：ComfyUI · Git / GitHub Actions

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chengzige7813/chengzige7813/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/chengzige7813/chengzige7813/output/github-snake.svg" alt="Contribution snake" />
</picture>
