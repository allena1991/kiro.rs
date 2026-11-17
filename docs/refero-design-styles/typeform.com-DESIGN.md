# Typeform — conversational product theatre

## Overview

An editorial, personable style that makes software feel like an exchange between people rather than a system of fields. Near-white and aubergine canvases alternate, with purple light and colorful product experiences providing the expressive moments. Fine serif display type contrasts with a light grotesk, while layered interfaces, human video portraits and tactile graphics keep spacious layouts lively. It suits expressive business software, workflow products and approachable AI tools.

### Essentials

- A conversational headline has one changeable object: Tobias 72px/1, weight 400, -2px tracking, with a purple underlined phrase inside an otherwise ink-colored two-line promise.
- The opening is a theatre, not a dashboard: centered text and a 48px action sit above a fan of overlapping 26px-radius product scenes; a roughly 620px-wide foreground scene is crisp while side scenes recede to 0.38 and 0.12 opacity.
- Actions are soft rectangles rather than capsules: 12px corners, 48px main height, 16px labels and 24px horizontal padding; the primary action is aubergine, not purple.
- Color lives in the experiences and their light: the surrounding page is predominantly #faf9fb or #2a222b, with #7761b3 for the changing headline phrase and #a25fba for small labels. Preserve both a light stage and a dark chapter somewhere in a new landing page.
- Software is staged as a human interaction: pair a product panel with a person, then float small outcome cards around it. Include a purple-lit product scene and glowing 44px icon frames; when no interface exists, construct a credible input-to-outcome panel instead.
- Editorial proof interrupts the feature rhythm: 36px serif quotations and 56px serif outcome headlines give evidence the weight of a story, rather than reducing it to tiny logo rows.
- The last promise has its own atmosphere: a centered 72px serif statement over #262028 with a top-centered purple radial glow, a light action 48px below it, then a five-column dark footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial violet | `#7761b3` | `--color-headline-accent` | text, accent | Changing object and underline within the opening headline. |
| Orchid | `#a25fba` | `--color-label-accent` | text, accent, action | Small chapter labels, icon glows and commercial add-on actions. |
| Luminous orchid | `#b96dd5` | `--color-glow` | accent | Thin illuminated frames and light behind product scenes, not full-page fills. |
| Pale orchid | `#eccffa` | `--color-inverse-accent` | text, border | Dark chapter labels and pale purple edges. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Raised white | `#ffffff` | `--color-white` | surface, text | Gallery and plan cards, integration enclosure, and selected inverse display text. |
| Porcelain | `#faf9fb` | `--color-canvas` | background, text, action | Default light canvas, inverse text and light actions. |
| Soft lilac gray | `#f5f3f6` | `--color-soft` | background, surface | Secondary neutral bands and media backing. |
| Story gray | `#eeecee` | `--color-story` | surface | Outcome cards and light-button hover fill. |
| Hairline | `#e5e1e5` | `--color-edge` | border | Card outlines, FAQ separators and comparison rules. |
| Fine-print gray | `#a49da6` | `--color-dim` | text | Gallery category captions and superseded prices. |
| Muted plum | `#655d67` | `--color-muted` | text | Secondary commercial descriptions and inactive light tabs. |
| Soft dark plum | `#564b58` | `--color-hover` | surface, border, action | Dark-button hover, expanded audience panels and footer rule. |
| Aubergine ink | `#2a222b` | `--color-ink` | text, background, action | Default text, primary actions, dark chapters and footer. |
| Closing charcoal | `#262028` | `--color-closing` | background | Atmospheric final promise. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Add-on wash | `#f7edfc` | `--color-pricing-tint` | surface | Large pale add-on panels. |
| pricing pages | Recommended orchid | `#a057bb` | `--color-recommended-edge` | border | Single highlighted plan outline. |
| integration landing pages | Bright lilac label | `#c98fe6` | `--color-integration-label` | text | Uppercase labels above integration demonstrations. |

## Typography

