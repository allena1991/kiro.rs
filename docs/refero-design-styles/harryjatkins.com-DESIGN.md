# Harry Atkins — initials and indexes

## Overview

A white, archive-like visual identity where monumental grotesk lettering sits above tiny operational labels and a disciplined catalogue of visual work. Charcoal and pale grey frame colorful website imagery without competing with it. The feeling is independent, exacting and matter-of-fact, suited to design-led tools, studios and products with a strong body of visible output; dense indexes coexist with broad stretches of empty space.

### Essentials

- Identity is the headline, not an advertising slogan: two bold initial forms occupy separate 680px halves of a 154px-tall masthead, above a 1px rule.
- The opening behaves like an archive desk: 32px side margins, four aligned metadata columns, 12px utility text and a 120px separation before the catalogue begins.
- Actions look like typeset controls rather than buttons: unfilled 12px navigation and mode labels, the latter paired with a parenthesized single-letter state and an 8px flex gap.
- Color belongs to the exhibits, not the architecture: white canvas, #292929 text, #f7f7f7 media stages and #ebebeb rules; saturated colors remain inside the project images.
- Visual proof is serial and numbered: four 332px-wide tiles with 16px column gaps and 40px row gaps, each pairing 14px metadata with a pale sequence number and a 332px square stage.
- The identity reduces rather than disappears on scroll: oversized initial artwork becomes a small pair pinned to the left edge and midpoint; the ending returns to two small 14px credit stacks instead of a promotional banner.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#292929` | `--color-ink` | text, link, action | Primary lettering, titles and links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Utility grey | `#999999` | `--color-muted` | text | Categories, utility labels and subdued navigation. |
| Index grey | `#c4c4c4` | `--color-faint` | text | Sequence numbers, counts and inactive archive rows. |
| Hairline grey | `#ebebeb` | `--color-rule` | border | Thin top rules on catalogue entries and information bands, and the masthead divider. |
| Exhibit grey | `#f7f7f7` | `--color-stage` | surface | Square media stages around visual exhibits. |
| Near-white edge | `#fafafa` | `--color-utility-edge` | border | The exceptionally faint bottom edge of the utility strip. |
| White | `#ffffff` | `--color-canvas` | background, surface | Page and masthead background; reversed index-row lettering on hover. |

## Typography

- **SoehneBuch** — All live text, from metadata to introductory prose and indexes. A compact neo-grotesk with regular weight, close-set letters and little typographic ceremony. If unavailable, use **Inter**. Use 400 for live text; retain the negative tracking. Font stack: "SoehneBuch", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| body | SoehneBuch | 400 | 14px | 1.14 | -0.02em | Catalogue names, categories, sequence numbers, prose, section labels and footer credits. |
| utility | SoehneBuch | 400 | 12px | 1 | -0.023em | Navigation, compact role description and system readout. |
| mode-control | SoehneBuch | 400 | 12px | 1 | normal | Mode labels and their parenthesized state indicators. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| information and credibility pages | statement-index | SoehneBuch | 400 | 28px | 1.14 | -0.03em, features "lnum", "tnum" | Introductory statement and tightly stacked evidence-index rows. |

**Notes:**

- The masthead is bold vector letter artwork, separate from the regular-weight live-text scale. Its visible letter height is about 150px at desktop; do not inflate ordinary headings to imitate it.
- Live text has only a small hierarchy: 12px utilities, 14px catalogue text, and a scoped 28px statement/index treatment. Tracking tightens proportionally for the latter.
- Keep grey hierarchy within the same weight rather than introducing bold subheads.

## Layout

**Density:** Airy at page level, compact within each record: thin metadata stacks and uninterrupted lists sit inside a spacious architectural grid.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Top inset under rules and gaps within utility controls. |
| 12px | Catalogue metadata margin before the media stage. |
| 16px | Column gutter and footer bottom padding. |
| 28px | Statement-to-prose separation on information pages. |
| 32px | Page side inset and space preceding the footer. |
| 40px | Catalogue row gap. |
| 120px | Space between the header reserve and the first content band. |
| 200px | Bottom breathing room of information bands. |

### Containers and grids

- **page-grid**: 12 columns · gap 16px · side padding 32px. Fluid full-width desktop composition; content spans 1376px at a 1440px viewport, not a narrow centered marketing column.
- **catalogue**: 4 columns · gap 16px. Equal-width visual records with a separate 40px vertical gap; each record is 332px wide at desktop.
- **information-split** (only for information and credibility pages): 2 columns · gap 16px. Left half carries small section/location labels; right half carries the statement or index.
- **prose** (only for information pages): max width 395px. Compact supporting paragraphs under the statement; statement max-width is 530px, constrained to 448px in its desktop column.

