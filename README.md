# Money for Mars

A space economy design exercise. Teams draw three cards — a place in the solar system, a person who needs financial services, and a financial tool from Earth — and design something that would actually work where Earth's version wouldn't.

The exercise is not about predicting space economies. It is about the muscle for questioning what a system takes for granted and rebuilding it when those assumptions no longer hold. Space is the prompt. The reasoning is the point, and it transfers — frontier markets, emerging technology, regulatory disruption, post-disruption strategy.

Created by Scott Smith and Susan Cox-Smith at [Changeist](https://changeist.com).

## Where this came from

Changeist developed the concept around 2017 and refined it over the following years. It was used at Future of Money at the University of the Arts London in 2022, run with John Willshire alongside Susan Cox-Smith and Scott Smith.

The version in this repository is a later and much expanded one — the full card ledger with its zones and latencies, the two-phase structure, the Crisis Cards, the printed deck and the facilitator guide.

For background on where Earth's financial instruments came from and what that suggests for designing new ones, there is an essay at [moneyformars.com/history](https://moneyformars.com/history/). Useful preparation for a facilitator, particularly for opening a skeptical room with the historical anchor. Not a participant pre-read — the game works better when people meet the problem cold.

---

## Start here

You need two printed things and half an hour of reading.

1. **[Quick-start deck](Money_for_Mars_Quickstart_Deck.pdf)** — print single-sided on A4, guillotine on the grid. 16 sheets, four A6 cards each: 56 playing cards plus 8 Crisis Cards. One deck for the whole session, not one per team.
2. **[The canvas](Money_for_Mars_Canvas_A3.pdf)** — A3 landscape, one per team.
3. **[The facilitator guide](Money_for_Mars_Facilitator_Guide.pdf)** — how to run it, what goes wrong, how to debrief.

That is a complete session. Everything else in this repository is for tuning it.

## What is here

| File | What it is |
|---|---|
| `Money_for_Mars_Facilitator_Guide.pdf` | The guide, with covers. Formats, phases, worked examples, facilitator notes, glossary. |
| `Money_for_Mars_Facilitator_Guide.docx` | Editable source of the same, without covers. |
| `Money_for_Mars_Card_Ledger.xlsx` | Every card that exists, with the tags used to build a deck. The README sheet explains the columns. |
| `Money_for_Mars_Quickstart_Deck.pdf` | The Core deck plus Crisis Cards, laid out to print and cut. |
| `Money_for_Mars_Canvas_A3.pdf` | The team worksheet. |
| `csv/cards.csv` | The card ledger as plain text, so changes are readable in the commit history. |
| `csv/crisis_cards.csv` | The eight Crisis Cards, same. |
| `csv/starting_decks.csv` | The five audience menus, one row per card. |
| `LICENSE` | CC BY-NC 4.0, full text. |

The spreadsheet is the working file; the CSVs are generated from it. If you are reading a diff, read the CSVs.

## Formats

Teams are two to five people. Every schedule allows four minutes per team for sharing, including the handover — that is the number to recalculate from if your team count changes.

| Format | Length | Teams | Notes |
|---|---|---|---|
| Quick Play | 90 min | 4–6 | Design and share. No ecosystem phase. |
| Quick Play + Crisis | 2 hours | 4–6 | Adds a Crisis Card every team has to survive. |
| Full Game | 3.5 hours | 6–9 | Both phases. Includes a break. |
| Two Sessions | 90 × 2 | 4–6 | Design and share, then ecosystem formation. |

## How the cards work

Three types are dealt: **Locations**, **Personas**, **Tools**. Each team draws one of each. A drawn card is out of play, so no two teams hold the same card — print at least as many Locations as you have teams, plus a couple spare for redraws.

**Crisis Cards** are a fourth type and are not dealt. The facilitator holds them and plays one to the whole room after teams have shared.

One piece of card information is a play variable: a Location's **zone** — Near Earth, Solar System, Deep Space — and the **latency** that goes with it. Latency sets everything the design has to answer: how long a message takes, how long help takes, whether a contract can be enforced, whose rules apply. Both are printed on the card face.

Everything else in the ledger is for whoever builds the deck. Category is a filing cut so a deck doesn't go out with five Borrowing cards in a row. The tag columns — status, tradition, time horizon, vocabulary, sensitivity — calibrate a deck to a room. None of it belongs on a card a player is holding.

**Core and Variant.** The Core set is the general deck and needs no assembly: 15 Locations, 20 Personas, 21 Tools. That is what the quick-start deck prints. Variants are tested additions for particular contexts. The ledger's five audience tabs — Corporate & Professional, Youth & Student, Expert & Fintech, Cross-tradition, Foresight — are an extended menu of cards worth swapping in for a particular room, not decks to print whole.

One thing worth knowing before you run it: the Core deck assumes Western finance vocabulary. The cards that break that assumption are all Variants — waqf, sukuk, rotating savings clubs, mutual aid pools, profit-sharing contracts, religious endowments, cooperative stewards. If your room has deeper or different financial traditions than the Core deck admits, reach for those deliberately.

## Making your own cards

The ledger is a working list, not a closed set. Sessions with a specific industry, region or policy context usually want a card the deck does not have.

A card earns its place by **collision** — the friction it creates against the other two draws. A card can be interesting on its own and still produce nothing in play.

- A **Location** works by removing something a financial tool assumes: real-time communication, a reachable counterparty, an enforceable contract, a shared clock, somebody with jurisdiction.
- A **Persona** works by having a need that the Earth-standard answer cannot meet once the location is applied.
- A **Tool** works by carrying an assumption that visibly breaks somewhere in the deck. Name the assumption in the extended description — that is the line a team will use.

Test a new card by drawing it against three random cards from the other two types. If two of the three produce a problem you can state in one sentence, keep it. If none do, the card will read well and produce nothing.

Short descriptions are one sentence and no more than 80 characters — that is what fits a card face beside the name. Anything longer goes in the extended description. New cards start as Variant; promote one to Core after a session where it produced real work.

## Tell us what happened

If you run it, we would like to know what came out — which combinations produced good work, which cards died on the table, what you added. Open an issue, or write to us via [changeist.com](https://changeist.com).

## Running it with us

Changeist runs Money for Mars as a facilitated session, half-day or ninety minutes, and builds custom decks for a particular sector or region. We also train facilitators to run it in-house. [moneyformars.com](https://moneyformars.com)

## Films where the money shows

Not films about money. Films with a moment of money in them — a contract, a bonus, a meter, a machine still taking coins. Ours, in order of appearance.

- **[Silent Running](https://en.wikipedia.org/wiki/Silent_Running)** (1972) — the order from the company to jettison the last forests and put the freighters back into commercial service.
- **[Alien](https://en.wikipedia.org/wiki/Alien_(film))** (1979) — the argument over shares and bonus before anyone will go back down.
- **[Outland](https://en.wikipedia.org/wiki/Outland_(film))** (1981) — productivity bonuses on Io, and what the company will overlook to keep them coming.
- **[Total Recall](https://en.wikipedia.org/wiki/Total_Recall_(1990_film))** (1990) — air sold by the meter.
- **[Moon](https://en.wikipedia.org/wiki/Moon_(2009_film))** (2009) — one worker, a three-year contract, and the bonus waiting at the end of it.
- **[Prospect](https://en.wikipedia.org/wiki/Prospect_(film))** (2018) — a claim worked against a deadline, with every split negotiated at gunpoint.
- **[Aniara](https://en.wikipedia.org/wiki/Aniara_(film))** (2018) — the onboard game arcade, still taking coins long after the destination is gone.

## License

© 2022–2026 Changeist. Licensed under [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) (CC BY-NC 4.0). Use it, adapt it, share it — not commercially.

Credit it like this:

> Money for Mars, created by Changeist, moneyformars.com, licensed CC BY-NC 4.0.

If you have adapted the deck or written your own cards, say so. It tells the next facilitator what they are looking at.
