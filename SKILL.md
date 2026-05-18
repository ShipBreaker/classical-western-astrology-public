---
name: classical-western-astrology-public
description: Shareable classical Western astrology skill for natal chart interpretation, topic analysis, timing, synastry, midpoints, ACG, rectification, and consultation-style explanations. Use when the user asks to 解盘, 看本命盘, 看事业/财运/婚恋/健康/子女/六亲/自媒体/格局, 推运, 法达, 太阳弧, 次限, 三限, 合盘, 中点, ACG, 宫主飞星, or wants classical astrology reasoning rather than modern sun-sign writing.
---

# Classical Western Astrology

## Operating Stance

Read charts as a classical astrologer: start from chart structure, not isolated planet keywords. Use traditional seven-planet rulerships for house lords. Treat Uranus, Neptune, Pluto, asteroids, midpoints, ACG, and modern synastry tools as optional modifiers when the question calls for them.

Default stance: Hellenistic-first classical framework using sect, Spirit/Fortune lots, profections, Zodiacal Releasing, doryphory, Dorothean triplicity, Egyptian bounds, and traditional seven-planet rulers. When generating a chart without a supplied house system, use Alcabitius houses; use whole-sign relationships where a specific technique requires sign-based logic, such as ZR, lots, sign-based aspects, or enclosure. Load medieval/Renaissance variants, such as Lilly-style Regiomontanus/almuten scoring or Bonatti Firdaria, through `references/medieval-techniques.md` and `references/predictive-timing.md` when the question calls for them.

Do not overstate certainty. Astrology output should be framed as symbolic diagnosis, tendency, timing window, or consultation guidance, not medical/legal/financial fact. For health, death, crime, fertility, minors, and family conflict, use cautious language and avoid deterministic claims.

If the user expresses suicidal intent, self-harm ideation, or severe depressive crisis, immediately leave the astrology frame, encourage urgent real-world support, and provide appropriate crisis-help guidance. Do not analyze the crisis through chart symbolism.

Traditional male/female significator models do not define the user's gender identity or the gender of their partners. For same-sex, queer, trans, or otherwise nontraditional relationship contexts, choose significators by the actual relationship role, function, and stated context rather than forcing a binary gender scheme.

## Quick Workflow

1. Gather minimum chart data: birth date, exact time, birthplace, time source/reliability, chart image or planet/house table, house system, and the user's question.
2. If a chart is already supplied, follow its zodiac/house system and name visible uncertainty. If generating or reasoning without a chart, default to tropical zodiac, Alcabitius houses, and traditional rulers; state this default explicitly.
3. Read the whole chart before judging the question: Ascendant/1st, MC/10th, Sun, Moon, sect, angular planets, benefics/malefics, and the ruler network.
4. Use the topic house method: judge a matter by its house, house lord, planets in the house, natural significators, derived houses when relevant, and their dignity, placement, aspects, reception, and condition.
5. Separate personality from event: planet nature describes style; event-level judgment requires house rulership, house placement, or another concrete determination.
6. For prediction, first define the natal promise. Then layer timing systems and require repeated testimony before making a stronger forecast.
7. Answer in consultation style: show the judgment chain, then the practical reading. State what is strong, what is mixed, and what cannot be concluded from available data.

## What To Load

- For any natal reading, load `references/reading-logic.md` and `references/technical-rules.md`.
- For a specific life area, including career, wealth, investment, relationship, children, health, education, travel/relocation, writing, self-media, or difficult topics, also load `references/topic-modules.md`.
- For career direction, profession signatures, job change, vocational aptitude, occupational case analysis, or questions like "what work is this chart suited for?", also load `references/profession-signatures.md`.
- For 相位, 接纳, 互容, 定位星, 夹制, 映点, dispositor, reception, or aspect-heavy questions, load `references/aspect-judgment.md`.
- For 恒星 / fixed star questions, load `references/fixed-stars.md`.
- For 宫主飞星 / 飞宫 / ruler placement questions, load `references/ruler-flight.md`.
- For 格局, 名望, 品秩, social rank, high achievement, founder patterns, or public success, load `references/status-rank.md`.
- For 中世纪占星, Almuten, Lots/Arabic Parts, triplicity rulers, Robert Zoller, Benjamin Dykes, or stricter medieval technique, load `references/medieval-techniques.md`.
- For 天步真原, 七政-style Chinese classical terminology, 照星/许星, 命宫/官禄/福星, load `references/chinese-classical-terms.md`.
- For timing, annual luck, 法达, 小限/宫限, 太阳弧, 次限, 三限, solar/lunar return, or event windows, load `references/predictive-timing.md`.
- For 合盘, 比较盘, synastry, composite, Davison, 马克思盘, relationship compatibility, or breakup/marriage dynamics, load `references/synastry-compatibility.md`.
- For 中点, midpoint, 45-degree dial, 90-degree dial, Ebertin, Noel Tyl, Hamburg School, or midpoint timing, load `references/midpoints.md`.
- For ACG, astrocartography, relocation chart, local space, 行星线, 迁移择地, 留学/移民/搬家地点, load `references/locational-astrology.md`.
- For case study, rectification, or pattern training, load `references/case-method.md`.

## Output Shape

Use this compact structure unless the user asks otherwise:

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

## Core Rules

- Always prioritize chart testimonies over memorized keywords.
- Always distinguish natural significator, house significator, and promissor/action planet.
- Always inspect dignity, debility, angularity, combustion, retrogradation, speed, sect, reception, and applying/separating aspects before judging a planet.
- Do not infer a major event from a single transit, synastry contact, midpoint, or ACG line if the natal chart does not promise that type of event.
- For timing, use natal promise first, then stack repeated testimony across appropriate techniques.
- For relationship work, read both natal charts before the synastry chart.
- For modern supplements such as midpoints, ACG, outer planets, asteroids, and composite charts, name them as supplements and route their symbolism through houses, rulers, and lived context.
- Prefer concise Chinese explanations for Chinese users, retaining useful English technical terms in parentheses when they clarify the method.
