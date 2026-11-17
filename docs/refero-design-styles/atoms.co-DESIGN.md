# Atoms — earthbound industrial ambition

## Overview

A black, earth-toned identity that feels more like an industrial manifesto than a software sales pitch. Warm ivory grotesk type, muted bronze landscape imagery and spare links create a stark but human atmosphere. Monumental symbols and a wide closing wordmark punctuate an otherwise restrained mix of compact portfolio information and dense editorial writing.

### Essentials

- An emblem leads before the promise: a roughly 376px square earth-textured geometric object floats above a centered three-line 44px/1 headline in a 900px first screen.
- Headlines speak rather than shout: Switzer 400 at 44px/44px with -0.4px tracking; smaller card copy uses 16px/18px at 500.
- Actions are unboxed words, not pills: 16px/18px text with 4px vertical padding and small trailing arrows; filled shapes are reserved for 10px category badges.
- Black is the overwhelming field: #000000 spans every section, warm ivory carries text, and sand #c8ad86 marks numbers, chapter headings and the monumental closing artwork. Earth color stays within imagery and lettering, never alternating bright bands.
- Pictures feel excavated rather than polished: sepia aerial terrain and route lines become wide, low banners or masked geometric symbols. Every new landing page needs an earth-textured emblem; a simple original SVG mask over monochrome material photography is the fallback.
- The ending is a typographic monument: a 1200px-wide, 165px-high extended wordmark sits 56px below a 2px divider, with a single row of 16px utility links 10px below it.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sand | `#c8ad86` | `--color-sand` | text, accent | Chapter titles, section numbers, credits and broad closing wordmark. |
| Cream symbol | `#fff7dc` | `--color-symbol` | accent | Solid portfolio symbols against black. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Earth bronze | `#957951` | `--color-earth` | surface, accent | Media tint backing, mixed with monochrome photographic detail rather than used as a page band. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm ivory | `#e6dec7` | `--color-text` | text, link, action | Headings, navigation and portfolio copy; rgba(255,247,221,0.9) over black. |
| Absolute black | `#000000` | `--color-canvas` | background, surface | Continuous page field and media tile backing. |
| Charcoal badge | `#1c1c1c` | `--color-badge` | surface | Visible result of white at 11% over black; tiny category lozenges. |
| Graphite rule | `#333333` | `--color-rule` | border | Visible result of white at 20% over black; horizontal chapter and footer separators. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial quotation interludes | Weathered ivory | `#999485` | `--color-muted` | text | Reduced-emphasis quotation text; rgba(255,247,221,0.6) on black. |
| editorial and manifesto content | Pale chalk | `#eff0e3` | `--color-prose` | text | Long-form paragraphs; rgba(254,255,241,0.94) over black. |

## Typography

- **Switzer** — All principal headings, body, labels and utility links. Contemporary neo-grotesk with open counters; regular headings and medium-weight dense text. If unavailable, use **Inter**. Use 400–600; preserve compact line heights and negative tracking. Font stack: "Switzer", "Inter", Arial, sans-serif.
- **Inter** (only for header dropdown labels) — Dropdown navigation label. Neutral grotesk with a slightly more utilitarian rhythm. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | Switzer | 400 | 44px | 1 | -0.0082em | Primary promise, portfolio section title and article titles. |
| compact-body | Switzer | 500 | 16px | 18px | -0.0156em | Portfolio descriptions, navigation, footer and primary text actions. |
| item-title | Switzer | 500 | 16px | 1 | -0.031em | Short title beside a category badge. |
| number | Switzer | 500 | 14px | 1 | 0.018em, uppercase | Two-digit chapter indexes, section counts and small list headings. |
| micro-link | Switzer | 400 | 12px | 1 | -0.042em | Compact external links beneath portfolio descriptions. |
| badge | Switzer | 500 | 10px | 1 | normal | Category names inside tiny rounded badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial quotation interludes | quote | Switzer | 400 | 54px | 1 | -0.0067em | Centered two-line quotation interrupting the reading column. |
| editorial process explanations | diagram-heading | Switzer | 400 | 32px | 1 | -0.0078em | Centered title over a three-step explanation. |
| numbered manifesto chapters | chapter-heading | Switzer | 500 | 24px | 1.4 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Sand-colored headings along the chapter rule. |
| editorial and manifesto content | body | Switzer | 500 | 20px | 1.2 | -0.0125em | Long-form paragraphs and inline editorial links. |
| header dropdown labels | dropdown-label | Inter | 500 | 16px | 1.2 | normal | Navigation dropdown text next to a small chevron. |
| signed articles and quotations | credit | Switzer | 600 | 11px | 1 | normal, uppercase | Author attribution and name beneath a signature. |

