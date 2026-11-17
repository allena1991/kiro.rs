# basic.space — objects before ornament

## Overview

A white, image-led editorial style that feels like a contemporary design showroom crossed with a working marketplace. Black grotesk typography, electric blue links and pale gray divisions let colorful objects and real creative environments carry the personality. The density shifts from compact catalogue labels to expansive statements and tall, unframed product demonstrations.

### Essentials

- The opening reads like an editorial spread, not an advertisement: a 560×399px environmental photograph faces a 55.3px medium-weight statement across a 40px gutter, with a monochrome credibility strip below the statement.
- Blue behaves like a hyperlink made architectural: a 49px electric-blue announcement band and underlined deep-blue 55.3px chapter links punctuate an otherwise white and black interface. Photography supplies almost all other color.
- One grotesk carries both showroom and inventory: FTBasicSpace at weight 500, -0.01em tracking for statements and 14px/1.2 for compact labels; display captions tighten to -0.022em.
- Actions are small capsules beside large pictures: 44px high, 9999px radius, 14px medium labels and a 20px northeast arrow. Black on white scenes and white on darker pictures are the two principal variants.
- Images are the argument: retain a strong environmental opening image and tall visual demonstrations. If there is no physical object, use a carefully art-directed working context and an unframed interface demonstration rather than decorative abstract art.
- The ending gives ownership language unusual prominence: three centered 48px service symbols lead into a four-column, hairline-divided footer, where a 38.5px copyright statement wraps into a narrow tower beside newsletter and utility columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0700ff` | `--color-announcement` | background, action, accent | Announcement band and highlighted action fills; keep the rest of the canvas neutral. |
| Deep hyperlink blue | `#0500b3` | `--color-chapter-link` | link, text | Oversized underlined editorial chapter links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, background | Primary typography, icons and dark action capsules. |
| Muted gray | `#b5b5b5` | `--color-muted` | text, accent | Secondary reassurance copy and subdued directional icons. |
| Input edge | `#e3e3e3` | `--color-input-edge` | border | Input outlines and short navigation dividers. |
| Structural rule | `#ebebeb` | `--color-rule` | border | Footer divisions, service band boundary and assistant panel separators. |
| Product backing | `#f7f7f7` | `--color-media-backing` | surface, border | Pale backing beneath catalogue photography and the very faint navigation edge. |
| Search wash | `#fafafa` | `--color-search` | surface | Search input backing. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Main canvas, navigation, light capsules and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pages with an interactive advisor | Soft ink | `#1a1a1a` | `--color-soft-ink` | text | Conversational prompt text. |
| pages with an interactive advisor | Advisor white | `#fbfbfb` | `--color-advisor` | surface | Persistent assistance panel. |

## Typography

- **FTBasicSpace** — All marketing text, navigation, labels and controls. A compact contemporary grotesk with open counters, plain terminals and an editorial medium weight; no competing display family. If unavailable, use **Inter**. Use 400–600; retain negative tracking and check line wrapping. Font stack: "FTBasicSpace", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | FTBasicSpace | 500 | 55.3px | 1.136 | -0.01em | size calc(12.5px + 2.97107vw) | Opening promise and oversized chapter links. Chapter links are blue and underlined; the opening statement is black without an underline. |
| display-caption | FTBasicSpace | 500 | 38.5px | 1.125 | -0.022em | size calc(25px + 0.938233vw) | Monumental footer copyright and centered photographic collection titles. |
| editorial-body | FTBasicSpace | 500 | 37.8px | 1.136 | -0.01em | size calc(17.5px + 1.40735vw) | Short explanatory paragraphs beside tall demonstrations; deliberately close to heading scale. |
| label | FTBasicSpace | 500 | 14px | 1.2 | -0.01em | fixed | Navigation, product names, prices, action labels and service titles. |
| muted-body | FTBasicSpace | 400 | 14px | 1.43 | -0.01em | fixed | Centered service explanations in muted gray. |
| footer-link | FTBasicSpace | 500 | 14px | 1.714 | -0.01em | fixed | Stacked footer utility links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| catalogue pages | catalogue-heading | FTBasicSpace | 500 | 37.5px | 1.2 | -0.01em | size calc(15px + 1.56372vw) | Compact category title above filters. |
| collection browsing sections | collection-eyebrow | FTBasicSpace | 600 | 14px | 1.2 | -0.01em, uppercase | fixed | White qualifier above a photographic collection title. |
| pages with an interactive advisor | question | FTBasicSpace | 400 | 13px | 1.25 | -0.01em | fixed | Natural-language suggestion pills. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Statements and explanatory paragraphs both use medium weight; size and placement establish hierarchy rather than heavy bold.
- Keep the opening headline ragged-right and sentence case. The underline belongs to linked chapter headings, not to every heading.
- Display captions and the footer copyright use -0.022em tracking; the principal editorial recipes retain -0.01em.
- The large editorial paragraph is not a conventional 16px support paragraph. Preserve its visual authority and restrict its length.

