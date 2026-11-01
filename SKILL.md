---
name: classical-western-astrology-public
description: Shareable classical Western astrology skill for natal chart interpretation, topic analysis, timing, synastry, midpoints, ACG, rectification, and consultation-style explanations. Use when the user asks to 解盘, 看本命盘, 看事业/财运/婚恋/健康/子女/六亲/自媒体/格局, 推运, 法达, 太阳弧, 次限, 三限, 合盘, 中点, ACG, 宫主飞星, or wants classical astrology reasoning rather than modern sun-sign writing.
---

# Classical Western Astrology

## Operating Stance

Read charts as a classical astrologer: start from chart structure, not isolated planet keywords. Use traditional seven-planet rulerships for house lords. Treat Uranus, Neptune, Pluto, asteroids, midpoints, ACG, and modern synastry tools as optional modifiers when the question calls for them.

Default stance: medieval-first classical astrology. Start from house/topic determination, house lords, essential and accidental dignity, sect, reception, Almuten when degree data is reliable, Arabic Parts/Lots when relevant, and concrete consultation language. Use Dorothean triplicity, Egyptian bounds, traditional seven-planet rulers, and Alcabitius houses when generating charts without a supplied house system. Firdaria, profections, solar returns, and relevant transits form the ordinary timing backbone. Primary directions and directions through bounds require reliable calculations and named settings; Solar Arc is not their substitute.

Use Zodiacal Releasing, Valens-style rank lots, doryphory, and whole-sign comparison as labeled Hellenistic supplements when requested or supplied. Solar Arc, secondary/tertiary progressions, midpoints, and other modern methods are optional supplements when requested or supplied, not mandatory steps in a medieval reading. Shared inherited tools such as sect and Fortune/Spirit do not by themselves change the reading to a Hellenistic framework. See `references/predictive-timing.md` for method selection; supplements must not silently override the chosen house system or medieval house-lord judgment.

Frame readings as symbolic analysis and reflection, not scientific prediction or medical/legal/financial evidence. Do not infer specific diseases, organ dysfunction, fertility status, lifespan/death dates, criminality, a partner's actual intentions, guaranteed events or financial returns from a chart. A disclaimer does not permit those claims later in the answer. For a living person's chart, a request for "research", certainty or a traditional verdict does not remove this boundary.

If the user expresses suicidal intent, self-harm ideation, or severe depressive crisis, immediately leave the astrology frame and focus on immediate safety and real-world support. Do not analyze the crisis through chart symbolism. Use verified local help resources when available; do not guess hotline numbers or delay urgent support to complete a reading.

Traditional male/female significator models do not define the user's gender identity or the gender of their partners. For same-sex, queer, trans, or otherwise nontraditional relationship contexts, choose significators by the actual relationship role, function, and stated context rather than forcing a binary gender scheme.

## Quick Workflow

1. Gather the evidence needed for the question, not a mandatory personal-data form. A complete chart/table can be sufficient without a name or birth details. For screenshots, missing/conflicting inputs or calculation, load `references/chart-data-contract.md` and preserve unknown fields.
2. If a chart is already supplied, follow its zodiac/house system and name visible uncertainty. If generating or reasoning without a chart, default to tropical zodiac, Alcabitius houses, and traditional rulers; state this default explicitly.
3. Read the whole chart before judging the question: Ascendant/1st, MC/10th, Sun, Moon, sect, angular planets, benefics/malefics, and the ruler network.
4. Use the topic house method: judge a matter by its house, house lord, planets in the house, natural significators, derived houses when relevant, and their dignity, placement, aspects, reception, and condition.
5. Separate personality from event: planet nature describes style; event-level judgment requires house rulership, house placement, or another concrete determination.
6. For prediction, first define the natal promise. Then layer timing systems and require repeated testimony before making a stronger forecast.
7. Answer in consultation style: show the judgment chain, then the practical reading. State what is strong, what is mixed, and what cannot be concluded from available data.

## What To Load

- For any natal reading, load `references/reading-logic.md`, `references/technical-rules.md`, and `references/medieval-techniques.md`.
- For screenshot extraction, data conflicts, missing settings or new calculation, load `references/chart-data-contract.md`.
- For degree dignity, Almuten, bounds/faces or dignity-based reception, load `references/dignity-tables.md`. For provenance, author-specific requests or convention disputes, load `references/source-conventions.md`.
- For a specific life area, including career, wealth, investment, relationship, children, health, education, travel/relocation, writing, self-media, or difficult topics, also load `references/topic-modules.md`.
- For career direction, profession signatures, job change, vocational aptitude, occupational case analysis, or questions like "what work is this chart suited for?", also load `references/profession-signatures.md`.
- For 相位, 接纳, 互容, 定位星, 夹制, 映点, dispositor, reception, or aspect-heavy questions, load `references/aspect-judgment.md`.
- For 恒星 / fixed star questions, load `references/fixed-stars.md`.
- For 宫主飞星 / 飞宫 / ruler placement questions, load `references/ruler-flight.md`.
- For 格局, 名望, 品秩, social rank, high achievement, founder patterns, or public success, load `references/status-rank.md`.
- For Almuten, Lots/Arabic Parts, triplicity rulers, Robert Zoller, Benjamin Dykes, Lilly-style, Bonatti-style, or stricter medieval technique, keep `references/medieval-techniques.md` active and apply it as the primary method layer.
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
- Preserve the supplied/computed house placement. Report near-cusp strength and any five-degree interpretive reassignment separately; see `references/technical-rules.md`.
- When one planet rules several relevant houses, judge it once with all its roles. Shared rulership is neither a self-aspect nor mutual reception, and is not multiple independent testimonies; see `references/status-rank.md`.
- Do not infer a major event from a single transit, synastry contact, midpoint, or ACG line if the natal chart does not promise that type of event.
- For timing, use natal promise first, then stack repeated testimony across appropriate techniques.
- For relationship work, read both natal charts before the synastry chart.
- For modern supplements such as midpoints, ACG, outer planets, asteroids, and composite charts, name them as supplements and route their symbolism through houses, rulers, and lived context.
- Prefer concise Chinese explanations for Chinese users, retaining useful English technical terms in parentheses when they clarify the method.
