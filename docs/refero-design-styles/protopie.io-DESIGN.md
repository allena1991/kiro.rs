# ProtoPie — pastel product playgrounds

## Overview

An approachable software style that makes sophisticated tools feel tactile and inviting. White space and soft mint, peach and lavender atmospheres surround bold geometric sans headings, practical interface imagery and playful clay-like objects. Dark violet demonstration stages give the otherwise light, spacious pages a more immersive register, while pricing and comparison areas become deliberately denser.

### Essentials

- Bold promises sit above a real working object: centered Figtree 62px/80px at 700, a 780px-wide support line, one compact violet action, then a 1200px interface stage entering the first screen.
- Soft color behaves like light rather than colored boxes: white remains the dominant canvas; edge-to-edge mint, peach and lavender radial washes fade back to white, with saturated #8169ff concentrated in actions and selected details.
- Small rectangular actions contrast with soft containers: 4px button corners and 14px 16px padding versus 12px resource cards, an 18px interface frame and 20px closing panels.
- Product truth and toy-like metaphors coexist: large readable interface demonstrations and natural hands-on footage are paired with rounded lavender, cream and coral objects; use a simplified shaded geometric object when bespoke 3D is unavailable.
- A violet theater interrupts the light page: a near-black purple field, white 48px headings, category tiles and a central demonstration create a focused showcase rather than turning the whole page dark.
- The closing invitation is a decorated stage, not a bare strip: a 1200px-wide translucent 20px-radius panel holds a centered 48px heading, compact reassurance row and action, with floating objects kept around the edges.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#8169ff` | `--color-accent` | action, link, accent | Primary actions, selected tiles, arrows and short emphasized words. |
| Midnight violet | `#1a1935` | `--color-theater` | background | Immersive demonstration stages. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint light | `#e0f6f6` | `--color-mint-wash` | background | Visible mint glow over white; source hue rgb(129,219,219) at 25% opacity. |
| Peach light | `#ffece9` | `--color-peach-wash` | background | Visible peach glow over white; source hue rgb(255,178,167) at 25% opacity. |
| Lavender light | `#f2efff` | `--color-lavender-wash` | background | Visible lavender glow over white; source hue rgb(201,191,255) at 25% opacity. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, border | Dominant canvas, interface frames, inverse text and white card edges. |
| Active feature gray | `#f5f5f5` | `--color-tile` | surface | Expanded feature item on the white page. |
| Utility fill | `#e9e9e9` | `--color-utility` | surface | Small language-selector backing. |
| Utility gray | `#999999` | `--color-faint` | text | Low-emphasis utility text and social icons. |
| Proof gray | `#828282` | `--color-label` | text | Subdued social-proof labels. |
| Supporting gray | `#666666` | `--color-support` | text | Secondary descriptions and data captions. |
| Navigation gray | `#636363` | `--color-muted` | text | Footer navigation links. |
| Card charcoal | `#474747` | `--color-secondary` | text | Resource-card descriptions. |
| Paragraph charcoal | `#373737` | `--color-body` | text | Longer explanatory paragraphs and FAQ answers. |
| Heading ink | `#181818` | `--color-ink` | text | Default heading and body ink. |
| Display black | `#000000` | `--color-black` | text | Section display text and simple solid icons. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark feature chapters | Inverse gray | `#e0e0e0` | `--color-inverse-muted` | text | Explanations on dark product chapters. |
| comparison and feature FAQ sections | Lavender hairline | `#f1efff` | `--color-lavender-rule` | border | Visible pale divider made from lavender at 50% opacity over white. |
| pricing pages | Pricing cream | `#fff8e7` | `--color-pricing-cream` | background | Warm edge of the pricing atmosphere. |
| pricing pages | Pricing lilac | `#ebe4ff` | `--color-pricing-lilac` | background | Cool edge of the pricing atmosphere. |

## Typography

