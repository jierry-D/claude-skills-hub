<!-- STRATEGY -->
## 策略说明（持续更新）

### 搜索优先词（按效果排序）
1. `claude-code skill` — 最广泛覆盖，配合星数过滤（效果最稳定）
2. `claude mcp plugin` — MCP 服务器和扩展插件
3. `claude-code knowledge graph codebase intelligence` — 高质量工具专项
4. `claude code game development agent studio skill` — 垂直领域（游戏、艺术）
5. `claude mcp server tool productivity` — MCP 服务器
6. `claude-code hooks extension plugin` — 扩展生态
7. `anthropic claude tool productivity developer` — 广泛工具搜索
8. `claude-code devops skill` — DevOps 专项（下周新增）
9. `claude skill data science` — 数据科学专项（下周新增）

### 星数阈值（动态调整）
- 当前门槛: 26,000+ stars（广泛类）
- 垂直专项领域: 1,000+ 可酌情考虑（代码审查更严格）
- 已排除大型非专项仓库（JeecgBoot、CowAgent 等）
- 已收录项目不重复收录（全量排重）

### 安全标准（不可更改，权重固定 40%）
详见 SECURITY.md

---

## 2026-06-29 — Daily Harvest (Monday — Weekly Strategy Review)

### 8 Items Added
| # | Name | Type | Stars | Source | Security | Score |
|---|------|------|-------|--------|----------|-------|
| 1 | Andrej Karpathy Skills | skill | 183,962 ⭐ | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | ✅ PASS | 95/100 |
| 2 | Open Design | plugin | 72,415 ⭐ | [nexu-io/open-design](https://github.com/nexu-io/open-design) | ✅ PASS | 93/100 |
| 3 | Awesome Claude Code | skill | 47,531 ⭐ | [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | ✅ PASS | 90/100 |
| 4 | Agents Plugin Marketplace | plugin | 37,296 ⭐ | [wshobson/agents](https://github.com/wshobson/agents) | ✅ PASS | 90/100 |
| 5 | Marketing Skills | skill | 35,312 ⭐ | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | ✅ PASS | 87/100 |
| 6 | Claude Plugins Official | plugin | 31,264 ⭐ | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | ✅ PASS | 87/100 |
| 7 | Scientific Agent Skills | skill | 29,521 ⭐ | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | ✅ PASS | 88/100 |
| 8 | Humanizer | skill | 26,600 ⭐ | [blader/humanizer](https://github.com/blader/humanizer) | ✅ PASS | 85/100 |

### Strategy Used Today
- Search queries: `claude-code skill`, `claude mcp plugin`, `claude hooks extension productivity`, `anthropic claude tool productivity developer`
- Total candidates evaluated: ~70
- Rejected (security fail): 0 | Rejected (duplicate / low score): 62
- Star threshold applied: 26,000+
- Category diversity: 8 distinct categories (behavior tuning, design tool, curated list, marketplace, marketing, official directory, science, writing quality)

### Self-Optimization Notes
与前三日对比：
- 2026-06-26: 低星精品为主（平均 ~700⭐）
- 2026-06-27: 垂直领域专项（游戏开发、安全、浏览器能力），平均 ~30k⭐
- 2026-06-28: 高星广覆盖（token 优化、职业生产力、学术研究），平均 ~61k⭐
- 2026-06-29（今日）: 继续高星策略，引入全新类别（行为调优、设计工具、营销垂直、官方目录、写作质量），平均 ~57k⭐
- **趋势**: 每日引入 1-2 个全新类别，保持内容差异化；插件比例偏低（21%），需补足
- **安全标准**: 固定不变，本次 8/8 通过，0 安全失败

### Weekly Strategy Review (2026-06-29 — Monday)

#### 过去4天分析（2026-06-26 至 2026-06-29）
| 日期 | 收录数 | Skills | Plugins | 平均星数 | 安全拒绝 |
|------|--------|--------|---------|----------|----------|
| 2026-06-26 | 8 | 4 | 4 | ~700⭐ | 0 |
| 2026-06-27 | 8 | 6 | 2 | ~30,500⭐ | 0 |
| 2026-06-28 | 8 | 8 | 0 | ~61,700⭐ | 0 |
| 2026-06-29 | 8 | 5 | 3 | ~57,987⭐ | 0 |
| **合计** | **32** | **23** | **9** | — | **0** |

#### 类别覆盖现状（截至 2026-06-29，共 24 项）
**Skills (19项):** Agent Harness · Behavior/CLAUDE.md · UI/UX Design · Token Optimization · Career · Academic Research · Research Automation · Planning · Security/Cybersecurity · Game Development · Writing Quality · Curated Reference · Marketing · Scientific Research · Engineering Workflow · Frontend/Slides

**Plugins (5项):** Knowledge Graph · MCP Memory · Design Tool · Plugin Marketplace · Official Directory

#### 类别缺口分析（下周优先补足）
1. **DevOps / CI-CD** — 无覆盖，高需求（搜索词: `claude-code devops skill`）
2. **Data Science / ML Engineering** — 有科学类但缺工程化工具
3. **Legal / Compliance** — 无覆盖
4. **Education / Learning** — 无覆盖
5. **Database / SQL** — pg-aiguide（Timescale, 1,773⭐）值得专项考虑

#### 策略调整建议（安全标准不可更改）
1. **新增搜索词**: `claude-code devops skill`, `claude skill data science`, `claude code legal compliance`, `claude mcp database`
2. **星数策略**: 广泛类维持 25,000+；垂直专项可降至 1,000+（需更严格代码审查）
3. **Awesome-list 控制**: 当前 2/24（8.3%），后续控制在总数 <10% 内
4. **插件比例目标**: 当前 21% → 目标 30%；优先寻找高质量 MCP 服务器
5. **安全标准**: 永久固定 40% 权重，不可更改，不可软化

---

## 2026-06-28 — Daily Harvest

### 8 Items Added
| # | 名称 | 类型 | Stars | 来源 | 安全 | 得分 |
|---|------|------|-------|------|------|------|
| 1 | ECC Agent Harness | skill | 222,624 ⭐ | [affaan-m/ECC](https://github.com/affaan-m/ECC) | ✅ PASS | 99/100 |
| 2 | Academic Research Skills | skill | 34,884 ⭐ | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | ✅ PASS | 95/100 |
| 3 | Agent Skills (Addy Osmani) | skill | 67,274 ⭐ | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | ✅ PASS | 93/100 |
| 4 | Last30Days Skill | skill | 47,175 ⭐ | [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | ✅ PASS | 92/100 |
| 5 | UI UX Pro Max Skill | skill | 97,170 ⭐ | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | ✅ PASS | 91/100 |
| 6 | Planning with Files | skill | 24,028 ⭐ | [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | ✅ PASS | 91/100 |
| 7 | Career-Ops | skill | 56,179 ⭐ | [santifer/career-ops](https://github.com/santifer/career-ops) | ✅ PASS | 89/100 |
| 8 | Caveman | skill | 77,438 ⭐ | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | ✅ PASS | 88/100 |

### 策略说明
- 搜索词: `claude-code skill topic:claude-code`, `claude mcp server tool productivity`, `claude-code hooks extension plugin`
- 候选总数: ~65 个
- 安全筛查通过: 12 个 | 安全失败: 0 | 低分淘汰: 4 个
- 星数中位数（今日入选）: 61,727

### 分类多样性
- Agent Harness: 1 项（ECC — 67 agents, 271 skills, AgentShield）
- Academic/Research: 1 项（academic-research-skills — 42 agents, citation verification）
- Engineering Workflow: 1 项（agent-skills — 24 skills, Addy Osmani / Google Chrome）
- Research Automation: 1 项（last30days-skill — 13+ platforms, engagement scoring）
- UI/UX Design: 1 项（ui-ux-pro-max-skill — 67 styles, 161 palettes, 22 stacks）
- Project Planning: 1 项（planning-with-files — persistent context, SHA-256 attestation）
- Career/Productivity: 1 项（career-ops — 14 modes, Go dashboard, 45+ portals）
- Token Optimization: 1 项（caveman — 65% reduction, benchmarked）

### Self-Optimization Notes
与前三日对比：
- 2026-06-25: 低星精品为主
- 2026-06-26: 广泛覆盖多类别（平均 ~17k⭐）
- 2026-06-27: 垂直领域专项（游戏开发、网络安全、浏览器能力），平均 ~30k⭐
- 2026-06-28（今日）: 高星广覆盖，引入 token 优化、职业生产力、学术研究等新类别，平均星数大幅提升至 ~61k⭐
- **趋势**: 越来越多高质量仓库涌现，`topic:claude-code` 搜索效率最高
- **安全标准**: 固定不变，本次 12 个候选全部通过安全审查

---

## 2026-06-27 — Daily Harvest

### 8 Items Added
| # | 名称 | 类型 | Stars | 来源 | 安全 | 得分 |
|---|------|------|-------|------|------|------|
| 1 | Codebase Memory MCP | plugin (mcp) | 15,619 ⭐ | [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | ✅ PASS | 95/100 |
| 2 | Anthropic Cybersecurity Skills | skill | 21,801 ⭐ | [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) | ✅ PASS | 92/100 |
| 3 | Graphify | plugin | 72,588 ⭐ | [safishamsi/graphify](https://github.com/safishamsi/graphify) | ✅ PASS | 90/100 |
| 4 | Dev Browser | skill | 6,333 ⭐ | [SawyerHood/dev-browser](https://github.com/SawyerHood/dev-browser) | ✅ PASS | 90/100 |
| 5 | Antigravity Awesome Skills | skill | 41,782 ⭐ | [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | ✅ PASS | 90/100 |
| 6 | Taste Skill | skill | 51,568 ⭐ | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | ✅ PASS | 87/100 |
| 7 | Claude Code Game Studios | skill | 22,339 ⭐ | [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | ✅ PASS | 87/100 |
| 8 | Frontend Slides | skill | 23,308 ⭐ | [zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides) | ✅ PASS | 83/100 |

### 策略说明
- 搜索词: `claude-code skill topic:claude-code`, `claude mcp server tool productivity`, `claude-code hooks extension plugin`, `claude-code knowledge graph codebase intelligence`, `claude code game development agent studio skill`
- 候选总数: ~75 个
- 安全筛查通过: 12 个 | 安全失败: 0 | 低分淘汰: 4 个
- 星数中位数（今日入选）: 22,070

### 分类多样性
- MCP Server: 1 项（codebase-memory-mcp）
- Plugin/知识图谱: 1 项（graphify）
- Skills/安全: 1 项（Anthropic-Cybersecurity-Skills）
- Skills/浏览器: 1 项（dev-browser）
- Skills/元库: 1 项（antigravity-awesome-skills）
- Skills/输出质量: 1 项（taste-skill）
- Skills/游戏开发: 1 项（Claude-Code-Game-Studios）
- Skills/演示文稿: 1 项（frontend-slides）

### Self-Optimization Notes
与前两日对比：
- 2026-06-25: 以低星精品为主（平均 ~30k⭐）
- 2026-06-26: 广泛覆盖多类别（平均 ~17k⭐）
- 2026-06-27（今日）: 引入专项垂直类别（游戏开发、网络安全、浏览器能力），平均星数 ~30k⭐
- **趋势**: 垂直领域 skill 呈现差异化价值，建议持续搜索游戏、安全、创意类专项
- **安全标准**: 固定不变，本次 12 个候选全部通过，验证了搜索词的质量

---

## 2026-06-26 — Daily Harvest

### 8 Items Added
| # | 名称 | 类型 | Stars | 来源 | 安全 |
|---|------|------|-------|------|------|
| 1 | MCPJam Inspector | plugin (mcp-tool) | 2,034 ⭐ | [MCPJam/inspector](https://github.com/MCPJam/inspector) | ✅ PASS |
| 2 | LinkedIn MCP Server | plugin (mcp-server) | 2,516 ⭐ | [stickerdaniel/linkedin-mcp-server](https://github.com/stickerdaniel/linkedin-mcp-server) | ⚠️ |
| 3 | Claude Forge | skill | 757 ⭐ | [sangrokjung/claude-forge](https://github.com/sangrokjung/claude-forge) | ✅ PASS |
| 4 | MCP-NixOS | plugin (mcp-server) | 722 ⭐ | [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) | ✅ PASS |
| 5 | Storybloq | skill | 629 ⭐ | [Storybloq/storybloq](https://github.com/Storybloq/storybloq) | ✅ PASS |
| 6 | Claude Code Skills (lev) | skill | 501 ⭐ | [levnikolaevich/claude-code-skills](https://github.com/levnikolaevich/claude-code-skills) | ✅ PASS |
| 7 | ComfyUI MCP | plugin (mcp-server) | 185 ⭐ | [artokun/comfyui-mcp](https://github.com/artokun/comfyui-mcp) | ✅ PASS |
| 8 | PostHog AI Plugin | plugin | 57 ⭐ | [PostHog/ai-plugin](https://github.com/PostHog/ai-plugin) | ⚠️ |
