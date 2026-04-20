# cc-learning
_claude-code: learning from open-source project._



## Let's go

**# harness is all you need**

_claude_

**CLAUDE.md**:只记录目标、架构，【约束（技术栈）和测试】。




##  Task

**/plan**： _拆解出task_

**# 复杂task采用team模式：分文件夹，多窗口多subagent，获取关键context给主agent**



## Command

_/clear /compact: for context_

_/pua:pua：keep the loop continue_

_/btw：不中断对话问一个简短问题_

_/rewind：回退代码_

_!：bash模式_



## MCP/Tool

_配置好用的MCP/工具：图片理解，网页读取，查看GitHub同类项目_

npm install -g @modelcontextprotocol/server-github



## Skill

_**/skill-creator：创建属于你的skill吧！**_

_开源网站：https://skillsmcp.com_

<img width="1462" height="726" alt="image-20260327153613563" src="https://github.com/user-attachments/assets/244da3d2-482d-4e27-b7f2-1cad56994849" />




## Plugin
_/plugin: 可以下载官方插件_ 

- **superpowers（日常开发）**
  
❯ /plugin marketplace add obra/superpowers-marketplace


❯ /plugin install superpowers@superpowers-marketplace

- **everything-claude-code（harness-learning）**
  
- **web-access/claude-mem（基础设施：联网加记忆）**

- **claude-hub**



_总结：可以从everything-clause-code中汲取到一些好用的harness_

1. _~/.claude/rules/ ：相当于 cursor 的rules_
2. _输入图片和语音提效_
3. _创建自己经常使用的skill或command_



## Subagent/Multi-agents

1. 长程规划/反思修正
2. 需要用到不同领域的知识

总之遇到会占用过多上下文或污染上下文（复杂或有冲突）的任务时，

复杂、模糊、综合性、需要拆解的任务时，

就需要用多智能体系统（MAS）



## TOOLCHAIN
- 切换工具：
1. **cc-switch(⭐️⭐️⭐️⭐️⭐️)** : _switch the model of cc_
- 日常使用：
2. **ghostty(⭐️⭐️⭐️⭐️⭐️)** : _多开claude-code_
3. **claude-hub(⭐️⭐️⭐️)**: _shows context usage, active tools, running agents, and todo progress_
4. **语音输入**: _含语音功能的输入法，typeoff等模型_
6. **远程控制**: _happy/remote，其他设备控制claude_
- 终端工具：
7. **fzf(⭐️⭐️⭐️)** :_ctrl+r 搜索全局命令/ ctrl+t+z 模糊项目_
8. **zoxide(⭐️⭐️)**: _终端 cd 补全path_
   - **__usage__** : _z 项目名_