- **Figtree** — Headings, navigation and strong labels. Friendly geometric sans with open counters and rounded terminals. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Figtree", sans-serif.
- **Inter** — Paragraphs, actions, forms and utility copy. Neutral, compact interface sans; regular paragraphs balance the rounded bold headings. Font stack: "Inter", sans-serif.
- **Palmer Lake Print** — Short handwritten invitations beside a demonstration. Casual, narrow hand-lettered capitals. If unavailable, use **Caveat**. 400; keep labels brief rather than expanding into a handwriting system. Font stack: "Palmer Lake Print", "Caveat", sans-serif.
- **Gilroy** (only for quantified business proof) — Oversized numerical results and their suffixes. Heavy geometric numerals with round counters. If unavailable, use **Plus Jakarta Sans**. 800 for numerals, 700 for suffixes. Font stack: "Gilroy", "Plus Jakarta Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Figtree | 700 | 62px | 80px | normal | Primary centered promise, usually one or two lines. |
| heading | Figtree | 700 | 48px | 1.3 | normal | Section headings and the closing invitation. |
| subheading | Figtree | 700 | 36px | 1.4 | normal | Split editorial rows and price amounts. |
| hand-note | Palmer Lake Print | 400 | 32px | 1.4 | normal | Brief violet demonstration invitation. |
| card-heading | Figtree | 700 | 28px | 1.4 | normal | Resource and tier card titles. |
| lead | Inter | 400 | 24px | 1.4 | normal | Centered support under major headings. |
| item-heading | Figtree | 700 | 22px | 1.4 | normal | Feature selectors and footer column headings. |
| body-lg | Inter | 400 | 18px | 1.4 | normal | FAQ answers, showcase captions and reassurance copy. |
| action | Inter | 600 | 18px | 1.4 | normal | Hero and major conversion buttons. |
| faq-question | Inter | 700 | 18px | 1.4 | normal | Default FAQ questions. |
| body | Inter | 400 | 16px | 1.5 | normal | Feature explanations, cards and form labels. |
| action-sm | Inter | 600 | 16px | 1.4 | normal | Compact buttons and arrow links. |
| nav | Figtree | 700 | 16px | 1.4 | normal, capitalize | Main navigation labels. |
| proof-label | Figtree | 700 | 16px | 1.5 | normal | Centered trust label above muted logos. |
| small | Inter | 400 | 14px | 1.4 | normal | Footer links and compact comparison values. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quantified business proof | stat | Gilroy | 800 | 64px | 1.2 | normal | Violet result numerals. |
| quantified business proof | stat-suffix | Gilroy | 700 | 64px | 1.2 | normal | Percentage signs accompanying result numerals. |
| dark feature chapters | dark-heading | Figtree | 700 | 36px | 1.2 | normal | Compact benefit headings next to a demonstration. |
| pricing pages | plan-label | Figtree | 700 | 24px | 1.4 | normal | Plan names and comparison category headings. |
| AI feature FAQs | feature-faq | Figtree | 700 | 22px | 1.2 | normal | Larger question text in widely spaced rows. |
| dark feature chapters | dark-body | Inter | 400 | 16px | 1.4 | -0.01em | Gray explanatory copy and bullet lists. |

**Notes:**

- Use natural tracking for the default scale; rounded bold headings do not need aggressive negative letter spacing.
- Keep Figtree for hierarchy and Inter for reading. The handwritten note is a tiny expressive interruption, not a body font.
- Centered heading blocks usually occupy 900px; hero titles can reach 996px. Support lines are narrower, so line breaks remain deliberate.
- The dark chapter treatment compresses 36px headings to 1.2 line height and uses -0.01em body tracking; it is not the default light-page recipe.

## Layout

**Density:** Airy at section level, with compact controls and practical dense comparison rows.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-description and stacked detail gaps. |
| 16px | Hero title-to-support gap and pricing-column gutters. |
| 24px | Card-grid gutters, form row gaps and FAQ padding. |
| 32px | Support-to-action spacing in recurring heading groups. |
| 48px | Major content-group separation. |
| 64px | Default feature-section top and bottom padding. |
| 80px | Space before gallery media and above the closing panel. |
| 128px | Spacious dark benefit-chapter padding. |
| 160px | Extended chapter breathing room and resource-section lead-in. |
| 176px | Opening text clearance beneath navigation. |

### Containers and grids