## Corner radius

| Element | Radius |
| --- | --- |
| media-stage | 6px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous background across the entire page.

**CSS:** `background: #ffffff; color: #292929`

**Observed:** No alternating dark bands, gradients, textures or raised material effects.

**Transfer:** Let the grid, images and type provide differentiation.

#### Exhibit stage · level 1

**Use:** Backing for each catalogue image.

**CSS:** `background: #f7f7f7; border-radius: 6px; overflow: hidden; position: relative`

**Observed:** A square pale field contains a narrower upright image, centered horizontally and flush to the stage bottom.

**Transfer:** Maintain the stage even when the exhibit is a product view rather than a website.

#### Ruled band · level 0

**Use:** Separate records and information sections without enclosing them.

**CSS:** `border-top: 1px solid #ebebeb; padding-top: 8px`

**Observed:** The rule precedes the label, not the image alone.

**Transfer:** Use horizontal divisions instead of boxed text panels.

## Components

### Identity masthead

**Use:** Brand-scale opening and persistent scroll identity.

**CSS:** `background-color: #ffffff; border-bottom: 1px solid #ebebeb; padding-top: 13px; padding-bottom: 11px`

**Observed:** Two bold initial artworks occupy the left edge of each half. A full-name wordmark is the information-page variant. The scrolled state shows only small initials at the same anchors.

**Transfer:** Make a custom initial pair from the new identity; preserve the split anchors, not the original letters.

### Utility navigation

**Use:** Primary page switching in the second grid column.

**CSS:** `color: #292929; font-size: 12px; line-height: 12px; letter-spacing: -0.3px`

**Text style:** `utility` — SoehneBuch 400 · 12px/1 · tracking -0.023em

**Observed:** Two links stack without enclosing shapes; current and alternate destinations are distinguished through charcoal and grey.

**States:** Declared: hover color hsla(60, 0%, 60%, 1).

### Mode control

**Use:** Compact presentation preferences in the third metadata column.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 8px; color: #999999`

**Text style:** `mode-control` — SoehneBuch 400 · 12px/1

**Observed:** Three text-only controls stack tightly, with state letters aligned in a second narrow column. They are not switches or pill buttons.

**States:** Declared: hover color hsla(0, 0%, 16%, 1).

**Transfer:** Use for actual presentation controls only; retain the label-plus-parenthesis construction.

### Catalogue record

**Use:** Clickable visual proof entry.

**CSS:** `border-top: 1px solid #ebebeb; padding-top: 8px; color: #292929`

**Text style:** `body` — SoehneBuch 400 · 14px/1.14 · tracking -0.02em

**Observed:** Name and muted category sit at left above Exhibit stage; a descending two-digit index sits at right on the category baseline. Metadata has an 8px bottom inset and 12px margin before the stage. The entire entry acts as a link.

**Transfer:** Use names, use cases or demonstrations as the title, with a factual content type underneath.

### Media viewport

**Use:** Consistent framing inside Exhibit stage.

**CSS:** `position: absolute; width: 242px; height: 286px; overflow: hidden; transform: translate(-50%, 0px)`

**Observed:** Centered within a 332px square with 45px side space and about 46px above; image fills the upright viewport and ends at the square's bottom. These are miniatures of real designed pages, not browser-window chrome.

**Transfer:** Scale the proportions with the tile; use clear product compositions with a strong upper region.

### Credit footer

**Use:** Small final sign-off after the content.

**CSS:** `padding-bottom: 16px; margin-top: 32px; position: relative`

**Text style:** `body` — SoehneBuch 400 · 14px/1.14 · tracking -0.02em

**Observed:** A faint full-width rule precedes two stacks aligned at the page left and midpoint. Copyright marker sits over year; a muted credit label sits over a short linked studio name. No multi-column sitemap or final sales pitch.

**Transfer:** Use a current year and a brief genuine attribution or ownership line.

### Evidence index row

**Only for:** information and credibility pages

**Use:** Text-only proof catalogue with counts or award descriptors.

**CSS:** `display: grid; position: relative; grid-template-columns: repeat(6, 1fr); gap: 16px; color: #292929`

**Text style:** `statement-index` — SoehneBuch 400 · 28px/1.14 · tracking -0.03em

**Observed:** Unbroken approximately 32px rows in the right half of the page. Name spans most columns; pale count occupies the following column. The descriptor variant uses two wider text columns. Non-linked historical entries fade as a whole.

**States:** Declared: hover color hsla(0, 0%, 100%, 1); a pseudo-element background uses hsla(0, 0%, 16%, 1).

### Personal sign-off

**Only for:** personal profile pages

