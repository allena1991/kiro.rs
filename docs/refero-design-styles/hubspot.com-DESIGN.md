# HubSpot — human warmth, connected growth

## Overview

An approachable business-software style with an editorial serif voice and a practical humanist sans underneath. White and warm ivory dominate, with vivid orange actions, deep green closing bands, and occasional peach-pink feature stages. Warm workplace photography sits alongside simplified interface collages and personable line illustrations; the overall density is airy even when the product catalog is extensive.

### Essentials

- Business promises sound editorial rather than technical: light serif headlines at 65px/1.2, 40px/1.1 section headings, and normal tracking, contrasted with 16px/28px lightweight sans body text.
- The opening gives the promise room before showing people: a centered headline across about 1078px, a 614px support line, paired actions, then an edge-to-edge three-panel photographic strip beginning at 702px.
- Conversion orange is concentrated, not wallpaper: #ff4800 buttons with 8px corners and 2px borders, 68px tall in the opening and 56px in ordinary sections; the default page remains mostly white and off-white.
- Human activity supplies the emotional proof: warm natural-light portraits in three 464px × 560px panels, dark bottom scrims, and 28px serif captions. For products without interface media, use people performing the relevant work rather than abstract technology stock art.
- Product breadth is organized like a helpful catalog: white 16px-radius cards, 1px black-at-11% edges, 24px grid gaps, orange icons and checkmarks, and faint dashed internal rules.
- A peach-to-pink feature stage and a deep-green conversion band punctuate the light page: stage white demonstration cards on the warm wash, then give the closing promise 48px light serif type on #042729 before the charcoal directory footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion orange | `#ff4800` | `--color-orange` | action, accent, border | Primary actions, secondary action outlines, small icons, checkmarks and occasional punctuation. |
| Deep green | `#042729` | `--color-green` | background | Closing conversion bands and emphatic explanatory sections. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Campaign ember | `#c93700` | `--color-ember` | background, action | Warm center of the dark hero glow; also the declared hover fill for orange buttons. |
| Peach stage | `#fcded2` | `--color-peach` | background | Base of the peach-pink feature-stage gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Photographic green-black | `#061c1d` | `--color-photo-base` | background | Backing beneath the full-height photographic panels. |
| Charcoal ink | `#1f1f1f` | `--color-ink` | text, background | Default text and directory footer background. |
| Secondary gray | `#60605f` | `--color-muted` | text | Secondary descriptions on the near-white canvas, rendered with black at 62%. |
| Footer silver | `#aaaaaa` | `--color-footer-muted` | text | White at 62% over charcoal for directory links. |
| Soft card edge | `#e3e3e3` | `--color-edge` | border | Visible black-at-11% outline over white cards; use rgba(0,0,0,0.11) to preserve the edge on other backgrounds. |
| Warm ivory | `#f8f5ee` | `--color-cream` | background, text, border | Warm section bands and reversed lettering or outlines on dark surfaces. |
| Near-white canvas | `#fcfcfa` | `--color-canvas` | background | Main long-form marketing canvas. |
| Pure white | `#ffffff` | `--color-white` | surface, background, text | Opening, navigation, cards, and primary-button lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark product campaigns | Campaign plum | `#290519` | `--color-plum` | background | Full dark product-campaign canvas, not the default landing-page background. |
| dark product campaigns | Glow perimeter | `#370621` | `--color-plum-glow` | background | Outer tone of the campaign radial gradient. |
| dark product campaigns | Smoked plum glass | `#19030f` | `--color-glass` | surface | Visible black-at-40% panel over the plum canvas. |

## Typography