- **content**: max width 1200px · side padding 30px. Centered desktop content rail; at 1440px the main media and card grids sit 120px from either edge.
- **heading block**: max width 900px · side padding 20px. Centered section title and support, independent of wider media.
- **hero title**: max width 996px · side padding 34px. Two-line centered promise over a 780px support line.
- **resource grid**: max width 1200px · 3 columns · gap 24px. Three equal 384px cards with copy above bottom-anchored imagery.
- **feature stage**: max width 1200px · 2 columns · gap 126px. 384px selection rail at left, 690px-wide 16:9 media at right; align to the first expanded item.
- **footer grid**: max width 1072px · 6 columns · gap 10px. Six left-aligned 170px link columns nested inside the main rail.
- **plan grid** (only for pricing pages): max width 1264px · 4 columns · gap 16px. Four equal 304px tier cards with bottom-aligned actions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | cards | 12px |
|  | product frame | 18px |
|  | closing panel | 20px |
| lead-generation sections | form panel | 16px |
| pricing comparison navigation | filters | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| resource edge | `rgba(0, 0, 0, 0.08) 0px 3px 12px 0px, rgba(0, 0, 0, 0.2) 0px 0px 2px 0px` | Subtle lift plus a fine contact edge on translucent cards and closing panels. |
| interface edge | `rgba(0, 0, 0, 0.01) 0px 0px 3px 8px, rgba(0, 0, 0, 0.12) 0px 0px 4px 0px` | Large white demonstration frame. |

### Surfaces

#### Canvas · level 0

**Use:** Default light page.

**CSS:** `background: #ffffff; color: #181818`

#### Pastel atmosphere · level 0

**Use:** Opening and selected proof or closing sections.

**CSS:** `background-color: #ffffff; background-image: radial-gradient(47.72% 108.66% at -12.1% 21.18%, rgba(129, 219, 219, 0.25) 24.27%, rgba(160, 232, 232, 0) 100%), radial-gradient(76.64% 192.13% at 107.15% 116.7%, rgba(255, 178, 167, 0.25) 0%, rgba(201, 191, 255, 0.25) 74.61%); mask-image: linear-gradient(rgba(0,0,0,0) 0%, rgba(0,0,0,0) 10%, rgba(0,0,0,1) 25%, rgba(0,0,0,1) 75%, rgba(0,0,0,0) 90%, rgba(0,0,0,0) 100%)`

**Observed:** An independent background layer fades at both ends, behind content that stays fully opaque.

**Transfer:** Apply the mask only to the background layer. Keep the middle soft and the edges luminous, not rainbow-striped.

#### Violet theater · level 0

**Use:** Immersive product demonstration.

**CSS:** `background: #1a1935; color: #ffffff`

**Observed:** The lower field becomes a violet glow behind dimensional objects; the demonstration stays visually dominant.

**Transfer:** Use this contrast break for the strongest proof scene rather than every section.

#### Translucent card · level 1

**Use:** Resources and closing invitations over pastel light.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 12px; box-shadow: rgba(0, 0, 0, 0.08) 0px 3px 12px 0px, rgba(0, 0, 0, 0.2) 0px 0px 2px 0px`

**Observed:** The background hue remains visible through a pale card with a restrained contact edge.

**Transfer:** Reserve stronger blur for media captions; these light cards need no heavy frosting.

#### Product frame · level 1

**Use:** Large working-interface demonstration.

**CSS:** `background: #ffffff; border-radius: 18px; box-shadow: rgba(0, 0, 0, 0.01) 0px 0px 3px 8px, rgba(0, 0, 0, 0.12) 0px 0px 4px 0px; overflow: hidden`

#### Media caption glass · level 2

**Use:** Caption and actions inset over demonstration footage.

**CSS:** `background: rgba(0, 0, 0, 0.2); border-radius: 12px; backdrop-filter: blur(10px); padding: 16px 24px; color: #ffffff`

#### Pricing atmosphere · level 0

**Only for:** pricing pages

**Use:** Tier selection and competitive comparison.

**CSS:** `background-image: radial-gradient(50% 80% at 0% 50%, #fff8e7 0%, rgba(255,255,255,0) 100%), radial-gradient(50% 80% at 100% 50%, #ebe4ff 0%, rgba(255,255,255,0) 100%)`

**Observed:** Cream enters from the left and lilac from the right, leaving the center almost white.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #8169ff; color: #ffffff; border-radius: 4px; padding: 14px 16px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 600 · 18px/1.4