**Notes:**

- The headline is modest relative to the opening symbol; do not inflate it to the scale of the footer artwork.
- Headings remain regular while prose is medium. Chapter titles tighten to -0.04em, distinctly tighter than the main 44px heading.
- Long-form emphasis uses selective 700 weight or italic at the same 20px/24px size; it does not introduce a new face.
- The broad closing wordmark is artwork with extended letterforms, not the 44px heading enlarged.

## Layout

**Density:** Airy framing around compact content: large black intervals separate tightly set information and paragraphs.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Tiny arrow-to-label gaps and thin horizontal separators. |
| 8px | Item title to description, or title to badge. |
| 16px | Portfolio column gutters and description-to-links spacing. |
| 20px | Media tile to its metadata block. |
| 24px | Article heading to body, process column gaps and quotation vertical padding. |
| 28px | Paragraph separation in long-form text. |
| 44px | Desktop navigation link gaps and process title-to-columns gap. |
| 48px | Portfolio grid row gap and section-title-to-grid gap. |
| 50px | Editorial banner-to-title gap. |
| 56px | Footer rule-to-wordmark gap. |
| 60px | Separation between editorial chapters. |
| 160px | Footer top padding before its rule. |

### Containers and grids

- **wide frame**: max width 1200px · side padding 80px. Centered portfolio and footer frame; at 1440px the actual content margins are 120px. Navigation uses this same maximum with 40px outer padding.
- **portfolio grid**: 12 columns · gap 16px. Three four-column cards in the first row, four three-column cards in the second; 48px row gaps.
- **reading column** (only for editorial and manifesto content): max width 912px. Centered article text and banner media; at 1440px the side margins are 264px.
- **process grid** (only for editorial process explanations): max width 912px · 3 columns · gap 24px. Three 288px-wide, text-only process explanations.

## Corner radius

| Element | Radius |
| --- | --- |
| media tiles | 4px |
| category badges | 100px |

## Surfaces and depth

### Surfaces

#### Black canvas · level 0

**Use:** All page sections.

**CSS:** `background: #000000`

**Observed:** The same field continues behind content, hero and footer without alternating surface bands.

**Transfer:** Separate narrative blocks with distance and rules rather than new background colors.

#### Portfolio media tile · level 0

**Use:** A stage for a centered cream logo or abstract product emblem.

**CSS:** `background: #000000; border-radius: 4px; overflow: hidden`

**Observed:** 304px high, with widths of 389px or 288px; very faint rectangular edges visually separate the tiles from the field.

**Transfer:** Use restrained edges rather than raised cards; put the description outside the media rectangle.

#### Category lozenge · level 1

**Use:** Small classification beside item titles.

**CSS:** `background: rgba(255,255,255,0.11); border-radius: 100px; padding: 0px 6px; height: 18px`

**Observed:** The tiny badge is the only recurring pill treatment.

**Transfer:** Limit to category nouns, not conversion actions.

#### Content fade

**Use:** Transition from opening artwork into the portfolio.

**CSS:** `background-image: linear-gradient(rgba(0,0,0,0) 0%, #000000 25%)`

**Observed:** Black gradually consumes the remaining hero image behind the next content field.

**Transfer:** Blend the atmospheric object into the continuous canvas without a hard band boundary.

#### Editorial earth media

**Only for:** editorial banner media

**Use:** Wide photographic banner.

**CSS:** `background-color: #957951; mix-blend-mode: luminosity; opacity: 0.8; overflow: hidden`

**Observed:** Muted terrain detail is fused into a bronze backing, with additional attenuation from its enclosing layer.

**Transfer:** Tune photographic contrast to remain subdued; preserve readable rock, soil or route detail.

## Components

### Fixed navigation

**Use:** Persistent orientation above the opening and reading content.

**CSS:** `height: 98px; padding: 36px 40px; display: flex; align-items: center; justify-content: center`

