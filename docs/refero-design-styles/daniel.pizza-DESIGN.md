# daniel.pizza — a right-hand commonplace

## Overview

A literary, personal style with a deliberately off-centre composition: small modern sans-serif headings sit above bookish serif prose, surrounded by an unusually open left margin. Light grey paper, soft sage and warm parchment support natural photography, printed objects and matter-of-fact previews of digital work. It suits thoughtful software, independent studios and editorial products that can explain themselves through considered writing and tangible examples rather than a sales spectacle.

### Essentials

- The page reads from a right-hand reading desk: a 512px prose column is aligned to the right of a wider media lane, while fixed serif navigation occupies the bottom-left corner with a 24px edge inset.
- A modest sans headline introduces a literary voice: Degular 40px/46px at weight 500, followed by Blanco 28px/1.2 at weight 400 and Blanco prose at 20px/1.5. Keep tracking normal rather than squeezing the heading into a display logo.
- The opening leaves room for thought before showing work: the text starts about 193px down, and a wider 896px image begins at 636px, extending left of the prose while sharing its right edge. Every new landing page needs this narrow-text/wide-artifact contrast; use a well-lit real object or one carefully framed interface if photography is unavailable.
- Actions are editorial cross-references, not conversion pills: use underlined words inside prose and 22px/1.5 serif navigation. The theme control is a compact 6px-radius icon button, not a model for a large filled CTA.
- Colour belongs to paper and pictures: the default canvas is #ededea, with slate prose and charcoal headings; muted wine #8b5050 is reserved for hover and tiny annotations. Saturated colours remain inside media, never as repeated full-width marketing bands.
- Proof feels filed rather than packaged: use 1px translucent rules, 14px uppercase dates with 0.1em tracking, white 8px-radius bookmark previews, and a small-link closing footer separated from the final content by substantial paper space.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Wine annotation | `#8b5050` | `--color-accent` | link, accent | Text-link hover and small recommendation stars; not a fill colour. |
| Blue photographic backing | `#d9eaf2` | `--color-photo-tint` | surface | Backing for the cool monochrome documentary portrait, not a general section fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep ink | `#111827` | `--color-heading` | text, link | Section headings, article headings and emphasized links. |
| Slate ink | `#374151` | `--color-body` | text, link | Serif prose, navigation and archive titles. |
| Charcoal | `#2a2a28` | `--color-ink` | text | Opening headline, serif callout and media captions. |
| Soft charcoal | `#656562` | `--color-identity` | text | Visible identity colour on grey paper; charcoal at 70% opacity. The same alpha recipe adapts to other paper colours. |
| Footer ink | `#6e6e6c` | `--color-footer` | text | Small utility links and social marks; charcoal at 65% over grey paper. |
| Metadata grey | `#6b7280` | `--color-muted` | text | Dates, sequence labels and taxonomy. |
| Faded ink | `#8c8c89` | `--color-footnote` | text | Footnotes and statistical summaries; charcoal at 50% over grey paper. |
| Focus grey | `#9ca3af` | `--color-focus` | border | Navigation focus ring and hover underlines. |
| Paper rule | `#dadad7` | `--color-rule` | border | Visible 10% charcoal rules on the default paper. |
| Cool card edge | `#e5e7eb` | `--color-card-edge` | border | White preview outlines and pagination divider. |
| Grey paper | `#ededea` | `--color-canvas` | background | Default continuous page canvas. |
| White card | `#ffffff` | `--color-card` | surface | Bookmark preview backing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial feeds | Sage paper | `#e3e7df` | `--color-sage` | background | Continuous background for an editorial feed. |
| catalogue pages | Parchment | `#efe9e2` | `--color-parchment` | background | Continuous background for a chronological catalogue. |

## Typography