**Observed:** Text-width button centered under the promise. Pricing variants fill the available card width; a low-priority free tier uses an outlined violet action.

**Transfer:** Use one principal next step per heading group.

### Compact button

**Use:** Navigation conversion and section actions.

**CSS:** `background: #8169ff; color: #ffffff; border-radius: 4px; padding: 12px 16px; display: inline-flex; justify-content: center; align-items: center`

**Text style:** `action-sm` — Inter 600 · 16px/1.4

**Observed:** The header instance is 40px tall with vertically centered text; standalone section instances are about 46px tall. Keep the header height constrained rather than deriving it only from padding.

### Navigation item

**Use:** Persistent desktop navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 4px 20px; height: 60px; gap: 10px; color: #181818`

**Text style:** `nav` — Figtree 700 · 16px/1.4 · capitalize

**Observed:** Small solid down-triangles follow menu labels. Logo anchors the left; a violet text action and Compact button balance the right. The ordinary landing header is a centered white 1200px bar; immersive openings use a full-width dark-compatible variant.

### Arrow link

**Use:** Secondary exploration inside feature and resource blocks.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; padding-bottom: 16px; color: #8169ff`

**Text style:** `action-sm` — Inter 600 · 16px/1.4

**Observed:** An 18px right-arrow follows the label; it reads as a text action, not a bordered button.

### Feature selector

**Use:** Active capability in a vertical demonstration rail.

**CSS:** `background: #f5f5f5; border-radius: 12px; overflow: hidden`

**Text style:** `item-heading` — Figtree 700 · 22px/1.4

**Observed:** The expanded item is 384px wide with 22px internal padding, an 8px gap, body explanation and Arrow link. Other rows retain only the bold title on white; the related media sits on the right.

**Transfer:** Expand one capability at a time rather than presenting six equally detailed cards.

### Resource card

**Use:** Three-way routes to learning or deeper exploration.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 12px; box-shadow: rgba(0, 0, 0, 0.08) 0px 3px 12px 0px, rgba(0, 0, 0, 0.2) 0px 0px 2px 0px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `card-heading` — Figtree 700 · 28px/1.4

**Observed:** A 384px by 386px card places a title, short body and Arrow link in the upper area with 22px inset; a 384px-wide illustration occupies the lower half. Tier variants use opaque white and interface collages instead of toy objects.

### Closing panel

**Use:** Decorated conversion destination.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 20px; box-shadow: rgba(0, 0, 0, 0.08) 0px 3px 12px 0px, rgba(0, 0, 0, 0.2) 0px 0px 2px 0px; max-width: 1200px; padding: 40px 0; display: flex; flex-direction: column; align-items: center; gap: 32px; overflow: hidden`

**Text style:** `heading` — Figtree 700 · 48px/1.3

**Observed:** A 508px-tall pale stage. Centered heading, three short checkmarked reassurances, compact action and a smaller secondary invitation sit inside a perimeter of floating playful objects.

### FAQ row

**Use:** Objection handling near the ending.

**CSS:** `padding: 24px; display: flex; align-items: center; color: #181818`

**Text style:** `faq-question` — Inter 700 · 18px/1.4

**Observed:** Default question rows are about 73px tall in a 993px rail, separated by faint rules. Answers use body-lg and retain text links. The AI feature variant widens to 1184px, uses feature-faq and more separation.

**Transfer:** Keep answers collapsed initially; avoid making the whole ending a wall of expanded prose.

### Footer column

**Use:** Shared informational ending.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 32px; width: 170px`

**Text style:** `item-heading` — Figtree 700 · 22px/1.4

**Observed:** Bold title above a stack of small gray links separated by 24px. Six columns occupy a white rail; the lower row aligns social icons left, legal information centrally and language selection right.

### Footer link

**Use:** Low-emphasis navigation in the closing directory.

**CSS:** `color: #636363; text-decoration: none`

**Text style:** `small` — Inter 400 · 14px/1.4

**Observed:** Plain gray label without a button surface.

**States:** Declared: hover color #8169ff and no underline; focus-visible not specified.

### Plan card

**Only for:** pricing pages

**Use:** Tier selection.

