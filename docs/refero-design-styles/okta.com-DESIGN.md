# Okta — luminous enterprise editorial

## Overview

An enterprise technology style with an unexpectedly literary serif voice and electric blue light. Warm off-white and stone canvases carry spacious explanations, while luminous interface sculptures, natural workplace photography, and dark blue feature moments give the technology a tangible presence. Rounded panels and floating charcoal navigation keep the experience approachable without losing its institutional confidence.

### Essentials

- Literary headlines over technical substance: SeasonMix at 56px/1.14 for the opening, 48px/1.16 for section leads, and 40px/1.2 for capability chapters, all weight 400 with normal tracking; Aeonik carries explanations.
- The default opening is a light, two-sided product stage: a 632px text column beside a floating interface sculpture, within 1312px of content and 64px side gutters. A blue-violet light wash sits behind the navigation and fades into off-white beneath the headline.
- Navigation floats as two separate dark glass capsules: 80px tall, 40px corners, rgba(0,0,0,0.66), and 22px backdrop blur; only its conversion action is a vivid blue pill.
- Actions are sturdy rounded rectangles, not generic pills: 64px tall with 8px corners, 20px/32px medium labels, and 48px horizontal padding. Pair near-black fill with a 1.5px outlined alternative; reserve pill geometry for navigation.
- Color behaves like illumination rather than a page-wide paint bucket: off-white and stone dominate the reading sections; saturated blue occupies media stages, selected controls, and bounded promotional moments. Every new landing page includes a blue-lit product scene and an atmospheric closing treatment.
- Interfaces become physical objects: white panels float in shallow perspective with blue edges, soft grounding shadows, and smaller overlapping callouts. Use a simplified working model with two or three meaningful data panels when no polished product artwork exists.
- Large containers feel architectural while cards feel practical: 32px corners on chapter enclosures, 24px on photographic proof, 16px on resource cards, with 32px card gaps and 128px separations between major narrative blocks.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0131ff` | `--color-blue` | action, accent, link | Navigation conversion fill, link hover, selected controls, and graphic illumination. |
| Deep blue stage | `#00033e` | `--color-navy` | background, surface | Dark editorial billboards and backing for luminous product graphics. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Reverse lavender link | `#99a7f1` | `--color-lavender-link` | link | Article links on deep blue surfaces. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action black | `#111111` | `--color-button-ink` | action, background | Default filled conversion buttons on light surfaces. |
| Outline charcoal | `#191919` | `--color-outline-ink` | border, text | Outlined action edges and labels. |
| Warm link ink | `#201b16` | `--color-link-ink` | link | Underlined editorial links on light backgrounds. |
| Heading charcoal | `#1e1e1e` | `--color-ink` | text, background, border | Headings, accordion rules, and the full-width footer. |
| Body charcoal | `#383838` | `--color-body` | text | Longer marketing paragraphs and supporting text. |
| Muted grey | `#555555` | `--color-muted` | text | Uppercase overlines and secondary text. Black at 66% opacity on the off-white canvas has a similar visible tone. |
| Medium hairline | `#ababab` | `--color-rule` | border, text | Tab and catalogue separators; footer column headings. |
| Reverse paragraph grey | `#e5e5e5` | `--color-reverse-body` | text | Supporting text on dark blue graphics. |
| Warm stone | `#ece8e4` | `--color-stone` | surface, background | Resource cards, pricing cards, and large explanatory enclosures. |
| Off-white canvas | `#fbfbfa` | `--color-canvas` | background, text, action | Default page canvas; also reverse text and light buttons on dark backgrounds. |
| Warm reverse white | `#fffefa` | `--color-warm-white` | text | Labels on dark filled buttons and subtle reverse details. |
| Pure white | `#ffffff` | `--color-white` | text, border | Navigation labels, large reverse statistics, and translucent glass edges. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial resource sections | Pale blue divider | `#b6caff` | `--color-blue-rule` | border | Fine separators in editorial proof and category navigation. |

## Typography

