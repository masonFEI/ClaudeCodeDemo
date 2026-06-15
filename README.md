# ClaudeCodeDemo

# 实战笔记

# kimi配置

ANTHROPIC_AUTH_TOKEN=sk-03EI6IbMBIrfoKAm1GqAvn3dD8Q5IudDqoTZKCj5JpKoPVQC

AnTHROPIC_BASE_URL=https://api.moonshot.cn/anthropic/

ANTHROPIC_MODEL
kimi-k2.6

ds

apiKey:sk-191444e19f8f4d0d897e11f878c0c22d

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

# claude命令

/add-dir <项目地址>：添加项目目录，claude会分析项目结构和文件内容，构建知识库。

/init 初始化项目的记忆文档，claude会根据项目文件内容生成记忆文档，记录项目的结构、功能、依赖等信息。

/clear 清除项目的记忆文档，重新初始化项目的记忆文档。

/compact 压缩对话内容，保留重要信息，删除冗余内容，减少对话历史的长度。

/memory 编辑会话记忆文件，claude会根据记忆文件的内容调整对话的上下文和回答的内容。

/status 查看会话状态，包括当前使用的模型、对话历史长度、记忆文档的状态等信息。

/cost 令牌消耗统计，查看当前会话的令牌消耗情况，包括输入令牌、输出令牌、总令牌等信息。

/config 查看并修改配置文件

/model 查看可用模型列表，选择使用的模型。





