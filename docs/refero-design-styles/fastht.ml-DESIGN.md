# FastHTML — candy blocks, serious tools

## Overview

A playful technical style pairs oversized, matter-of-fact grotesk headlines with candy-colored architectural blocks. Pale gray openings give way to plum, yellow, green, violet and pink chapters, with soft inset cards and tactile pill controls. Flat vector symbols and live demonstrations make it especially suited to developer tools and approachable technical products; a denser white editorial variant supports longer explanations.

### Essentials

- Plainspoken headlines have billboard scale without heavy weight: Geist 72px/88px at 500 with -0.015em tracking, followed by 60px/1.1 section leads.
- The opening is a centered clearing inside a toy-like field: a 768px headline, 640px support line and paired 350×76px pills sit among edge-clipped rounded vector shapes on #f3f3f3.
- Chapters feel like overlapping sheets of colored rubber: full-width solid fills, 40px upper corners and 40–64px overlaps. Saturated color occupies most of the long marketing page, not just its buttons.
- Controls look gently pressable rather than flat: black and white 9999px pills use inset highlights and short dark drop shadows; ordinary navigation actions are 40px high.
- Graphics stay blunt and friendly: rounded blocks, capsules and large cutout symbols use the chapter palette. Repeat this graphic language in a monumental closing wordmark over colored shapes; use a new product name as vector lettering when no artwork exists.
- Technical credibility has its own voice: Geist Mono 16px/1.8 at 500 labels chapters and links, while demonstrations pair readable code with a working visual result rather than glossy device mockups.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bright green | `#3cdd8c` | `--color-green` | background, accent | Large capability chapter, geometric artwork and editorial navigation. |
| Deep plum | `#3a2234` | `--color-plum` | background | Demonstration stage with reversed text. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden yellow | `#ffc435` | `--color-yellow` | background, accent | Benefit chapter and geometric artwork. |
| Violet | `#7575f0` | `--color-violet` | background | Question-and-answer chapter. |
| Orchid pink | `#e699d9` | `--color-pink` | background, accent | Social-proof chapter and geometric artwork. |
| Pale cream | `#ffeecc` | `--color-cream-card` | surface | Benefit cards on yellow. |
| Pale rose | `#ffccf7` | `--color-rose-card` | surface | Quote cards on pink. |
| Pale mint | `#d4f7e6` | `--color-mint-card` | surface | Stacking capability cards on green. |
| Pale lavender | `#e8e8fc` | `--color-lavender-card` | surface, accent | Question panels and pale geometric capsules. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Headings, dark pills and closing canvas. Body copy also uses this at 80% opacity; secondary chip labels use 60%. |
| Soft gray | `#f3f3f3` | `--color-canvas` | background | Opening and sample-gallery canvas. |
| Frosted mint | `#eefcf5` | `--color-chip-wash` | surface | Visible white at 60% over pale mint in integration chips. |
| White | `#ffffff` | `--color-white` | text, surface, border | Light action fills and reversed text. White at 80% makes footer copy; 50% with a 20% white edge makes navigation glass. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial information pages | Link blue | `#2563eb` | `--color-article-blue` | link, border, action | Underlined prose links, quote rules and active section navigation. |
| editorial information pages | Yellow highlighter | `#fbe06b` | `--color-article-yellow` | background | Visible 70% yellow over white for chapter bars; source hue is yellow at rgba(250,204,21,0.7). |
| editorial information pages | Teal highlighter | `#6ce1d2` | `--color-article-teal` | background | Visible 70% teal over white for chapter bars, using rgba(45,212,191,0.7). |
| editorial information pages | Pink highlighter | `#f79ccc` | `--color-article-pink` | background | Visible 70% pink over white for chapter bars, using rgba(244,114,182,0.7). |
| editorial information pages | Blue-black | `#020817` | `--color-article-ink` | text | Long-form text and navigation. |
| editorial information pages | Slate gray | `#6b7280` | `--color-article-muted` | text | Figure captions and restrained footer links. |
| editorial information pages | Light gray edge | `#e5e7eb` | `--color-article-edge` | border | Figure borders and footer separator. |