- **Twklausanne** — Grotesk headings, body, actions and labels. Open, light contemporary grotesk with a friendly rather than mechanical rhythm. If unavailable, use **Inter**. Use 350–600; keep light headings and tune line breaks to the original width. Font stack: "Twklausanne", "Inter", Arial, sans-serif.
- **Tobias** — Opening promises, editorial chapter titles, quotations, outcome stories and commercial numerals. Fine high-contrast serif with expressive curves and sharply drawn details. If unavailable, use **Instrument Serif**. Use regular; tune width before changing the tight tracking. Font stack: "Tobias", "Instrument Serif", Georgia, 'Times New Roman', serif.
- **Apercumonopro** — Prompt text and gallery taxonomy. Small utilitarian monospace that reads as a prompt or category marking. If unavailable, use **IBM Plex Mono**. Font stack: "Apercumonopro", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Tobias | 400 | 72px | 1 | -2px, features "clig", "liga", "ss01", "ss11" | Default opening and atmospheric closing statement. |
| editorial-heading | Tobias | 400 | 64px | 1.1 | -2px, features "clig", "liga", "ss01", "ss11" | Centered chapter transitions and closing calls on secondary page types. |
| story-heading | Tobias | 400 | 56px | 1 | -0.03125em, features "clig", "liga", "ss01", "ss11" | Expanded outcome story card. |
| heading | Twklausanne | 350 | 48px | 1.1 | normal, features "clig", "liga", "ss01", "ss11" | Default feature and gallery headings. |
| quote | Tobias | 400 | 36px | 1.15 | normal, features "clig", "liga", "ss01", "ss11" | Standalone customer quotation. |
| card-heading | Twklausanne | 500 | 24px | 1.15 | -0.01em, features "clig", "liga", "ss01", "ss11" | Feature-strip titles and people names. |
| question | Twklausanne | 500 | 24px | 1.15 | normal, features "clig", "liga", "ss01", "ss11" | Accordion questions and commercial panel titles. |
| lead | Twklausanne | 400 | 20px | 1.3 | normal | Hero support and feature introductions. |
| body | Twklausanne | 400 | 16px | 1.3 | normal | Feature details, navigation and footer links. |
| action | Twklausanne | 500 | 16px | 1.3 | normal | Default main conversion label. |
| compact-action | Twklausanne | 500 | 16px | 1 | normal | Navigation and standard secondary action labels. |
| footer-heading | Twklausanne | 700 | 16px | 1 | normal, uppercase, features "clig", "liga", "ss01", "ss11" | Footer column names. |
| eyebrow | Twklausanne | 600 | 14px | 1.2 | normal, uppercase | Small colored label above a chapter. |
| prompt | Apercumonopro | 400 | 14px | 1.486 | normal | Single-line natural-language prompt inside the Prompt bar. |
| category | Apercumonopro | 400 | 10.5px | 1.98 | 0.1em | Short uppercase taxonomy beneath a gallery title. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quantified research or performance proof | stat | Tobias | 400 | 112px | 1 | normal | Multipliers with their suffix on the same baseline. |
| pricing pages | pricing-display | Tobias | 400 | 80px | 1 | -1px, features "clig", "liga", "ss01", "ss11" | Short pricing-page opening title. |
| integration landing pages | split-display | Tobias | 400 | 64px | 1.06 | -1px, features "clig", "liga", "ss01", "ss11" | Left-aligned title in a half-photo, half-text opening. |
| integration landing pages | integration-heading | Twklausanne | 350 | 48px | 1.1 | -1px, features "clig", "liga", "ss01", "ss11" | More tightly tracked demonstration headings. |
| pricing pages | price | Tobias | 400 | 36px | 1.1 | normal | Price and currency, with smaller sans billing interval. |
| integration setup instructions | step-heading | Tobias | 500 | 30px | 1.1 | -0.01em, features "clig", "liga", "ss01", "ss11" | Short numbered setup-card title. |
| integration landing pages | integration-eyebrow | Twklausanne | 600 | 14px | 1.2 | 0.05em, uppercase | Bright lilac overlines in integration explanations. |

**Notes:**

- Use the fine serif for the promise and proof; use the light grotesk to explain the product. Do not make every section headline serif.
- Display tracking is tight while body tracking remains normal. Keep the entire changing phrase, including its underline, in the same display recipe.
- The sans families have separate named cuts: heading uses the 350 cut, title and action use the 500 cut, and eyebrow uses the 600 cut.
- No viewport-relative type formula is established; the desktop recipes are the starting scale.

## Layout

**Density:** Airy editorial sections around compact interface details; most major bands have 80px vertical padding, with deeper pauses around the opening and final statement.

### Spacing

**Spacing system:**

- **layout step** 8px — Main 16px, 24px, 32px, 48px, 64px and 80px spacing tokens; 20px is a separate declared spacer.

| Value | Use |
| --- | --- |
| 8px | Title-to-detail and small inline gaps. |
| 16px | Icon-to-copy and compact stacked text gaps. |
| 20px | Commercial text groups and gallery-card side padding. |
| 24px | Main button horizontal padding, card padding and gallery gutters. |
| 26px | Opening headline, support and action spacing. |
| 32px | Main grids and eyebrow-to-content spacing. |
| 48px | Desktop outer gutters and media-to-feature-strip spacing. |
| 64px | Large heading-to-grid separation in integration sections. |
| 80px | Standard major section vertical padding. |
| 112px | Expanded integration sections and selected section endings. |
| 120px | Roomier product chapters. |
| 180px | Top breathing room of the atmospheric final statement. |

### Containers and grids

