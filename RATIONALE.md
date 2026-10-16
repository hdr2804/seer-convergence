# Convergence — design rationale

## Concept

Seer's six interfaces are one ecosystem, but today they look like six products from six companies: the legacy raven logo on the homepage and explorer, zero Seer branding on Deep and Futarchy, and Kleros/Foresight branding dominating Risk Pricing. **Convergence** is the design thesis that fixes this: take the Electric Foundation kit's signature visual — light lines converging to a single vanishing point — and make it the metaphor *and* the motif. Six interfaces, one family, one point of convergence.

The single most visible decision: **one identical ecosystem bar on every page** — hexagonal-S mark, lowercase "seer", links to all six demos, one Connect button. A judge opening any demo instantly sees the family resemblance. Dark heroes carry the converging-lines motif; functional surfaces stay light, clean, and consistent.

## Page-by-page rationale

1. **Homepage** — reframes Seer as *the protocol beneath the applications*. The hero states the kit's own tagline ("SEE WHAT THE MARKETS BELIEVE"); the ecosystem-map section is the piece the current seer.pm lacks: a visual answer to "how do these six apps fit together?" Market primitives (Categorical → Multi-Scalar) are presented as one engine, and the Kleros/Reality.eth trust strip answers "why believe these markets?"
2. **Seer App** — the general explorer ("Seer's Etherscan"). The current app.seer.pm's weaknesses are dense cards and unreadable donut charts; we replace them with readable question-first cards, a single outcome bar per market, and explicit market-type taxonomy chips — the thing that makes an *explorer* explorable.
3. **Deep** — markets for AI agents get an agent-native console aesthetic, but the key addition is legibility: UP = share of original work / DOWN = share carried by dependencies, explained before any number appears, with the "share of original work over time" chart as the hero visual the current deep.seer.pm buries.
4. **Futarchy** — the current futarchy.seer.pm has no visualization of its core mechanic. We add it: a dual-panel conditional forecast (pass vs. reject revenue curves) for a sample proposal, because "markets know better than experts" is meaningless without showing both futures side by side.
5. **Opportunity Markets** — the five-step flow (call → odds → triage → sponsor decides → P&L) is the product's story; the live contest boards with odds bars demonstrate the triage mechanic, using Seer's own real contests as sample data.
6. **Risk Pricing** — keeps its neutral product name. The redesign centers the comparison: risk bars on one LOW→CRITICAL gradient so 33 assets are comparable at a glance, with the aggregate "chance that no listed asset defaults" as the anchor stat.

## Departures from the EF kit (explicit, as the bounty requests)

The EF kit is a visual board, not a written spec: it shows dark/light UI mockups, the palette, Manrope, and the S mark, but contains **no written rules for tone of voice, type scale, spacing, or data-visualization**. The following are our documented interpretations, not kit prescriptions:

- **Primary violet `#7C3AED`.** The kit's button-primary hex could not be read with certainty from the Figma board (a bounty commenter cited `#7C3AED` from the kit thumbnail). We adopt `#7C3AED` as the primary accent, with `#6C2BD9` (kit-verified secondary-button text) as the deep variant and `#EFE9FC` as the soft surface.
- **Type scale & spacing.** Kit shows Manrope in Medium/Semibold/Bold/Extrabold with no scale; we set display 56 / H2 36 / H3 20 / body 16 on an 8px spacing grid, tight −2–3% tracking on display type.
- **Dark surface range.** Kit shows dark navy/violet UI without hex values; we use `#0D0B16`–`#1A1730` with the converging-lines motif carrying the brand's "electric" quality.
- **Data-viz language.** The kit has no chart guidance; we define one per interface family: outcome bars (App, Opportunity), UP/DOWN price tables (Deep), dual conditional panels (Futarchy), LOW→CRITICAL risk gradient (Risk Pricing) — distinct grammars, one palette and type system.
- **Logo.** The hexagonal "S" is our clean vector approximation of the kit's geometric S mark (kit original by the identity's designer); the lowercase "seer" wordmark follows the kit's lockup.
- **Voice.** Kit taglines ("SEE WHAT THE MARKETS BELIEVE", "EVERY OPINION HAS A PRICE", "Prediction Markets For Distilled Human Judgement") are used verbatim where they fit; interface copy is written in the kit's plain, confident register.