## Typography

- **Geist** — All marketing headlines, paragraphs and controls. Clean contemporary grotesk; medium-weight headlines and regular body text. OpenType features: "clig" 0, "liga" 0. Font stack: "Geist", sans-serif.
- **Geist Mono** — Technical chapter labels, code and marketing footer links. Even-width technical lettering with relaxed line spacing. Font stack: "Geist Mono", monospace.
- **ui-sans-serif** (only for editorial information pages) — Long-form text, article headings and navigation. System sans with a heavier, more utilitarian hierarchy than the marketing face. Font stack: "ui-sans-serif", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Geist | 500 | 72px | 88px | -0.015em | Centered first-screen promise. |
| section-heading | Geist | 500 | 60px | 1.1 | -0.015em | Major chapter leads, centered above grids or left-aligned beside panels. |
| card-heading | Geist | 500 | 32px | 1.25 | -0.015em | Benefit and capability card titles. |
| lead | Geist | 400 | 24px | 32px | -0.01em | Section support lines, large card paragraphs and gallery labels. |
| body | Geist | 400 | 20px | 1.4 | -0.01em | Hero support, pill labels, capability copy and testimonials. |
| small | Geist | 400 | 16px | 1.5 | -0.005em | Compact navigation actions and question labels. |
| technical-label | Geist Mono | 500 | 16px | 1.8 | normal, features "clig" 0, "liga" 0 | Uppercase chapter labels and mixed-case footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial information pages | article-title | ui-sans-serif | 800 | 36px | 40px | -0.025em | Compact long-form title. |
| editorial information pages | article-heading | ui-sans-serif | 600 | 30px | 1.2 | -0.025em | Chapter heading on a colored marker bar. |
| editorial information pages | article-body | ui-sans-serif | 400 | 18px | 1.625 | normal | Explanatory paragraphs and lists. |
| editorial information pages | article-footer | ui-sans-serif | 400 | 18px | 28px | normal | Muted footer text and links. |
| editorial information pages | article-caption | ui-sans-serif | 400 | 14px | 20px | normal | Centered figure captions and small navigation labels. |

**Notes:**

- Marketing headlines use the same medium weight and -0.015em tracking across three sizes; scale, line breaks and alignment create hierarchy rather than boldness.
- Body tracking relaxes to -0.01em, and small text to -0.005em. Technical labels retain normal tracking instead of widely spaced capitals.
- Keep the long-form system-sans hierarchy separate: its 800-weight title is not the default landing-page headline.

## Layout

**Density:** Airy marketing chapters with tightly grouped controls; editorial pages are denser and paragraph-led.

### Spacing

**Spacing system:**

- **grid** 8px — Dominant layout rhythm; 4px and 12px are local control exceptions.

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and chip spacing. |
| 16px | Question-panel gaps and compact grid gutters. |
| 24px | Headline-to-support gap, opening action gap and testimonial gutter. |
| 32px | Benefit-grid gutter and quote-card padding. |
| 48px | Desktop benefit and capability card padding. |
| 64px | Desktop chapter side padding, heading-to-content space and section overlaps. |
| 96px | Standard marketing chapter bottom padding. |
| 192px | Scroll breathing room behind sticky capability cards. |

### Containers and grids