- **HubSpot Sans** — Body copy, navigation, controls, card headings and labels. Open, friendly humanist sans; light body strokes and medium-weight functional text. If unavailable, use **Lato**. Use 300 and 500; preserve open counters and normal tracking. Font stack: "HubSpot Sans", "Lato", Arial, sans-serif.
- **HubSpot Serif** — Core display, section headings, photographic captions and proof numerals; product landing pages use the Book companion cut at the recipe's stated visual weight. Soft editorial serif with gently flared details, generous counters and a light headline color. If unavailable, use **Lora**. Use the lightest available cut for 300 roles and 500 for stronger editorial headings. Font stack: "HubSpot Serif", "Lora", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | HubSpot Serif | 300 | 65px | 1.2 | normal | Default centered opening promise. |
| closing-heading | HubSpot Serif | 300 | 48px | 1.154 | normal | Expansive closing promise on a dark green band; also suitable for a short split photographic opening. |
| heading | HubSpot Serif | 300 | 40px | 1.1 | normal | Core section headings, centered or left-aligned. |
| stat | HubSpot Serif | 500 | 40px | 1.1 | normal | Standalone outcome values paired with compact explanatory labels. |
| photo-caption | HubSpot Serif | 300 | 28px | 1.1 | normal | Bottom-aligned benefit captions over photography. |
| subheading | HubSpot Sans | 500 | 24px | 1.417 | normal | Prominent card headings, integration statements and short editorial subheads. |
| lead | HubSpot Sans | 300 | 18px | 1.778 | normal | Opening support and spacious testimonial statements. |
| card-heading | HubSpot Sans | 500 | 18px | 1.556 | normal | Compact product cards and accordion questions. |
| action-large | HubSpot Sans | 500 | 18px | 1.778 | normal | Opening and prominent conversion actions. |
| body | HubSpot Sans | 300 | 16px | 1.75 | normal | Explanatory paragraphs and feature details. |
| action | HubSpot Sans | 500 | 16px | 1.75 | normal | Ordinary buttons, navigation links and tabs. |
| eyebrow | HubSpot Sans | 500 | 14px | 1.57 | normal, uppercase | Centered opening category line. |
| small-body | HubSpot Sans | 300 | 14px | 1.57 | normal | Compact product-card descriptions and supporting captions. |
| small-action | HubSpot Sans | 500 | 14px | 1.57 | normal | Small text links, framed labels and compact navigation actions. |
| stat-caption | HubSpot Sans | 300 | 14px | 1.75 | normal | Descriptions below proof numerals. |
| footer-link | HubSpot Sans | 500 | 12px | 2.4 | normal | Dense directory links in the footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| dedicated product landing pages | product-display | HubSpot Serif | 300 | 72px | 1.222 | normal | Dedicated product opening, often broken into two or three lines. |
| company and culture pages | company-display | HubSpot Serif | 500 | 48px | 1.154 | normal | Short company-story opening title. |
| dedicated product landing pages | product-heading | HubSpot Serif | 300 | 40px | 1.1 | normal | Capability chapters and product section leads. |
| company and culture pages | company-heading | HubSpot Serif | 500 | 40px | 1.1 | normal | Centered company-story section headings. |
| light product pricing sections | price | HubSpot Sans | 500 | 22px | 1.455 | normal | Monthly prices in three-tier plan cards. |

**Notes:**

- Keep tracking normal throughout; the contrast comes from serif versus sans and light versus medium weight, not condensed spacing.
- Headlines use sentence case. Uppercase belongs to short category lines and select section labels, not ordinary navigation or card headings.
- Default section headings remain light at 40px; stronger 500-weight serif headings belong to company-story content and numeric proof.

## Layout

**Density:** Airy in narrative sections, compact inside useful catalog cards; large outer pauses coexist with tightly grouped bullets.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Principal horizontal padding and gap rhythm; retain the distinct 28px column-gap variant.

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-heading gaps, icon-to-label gaps and close supporting details. |
| 16px | Button pairs, compact content groups and card stacks. |
| 24px | Card gutters, ordinary content gaps and proof-panel padding. |
| 28px | Editorial and two-column FAQ gutters. |
| 32px | Product-card top and side padding; portrait caption insets. |
| 40px | Opening support-to-action gap and chapter spacing. |
| 48px | Product text-to-media gutter and footer vertical padding. |
| 64px | Default major section top and bottom padding. |
| 96px | Opening content inset and larger narrative section pauses. |

### Containers and grids

- **marketing-container**: max width 1220px · side padding 32px. Centered content container for ordinary marketing sections; at 1440px it leaves 110px margins.
- **catalog-grid**: 3 columns · gap 24px. A one-third sticky introduction beside a two-thirds area containing a two-column product-card grid.
- **proof-grid**: 3 columns · gap 24px. Equal feature or proof columns; the first item does not need a left dividing rule.
- **photo-strip**: 3 columns · gap 8px · side padding 16px. Near-full-width portrait strip outside the ordinary content container.
- **editorial-container** (only for company and culture pages): max width 1080px · side padding 16px. Narrower centered company-story layout with more intimate image-and-copy rows.
- **product-split** (only for dedicated product capability chapters): max width 1220px · 2 columns · gap 48px. Text occupies about two fifths, demonstration art the larger remaining area.
- **location-grid** (only for company location directories): max width 1080px · 4 columns · gap 28px. Square illustrations above short, left-aligned location records.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons | 8px |
| cards | 16px |
| labels | 4px |
| carousel-controls | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation | `0px 2px 4px 0px rgba(33, 51, 67, 0.12)` | Subtle separation under the white global navigation. |

### Surfaces

#### Canvas · level 0

**Use:** Main marketing background.

**CSS:** `background: #fcfcfa`

#### White stage · level 0

**Use:** Opening promise and photographic strip backing.