**Text style:** `compact-body` — Switzer 500 · 16px/18px · tracking -0.0156em

**Observed:** A small cream wordmark anchors the left of a 1200px inner frame. Four sparse links sit at the right with 44px gaps; the careers item has a chevron. The enclosing layer is fixed above content.

**Transfer:** Use a short brand mark and a small number of destination links, not a full menu bar.

### Text action

**Use:** Primary and secondary navigation or conversion.

**CSS:** `color: #e6dec7; padding: 4px 0px; background: none; display: inline-flex; align-items: center; gap: 2px`

**Text style:** `compact-body` — Switzer 500 · 16px/18px · tracking -0.0156em

**Observed:** No filled container or visible button border. Hero actions are paired beneath the statement; some actions carry a trailing right arrow.

**Transfer:** Prefer a clear verb or destination to a loud sales CTA.

### Portfolio card

**Use:** Present a product, initiative or capability as a compact identity.

**CSS:** `display: flex; flex-direction: column; gap: 20px`

**Text style:** `compact-body` — Switzer 500 · 16px/18px · tracking -0.0156em

**Observed:** Portfolio media tile first; item title plus Category badge next; short paragraph below; External micro links last. Text occupies about 90% of the tile width, aligned left.

**Transfer:** For one product, show a small family of capabilities with original symbolic identities.

### Category badge

**Use:** Classify each portfolio entry.

**CSS:** `background: rgba(255,255,255,0.11); border-radius: 100px; height: 18px; padding: 0px 6px; display: inline-flex; align-items: center; color: #e6dec7`

**Text style:** `badge` — Switzer 500 · 10px/1

**Observed:** Sits beside, not above, the item title. The label is slightly subdued inside the lozenge.

### External micro links

**Use:** Secondary destinations beneath card copy.

**CSS:** `display: inline-flex; gap: 2px; padding: 4px 0px; color: #e6dec7`

**Text style:** `micro-link` — Switzer 400 · 12px/1 · tracking -0.042em

**Observed:** Tiny outward arrows follow each label; multiple links use 16px spacing.

### Monumental footer

**Use:** Close every page with a branded visual full stop.

**CSS:** `padding: 160px 80px 64px; display: flex; flex-direction: column; align-items: center; gap: 60px`

**Text style:** `compact-body` — Switzer 500 · 16px/18px · tracking -0.0156em

**Observed:** Inside a 1200px maximum frame: a 2px rule, 56px gap, extended sand wordmark spanning 1200px by 165px, then 10px to a single utility row. Copyright, contact, social, careers and legal links spread across the full width.

**Transfer:** Create a wide original wordmark or a typeset extended name in SVG; maintain its monumental width and the low single-line link row.

### Numbered chapter header

**Only for:** numbered manifesto chapters

**Use:** Create a readable scaffold for a long argument.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; color: #c8ad86`

**Text style:** `chapter-heading` — Switzer 500 · 24px/1.4 · tracking -0.04em

**Observed:** A 2px graphite rule spans the reading column. Title starts 22px below the section top; the 14px two-digit index is pinned at the far right, aligned to the title top. Prose starts 15px after the title.

**Transfer:** Number actual conceptual chapters rather than every small feature.

### Inline editorial link

**Only for:** editorial content

**Use:** Connect an article to a deeper argument.

**CSS:** `color: #e6dec7; text-decoration-line: underline`

**Text style:** `body` — Switzer 500 · 20px/1.2 · tracking -0.0125em

**Observed:** Lives inside the flow of a paragraph rather than as a separate button.

**States:** Declared: hover color rgba(255,247,221,0.8) with underline retained; focus-visible not specified.

### Signature signoff

**Only for:** signed editorial letters

**Use:** End a personal letter with authorship.

**CSS:** `display: flex; flex-direction: column; gap: 16px`

**Text style:** `credit` — Switzer 600 · 11px/1 · uppercase

**Observed:** A reading-column divider precedes an ivory handwritten signature 162px by 72px, followed by a small sand uppercase name. The signature begins 18px below the section top.

**Transfer:** Use an authentic signature or an original author mark, retaining the small scale.

## Imagery and graphics

### Earth-textured emblem

**Use:** Signature opening object for a landing page.