**CSS:** `background: rgba(255, 255, 255, 0.2); border: 2px solid #ffffff; border-radius: 12px; box-shadow: rgba(0, 0, 0, 0.08) 0px 0px 18px 0px; padding: 18px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `plan-label` — Figtree 700 · 24px/1.4

**Observed:** Equal 304px by 600px columns. Violet plan name, subheading-sized amount, concise checkmarked inclusions and add-ons precede bottom-aligned actions. A small dark-violet popularity badge differentiates a recommended paid tier.

### Lead form panel

**Only for:** lead-generation sections

**Use:** Sales inquiry after industry-specific proof.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; gap: 36px; overflow: hidden`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** A 1072px white form sits on a saturated violet band. Heading and response reassurance precede two-column labeled fields, full-width message area, consent copy and submit. Standard fields are 56px high with 4px corners and a thin gray outline; the calculator variant uses softer filled 40px fields.

## Imagery and graphics

### Readable product demonstration

**Use:** Opening object and capability chapters.

**Observed:** A broad white desktop editor with fine gray chrome fills the 1200px stage. Later examples mix software views with hands touching tablets, dashboard interfaces and working devices; video panels are typically 690px by 388px and remain brighter than their surroundings.

**Transfer:** Show the new product doing one understandable task. If no functioning demo exists, compose a believable interface with one clear input and result rather than a generic dashboard collage.

### Pastel light fields

**Use:** Signature atmosphere behind the opening, proof and closing.

**Observed:** Mint enters from one outside edge, peach and lavender from the other; the center stays pale and the wash fades into white vertically.

**Transfer:** Recreate the atmosphere with CSS gradients independent of the subject matter; match the soft glow rather than emphasizing exact stops.

**Build:** Place an absolute full-section layer behind content. Layer broad radial ellipses centered just outside the left and right edges: mint rgba(129,219,219,0.25), peach rgba(255,178,167,0.25), lavender rgba(201,191,255,0.25). Fade each toward transparent; apply a vertical alpha mask clear at 0–10% and 90–100%, opaque at 25–75%. Keep the content above the masked layer.

### Soft object metaphors

**Use:** Signature punctuation on resource cards, proof stages and the closing invitation.

**Observed:** Rounded cream and lavender objects, coral accents, soft studio shadows and smooth matte-to-satin highlights. Books, hands, a magnifier, rocket and abstract blobs are cropped at card edges or float around an empty center, never covering the conversion text.

**Transfer:** Create new metaphors from the product's user outcomes. Minimum treatment is a few softly shaded spheres, rings and rounded cuboids with the same light and perimeter placement.

**Build:** Use SVG shaded ellipses and rounded rectangles or simple 3D primitives. Combine cream bodies with lavender rings or handles and one coral accent. Put highlights at upper left, soft dark contact shadows below, and rotate each group slightly. Arrange 3–5 unequal objects around a 1200px panel's perimeter, clipping the larger lower-corner objects; preserve a broad clear central text area.

### Customer proof stage

**Use:** Testimonial presentation between product promise and detailed capabilities.

**Observed:** A horizontal chain of circular white customer discs connected by thin progress lines sits above a centered translucent testimonial. A small portrait and identity precede a quote with brief bold emphasis, then a large playable product story. Handwritten notes and soft objects occupy the outer margins.

**Transfer:** Use verified customer material or a clearly labeled user story. Preserve the disc-and-stage composition even when the proof is a single story; do not manufacture endorsements.

**Build:** Use 127px white circular discs with a faint ambient shadow and 120px spacing. Connect their centers with thin gray lines, coloring the active segment violet. Below, use a 20px rounded pale panel with 32px inset and a media rectangle; keep decorative objects outside its text area.

### Immersive violet hardware scene

**Only for:** hardware-oriented feature openings

**Use:** A more cinematic alternative to the centered light opening.

**Observed:** A large perspective monitor is cropped off the right edge, accompanied by phone, watch and keyboard. Violet rim lighting unifies the devices against midnight purple; left-aligned white copy and a translucent testimonial remain readable on the left.

**Transfer:** Use a three-quarter view of the relevant tool or connected system. A single well-lit device plus a readable product screen is sufficient; avoid filling the scene with unrelated gadgets.

