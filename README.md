# 古典西洋占星 Codex Skill

面向中文咨询、学习与案例复盘的 Codex skill。它把古典西洋占星的判断链整理成可复用的工作流，用于本命盘、专题分析、推运、合盘、中点、ACG、校时与案例训练。

这个 skill 的重点不是泛化的星座描述，而是从盘面结构、宫主关系、星体状态、相位接纳和时间技法出发，形成有证据层级的咨询式结论。

## 适用场景

| 场景 | 可处理的问题 |
| --- | --- |
| 本命解读 | 命格主轴、优势短板、事业方向、财富模式、关系结构、学习与迁移 |
| 专题判断 | 事业、财运、婚恋、健康、子女、六亲、自媒体、名望与社会位置 |
| 推运分析 | 法达、宫限/小限、黄道释放、返照、太阳弧、次限、三限、行运 |
| 关系分析 | 比较盘、合盘、组合盘、关系阶段、分合窗口和互动模式 |
| 辅助技法 | 中点、45 度盘、90 度盘、恒星、ACG、迁移盘、Local Space |
| 学习训练 | 宫主飞星、尊贵无力、接纳互容、中世纪技法、案例复盘与校时 |

## 安装

1. 下载或克隆本仓库。
2. 将文件夹放入 Codex skills 目录，例如：

   ```text
   C:\Users\<你的用户名>\.codex\skills\classical-western-astrology-public
   ```

3. 重新打开 Codex，或开启一个新会话，让 skill 被重新发现。
4. 在对话中使用相关触发词调用。

## 调用示例

```text
用 classical-western-astrology-public 解读这张本命盘。
请按古典西洋占星看事业和财运。
用法达、太阳弧、次限和行运判断未来一年。
请用宫主飞星、接纳和互容分析婚恋结构。
根据这几件已发生事件，帮我做出生时间校正。
```

## 建议提供的信息

完整判断通常需要以下资料：

```text
出生日期：
出生时间：
出生地：
出生时间来源和可靠度：
星盘截图或行星/宫位表：
黄道与宫制：
想问的具体问题：
目标时间范围：
已发生的重要事件：
```

如果已经有星盘截图，可以直接上传截图并说明问题。资料不完整时，skill 会先标明判断边界，再补问必要信息。

## 判断框架

这个 skill 默认按以下顺序工作：

1. 读取整体盘面：上升、命主星、MC、太阳、月亮、昼夜、角宫星、吉凶星。
2. 锁定主题宫位：本宫、宫主、宫内星、自然征象星、派生宫。
3. 判断星体状态：庙旺陷弱、尊贵无力、角续果、燃烧、逆行、速度、昼夜得势。
4. 分析关系结构：入相/出相、接纳、互容、定位星、夹制、映点、南北交。
5. 合成证据层级：强证据、混合证据和辅助证据分开说明。
6. 叠加时间技法：先确认本命承诺，再使用推运系统定位窗口。
7. 输出咨询结论：把术语转译成可理解、可验证、可行动的建议。

## 输出风格

默认回答会尽量保持清晰的证据链：

```markdown
**盘面总纲**
一句话说明命格主轴、强弱、最关键的宫位/星体/结构。

**判断链**
- 证据 1：宫位 / 宫主 / 星体状态 -> 含义
- 证据 2：相位 / 接纳 / 飞星 / 推运 -> 含义
- 证据 3：重复证据或案例逻辑 -> 含义

**结论**
给出可理解、可执行的解读；强证据先说，弱证据标明为辅助。

**边界**
说明出生时间、宫制、资料缺口、现实条件或高风险主题的限制。
```

## 项目结构

```text
classical-western-astrology-public/
  README.md
  SKILL.md
  agents/
    openai.yaml
  references/
    aspect-judgment.md
    case-method.md
    chinese-classical-terms.md
    fixed-stars.md
    locational-astrology.md
    medieval-techniques.md
    midpoints.md
    predictive-timing.md
    profession-signatures.md
    reading-logic.md
    ruler-flight.md
    status-rank.md
    synastry-compatibility.md
    technical-rules.md
    topic-modules.md
```

## 参考模块

| 文件 | 主题 |
| --- | --- |
| `reading-logic.md` | 本命解读总流程、问题转译、咨询边界 |
| `technical-rules.md` | 七政、尊贵、昼夜、宫位力量、燃烧、逆行等基础规则 |
| `topic-modules.md` | 事业、财运、婚恋、健康、子女、教育、迁移、自媒体等主题 |
| `aspect-judgment.md` | 相位、接纳、互容、定位星、夹制、映点、南北交 |
| `ruler-flight.md` | 宫主飞星和宫位主题转移 |
| `predictive-timing.md` | 法达、宫限/小限、黄道释放、返照、太阳弧、次限、三限、行运 |
| `profession-signatures.md` | 职业取象、职业适配、行业选择、转行和职业案例判断 |
| `synastry-compatibility.md` | 比较盘、合盘、组合盘、关系阶段和关系事件 |
| `midpoints.md` | 中点、45 度盘、90 度盘、太阳弧与中点触发 |
| `locational-astrology.md` | ACG、迁移盘、Local Space 和择地判断 |
| `medieval-techniques.md` | Almuten、Lots、三分主星、中世纪框架 |
| `chinese-classical-terms.md` | 中文古典术语和七政式表达转换 |
| `status-rank.md` | 格局、名望、品秩、事业高度和社会位置 |
| `fixed-stars.md` | 恒星判断 |
| `case-method.md` | 案例复盘、校时、模式训练和反过拟合规则 |

## 使用边界

占星判断适合作为象征性分析、趋势整理和咨询参考。涉及健康、法律、投资、生育、未成年人、家庭冲突或重大人生选择时，应结合现实资料与专业意见，避免把单一星象当作决定性结论。

本 skill 会优先给出证据链和不确定性说明，不做死亡断言、疾病诊断、犯罪结论、收益承诺或他人真实意图判定。

## 维护建议

- 更新 `references/` 后，重新打开 Codex 或开启新会话以刷新 skill。
- 新增判断规则时，优先写成可复用流程、证据层级或案例校验方法。
- 单个案例中的特殊结论不要直接升级为通用规则；只有反复出现、且能被盘面结构支持的模式才适合沉淀。