**Observed:** Four stepped, softly rounded corner forms surround a large black cross-like void. Low-contrast aerial earth imagery is visible within bronze shapes, with darker detail at the top and clearer terrain below. The roughly 376px square object occupies the central upper half of the screen; no frame or drop shadow surrounds it.

**Transfer:** Make a geometric emblem meaningful to the new product and fill it with subdued material imagery. Minimum equivalent: a simple original negative-space SVG symbol with one monochrome photograph clipped into it.

**Build:** Create an SVG mask in a 400px square viewBox using four mirrored stepped shapes around an empty center. Use rounded corners near 8px, broad black channels between the pieces and a central void near one third of the width. Clip an aerial terrain image into the mask; grayscale it, place a bronze #957951 layer above it at low opacity, and darken its upper portion with a transparent-to-black vertical gradient. Keep the result flat, without bevels or glow.

### Portfolio identity marks

**Use:** Visual anchors inside black media tiles.

**Observed:** Cream flat wordmarks and geometric symbols sit centered with ample surrounding black. Some symbols are small and solid; others are horizontally extended. They are not product screenshots.

**Transfer:** Give each capability a simple silhouette or short wordmark. Use cream and consistent optical weight instead of a row of full-color logos.

### Extended closing lettering

**Use:** Signature device in the Monumental footer.

**Observed:** Broad, almost mechanical uppercase lettering in muted sand spans the entire content frame. Heavy strokes, flat terminals and wide rounded counters create an architectural silhouette.

**Transfer:** Use an original extended wordmark with equally broad proportions; a stretched display name rendered as SVG is the minimum equivalent.

**Build:** Set the new name in a heavy extended grotesk, convert to SVG paths and fit it into a 1200px by 165px viewBox. Preserve a nearly full-width silhouette, flat baseline and sand fill, with no outline or shadow. Adjust width optically rather than increasing normal body font size.

### Geological banner

**Only for:** editorial and manifesto openings

**Use:** Set a physical, material tone before long-form prose.

**Observed:** 912px by 320px panoramic aerial terrain, showing river-like cuts and craggy earth. Sepia and bronze dominate, with muted highlights; the rectangle is unframed and square-cornered on black.

**Transfer:** Use close aerial geology, raw material or industrial topography related to the new offering, not a smiling lifestyle photo.

### Route-map film

**Only for:** announcement openings

**Use:** Announcement opening media.

**Observed:** A dark, wide film panel displays thin sand route lines over dim terrain, with a bright centered wordmark. The atmosphere is archival and cartographic rather than a brightly colored data dashboard.

**Transfer:** Use a short monochrome material or network film with an original centered title. A still with restrained route lines is sufficient if film is unavailable.

**Build:** For a still fallback, overlay a dark desaturated terrain image with an SVG of gently curving connected paths, 1px strokes in sand at 25–45% opacity. Keep paths irregular and geographic, then center an ivory original wordmark above them.

### Icons

**Observed:** Small trailing arrows and a down chevron are the main interface symbols: 12px for portfolio links, 16px for the header chevron and 18px for a section action. They appear light against black and visually follow the text.

**Transfer:** Use simple thin arrows and chevrons matching the text color. Avoid decorative feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Emblem and promise opening

**Observed:** A full 900px black first screen carries Fixed navigation at the top. Centered below it is the Earth-textured emblem, about 376px square, beginning roughly one fifth of the way down the screen. Beneath a generous interval, the centered 44px/44px regular headline spans about 410px and wraps into three balanced lines; its final line carries a subtle sandward warmth. Two Text actions sit in a centered row underneath, one brighter than the other. Back to front: black canvas, terrain inside the symbol mask, warm headline, small text links, fixed header. The emblem, full promise and both actions are visible within 900px; there is no separate supporting paragraph. The next section title starts just below the fold.

**Transfer:** Lead with an original material-filled emblem and a concise outcome statement, not a screenshot. Keep the first-screen hierarchy object → promise → understated actions. Editorial page types instead open with a 912px by 320px banner at 144px from the top, then 50px to a left-aligned 44px title and 24px to prose.

**Avoid:** Do not turn this into a left-copy/right-dashboard split, add a giant 100px headline, or replace the small text actions with bright filled pills.

**Text style:** `heading` — Switzer 400 · 44px/1 · tracking -0.0082em

### Counted portfolio field