- **Aeonik** — Body copy, controls, overlines, resource headings, and statistical emphasis. A clean geometric grotesk with open, rounded forms; regular paragraphs and medium controls. If unavailable, use **DM Sans**. Use weights 400 and 500; preserve the relatively open body setting. Font stack: "Aeonik", "DM Sans", "Helvetica Neue", sans-serif.
- **SeasonMix** — Primary headlines, section titles, feature headings, and plan names. A low-contrast editorial serif with gently flared terminals and a contemporary, almost sans-like openness. If unavailable, use **Lora**. Use 400 for headings and 500 for plan names; tune line breaks to retain the broad editorial silhouette. Font stack: "SeasonMix", "Lora", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | SeasonMix | 400 | 56px | 1.14 | normal | Default opening headline and prominent closing call. |
| heading-lg | SeasonMix | 400 | 48px | 1.16 | normal | Major section headings and secondary promotional banners. |
| heading | SeasonMix | 400 | 40px | 1.2 | normal | Capability chapters and smaller section leads. |
| card-heading | SeasonMix | 400 | 32px | 1.25 | normal | Feature cards, editorial cards, and expandable benefit titles. |
| billboard-heading | Aeonik | 400 | 32px | 1.36 | -0.005em | Short article-billboard headlines and large explanatory statements. |
| lead | Aeonik | 400 | 24px | 1.35 | normal | Opening support line and large section introductions. |
| resource-heading | Aeonik | 500 | 24px | 1.35 | normal | Text-only resource cards and compact benefit headings. |
| body | Aeonik | 400 | 20px | 1.4 | 0.004em | Default feature explanations and card descriptions. |
| button | Aeonik | 500 | 20px | 1.6 | 0.008em | Large conversion actions. |
| question | Aeonik | 500 | 20px | 1.4 | 0.004em | FAQ questions and reverse article links. |
| footer-heading | Aeonik | 400 | 20px | 1.4 | 0.005em | Muted footer column titles. |
| text-link | Aeonik | 500 | 18px | 25px | 0.028em | Underlined editorial actions. |
| eyebrow | Aeonik | 500 | 16px | 22px | 0.12em, uppercase | Chapter questions, content types, and compact section labels. |
| nav-label | Aeonik | 500 | 16px | 1.4 | 0.0125em | Desktop navigation labels and its conversion control. |
| detail | Aeonik | 400 | 16px | 1.4 | 0.0125em | FAQ answers, catalogue descriptions, and supporting detail. |
| footer-link | Aeonik | 500 | 16px | 26px | 0.0125em | Footer destination links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| photographic quantified proof | photo-stat | Aeonik | 500 | 80px | 1.1 | 0.001em | One large proof metric inside a photographic customer-story panel. |
| pricing pages | pricing-display | SeasonMix | 400 | 64px | 1.12 | normal | Short pricing-page opening. |
| pricing pages | plan-name | SeasonMix | 500 | 40px | 1.2 | normal | Plan titles above price or inquiry text. |
| broad campaign landing pages | compact-close-heading | Aeonik | 400 | 32px | 38px | -0.005em | Short translucent closing-choice cards. |

**Notes:**

- The serif is the principal marketing voice, not a decorative accent confined to the opening. Keep it regular rather than turning titles into bold enterprise sans headings.
- Body copy is unusually substantial at 20px; the 24px lead remains visibly subordinate to the 56px headline. Use 16px detail only for dense explanatory content.
- Serif tracking stays normal. Technical overlines expand to 0.12em while 32px sans billboard titles tighten slightly to -0.005em.
- Use sentence case for headings and controls. Uppercase belongs to small overlines, not paragraph copy.

## Layout

**Density:** Airy at section level, with readable medium-density explanations inside cards and feature chapters.

### Spacing

**Spacing system:**

- **layout step** 8px — Primary structural cadence for section padding, card gutters, and content gaps; 12px and 24px provide intermediate optical spacing.

| Value | Use |
| --- | --- |
| 12px | Small icon-to-label gaps and compact link groups. |
| 16px | Eyebrow-to-title and title-to-body gaps; paired action gap. |
| 24px | Hero heading-to-lead separation and pricing-card padding. |
| 32px | Default grid gaps and resource-card inner padding. |
| 40px | Outer inset for large chapter enclosures. |
| 48px | Wide button horizontal padding and image-to-content spacing. |
| 64px | Desktop page gutters, chapter separations, and opening inner padding. |
| 96px | Top and bottom padding of immersive chapter bands. |
| 112px | Wide two-column feature gap. |
| 128px | Major section separation. |

### Containers and grids

- **page shell**: max width 1440px · side padding 64px. Centered desktop shell producing 1312px of usable content.
- **opening text**: max width 632px. Left-aligned headline, lead, and actions balanced against a product scene of similar width.
- **chapter enclosure**: max width 1360px · side padding 64px. Broad rounded band inset 40px from the desktop viewport; inner content spans 1232px.
- **feature split**: max width 1312px · 2 columns · gap 112px. Equal media-and-copy columns with vertically centered text. Inside an inset enclosure the columns are 560px wide.
- **resource grid**: max width 1312px · 3 columns · gap 32px. Equal 416px text or media cards.
- **faq split**: max width 1312px · 2 columns · gap 32px. Short title on the left; a wider 853px accordion on the right.
- **plan grid** (only for pricing pages): max width 1312px · 4 columns · gap 24px. Four equal 310px pricing columns.
- **benefit grid** (only for solution and industry pages): max width 1312px · 4 columns · gap 112px. Narrow 244px explanatory columns without card boxes.

## Corner radius

