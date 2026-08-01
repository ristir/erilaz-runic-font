# Sources

Erilaz is drawn from inscriptions and manuscripts rather than from existing
digital revivals. This file records which monument a given letterform was
taken from, where the working notes preserve it.

The list is not exhaustive: it covers the variants whose origin was written
down during the drawing, between August 2020 and January 2022.

## How the character variant features are organised

| Feature | Content |
|---|---|
| `cv01` | Rounded form, for those runes that have one |
| `cv02`–`cv08` | Letterform variants attested in particular monuments |
| `cv09` | Staveless runes, set between superscript and subscript rules |
| `cv10` | Mirrored form, only for runes where one is attested |
| `cv11` | Cipher runes, Rök stone |
| `cv12`–`cv13` | Tent runes (*tjaldrúnir*), Rök stone |
| `cv14` | Cipher runes, "fish" |
| `cv15` | Cipher runes, "beards" |
| `cv19` | Staveless runes, without the rules |

`cv01` is reserved for rounded forms alone; anything else angular goes to
`cv02` and above.

Staveless runes are not a cipher but a reduced form of the Younger Futhark,
alongside the long-branch and short-twig types, in which the main stave of
each letter is left out. They are given twice: `cv09` between the ruled
lines that usually accompany them, and `cv19` without.

## Design brief

The starting point was book typography rather than display use: thin
strokes, narrow letterforms, a classical look without fantasy mannerism.
Junicode and Gullhornet/Gullskoen were studied as the closest existing
attempts at the same brief, and the departures from them were deliberate —
uniform stroke weight throughout, where theirs varies in half-ovals and
diagonals; rounded rather than spiked apexes; and smooth transitions where
a straight stroke meets a diagonal. Tiwaz, Raido and Perþu were the runes
where this mattered most.

## Gullhornet, Gullskoen, Junicode

The repertoire of these fonts — the inventory of which variant forms exist
— was used as a checklist while drawing. All outlines in Erilaz were drawn
from scratch. A contour comparison of the released font against all three,
matching node counts, node order and coordinates after normalisation, found
no transferred outlines: Erilaz is roughly three times denser in nodes and
uses curves throughout where the others are close to polygons.

| Code point | Variant | Source |
|---|---|---|
| U+16A9 ᚩ | `cv03` | Gullhornet |

## Manuscripts and inscriptions

### Rök stone

The largest single source, supplying three of the cipher features: `cv11`
for the cipher runes proper, sixteen Younger Futhark runes, and `cv12`–`cv13`
for the tent runes. Also from the stone: the ᛆ+ᚦ bind rune, a mirrored U
with a stave, and a double-sloped U.

### Codex Sangallensis 878

Anglo-Saxon runes with raised, hooked terminals.

| Code point | Variant | Form |
|---|---|---|
| U+16C9 ᛉ | ALGIZ EOLHX | shaped like Cyrillic Ж |
| U+16DF ᛟ | OTHALAN | with legs |

### Falstone hogback (Stephens, p. 138)

| Code point | Variant | Form |
|---|---|---|
| U+16A6 ᚦ | `cv02` | rounded |
| U+16BB ᚻ | HAEGL | mirrored |
| U+16E0 ᛠ | `cv02` | — |

### Golden Horns of Gallehus

Mirrored forms of Hagalaz and Naudiz.

### Runic stick from Bryggen, Bergen

The "beard" forms, `cv15`.

### Franks Casket

The f+a bind rune.

### Thorsberg

The ᛖ͡ᛗ bind rune.

### Amulet ring, England

The *ærkriuflt / kriuriþon / glæstæpon* charm formula, known from the
Bramham Moor and Kingmoor rings (Stephens, p. 157).

### Seax of Beagnoth

Anglo-Saxon Dagaz with a triangle in place of the crossing.

### Hälsingland

Staveless runes, `cv09` and `cv19`.

## Thor's hammer

The hammer symbols on the `^` key are taken from runestones on which the
hammer was carved, generally understood as a pagan answer to the Christian
cross.

| Stone | Place |
|---|---|
| Sö 111 | Stenkvista, Sweden, early 11th c. |
| Sö 86 | Åby, Sweden |
| Vg 113 | Lärkegapet, Sweden, 980–1015 |
| DR 26 | Læborg, Denmark, 900–950 |
| DR 48 | Hanning, Denmark, 12th c. |
| DR 120 | Spentrup, Denmark, 970–1020 |
| DR 331 | Gårdstånga, Sweden |
| Öl 1 | Karlevi, Sweden, 980–1015 |

## Stephens

George Stephens, *The Old-Northern Runic Monuments of Scandinavia and
England* (London and Copenhagen, 1866–1901). Page references.

| Code point | Variant | Page |
|---|---|---|
| U+16A9 ᚩ | `cv02` | 157–158 |
| U+16AA ᚪ | `cv02` | 248 |
| U+16C8 ᛈ | `cv02` | 157–158 |
| Sowilu | round, mirroring the digit 3 | 3 |
| Sowilu | reversed | 7 |
| Uruz | gabled | 7 |
| Wunju | facing both ways | 7 |
| n+t, l+t | bind runes | 157 |

## Additions outside the Runic block

| Code point | Purpose |
|---|---|
| U+0361 | combining double inverted breve, for /k͡p/ |
| U+035C | combining double breve below, for /k͜p/ |
| U+2026 | ellipsis, set as three vertical dots |

Digits, æ, brackets and the Thor's hammer symbols were added in June 2021.
The digits reproduce no historical numeral system; their shapes are taken
from the pips of dice.
