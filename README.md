# 偷懒配方 · Save Time (`save-time`)

> 100 个拯救时间的日常极简自动化配方  
> 100 time-saving minimalist scripts, shortcuts & Raycast recipes for builders.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/realchendahuang/save-time/pulls)

---

## 设立宗旨

每个建造者每天都在大量重复的体力脏活中消耗心力：转换图片格式、重命名文件、整理杂乱的下载目录、手动把数据贴进报表。

偷懒配方（Save Time）整理了一套基于系统原生命令、轻量脚本与快捷工具的即用方案：
1. 零重型框架：拒绝沉重的自动化平台，几行 Bash、Python 或原生快捷指令搞定；
2. 即开即走：双击或快捷键直接触发，无感运行在后台；
3. 每天至少省出一小时专注深度创造。

---

## 配方分类索引

### 1. 桌面与文件整理配方
- `clean-downloads.sh`：自动将 Downloads 目录下超过 7 天的文件按后缀归档至年份文件夹；
- `batch-webp.sh`：单行命令批量把当前目录下所有 PNG/JPG 转换为高质量 WebP 格式；
- `clean-clipboard.sh`：一键清除剪贴板中的追踪参数（如 utm_source, spm）。

### 2. 开发者与 Git 流水线
- `git-quick-save.sh`：一键暂存未提交工作区并打上时间戳分支；
- `kill-port.sh`：一秒找出并杀掉占用 3000/8080 等本地端口的僵尸进程。

### 3. 内容与信息分发
- `markdown-image-dl.py`：自动下载 Markdown 文档中所有外链图片并替换为本地相对路径；
- `notify-me.sh`：长时间耗时任务跑完后，调用系统通知发出清脆提示音。

---

## License

MIT License. Copyright (c) 2026 realchendahuang.