- **Degular** — Headings, identity, labels, captions and bookmark previews. A compact, human and slightly soft sans-serif whose modest medium weights feel closer to an editorial title than a corporate display face. If unavailable, use **Inter**. Use weights 400–600 and preserve the restrained sizes. Font stack: "Degular", Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.
- **Blanco** — Reading text, callout, navigation, article titles and utility links. A sturdy literary serif with lively italic forms; comfortable at substantial reading sizes. If unavailable, use **Source Serif 4**. Use regular, medium and true italic; tune wrapping to the 512px text measure. Font stack: "Blanco", "Source Serif 4", "Times New Roman", Times, Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| headline | Degular | 500 | 40px | 46px | normal | Opening statement and page title. |
| heading-major | Degular | 500 | 32px | 1.25 | normal | Larger documentary chapters and structured proof sections. |
| callout | Blanco | 400 | 28px | 1.2 | normal | A personal conviction between headline and explanatory prose. |
| heading | Degular | 500 | 28px | 1.25 | normal | Ordinary project headings and chronological group headings. |
| identity | Degular | 500 | 22px | 1.5 | normal | Fixed textual identity. |
| navigation | Blanco | 400 | 22px | 1.5 | normal | Persistent primary navigation. |
| body | Blanco | 400 | 20px | 1.5 | normal | Primary reading text and inline links. |
| row-body | Blanco | 400 | 20px | 1.3 | normal | Descriptions inside compact dated proof rows. |
| preview-title | Degular | 600 | 18px | 1.25 | normal | White bookmark preview title. |
| caption | Degular | 400 | 16px | 1.25 | 0.025em | Attribution directly below media. |
| preview-description | Degular | 400 | 16px | 1.35 | normal | Bookmark preview description. |
| footnote | Degular | 400 | 16px | 22px | 0.025em | Small collaborator notes and prose-form numerical summaries. |
| date | Degular | 400 | 14px | 1.5 | 0.1em, uppercase | Date ranges and secondary list actions. |
| footer-link | Blanco | 400 | 14px | 1.5 | normal | Utility footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial feeds | article-title | Blanco | 500 | 24px | 1.2 | normal | Linked titles introducing long editorial entries. |
| catalogue pages | archive-title | Blanco | 500 | 22px | 1.2 | normal | Primary title in a catalogue row. |
| catalogue pages | archive-credit | Blanco | 400 italic | 18px | 1.5 | normal | Secondary author or maker line below each title. |
| editorial feeds and catalogue pages | sequence-label | Degular | 600 | 14px | 1.5 | 0.1em, uppercase | Right-aligned sequence numbers or month labels. |

**Notes:**

- The hierarchy switches type class rather than relying on enormous size changes: sans titles identify, serif sentences explain, sans labels organize.
- Keep normal tracking throughout the reading faces. Only small sans captions and footnotes use 0.025em; uppercase metadata uses 0.1em.
- Use genuine serif italics for publication names, quoted passages and secondary credits; do not italicize whole ordinary sections.
- The 40px headline remains conversational. The larger visual gesture comes from the composition and image width, not oversized typography.

## Layout

**Density:** Airy at page scale, with a compact reading measure and closely ruled lists. The wide left field is intentional space, not a second content column.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Media-to-caption gap and small preview exterior margins. |
| 12px | Bottom padding of catalogue entries and vertical padding of feed entries. |
| 16px | Heading-to-body spacing, utility-link gaps and compact row text margins. |
| 20px | Horizontal padding inside bookmark previews. |
| 24px | Fixed header edge padding and gap after the 96px date column. |
| 26.7px | Primary prose paragraph margins. |
| 32px | Photographic portrait margins and pagination separation. |
| 48px | Desktop main side padding and catalogue summary separation. |
| 64px | Separation around wide media and between major content groups. |
| 112.5px | Opening text padding below the main content's 80px top offset. |
| 128px | Footer separation and desktop outer right margin. |

### Containers and grids