- **wide container**: max width 1536px · side padding 48px. Desktop shell for navigation, footer, wide media and commercial layouts. At 1440px the usable width is 1344px.
- **editorial container**: max width 1280px · side padding 48px. Inset text/media chapters; content is roughly 1104px wide at the desktop reference.
- **opening copy**: max width 1000px · side padding 24px. Centered display, with support limited to 640px.
- **feature strip**: 3 columns · gap 32px. Three unboxed icon-and-copy groups beneath the main product scene.
- **gallery**: 3 columns · gap 24px. Two rows of colorful visual cards, approximately 416px wide.
- **footer grid**: 5 columns · gap 32px. Five left-aligned columns with unequal content lengths.
- **plan grid** (only for pricing pages): 4 columns · gap 16px. Equal-width 324px plan cards.
- **integration container** (only for integration landing pages): max width 1216px · side padding 40px. More compact explanation and setup stage.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons and commercial cards | 12px |
|  | button hover | 16px |
|  | gallery cards | 18px |
|  | story and logo tiles | 24px |
|  | opening product scenes | 26px |
|  | integration enclosure | 80px |
|  | prompt bar | 9999px (pill) |
|  | glowing icon frame | 8px |
| integration demonstrations | demonstration stage | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | foreground product | `0px 44px 90px -42px rgba(42, 34, 43, 0.38)` | Foreground scene in the layered opening. |
|  | prompt float | `0px 20px 44px -26px rgba(42, 34, 43, 0.3)` | Prompt bar above the gallery. |
|  | icon glow | `0px 0px 15px 0px #a25fba` | Thin luminous icon housings. |
| pricing pages | recommended plan | `0px 16px 40px 0px rgba(42, 34, 43, 0.08)` | Only the emphasized commercial plan. |

### Surfaces

#### Porcelain canvas · level 0

**Use:** Default marketing backdrop.

**CSS:** `background: #faf9fb; color: #2a222b`

**Transfer:** Let the product scenes carry color instead of coloring every section.

#### Aubergine chapter · level 0

**Use:** Deep product chapters and shared footer.

**CSS:** `background: #2a222b; color: #faf9fb`

**Observed:** A flat warm near-black, not cool navy; light actions and pale orchid labels reverse the hierarchy.

**Transfer:** Use as a meaningful change in narrative depth.

#### Soft band · level 0

**Use:** Secondary editorial grouping.

**CSS:** `background: #f5f3f6`

**Transfer:** Use a small tonal shift rather than a colored block.

#### Closing glow · level 0

**Use:** Signature final promise.

**CSS:** `background-color: #262028; background-image: radial-gradient(55% 42% at 50% 0%, rgba(148, 84, 171, 0.38), rgba(38, 32, 40, 0) 72%); padding: 180px 24px 150px; color: #faf9fb`

**Observed:** The light is confined to the top center and fades into charcoal below the headline.

**Transfer:** Keep the glow soft; exact stops are less important than the top-lit silhouette.

#### Integration enclosure · level 1

**Use:** Logo marquee inside the light page.

**CSS:** `background: #ffffff; border-radius: 80px; padding: 80px 0px`

**Observed:** A very broad rounded white island, inset from the page edges.

**Transfer:** Use one broad enclosure rather than separate large boxes for every partner.

#### Add-on wash · level 1

**Only for:** pricing pages

**Use:** Related paid extensions.

**CSS:** `background: #f7edfc; border: 1px solid #eccffa; border-radius: 12px; padding: 32px 24px`

**Observed:** Two pale panels contain smaller white option cards.

**Transfer:** Reserve this larger purple wash for commercial grouping.

#### Dark translucent proof · level 1

**Only for:** quantified research or performance proof

**Use:** Quantified proof panels.

**CSS:** `background: rgba(36, 25, 37, 0.45); border-radius: 12px; padding: 40px 32px`

**Observed:** Three recessed dark panels use a fine illuminated edge and a purple glow behind the group; 112px serif multipliers dominate.

**Transfer:** Place a subtle 1px translucent edge around the panel and keep the caption subordinate.

#### Lit demonstration panel · level 1

**Only for:** integration demonstrations

**Use:** Active prompts and setup cards.

**CSS:** `background-color: rgba(255, 255, 255, 0.03); border: 1px solid rgba(255, 255, 255, 0.35); border-radius: 16px; padding: 24px`

**Observed:** A cropped purple light sweep brightens the upper edge while most of the panel remains dark. Inactive prompts have a weaker edge and less light.

**Transfer:** Add the Light sweep artwork behind real text; do not blur the text itself.

## Components

### Navigation

**Use:** Persistent orientation above the main story.

**CSS:** `display: flex; align-items: center; gap: 32px; padding: 0px 48px; height: 88px; max-width: 1536px; background: #faf9fb`

**Text style:** `body` — Twklausanne 400 · 16px/1.3

**Observed:** Logo left, three compact dropdown groups and a plain pricing link; login, outlined sales action and filled signup sit to the right. A separate 72px dark announcement band precedes it. The navigation remains at the top while scrolling.

**Transfer:** Use a short product logo and few category links; keep conversion controls separated from exploration.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #2a222b; color: #faf9fb; border-radius: 12px; padding: 8px 24px; height: 48px`

**Text style:** `action` — Twklausanne 500 · 16px/1.3

**Observed:** Text-only centered action; the main opening uses a single action. A 40px navigation variant has 20px horizontal padding. On dark chapters, reverse the fill to porcelain and text to ink.