| Element | Radius |
| --- | --- |
| conversion buttons | 8px |
| resource cards | 16px |
| photographic proof | 24px |
| chapter enclosures | 32px |
| navigation capsules | 40px |
| navigation conversion | 30px |
| carousel arrows | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | navigation | `0px 1px 24px 0px rgba(25,25,25,0.1)` | Soft elevation beneath dark navigation capsules. |
| customer-story carousels | photographic carousel | `0px 10px 30px 0px rgba(0,0,0,0.3)` | Grounding for the large image panel and its receding neighbours. |
| broad campaign landing pages | closing choice | `0px 24px 40px 0px rgba(0,0,0,0.08)` | Soft lift beneath translucent closing cards. |

### Surfaces

#### Canvas · level 0

**Use:** Default reading background.

**CSS:** `background: #fbfbfa; color: #383838`

#### Stone chapter · level 0

**Use:** A bounded explanatory chapter containing media and copy.

**CSS:** `background: #ece8e4; border-radius: 32px`

**Observed:** A large inset enclosure; long product chapters carry a faint blue-violet edge glow. A full-width stone band is also used for product announcements.

**Transfer:** Use for a connected group of capabilities rather than wrapping every section.

#### Resource card · level 1

**Use:** Practical text-first reading and conversion cards.

**CSS:** `background: #ece8e4; border-radius: 16px; box-shadow: none`

**Observed:** Flat warm material with no outline; a fixed inner structure keeps actions at the bottom.

**Transfer:** Retain the quiet flat surface even when adding a thumbnail.

#### Navigation glass · level 2

**Use:** Floating persistent navigation.

**CSS:** `background: rgba(0,0,0,0.66); border-radius: 40px; backdrop-filter: blur(22px); box-shadow: 0px 1px 24px 0px rgba(25,25,25,0.1)`

**Observed:** Two independent dark translucent capsules reveal the changing background through them.

**Transfer:** Keep the left destination group separate from the right conversion group.

#### Deep blue billboard · level 1

**Use:** An editorial story beside a luminous technical illustration.

**CSS:** `background: #00033e; color: #fbfbfa`

**Observed:** The text half joins an illustrated half inside one 32px rounded container. It uses muted reverse paragraphs and lavender links.

**Transfer:** Keep it a bounded interruption in an otherwise light page.

#### Frosted closing panel · level 1

**Use:** Default product-page closing conversion stage.

**CSS:** `background: linear-gradient(182deg, rgba(236,232,228,0.8) 1.24%, rgba(250,250,249,0) 102.15%); border: 1px solid rgba(255,255,255,0.7); border-radius: 32px; backdrop-filter: blur(12px); padding: 0px 64px`

**Observed:** A 1312px-wide panel sits over atmospheric color within a 522px full-width closing band.

**Transfer:** Pair a single serif promise with a short lead and two actions.

#### Footer charcoal · level 0

**Use:** Full-width institutional ending.

**CSS:** `background: #1e1e1e; color: #fbfbfa`

**Observed:** Disclosure text, when needed, shares the footer material rather than floating on the light canvas.

**Transfer:** Use this consistent dark landing zone after the colored closing stage.

#### Navy glass category · level 1

**Only for:** broad portfolio presentations

**Use:** Large category cards over an immersive blue scene.

**CSS:** `background: rgba(0,3,62,0.6); border-radius: 16px; backdrop-filter: blur(15px); padding: 32px`

**Observed:** Three tall cards sit over a shared dimensional graphic; light objects remain softly visible through their lower areas.

**Transfer:** Reserve this darker glass for visually immersive category navigation.

#### Translucent closing choice · level 1

**Only for:** broad campaign landing pages

**Use:** Compact next-step cards above a soft multicolor horizon.

**CSS:** `background: rgba(255,254,250,0.5); border-radius: 8px; box-shadow: 0px 24px 40px 0px rgba(0,0,0,0.08)`

**Observed:** Three shallow cards use sans headings and short descriptions; the colorful backing is stronger beneath than above them.

**Transfer:** Offer distinct levels of commitment, with the entire card acting as a destination.

## Components

### Floating navigation

**Use:** Primary site destinations and conversion group.

**CSS:** `display: flex; align-items: center; gap: 40px; height: 80px; padding: 0px 24px; background: rgba(0,0,0,0.66); border-radius: 40px; backdrop-filter: blur(22px); box-shadow: 0px 1px 24px 0px rgba(25,25,25,0.1)`

**Observed:** Logo and destinations share the larger left capsule; trial and contact actions occupy a smaller separate right capsule. A slim utility strip sits above the opening, while the capsules remain visible through later sections.

**Transfer:** Use the new brand's compact identity at the left and keep the central space between capsules open.

### Navigation item

**Use:** Compact top-level destination control.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 4px 12px; border: 1px solid transparent; border-radius: 15px; color: #ffffff`

**Text style:** `nav-label` — Aeonik 500 · 16px/1.4 · tracking 0.0125em