## Layout

**Density:** Airy editorial chapters with compact navigation and catalogue metadata; large media carry the page between short text groups.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Price-to-name gaps and icon-to-label spacing. |
| 8px | Collection rail gutters and advisor prompt gaps. |
| 12px | Media-to-metadata spacing and capsule padding. |
| 16px | Product grid gutters and navigation side padding. |
| 24px | Footer cell padding and compact category header vertical padding. |
| 32px | Opening offset below navigation and rail heading-to-media gap. |
| 40px | Editorial column gutters and chapter link-to-paragraph separation. |
| 48px | Commerce section side inset and separation between merchandising blocks. |
| 72px | Service reassurance band top and bottom padding. |
| 80px | Editorial chapter separation. |

### Containers and grids

- **editorial container**: max width 1280px · 12 columns · gap 40px · side padding 32px. Editorial grid. At 1440px with the advisor open the main region is 1224px wide; the content spans 1160px. The opening divides equally into two 560px columns.
- **demonstration chapter**: 12 columns · gap 40px. Tall 360px media occupies four columns, while a 660px text group occupies seven columns across a deliberate intervening space. Alternate which side holds the media.
- **footer cells**: 4 columns · gap 0px · side padding 24px. Equal-width footer columns with hairline divisions. Each is 306px wide in the advisor-open desktop composition.
- **catalogue grid** (only for catalogue and merchandising sections): 6 columns · gap 16px · side padding 48px. Six equal 175px product columns inside the main region; horizontal rails retain this media width and reveal a partial next item.
- **assistance allocation** (only for pages with an interactive advisor): max width 216px. Fixed right-hand full-height advisor panel; main content reserves its width instead of being obscured by it.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action capsules | 9999px (pill) |
|  | search input | 16px |
| catalogue and merchandising sections | catalogue media | 2px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default page plane.

**CSS:** `background: #ffffff; color: #000000; box-shadow: none`

**Observed:** Media and text sit directly on white with no enclosing raised card.

**Transfer:** Let column geometry and image boundaries organize the page.

#### Hairline divisions · level 0

**Use:** Navigation edge, service band and footer structure.

**CSS:** `border-top: 1px solid #ebebeb; box-shadow: none`

**Observed:** Rules divide adjoining regions rather than outlining every text group.

**Transfer:** Use a single shared rule between adjacent cells.

#### Catalogue image field · level 0

**Only for:** catalogue and merchandising sections

**Use:** Neutral support for object photography.

**CSS:** `background: #f7f7f7; aspect-ratio: 4 / 5; overflow: hidden`

**Observed:** Images have 2px corners and multiply blending, integrating light photographic backings with the field.

**Transfer:** Use a softly lit product image with its ground intact, not a floating cutout with a UI shadow.

#### Collection scrim · level 1

**Only for:** collection browsing sections