**States:** Declared: hover background #564b58 and border-radius 16px; focus-visible not established for this variant; active outline 0px.

**Transfer:** Use one direct verb and a short risk-reducing qualifier where truthful.

### Secondary button

**Use:** Sales, exploration and alternate actions.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #faf9fb; color: #2a222b; border: 1px solid #2a222b; border-radius: 12px; padding: 8px 20px; height: 40px; gap: 8px`

**Text style:** `compact-action` — Twklausanne 500 · 16px/1

**Observed:** The default is the compact navigation outline; section versions grow to 48px with 24px side padding. Dark hero alternate actions invert the outline and text.

**States:** Declared: hover background #eeecee and border-radius calc(.75rem * 1.33); focus-visible not established for this variant; active outline 0px.

### Feature strip item

**Use:** Small capability explanations below a staged scene.

**CSS:** `display: flex; gap: 16px; position: relative`

**Text style:** `card-heading` — Twklausanne 500 · 24px/1.15 · tracking -0.01em

**Observed:** A 44px glowing icon frame sits at the left. Text contains a title, an 8px gap and body copy; three items share a row, without card backgrounds.

**Transfer:** Give each item one concrete capability and two to four lines of explanation.

### Gallery card

**Use:** Examples that demonstrate the variety of possible outcomes.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid #e5e1e5; border-radius: 18px; overflow: hidden`

**Text style:** `body` — Twklausanne 400 · 16px/1.3

**Observed:** Colorful 414×184px artwork sits above a white caption area with a 16px title and tiny tracked mono category; the whole card is clickable. Caption padding is 16px 20px 18px.

**States:** Declared: hover translateY(-4px) and box-shadow rgba(42, 34, 43, 0.35) 0px 22px 44px -26px; focus-visible not established; active outline 0px.

**Transfer:** Create genuinely different thumbnail compositions instead of recoloring one repeated layout.

### Prompt bar

**Use:** Natural-language input motif before the gallery.

**CSS:** `display: flex; align-items: center; gap: 14px; width: 640px; background: #ffffff; border: 1px solid #e5e1e5; border-radius: 9999px; padding: 13px 24px; box-shadow: 0px 20px 44px -26px rgba(42, 34, 43, 0.3)`

**Text style:** `prompt` — Apercumonopro 400 · 14px/1.486

**Observed:** One short colored category tag precedes a single-line monospace prompt. The overall bar is approximately 59px high.

**Transfer:** Use a plausible instruction a customer would actually type, not placeholder UI jargon.

### Outcome story card

**Use:** Editorial customer proof in an asymmetric slider.

**CSS:** `background: #eeecee; border-radius: 24px; overflow: hidden; margin-right: 32px`

**Text style:** `story-heading` — Tobias 400 · 56px/1 · tracking -0.03125em

**Observed:** A black customer mark sits above a large serif outcome. The active card is 699×480px with 40px vertical and 32px horizontal content padding; neighboring cards are 459px wide with 28px serif text. Soft lilac light touches the top. Pagination dots and an outlined story-index action follow.

**Transfer:** Keep the main result readable as a complete story; a single factual sentence can replace unavailable case-study media.

### Logo tile

**Use:** Partner or customer marks inside a moving proof band.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #faf9fb; border-radius: 24px; padding: 16px 32px; width: 200px; height: 80px`

**Observed:** Black marks are centered at consistent optical scale. Two offset horizontal tracks are clipped by the Integration enclosure; their gutters are 16px.

**Transfer:** Use supported integrations or verified customer marks, with restrained monochrome treatment.

### FAQ row

**Use:** Objection handling near the final conversion.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 32px 48px; border-radius: 24px`

**Text style:** `question` — Twklausanne 500 · 24px/1.15

**Observed:** A broad button with a small right chevron sits inside a hairline-separated list about 1115px wide. The first answer is open, set in 20px lead text; the list stays on the porcelain canvas.

**Transfer:** Keep the question short and answer in direct prose rather than a dense feature list.

### Footer columns

**Use:** Shared site ending after the final promise.

**CSS:** `display: grid; grid-template-columns: repeat(5, 1fr); gap: 32px; color: #faf9fb`

**Text style:** `footer-heading` — Twklausanne 700 · 16px/1 · uppercase

**Observed:** Uppercase column titles precede 16px links by 32px. Links stack with 16px gaps, some with small dropdown chevrons. Social glyphs sit under the company column. A full-width muted rule separates the small legal links and right-aligned copyright.

**Transfer:** Preserve the broad dark base and left alignment rather than centering the footer into a small pile.

### Plan card

**Only for:** pricing pages

**Use:** At-a-glance commercial choice.

**CSS:** `display: flex; flex-direction: column; gap: 32px; background: #ffffff; border: 1px solid #e5e1e5; border-radius: 12px; padding: 48px 24px 24px`

**Text style:** `question` — Twklausanne 500 · 24px/1.15

**Observed:** Four equal cards align title, short muted description, serif price, billing detail and dark CTA. Inclusions use checkmarks and thin horizontal rules. The recommended card alone has an orchid outline, soft shadow and a small trial badge; all plan buttons remain dark.

