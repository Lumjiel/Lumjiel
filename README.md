# Lumjiel

> **写工具，把重复劳动交给机器。**

AI Agent 工具链 · 逆向工程 · 自动化

最近在把联通云盘的 API 封成 MCP Server —— 25 个工具，模型可以直接调。

---

## 🧰 工具

能被别人直接装、直接用，不依赖我的私有环境。

| 仓库 | 解决什么问题 | 规模 | 怎么用 |
|:--|:--|:--|:--|
| [`wocloud`](https://github.com/Lumjiel/wocloud) | 联通云盘第三方客户端 + MCP Server | 38 个命令 · 25 个 MCP 工具 · 零 npm 依赖 | `node mcp/server.mjs` |
| [`freellm`](https://github.com/Lumjiel/freellm) | 免费 LLM 调用：6 家平台互为备胎，档位优先自动降级 | 6 家 provider · 零依赖 | `pip install git+https://github.com/Lumjiel/freellm.git` |
| [`browser-agent`](https://github.com/Lumjiel/browser-agent) | 给 AI agent 的浏览器手和眼 | HTTP → 油猴 → DOM 三级桥接 | `make install` → 起本地桥接服务 |
| [`deepseek-mindtrace`](https://github.com/Lumjiel/deepseek-mindtrace) | DeepSeek 对话全量导出、分支树还原、中文全文检索 | 油猴全量 + API 增量双轨 | 见 README |
| [`pi-config`](https://github.com/Lumjiel/pi-config) | 终端编码代理 Pi 的整套配置 | 20 插件 · 17 Skill · 1 MCP | 一条命令完整复刻 |
| [`tampermonkey-scripts`](https://github.com/Lumjiel/tampermonkey-scripts) | 浏览器用户脚本合集 | 7 个脚本 · 3 个平台 | `npm run build` → `dist/*.user.js` |

## 🎮 作品

做完的、给人玩的，不一定给别人用。

| 仓库 | 说明 | 怎么用 |
|:--|:--|:--|
| [`PBTI`](https://github.com/Lumjiel/PBTI) | 乒乓球人格测评：30 题 · 25 种人格 · 雷达图与海报分享 | `npm install && npm run dev` |
| [`zxtx`](https://github.com/Lumjiel/zxtx) | 智能旅游平台：AI 线路规划 + 组队 + 门票秒杀，Spring Boot + LangChain4j | 见 README |

## 🗄 归档

不再维护，只读。留着是因为外链和迁移记录还在用。

| 仓库 | 说明 |
|:--|:--|
| [`Todolist`](https://github.com/Lumjiel/Todolist) | 极简 Todo（Vue）· 2026-05 起停止维护 |
| [`Observatory`](https://github.com/Lumjiel/Observatory) | 终端风格学习面板：追踪编码 / 阅读活动 |
| [`x-list-following-picker`](https://github.com/Lumjiel/x-list-following-picker) | X 列表批量导入 · 已并入 `tampermonkey-scripts`，此处仅保留历史 |

## 📚 上游参考

fork，不是我的作品，留着当参照。

| 仓库 | 说明 |
|:--|:--|
| [`IRIS`](https://github.com/Lumjiel/IRIS) | 竞品调研 Agent（LangGraph 多 Agent）· 有本地开发分支 |
| [`wechat-intelligence-hub`](https://github.com/Lumjiel/wechat-intelligence-hub) | Local-first 微信情报系统 · 仅作上游参照 |

---

<sub>公开仓库的收录规则：[POLICY.md](POLICY.md) —— **默认私有，通过三条准入才公开。** 本页本地维护于 `~/projects/profile-readme/`，改完 push 即生效。</sub>