- **marketing-shell**: max width 1440px · side padding 64px. Full-width chapter surfaces with inset content; surfaces themselves remain edge-to-edge.
- **heading-group**: max width 800px · gap 24px. Centered heading stack; constrain most section headline and support text further to 512px.
- **opening-copy**: max width 768px. Centered headline with a narrower 640px support paragraph.
- **benefit-grid**: max width 1280px · 3 columns · gap 32px. Three equal cards in one desktop row.
- **capability-stack**: max width 800px · gap 32px. Single centered column of overlapping sticky cards.
- **gallery-grid**: max width 1280px · 4 columns · gap 48px. Four large square-symbol tiles with labels below.
- **split-proof**: max width 1280px · 2 columns · gap 64px. Left introduction beside a 512px question list or a horizontally clipped quote rail.
- **article-shell** (only for editorial information pages): max width 1600px · 6 columns · gap 16px · side padding 32px. One column for the section index and five for the reading area.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | chapter upper corners | 40px |
|  | benefit cards | 16px |
|  | capability and quote cards | 24px |
|  | question panels | 20px |
|  | pills | 9999px (pill) |
| editorial information pages | article figures | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | dark tactile | `inset 0px 2px 4px rgba(255,255,255,0.1), 0px 4px 8px rgba(0,0,0,0.5)` | Primary hero action and question panels. |
|  | light tactile | `0px 2px 2px rgba(255,255,255,0.5), 0px 3px 3px rgba(0,0,0,0.2)` | Video action and integration pills. |
| editorial information pages | figure lift | `0px 1px 2px rgba(0,0,0,0.05)` | Subtle white figure frame. |

### Surfaces

#### Opening canvas · level 0

**Use:** Light opening and sample-gallery field.

**CSS:** `background: #f3f3f3; color: #000000`

#### Color chapter · level 0

**Use:** Large overlapping narrative sheet.

**CSS:** `background: #ffc435; border-radius: 40px 40px 0px 0px; padding: 64px 64px 96px; margin-top: -64px`

**Observed:** Green, violet and pink change the chapter's mood without changing its construction. Plum reverses its text to white and begins with a 40px overlap.

**Transfer:** Assign one strong flat hue to a narrative chapter rather than scattering all colors among small decorations.

#### Soft inset card · level 1

**Use:** Quiet reading area on a saturated chapter.

**CSS:** `background: #ffeecc; border-radius: 16px; padding: 48px; box-shadow: none`

**Observed:** Mint capability cards use 24px corners; rose quote cards use 24px corners and 32px padding.

**Transfer:** Match a pale tint to its parent hue; reserve depth shadows for controls and question panels.

#### Demonstration stage · level 0

**Use:** Working proof with code beside a visual result.

**CSS:** `background: #3a2234; color: #ffffff; border-radius: 40px 40px 0px 0px; padding: 0px 64px 96px`

**Observed:** Code is placed directly on plum, with darker translucent filename and tab capsules; the result has its own pale backing.

**Transfer:** Retain a visible cause-and-effect pair even when the product does not use code.

#### Closing canvas · level 0

**Use:** Monumental graphic sign-off.

**CSS:** `background: #000000; border-radius: 40px 40px 0px 0px; height: 600px; padding-top: 48px; overflow: hidden`

**Observed:** A small utility row occupies the top; oversized colored shapes and lettering fill the lower field.

#### Article paper · level 0

**Only for:** editorial information pages

**Use:** Denser white reading environment.

**CSS:** `background: #ffffff; color: #020817`

**Observed:** Color is localized to a green header and marker-like chapter bars rather than full-height chapter fills.

## Components

### Floating navigation

**Use:** Persistent compact landing-page navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; max-width: 400px; height: 58px; padding: 8px 16px; background: rgba(255,255,255,0.5); border: 1px solid rgba(255,255,255,0.2); border-radius: 9999px; backdrop-filter: blur(16px)`

**Text style:** `small` — Geist 400 · 16px/1.5 · tracking -0.005em

**Observed:** Centered within a fixed header 16px below the top, with a compact logo left and a black 40px action right. Editorial navigation instead spans the inset width on green, with 24px upper corners and small text links.

### Primary button

**Use:** Main opening action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #000000; color: #ffffff; border-radius: 9999px; padding: 4px 16px; height: 76px; max-width: 350px; width: 100%; box-shadow: inset 0px 2px 4px rgba(255,255,255,0.1), 0px 4px 8px rgba(0,0,0,0.5)`

**Text style:** `body` — Geist 400 · 20px/1.4 · tracking -0.01em

**Observed:** Broad and centered beside the equally sized white video action. Smaller chapter actions and the navigation action use the small text recipe with 40px height and 8px 16px padding.