**Use:** A transparent contrast layer above full-bleed photography.

**CSS:** `background: rgba(92,84,84,0.3)`

**Observed:** Warm-gray transparency darkens the photograph uniformly behind white labels.

**Transfer:** Preserve visible material texture; this is not a gray panel independent of the image.

#### Advisor plane · level 1

**Only for:** pages with an interactive advisor

**Use:** Adjacent conversational assistance.

**CSS:** `background: #fbfbfb; border-left: 1px solid #ebebeb; box-shadow: none`

**Observed:** A full-height neutral plane with header and bottom-pinned questions.

**Transfer:** Use only when real interactive help is available.

## Components

### Navigation

**Use:** Compact persistent wayfinding.

**CSS:** `background: #ffffff; height: 61px; padding: 0px 16px; border-bottom: 1px solid #f7f7f7`

**Text style:** `label` — FTBasicSpace 500 · 14px/1.2 · tracking -0.01em

**Observed:** A small text wordmark and tightly spaced category links sit left; pale Search, account and cart sit right. Short vertical dividers separate link families. The combined announcement and navigation remain sticky at 110px.

### Announcement band

**Use:** Single high-priority site-wide action.

**CSS:** `background: #0700ff; color: #ffffff; padding: 16px; height: 49px; display: flex; justify-content: center; align-items: center`

**Text style:** `label` — FTBasicSpace 500 · 14px/1.2 · tracking -0.01em

**Observed:** One underlined line centered over the main page region, not over the advisor.

### Primary capsule

**Use:** A short action associated with a visual scene.

**CSS:** `background: #000000; color: #ffffff; border-radius: 9999px; height: 44px; padding: 12px 12px 12px 16px; display: inline-flex; align-items: center; gap: 4px`

**Text style:** `label` — FTBasicSpace 500 · 14px/1.2 · tracking -0.01em

**Observed:** A northeast arrow follows the label. Width is content-driven, with an 87px example; it is not a full-width conversion bar. A white version over photography uses 12px padding on all sides and black lettering.

**Transfer:** Keep labels brief enough that the action stays secondary to the scene.

### Chapter link

**Use:** Introduce a linked editorial explanation.

**CSS:** `color: #0500b3; text-decoration-line: underline; margin-bottom: 40px`

**Text style:** `display` — FTBasicSpace 500 · 55.3px/1.136 · tracking -0.01em

**Observed:** A heading-sized link precedes a large black paragraph; it is the action, so a competing button is unnecessary.

**Transfer:** Name the useful destination in direct language rather than adding a generic learn-more control.

### Service assurance

**Use:** Compact trust language near the ending.

**CSS:** `width: 256px; padding: 0px 24px; text-align: center`

**Text style:** `label` — FTBasicSpace 500 · 14px/1.2 · tracking -0.01em

**Observed:** A 48px black symbol sits above a short title and muted-body explanation. Three equal items are spread evenly in a band with 72px top and bottom padding.

**Transfer:** Use three concrete promises about the new offering rather than inflated social-proof counters.

### Footer column

**Use:** Utility navigation and identity closing.

**CSS:** `padding: 24px; border-left: 1px solid #ebebeb; height: 329px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `footer-link` — FTBasicSpace 500 · 14px/1.714 · tracking -0.01em

**Observed:** Four equal cells share a top rule. The first has no left rule and carries display-caption copyright language above a short ownership line. The other cells contain a newsletter, a link list with a bottom-pinned policy link, and account/legal links.

### Newsletter field

**Use:** A low-pressure subscription action in the footer.

**CSS:** `background: #ffffff; height: 44px; width: 233px; border: 0px; border-radius: 0px`

**Observed:** A short invitation sits at the top of the cell; an oversized pale email prompt and right arrow sit at the bottom without a surrounding rounded container. The arrow is a separate submit control.

**Transfer:** Keep the input visually open and make its label accessible; do not substitute a boxed signup card.

### Search field

**Use:** Compact search within navigation.

