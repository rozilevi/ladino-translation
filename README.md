# ladino-translation
A Claude skill file for translating text into authentic Ladino (Judeo-Spanish), Ottoman Sephardic register, using Aki Yerushalayim orthography.

---

## What This Is

Ladino is the language of Sephardic Jews expelled from Spain in 1492 and resettled across the Ottoman Empire. This skill targets the **Ottoman Turkish register** — specifically the variety spoken in İzmir, İstanbul, and Selanik — not Modern Spanish, not North African Ladino, not a simplified approximation.

The prestige reference dialect is **İzmir Sephardic**.

The writing standard is **Aki Yerushalayim** — the orthography system developed by the Ladino journal of the same name, published in Jerusalem, designed to render Judeo-Spanish in Latin script in a consistent, readable way.

---

## Aki Yerushalayim Orthography — Quick Reference

| Sound | Spelling | Example |
|---|---|---|
| "j" as in jumbo | DJ | djudia |
| "ch" as in chair | CH | chiko |
| ñ | NY | anyo |
| "sh" as in short | SH | shavon |
| c / qu → always | K | kaza, ke, komo |
| z as in French zéro | Z | koza |
| "zh" as in French jour | J | ojos |
| double r | RR | serrar |
| silent h (dropped) | — | erensya |
| Hebrew/marked h | 'H | 'Herzl |

Key rules:
- **i** = and (never *y*)
- **ke** = that/which (never *que*)
- City names use Ladino/Ottoman forms: *Estambol, Londra, Selanik*

---

## Usage

Place `SKILL.md` in your Claude skills directory:

```
/mnt/skills/user/ladino-translation/SKILL.md
```

Claude will load it automatically when asked to translate into Ladino or Judeo-Spanish.

---

## What the Skill Covers

- Orthography rules (full Aki Yerushalayim table)
- Grammar — archaic Castilian verb forms preserved in Ladino (*só, bivir, dezir, meldar*)
- Lexicon priority order: Archaic Castilian → Ottoman Turkish → Hebrew/Aramaic → Greek → Modern Spanish calques
- Register guidance: domestic prose, formal editorial, song/poetry, contemporary content
- Euphemistic language conventions (e.g. death vocabulary)
- Core vocabulary reference table
- What to avoid (Modern Spanish spellings, *y* for "and", *que*, *c/qu*)
- Output format — translation + notes on lexical choices

---

*Built for Claude (Anthropic). Dialect reference: İzmir Sephardic.*
