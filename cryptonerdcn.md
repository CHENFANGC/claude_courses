---
timezone: UTC+9
---

# cryptonerdcn

**GitHub ID:** cryptonerdcn

**Telegram:** @cryptonerdcn

## Self-introduction

cryptonerdcn

## Notes

<!-- Content_START -->
# 2025-07-26

同步发于推特：https://x.com/cryptonerdcn/status/1949058784552440285

尝试了下怎么在Claude code中使用 playwright， 以前都是在cursor里使用。
playwright本身的使用方法不再强调，只说在Claude中需要添加的部分。

最简单的添加：
`claude mcp add playwright npx @playwright/mcp@latest`

个人现在使用下面的rules(放入Claude.md):

## Playwright MCP Usage Rules
### Absolute Prohibitions
- Execution of any code in any form is strictly prohibited
- No code execution to investigate MCP tools
- No approaches involving subprocess or command execution

### Only direct invocation of MCP tools is allowed
- playwright:browser_navigate
- playwright:browser_screenshot
- Other Playwright MCP tools


之后修改UI时提出要求，然后让Claude自行截图和修正即可。

# 2025-07-25

同步发于推特：https://x.com/cryptonerdcn/status/1948669514562122049
看到官方教程的安排和我之前在社内分享时的思路几乎一模一样，愈加觉得我在有限的时间里，还抽出一大段时间来讲LLM只有上下文处理能力，以及Function Call到MCP的演变历程这个安排是合理的。
LLM本身的实现也许可以看作是力大砖飞的魔法，但围绕 LLM 构建起来的工具链、产品和功能，大多归根结底还是上下文工程的延伸，更多的是属于传统开发的领域。
对于并非LLM相关研究者的普通工程师（以及非工程师）来说，有机会参与的真正的挑战与创新，并不在模型本体，而是应该思考，如何以工程化的方式组织如Prompt、Function Call、RAG等模块，使得LLM这一上下文处理引擎能够在特定场景下稳定地产生智能行为--而且还要趁早，不然你想到的创新点可能很快就被做进LLM提供商的SDK，甚至直接被LLM接管。

# 2025-07-24

同步发于TG群组。
个人心得：
1. 如果想要使用Claude code，请直接访问 https://anthropic.skilljar.com/claude-code-in-action
2. https://anthropic.skilljar.com/claude-with-the-anthropic-api 课程对于已经学过openai和吴恩达的课程的同学没什么新东西，学过的可以直接跳到claude自家工具和mcp概念那部分。

3. Claude with Amazon Bedrock和 Claude with Google Cloud's Vertex AI 你不用相关平台的东西就不用学。


个人重点看两个MCP相关的了。


<!-- Content_END -->
