# Lumjiel

写工具，把重复劳动交给机器。

AI Agent 工具链 · 逆向工程 · 自动化 · [个人站](https://lumjiel.top)

---

## 工具

装得上、跑得起来的那几个。README 里都写了为什么做、卡在哪、怎么验证。

### [wocloud](https://github.com/Lumjiel/wocloud)

联通云盘第三方客户端 + MCP Server。38 个命令，25 个 MCP 工具，零 npm 依赖。

```bash
node mcp/server.mjs          # stdio — 给本地 agent
node mcp/server.mjs --http   # 8788 — 给远程 agent
```

### [freellm](https://github.com/Lumjiel/freellm)

六个免费 LLM 平台互为备胎。一家额度用完自动降档，调用方无感。

```bash
pip install git+https://github.com/Lumjiel/freellm.git
```

### [browser-agent](https://github.com/Lumjiel/browser-agent)

给 agent 装上眼睛和手。HTTP → 油猴 → DOM 三级桥接，不用起浏览器调试端口。

```bash
make install && make run
```

### [pi-config](https://github.com/Lumjiel/pi-config)

终端编码代理 Pi 的整套配置。20 插件 / 17 Skill / 1 MCP，一条命令复刻。

### [tampermonkey-scripts](https://github.com/Lumjiel/tampermonkey-scripts)

浏览器用户脚本合集。7 个脚本，3 个平台，构建产物直接装。

```bash
npm run build   # → dist/*.user.js
```

## 作品

做完了给人玩的，不一定给别人用。

- **[PBTI](https://github.com/Lumjiel/PBTI)** — 乒乓球人格测评。30 题，25 种人格，雷达图 + 海报分享。
- **[zxtx](https://github.com/Lumjiel/zxtx)** — 智能旅游平台。AI 线路规划 + 组队 + 门票秒杀，Spring Boot + LangChain4j。

## 归档

只读，留着是因为外链还在用。

- **[Todolist](https://github.com/Lumjiel/Todolist)** — 极简 Todo（Vue）
- **[Observatory](https://github.com/Lumjiel/Observatory)** — 终端风格学习面板
- **[x-list-following-picker](https://github.com/Lumjiel/x-list-following-picker)** — 已并入 `tampermonkey-scripts`

## 上游参考

fork，不是我的作品。

- **[IRIS](https://github.com/Lumjiel/IRIS)** — 竞品调研 Agent（LangGraph）
- **[wechat-intelligence-hub](https://github.com/Lumjiel/wechat-intelligence-hub)** — Local-first 微信情报系统

---

<sub>公开仓库的收录规则：[POLICY.md](https://github.com/Lumjiel/Lumjiel/blob/main/POLICY.md) — 默认私有，通过三条准入才公开。</sub>
