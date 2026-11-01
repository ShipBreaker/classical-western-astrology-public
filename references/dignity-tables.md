# Dignity Lookup And Degree Almuten

Use for exact dignity, reception or Almuten work. Sources and deviations are registered as D1, P1 and L1 in `source-conventions.md`. Supplied tables take precedence when explicitly identified; do not silently combine a different terms or triplicity table with this one.

## Coordinates And Boundaries

Normalize longitude into [0, 360). Aries starts at 0, Taurus at 30, through Pisces at 330. The sign index is `floor(longitude / 30)` and the within-sign degree is `longitude % 30`. Ranges are start-inclusive and end-exclusive. At exactly 30 degrees use the next sign at zero. Never round before a lookup. If the input is rounded or uncertain across a boundary, report both possible rulers instead of inventing seconds.

## Domicile And Exaltation

Exaltation applies throughout the sign, not only at its traditional degree. Detriment and fall are the signs opposite domicile and exaltation respectively. None means no traditional seven-planet exaltation lord.

| Sign | Domicile | Exaltation |
| --- | --- | --- |
| Aries | Mars | Sun |
| Taurus | Venus | Moon |
| Gemini | Mercury | None |
| Cancer | Moon | Jupiter |
| Leo | Sun | None |
| Virgo | Mercury | Mercury |
| Libra | Venus | Saturn |
| Scorpio | Mars | None |
| Sagittarius | Jupiter | None |
| Capricorn | Saturn | Mars |
| Aquarius | Saturn | None |
| Pisces | Jupiter | Venus |

## Dorothean Triplicities

The first two rulers exchange priority with sect; the participating ruler remains third. This table is the element-based working scheme, not an instruction to divide life into three equal periods.

| Element | Signs | Day | Night | Participating |
| --- | --- | --- | --- | --- |
| Fire | Aries, Leo, Sagittarius | Sun | Jupiter | Saturn |
| Earth | Taurus, Virgo, Capricorn | Venus | Moon | Mars |
| Air | Gemini, Libra, Aquarius | Saturn | Mercury | Jupiter |
| Water | Cancer, Scorpio, Pisces | Venus | Mars | Moon |

For the default degree score, count the Day ruler in a day chart or Night ruler in a night chart, once. Keep the other two as qualitative support rather than silently awarding all three 3 points. If sect is unknown, show both score variants or defer selection. All-three scoring is a separate convention and must be named when supplied.

## Egyptian Bounds

Each cell gives the ruler and its exclusive upper boundary; its lower boundary is the previous cell's upper boundary, or zero for the first cell. These endpoints are cumulative sums of the lengths in P1, not Ptolemy's alternative table.

| Sign | Bound 1 | Bound 2 | Bound 3 | Bound 4 | Bound 5 |
| --- | --- | --- | --- | --- | --- |
| Aries | Jupiter 6 | Venus 12 | Mercury 20 | Mars 25 | Saturn 30 |
| Taurus | Venus 8 | Mercury 14 | Jupiter 22 | Saturn 27 | Mars 30 |
| Gemini | Mercury 6 | Jupiter 12 | Venus 17 | Mars 24 | Saturn 30 |
| Cancer | Mars 7 | Venus 13 | Mercury 19 | Jupiter 26 | Saturn 30 |
| Leo | Jupiter 6 | Venus 11 | Saturn 18 | Mercury 24 | Mars 30 |
| Virgo | Mercury 7 | Venus 17 | Jupiter 21 | Mars 28 | Saturn 30 |
| Libra | Saturn 6 | Mercury 14 | Jupiter 21 | Venus 28 | Mars 30 |
| Scorpio | Mars 7 | Venus 11 | Mercury 19 | Jupiter 24 | Saturn 30 |
| Sagittarius | Jupiter 12 | Venus 17 | Mercury 21 | Saturn 26 | Mars 30 |
| Capricorn | Mercury 7 | Jupiter 14 | Venus 22 | Saturn 26 | Mars 30 |
| Aquarius | Mercury 7 | Venus 13 | Jupiter 20 | Mars 25 | Saturn 30 |
| Pisces | Venus 12 | Jupiter 16 | Mercury 19 | Mars 28 | Saturn 30 |

## Faces

Chaldean sequence, beginning with Mars in the first face of Aries (L1 p. 104). Faces are not triplicity rulers or modern sign decans.

| Sign | 0 to 10 | 10 to 20 | 20 to 30 |
| --- | --- | --- | --- |
| Aries | Mars | Sun | Venus |
| Taurus | Mercury | Moon | Saturn |
| Gemini | Jupiter | Mars | Sun |
| Cancer | Venus | Mercury | Moon |
| Leo | Saturn | Jupiter | Mars |
| Virgo | Sun | Venus | Mercury |
| Libra | Moon | Saturn | Jupiter |
| Scorpio | Mars | Sun | Venus |
| Sagittarius | Mercury | Moon | Saturn |
| Capricorn | Jupiter | Mars | Sun |
| Aquarius | Venus | Mercury | Moon |
| Pisces | Saturn | Jupiter | Mars |

## Degree Almuten Procedure

1. Require a reliable longitude and the chosen tables/sect. Start each traditional planet at zero.
2. Add domicile 5, exaltation 4 where present, active triplicity 3, bound 2, and face 1 to each corresponding lord. A planet can receive more than one of these distinct claims.
3. Report the score breakdown and every tied maximum. A tie is not a calculation failure. Use topic relevance and planetary condition for qualitative selection, without secretly changing the degree score.
4. Do not subtract detriment/fall or add house strength, reception, planetary hours, or accidental points to this degree-ownership score. Those belong to separate condition assessments or specifically defined whole-chart methods.
5. Do not equate the winning score with the best-conditioned planet, chart ruler, wealth, or a guaranteed outcome. Whole-chart Almuten Figuris requires a separately specified method and inputs.

For a synthetic example at Aries 19 degrees by day, Sun has exaltation 4 plus triplicity 3 plus face 1, Mars domicile 5, and Mercury bound 2. Sun leads at 8. At Taurus 12 degrees by night, Venus 5 and Moon 4+3+1 compete; Moon leads at 8. These examples test lookup and aggregation, not interpretation.