**Use:** Handwritten counterpoint beneath informational prose.

**CSS:** `position: relative; margin-top: 35px; height: 120px`

**Observed:** A thin, dark 120px square signature drawing overlaps a hairline extending across the prose column.

**Transfer:** Use an authentic signature or a restrained original drawn flourish, kept small against the typographic system.

## Imagery and graphics

### Miniature page exhibits

**Use:** Primary visual content of the catalogue.

**Observed:** Upright views of carefully designed websites: typography-led pages, photographs, product compositions and graphic color fields. Each sits inside Exhibit stage as an unshadowed rectangular miniature. Colors vary strongly between exhibits while the surrounding page remains neutral; imagery takes most of each record, with captions occupying only a shallow strip.

**Transfer:** Show real outputs, product screens, packaging layouts or demonstrations with equally legible composition. With no finished media, create a typographic product specimen using actual content and one relevant image; keep the same upright framing rather than leaving an empty stage.

### Split letter identity

**Use:** Required visual anchor above the catalogue and in the compact scroll header.

**Observed:** Heavy charcoal uppercase initials are separated by half a page of white space. The full-name variant fills both halves with a tightly fitted wordmark; live content below remains much smaller.

**Transfer:** Construct a distinctive pair of initials or two-part product title. Keep their cap heights equal and align the second form with the page midpoint.

**Build:** Use two SVG viewports in a two-column grid with a 16px gap. Draw or convert heavy neo-grotesk capital forms to paths, fill #292929, set the desktop artwork height to 154px, and left-align each shape. For the compact state scale both forms down to roughly 36px high while retaining their grid anchors; for a full-name variant fit each word into its half without stretching individual glyphs.

## Section recipes

How recurring sections are built.

### First screen: Identity and catalogue opening

**Observed:** Canvas runs behind Identity masthead and a compact four-column utility strip. The two initial forms dominate only the top 179px rather than becoming a centered sales headline. Utility navigation occupies the second quarter; Mode control the third; a role label and system readout anchor the outer quarters. A broad empty interval separates this header from the catalogue, whose first top rules begin around 358px. Catalogue record uses 14px body text, followed by Media viewport on Exhibit stage. Within 900px the complete first row of four images and the metadata plus upper edge of the next row are visible; all later records and Credit footer fall below. Primary actions are navigation and the records themselves, not a separate CTA pair.

**Transfer:** Make the product identity the visual headline and place concrete demonstrations directly beneath the utility strip. If there is no portfolio, use product-use specimens or outputs in the same numbered format. Information-oriented pages use a full wordmark and replace the catalogue with a left-label/right-statement split.

**Avoid:** Do not substitute a centered slogan, giant paragraph and rounded conversion buttons for this index-like first impression.

**Text style:** `body` — SoehneBuch 400 · 14px/1.14 · tracking -0.02em

### Serial visual proof

**Observed:** Catalogue records repeat on the page-grid in four columns with 16px horizontal and 40px vertical gaps. The last row may remain incomplete and left-aligned, leaving clean white space to its right.

**Transfer:** Choose enough genuinely distinct visual examples to make the serial format meaningful; preserve the numbering device without requiring the same number of records.

### Ledger ending

**Observed:** After the last record or the final faded index entries, white space resolves into Credit footer. On the visual catalogue the final two records occupy only the left half; on the text-led variant a 200px bottom inset gives the index a deliberate end before the footer.

**Transfer:** Close with ownership and attribution rather than adding an unrelated conversion panel.

### Statement with marginal facts

**Only for:** information pages

**Observed:** Ruled band carries small factual labels and contact information in the left half. Right-half 28px statement leads 14px prose in a 395px measure, separated by 28px; Personal sign-off follows. The band ends with 200px of breathing room.

**Transfer:** Use for an explanation of purpose, method or team; keep factual side information separate from narrative prose.

**Text style:** `statement-index` — SoehneBuch 400 · 28px/1.14 · tracking -0.03em

### Label and proof index

**Only for:** information and credibility pages

**Observed:** Ruled band aligns a two-line 14px label at left with Evidence index row in the right 680px half. Recognition rows pair name and descriptor; relationship rows pair name and faint count. There are no badges or logo walls. A 200px bottom space separates the index from the next boundary.

**Transfer:** Use verified integrations, recognitions or contributors as an index; show counts only when they mean something.

**Text style:** `statement-index` — SoehneBuch 400 · 28px/1.14 · tracking -0.03em

## Page flow

**Storyline:** identity → visible body of work or concise explanation → indexed proof → restrained attribution

### Visual-led product or work catalogue