**States:** Declared: hover background rgba(0,0,0,0.8); focus-visible not specified.

### Video action

**Use:** Secondary opening action with human context.

**CSS:** `display: flex; align-items: center; gap: 16px; background: #ffffff; color: #000000; border-radius: 9999px; padding: 8px; height: 76px; max-width: 350px; width: 100%; box-shadow: 0px 2px 2px rgba(255,255,255,0.5), 0px 3px 3px rgba(0,0,0,0.2)`

**Text style:** `body` — Geist 400 · 20px/1.4 · tracking -0.01em

**Observed:** A rounded presenter thumbnail sits left, label and smaller runtime stack in the middle, and a play-service mark sits right.

**States:** Declared: hover background rgba(255,255,255,0.8); focus-visible not specified.

**Transfer:** Use a real demo still and truthful duration; keep the three-part composition.

### Benefit card

**Use:** Short practical benefit explanation.

**CSS:** `background: #ffeecc; border-radius: 16px; padding: 48px; height: 352px`

**Text style:** `card-heading` — Geist 500 · 32px/1.25 · tracking -0.015em

**Observed:** Title first, then a lead-recipe paragraph after 24px. Equal cards align in a three-column row.

**Transfer:** Give each card a distinct practical advantage and enough text to explain it, not a decorative icon.

### Stacking capability card

**Use:** Sequential capability or compatibility proof.

**CSS:** `background: #d4f7e6; border-radius: 24px; padding: 48px; max-width: 800px; min-height: 272px`

**Text style:** `card-heading` — Geist 500 · 32px/1.25 · tracking -0.015em

**Observed:** Title, body line and a wrapping integration-chip row. Cards stay centered as later cards layer over earlier ones; the foremost card stays crisp.

**Transfer:** Use a few capability families with specific supporting examples.

### Integration chip

**Use:** Named technology, partner or compatibility link.

**CSS:** `display: flex; align-items: center; gap: 8px; background: rgba(255,255,255,0.6); color: rgba(0,0,0,0.6); border-radius: 9999px; padding: 8px 16px; height: 44px; box-shadow: 0px 2px 2px rgba(255,255,255,0.5), 0px 3px 3px rgba(0,0,0,0.2)`

**Text style:** `body` — Geist 400 · 20px/1.4 · tracking -0.01em

**Observed:** A 24px logo precedes a short label; chips wrap with 8px gaps.

### Question panel

**Use:** Compact objection handling.

**CSS:** `background: #e8e8fc; color: #000000; border-radius: 20px; max-width: 512px; min-height: 72px; box-shadow: inset 0px 2px 4px rgba(255,255,255,0.1), 0px 4px 8px rgba(0,0,0,0.5)`

**Text style:** `small` — Geist 400 · 16px/1.5 · tracking -0.005em

**Observed:** The question label has 24px vertical padding, 32px left and 24px right; a small plus sits at its right edge. Longer questions create 96px panels; rows have 16px gaps.

**Transfer:** Let labels wrap and preserve the compact text size rather than enlarging the whole accordion.

### Testimonial card

**Use:** Expert or customer proof in a horizontal rail.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #ffccf7; color: #000000; border-radius: 24px; padding: 32px; width: 384px; height: 384px`

**Text style:** `body` — Geist 400 · 20px/1.4 · tracking -0.01em

**Observed:** Quote above a bottom-aligned identity row with a small circular portrait, name and mono role. Neighboring cards are partially visible; two plain arrow controls sit below.

**Transfer:** Use attributable language and retain the visual cadence of quote, portrait and technical byline.

### Footer link

**Use:** Utility and community links in the graphic closing band.

**CSS:** `display: flex; align-items: center; gap: 8px; color: rgba(255,255,255,0.8); border-bottom: 1px solid transparent`

**Text style:** `technical-label` — Geist Mono 500 · 16px/1.8

**Observed:** The text span has a 1px white-at-50% underline; an external northeast arrow follows it. Links share a row opposite the copyright.