**Transfer:** Use real tier differences and keep the comparison action pinned consistently near the bottom.

### Underline tab

**Only for:** multi-step product explanations

**Use:** Switching a staged workflow or example.

**CSS:** `display: flex; align-items: flex-end; justify-content: center; padding: 8px 0px 24px; border-bottom: 2px solid #2a222b; height: 55px`

**Text style:** `body` — Twklausanne 400 · 16px/1.3

**Observed:** Evenly distributed text tabs share a fine baseline; the active tab replaces it with a darker 2px segment. On dark chapters the active text and rule reverse to porcelain.

**States:** Declared: hover color #2a222b; focus-visible and active behavior not established.

**Transfer:** Use a short noun phrase or numbered verb; the associated media must change with the selection.

## Imagery and graphics

### Overlapping experience fan

**Use:** Signature opening object beneath the promise.

**Observed:** A crisp central product experience combines a close human video portrait and a dark conversational panel. Broad neighboring scenes tilt and overlap behind it, becoming smaller, less saturated and more transparent toward the edges. The fan spans beyond the viewport and is clipped; it is much wider than the text.

**Transfer:** Pair your product's input with a human or outcome image. If no interface is available, build a believable two-part card showing a person and a short interaction, then create distinct neighboring use cases.

**Build:** Use five absolute-positioned panels around a 620×430px center. Apply 26px corners and a 1px rgba(42,34,43,0.1) edge. Keep the center opaque with a 0px 44px 90px -42px rgba(42,34,43,0.38) shadow; rotate side panels gently in opposing directions, lower their saturation to 0.75 and opacity to 0.38, then 0.12. Clip the fan at the viewport edges.

### Floating conversational scene

**Use:** Signature product demonstrations in light and dark chapters.

**Observed:** A roughly 629×440px rounded stage contains an angled form or workflow panel with a human photo/video alongside text. Small translucent outcome cards float in front and behind. Light versions use a pearly gray stage with pale lilac illumination; dark versions use aubergine and vivid purple light behind the cards.

**Transfer:** Show one meaningful input and its consequence. The minimum version is a readable interface plane, a human image and two smaller result chips, not a full application screen.

**Build:** Create a rounded stage, center a slightly perspective-rotated two-column panel, then overlap two smaller 12px-radius cards at opposing corners. Add an elliptical rgba(185,109,213,0.35) light layer behind the main plane, blur about 40px, and use thin translucent white edges on the floating cards. Keep light away from body text.

### Luminous icon housing

**Use:** Required small signature device in feature strips.

**Observed:** A dark square holds a small white pictogram; a fine purple-and-white perimeter and diffuse glow separate it from either canvas.

**Transfer:** Use simple recognisable capability pictograms, retaining the lit housing rather than switching to generic flat colored circles.

**Build:** Place a 42×42px #2a222b square with 8px corners inside a 44×44px frame padded by 1px. Frame background: linear-gradient(90deg, #b96dd5, #ffffff 50%, #b96dd5); add 0px 0px 15px #a25fba. Center a 24px icon.

### Colorful example artwork

**Use:** Gallery thumbnails.

**Observed:** Each thumbnail is a miniature designed experience: olive product choices, peach survey with a pendant lamp, coral registration, lilac analytics, cream bicycle photography and yellow sketch-like feedback. Strong type, photos and small controls are composed into distinct color worlds.

**Transfer:** Use a similarly varied set of art-directed outputs for your own product. Keep the saturated color inside thumbnails rather than extending it across the page.

### Human-use photography

**Use:** A person experiencing the product rather than abstract software alone.

**Observed:** Warm domestic or working settings, often close to a laptop on a colored couch. A square 541px image balances a compact text column; integration openings instead use an edge-to-edge half-width photo with translucent chat over it.

**Transfer:** Photograph a believable user context with warm light and a visible meaningful interaction. Retain rich local color without applying a purple filter to every photo.

### Light sweep

**Only for:** dark performance proof and integration demonstrations

**Use:** Purple-lit proof, prompts and setup panels.

**Observed:** Blurred orchid ribbons skim across the top of dark translucent panels; their centers stay readable. Proof cards use a group-level glow while integration cards have individual cropped sweeps.

**Transfer:** Recreate a restrained luminous curve without requiring complex rendered artwork.

**Build:** Behind the cards, draw an SVG elliptical arc with a broad rgba(185,109,213,0.55) stroke, blur it 24–40px, and place it partly outside the top edge. Layer a smaller rgba(255,255,255,0.12) highlight above it; clip individual card sweeps to 16px or 20px corners. Leave the bottom half mostly aubergine.

### People grid

**Only for:** company and team pages

**Use:** Leadership or team introduction.

**Observed:** Three-column square portraits, approximately 427px each, with soft rounded corners, natural backgrounds, 24px names and 16px role captions on a pale gray band.

**Transfer:** Use consistent portrait framing but preserve natural individual settings.