### Icons

**Observed:** Simple solid silhouettes rather than elaborate outlined pictograms. Small right-arrows are 18px; navigation triangles are 8px by 6px. Violet circular checkmarks mark benefits; footer social marks are compact monochrome symbols.

**Transfer:** Use recognizable solid category symbols in selected tiles, small violet arrow links and a consistent checkmark family. Preserve the light visual weight of utility chevrons.

## Section recipes

How recurring sections are built.

### First screen: Working product opening

**Observed:** A centered white navigation bar floats above an exceptionally open introduction. Back to front: white canvas, pale mint/lavender/peach atmosphere, centered dark display title spanning about two thirds of the width, a narrower two-line lead 16px below it, then Primary button. The title uses display at 62px/80px with natural tracking; the content begins with 176px of top clearance below the section edge. The action sits well clear of the support text. A hand-note invitation introduces the 1200px Product frame below, separated from the introductory block by 48px. In the first 900px, navigation, title, support, action, handwritten invitation and the upper part of the interface are visible; the full working stage and trust logos continue below.

**Transfer:** Use a short category promise and one concrete demonstration. Without bespoke media, show a carefully authored interface state in Product frame, not a decorative blank rectangle. Hardware feature pages can use a left-aligned 48px title beside a violet-lit object; immersive feature campaigns use centered white display text over darkened motion. Pricing opens with a centered title, compact billing toggle and four comparable cards.

**Avoid:** Do not replace this opening with a left-copy/right-thumbnail template, a giant logo sculpture or a full-screen saturated gradient that hides the product.

**Text style:** `display` — Figtree 700 · 62px/80px

### Heading pair

**Observed:** A centered heading block uses heading, then lead after 8–16px, with an optional action about 32px lower. Copy sits within 900px, and the wider demonstration or grid begins around 48–80px later.

**Transfer:** State one benefit per chapter; let the wider content prove it. Industry variants emphasize just one meaningful phrase in violet.

**Text style:** `heading` — Figtree 700 · 48px/1.3

### Violet demonstration theater

**Observed:** Violet theater interrupts the white page with a white heading, six compact category tiles and a central 680px by 401px media panel. An oversized lavender physical object peeks from behind the media; Media caption glass anchors a short claim and paired actions near the lower edge.

**Transfer:** Give a key use case a theatrical setting, using category labels relevant to the new product. Maintain a real demonstration as the focal point, with one shaded object behind it.

### Selectable capability stage

**Observed:** Heading pair above a Feature selector rail and a 690px-wide demonstration. One expanded gray item contains body and Arrow link; the remaining items are title-only rows. Content sits within the 1200px rail with 64px section padding.

**Transfer:** Use for related capabilities that share one changing media area, rather than a grid of repetitive screenshots.

### Resource trio

**Observed:** Heading pair leads to three Resource cards separated by 24px over Pastel atmosphere. Titles and descriptions align at the top; soft object illustrations are cropped into the bottom half.

**Transfer:** Offer three different next steps with comparable description lengths and distinct metaphors.

### Split proof chapters

**Observed:** Light industry stories alternate 545px by 306px imagery and text, with 36px subheadings, body paragraphs, a short bold lead-in and Arrow link. Dark feature chapters instead retain media on the left at 424px by 318px and a wider text column on the right, using dark-heading, dark-body and three concise bullets.

**Transfer:** Use alternating light rows for case-driven narratives; keep a consistent left-media pattern inside an immersive feature sequence.

### Objections and endings

**Observed:** FAQ row lists resolve purchase and usage questions. Feature and pricing paths can proceed directly from FAQs to the white footer. A feature-campaign ending uses a 1184px-wide, 358px-tall rounded dark-to-violet demo invitation with white heading and support. The default landing ending is Closing panel over Pastel atmosphere, followed by a white footer with 104px top and 108px bottom breathing room.

**Transfer:** Choose the closing variant appropriate to user intent, retain a distinct invitation stage for general landing pages, and always finish with the shared directory rather than extending the colored background through it.

### Quantified proof and inquiry

**Only for:** industry solution pages

**Observed:** Three violet 64px stat values form a centered row with gray captions and 64px group gaps. A white calculator panel follows. Later, a saturated violet band holds a centered white invitation above Lead form panel.