**States:** Declared: hover color white and border-bottom-color white; focus-visible not specified.

### Article chapter bar

**Only for:** editorial information pages

**Use:** Section divider within long prose.

**CSS:** `background: rgba(250,204,21,0.7); color: #020817; border-radius: 24px 0px 0px 0px; padding: 8px 12px; margin-top: 16px; margin-bottom: 8px`

**Text style:** `article-heading` — ui-sans-serif 600 · 30px/1.2 · tracking -0.025em

**Observed:** Full reading-column width. Later chapter variants use translucent pink and teal, with the same single rounded corner.

### Article figure

**Only for:** editorial information pages

**Use:** Supporting image with explanatory caption.

**CSS:** `background: #ffffff; border: 1px solid #e5e7eb; border-radius: 8px; padding: 16px; margin: 16px; box-shadow: 0px 1px 2px rgba(0,0,0,0.05)`

**Text style:** `article-caption` — ui-sans-serif 400 · 14px/20px

**Observed:** A right-floated image lets prose wrap beside it. The caption is centered and slate gray; the larger version takes about half the reading column.

**Transfer:** Use a concrete diagram or a lightly humorous explanatory illustration, not a decorative stock photo.

### Article footer

**Only for:** editorial information pages

**Use:** Restrained long-form page ending.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); gap: 16px; color: #6b7280`

**Text style:** `article-footer` — ui-sans-serif 400 · 18px/28px

**Observed:** A thin gray separator precedes copyright left, a compact logo centered, and three utility links aligned right. No giant graphic or conversion banner follows.

## Imagery and graphics

### Rounded geometric field

**Use:** Signature opening and closing artwork.

**Observed:** Flat green, yellow, pink and pale-lavender blocks, capsules and repeated bars drift beyond the edges. The center of the opening remains clear for text. The closing version sits behind enormous lettering on black, with colored overlaps.

**Transfer:** Recreate this abstract language for any product, even without product media. Use original proportions and a new product wordmark, keeping simple shapes and edge clipping.

**Build:** Use an absolutely positioned SVG behind content: a green capsule near the upper center-left, a tall yellow rounded rectangle at upper right, a wide pink rounded rectangle upper left, a lavender capsule at mid-right and three lavender bars entering from the left. Add a green rounded block clipped at bottom right. At a 1440px canvas use major shapes roughly 240–320px across, with 40–96px corner radii; keep the central 800px text zone unobstructed. For the closing field reuse enlarged shapes behind a pale wordmark stretched across the 1312px inset width. Use an SVG exclusion-style blend or colored overlap masks to produce the blue/purple intersections rather than gradients.

### Oversized closing lettering

**Use:** Signature marketing sign-off.

**Observed:** A near-full-width vector wordmark sits at the bottom of a 600px black band; the letterforms visually intertwine with the colored geometry and approach the edges.

**Transfer:** Use original product lettering as outlined SVG. If a custom wordmark is unavailable, convert a light grotesk product name to paths and scale it to fill the lower band; the graphic sign-off remains part of the design.

**Build:** Position a 1312px-wide SVG lettering layer within 64px desktop insets, aligned to the lower edge. Put yellow, green and lavender rounded geometry behind it. Apply overlap masks to selected intersections and clip all overflow at the band boundary.

### Large sample symbols

**Use:** Gallery navigation to examples or use cases.

**Observed:** Four 268px square vector illustrations use very rounded colored backings and oversized pale cutout symbols: a four-cell grid, check, dialogue bubbles and a flower-like loop. Captions with external arrows sit underneath on gray.

**Transfer:** Give each use case one instantly readable silhouette. Maintain equal illustration scale and use the chapter palette rather than detailed interface thumbnails.

**Build:** Use a square SVG with a deeply rounded background in pink, yellow, plum or green. Center one thick, pale silhouette with softly rounded corners and generous negative space; keep symbols nearly as large as the backing. Place a 24px text label 24px below.

### Working demonstration pair