### Die-cut culture collage

**Only for:** company and recruiting pages

**Use:** Recruitment or culture story illustration.

**Observed:** A 541px square lilac field holds overlapping green, orchid, red and mustard stickers with thick white cut edges. Shapes include a flower, a rounded banner and a bent ribbon; small uppercase statements rotate with their shapes.

**Transfer:** Create a tactile collage of your own short principles; minimum quality is clean vector die-cuts with deliberate overlaps and readable rotated labels.

**Build:** Use an SVG square with 24px corners. Arrange four oversized rounded or scalloped silhouettes crossing its edges; apply thick white outlines, slight rotations and a shallow drop shadow. Put short white uppercase phrases inside each silhouette and clip the collage to the square.

### Icons

**Observed:** Navigation chevrons are compact filled 16px glyphs. Feature pictograms are white 24px line-like marks inside glowing dark housings. Pricing uses small checkmarks and circled information symbols; the footer uses solid monochrome social glyphs.

**Transfer:** Keep utility symbols small and monochrome. Reserve luminous housings for capabilities, not every arrow or metadata item.

## Section recipes

How recurring sections are built.

### First screen: Conversational product stage

**Observed:** A 72px dark announcement band and 88px porcelain Navigation sit above a centered light opening. The headline begins after about 52px of breathing room and occupies roughly half the viewport width in two lines: a verb and purple underlined object above a dark concluding line. Use display, then a centered 640px-wide lead separated by 26px, then a single Primary button another 26px below. Below the action, the Overlapping experience fan fills the lower half of the first screen: its center is crisp and forward, sides faded and tilted. Within the first 900px the entire headline, two-line support, action and upper majority of the main object are visible; the fan's lower edge and next feature chapter continue below. Layers run porcelain → receding scenes → foreground interaction, with the copy clearly above the media.

**Transfer:** Lead with the result a reader can create and highlight its changeable object. Stage a human interaction or input-to-outcome card if no finished product media exists. A research-oriented product can instead open on aubergine with centered display and two actions above a wide demo; integration launches can use split-display beside a half-width human photo. Commercial pages open with pricing-display and plan cards, and company pages with a short display plus a broad colorful product collage.

**Avoid:** Do not replace the fan with a tiny dashboard thumbnail beside the headline, or let a decorative glow compete with the text. The opening is not an all-purple gradient hero.

**Text style:** `display` — Tobias 400 · 72px/1 · tracking -2px

### Text and staged capability

**Observed:** An inset two-column chapter pairs a roughly 442px copy group with a 629×440px Floating conversational scene. Eyebrow precedes heading, lead and action, with 16px and 32px internal intervals. A Feature strip item row follows the scene by 48px. Alternating chapters swap media and copy sides; dark variants use the Aubergine chapter and reversed actions.

**Transfer:** Explain one job in the large pair, then support it with three distinct capabilities rather than three duplicate summaries.

**Text style:** `heading` — Twklausanne 350 · 48px/1.1

### Prompt and example gallery

**Observed:** Centered heading and short lead introduce a Prompt bar. A three-column, 24px-gap Gallery card grid follows; colorful artwork occupies most of each card and quiet captions sit below. A plain underlined catalog link concludes the grouping.

**Transfer:** Show a range of finished outcomes and a natural-language way to start one.

**Text style:** `heading` — Twklausanne 350 · 48px/1.1

### Editorial testimonial pause

**Observed:** An unboxed centered quote spans an inset 1115px measure on porcelain, with 80px vertical padding. A small circular portrait and two-line name/role attribution sit underneath. The quotation uses quote rather than the large display scale.

**Transfer:** Let a specific customer observation interrupt the feature cadence; use one verified quote without surrounding it with a dense card.

**Text style:** `quote` — Tobias 400 · 36px/1.15

### Moving ecosystem island

**Observed:** Integration enclosure holds a centered 36px sans title, two staggered rows of Logo tile components and a centered outlined action. The tracks extend beyond the visible enclosure and run in opposite directions.

**Transfer:** Show genuine compatibility or customers as an ecosystem, with consistent monochrome logos and broad rounded framing.

### Editorial outcome carousel

**Observed:** Outcome story card components sit in a horizontal track with an expanded lead card and smaller neighbors visible beyond the right edge. Six small dots center below, followed by a bordered index action after 48px.

**Transfer:** Use asymmetry to privilege the current story; keep the customer result, not decorative art, as the content.

### Objections and final invitation

**Observed:** Where questions need answering, a porcelain FAQ row list sits before the close, with its first answer expanded. The default close is Closing glow: a two-line display constrained to 960px, one light Primary button 48px beneath it, then Footer columns. Other product pages use a 64px centered statement with 20px support and a 36–44px action gap; commercial and integration variants use a light close whose lower corners curve by 80px into the dark footer.

**Transfer:** Restate the broad outcome rather than adding new features. Keep the atmospheric final promise and deep footer even when the page does not need an FAQ.

**Text style:** `display` — Tobias 400 · 72px/1 · tracking -2px

