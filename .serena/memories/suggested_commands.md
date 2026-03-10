# 常用命令（Windows/跨平台）
- 创建虚拟环境：`python -m venv venv`
- 激活虚拟环境（PowerShell）：`venv\\Scripts\\Activate.ps1`
- 安装依赖：`pip install -r requirements.txt`
- 立即运行：`python weread-bot.py`
- 指定配置运行：`python weread-bot.py --config config.yaml`
- 定时模式：`python weread-bot.py --mode scheduled`
- 守护进程模式：`python weread-bot.py --mode daemon`
- 详细日志：`python weread-bot.py --verbose`
- 搜索关键配置（本地排查）：`rg -n "WEREAD_CURL_STRING|STARTUP_MODE|SCHEDULE_ENABLED|CRON_EXPRESSION|TIMEZONE" README.md weread-bot.py`