**CSS:** `background: #ffffff`

#### Ivory band · level 0

**Use:** Warm explanatory and proof sections.

**CSS:** `background: #f8f5ee`

#### Outlined card · level 1

**Use:** Catalog, feature and customer-proof containers.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.11); border-radius: 16px; box-shadow: none`

**Observed:** Cards rely on faint outlines rather than heavy elevation; internal dashed rules can divide heading, benefit list and link.

**Transfer:** Keep the outside silhouette simple and let the content determine height.

#### Peach pink stage · level 0

**Use:** Signature highlighted capability or demonstration carousel.

**CSS:** `background-color: #fcded2; background-image: linear-gradient(257deg, rgba(251, 221, 208, 0.3) -32.4%, rgba(255, 165, 129, 0.3) -3.42%, rgba(255, 73, 0, 0.3) 23.87%, rgba(251, 223, 233, 0.3) 50.46%, rgba(253, 191, 219, 0.3) 79.15%, rgba(249, 57, 166, 0.3) 103.64%)`

**Observed:** A full-width warm wash behind white demonstration cards, with pink on the left and peach-orange toward the right.

**Transfer:** Use this stage to distinguish one important capability from the neutral catalog.

#### Green band · level 0

**Use:** Emphatic closing conversion and unifying statements.

**CSS:** `background: #042729; color: #f8f5ee`

#### Charcoal directory · level 0

**Use:** Footer after the conversion section.

**CSS:** `background: #1f1f1f`

#### Campaign glow · level 0

**Only for:** dark product campaigns

**Use:** Dark product opening with ember illumination.

**CSS:** `background-color: #290519; background-image: radial-gradient(98.9% 65.48% at 67.92% 13.95%, #c93700 0px, #370621 95%, rgba(0, 0, 0, 0) 100%)`

**Observed:** A bright, diffuse orange shape sweeps behind the centered headline and fades into plum; pale text sits above it.

**Transfer:** Maintain a broad warm light field, not a small neon halo.

#### Smoked panel · level 1

**Only for:** dark product campaigns

**Use:** Campaign benefit cards, pricing and testimonial panels.

**CSS:** `background: rgba(0, 0, 0, 0.4); border: 1px solid transparent; border-radius: 16px; backdrop-filter: blur(4px); box-shadow: 0px 1px 0px 0px rgba(0, 0, 0, 0.09), -2.5px 0px 3.8px 0px rgba(128, 128, 128, 0.09) inset, 0px 2.5px 3.8px 0px rgba(255, 255, 255, 0.09) inset, 2.5px 0px 3.8px 0px rgba(128, 128, 128, 0.09) inset, 0px -2.5px 3.8px 0px rgba(0, 0, 0, 0.09) inset`

**Observed:** Extremely restrained inset highlights make a softened glass edge, not a glossy floating window.

**Transfer:** Keep the material close to the dark background and use ivory lettering.

## Components

### Global navigation

**Use:** Shared navigation shell.

**CSS:** `background: #ffffff; box-shadow: 0px 2px 4px 0px rgba(33, 51, 67, 0.12); height: 128px`

**Text style:** `action` — HubSpot Sans 500 · 16px/1.75

**Observed:** Two levels: a 52px utility row above a 76px main row. Brand mark on the left, product/solution/resource menus and pricing in the middle, compact conversion actions on the right. On scroll the main row remains visible in a condensed single-bar presentation.

**Transfer:** Separate utility functions from the main product decision paths.

### Primary button

**Use:** Default conversion action in ordinary sections.

**CSS:** `background: #ff4800; color: #ffffff; border: 2px solid transparent; border-radius: 8px; padding: 12px 24px; height: 56px; box-sizing: border-box; text-decoration: none`

**Text style:** `action` — HubSpot Sans 500 · 16px/1.75

**Observed:** Solid primary sits before the outlined alternative. Opening variant uses action-large with 16px 40px padding and 68px height; compact navigation variant uses small-action with 8px 16px padding and 42px height.

**States:** Declared: hover background #c93700 and white text; focus-visible same fill with 2px solid #459195 outline and 2px offset; active background #9f2800.

**Transfer:** Use a direct verb-led conversion label, not a decorative arrow.

### Secondary button

**Use:** Lower-commitment action beside the primary.

**CSS:** `background: #ffffff; color: #ff4800; border: 2px solid #ff4800; border-radius: 8px; padding: 12px 24px; height: 56px; box-sizing: border-box; text-decoration: none`

**Text style:** `action` — HubSpot Sans 500 · 16px/1.75

**Observed:** Matches the primary silhouette. Opening variant follows the same enlarged dimensions as the primary. On dark bands reverse the outline and lettering to ivory over black at 11%.