**CSS:** `background: #fafafa; height: 36px; width: 278px; border-radius: 16px; padding: 0px 80px 0px 40px`

**Text style:** `label` — FTBasicSpace 500 · 14px/1.2 · tracking -0.01em

**Observed:** A black 16px search icon anchors the left; the pale control is visually quieter than category links.

### Product card

**Only for:** catalogue and merchandising sections

**Use:** A compact visual unit of browsable inventory.

**CSS:** `width: 175px; flex-shrink: 0; box-shadow: none`

**Text style:** `label` — FTBasicSpace 500 · 14px/1.2 · tracking -0.01em

**Observed:** A 4:5 Catalogue image field precedes a one-line truncated name, price on the next line and uppercase maker attribution on a pale gray strip. Media-to-text spacing is 12px; name-to-price spacing is 4px. Sold-out variants blur the image by 4px and add a black status tab; this is an availability treatment, not the normal image style.

**Transfer:** For non-retail content use a concise artifact name, meaningful metadata and attribution in the same order.

### Collection tile

**Only for:** collection browsing sections

**Use:** Immersive browsing by theme.

**CSS:** `width: 432px; height: 648px; background-size: cover; background-position: 50% 50%; color: #ffffff`

**Text style:** `display-caption` — FTBasicSpace 500 · 38.5px/1.125 · tracking -0.022em

**Observed:** Collection scrim covers the image. A centered uppercase qualifier sits 16px above the title in the lower-middle area; a white Primary capsule sits 32px above the bottom. Tiles form an 8px-gutter horizontal overflow rail.

### Advisor panel

**Only for:** pages with an interactive advisor

**Use:** Persistent contextual help alongside the page.

**CSS:** `background: #fbfbfb; border-left: 1px solid #ebebeb; width: 216px; position: fixed; right: 0px; top: 0px; height: 100%; display: flex; flex-direction: column`

**Observed:** A named advisor header, short invitation, open conversational area and bottom question group fill the rail. Small blue four-point stars mark the advisor. The send control is a 32px black circle.

**Transfer:** Reserve space in the content layout; do not lay the panel over images.

### Question pill

**Only for:** pages with an interactive advisor

**Use:** Suggested natural-language help requests.

**CSS:** `background: #ffffff; color: #1a1a1a; border: 1px solid #000000; border-radius: 9999px; padding: 4px 12px 6px; text-align: left`

**Text style:** `question` — FTBasicSpace 400 · 13px/1.25 · tracking -0.01em

**Observed:** Pills stack with 8px gaps and wrap naturally; examples range from 28px to 61px high. A separate input pill below them uses the lighter Input edge border.

**States:** Declared: hover background #000000 and text #ffffff; focus-visible not specified.

**Transfer:** Use genuine questions rather than terse filter tags.

## Imagery and graphics

### Environmental opening photograph

**Use:** The default opening's large visual proof.

**Observed:** A bright working showroom with tall windows, plywood display plinths, a pale blue chair, vivid green accents and a person in the background. The frame is landscape, rectangular and edge-to-edge with no border, shadow or color filter; it occupies half of the editorial spread.

**Transfer:** Photograph the new product in a credible working environment with daylight, physical material and one memorable colored detail. For a digital offering, show the product in use in a real setting instead of a stock-office handshake.

### Tall interface demonstrations

**Use:** Editorial chapters explaining experience and participation.

**Observed:** Unframed mobile interface images sit directly against white at about 360×779px, alternating sides. One shows a three-column object grid, another a portrait mosaic, and another a social-style experience view; their scale outweighs surrounding UI controls.

**Transfer:** Show the new product's meaningful interactions or people in a tall, clean composition. Retain white backing and avoid adding an invented metallic device shell.

### Monochrome credibility strip

**Use:** Proof placed beneath the opening statement.

**Observed:** Five black publication marks of unequal widths align in one low strip below generous white space. Their original lettering varies, while monochrome treatment unifies the row.