- **Desktop shell**: max width 1600px · side padding 48px. Main content has a 320px left margin and 128px right margin. Within it a right-aligned wrapper has a 1400px maximum; at a 1440px window the available media lane is 896px wide.
- **Reading column**: max width 512px. Right-align prose and footer inside the media lane. At desktop this leaves a very broad unoccupied left field.
- **Media lane**: max width 1400px. Wide figures expand left from the reading column and retain its right edge; 896px wide at the desktop reference size.
- **Dated rows**: 2 columns · gap 24px. Use a fixed 96px date column and remaining-width serif description, aligned on the first baseline.

## Corner radius

| Element | Radius |
| --- | --- |
| Media | 3px |
| Bookmark previews | 8px |
| Text-link focus corners | 2px |
| Theme control | 6px |

## Surfaces and depth

### Surfaces

#### Grey paper canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #ededea`

**Observed:** One uninterrupted matte colour sits behind prose, fixed navigation and footer. No panel or shadow separates the header.

**Transfer:** Let page structure emerge from text alignment, spacing and rules rather than alternating backgrounds.

#### White bookmark · level 1

**Use:** A small evidence preview embedded in the prose column.

**CSS:** `background: #ffffff; border: 1px solid #e5e7eb; border-radius: 8px; box-shadow: none`

**Observed:** A rare white island among paragraphs rather than a repeated feature-card grid.

**Transfer:** Use only for links to substantial supporting work or a useful next step.

#### Tinted photographic frame · level 1

**Use:** A documentary image within the reading column.

**CSS:** `background: #d9eaf2; border-radius: 3px; overflow: hidden`

**Observed:** A square photograph of a speaker is treated in cool monochrome, with deep charcoal shadows.

**Transfer:** Apply a restrained cool tint to a real process or people photograph, not to every image.

#### Sage canvas · level 0

**Only for:** editorial feeds

**Use:** Background for a stream of long editorial entries.

**CSS:** `background: #e3e7df`

**Observed:** The tint covers the entire page, including navigation and footer.

**Transfer:** Use the same shell with a single page-level tint.

#### Parchment canvas · level 0

**Only for:** catalogue pages

**Use:** Background for chronological lists.

**CSS:** `background: #efe9e2`

**Observed:** Warm paper behind text-only entries, with no cover tiles.

**Transfer:** Keep the catalogue typographic and lightly ruled.

## Components

### Fixed identity header

**Use:** Persistent identity at the top of the viewport.

**CSS:** `position: fixed; top: 0px; left: 0px; width: 100%; padding: 24px; display: flex; justify-content: space-between; align-items: center; z-index: 50`

**Text style:** `identity` — Degular 500 · 22px/1.5

**Observed:** A plain text identity sits at the left and the Theme control sits at the far right; the paper remains visible behind them.

### Editorial navigation link

**Use:** Primary destinations in the fixed bottom-left navigation.

**CSS:** `display: block; color: #374151; border-radius: 2px`

**Text style:** `navigation` — Blanco 400 · 22px/1.5

**Observed:** Six short destinations form a vertical list, with about 12px between 33px text lines. The active destination has a fine underline; ordinary destinations are not filled buttons.

**States:** Declared: hover color #111827 with a 1px #9ca3af underline offset 3px; focus-visible 1px #9ca3af outline, 1px offset and 2px same-colour ring; active outline and shadow removed.

**Transfer:** Keep the navigation as words on paper, with a comparable handful of destinations.

### Inline reading link

**Use:** Contextual actions and references inside prose.

**CSS:** `color: #111827; text-decoration-line: underline; text-underline-offset: 3px`

**Text style:** `body` — Blanco 400 · 20px/1.5

**Observed:** Links belong grammatically to the sentence; they do not interrupt paragraphs with standalone button rows.

**States:** Declared: hover color #8b5050 and 1px same-colour underline offset 3px; active outline and shadow removed.

**Transfer:** Put a useful next action into a natural sentence.

### Bookmark preview

**Use:** Supporting project or article preview.

**CSS:** `display: flex; justify-content: space-between; background: #ffffff; border: 1px solid #e5e7eb; border-radius: 8px; overflow: hidden; margin-top: 8px; margin-bottom: 8px; transition: border-color 0.2s, transform 0.2s`