**Observed:** Labels are plain sentence-case words with no permanent underline.

**States:** Declared: hover background #0131ff and color #fbfbfa; focus-visible outline #0131ff solid 3px with 2px offset.

### Navigation conversion

**Use:** Persistent high-priority contact destination.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 56px; padding: 18px 16px; background: #0131ff; color: #fbfbfa; border-radius: 30px`

**Text style:** `nav-label` — Aeonik 500 · 16px/1.4 · tracking 0.0125em

**Observed:** A small blue pill is nested inside the dark right-hand capsule, beside a plain trial link.

**States:** Declared: hover background #0131ff and color #fbfbfa; focus-visible outline #0131ff solid 3px with 2px offset.

### Primary button

**Use:** Default product-page conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 64px; padding: 16px 48px; background: #111111; color: #fffefa; border-radius: 8px`

**Text style:** `button` — Aeonik 500 · 20px/1.6 · tracking 0.008em

**Observed:** The filled action leads a paired row. A compact 48px version uses 12px 32px padding and 16px/24px medium text with 0.5px tracking. On dark scenes the default fill reverses to off-white with charcoal text.

**States:** Declared: hover background #0131ff and color #fffefa; active background #001fa5 and color #fffefa. The light-on-dark variant instead hovers to #1e1e1e with #fbfbfa text.

### Secondary button

**Use:** Alternative conversion beside the filled action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 64px; padding: 14.5px 48px; border: 1.5px solid #191919; border-radius: 8px; color: #191919; background: transparent`

**Text style:** `button` — Aeonik 500 · 20px/1.6 · tracking 0.008em

**Observed:** Matches the filled action's optical height. Dark-stage versions use off-white borders and text.

**States:** Declared: hover border and text #0131ff; active border and text #001fa5.

### Editorial link

**Use:** Secondary reading, exploration, and resource actions.

**CSS:** `display: inline-flex; align-items: center; gap: 12px; color: #201b16; text-decoration: underline`

**Text style:** `text-link` — Aeonik 500 · 18px/25px · tracking 0.028em

**Observed:** Usually an unboxed underlined text label. Video links add a small play disc; reverse billboards use lavender and the question recipe.

**States:** Declared: hover color #0131ff with underline; active color #001fa5.

### Resource tile

**Use:** Text-only resources and next-step choices.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 32px; background: #ece8e4; border-radius: 16px; min-height: 416px`

**Text style:** `resource-heading` — Aeonik 500 · 24px/1.35

**Observed:** Uppercase content type first, medium sans heading second, body copy third, underlined action pinned low. The entire tile can link. Closing-choice variants use serif card headings and a simple icon.

**Transfer:** Keep equal heights and bottom-aligned actions across each row.

### FAQ row

**Use:** Objection handling in a wide accordion column.

**CSS:** `border-top: 1px solid #1e1e1e; color: #1e1e1e`

**Text style:** `question` — Aeonik 500 · 20px/1.4 · tracking 0.004em

**Observed:** Question and plus icon share a full-width button with 24px vertical padding. The expanded answer uses the detail recipe and 24px bottom padding; the final item adds a bottom rule.

**Transfer:** Keep questions visible and concise; use structured paragraphs or bullets for complex answers.

### Footer

**Use:** Consistent contact and destination ending.

**CSS:** `background: #1e1e1e; color: #fbfbfa; padding: 24px 64px`

**Text style:** `footer-link` — Aeonik 500 · 16px/26px · tracking 0.0125em

**Observed:** A roomy internal wrapper begins 80px below the section top. The left column carries a compact wordmark, contact sentence, outlined action, and social icons; two narrower destination columns sit to the right. Muted column titles precede bright links. Fine rules separate disclosure and the small legal-and-locale row.

**Transfer:** Keep the footer compact in number of columns but spacious vertically.

### Expandable benefit tabs

**Only for:** solution and industry narratives

**Use:** Paired photograph or graphic and benefit explanations.

**CSS:** `border-top: 1px solid #ababab; margin-bottom: 16px`

**Text style:** `card-heading` — SeasonMix 400 · 32px/1.25

**Observed:** The active item expands its body and editorial link; a 3px electric-blue progress line runs along the top rule. Inactive rows show a serif title and plus icon. Pause control accompanies autoplay, and the media occupies the opposite equal-width column.

**Transfer:** Use for a small set of connected outcomes, with matching media per outcome.

### Plan column

**Only for:** pricing pages

**Use:** Comparable packages with progressively richer capabilities.

**CSS:** `background: #ece8e4; border-radius: 16px; padding: 24px`

**Text style:** `plan-name` — SeasonMix 500 · 40px/1.2

**Observed:** Plan name, price or inquiry line, short use-case paragraph, aligned action, and inclusion list. The entry plan has the filled dark action; others use outlines. Blue circular checks mark included features.