### Quantified luminous proof

**Only for:** research or performance-led product pages

**Observed:** Three 427×233px Dark translucent proof panels share a 32px gap. Large serif multipliers sit left aligned above 20px short captions; a diffuse purple sweep crosses behind the group.

**Transfer:** Use a small set of independently defensible metrics. Keep suffixes on the number baseline and descriptions outside the oversized type.

**Text style:** `stat` — Tobias 400 · 112px/1

### Demonstration and setup

**Only for:** integration landing pages

**Observed:** A centered integration-heading introduces a 5:7 split of prompt choices and a large demonstration stage, separated by 24px. Below, horizontal prompt cards offer more examples. A light three-column benefits chapter leads into dark setup instructions: a pill-like tool selector, three lit cards with step labels and 30px serif titles, then a white action.

**Transfer:** Turn technical connectivity into concrete commands, then show the shortest real setup path.

**Text style:** `integration-heading` — Twklausanne 350 · 48px/1.1 · tracking -1px

### Commercial comparison

**Only for:** pricing pages

**Observed:** A short centered pricing-display leads to monthly/yearly controls, a compact enterprise strip and four Plan card components. An inset dark enterprise panel uses six small bordered benefits; two Add-on wash panels follow. A broad white comparison matrix groups 16px labels and centered checks into approximately 97px rows, with 1px rules and a persistent compact plan-selection row.

**Transfer:** Separate fast plan selection from exhaustive comparison. Keep a feature-label column wider than each plan column and maintain billing/action context through the long matrix.

**Text style:** `pricing-display` — Tobias 400 · 80px/1 · tracking -1px

### Company story and recruiting

**Only for:** company and recruiting pages

**Observed:** A centered display and short lead sit above a 1344px-wide colorful product collage. A quiet logo strip leads to a square human-use photo with mission copy. A Soft band holds a three-column People grid, followed by a text-and-Die-cut culture collage pair.

**Transfer:** Describe the company's point of view through people, product use and one playful physical-feeling graphic, not an abstract manifesto alone.

## Page flow

**Storyline:** Conversational promise → tangible interaction → capabilities and examples → proof → deeper product possibilities → objections where needed → broad final invitation and dark resource base.

### Broad product landing page

1. **Promise** — Centered changing-object headline and layered product fan.
2. **Product demonstration** — Text/media chapter and unboxed three-part capability strip.
3. **Examples** — Prompt motif above a colorful gallery.
4. **Social proof** — Editorial quotation, moving ecosystem marks and asymmetric customer stories.
5. **Capability chapters** — A dark transition line opens deeper workflow scenes.
6. **Closing call** — Purple top-lit serif promise, light action and five-column dark footer.

**Transfer:** Use this as the default visual language, changing the quantity and order of proof and capability blocks to fit the product.

### Focused product with a consultative conversion

1. **Promise** — Dark centered serif opening and wide demonstration.
2. **Process explanation** — Numbered underline tabs select a media/copy pair.
3. **Product proof** — Light example reports and category tabs.
4. **Audience relevance** — Dark expandable audience panels beside a large scene.
5. **Quantified proof** — Three luminous multiplier cards.
6. **Objection handling** — Light accordion with first answer open.
7. **Closing call** — Dark centered statement, demo action and shared dark footer.

**Transfer:** Use when a complex workflow needs explanation and a guided sale rather than immediate self-service.

### Commercial evaluation and plan selection

1. **Pricing** — Short serif title, billing selector and four aligned plan cards.
2. **Commercial alternatives** — Dark enterprise panel and pale orchid add-ons.
3. **Detailed comparison** — Grouped ruled matrix with persistent compact plan actions.
4. **Social proof** — Customer logos and large unboxed quotation.
5. **Objection handling** — Broad FAQ accordion.
6. **Closing call** — Light serif invitation with dark action, rounded transition and shared footer.

**Transfer:** Keep the expressive typography but let the information system become denser and more regular.

### Integration launch that makes technical capability approachable

1. **Promise** — Full-height half-photo opening with a left-aligned serif title on dark.
2. **Explanation** — Light text paired with a vivid connector scene.
3. **Product demonstration** — Dark prompt selections and chat-like result panel.
4. **Capability examples** — Horizontal glowing prompt cards.
5. **Trust and control** — Three light benefits with close interface details.
6. **Setup** — Tool tabs and three purple-lit numbered instruction cards.
7. **Objection handling** — Light FAQ.
8. **Closing call** — Light centered invitation, curved lower edge and shared footer.

**Transfer:** Use real commands and clear permission language; keep the richer glow treatment confined to demonstration areas.

### Company introduction with a recruiting branch

1. **Identity** — Centered serif title and broad colorful product collage.
2. **Credibility** — Quiet customer-mark strip.
3. **Point of view** — Human-use photo paired with mission prose.
4. **People** — Three-column portrait grid on a soft band.
5. **Recruiting** — Short invitation beside oversized die-cut graphics.
6. **Closing call** — Dark outcome statement with signup and comparison actions, followed by the shared footer.