**Observed:** A 1200px frame holds a 44px title with a small sand count beside its top edge and a right-aligned text action. A 48px gap leads to the Portfolio card grid: three broad tiles followed by four narrower tiles, 16px column gutters and 48px between rows. Content fade dissolves the opening object into black.

**Transfer:** Use a counted collection when the offering has distinct products or capabilities; vary column spans while keeping media heights aligned.

**Text style:** `heading` — Switzer 400 · 44px/1 · tracking -0.0082em

### Authored ending and monumental close

**Observed:** A signed letter ends with a short personal line, divider and Signature signoff. All page types then close with Monumental footer on the uninterrupted Black canvas; the large wordmark replaces a conventional last sales panel.

**Transfer:** Keep the monumental closing lettering on new pages. Add the personal signoff only when the page is genuinely authored.

### Numbered argument chapters

**Only for:** long-form manifesto pages

**Observed:** Within the 912px reading column, Numbered chapter header combines rule, title and top-right index. Medium 20px/24px prose follows with 28px paragraph spacing. Successive chapters have 60px separation.

**Transfer:** Use this for a substantial thesis, technical explanation or founder narrative rather than turning every paragraph into a card.

**Text style:** `chapter-heading` — Switzer 500 · 24px/1.4 · tracking -0.04em

### Quotation pause

**Only for:** editorial quotation interludes

**Observed:** The reading column opens into a full-width centered quotation in muted 54px/54px text, usually two lines. A tiny uppercase sand credit sits 10px below; the band has 24px vertical padding and black backing.

**Transfer:** Interrupt a dense argument with one concise, attributable idea relevant to the new product.

**Text style:** `quote` — Switzer 400 · 54px/1 · tracking -0.0067em

### Unboxed explanatory grids

**Only for:** editorial process explanations

**Observed:** A centered 32px title sits 44px above three 288px columns separated by 24px. Each column has a small uppercase step label and 20px explanation. A separate competency list uses plain bullet columns, with no cards or icons.

**Transfer:** Show a short process or taxonomy as aligned text, not boxed feature illustrations.

**Text style:** `diagram-heading` — Switzer 400 · 32px/1 · tracking -0.0078em

### Partner acknowledgment

**Only for:** announcement letters

**Observed:** After the argument, two plain text lists sit side by side in the reading column with a 24px gutter and 24px left inset within each group. Sand uppercase 14px labels classify the lists; names use 20px/24px text rather than a logo wall.

**Transfer:** For an announcement, thank actual collaborators with compact grouped text.

**Text style:** `body` — Switzer 500 · 20px/1.2 · tracking -0.0125em

## Page flow

**Storyline:** symbolic promise → concrete offering or sustained argument → clear authorship or proof → monumental identity close

### A concise portfolio landing page

1. **Promise** — Material-filled emblem over a centered outcome statement and two text destinations.
2. **Offering** — Counted collection with broad identity tiles, compact descriptions, category badges and small outbound links.
3. **Closing identity** — Oversized sand wordmark and low utility row.

**Transfer:** For a single-product landing page, translate the portfolio into a small set of clearly distinguished capabilities, keeping the strong symbolic opening and branded ending.

### A consequential announcement presented as a personal letter

1. **Context** — Short cartographic film before the article title.
2. **Announcement** — Direct statement followed by personal context and an inline deeper-reading link.
3. **Argument** — Large simple subheads organize the broader rationale in dense prose.
4. **Acknowledgment** — Grouped partner names, then divider and personal signature.
5. **Closing identity** — Shared monumental footer.

**Transfer:** Use for a launch, partnership or milestone that merits an authored explanation, with real acknowledgments rather than decorative proof logos.

### An expansive manifesto that articulates a worldview

1. **Personal premise** — Earth banner, short title and first-person introduction.
2. **Thesis** — Numbered, ruled chapters move from mission to a broader case.
3. **Reflection** — Large muted quotation creates a pause in the prose.
4. **Explanation** — Further chapters, a three-step framework and plain bullet columns make the thesis tangible.
5. **Human resolution** — Short concluding line and handwritten signoff.
6. **Closing identity** — Shared monumental footer.

**Transfer:** Use this long-form variant for a product philosophy or technical vision. Choose chapters by argument, not by a fixed count.

## Writing