**Transfer:** Keep the action baseline aligned despite different amounts of introductory copy.

## Imagery and graphics

### Floating interface sculpture

**Use:** Default hero object and feature chapter media.

**Observed:** White interface slabs float in a shallow three-quarter view, with a saturated blue side edge and smaller overlapping badges. The hero object fills roughly the right half of the content area, grounds itself with a soft grey shadow, and has no enclosing screenshot frame. Capability media uses simplified interface panels over an electric-blue rounded square that fades toward lavender at its lower edge.

**Transfer:** Show the new product's core relationship or workflow using two to four meaningful panels, not a complete application window. The minimum version is a crisp front-facing white panel with two overlapping callouts, a blue backing edge, and a soft grounding shadow.

**Build:** Use a 560px-wide stage. Layer white rounded rectangles with gentle perspective rotation and a narrow electric-blue duplicate offset behind them. Add a small top-right badge and a lower-left status card. Beneath the group place a wide low-opacity black ellipse blurred by about 24px. For chapter illustrations use a blue square with a pale blurred lower-edge glow. Keep internal details as product UI, not marketing typography.

### Atmospheric blue light

**Use:** Required visual connective tissue in the opening, product media, and closing conversion stage.

**Observed:** Electric blue and violet mingle with a small warm coral-orange glow. Light openings wash the color out toward off-white under the copy; dark variants retain a deep blue field. Long stone chapters show only a faint colored edge, whereas closing bands can carry a stronger horizon.

**Transfer:** Recreate the light rather than an arbitrary pastel mesh. Keep text on a clean field and concentrate saturated color near edges, behind the object, or below the conversion panel.

**Build:** Layer a broad blue radial glow from the upper left, a violet glow toward the upper center, and a smaller warm orange glow at the upper right. Blur the layers together and mask them toward transparent over the off-white canvas by the middle of a light hero. For a closer, move the light sources to the bottom edge; for a dark variant retain deep blue beneath all layers. Match the soft glow; exact stops are not essential.

### Blueprint proof banner

**Use:** A distinctive technical-proof interruption within the light page.

**Observed:** A deep blue rounded rectangle carries a faint square engineering grid. A bold white symbolic mark or short graphic statement occupies one half, with a serif heading, reverse paragraph, and light button on the other.

**Transfer:** Translate the graphic half into a simple original diagram or large proof phrase appropriate to the new product; retain the technical grid and asymmetrical reading composition.

**Build:** Fill a 1312px-wide rounded stage with deep blue. Draw fine low-opacity pale-blue horizontal and vertical SVG lines at roughly 80px intervals, fading toward the center. Place a simple white diagram in the left half and vertically centered copy in the right. Keep the grid subordinate to the text.

### Human workplace photography

**Only for:** industry and service-oriented narratives

**Use:** Industry openings, benefit tabs, and paired service cards.

**Observed:** Natural color photographs show people using technology in believable offices, public spaces, or customer settings. Crops favor one engaged person and contextual surroundings; rectangular images have softly rounded edges. Some hero images add translucent technical badges and a circular play control.

**Transfer:** Use credible work or customer situations with natural light, not isolated stock portraits. Add only a small meaningful interface overlay when it clarifies the product.

### Layered photographic proof

**Only for:** customer proof collections

**Use:** Customer-story and testimonial carousels.

**Observed:** A large rounded photographic panel is centered while smaller or dimmer neighbours peek out behind both sides. One variant places an 80px white metric over a darkened image area; another places a warm stone quote card over the left side of a workplace photograph, followed by name and small role caption. Circular arrows sit near the lower edge.

**Transfer:** Use one verified outcome or one substantive quote, with a contextual photograph. Keep the off-axis neighbouring panels as evidence of a larger story collection rather than an ornamental card stack.

**Build:** Create a wide central photo panel with 24px to 32px corners. Offset two neighbouring photo panels laterally behind it, reduce their apparent size, and dim them. Use a left-to-right black gradient on the metric variant; use a stone inset quote rectangle on the testimonial variant.

### Immersive portfolio art

**Only for:** broad portfolio presentations

**Use:** Shared media backdrop behind category cards.

**Observed:** Blue glass-like objects, translucent slabs, and bright edge highlights sit over a saturated blue field with violet and orange light. Dark navy glass cards reveal the underlying objects through blur.

**Transfer:** Use a small set of original objects representing the new product's functional categories. A minimum version is three translucent geometric slabs with blue edges and carefully controlled reflections.

**Build:** Place three broad rounded slabs in shallow isometric perspective over the blue-lit stage, overlap them, and add thin bright edge strokes plus blurred glints. Overlay the Navy glass category surface so objects remain partly visible rather than placing a separate illustration inside every card.

### Icons