**Transfer:** Use legitimate customer, partner or certification marks in black with comparable optical height. Where marks are unavailable, use a small typographic proof strip of substantiated credentials.

### Studio object photography

**Only for:** catalogue and merchandising sections

**Use:** Compact product cards and immersive themed tiles.

**Observed:** Isolated collectible objects, furniture and art on white, pale gray, warm beige or dark studio grounds, with soft directional shadows. Product grids mix straight-on and three-quarter views; collection images crop closer into fruit, carved wood and pleated lighting, emphasizing tactile material.

**Transfer:** Keep real object texture and diverse silhouettes. For a digital service, use focused visual artifacts or individual output examples rather than repeated generic dashboard thumbnails.

### Striped campaign artwork

**Only for:** graphic campaign promotions

**Use:** A high-contrast interruption within merchandising content.

**Observed:** A black landscape banner combines dense diagonal white lines over its left portion with large white lettering toward the right. The art reads as a poster rather than an interface.

**Transfer:** Use a project-specific statement with similarly strong geometric contrast; keep this look limited to an actual campaign.

**Build:** Use a black rectangle; place an SVG group of parallel white diagonal lines over roughly the left two thirds, clipping the group to a sloped edge. Put a short white text line over the stripe field and a larger project-specific sans word treatment over the clear black right side. Keep the pattern sharp, without glow or blur.

### Icons

**Observed:** Functional symbols are plain black filled SVGs at 16–20px, with northeast arrows in visual actions. Service symbols are much larger at 48px: a circular arrow, a seal/check and an outlined parcel. The advisor adds small blue four-point stars and restrained thin outline controls.

**Transfer:** Match each function with one clear monochrome glyph; keep 48px symbols reserved for service assurance, not every feature heading.

## Section recipes

How recurring sections are built.

### First screen: Editorial proof opening

**Observed:** White canvas sits behind the 49px Announcement band and 61px Navigation. After a 32px offset, a 560×399px environmental photograph fills the left half of a 1160px-wide editorial spread; a 40px gutter separates it from a right-hand black display statement. The headline wraps into three lines near the top, with five black credibility marks near the bottom of its column. There is no hero capsule or extra support paragraph: the statement and linked global band do that work. In the first 900px the entire spread is visible and the next tall visual chapter begins after an 80px gap; its large chapter link starts to enter near the lower edge. A 216px advisor occupies a separate right-hand plane when active.

**Transfer:** Make the default new landing page an image-and-statement editorial spread with a credibility strip. Use a real working-context photograph or a carefully composed output scene when there is no physical product. Let the next chapter demonstrate the promise. Catalogue pages instead open with a compact category heading, one descriptive line and filter/sort controls; merchandising pages can open with a horizontal product rail.

**Avoid:** Do not turn this into a centered mega-headline above a floating dashboard, add a hero button stack, or shrink the photograph to a decorative thumbnail.

**Text style:** `display` — FTBasicSpace 500 · 55.3px/1.136 · tracking -0.01em

### Alternating explanation chapter

**Observed:** A tall interface demonstration occupies four columns; a seven-column text group centers vertically against it. Chapter link precedes editorial-body text by 40px. The next chapter reverses the media side; chapters are separated by 80px and remain on White canvas.

**Transfer:** Give each chapter one destination and one clear explanation of utility. Use content length, not equal-height text cards, to control the reading rhythm.

**Text style:** `editorial-body` — FTBasicSpace 500 · 37.8px/1.136 · tracking -0.01em

### Assurance and ownership ending

**Observed:** Three Service assurance items form a roughly 309px-tall band above a four-column footer. Hairline divisions mark the lower 330px region. The copyright takes display-caption scale and wraps across approximately five lines inside the first cell; the short ownership line anchors its bottom. Newsletter field, contact links, policy and account links fill the other cells. This is the closing action area, without a giant final sales button.

