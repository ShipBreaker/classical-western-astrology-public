# Technical Rules

## Traditional Rulerships

Use traditional seven-planet rulerships when judging house lords:

| Sign | Ruler |
| --- | --- |
| Aries 白羊 | Mars 火星 |
| Taurus 金牛 | Venus 金星 |
| Gemini 双子 | Mercury 水星 |
| Cancer 巨蟹 | Moon 月亮 |
| Leo 狮子 | Sun 太阳 |
| Virgo 处女 | Mercury 水星 |
| Libra 天秤 | Venus 金星 |
| Scorpio 天蝎 | Mars 火星 |
| Sagittarius 射手 | Jupiter 木星 |
| Capricorn 摩羯 | Saturn 土星 |
| Aquarius 水瓶 | Saturn 土星 |
| Pisces 双鱼 | Jupiter 木星 |

Outer planets may be described as modifiers when present, but do not make Uranus, Neptune, or Pluto the ruler of Aquarius, Pisces, or Scorpio in a classical judgment.

## Planetary Natures

- Sun: vitality, authority, honor, father/men in many contexts, visibility, command.
- Moon: body, habit, mother/women in many contexts, fluctuation, public, daily life.
- Mercury: mind, speech, writing, commerce, calculation, youth, mediation; takes color from its contacts.
- Venus: union, affection, art, beauty, pleasure, women, agreement, gifts.
- Mars: heat, cutting, conflict, courage, injury, tools, surgery, military, urgency.
- Jupiter: expansion, wealth, law, protection, teachers, faith, generosity, honors.
- Saturn: cold, delay, fear, age, boundaries, poverty, persistence, land, confinement.

Benefics are Venus and Jupiter; malefics are Mars and Saturn. Their results depend on sect, dignity, placement, rulership, and reception. A dignified malefic can produce disciplined achievement; a debilitated benefic can overpromise or waste.

## Sect

First decide whether the chart is diurnal or nocturnal.

- Day chart: Sun above horizon. Jupiter is the benefic of sect; Saturn is more constructive; Mars is more troublesome.
- Night chart: Sun below horizon. Venus is the benefic of sect; Mars is more manageable; Saturn is more troublesome.

Use sect to adjust the heat/cold and usefulness of benefics and malefics. Do not use sect as a single yes/no verdict.

## Phase And Quality Modifiers

Use these as modifiers, not replacements for dignity and house rulership:

- Planetary qualities in the Ptolemaic stream: Sun hot/dry; Moon wet with reflected warmth; Saturn cold/dry; Jupiter warm/moist; Mars hot/dry; Venus warm/moist; Mercury variable, drying near the Sun and moistening by proximity to the Moon's sphere.
- Moon phase can color timing and temperament: new to first quarter increases moisture/growth; first quarter to full increases heat/activity; full to last quarter dries/reveals/declines; last quarter to dark cools, hides, and releases.
- Morning-star planets tend to act more assertively or outwardly; evening-star planets more receptively or inwardly. This matters most for Mercury, Venus, Mars, Jupiter, and Saturn when the rest of the chart already supports the distinction.
- Hemisphere can modify expression: planets in the eastern quadrants tend to be more self-initiating; planets in western quadrants more responsive to other people or circumstances.

Do not moralize these qualities. Translate them into style, timing, and material condition.

Via combusta / 燃烧之路 is mainly a horary and older technical warning. In natal work, do not make it a major judgment by itself. Use it only as a light modifier when the Moon or a key significator is already afflicted by stronger testimonies.

## Essential Dignity

Judge whether a planet has power to act according to its own nature:

- Domicile: strong ownership, stable expression.
- Exaltation: honored, amplified, high-functioning but sometimes dramatic.
- Triplicity, term/bound, face: smaller dignities; useful for nuance and almuten calculations.
- Detriment: exiled, must act through an opposing environment.
- Fall: lowered, awkward, less able to express its best promise.
- Peregrine: without essential dignity; the planet has less rooted authority and depends more heavily on its dispositor, aspects, and house condition.

When exact degree dignity matters, load `dignity-tables.md` for the checked working tables, interval boundaries and degree-score procedure, or use a clearly identified supplied table. Do not invent degree-level dignities from memory.

Use Dorothean triplicity rulers and Egyptian bounds unless the user or chart source specifies another table. Almuten is the highest degree-ownership score under the named scheme; preserve ties and distinguish this from overall planetary strength. See `source-conventions.md` for sources and explicit skill choices.

## Accidental Condition

Judge whether a planet has circumstances to act:

- Angular houses/near angles: loud, visible, event-producing.
- Succedent houses: stable, accumulating.
- Cadent houses: weaker, hidden, delayed, preparatory, or mental/foreign/service-oriented depending on house.
- Speed: fast planets act readily; slow planets delay or internalize.
- Retrograde: reversal, repetition, withdrawal, revision, or return.
- Combustion/under beams: hidden, weakened, consumed by solar authority; cazimi is an exception of empowerment.
- Lunar phase: increasing Moon grows and manifests; decreasing Moon releases and declines.
- Oriental/occidental: modify planetary style, especially Mercury, Venus, Mars, Jupiter, Saturn.
- House joy, nodes, fixed stars, antiscia, besiegement, and enclosure can strengthen details when tight and relevant.
- Hayz: a planet is especially well-situated when it matches sect, hemisphere, and sign gender. Use it as a quality modifier, not a standalone verdict.
- Dispositor strength matters. A weak planet with a strong dispositor can recover; a strong planet with a weak dispositor can have its promise undermined by its environment.

For a qualitative house-strength guide, this skill uses Lilly's *Christian Astrology* p. 48 order: 1st, 10th, 7th, 4th, 11th, 5th, 9th, 3rd, 2nd, 8th, 6th, 12th (source L1 in `source-conventions.md`). This is a named weighting, not a universal arithmetic ranking or a substitute for the topic and angular proximity.

### Near-Cusp Placement And Strength

Keep three facts separate: the supplied/computed house placement, proximity to a cusp or angle, and an optional interpretive reassignment. In quadrant or equal houses, a planet within about 5 degrees before the next cusp can be read as acting in the following house, especially before an angle. This convention does not alter its longitude or silently replace its recorded house.

When it changes the reading, report the original house, distance/direction to the next cusp, and whether the five-degree convention is being applied. A planet recorded in the 12th close to the Ascendant can have substantial angular strength and optional 1st-house action without erasing its original 12th-house placement. In house-lord flight, label the original destination and any supplementary destination separately; do not count them as independent evidence.

If birth-time uncertainty can move the planet across the cusp, compare the candidate placements and weaken house-specific claims. Preserve whether a time is recorded, approximate, or rectified. Do not apply this degree rule to rewrite whole-sign house membership. If a sign is intercepted in a house, consider both the cusp ruler and the intercepted sign ruler for that house.

Traditional house joys can refine accidental condition: Mercury joys in the 1st, Moon in the 3rd, Venus in the 5th, Mars in the 6th, Sun in the 9th, Jupiter in the 11th, Saturn in the 12th. A joy does not make a planet "good" by itself; it lets the planet express its nature more coherently.

## Aspects And Reception

Use Ptolemaic aspects first: conjunction, sextile, square, trine, opposition. Keep whole-sign relationship and measured degree contact distinct; use the out-of-sign and motion rules in `aspect-judgment.md` rather than silently discarding a close degree contact.

- Applying/separating is a motion classification first, requiring reliable speeds or a trusted chart flag; its symbolism is not proof that an event will occur or has occurred.
- Reception can help a difficult aspect because the receiving planet has reason to support the other.
- Mutual reception links two topics strongly and can transfer resources between them.
- Lack of aspect by sign aversion can show disconnection, ignorance, or inability to cooperate.

Do not call every trine good or every square bad. Dignity, reception, house topics, and the planets involved decide the outcome.

For the moiety orb table, exact reception logic, dispositor judgment, mutual reception, besiegement, antiscia, and node modifiers, load `aspect-judgment.md`. Do not substitute modern narrow orb defaults unless the user explicitly asks for a modern technique.

## House Meanings

Use these as the first layer of topical judgment:

1. Self, body, temperament, vitality, life direction.
2. Money, movable assets, livelihood, food, values.
3. Siblings, communication, writing, short travel, basic study, neighbors.
4. Home, land, family root, father/parents in many traditions, private foundation.
5. Children, pleasure, romance, creativity, performance, speculation.
6. Illness, labor, employees, subordinates, service, small animals, burdens.
7. Spouse, partners, open enemies, contracts, litigation, other people.
8. Death, fear, debt, partner's money, inheritance, crisis, hidden vulnerability.
9. Higher learning, religion, law, publishing, foreign places, teachers, long travel.
10. Career, rank, authority, reputation, action in the world, mother/parents in many traditions.
11. Friends, patrons, alliances, groups, hopes, gains from career.
12. Isolation, hidden enemies, confinement, sorrow, hospitals, self-undoing, retreat.

For parents, compare 4th/10th, Sun/Saturn for father themes, and Moon/Venus for mother themes; use the tradition or chart context that best fits the testimony.
