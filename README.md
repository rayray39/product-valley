# Product Valley

A 2D pixel-art RPG that teaches product thinking.

**▶ Play: https://rayray39.github.io/product-valley/**

Walk a Stardew-Valley-style world and talk to seven neighbours. Each one teaches one
framework for not building the wrong thing, then drills you on it. Collect their field
cards, then sit the mixed final exam at the Town Hall — the one where nobody tells you
which framework a question belongs to.

| Who | Where | Teaches |
| --- | --- | --- |
| Mira the Joiner | Workshop Lane, west | The Swap Test; "so that what?" |
| Old Wren | the well, south road | Five Whys; choosing the level to fix |
| Scribe Pell | Scribe Row, north-west | The Four Cs problem statement |
| Tilda the Surveyor | Stargazer Hill, north-east | Outputs vs outcomes; SMART; leading/lagging; value–cost ratio |
| Bram | Risk Ridge, over the bridge | Riskiest assumption; PoC → PoV → Scale → Maturity |
| Nura | Starlight Inn, south-east | The 11-Star exercise; services people can't opt out of |
| Mayor Hale | Town Hall | The three shifts, plus the mixed final |

33 questions, 7 field cards, about 7,500 words of dialogue.

## Controls

- **WASD** / **arrow keys** — walk
- **E** or **space** — talk, read signposts, advance dialogue
- **1–4** or click — answer
- **J** — field journal · **M** — mute · **Esc** — close

Touch controls appear automatically on phones and tablets.

## Technical

One self-contained `index.html`. No build step, no framework, no image assets — every
tree, building, fountain and character is drawn procedurally into a canvas at 3× pixel
scale. The only external requests are two Google pixel fonts, which fall back to
monospace if blocked.

Progress is per-session and is not saved between reloads.

## Sources

Built on the [IDG Product Thinking](https://www.idg.gov.sg/product-thinking/) curriculum,
with its Singapore public-service framing translated to general product and AI work.
Supporting material from [Marty Cagan / SVPG](https://www.svpg.com/focus-on-value/),
[Teresa Torres](https://www.producttalk.org/), and Brian Chesky's eleven-star exercise.

One honesty note is carried into the game itself: IDG presents the Four Cs inside a
graphic and never spells the four terms out in text, so Scribe Pell tells you up front
that what he teaches is a reconstruction, not a quotation.