**Use:** Technical proof chapter.

**Observed:** A readable code pane occupies the left half; a pale, softly rounded stage contains a portrait-format fantasy-art card on the right. A filename strip and tab capsule expose that the demonstration is interactive.

**Transfer:** Replace the fantasy image with a real artifact appropriate to the new tool. Keep implementation or input beside output and retain the pale result backing; do not make the fantasy subject part of the brand language.

### Editorial explanatory figure

**Only for:** editorial information pages

**Use:** Illustrated context within prose.

**Observed:** A small code-window image or a large humorous multi-panel web-development comic sits inside Article figure, with a small gray caption. Image colors remain local to the figure.

**Transfer:** Choose an explanatory diagram or relevant humorous illustration; preserve the right-floated frame and caption rather than turning it into a full-bleed chapter.

### Icons

**Observed:** Small SVG images usually measure 24px for chip logos and arrows, 16px for compact utility controls, and 20px in editorial navigation. Plus signs and arrows are simple dark line shapes; partner logos keep their own colors.

**Transfer:** Use plain line arrows and plus signs for actions; use real recognizable marks only for genuine integrations. Do not turn all pictograms into a matching decorative icon library.

## Section recipes

How recurring sections are built.

### First screen: Geometric clearing opening

**Observed:** A 900px-tall soft-gray first screen, with a 720px minimum and 1024px maximum, places the Rounded geometric field behind a centered promise. Floating navigation sits at the top. The 72px display headline spans a 768px maximum width and breaks into three balanced lines; the 20px body support below is limited to 640px with a 24px gap. The lower area contains Primary button and Video action, each 350×76px with a 24px gap. All copy, both actions and the clipped main graphic are visible within 900px; the next plum sheet's rounded top enters at the bottom, while its actual demonstration remains below the fold.

**Transfer:** Use the same central clearing, original flat vector shapes and a clear outcome headline for a different product. The abstract field supplies visual strength without needing a product render. Editorial pages instead open with the green inset navigation, a left section index and a compact article-title above prose.

**Avoid:** Do not replace the field with a central device render, a dark gradient, or a two-column sales hero; do not let decorative shapes obscure the promise.

**Text style:** `display` — Geist 500 · 72px/88px · tracking -0.015em

### Interactive proof chapter

**Observed:** Demonstration stage carries a centered 60px white headline and 24px support, followed by implementation left and visual result right. A pill-shaped tab strip sits under the pair.

**Transfer:** Show one usable interaction and make the relationship between input and result obvious.

**Text style:** `section-heading` — Geist 500 · 60px/1.1 · tracking -0.015em

### Benefit chapter

**Observed:** Color chapter in yellow has a technical-label eyebrow, centered section-heading and lead, then Benefit card in a three-column row with 32px gutters.

**Transfer:** Use distinct short benefits and natural multiline titles; the colored sheet provides the emphasis.

**Text style:** `section-heading` — Geist 500 · 60px/1.1 · tracking -0.015em

### Sticky capability chapter

**Observed:** A green heading surface introduces the topic; an 800px centered column of Stacking capability card follows. Each card contains a title, body line and Integration chip row. During progression earlier cards recede behind the crisp foreground card.

**Transfer:** Use the stack to explain complementary capabilities or compatibility families rather than repeating a grid.

**Text style:** `card-heading` — Geist 500 · 32px/1.25 · tracking -0.015em

### Symbol gallery

**Observed:** Opening canvas supports a centered heading group, a four-column row of Large sample symbols and a small black discovery action centered below.

**Transfer:** Use this as a browseable set of examples or product applications, with one symbol per destination.

**Text style:** `section-heading` — Geist 500 · 60px/1.1 · tracking -0.015em

### Split objection handling

**Observed:** A violet Color chapter uses a left-aligned eyebrow, section-heading and lead beside a 512px column of Question panel. The heading can wrap into two compact lines.

**Transfer:** Pair a concise reassuring introduction with concrete user questions.

**Text style:** `section-heading` — Geist 500 · 60px/1.1 · tracking -0.015em