**States:** Declared: hover color #c93700, background #fcece6, border currentColor; focus-visible adds 2px solid #459195 outline at 2px offset; active color #9f2800 and background #fcc6b1.

### Text link

**Use:** Contextual exploration beneath descriptions.

**CSS:** `color: #1f1f1f; display: flex; align-items: center; gap: 8px; border-radius: 8px`

**Text style:** `small-action` — HubSpot Sans 500 · 14px/1.57

**Observed:** Compact card links often append a thin arrow; editorial links use a fine orange underline rather than turning all their lettering orange.

**States:** Declared: hover text-underline-offset 2px; focus-visible outline 2px solid #459195 at 2px offset; active lettering remains charcoal.

### Section label

**Use:** Small framed category marker above a chapter.

**CSS:** `background: #ffffff; color: #1f1f1f; border: 1px solid rgba(0, 0, 0, 0.11); border-radius: 4px; padding: 4px 8px; display: flex; align-items: center; gap: 8px`

**Text style:** `small-action` — HubSpot Sans 500 · 14px/1.57

**Observed:** Can include a small orange symbol. A fine dashed horizontal rule extends into the space beside labels or larger icon tiles; a far-right outline action can terminate that header row.

**Transfer:** Use a short category label, not a paragraph-sized badge.

### Product card

**Use:** Concise catalog or capability summaries.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.11); border-radius: 16px; padding: 32px 32px 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-heading` — HubSpot Sans 500 · 18px/1.556

**Observed:** Orange outline symbol beside the heading, faint dashed rule, two short benefit bullets with orange checkmarks, another dashed rule and a Text link at the bottom. Body text uses small-body.

**Transfer:** Keep bullets concrete and balance neighboring cards without forcing equal copy length.

### Customer proof panel

**Use:** Large customer story plus measurable outcomes.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.11); border-radius: 16px; padding: 24px; display: grid; gap: 24px; grid-template-columns: 600px 1fr`

**Text style:** `body` — HubSpot Sans 300 · 16px/1.75

**Observed:** Large working-person photo left, quote and attribution right, two centered stats below separated by a fine vertical rule. Segment tabs sit above, using a 4px orange active underline. Product-story variant places segment navigation vertically at the left, uses a dark active rule, and keeps statistics beneath the photograph.

**Transfer:** Use a real customer image and concise attributable quote; substitute a documented outcome story when testimonials are unavailable.

### FAQ row

**Use:** Objection handling near the end of a product page.

**CSS:** `display: flex; justify-content: space-between; align-items: baseline; padding: 20px 24px; gap: 12px; color: #1f1f1f`

**Text style:** `card-heading` — HubSpot Sans 500 · 18px/1.556

**Observed:** Button sits inside an Outlined card; chevron at the right, with 16px between rows and a 28px gutter between two columns. Dark campaign variant is a full-width list with a leading chevron and peach-at-20% top rules instead of rounded white boxes.

**Transfer:** Keep the question label readable and allow multiline rows to grow.

### Footer directory

**Use:** Persistent ending for the entire site.

**CSS:** `background: #1f1f1f; padding: 48px 32px`

**Observed:** A broad two-column feature directory occupies the left, separated by a pale vertical rule from three narrower groups. Beneath: social icons between fine horizontal rules, centered brand mark, copyright, and a row of legal/privacy controls. Uses the marketing container, or the narrower editorial container on company pages.

**Transfer:** Preserve the dense-but-orderly directory hierarchy rather than replacing it with a single email form.

### Footer link

**Use:** Secondary navigation inside the directory.

**CSS:** `color: rgba(255, 255, 255, 0.62); padding: 2px 0px`

**Text style:** `footer-link` — HubSpot Sans 500 · 12px/2.4

**Observed:** Low-contrast links sit below brighter category headings, with an approximately 33px row rhythm.

**States:** Declared: hover ivory text with underline; focus-visible ivory text and 2px solid #7aa485 outline at 2px offset; active ivory text.

### Plan card

**Only for:** light product pricing sections

**Use:** Three parallel product tiers.

**CSS:** `background: #ffffff; border-radius: 16px; display: grid`

**Text style:** `subheading` — HubSpot Sans 500 · 24px/1.417

**Observed:** Small orange tier symbol, 24px sans title, short qualifier, 22px medium price and compact checkmarked feature list. Three 396px-wide cards use 16px column gaps; paired conversion actions sit beneath the entire group rather than repeating on each tier.

**Transfer:** Make inclusions and the progression between tiers easy to compare.

## Imagery and graphics

### Warm working portraits

**Use:** Primary humanizing device in openings and customer stories.