**Transfer:** Use independently defensible result metrics followed by a relevant interactive calculation or inquiry. Keep the long form specific to high-intent pages.

### Comparison system

**Only for:** pricing and comparison pages

**Observed:** Plan card grid introduces the offering. Detailed matrices use a wide label column, centered values, small checks, 40px rows and 24px category labels. A floating rounded filter strip and persistent tier actions help navigation. A separate competitive comparison gives the central recommendation an uninterrupted violet column while alternatives stay pale.

**Transfer:** Separate fast tier selection from exhaustive evaluation. Keep the featured column exceptional rather than tinting every cell.

## Page flow

**Storyline:** Promise → tangible demonstration → trusted proof → capability depth → evaluation or learning → resolved objections → relevant invitation → shared directory.

### Broad product landing page

1. **Promise** — Centered benefit/category headline and one free-start action above a working product stage.
2. **Social proof** — Muted logo rows followed by a dark use-case theater and richer customer-story stage.
3. **Capability depth** — Selectable feature rail, comparison invitation and illustrated resource trio.
4. **Inspiration** — Wide gallery of device and interface examples.
5. **Closing call** — Decorated translucent conversion panel, then six-column white footer.

**Transfer:** Move between doing, proof and exploration; retain the playful invitation and clear product object without copying the original topics.

### Connected-system feature page

1. **Promise** — Left-aligned white headline and download action beside violet-lit hardware; testimonial at the bottom of the opening.
2. **Use cases** — Hands-on media next to expandable application descriptions.
3. **Evaluation** — Three tier cards, feature rail and compact enterprise sales prompt.
4. **Context** — Horizontal ecosystem diagram and dark course invitation.
5. **Objection handling** — Pale atmospheric FAQs followed directly by the shared white footer.

**Transfer:** Explain how a specialized feature fits a larger workflow, then remove adoption friction instead of repeating a generic final signup panel.

### Focused intelligent-feature campaign

1. **Promise** — Centered white headline over dim product motion with filled and outlined actions.
2. **Capability chapters** — Three dark media/text benefits with short bullet lists.
3. **Trust** — Light audience cards and controllability assurances.
4. **Evaluation** — Sparse comparison table and spacious FAQ rows.
5. **Closing call** — Rounded violet-gradient demo panel followed by the common footer.

**Transfer:** Use the dark opening and chapters for a single focused feature, returning to light surfaces for trust and evaluation.

### Industry-specific sales page

1. **Promise** — Dark video opening with centered benefit headline and four immediate outcome checks.
2. **Proof** — Hands-on product film, enterprise assurances, logo rail and attributed quote.
3. **Problem solution** — Alternating image/text stories map common problems to concrete outcomes.
4. **Capability depth** — Selectable feature stage.
5. **Quantified proof** — Violet result figures and calculator inquiry.
6. **Education** — Two demo cards and a horizontal resource collection.
7. **Closing call** — Full violet contact band containing a large white two-column form, then the white footer.

**Transfer:** Pair specialist vocabulary with real physical context, verifiable proof and an appropriately high-intent conversion.

### Pricing and detailed evaluation

1. **Selection** — Centered title and billing toggle above four pale tier cards.
2. **Evaluation** — Long grouped feature matrix with persistent tier actions and floating category filters.
3. **Add-on evaluation** — Second matrix for optional capabilities.
4. **Differentiation** — Competitive comparison with a saturated central recommendation.
5. **Objection handling** — Muted trust logos and FAQs; shared footer closes without a separate signup banner.

**Transfer:** Let the opening cards support a quick choice and the matrices support due diligence. Preserve the restrained white canvas despite the information density.

## Writing

Confident and encouraging, with practical details beneath ambitious benefit claims. The tone is accessible to designers while remaining specific enough for professional evaluation.

**Do not copy:** Do not reuse ProtoPie names, logos, illustrations, customer identities, quotations, rankings, prices, performance statistics or compliance claims. Source examples illustrate sentence structure only; all new claims and proof must belong to the new product.