**Text style:** `preview-title` — Degular 600 · 18px/1.25

**Observed:** The full preview is linked. Its interior stacks a semibold sans title, smaller sans description and a tiny domain line with a favicon or external-link mark. The interior has 16px vertical and 20px horizontal padding with 5.6px gaps.

**States:** Declared: hover border and text color #8b5050 with no text decoration; active outline and shadow removed.

**Transfer:** Use a short title, two or three lines of supporting text and a real destination domain.

### Dated proof row

**Use:** Experience, release, event or other chronological evidence.

**CSS:** `display: flex; align-items: baseline; border-bottom: 1px solid rgba(42, 42, 40, 0.1)`

**Text style:** `row-body` — Blanco 400 · 20px/1.3

**Observed:** A spaced uppercase date precedes the serif description. The date occupies 96px plus a 24px trailing gap. Description paragraphs have 16px top and bottom margins; rows grow naturally for wrapping or a secondary label.

**Transfer:** Use for evidence with dates, not as a general feature list.

### Theme control

**Use:** Compact colour-mode utility at the top-right.

**CSS:** `display: flex; align-items: center; position: relative; padding: 8px; border-radius: 6px; overflow: hidden; color: #111827`

**Observed:** An unfilled icon-only control shows a small horizon-like solid mark rather than a textual switch.

**States:** Declared: hover background rgba(42,42,40,0.1); focus-visible box-shadow 0 0 #0000,0 0 #0000,0 0 #0000; active transform resets to identity.

### Utility footer