**Observed:** Candid people using laptops, phones or tablets in sunlit, tactile workspaces. Skin tones are warm and natural; beige plaster, wood, plants and soft furnishings replace sterile office blue. The opening strip uses close vertical framing and squared corners; case-study photos are broader and lightly rounded.

**Transfer:** Photograph the relevant people at work, framed close enough to feel personal. Retain the warm environmental light and believable task rather than posing a smiling team at the camera.

**Build:** For a three-panel strip, use three equal object-fit: cover images in 464px × 560px desktop panels with 8px gaps and 16px outer insets. Overlay linear-gradient(188deg, rgba(58,61,59,0) 28.2%, #1f1f1f 94.49%); place ivory serif captions with 32px bottom and side insets.

### Simplified interface collages

**Use:** Capability explanations and feature-stage cards.

**Observed:** Two or three overlapping interface fragments show one understandable task, not a complete dense application. Light product chapters place white and muted sage interface panels on a warm ivory rectangular backing with soft, restrained shadows. Dark campaigns use lavender foreground charts over near-black plum panels. Full browser-scale tours sit in wide rounded frames.

**Transfer:** Rebuild a real workflow as a small number of readable interface fragments, showing a meaningful input, status or result. When no interface exists, use a simple diagram of the same input-to-outcome relationship with the same layered cards.

### Peach pink demonstration stage

**Use:** Signature warm color interruption for a highlighted capability.

**Observed:** A broad smooth pink-to-peach wash supports a central white demonstration card; neighboring cards are smaller and translucent. The header combines an icon tile, faint dashed divider, left serif heading and right support paragraph.

**Transfer:** Give one feature this expressive treatment, using a focused diagram or task card if there is no interface to display.

**Build:** Use the Peach pink stage surface across the full viewport width. Inside a 1220px container, arrange three white 16px-radius cards; center card full scale, flank cards scale(0.9) and opacity 0.5. Use 48px circular white previous/next controls and a separate 32px pause control.

### Personable line illustration

**Use:** Benefit triads, explanatory cards and small proof summaries.

**Observed:** Thin dark green contour drawings on ivory or white, with orange focal shapes, restrained sage and very little shading. Hands, maps, funnels, people and documents turn business ideas into everyday visual metaphors. Typical illustrations occupy a 180px square above sans titles.

**Transfer:** Draw one simple object interaction per benefit; favor human hands and familiar tools over generic glowing AI brains.

**Build:** Create an SVG in a 180px square viewBox using fine dark green contour paths, open cream areas and a few flat orange shapes. Keep backgrounds absent and let the surrounding card supply the paper.

### Ember atmospheric shape

**Only for:** dark product campaigns

**Use:** Hero backdrop and a repeated pricing-area accent.

**Observed:** An oversized orange rounded folded form glows across the upper field, softening into burgundy and plum toward the edges. Its broad scale supports ivory serif type without becoming a literal product object.

**Transfer:** Use one broad diffuse rounded shape with an illuminated upper ridge; match the soft glow, exact stops are not essential.

**Build:** Start with Campaign glow. Behind the text, add an oversized asymmetric rounded rectangle rotated slightly counterclockwise, concentrated toward the upper-right half. Fill with orange-to-transparent tones using rgba(255,72,0,0.7), blur by 50px, and fade it into the plum canvas. Reuse a lower-intensity sweep behind pricing.

### Curved photographic opening

**Only for:** brand rationale and comparison pages

**Use:** Split opening with an expressive crop boundary.

**Observed:** Warm collaborative workplace photo fills the right portion while an oversized near-white organic shape masks its left edge. The left copy stays calmly aligned with the main content container.

**Transfer:** Use a curved mask to join text and photo without enclosing them in separate floating cards.

**Build:** Place a wide cover photo behind the right half. Overlay a near-white SVG shape covering the left half with one broad outward curve at its right edge; keep all text and the orange CTA above this mask.

### Company photography and location art

**Only for:** company and culture pages

**Use:** Company narrative, reports and location directory.

**Observed:** Rounded office and leadership photography alternates with text in a narrower editorial container. Location squares are pastel architectural illustrations with ivory skies, sage landscape, lavender structures, pink water or paths and selective orange landmarks.

**Transfer:** Use genuine workplace photography for the story. For directories, commission consistent flat location scenes; a minimum equivalent uses simplified landmark silhouettes, a curved foreground path and the same restrained pastel distribution.

**Build:** For each square scene, layer an ivory background, pale circular sun, two or three sage or lavender landmark silhouettes, curved pink foreground paths and one orange landmark or vehicle. Use flat fills, sparse thin detail and softly rounded image corners.

### Icons

**Observed:** Small functional SVG icons are primarily filled silhouettes at 12px, 16px and 18px. Product symbols read as light orange outline marks at roughly 24px; carousel chevrons sit in 48px circles. Small orange checkmarks accompany benefit bullets.

**Transfer:** Keep functional icons simple, single-color and aligned with the text baseline; reserve the more expressive outline symbols for product and section identities.

## Section recipes

How recurring sections are built.

### First screen: Editorial promise opening

**Observed:** A white two-level Global navigation occupies the top 128px. Beneath, a 574px white stage centers the category line, display headline, support paragraph and a Primary button/Secondary button pair. The headline spans about three quarters of the viewport and breaks into two balanced lines; its 65px light serif has a small orange final punctuation accent. The eyebrow sits 8px above it, support follows after 24px, and actions follow after 40px with a 16px gap. Text content has a 96px top and bottom inset. The 614px-wide support is much narrower than the headline. Within the first 900px, all text and actions are visible, followed by the upper 198px of the three-panel Warm working portraits strip; the dark captions are below the fold. Layers are plain white, text/actions, then the independent photographic strip, not a background image under the headline.

**Transfer:** For another product, write a broad outcome promise and bring the people doing that work into the strip; no source-specific interface is needed. Dedicated product pages open with product-display, a short identifying line and a wide demonstration beginning below the actions. Brand-rationale pages use Curved photographic opening with a 48px serif title. Company pages use company-display with a smaller rounded photo on an Ivory band. Dark campaigns use the product display over Campaign glow.

**Avoid:** Do not turn this default opening into a split-screen dashboard hero, put the headline over a photo, or replace the broad centered statement with a small left-aligned sans heading.

**Text style:** `display` — HubSpot Serif 300 · 65px/1.2

### Label and heading pair

**Observed:** A Section label or 66px icon tile sits at the start of a faint dashed rule. An outline action can sit at the far end. Below, a 40px light serif heading occupies about 436px at the left while a 436px body paragraph aligns at the right, within the 1220px container. Typical gaps are 16px within the header structure and 24px between content groups.

**Transfer:** Pair a short benefit statement with a practical explanation; keep their widths comparable rather than stretching the paragraph across the empty middle.

**Text style:** `heading` — HubSpot Serif 300 · 40px/1.1

### Sticky catalog

**Observed:** A one-third introductory column remains beside a two-column Product card grid in the remaining two thirds. The section uses Canvas, 64px outer padding and 24px gaps. Intro includes Section label, heading, body and paired actions; card bullets and dashed separators keep the product list scannable.

**Transfer:** Use this construction for related capabilities or offerings; it does not require a large product family.

**Text style:** `heading` — HubSpot Serif 300 · 40px/1.1

### Highlighted capability carousel

**Observed:** Peach pink stage carries a Label and heading pair over white demonstration cards, with the center card emphasized and flanks faded. Card title uses subheading, body uses body, and controls remain separate from the card text.

**Transfer:** Use a short set of task examples, each showing a different outcome from the same capability.

### Customer story and outcomes

**Observed:** A label, heading pair and far-right case-study action introduce a Customer proof panel. Segment tabs lead into a warm photograph, attributable quote and two stats. Nearby award badges form a compact row rather than a wall of giant logos.

**Transfer:** Choose one story with depth and measurable effects instead of a grid of anonymous praise.

### Green closing promise

**Observed:** Green band gives the closing line 48px light serif type, ivory lettering, 64px vertical padding and 40px before paired actions. The primary remains orange; the secondary reverses to an ivory outline. A product variant centers a 40px serif line, brief support and the action pair.

**Transfer:** End the argument with one clear outcome and a familiar next step, preserving a distinct deep-green pause before the directory.

**Text style:** `closing-heading` — HubSpot Serif 300 · 48px/1.154

### Product capability chapter

**Only for:** dedicated product capability chapters

**Observed:** A 1220px product-split presents a 40px serif heading, 16px body paragraph and orange-dot benefit list opposite layered interface art. Two proof values sit below the art with a fine divider, light serif numerals and compact sans descriptions. Chapters are separated with 40px–64px vertical padding.

**Transfer:** Repeat the text-to-result relationship for distinct tasks, not different synonyms for the same benefit.

**Text style:** `product-heading` — HubSpot Serif 300 · 40px/1.1

### Quantified proof triad

**Only for:** brand rationale and quantified proof sections

**Observed:** Three centered outcomes sit on an Ivory band, separated by faint dashed vertical rules, beneath a centered 40px serif statement. Values use 48px light serif type, with 18px/32px explanatory labels and an underlined source link. A compact calculator prompt can follow below.

**Transfer:** Use verified outcome metrics with visible context and a traceable source; keep numbers black rather than oversized orange badges.

### Plans and objections

**Only for:** product buying sections

**Observed:** A centered product heading introduces three Plan cards. Paired actions and a compact pricing qualifier sit below. FAQ row components follow in two light columns; dark campaigns instead use a single full-width ruled accordion list.

**Transfer:** Let buying information become more compact toward the end without changing the overall typography system.

### Scoped photographic close

**Only for:** brand rationale and dark product campaigns

**Observed:** Brand-rationale content ends on an Ivory band with 24px sans heading, short support and a 68px primary action on the left; a roughly 380px square warm portrait sits right with a rotated orange shape behind it. Dark product campaigns retain their plum canvas, use a 40px serif heading and a 380px × 285px portrait, with trial and buy actions plus a short package note.

**Transfer:** Use this close for a more personal campaign ending instead of importing its dark palette into the default layout.

### Company directory close

**Only for:** company and culture pages

**Observed:** The company-story ending is not another oversized hero: Green band contains a centered 40px medium serif title, compact support and six narrow white 16px-radius related-offering cards. Charcoal directory follows directly.

**Transfer:** For an organizational page, conclude by connecting the story to useful offerings or next destinations rather than inventing a hard-sell trial block.

**Text style:** `company-heading` — HubSpot Serif 500 · 40px/1.1

## Page flow

**Storyline:** Outcome promise → human or product demonstration → trust → capabilities and connected value → customer outcomes → buying questions → closing invitation → directory.

### Broad platform or portfolio landing page

1. **Promise** — Centered editorial outcome statement and dual conversion actions, followed by a warm portrait triptych.
2. **Orientation and trust** — Split definition row and compact customer-logo strip.
3. **Capability breadth** — Sticky introduction beside a product-card catalog.
4. **Highlighted demonstration** — Warm gradient carousel and a compact integrations panel.
5. **Customer proof** — Segmented customer story, outcome stats and award badges.
6. **Closing invitation** — Deep-green oversized serif promise, two actions, then the full charcoal footer.

**Transfer:** Balance breadth with one expressive capability stage and one detailed outcome story.

### Brand rationale and differentiation page

1. **Promise** — Curved-mask workplace opening with a short title and single action.
2. **Problem framing** — Ivory illustration triad followed by a centered deep-green unifying statement.
3. **Capability chapters** — Journey diagram, paired large illustrated feature cards, smaller supporting triads and focused feature explanations.
4. **Quantified proof** — Three large percentages, source links and a calculator invitation.
5. **Comparison and objections** — Tabbed product overview followed by a short FAQ.
6. **Closing invitation** — Ivory split portrait call to action followed by the charcoal directory.

**Transfer:** Make the argument concrete with contrasting problems and joined-up solutions, then prove the difference.

### Detailed product conversion page

1. **Promise and demonstration** — 72px serif statement, dual actions and wide product video.
2. **Trust** — Award badges, customer logos and a compact product section navigation.
3. **Capability chapters** — Three text-and-interface chapters, each with quantified outcomes, followed by a full tour.
4. **Audience relevance** — Role tabs connect demonstrations to distinct team benefits.
5. **Customer and comparative proof** — Vertical-segment story panel and a fine-lined comparison table.
6. **Buying information** — Ivory feature directory, three-tier pricing and two-column FAQs.
7. **Closing invitation** — Centered green call to action and shared directory footer.

**Transfer:** Expand the path from task to measurable result, then answer practical buying questions.

### Focused dark product campaign

1. **Promise** — Ivory 72px serif opening over ember/plum atmosphere, white primary action and broad dashboard below.
2. **Problem and method** — Smoked benefit triad followed by repeated text-and-lavender-interface chapters.
3. **Demonstration and proof** — Wide guided tour, centered glass testimonial with circular controls.
4. **Buying information** — Feature checklist beside a single smoked price panel, followed by an integration-value panel and resource columns.
5. **Objection handling** — Long full-width ruled FAQ list.
6. **Closing invitation** — Plum split portrait close with trial and buy actions, then the common charcoal footer.

**Transfer:** Keep the dark campaign coherent end to end, while preserving shared typography, button silhouettes and footer structure.

### Company narrative and practical organizational information

1. **Identity** — Compact ivory split title/photo opening.
2. **Narrative** — Alternating workplace and leadership photographs with mission and origin copy.
3. **Credibility** — Illustrated scale cards, awards and testimonial carousel.
4. **Values and access** — Report carousel, contact information and four-column illustrated location directory.
5. **Further exploration** — Three resource cards.
6. **Closing orientation** — Deep-green related-offerings directory with white cards, then shared charcoal footer.

**Transfer:** Use a narrower editorial container and practical destinations rather than imposing a product trial funnel.

## Writing

Warm, commercially direct and reassuring. It treats complex software as a practical way to make everyday work easier, with confidence grounded in tasks and outcomes rather than technical spectacle.

**Do not copy:** Do not reuse HubSpot names, logos, product identities, customer names, proprietary illustrations, testimonials, prices, market-leadership statements or performance claims. Replace all facts and proof with material true of the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team; refer to the product by its name when explaining what it does. Use we sparingly in organizational narrative.
- **Rhythm:** Headlines alternate a flowing benefit sentence with short emphatic clauses. Supporting copy explains one mechanism at a time, often using a contrast or an em dash; actions are short verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Link a small chain of concrete outcomes to one unifying product idea. | 8–18 words | “Build demand, win deals, and delight customers — all on one platform” |
| Capability heading | Name the job and remove the familiar frustration. | 4–10 words | “Create quotes with prompts, not spreadsheets.”<br>“Let payments collect themselves.” |
| Supporting explanation | Lead with a known fact, then show the practical new possibility. | One or two concise sentences | “Your CRM already knows your customers. Now it handles your revenue, too.” |
| Section bridge | Contrast isolated effort with an integrated outcome. | Two short clauses | “The solution isn't more tools. It's everything working together.” |
| Primary action | Direct verb plus a concrete next step or low-risk qualifier. | 2–5 words | “Get a demo”<br>“Get started free” |
| Closing promise | Return to the benefit with a compact memorable reversal. | 5–12 words | “Make impossible growth feel impossibly easy, with [Brand]” |

**Words and phrasing to use:** work together; your team; connected; context; grow; built in; get started; less time; one place; clear next steps

**Avoid:** revolutionary disruption; unparalleled synergy; next-gen magic; frictionless everything; technical acronyms without explanation

**Rules:**

- Write benefits as actions someone can recognize in their working day.
- Follow an abstract promise with a concrete mechanism, task or result.
- Use contrasts such as prompts, not spreadsheets to clarify the difference without sounding combative.
- Keep package qualifiers adjacent to the relevant conversion action.
- Use numbers only with enough context to explain what changed and for whom.

## Do's and Don'ts

### Do

- Use the 65px/78px light serif as the default opening voice and 40px/44px serif for section leads.
- Keep support paragraphs around 436px wide in split heading rows and 614px in the centered opening.
- Pair solid orange and outlined actions with a 16px gap; retain 8px corners and 2px borders.
- Use 24px card gutters and 16px corners to keep dense catalogs soft but structured.
- Keep 32px portrait caption insets and a dark scrim so warm photography can carry pale serif text.
- Reserve a full-width peach-pink stage for the highlighted demonstration and deep green for the emphatic close.
- Give proof values compact labels and fine dividers instead of decorative badges.
- Retain the charcoal multi-column directory and its centered social/legal ending.

### Don't

- Do not replace the serif/sans contrast with all-bold geometric sans typography.
- Do not tighten headline letter spacing; normal tracking is part of the open editorial character.
- Do not make buttons pill-shaped or use 16px card corners for their silhouette.
- Do not add large card drop shadows to the neutral catalog; its outline is only black at 11%.
- Do not spread saturated orange across every section; its main job is conversion and small emphasis.
- Do not render every product illustration as a dense full application view; isolate the task in two or three fragments.
- Do not treat plum glass and ember atmosphere as the default light-page material.
- Do not make every section centered; split heading rows and asymmetrical text/media chapters supply necessary variety.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color 0.15s linear and color 0.15s linear transitions.
- Text links declare text-underline-offset 0.3s ease-in-out.
- Product chapter copy declares slide-up-fade-in 1s ease; the product display declares slide-up-blur-focus 1s cubic-bezier(0, 0, 0.4, 1).
- Logo strips declare 20s linear scrolling; a separate marquee declares 10s linear. Carousel presentations include pause controls.
- The dark opening declares a 1.8s cubic-bezier(0.42, 0, 0.27, 0.99) reveal.

**Transfer:**

- Keep button feedback quick and restrained while preserving the richer reveal for product-story moments.
- Preserve pause controls for automatically moving logo or demonstration strips.

**Unknown:**

- Exact autoplay dwell times and the timing of all scroll triggers are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 544px, 600px, 800px, 966px, 1080px and 1152px; product templates also declare 1280px.
- The desktop catalog uses a sticky sidebar; tab controls allow horizontal overflow.

**Transfer:**

- Recommended adaptation: stack the introductory column above the catalog when the two-column card area can no longer retain readable line lengths.
- Recommended adaptation: preserve the portrait strip as a swipeable sequence rather than shrinking three captions into narrow columns.
- Recommended adaptation: retain horizontally scrollable tab labels and stack text/media chapters, keeping the benefit before its demonstration.

**Unknown:**

- Exact small-screen typography, navigation behavior and layout changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