**Transfer:** Preserve the contrast between small service reassurance and unusually prominent ownership typography. Adapt the legal identity to the new project and keep subscription low pressure.

**Text style:** `display-caption` — FTBasicSpace 500 · 38.5px/1.125 · tracking -0.022em

### Compact inventory opening

**Only for:** catalogue pages

**Observed:** The category header uses 24px vertical and 48px horizontal padding, a catalogue-heading title and one compact descriptive line, followed by a ruled 66px filter/sort row. A six-column Product card grid begins below it with 16px gutters.

**Transfer:** Use when the visitor needs to browse a large collection rather than read a brand proposition.

**Text style:** `catalogue-heading` — FTBasicSpace 500 · 37.5px/1.2 · tracking -0.01em

### Photographic collection rail

**Only for:** collection browsing sections

**Observed:** A small left-aligned section label and right-side arrows precede Collection tiles. The rail starts at a 48px side inset, overflows horizontally and exposes a partial next tile. Image captions are much larger than catalogue metadata.

**Transfer:** Group a broad offering into visually distinct use cases and use the same close material framing for each.

### Full-width visual invitation

**Only for:** merchandising and campaign pages

**Observed:** A 576px-high landscape scene covers the main region with 48px horizontal insets for content. A short qualifier and a 40px black title sit near the lower-left, with a Primary capsule at lower-right. A separate poster-like campaign version uses Striped campaign artwork.

**Transfer:** Use a scene with sufficient clear floor or background for readable text; keep it a focused invitation rather than a multi-card feature summary.

## Page flow

**Storyline:** Visual promise → concrete experience → human or practical proof → reassurance → utility and ownership closing.

### Editorial introduction to a product or platform

1. **Promise and credibility** — Environmental photograph beside a large statement, with a monochrome proof strip below.
2. **Product demonstration** — Tall interface image paired with a heading-sized link and large explanatory paragraph.
3. **Human proof** — Reversed chapter places a people-focused interface opposite an explanation of participation and trust.
4. **Contextual experience** — Another tall visual connects real-world experience and digital access.
5. **Reassurance and closing** — Three service promises precede the divided utility footer and prominent copyright.

**Transfer:** Use the alternating editorial structure for a new product's benefits, outputs and people; the number of chapters follows the story.

### Discovery-led merchandising

1. **Immediate product proof** — A compact recommendation rail shows object images, prices and attribution before a large proposition.
2. **Timely invitation** — A full-width graphic campaign banner interrupts the white catalogue rhythm.
3. **Guided exploration** — Tall photographic collection tiles turn inventory into themes.
4. **Closing invitation** — A wide scene offers one short participation action.
5. **Reassurance and closing** — Shared service band and four-column footer.

**Transfer:** Use this variant when users already understand the category and benefit more from seeing selectable examples immediately.

### High-density collection browsing

1. **Orientation** — Compact title and one descriptive sentence establish the collection.
2. **Control** — Filter and sort row gives immediate browsing tools.
3. **Product demonstration** — A long six-column grid maintains image, title, price and attribution order, including explicit availability labels.
4. **Reassurance and closing** — The same assurance band and ownership-led footer close the long list.

**Transfer:** Use the catalogue treatment for substantial inventories without carrying its extreme list length into a marketing page.

## Writing

Confident curatorial language meets direct marketplace utility. Editorial statements are expansive but plainspoken; controls and item labels are factual and short.