1. **Identity** — Split initial artwork with functional metadata.
2. **Demonstration** — Numbered four-column visual records, with titles and content types.
3. **Closing** — Incomplete final row stays left-aligned, followed by two small credit stacks.

**Transfer:** Use the catalogue as the main argument: demonstrate breadth or concrete outputs instead of a long feature pitch.

### Text-led profile and credibility presentation

1. **Identity** — Full-width name artwork over the shared utility grid.
2. **Explanation** — Left-side factual metadata paired with a right-side statement, supporting prose and signature.
3. **External proof** — Recognition names and descriptors in a tight large-text index.
4. **Relationship proof** — Long partner index with pale counts and muted historical entries.
5. **Closing** — White breathing room and the same minimal credit footer.

**Transfer:** Replace biographical material with a product's method and verified ecosystem; keep this as a scoped editorial variant, not the default catalogue opening.

## Writing

Understated professional confidence, factual in labels and warm but measured in prose. Work is presented as the argument rather than surrounded by slogans.

**Do not copy:** Do not reuse the original personal name, initial artwork, signature, project/client names, email, credits, awards, experience claim or numerical proof as another brand's assets or achievements. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First-person singular for the independent practitioner's prose; labels are impersonal. A product or team can use its own truthful first-person voice without turning every line into direct-address sales copy.
- **Rhythm:** Short noun labels and compact factual categories dominate. Editorial prose uses complete sentences and longer explanatory statements, followed by a shorter personal paragraph.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Identity descriptor | A plain role, not a promise. | 2–3 words | “Independent Developer” |
| Catalogue metadata | Name above literal format or output type. | 1–4 words per line | “Studio website”<br>“Digital product” |
| Section label | A category and its index function on separate lines. | 1–2 words per line | “Clients”<br>“Index” |
| Editorial lead | State specialism directly, then explain the range of people served. | Two complete sentences | “I specialise in front-end development. Being independent, I work with small to large companies, startups, design studios, and creative individuals globally.” |
| Utility action | Literal destination or presentation setting. | 1–2 words | “Information”<br>“Text mode” |

**Words and phrasing to use:** independent; specialise; interaction; detail-oriented; working relationships; Website; Index

**Avoid:** revolutionary; game-changing; unlock your potential; supercharge; world's best

**Rules:**

- Lead labels with concrete nouns; omit adjectives that do not distinguish the item.
- Use numerical proof as a quiet index column rather than an oversized statistic.
- Make long prose specific to the method and relationships behind the work.
- Keep navigation labels literal and credit labels short.

## Do's and Don'ts

### Do

- Use 32px desktop side insets and 16px column gutters.
- Set catalogue captions at 14px/1.14 with -0.02em tracking and weight 400.
- Keep the square stage #f7f7f7 with 6px corners.
- Align the second identity mark, long-form content and second footer stack to the same midpoint.
- Place 1px #ebebeb rules above records and information bands.
- Preserve the contrast between 12px operational labels and monumental identity artwork.
- Keep index counts #c4c4c4 and aligned in their own column.

### Don't

- Do not turn 14px catalogue titles into bold 24px card headings.
- Do not add shadows or floating glass panels to the square stages.
- Do not promote colors from individual exhibits into full-page brand backgrounds.
- Do not replace the 6px stage corners with 24px rounding or pill containers.
- Do not add browser toolbars and device frames to every miniature.
- Do not justify or widen the 395px prose measure across the full right half.
- Do not spread index rows into spacious individual cards; retain their approximately 32px cadence.

## Motion and responsive

### Motion

**Observed:**

- Declared: media-stage background-color transition .2s var(--easingOut).
- Declared: masthead background and border-color transitions .4s var(--easingOut); utility strip transform .8s cubic-bezier(.83, 0, .17, 1).
- Seen: the initial artwork is small in scrolled views, retaining left and midpoint anchors.

**Transfer:**

- Retain the change from monumental identity to compact anchored initials rather than swapping in a conventional sticky navigation bar.
- Use the declared short background transitions for exhibit feedback, not decorative entrance effects.

**Unknown:**

- The resolved value of --easingOut and exact scroll thresholds are unknown.
- Mode-change outcomes, media-opening behavior and focus-visible states are not established.

### Responsive

**Observed:**

- Stylesheets declare width breakpoints at 768px, 950px and 1200px.
- Desktop catalogue has four columns; header role and configuration groups carry small-screen hiding classes.

**Transfer:**

- For narrow layouts, reduce catalogue columns while retaining numbered captions and square stages; keep the identity's two anchors legible.
- Prioritize page navigation over optional system readouts when the utility strip cannot fit.

**Unknown:**

- Exact mobile type sizes, column counts and menu presentation are unknown; these collapse rules are recommendations rather than established mobile behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