- **Addressing the reader:** Address the reader as you or your team. Name the product in descriptive explanations; use our sparingly for resources or experts.
- **Rhythm:** Short benefit-led headlines, often paired clauses or three-part promises. Support lines usually form one sentence; feature explanations name actions and concrete mechanisms. Actions use short verbs; FAQs use natural questions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Category authority or paired outcome statements. | 4–9 words | “#1 AI-driven advanced prototyping software”<br>“Effortless Start. Flawless Finish.” |
| Section heading | Lead with an improvement, then name the task or audience. | 5–10 words | “Powerful features for highest fidelity”<br>“Built for designers. Trusted by teams.” |
| Supporting line | Explain the promise with observable actions, not another abstract slogan. | 12–25 words | “Connect your prototypes to multiple screens, custom hardware, APIs, and more.” |
| Capability title | Plain noun phrase or direct imperative describing the gain. | 2–5 words | “Dynamic interactions”<br>“Cut the learning curve” |
| Primary action | Verb plus immediate next step; lower the commitment when true. | 2–5 words | “Get started for free”<br>“Book a Demo” |
| Objection handling | Ask the user's practical question directly. | 7–13 words | “Can I edit and refine AI-generated interactions?” |
| Closing invitation | Action plus a near-term time cue. | 3–6 words | “Start prototyping today” |

**Words and phrasing to use:** Create; Explore; Connect; real; dynamic; your team; control; refine; Learn More

**Avoid:** paradigm shift; synergy; revolutionary ecosystem; mysterious technical acronyms without context; slang-heavy hype

**Rules:**

- Follow an ambitious headline with a mechanism or concrete user action.
- Use brief reassurance close to conversion rather than long persuasive paragraphs.
- Describe what remains editable or controllable when explaining automation.
- Reserve emphatic bold fragments in testimonials or paragraphs for one meaningful outcome.
- Use domain-specific nouns in specialist sections, not in every general headline.

## Do's and Don'ts

### Do

- Use 62px bold Figtree for the opening promise and 48px for recurring major headings.
- Keep the main demonstration and card grids on the 1200px rail.
- Let 24px gutters separate equal resource cards while their text stays left aligned.
- Use 4px corners for primary actions against softer 12–20px panels.
- Give the active feature item a #f5f5f5 backing and leave inactive titles on white.
- Preserve the pastel glow, violet theater and playful perimeter objects as distinct signature devices.
- Keep footer hierarchy strong: 22px headings above 14px gray links.
- Keep numerical proof violet and oversized, with modest gray explanation below.

### Don't

- Do not use pill-shaped primary conversion buttons; pills belong to filters and billing controls.
- Do not replace the Figtree/Inter pairing with a condensed display face or a mono-heavy technical aesthetic.
- Do not turn all white sections into individually bordered dashboard cards.
- Do not use saturated mint or coral as competing button colors; they belong to light and imagery.
- Do not enlarge secondary arrow links into full-width colored bars.
- Do not use equal shadow strength everywhere; working media, light resources and flat feature selectors have different depth.
- Do not run dense comparison typography through spacious narrative sections; 14px values belong to evaluation details.
- Do not make the footer a dark continuation of the theater; its shared white directory is a deliberate reset.

## Motion and responsive

### Motion

**Observed:**

- Product footage and changing demonstration states supply visible motion.
- Navigation persists as a white bar during scrolling; immersive openings can start with dark-compatible navigation.
- Footer links declare violet hover with no underline. No action or surface transition timings are specified.

**Transfer:**

- Keep media changes within the stable demonstration frame and reserve immersive motion for product proof.
- Maintain a readable header and caption layer while the underlying product scene changes.

**Unknown:**

- Autoplay behavior, carousel timing, scroll choreography, transition duration and easing for marketing interactions are not established.

### Responsive

**Observed:**

- Width breakpoints cluster around 810px, 1024px and 1200px; a feature campaign adds boundaries near 767px and 832px.

**Transfer:**

- On narrower screens, stack the feature rail before its media and retain one expanded item.
- Keep object decoration at the edges and reduce its footprint before compromising the centered promise or action.
- Allow pricing comparison to retain readable aligned columns rather than compressing every value; provide an intentional narrow-screen navigation treatment.

**Unknown:**

- Exact mobile type sizes, header menu construction, stacking order and table overflow behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
