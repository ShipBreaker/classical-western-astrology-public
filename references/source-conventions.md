# Sources And Working Conventions

This skill is a medieval-first working synthesis, not a critical edition or one author's complete system. Inherited techniques are not evidence that astrology predicts real-world outcomes. Cite a checked passage for historical claims; label implementation choices as this skill's conventions. Do not invent page numbers or call a software implementation an ancient source.

## Source Register

| ID | Source and location | Kind and checked use |
| --- | --- | --- |
| D1 | Dorotheus, *Carmen Astrologicum*, Book I.1-2, David Pingree translation (1976), pp. 161-162; [authorized study reproduction, PDF p. 2](https://www.skyscript.co.uk/dorotheus1.pdf) | Translated primary text: triplicity sequence, domiciles and exaltations. The text's extra Mercury share in Virgo is not added to the default element-based scoring table. |
| P1 | Ptolemy, *Tetrabiblos*, I.20 in the Robbins numbering, [Egyptian terms passage](https://astrolibrary.org/library/tetrabiblos/tetrabiblos-22/) | Translated primary text, not the site's modern abstract: Egyptian segment lengths. These are distinct from Ptolemy's own alternative terms. |
| L1 | William Lilly, *Christian Astrology*, Book I (1647), [retyped edition](https://krasiancientastrology.com/wp-content/uploads/2016/11/CA-I-copy.pdf) | Primary text in a modern transcription: p. 48 house order; pp. 101-104 dignities/faces; p. 107 orbs; pp. 107-111 motion; p. 112 reception; pp. 113-114 solar proximity; p. 115 dignity weights. Use printed page numbers, not PDF indices. Renaissance comparison does not make the whole skill Lilly-only. |
| F1 | Oner Doser, *Astrological Prediction*, [publisher extract](https://bendykes.com/wp-content/uploads/2016/08/ap-extract.pdf), p. 6 and pp. 38-40 | Modern exposition: distinction of primary directions and Solar Arc; the author's presentation of Bonatti-style Firdaria and a nodes-last variant. Not a direct quotation from Bonatti or a verified Zoller edition. |
| Z1 | [Morphemeris ZR reference](https://docs.morphemeris.com/docs/reference/zodiacal-releasing), units and walk | Software implementation cross-check: 360-day year, division by twelve, Capricorn 27/Aquarius 30, parent truncation and LB. Not a primary Valens edition. |
| E1 | [Swiss Ephemeris programmer's reference](https://www.astro.com/swisseph/swephprg.htm), houses and planetary positions | Calculation reference: coordinates, time scales and supported house systems. A calculation engine does not validate interpretation. |
| V1 | Valens, *Anthologies*, Riley translation, [annotated re-typesetting](https://raw.githubusercontent.com/janegca/latex-valens/main/Valens-Anthologies-Annotated.pdf), Book II, "Notable and Distinguished Nativities" (22K/23P), printed pp. 146-147 | Translated primary text plus distinguishable editorial notes: Spirit and Basis. The Basis passage and editor's short-distance note support the named working formula, but do not erase translation/convention differences. |

Verified passages support only the rules identified above, not every interpretive statement in this repository. Links can move; if unavailable, retain the bibliographic locator and disclose the access gap. Do not redistribute scans or translations with the skill; their rights are separate from this repository's license.

## Default Policy Map

| Area | Operational choice | Variant handling |
| --- | --- | --- |
| Frame | Tropical, Alcabitius, traditional seven rulers when no frame is supplied | Preserve a supplied frame; compare rather than silently convert |
| Dignities | D1 element-based triplicities; P1 Egyptian bounds; L1 Chaldean faces | `dignity-tables.md` is the single lookup source; record alternative tables |
| Degree Almuten | Positive 5/4/3/2/1 claims; only the sect-leading triplicity ruler gets 3 by default | This combination is a declared skill policy, not Lilly's complete table or an Almuten Figuris calculation; retain ties |
| Aspects | Smaller orb column recorded by L1 p. 107, consistently across all seven planets | Preserve named chart settings. Former Mars 8 degrees was unsupported here; default is now 7 |
| Reception | Directional dignity relation, with the explicit contact/strength rules in `aspect-judgment.md` | Small-dignity threshold is a skill convention; Lilly's p. 112 terminology includes what is often called mutual reception and permits no-aspect cases |
| Solar proximity | L1 pp. 113-114 longitude-based policy, separately from aspect orbs | Name different cazimi/combustion thresholds, sign or latitude requirements rather than blending them |
| House strength | L1 p. 48 order as a qualitative guide | Not a universal numeric ranking; actual topic and near-angle strength still matter |
| Firdaria and ZR | Defined independently in `predictive-timing.md` | Record sequence, year length, epoch, timezone and level; do not mix conventions |
| Lots | Formula and boundary policy in `medieval-techniques.md`; V1 for Spirit/Basis context | Basis short-arc normalization is a declared working convention, not an assertion that every Valens translation agrees |

## Evidence Limits

- Chinese-transmission notes name historical works but do not establish an edition/page for every claim. Do not present unverified paraphrases as quotations from those works. Use the checked computational tables above when a numeric rule is needed.
- Profession, relationship, fixed-star and rank interpretations are traditional or pedagogical associations, not measured probabilities or proof of a person's attributes.
- An author-specific request overrides the default only for that named method after its settings are identified. For example, requesting Lilly requires checking his triplicity/term choices; do not merely rename the default Dorothean/Egyptian combination.
- Keep historical description, chosen calculation policy, symbolic interpretation and externally verified real-world facts separate in the answer.