**Observed:** Utility and action icons are generally 16px to 24px, monochrome white or charcoal, with blue reserved for emphasis. Fine line icons use approximately 1.5px strokes; larger 64px benefit illustrations mix blue and charcoal outlines. Plus signs and arrows remain simple and unboxed except for circular carousel controls.

**Transfer:** Choose simple outline metaphors and plain directional arrows. Use blue check discs for inclusion lists, not multicolored decorative icon badges.

## Section recipes

How recurring sections are built.

### First screen: Light product stage opening

**Observed:** A 40px utility strip precedes two floating navigation capsules. The atmospheric backdrop begins behind the capsules and fades into the off-white canvas. Below the navigation, a left 632px column contains breadcrumb, a two-line 56px serif headline, a 24px lead separated by 24px, and a filled-plus-outline action row with 16px gap. The product object occupies the right half at comparable visual scale, with overlapping white interface slabs and a low grounding shadow. The inner hero has 64px top and bottom padding within 1312px of content. Within the first 900px, the entire headline, support line, both actions, and product object are visible; the rounded stone next chapter just begins at the bottom, with its content below the fold.

**Transfer:** Use this as the default marketing and product opening. Without bespoke 3D art, make a clean floating workflow panel with two meaningful callouts and a blue edge. Pricing opens with a short 64px serif title and no hero sculpture; industry pages reverse the text over a saturated blue-light field and pair it with a contextual video photograph. Solution pages can inset the whole split composition in a translucent stone panel.

**Avoid:** Do not center the default headline above a full-width dashboard or turn the entire first screen into an opaque blue rectangle. Do not scale the opening title into oversized poster typography.

**Text style:** `display` — SeasonMix 400 · 56px/1.14

### Chapter heading pair

**Observed:** An uppercase eyebrow introduces a centered 48px serif lead with 16px gaps to its supporting 24px explanation and underlined editorial action. In ordinary sections, the same heading and support pair aligns left; some broad benefit sections place headline and support beside each other.

**Transfer:** Use a question or content-type overline only when it adds structure, then express one outcome and one explanatory sentence.

**Text style:** `heading-lg` — SeasonMix 400 · 48px/1.16

### Alternating capability chapter

**Observed:** Inside Stone chapter, 96px top and bottom padding frames a heading pair and a succession of two-column media-copy rows. Product media is 560px by 523px, separated from copy by 112px; sides alternate. Copy is vertically centered and uses eyebrow, 40px serif title, and 20px body with 16px gaps. Rows separate by 64px.

**Transfer:** Use a connected capability story of whatever length the content needs. Match each image to the adjacent claim rather than repeating a generic dashboard.

**Text style:** `heading` — SeasonMix 400 · 40px/1.2

### Technical proof billboard

**Observed:** Blueprint proof banner uses a 1312px-wide rounded stage with graphic left and text right. Deep blue billboard uses a similarly rounded split image-story treatment with 64px vertical padding in the text half, 72px at its left, and a lavender article link below.

**Transfer:** Give the page a distinctive technical-proof moment using an original diagram, a compatibility story, or a research result. Choose the symbolic proof banner or the editorial story form according to the content.

### Resource collection

**Observed:** A 48px serif section title precedes a three-column Resource tile grid with 32px gaps. Tiles are 416px square with 32px inner padding, uppercase type labels, 24px medium sans titles, and 20px paragraphs. A second row is separated by 48px.

**Transfer:** Offer meaningful educational destinations; preserve title, explanation, and low action alignment even when titles differ in length.

**Text style:** `resource-heading` — Aeonik 500 · 24px/1.35

### Split FAQ

**Observed:** A serif title occupies the narrow left column while FAQ rows occupy the 853px right column, separated by 32px. Expanded answers use 16px detail text; simple plus controls stay aligned at the right edge.

**Transfer:** Address adoption and buying objections in the reader's language, leaving lengthy technical qualification in expanded content.

**Text style:** `question` — Aeonik 500 · 20px/1.4 · tracking 0.004em

### Atmospheric conversion and footer

**Observed:** The default close places a 56px serif heading, 24px lead, and paired actions inside Frosted closing panel over atmospheric light. Solution and industry variants use a 392px saturated blue-light band with reverse text and light-plus-outline actions. Broad campaign variants use three shallow Translucent closing choice cards; pricing uses three taller stone next-step cards over a bright bottom-edge glow. All end on Footer charcoal with disclosures where needed, a compact logo/contact column, two link columns, social icons, and a separated legal/locale baseline.

**Transfer:** Always resolve the page with a luminous conversion moment and the stable dark footer. Choose one clear commitment pair or three genuinely different next steps; do not force all closing variants into the same page.

**Text style:** `display` — SeasonMix 400 · 56px/1.14

### Expandable outcome pair

**Only for:** solution and industry narratives

