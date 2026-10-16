# Convergence — a unified Seer design concept

One design language for Seer's six interfaces, built on the **Electric Foundation (EF)** brand kit.

**The idea.** Seer is a protocol, not a pile of products. Today its interfaces speak six visual dialects — the old raven logo on seer.pm, no Seer branding at all on Deep and Futarchy, Kleros/Foresight branding dominating Risk Pricing. *Convergence* gives them one family: the EF kit's converging light lines become the shared motif, the violet accent the shared voice, and **one ecosystem bar** the shared skeleton across all six demos.

**The six demos**

| Demo | Interface | What it shows |
|------|-----------|---------------|
| [Homepage](https://hdr2804.github.io/seer-convergence/) | Protocol front door | Hero, ecosystem map linking all six, market primitives, Kleros trust strip |
| [App](https://hdr2804.github.io/seer-convergence/app.html) | Seer App — general market explorer | Search, type filters, market cards, forecaster leaderboard |
| [Deep](https://hdr2804.github.io/seer-convergence/deep.html) | AI-agent prediction markets | UP/DOWN originality mechanics, originality-over-time chart, repo markets table |
| [Futarchy](https://hdr2804.github.io/seer-convergence/futarchy.html) | Conditional governance markets | Dual-panel pass-vs-reject forecast, milestones, organizations |
| [Opportunity](https://hdr2804.github.io/seer-convergence/opportunity.html) | Opportunity Markets | Five-step flow, live contest boards with odds |
| [Risk Pricing](https://hdr2804.github.io/seer-convergence/risk.html) | Risk Pricing | PD estimates across 33 DeFi assets, risk bars, aggregate default odds |

**Design tokens** (from the EF kit, interpretations noted in [RATIONALE.md](RATIONALE.md))

- Type: Manrope (Medium / Semibold / Bold / Extrabold)
- Ink `#17171C` · secondary `#5C5C66` · muted `#8E8E99`
- Primary violet `#7C3AED` · deep `#6C2BD9` · soft `#EFE9FC`
- Dark surfaces `#0D0B16` / `#12101F`; converging light lines motif in dark heroes

**Build.** Pure static HTML + one shared `styles.css`. No build step, no dependencies, no tracking. All data is plausible mock data modelled on the real products; nothing here transacts.

**Structure**
```
index.html  app.html  deep.html  futarchy.html  opportunity.html  risk.html
styles.css          # shared design system
partials.html       # shared snippets (bar, hero motif, footer) — reference only
README.md  RATIONALE.md
preview.png         # six-interface collage
```