Earnest, ambitious and materially specific. Compact portfolio descriptions are practical; authored essays are personal, argumentative and willing to use blunt fragments alongside expansive claims.

**Do not copy:** Do not reuse Atoms names, logos, company identities, founder signature, quotations, investment figures, biographical stories or claims of industrial impact. Replace them with original, substantiated product content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Portfolio copy speaks impersonally about what an offering does. Essays use I for lived conviction and we for shared work, with occasional direct questions to the reader.
- **Rhythm:** Short headings name an idea in one to six words. Card descriptions usually fit one sentence; essays combine long explanatory paragraphs with abrupt short sentences and rhetorical questions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Concrete means followed by consequential outcome. | About 10–15 words | “Physical automation to transform industry and move the world.” |
| Section heading | Plain noun or compact thesis, not a promotional slogan. | 1–6 words | “Companies”<br>“Valuable Unknown Truths” |
| Portfolio description | Name the category, job and practical benefit in a single sentence. | 15–25 words | “Robotics for better food. Automated kitchen systems that deliver consistent, affordable meals at scale.” |
| Action | Name the destination or invite reading without pressure. | 1–3 words | “Read vision”<br>“My vision letter” |
| Editorial resolution | A brief first-person statement resolves the preceding argument. | 4–8 words | “The thing is, I never left.” |

**Words and phrasing to use:** build; make; move; systems; infrastructure; progress; productive; understand; predict; control

**Avoid:** magic; delightful experiences; supercharge; game-changing; seamless everything

**Rules:**

- Tie expansive ambition to a specific mechanism, job or physical result.
- Use selective bold or italic emphasis within prose instead of creating callout boxes for every claim.
- Let headings identify the argument; let paragraphs carry the nuance.
- Keep navigation and link labels factual and short.

## Do's and Don'ts

### Do

- Keep main headings regular at 44px/44px rather than bolding them for impact.
- Stage one material-filled emblem above the promise, with a footprint around 376px square.
- Use 16px/18px medium type for compact card descriptions and utility links.
- Keep portfolio tiles 304px high with 4px corners and descriptions outside them.
- Use sand for small indexes and the broad closing wordmark, maintaining a predominantly black page.
- Keep editorial copy within 912px and separate paragraphs by 28px.
- Close with the 1200px-wide wordmark, a 2px rule and single utility row.
- Use 10px category labels in 18px-high lozenges, not full-size tags.

### Don't

- Do not replace black with a navy or charcoal page field; the warm material contrast depends on true black.
- Do not set long-form paragraphs in the muted quotation color; prose uses the brighter chalk tone.
- Do not carry the 100px badge radius into cards; media tiles use 4px.
- Do not add floating card shadows or glossy panels; the layout is flat and ruled.
- Do not substitute colorful product screenshots for the cream identity marks in the portfolio.
- Do not use the tightly tracked 24px chapter treatment as the universal heading; it belongs to the numbered essay variant.
- Do not reduce the footer to a tiny logo beside a multi-column sitemap.
- Do not introduce monospace labels or serif pull quotes; the hierarchy stays grotesk throughout.

## Motion and responsive

### Motion

**Observed:**

- Dropdown label declares a color transition of 0.4s cubic-bezier(0.44,0,0.56,1).
- Inline editorial link declares 0.2s transitions for color and text-decoration properties with cubic-bezier(0.44,0,0.56,1).
- The header remains fixed; its upper field softens content behind it through progressively masked blur layers reaching 5px.

**Transfer:**

- Keep link motion focused on subtle color changes, preserving the unboxed action style.
- If material media moves, retain its restrained monochrome tone rather than turning the opening into a colorful effects reel.

**Unknown:**

- Exact emblem animation behavior, scroll timing and video loop duration are not established.
- Focus-visible and active treatments are not established.

### Responsive

**Observed:**

- Styles declare width boundaries around 810px, 1200px and 1440px.

**Transfer:**

- On narrow layouts, preserve the vertical emblem → promise → actions hierarchy; reduce the object to fit within side gutters.
- Collapse the portfolio and explanatory columns while keeping media above each text block.
- Keep chapter indexes aligned to heading tops, and retain a wide closing wordmark that scales with its frame.

**Unknown:**

- Mobile navigation behavior, exact smaller-screen typography and gutter values are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
