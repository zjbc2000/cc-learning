# cc-learning
ghostty, cc-switch, claude-code: learning from open information source



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



## MCP-config

好用的MCP工具，联网搜索，图片理解，网页读取，连接数据库，查看开源代码库



## Skill

https://skillsmp.com/
<img width="1462" height="726" alt="image" src="https://github.com/user-attachments/assets/9bca688d-dfbd-4468-9e28-1cbcc4931323" />

## Tips

1. ~/.claude/rules/ ：相当于 cursor 的rules

2. 用 ! 直接跑 Bash：直接执行 shell 命令，并把输出加入对话，例如：!npm test。

3. /plan：先规划

4. 图片分析：可复制图片到终端



## TOOLCHAIN

1. **cc-switch(⭐️⭐️⭐️⭐️⭐️)** : switch the model of cc

2. **ghostty(⭐️⭐️⭐️⭐️⭐️)** : multi-open cc
3. **claude-hub(⭐️⭐️⭐️) **: shows what's happening in cc - context usage, active tools, running agents, and todo progress
4. **fzf(⭐️⭐️⭐️)** :ctrl+r 搜索全局命令/ ctrl+t+z 模糊项目

5. **zoxide(⭐️⭐️)**: 终端 cd 补全path
   - **__usage__** : z 项目名
