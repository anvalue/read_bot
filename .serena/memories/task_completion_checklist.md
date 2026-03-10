# 任务完成检查
- 至少执行一次可运行验证：`python weread-bot.py --verbose`（或目标模式）。
- 检查日志输出是否正常、CURL 解析是否成功。
- 若涉及定时：确认 `CRON_EXPRESSION` 与 `TIMEZONE` 组合是否符合预期。
- 若涉及通知：验证对应 token/webhook 是否生效。
- 更新 README/docs 中受影响的配置说明。