**Observed:** A 600px square photograph or illustration sits beside a 600px expandable benefit list with a 112px column gap. The active row shows heading, body, and editorial link under a blue progress line; collapsed titles sit beneath fine grey rules.

**Transfer:** Use this scoped alternative for industry or solution benefits, keeping only the active explanation prominent.

**Text style:** `card-heading` — SeasonMix 400 · 32px/1.25

### Quantified proof stage

**Only for:** quantified customer proof

**Observed:** Photographic proof gives one oversized 80px sans value an adjacent 20px explanation over an image. Industry proof instead places three 48px serif numbers in an open layout beside an introduction, with small explanatory captions and a monochrome customer-logo strip below.

**Transfer:** Use verified measures with a clear unit and scope. Keep the metric attached to its explanation rather than presenting disconnected decorative numerals.

**Text style:** `photo-stat` — Aeonik 500 · 80px/1.1 · tracking 0.001em

### Pricing decision system

**Only for:** pricing pages

**Observed:** Four equal Plan columns use 24px gaps, 40px medium serif names, and either 40px serif prices or smaller inquiry text. Below them, a catalogue of capabilities uses full-width 1px ruled rows with label left, explanation right, and arrow at the far edge. The comparison matrix uses pale alternating rows, compact blue checks, and outlined add-on tags. Trust logos, two photographic support cards, a split FAQ, and three large next-step cards complete the decision narrative.

**Transfer:** Separate package selection, detailed comparison, and reassurance so density increases only after the initial choice.

**Text style:** `plan-name` — SeasonMix 500 · 40px/1.2

## Page flow

**Storyline:** Promise → explain the mechanism → demonstrate outcomes → establish trust → support evaluation → offer a next step → institutional footer.

### Broad brand or portfolio landing page

1. **Promise** — Full-bleed photographic campaign opening with serif copy and paired actions.
2. **Technical proof** — A bounded deep-blue gridded proof banner.
3. **Portfolio orientation** — Immersive blue art behind three navy glass category cards.
4. **Customer proof** — Logo strip and layered photographic story carousel with a large metric.
5. **Authority and education** — Open analyst-proof columns and tabbed editorial cards.
6. **Closing call** — Three shallow choices over atmospheric light, followed by disclosure and the common dark footer.

**Transfer:** Use this form when the visitor must choose among several audiences or product families; retain the expressive media but reduce campaign-specific navigation when the offer is narrow.

### Pricing and commercial evaluation

1. **Orientation** — Short serif introduction over a fading color wash, followed by an audience selector.
2. **Package choice** — Four stone plan columns with aligned actions and blue inclusion checks.
3. **Detailed evaluation** — Capability catalogue and compact comparison matrix.
4. **Reassurance** — Trust logos and two photographic security/support cards.
5. **Objection handling** — Split FAQ.
6. **Closing call** — Three large next-step cards over a colored horizon, billing qualifications, and the common dark footer.

**Transfer:** Let initial packages remain readable before exposing exhaustive comparison detail.

### Flagship product landing page; default visual model

1. **Promise** — Light split hero with floating interface sculpture and paired actions.
2. **Mechanism** — Centered chapter introduction inside a stone-and-light enclosure.
3. **Capability chapters** — Alternating blue-backed product illustrations and concise explanations.
4. **Technical proof** — Gridded proof banner, innovation pair, and dark article billboard.
5. **Customer proof** — Layered photographic quote carousel.
6. **Evaluation support** — Text-only resource grid and split FAQ.
7. **Closing call** — Frosted conversion panel over light, disclosures, and common dark footer.

**Transfer:** Start with the new product's outcome, then make the mechanism concrete through a small number of visually distinct capabilities.

### Developer-facing solution adoption

1. **Promise** — Inset stone hero pairing a business outcome with a video photograph and technical overlay.
2. **Problem framing** — Four open risk columns.
3. **Solution principles** — Rounded stone benefits band with simple line icons.
4. **Product demonstration** — Technical introduction and blue diagram/video beside explanatory copy.
5. **Adoption benefits** — Expandable outcome pair.
6. **Ecosystem proof** — Dark illustrated article inside a stone enclosure with partner-logo rows.
7. **Closing call** — Reverse conversion band, qualification text, and common dark footer.

**Transfer:** Join the business reason to adopt with a clear protocol or workflow explanation and an actionable technical destination.

### Industry-specific confidence and relevance

1. **Promise** — Reverse blue-light hero beside a contextual video photograph.
2. **Relevance** — Brief stone statement of the industry outcome.
3. **Quantified proof** — Open serif metrics and customer-logo strip.
4. **Benefit chapters** — Photographic expandable tabs and open subcategory columns.
5. **Customer proof** — Layered testimonial photograph with an inset quote card.
6. **Product fit** — Vertical product selector, new-release columns, partner tabs, and paired platform cards.
7. **Closing call** — Reverse blue-light conversion band directly above the common dark footer.