### Quote rail

**Observed:** A pink Color chapter puts a left-aligned heading stack beside Testimonial card in a clipped horizontal rail, with plain directional arrows below.

**Transfer:** Use the partial next card to imply a larger collection without shrinking cards to fit.

**Text style:** `section-heading` — Geist 500 · 60px/1.1 · tracking -0.015em

### Graphic closing band

**Observed:** Closing canvas begins with copyright and Footer link in a sparse mono row. Oversized closing lettering and Rounded geometric field fill the lower area; the ending is artwork, not another sales headline.

**Transfer:** Close a marketing story with a strong branded graphic and useful outward links rather than a generic final conversion panel.

**Text style:** `technical-label` — Geist Mono 500 · 16px/1.8

### Long-form article

**Only for:** editorial information pages

**Observed:** Article paper uses an inset green navigation bar, one-of-six-column section index and five-column reading area. A 36px heavy title precedes Article chapter bar, 18px relaxed paragraphs, occasional lists and Article figure. Links are blue and underlined; an italic quote can use a 4px blue left rule with 16px inner padding. Article footer ends the prose.

**Transfer:** Use this variant for explanations that need sustained reading; retain color as a chapter marker, not a full-page background.

**Text style:** `article-title` — ui-sans-serif 800 · 36px/40px · tracking -0.025em

## Page flow

**Storyline:** clear promise → working proof → practical benefits → capability depth → examples → reassurance → useful sign-off

### An approachable technical-product landing page

1. **Promise** — Centered headline in a playful geometric clearing with two broad actions.
2. **Product demonstration** — Plum live proof stage pairs implementation and result.
3. **Benefits** — Yellow chapter with three explanatory cards.
4. **Capability depth** — Green stacking cards expose foundations, familiar tools and compatibility.
5. **Examples** — Large symbol gallery turns applications into browseable destinations.
6. **Objection handling** — Violet split layout with compact question panels.
7. **Social proof** — Pink quote rail with author identity.
8. **Sign-off** — Black graphic band with mono outward links and enormous lettering.

**Transfer:** Borrow the narrative moves as needed; keep the geometric opening and graphic sign-off while choosing the proof and chapters that fit the new product.

### A concise product philosophy or strategy explanation

1. **Orientation** — Green navigation, left section index and compact title.
2. **Thesis** — Yellow marker bar introduces the central argument and contrasting approaches.
3. **Explanation** — Pink chapter supports concrete simplicity with a small framed visual.
4. **Implication** — Teal chapter explains how the idea extends to greater complexity.
5. **Sign-off** — Thin divider and restrained three-part Article footer.

**Transfer:** Use a few coherent arguments and localized color bars; the editorial opening and ending replace the marketing spectacle.

### A longer product introduction and background article

1. **Orientation** — Shared green navigation and article title with section index.
2. **Practical introduction** — Yellow chapter combines explanation, source links and an attributed inset quotation.
3. **Background** — Pink chapter combines narrative, bullets and a large captioned explanatory comic.
4. **Current direction** — Teal chapter presents candid status, limitations and a short agenda.
5. **Sign-off** — Shared restrained copyright, logo and utility-link footer.

**Transfer:** Let the length follow the argument; use framed visuals to break dense text and end candidly with useful next steps.

## Writing

Confident, pragmatic and welcoming to technically curious readers. Claims are explained through familiar foundations and concrete examples, with flashes of informal humor rather than enterprise polish.