**Do not copy:** Do not reuse Basic.Space names, slogans, campaign artwork, publication endorsements, seller identities, product names, membership counts, locations or exclusivity claims as assets or facts for another brand. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader with you and your in practical copy; use our for the team or service. Labels are usually impersonal nouns, while invitations use simple verbs.
- **Rhythm:** Short noun-led labels alternate with one substantial sentence in editorial chapters. Headlines use sentence case or concise title case; uppercase is reserved for maker attribution and photographic qualifiers.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | An action-led sentence that names what the visitor can discover and its breadth. | About 12–16 words | “Discover and shop the future of fashion, design, art and more.” |
| Chapter link | A concise destination or experience, expressed as a useful phrase. | 2–4 words | “Shop Anything, Anytime”<br>“Our Sellers” |
| Reassurance title | A compact service promise with a specific quality or reader benefit. | 2–5 words | “Obsessively Curated”<br>“Shipping Tailored to You” |
| Supporting line | Describe concrete access or service in one sentence rather than stacking abstract benefits. | About 12–25 words | “Access our exclusive community of trusted sellers, hand-picked by our team.” |
| Action | One short verb or established participation term; the arrow supplies direction. | 1–2 words | “Shop”<br>“Enter”<br>“RSVP” |

**Words and phrasing to use:** discover; curated; hand-picked; trusted; access; experience; tailored; limited editions

**Avoid:** revolutionary solution; unlock your potential; game-changing; seamless ecosystem; !!!

**Rules:**

- Pair broad editorial claims with a concrete visual or demonstrable service.
- Keep catalogue names descriptive and preserve meaningful attribution.
- Let linked headings carry navigation; do not append a learn-more sentence to every paragraph.
- Use natural-language questions only in help interactions.

## Do's and Don'ts

### Do

- Use the 55.3px medium statement and 40px gutter for the default editorial opening.
- Keep chapter descriptions visually substantial at 37.8px rather than reverting to tiny support text.
- Keep visual actions at 44px high with 9999px corners and a 20px arrow.
- Use 1px structural rules to divide adjoining footer cells.
- Preserve 4:5 catalogue media and 12px media-to-label spacing.
- Place three 48px service symbols above the closing utility area.
- Give the copyright the same 38.5px scale used for photographic captions.
- Use blue sparingly in the page shell and let image content supply varied color.

### Don't

- Do not add drop shadows or rounded shells to editorial media; the surfaces are flat.
- Do not render the entire page in electric blue; the 49px band is the principal blue fill.
- Do not use wide-tracked uppercase for normal navigation; it is 14px with -0.01em tracking.
- Do not make large explanatory paragraphs light gray; muted gray belongs to small reassurance copy.
- Do not make all images identical floating cutouts; environmental and close material views are part of the vocabulary.
- Do not replace the narrow, wrapping ownership statement with a tiny single-line legal tail.
- Do not use the 4px sold-out blur on available products or editorial pictures.
- Do not turn the footer newsletter into a filled promotional card or a full-width subscription button.

## Motion and responsive

### Motion

**Observed:**

- Action and listing transitions include 0.3s cubic-bezier(0.4, 0, 0.2, 1). Question pills declare color transitions at 0.15s with the same curve and invert to white on black on hover.
- The advisor panel declares a width transition of 0.2s. No page-level animation is established.

**Transfer:**

- Keep interaction feedback concentrated on compact controls and listing surfaces rather than animating the editorial composition.

**Unknown:**

- Scroll choreography, autoplay behavior and animation timing beyond the declared transitions are unspecified.

### Responsive

**Observed:**

- Editorial columns declare full-width spans before the lg layout, then use the 12-column arrangement. Section spacing changes from 40px to 80px; chapter heading-to-paragraph spacing changes from 12px to 40px.
- Desktop announcement and expanded search are hidden outside the lg layout. Footer declares one column before the four-column desktop layout.
- Declared width breakpoints include 640px, 768px, 1023px, 1024px, 1280px and 1400px.

**Transfer:**

- Stack the editorial image and statement while preserving image prominence and sentence hierarchy. Keep demonstration media on white and let the fluid type recipes reduce their scale.
- Retain horizontal browsing for themed tiles rather than compressing them into illegible narrow columns; stack footer utility cells with shared rules.
- When a persistent help rail cannot fit, move assistance out of the main reading columns rather than covering editorial imagery.

**Unknown:**

- Exact mobile advisor behavior, navigation menu construction and all narrow-screen image crops are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
