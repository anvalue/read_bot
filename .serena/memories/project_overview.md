# 项目概览
- 项目名：weread-bot
- 目的：模拟微信读书阅读行为，支持立即执行、定时执行、守护进程，多用户配置与通知。
- 主要入口：`weread-bot.py`
- 关键配置模板：`config.yaml.example`
- 文档目录：`docs/`
- 依赖：requests、httpx、PyYAML、urllib3、croniter、apprise（见 `requirements.txt`）。
- 典型部署环境：本地、Docker、面板（README 明确提到青龙可用 `WEREAD_CURL_STRING`）。