**Do not copy:** Do not reuse the FastHTML name or wordmarks, specific technology claims, deployment promises, speed claims, author identities, testimonials, copyrighted illustrations or source code as claims or assets for a new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' about what can be made; use 'we' when discussing the team's choices or unfinished work. Name the product plainly in major claims.
- **Rhythm:** Headlines are short complete thoughts, often 4–10 words and naturally multiline. Support paragraphs explain the promise rather than adding slogans. Long-form prose tolerates fuller sentences, contractions, asides and occasional exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name an outcome and the simplifying method, without a decorative metaphor. | 5–9 words | “Modern web applications in pure Python” |
| Section lead | State a practical benefit or use a conversational question-and-answer pair. | 2–10 words | “Questions? Answers.”<br>“The fastest way to create a real web application.” |
| Technical eyebrow | Short uppercase category with an occasional friendly idiom. | 1–5 words | “GET STARTED IN MINUTES”<br>“LOVE IS IN THE AIR” |
| Action | Plain verb plus destination or object. | 2–3 words | “Learn more”<br>“Watch intro”<br>“Discover all” |
| Editorial caption | A small declarative observation, sometimes gently wry. | 6–10 words | “A minimal [Brand] app really is minimal.”<br>“'Real' web development shouldn't be this hard...” |

**Words and phrasing to use:** build; create; simple; familiar; foundations; in action; get started; scale up and scale down

**Avoid:** revolutionary ecosystem; unparalleled synergy; enterprise-grade transformation; effortless magic

**Rules:**

- Explain what a user can actually make before describing architecture.
- Support broad promises with visible working examples or specific mechanisms.
- Use conversational questions for objections and direct verbs for actions.
- In long-form writing, acknowledge unfinished work and explain the next steps candidly.

## Do's and Don'ts

### Do

- Keep landing-page display type at 500 weight and -0.015em tracking.
- Pair 40px chapter corners with full-width flat color fields.
- Use 24px between major headings and their support copy.
- Give the opening actions equal 350×76px footprints.
- Keep code labels and footer utility links in Geist Mono at 16px/1.8.
- Use 48px desktop padding inside capability and benefit cards.
- Keep sample symbols at a comparable 268px square scale.
- Keep the editorial footer sparse and aligned in three columns.

### Don't

- Do not make all headings 700 or 800 weight; the heavier title belongs only to the editorial variant.
- Do not reduce saturated chapter colors to tiny accent dots on an otherwise white landing page.
- Do not give ordinary benefit cards the strong accordion shadow; their flat inset treatment is intentional.
- Do not replace all corner sizes with one radius: 16px, 20px, 24px and 40px serve distinct roles.
- Do not give the 16px question labels the 24px support-copy recipe.
- Do not put every chapter headline at full container width; centered leads often stay within 512px.
- Do not convert the compact navigation into a full-width corporate menu on the marketing variant.
- Do not end the marketing page with only legal text; preserve the oversized letter-and-shape composition.

## Motion and responsive

### Motion

**Observed:**

- Primary and video actions declare 0.3s color transitions with cubic-bezier(0.4,0,0.2,1). Other action color transitions use 150ms with the same curve.
- Two geometric elements declare orbit at 16s ease-in-out, infinitely repeating.
- Capability cards use sticky positioning and visually recede as later cards overlap them. The demonstration artwork declares transform 0.3s ease-out and box-shadow transition.

**Transfer:**

- Keep decorative motion in the perimeter field, away from reading text.
- Use progressive overlap for the capability stack, leaving the active card crisp and readable.

**Unknown:**

- Exact orbit paths, scroll-linked blur mapping and all animated intermediate states are not specified.
- Expanded question-panel layout and keyboard-focus styling are not established.

### Responsive

**Observed:**

- Marketing CSS includes width breakpoints at 640px, 768px, 1024px and 1440px; editorial CSS includes 640px, 768px, 1024px and 1280px.
- Class declarations switch chapter side padding from 16px to 64px and upper corners from 24px to 40px on larger layouts. Benefit and capability padding switches from 24px to 48px.
- Benefit layouts declare column stacking before the desktop row; footer utility links also declare a stacked narrow layout.

**Transfer:**

- On narrow layouts stack paired actions and proof columns, keep the geometric field clipped at the perimeter, and preserve a clear central reading area.
- Let chips wrap instead of compressing their labels. Collapse the long-form section index rather than retaining a narrow six-column desktop grid.

**Unknown:**

- Mobile renderings, exact type-size changes, navigation-menu behavior and intermediate tablet layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
