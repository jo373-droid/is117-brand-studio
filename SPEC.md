# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: Lukewarm storefront and live style guide built on the feature branch; learner review pending.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: BRAND-001 implementation built; browser review, one check explanation, and LEARNING.md review pending.
- Next small decision: Inspect the local storefront, style guide, and previews; report a first impression.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                              | Secondary audience                                       |
| ------------------------------------- | --------------------------------------------- | -------------------------------------------------------- |
| Person in a concrete situation        | Uses a simple shirt to express creative style | Wants an everyday basic and clear size/price information |
| Goal or meaning they seek             | A more defined look while feeling loose       | Find a straightforward everyday option                   |
| Concern before choosing               | Not chosen yet                                | Clear size and price details                             |
| What the page should help them decide | Not chosen yet                                | Whether the size and fictional price suit them           |
| Evidence or assumption                | Assumption; not validated                     | Assumption; not validated                                |

## Early brand brief

| Decision                                 | Agreement                                                                 |
| ---------------------------------------- | ------------------------------------------------------------------------- |
| Brand name                               | Lukewarm                                                                  |
| One-sentence promise                     | Simple shirt. Your point of view.                                         |
| Primary archetype: the brand's character | Creator                                                                   |
| Three voice traits                       | Laid-back, contrarian, and clear (learner accepted the proposed voice)    |
| One example line in this voice           | Not chosen yet                                                            |
| Learner's predicted audience effect      | The tilted label feels unexpected; broader audience effect not stated yet |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                              |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | “Simple shirt. Your point of view.” / “An ordinary white tee, ready for the way you wear it.” / “See the T-shirt.”                                                                 |
| Modernist preview, reference, and annotations     | `public/explorations.html`; Herbert Bayer, _Architektur Lichtbilder Vortrag Professor Hans Poelzig_ (1926), MoMA; grid, asymmetry, sans-serif clarity; risk: may feel too orderly. |
| Postmodernist preview, reference, and annotations | `public/explorations.html`; Ettore Sottsass, _Carlton_ (1981), MoMA; playful geometry and mixed cues; risk: decoration may distract.                                               |
| Chosen direction and reason                       | Postmodernist; learner chose “Playful and contrarian” and the tilted sticker because it feels unexpected.                                                                          |
| Original SVG logo                                 | public/assets/wordmark.svg; Lukewarm wordmark with a tilted label mark. AI-created proposal; learner review pending.                                                               |
| Monochrome and small-size variants                | public/assets/wordmark-mono.svg; single-ink vector shown beside the color wordmark.                                                                                                |
| Logo review at actual use size                    | Pending learner browser review.                                                                                                                                                    |
| Shared palette, typography, spacing, and assets   | Warm paper, deep ink, lilac, sticker yellow, tomato action; shared system typography, spacing tokens, CSS, and wordmark assets.                                                    |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle                                                         | Actual copy or interaction                                                                      | Visitor benefit / factual support                                                                        |
| ----------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Unity / self-identification (AI proposal; learner review pending) | “If you like everyday pieces with a little edge, you’re in the right place.”                    | Lets visitors decide whether the brand’s point of view fits their taste; no claim about other customers. |
| Reciprocity (AI proposal; learner review pending)                 | “Try the white tee with one bold layer or accessory you already own. Keep what feels like you.” | Offers a free styling idea without gating it or making a product claim.                                  |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                                               | Issue / PR                                                             | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | public/index.html, public/styleguide.html, public/styles.css, public/explorations.html, public/assets/wordmark.svg, public/assets/wordmark-mono.svg | https://github.com/jo373-droid/is117-brand-studio/issues/1; https://github.com/jo373-droid/is117-brand-studio/pull/2 | Formatting and lint passed; all 7 server tests passed. 10 Playwright tests could not launch because Chromium is not installed. Manual browser check: submitting with no size showed an error and kept the bag at 0; keyboard-selected M added one item; emptying returned it to 0. The storefront, style guide, and previews had no horizontal overflow at 390px. Learner’s own observations and check explanation pending. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
