# ClaudeCodeDemo

# 实战笔记

# kimi配置

ANTHROPIC_AUTH_TOKEN=sk-03EI6IbMBIrfoKAm1GqAvn3dD8Q5IudDqoTZKCj5JpKoPVQC

AnTHROPIC_BASE_URL=https://api.moonshot.cn/anthropic/

ANTHROPIC_MODEL
kimi-k2.6

# git配置

CLAUDE_CODE_GIT_BASE_PATH:E:\Program Files\Git\bin\bash.exe

# 终端功能

比如iTerm2，Windows Terminal等，支持输入命令行指令，执行后返回结果。

# claude使用

在项目根目录，执行命令：claude

在启动目录，创建.claude目录，创建config.json文件，内容如下：

{
"model": "kimi-k2.6",
"max_tokens": 4000,
"temperature": 0.7,
"auto_approve": false,
"git_integration": true,
"exclude_files": ["node_modules/**", ".git/**", "*.log","dist/**", ],
"language_preference": {
"docu,emntation": "zh-CN",
"code_comments": "zh-CN",
}
}