**Use:** Understated ending within the reading column.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; padding-bottom: 24px; margin-top: 128px`

**Text style:** `footer-link` — Blanco 400 · 14px/1.5

**Observed:** Small text utilities sit on the left and four solid social marks on the right. Text utilities have 16px gaps. The default landing-page ending also leaves 225px of paper above the footer's own separation; no large closing banner appears.

**Transfer:** End with useful ancillary links and contact access rather than another pitch.

### Catalogue row

**Only for:** catalogue pages

**Use:** Repeated text-first catalogue entry.

**CSS:** `display: flex; position: relative; align-items: baseline; justify-content: space-between; border-bottom: 1px solid rgba(3, 7, 18, 0.1); padding-bottom: 12px; margin-top: 13.3px; margin-bottom: 13.3px`

**Text style:** `archive-title` — Blanco 500 · 22px/1.2

**Observed:** The title and an italic credit stack at left; a 14px uppercase month aligns at right. Selected titles carry a tiny wine-coloured star. Titles wrap without forcing every row to equal height.

**States:** Declared: title hover color #8b5050 without underline; active outline and shadow removed.

**Transfer:** Keep metadata as a subordinate second line, not a card badge.

### Editorial entry

**Only for:** editorial feeds

**Use:** Long linked observation with mixed media and commentary.

**CSS:** `border-top: 1px solid rgba(3, 7, 18, 0.1); padding-top: 12px; padding-bottom: 12px; margin-top: 13.3px; margin-bottom: 13.3px`

**Text style:** `article-title` — Blanco 500 · 24px/1.2

**Observed:** A serif heading shares a baseline with a right-aligned sequence label. Full-column media, attribution, prose, occasional quotes and small dot-separated taxonomy follow. The first entry has no leading rule.

**Transfer:** Let each entry's substance determine its length rather than imposing uniform cards.

## Imagery and graphics

### Wide tangible proof

**Use:** The primary visual counterweight to the narrow prose column; include this contrast on new landing pages.

**Observed:** Large landscape figures extend leftward beyond the text: a dark-roofed house among green trees and an overhead open book on a grey tabletop. The book has white paper, a narrow red binding and coral printed text; its physical shadows belong to the photograph, not to a surrounding UI card. Figures are 896px wide at desktop with subtle 3px corners and sans attribution 8px below.

**Transfer:** Show the new product in a believable environment, or photograph a physical outcome, workshop or printed artifact under soft natural light. If there is no suitable photograph, present one real interface at this wider scale on a plain backing, with a factual caption. Preserve the leftward expansion and shared right edge.

### Reading-column artifact

**Use:** Secondary media embedded between editorial paragraphs.

**Observed:** A printed magazine cover occupies the 512px reading width, with off-white paper and a greyscale relief sculpture. It feels like a document being shown, not an illustration floating in a decorative scene.

**Transfer:** Use a real report, manual, product detail or well-composed screen. Retain its proportions and enough physical context to understand the object.

### Cool documentary portrait

**Use:** Human or process proof near a structured evidence chapter.

**Observed:** A 512px square shows a speaker at a lectern, with projected printed material behind. The low-saturation blue-grey treatment gives it a slightly archival feel; it has a pale blue backing and 3px corners.

**Transfer:** Choose an actual person using, making or presenting the product. Convert to monochrome and apply a subtle cool cast while retaining shadow detail.

### Editorial mixed media

**Only for:** editorial feeds

**Use:** Illustration, photographs, video embeds and interface studies inside long entries.

**Observed:** Images stay at the 512px column width and retain their differing landscape and portrait ratios. Subjects range from an intimate workshop video to portraits, a vivid yellow bottle with green-and-purple labels, a colourful branching diagram and monochrome icon studies. Small sans credits sit directly beneath; colour intensity belongs to the media rather than the surrounding sage paper.

**Transfer:** Keep the original character of each useful reference rather than applying a uniform brand overlay. Show enough detail for the accompanying commentary to be meaningful.

### Icons

**Observed:** Mostly solid SVG utility and social marks at 20px, with some 16px-wide marks. Footer marks share the faded charcoal of utility links; the theme mark is dark ink. Icons are ancillary, not feature illustrations.

**Transfer:** Use recognizable solid utility marks sparingly, keep accessible text labels on icon-only controls, and align social marks as one small footer cluster.

## Section recipes

How recurring sections are built.

### First screen: Right-hand editorial opening

**Observed:** The continuous Grey paper canvas holds a Fixed identity header with 24px edge padding. Editorial navigation links are fixed at bottom-left, leaving almost the entire left half open. A right-aligned 512px text column begins about 193px down: a single-line 40px medium sans headline, a 28px serif conviction over two lines, then 20px serif prose over about seven lines. The opening has only contextual Inline reading links, not a CTA button row. After 64px, Wide tangible proof expands left into the media lane, keeping the text's right edge. At a 900px viewport, the full headline, conviction and introductory paragraph are visible, followed by the upper 264px of the 448px-tall landscape image. Its caption falls below the fold. Layers are paper, fixed edge utilities, right-hand text and then the wider photograph; nothing overlaps the prose.

**Transfer:** Write a concise identity or product promise, a human statement of intent, and a concrete paragraph explaining what the product does. Stage one real outcome or interface in the wider lane even without bespoke artwork. Feed and catalogue variants instead open with the same 40px title and compact introduction in the reading column, then begin their entries; catalogue filters sit directly under the title.

**Avoid:** Do not centre the opening, fill the left field with a second sales column, or put the main image in a floating device mockup behind the headline.

**Text style:** `headline` — Degular 500 · 40px/46px

### Narrative proof chapter

**Observed:** A 28px sans heading introduces 20px serif paragraphs in the Reading column, usually separated from the preceding chapter by a hairline and substantial vertical space. A White bookmark can follow the explanation; a wider figure can break out left while retaining the common right edge.

**Transfer:** Explain one capability or meaningful outcome in a few factual paragraphs, then offer a real visual or linked supporting artifact.

**Text style:** `heading` — Degular 500 · 28px/1.25

### Dated evidence chapter

**Observed:** A 32px sans chapter heading leads into Dated proof rows. The two columns align on baselines; pale rules and 14px spaced dates keep the list legible without turning it into a table grid. A cool square documentary portrait introduces one such chapter.

**Transfer:** Use releases, milestones, measured work or public activity as evidence. Let rows wrap and use real dates rather than inventing grand statistics.

**Text style:** `heading-major` — Degular 500 · 32px/1.25

### Paper-space ending

**Observed:** The final proof list finishes with a small collaborator footnote, followed by an exceptionally open area of the same paper. Utility footer remains confined to the 512px reading measure while fixed navigation stays at bottom-left. Feed endings add pagination and catalogue endings add an update-and-totals paragraph before the same small footer.

**Transfer:** Give the last substantive item room to settle, then provide contact and reference links. Preserve the small closing scale instead of escalating to a monumental CTA.

**Text style:** `footer-link` — Blanco 400 · 14px/1.5

### Editorial feed opening and entries

**Only for:** editorial feeds

**Observed:** Sage canvas uses the same offset 512px measure and 40px title. A short serif introduction includes a subscription link. Editorial entries combine 24px serif titles, small sequence labels, full-measure media, captions and commentary; quotation blocks use a 1px translucent left rule with 20px inset. The ending includes a fine top divider, centred page count, previous/next arrow controls, then Utility footer.

**Transfer:** Build a thoughtful update feed or resources journal with variable-length entries, explicit attributions and small pagination rather than infinite tile cards.

**Text style:** `article-title` — Blanco 500 · 24px/1.2

### Chronological catalogue and prose summary

**Only for:** catalogue pages

**Observed:** Parchment canvas begins with a 40px title, three compact uppercase category links and two introductory serif paragraphs. Groups use 28px sans year headings and Catalogue rows. After the last group, a small 16px sans paragraph summarizes the update date and collection totals in ordinary prose, with numbers inline rather than in stat tiles. Utility footer follows after generous space.

**Transfer:** Use the pattern for a dated resource archive, changelog or catalogue. Keep the final totals embedded in a sentence and contextualize what is counted.

**Text style:** `heading` — Degular 500 · 28px/1.25

## Page flow

**Storyline:** Plain-language introduction → specific work or curated material → deeper documentary evidence → small contextual ending and utility links.

### An editorial landing page that establishes capability through work and considered explanation

1. **Promise** — A brief sans identity statement, a serif conviction and a grounded introductory paragraph.
2. **Visual proof** — A wide real-world image expands left of the reading column.
3. **Capability chapters** — Prose-led chapters with linked previews, publication artifacts and occasional wider photography.
4. **Documentary proof** — Dated rows and a documentary portrait make the history concrete.
5. **Closing context** — A small collaborator note, expansive paper space and a compact utility footer.

**Transfer:** Use the default off-centre shell for a product or studio; substitute actual outcomes and release evidence for personal history.

### An editorial feed that rewards sustained reading

1. **Orientation** — A simple title, one-paragraph explanation and an inline subscription route.
2. **Curated proof** — Long entries with linked serif headings, sequence labels, media, commentary, quotes and taxonomy.
3. **Continuation** — Previous/next controls and a centred page count.
4. **Utility close** — The small shared footer closes on the same sage paper.

**Transfer:** Use for updates or resources when explanations matter more than card scanning.

### A text-first catalogue organized by time

1. **Orientation** — A simple title, category links and short explanatory paragraphs.
2. **Indexed evidence** — Year groups of ruled title-and-credit rows with small month labels and selective stars.
3. **Quantified context** — An update date and totals are expressed in one faded sans paragraph.
4. **Utility close** — The shared footer remains small on warm parchment.

**Transfer:** Adapt to a knowledge archive or release history, keeping the chronological organization and prose-form closing statistics.

## Writing

Personal, observant and literate, with confidence grounded in specific work. It reads like a thoughtful practitioner explaining choices to an interested reader, including reservations rather than smoothing everything into a sales claim.

**Do not copy:** Do not reuse the identity, publication titles, employer or collaborator names, artwork, personal history, quotations, book lists, counts or claims as the new product's own assets or achievements. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First-person singular explains intentions and experience; the reader is addressed only when it adds context. A product team can use an equally accountable first-person plural, naming what it actually makes.
- **Rhythm:** Brief noun-based headings alternate with full, gently varied paragraphs. Sentence fragments occasionally provide emphasis; ordinary punctuation, contractions, em dashes and italic titles do more work than slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A few concrete nouns state the identity without a superlative. | 3–6 words | “Designer, writer, reader.” |
| Conviction | A personal sentence joins two related concerns. | 10–18 words | “I care about the story as much as the typography it’s set in.” |
| Feed introduction | Explain what the collection is for in one direct sentence. | 15–25 words | “A regularly updated collection of things I find worth reading, watching, or listening to.” |
| Contextual action | A verb and a precise destination or extent, usually within reading text. | 2–4 words | “Read all 39”<br>“Subscribe via” |
| Evaluative aside | Let a precise short judgement follow a fuller explanation. | 3–8 words | “Restrained, but crackling.” |

**Words and phrasing to use:** I care about; I worked on; in collaboration with; worth reading; designed; written; care; craft; story; typography

**Avoid:** revolutionary; 10x; unlock your potential; seamless ecosystem; game-changing; industry-leading; act now

**Rules:**

- Name the work and explain the contribution before asserting quality.
- Make references part of the sentence and credit collaborators beside the relevant work.
- Use italics for titles and a few meaningful asides, not for promotional emphasis.
- Allow modest uncertainty in commentary; a specific reservation can make praise more credible.
- Use counts only when useful, and let them live in prose or labels rather than oversized trophy numbers.

## Do's and Don'ts

### Do

- Keep the primary reading measure at 512px and align its right edge with the wider figures.
- Pair the 40px medium sans headline with a 28px regular serif conviction.
- Use 20px/1.5 serif prose for the main narrative.
- Give figure captions an 8px gap and use 16px sans with 0.025em tracking.
- Keep white previews to an 8px radius and a 1px cool-grey edge with no shadow.
- Use 14px uppercase sans dates with 0.1em tracking in structured rows.
- Retain the fixed 24px-inset identity and bottom-left editorial navigation on desktop.
- Preserve a small 14px serif utility footer after the final content has breathing room.

### Don't

- Do not replace serif body copy with 16px interface text throughout.
- Do not tighten 40px headlines with aggressive negative tracking or inflate them into giant display type.
- Do not turn every narrative chapter into a white feature card; white is reserved for bookmark previews.
- Do not introduce drop shadows, glass blur or gradients onto the flat paper canvas.
- Do not use wine as a large CTA fill or repeat it as a section background.
- Do not turn the dated lists into boxed spreadsheet cells or equal-height tiles.
- Do not stretch the footer into a full-width dark mega-footer.
- Do not impose square image masks on landscape and portrait editorial media.

## Motion and responsive

### Motion

**Observed:**

- Navigation colour and related paint properties use 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- Bookmark previews declare border-color 0.2s and transform 0.2s transitions.
- The theme control declares all 0.15s cubic-bezier(0.4, 0, 0.2, 1).

**Transfer:**

- Keep interactions local to text colour, underlines, borders and the compact theme utility; the composition should remain readable without animated staging.

**Unknown:**

- The exact sequencing of figure changes and the operation of the declared device-scroll keyframe are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 480px, 640px, 768px, 1024px, 1280px, 1536px and 1920px.
- Main layout classes remove the 320px left and 128px right margins below the desktop layout, with 20px side padding at the narrowest size, 24px at the small breakpoint and 48px at desktop.
- Navigation classes provide a horizontally scrollable narrow-screen arrangement; desktop navigation is vertical.
- Wide figure margins are 32px at the narrowest size and 64px at the small breakpoint.

**Transfer:**

- On narrow screens, let prose and wide figures share the available width rather than maintaining an empty left half. Preserve the sans/serif contrast and move the persistent destinations into the compact horizontal navigation treatment.

**Unknown:**

- Exact rendered mobile typography, navigation backing and image scaling have not been established.
- Only the light appearance is specified; the theme toggle exists but the complete dark palette is unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