**Transfer:** Keep the product present in company storytelling, with personality carried by portraits and tactile illustration.

## Writing

Warm, capable and brisk. It explains advanced software through everyday actions and conversational outcomes, then supports confidence with concrete results rather than grandiose technical language.

**Do not copy:** Do not reuse Typeform names, logos, artwork, customer identities, quotations, numerical claims or commercial terms. Replace them with the new product's own supported facts and original examples. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we sparingly for a company point of view. Refer to the product directly when explaining what it does.
- **Rhythm:** Short verb-led headlines, one or two compact supporting sentences, then a clear action. Longer explanations break into concrete clauses; fragments and a brief final word can add pace. Em dashes and conversational turns are welcome; exclamation marks are rare.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An action and changeable object followed by an easy starting condition. | About 8–14 words | “at the drop of a prompt” |
| Capability heading | Simple verb plus expansive outcome, or a before-to-after transformation. | 2–7 words | “Capture anything”<br>“From scores to action”<br>“Don't just ask. Take action.” |
| Supporting line | Name concrete tasks and the useful consequence rather than describing the technology in isolation. | About 15–40 words | “Collect CSAT, NPS, and pulse surveys that turn scores into action, automatically.” |
| Primary action | Direct verb, destination or truthful reduction of risk. | 2–6 words | “Get started — it's free”<br>“Request a demo”<br>“Connect now” |
| Instruction | Specific location and exact next action; no ceremonial introduction. | One compact sentence | “In Claude, go to Customize → Connectors.” |
| Closing line | Broaden the product action into the start of an ongoing benefit. | 6–12 words | “The form is just the beginning”<br>“When the form ends, the flow begins...” |

**Words and phrasing to use:** start; build; collect; connect; act; your; in seconds; from … to …; all without; no code required

**Avoid:** revolutionary paradigm; unprecedented synergy; leverage our cutting-edge solution; next-generation ecosystem; effortlessly transform everything

**Rules:**

- Introduce the job before naming the mechanism.
- Attach a concrete object to a verb: create a study, connect a tool, send a follow-up.
- Use numbers only when they have a defensible meaning.
- Explain AI as useful work done with the reader's context and permission.
- Write example prompts as things a real user would ask, with a task, object and destination.

## Do's and Don'ts

### Do

- Keep the opening serif at 72px/1 with -2px tracking and a purple underlined object.
- Use 48px light sans headings for normal feature chapters.
- Keep main actions at 48px high with 12px corners; let hover soften them toward 16px.
- Use 32px feature-strip gutters and 24px gallery gutters.
- Pair a product interaction with a real human image and small outcome panels.
- Keep the dark chapter warm aubergine and its text porcelain.
- Give proof editorial presence with a 36px serif quote or a 56px outcome headline.
- Preserve the broad final statement and five-column dark resource base.

### Don't

- Do not turn all CTAs into purple pills; dark 12px-radius rectangles are the default.
- Do not make the 48px feature headings heavy or tightly tracked like the display serif.
- Do not spread colorful gallery palettes into every surrounding section.
- Do not apply bright purple glows behind all body copy; keep light localized to scenes, edges and the final promise.
- Do not put the three capability explanations into bulky filled cards; their normal construction is unboxed.
- Do not make every outcome card equal width when using the editorial carousel; one expanded story is the point.
- Do not put mono text into ordinary paragraphs; it belongs to prompt and taxonomy details.
- Do not give every commercial tier an accent outline and shadow; only the emphasized plan receives them.

## Motion and responsive

### Motion

**Observed:**

- Declared action transition: background-color 0.2s and border-radius 0.3s ease-out.
- Declared footer-link motion uses transform 0.3s ease-out; hover shifts selected links by 8px.
- Declared marquee and reverse-marquee loops run for 90s linearly.
- Declared layered-scene fadeInOut loops run for 20s with cubic-bezier(0.33, 1, 0.68, 1).
- Gallery hover raises cards by 4px; integration prompt panels declare background-color and border-color transitions of 0.25s.

**Transfer:**

- Keep the ecosystem tracks slow and opposing; do not make them a fast ticker.
- Confine card lifting to clickable gallery items and corner-softening to actions.
- Use changing headline objects and staged scene rotation as a paired product-story device, retaining a readable resting state.

**Unknown:**

- Exact synchronization of the headline and product scenes, full keyframe transforms and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Styles declare major width boundaries around 767–768px, 991–992px and 1023–1024px, with additional component-specific boundaries.
- The example-report section has a mobile-and-landscape hiding wrapper.

**Transfer:**

- On narrow layouts, keep the main interaction scene crisp and centered while clipping or suppressing receding fan panels; do not shrink all five into illegibility.
- Stack text/media pairs and feature strips, preserving the serif-versus-grotesk hierarchy.
- Let commercial comparison remain scrollable with readable labels rather than compressing the table into tiny type.

**Unknown:**

- Exact mobile typography, gutters, navigation expansion, table behavior and alternate report experience are not established; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