**Transfer:** Use domain-specific situations and proof while keeping the same serif hierarchy and geometric page shell.

## Writing

Assured, practical, and forward-looking. The language promises control and progress, then explains the mechanism in specific terms rather than relying only on aspiration.

**Do not copy:** Do not reuse Okta or Auth0 names, logos, partner graphics, event branding, proprietary product names, customer quotations, research rankings, numerical claims, or commercial terms. Replace them with the new project's own verified assets and facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Headlines and actions address the reader directly through imperative verbs; support copy uses you and your. The product is named plainly when explaining a mechanism, while we and our appear sparingly.
- **Rhythm:** Headlines are usually short outcome statements of roughly 5–11 words. Support is one or two complete sentences; capability paragraphs often use two or three concise sentences. Ampersands compact headings, and em dashes link an explanation or choice without making the tone breathless.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Imperative verb + concrete object + meaningful result. | 7–11 words | “Give every agent in your workforce an identity”<br>“Win enterprise deals by adopting the XAA protocol” |
| Supporting line | A concise explanation of the control or benefit the reader gains. | 16–35 words | “Gain the visibility, control, and governance you need to secure the agents your business deploys.” |
| Capability heading | Active verb and object, with the outcome readable at a glance. | 4–8 words | “Find & register your agents”<br>“Enforce policy at every tool call” |
| Chapter overline | A direct operational question or a plain content-type label. | 2–5 words | “Where are my agents?”<br>“What are they doing?” |
| Action | Verb + destination or commitment; conversational when asking for contact. | 2–5 words | “Get the datasheet”<br>“Talk to us”<br>“Watch and explore chapters” |
| Closing call | A short invitation that returns choice to the reader. | 4–9 words | “Ready to get started?”<br>“Choose your next step”<br>“Ready to secure your next big move?” |

**Words and phrasing to use:** gain; control; discover; govern; connect; trusted; visibility; across; every; your; get started; see how

**Avoid:** revolutionary magic; crush the competition; game-changing synergy; effortlessly solve everything; exclamation-heavy hype

**Rules:**

- Lead with the reader's desired outcome, then identify the mechanism that makes it credible.
- Keep technical terms when they carry real meaning, and explain new acronyms on first use.
- Make actions destination-specific: reading, watching, building, trying, and talking are different commitments.
- Treat quantitative proof as a qualified statement with units and context, not as decorative excitement.
- Use short questions to organize complex operational concerns; let the supporting paragraph answer them.

## Do's and Don'ts

### Do

- Keep the default hero headline at 56px/1.14 in a regular editorial serif.
- Maintain the 1312px reading width and 64px desktop side gutters.
- Separate major narrative blocks by 128px while keeping related text gaps at 16px.
- Use 32px corners for broad enclosures and 16px for practical resource cards.
- Retain electric-blue illumination in at least one substantive product scene and the closing treatment.
- Make resource grids three equal columns with 32px gaps and bottom-aligned actions.
- Keep ordinary conversion buttons at 8px radius, with a 1.5px secondary outline.
- Finish with a dark charcoal footer containing contact information and two destination columns.

### Don't

- Do not replace the regular serif heading system with bold geometric sans at every level.
- Do not use the blue navigation pill's 30px radius for all page buttons.
- Do not tint every content card blue; warm stone is the working card material.
- Do not add heavy drop shadows or outlines to the flat stone resource grid.
- Do not miniaturize ordinary marketing body copy to 14px; the default is 20px/28px.
- Do not turn the technical overline's 0.12em uppercase treatment into the style of every control.
- Do not scatter isolated 3D icons across the page; stage a coherent interface object or diagram.
- Do not make all sections dark; reserve deep blue for bounded graphic and proof moments.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions animate background-color, border-color, and color over 0.3s ease-out.
- FAQ buttons declare padding transitions of 0.3s linear; resource cards declare a 0.15s transition.
- Expandable benefit tabs show a blue progress line and an explicit pause control. The campaign opening also exposes autoplay control.

**Transfer:**

- Preserve the clear blue hover shift on dark buttons and outlined actions.
- If using timed benefit tabs or rotating hero content, keep the pause control visible rather than hiding it in navigation.

**Unknown:**

- The complete runtime timing of autoplay, entry choreography, and scroll-triggered effects is unspecified.

### Responsive

**Observed:**

- Stylesheets declare numerous width breakpoints, including 768px, 1024px, and 1200px; the design dimensions here describe the 1440px desktop composition.

**Transfer:**

- On narrow layouts, retain the serif headline and floating-light relationship while stacking product media beneath the promise and actions.
- Reflow card and pricing grids without shrinking the 20px reading copy into dense miniature columns.
- Keep the two navigation functions distinct even if destinations move into a compact menu.

**Unknown:**

- Exact mobile type sizes, gutters, menu behavior, and stacking breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
