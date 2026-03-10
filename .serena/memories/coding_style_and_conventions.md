# 代码风格与约定
- 语言：Python。
- 风格：PEP 8，4 空格缩进，函数 snake_case，类/数据类 PascalCase。
- 建议：优先扩展已有 dataclass，不直接散落 dict；新增函数补充类型标注；日志通过 logger 输出。
- 配置：环境变量 > 配置文件 > 默认值（README 明确）。
- 安全：不要提交敏感 cookie/token/curl 原文。