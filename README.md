# cc-learning
ghostty, cc-switch, claude-code: learning from open information source



## MCP

好用的MCP工具，联网搜索，图片理解，网页读取，连接数据库，查看开源代码库



## Plugin

1. **superpowers（日常开发）:**

/plugin marketplace add obra/superpowers-marketplace

/plugin install superpowers@claude-plugins-official



2. **claude-hub:**

/plugin marketplace add jarrodwatts/claude-hud

/plugin install claude-hud

/claude-hud:setup



3. **everything-claude-code（基础设施）:**

- /plugin marketplace add affaan-m/everything-claude-code

​	/plugin install everything-claude-code@everything-claude-code

- git clone https://github.com/affaan-m/everything-claude-code.git

​	#复制规则（通用 + 语言特定）

​	cp -r everything-claude-code/rules/common/* ~/.claude/rules/
​	cp -r everything-claude-code/rules/typescript/* ~/.claude/rules/   # 选择你的技术栈
​	cp -r everything-claude-code/rules/python/* ~/.claude/rules/
​	cp -r everything-claude-code/rules/golang/* ~/.claude/rules/
​	cp -r everything-claude-code/rules/perl/* ~/.claude/rules/

- #尝试一个命令（插件安装使用命名空间形式）

​	/everything-claude-code:plan "添加用户认证"

​	#手动安装（选项2）使用简短形式：

​	#/plan "添加用户认证"

​	#查看可用命令

​	/plugin list everything-claude-code@everything-claude-cod



## Skill

1. ~/.claude/CLAUDE.md 相当于 cursor 的rules





## TOOLCHAIN

1. **cc-switch(⭐️⭐️⭐️⭐️⭐️)** : switch the model of cc

2. **ghostty(⭐️⭐️⭐️⭐️⭐️)** : multi-open cc
3. **claude-hub(⭐️⭐️⭐️) **: shows what's happening in cc - context usage, active tools, running agents, and todo progress
4. **fzf(⭐️⭐️⭐️)** :ctrl+r 搜索全局命令/ ctrl+t+z 模糊项目

5. **zoxide(⭐️⭐️)**: 终端 cd 补全path
   - **__usage__** : z 项目名
