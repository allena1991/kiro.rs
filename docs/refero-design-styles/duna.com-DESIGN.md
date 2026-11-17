# Duna — pastoral infrastructure

## Overview

An optimistic enterprise style that pairs tightly set grotesk typography with luminous painted landscapes. White and warm stone carry the practical product story, while peach skies, meadow greens and teal create expansive moments around it. Small interface vignettes and natural portraits keep complex software approachable without losing institutional credibility. The overall density is airy, with compact controls inside broad editorial spaces.

### Essentials

- Enterprise clarity inside a painted world: the opening uses a full-width pastoral landscape fading into white behind a centered 800px headline block, with 72px/1 regular grotesk type and -0.06em tracking.
- Conversion controls are small dark pebbles, not rectangles: near-black pill buttons are 44px tall in the opening and 36px in the fixed 76px navigation.
- Color behaves like scenery rather than UI decoration: most reading sections remain white or #f7f7f5; rich color belongs to the landscape opening, a full-bleed sky interlude and the #46838c landscape-backed ending. Retain a painted atmospheric moment and a scenic ending even when the product has no natural imagery.
- Technical explanations are staged as intimate objects: 496px square warm-stone media panels face 496px feature lists across a 128px gap; one selected row receives a #edece7 fill and 16px corners.
- Proof has two human scales: 80px/1 medium numerals sit above small outcome labels, while a 32px/1.2 regular testimonial faces a large cut-out portrait on a neutral backing.
- The ending is a place to linger: six compact white link columns float above a painted meadow and mountain valley in a 644px scenic footer, with legal and utility links resting near the bottom.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Landscape teal | `#46838c` | `--color-teal` | background | Scenic footer ground and the extended conversion band above it. |
| Deep plum | `#1b0624` | `--color-plum` | text | 44px section headings, almost neutral rather than overtly purple. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal lime | `#aeec1d` | `--color-lime` | accent | An isolated 8px square in the translucent sky-interlude label; not a general button color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Espresso | `#160f0c` | `--color-action` | action, surface | Primary pill action fills. |
| Numeral black | `#000000` | `--color-black` | text | Large proof numerals and small explore actions. |
| Deep body ink | `#1a1816` | `--color-body-dark` | text | Feature titles and attribution text. |
| Charcoal | `#222221` | `--color-headline` | text, background | Opening headlines; dark institutional band on organization pages. |
| Warm ink | `#292421` | `--color-ink` | text, link | Body copy, navigation and card titles. |
| Chapter charcoal | `#272725` | `--color-chapter-ink` | text | 40px chapter headings. |
| Soft plum gray | `#766a7c` | `--color-soft-plum` | text, surface | Visible result of deep plum at 60% over white; secondary proof text. The same translucent hue becomes a dark glass announcement pill over artwork. |
| Warm gray | `#898683` | `--color-muted` | text | Support lines and secondary text. |
| Portrait ground | `#dfdcd5` | `--color-portrait-back` | surface | Flat warm-gray backing behind the large testimonial portrait. |
| Warm stone | `#edece7` | `--color-stone` | surface, text | Selected feature rows, product stages and quote cards; pale support text in the closing conversion band. |
| Faint rule | `#f5f5f5` | `--color-rule` | border | Visible black at 4% over white for extremely faint section and proof separators. |
| Warm paper | `#f7f7f5` | `--color-paper` | surface, background, text | Quiet bands, category pills and testimonial text panels; inverse heading variant. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Default reading canvas; inverse type and light buttons over scenery. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| organization and investor stories | Umber card | `#38322f` | `--color-institution-card` | surface | Logo plaques in the dark institutional band. |

## Typography

- **GT America** — All marketing headings, paragraphs, navigation, labels and proof numerals. An economical neo-grotesk with open counters, regular-weight headlines and a slightly stronger numeral cut. If unavailable, use **Inter**. Use 400 for text and 500 for medium cuts; preserve the tight display tracking. Font stack: "GT America", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | GT America | 500 | 80px | 1 | normal, features "tnum", "zero" | Large numerical proof with units kept on the same line. |
| display | GT America | 400 | 72px | 1 | -0.06em | Opening headline, generally two centered lines within 800px. |
| heading | GT America | 400 | 44px | 1.1 | -0.05em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Major section leads and the centered atmospheric interlude. |
| chapter | GT America | 400 | 40px | 1.2 | -0.03em | Secondary capability chapter leads and large centered product quotations. |
| quote | GT America | 400 | 32px | 1.2 | -0.03em | Primary portrait testimonial. |
| lead | GT America | 400 | 24px | 1.4 | -0.03em | Opening support copy and medium testimonial text. |
| story-title | GT America | 400 | 22px | 1.2 | -0.02em | Editorial titles below story thumbnails. |
| body | GT America | 400 | 20px | 1.4 | -0.02em | Chapter support sentences and feature-row titles. |
| primary-action | GT America | 400 | 20px | 1 | -0.03em | Opening conversion button. |
| footer-heading | GT America | 500 | 20px | 1.5 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Compact navigation group headings over the scenic footer. |
| caption | GT America | 400 | 18px | 1.2 | -0.01em | Outcome labels, concise section introductions and card support. |
| detail | GT America | 400 | 16px | 1.5 | -0.01em | Expanded feature descriptions, navigation and footer links. |
| compact-action | GT America | 400 | 16px | 1 | -0.01em | Header conversion action and secondary filled buttons. |
| eyebrow | GT America | 400 | 14px | 24px | normal | Sentence-case category label in a small rounded capsule. |
| announcement | GT America | 400 | 14px | 1.5 | normal | Short proof announcement floating above the opening headline. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product capability summary cards | card-title | GT America | 400 | 28px | 1.2 | -0.02em | Two-card summaries with a small icon above the text. |

**Notes:**

- Regular weight, tight tracking and deliberate line breaks create the headline presence; do not substitute bold weight for scale.
- Tracking tightens from -0.01em on small text to -0.06em on the opening headline. Proof numerals retain normal tracking.
- Keep supporting text visibly lighter than headings. The 44px heading and 40px chapter roles coexist; use the former for major narrative statements, the latter for detailed capability chapters.

## Layout

**Density:** Airy at section scale, compact within controls and feature rows; the broad whitespace is punctuated by tightly composed product objects.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title-to-expanded-detail gap inside a selected feature row. |
| 10px | Small icon/text group gaps. |
| 12px | Footer link rhythm and small metadata separation. |
| 16px | Heading-to-support gap and feature-row padding. |
| 24px | Category-to-heading spacing and summary-card padding. |
| 32px | Opening headline-to-support gap; compact quotation-card padding. |
| 40px | Support-to-action gap and standard section side padding. |
| 48px | Section heading group to product demonstration or proof content. |
| 64px | Large testimonial inset and spacing between numerical proof groups. |
| 80px | Editorial section padding and footer top inset. |
| 128px | Major section vertical padding and desktop two-column feature gutter. |
| 140px | Default expansive capability chapter vertical padding. |

### Containers and grids

- **chapter-container**: max width 1200px · side padding 40px. Centered outer wrapper with 1120px usable content at desktop; reading edges sit 160px from a 1440px viewport edge.
- **opening-copy**: max width 800px · side padding 0px. Centered headline and support measure; art runs independently to the viewport edges.
- **feature-pair**: max width 1120px · 2 columns · gap 128px. A 496px square product scene faces a 496px feature list; alternate which side holds the scene.
- **story-grid**: max width 1120px · 3 columns · gap 20px. Three 360px editorial tiles with images above unboxed titles.
- **footer-grid**: max width 1120px · 6 columns · gap 40px. Six short navigation groups above the landscape; bottom legal row spans the same width.
- **summary-grid** (only for product capability summary cards): max width 1120px · 2 columns · gap 24px. Two equal 548px text-led cards.
- **editorial-column** (only for organization narratives): max width 700px · side padding 0px. Left-aligned opening statement and long-form paragraphs centered as a narrow reading column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-labels | 9999px (pill) |
|  | selected-feature-and-quote-cards | 16px |
|  | product-media | 24px |
|  | portrait-testimonial | 8px |
| product capability summary cards | summary-cards | 12px |
| organization narratives | biography-cards | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| announcement-glass | `rgba(45, 32, 50, 0.08) 0px 0.6px 1.8px -0.7px, rgba(45, 32, 50, 0.09) 0px 2.3px 6.9px -1.3px, rgba(45, 32, 50, 0.12) 0px 10px 30px -2px` | Only the small glass proof announcement above the opening headline; ordinary cards stay flat. |

### Surfaces

#### Reading canvas · level 0

**Use:** Most of the page.

**CSS:** `background: #ffffff`

#### Paper band · level 0

**Use:** Quiet full-width reassurance or process sections.

**CSS:** `background: #f7f7f5`

**Observed:** Broad flat fields without a decorative border or shadow.

**Transfer:** Use to separate a calm explanatory passage from white chapters.

#### Stone panel · level 1

**Use:** Selected feature rows and compact testimonial cards.

**CSS:** `background: #edece7; border-radius: 16px; box-shadow: none`

**Observed:** Warm, opaque and deliberately low-contrast against white.

**Transfer:** Group the active explanation without making every row into a card.

#### Scenic ground · level 0

**Use:** Full-width painted ending and extended conversion area.

**CSS:** `background: #46838c; overflow: hidden`

**Observed:** Flat teal connects to a painted sky above the mountain-and-meadow scene. Text occupies the calmer sky and darkened foreground.

**Transfer:** Keep navigation readable over an original landscape using the same broad light-to-dark division.

#### Header veil · level 2

**Use:** Soft background layer behind fixed navigation.

**CSS:** `background: rgba(255,255,255,0.8); backdrop-filter: blur(1.5px)`

**Observed:** The opening leaves the artwork visible behind navigation; further down, the bar reads as a soft white veil. A graded blur extends below it rather than a hard drop shadow.

**Transfer:** Keep the veil on a separate layer so text and controls remain crisp.

#### Institutional band · level 0

**Only for:** organization and investor stories

**Use:** Credibility roster and institutional backing.

**CSS:** `background: #222221; color: #ffffff`

**Observed:** Umber logo plaques sit above a four-column name roster with translucent white horizontal rules.

**Transfer:** Reserve this sustained dark variant for people or institutional credentials, not every product chapter.

## Components

### Fixed navigation

**Use:** Persistent global orientation.

**CSS:** `position: fixed; height: 76px; padding: 20px 40px; display: flex; align-items: center; justify-content: space-between; z-index: 10`

**Text style:** `detail` — GT America 400 · 16px/1.5 · tracking -0.01em

**Observed:** Small symbol-and-wordmark at left, four restrained category links centered, and Compact conversion at right. Place Header veil behind these elements rather than blurring the content.

### Primary button

**Use:** Main opening conversion.

**CSS:** `background: #160f0c; color: #ffffff; border-radius: 9999px; padding: 12px 24px; height: 44px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `primary-action` — GT America 400 · 20px/1 · tracking -0.03em

**Observed:** A short plain-language action with no leading icon. The strong dark fill is surrounded by generous white space.

### Compact conversion

**Use:** Header conversion and smaller utility actions.

**CSS:** `background: #160f0c; color: #ffffff; border-radius: 9999px; padding: 8px 14px; height: 36px`

**Text style:** `compact-action` — GT America 400 · 16px/1 · tracking -0.01em

**Observed:** Same family as the main action, reduced in scale. The scenic interlude reverses to a white 44px button with a trailing chevron; the product closing form uses a white 42px action.

### Proof announcement

**Use:** A concise result or release link above the opening headline.

**CSS:** `background: rgba(27,6,36,0.6); color: #ffffff; border-radius: 99px; padding: 4px 8px 4px 14px; backdrop-filter: blur(5px); display: inline-flex; gap: 6px`

**Text style:** `announcement` — GT America 400 · 14px/1.5

**Observed:** A small trailing 12px chevron and a soft layered shadow distinguish this single floating label from ordinary category pills.

### Category pill

**Use:** Name a product chapter before its heading.

**CSS:** `background: #f7f7f5; border-radius: 9999px; padding: 4px 10px; display: inline-flex; align-items: center`

**Text style:** `eyebrow` — GT America 400 · 14px/24px

**Observed:** Sentence case, quiet fill, no colorful outline. The product-only opening inverts the capsule to white on a paper field.

### Feature selector

**Use:** Explain one capability at a time beside a product scene.

**CSS:** `background: #edece7; border-radius: 16px; padding: 16px; display: flex; flex-direction: column; gap: 8px`

**Text style:** `body` — GT America 400 · 20px/1.4 · tracking -0.02em

**Observed:** An icon precedes the title; the active item expands to reveal Detail text below. Other rows sit directly on white with title and icon only, about 60px high. The list uses a 4px inter-row gap.

**Transfer:** Bind each active explanation to a matching illustration. Use real details rather than empty explanatory text.

### Portrait testimonial

**Use:** Make social proof personal and prominent.

**CSS:** `background: #f7f7f5; border-radius: 8px; display: flex; overflow: hidden`

**Text style:** `quote` — GT America 400 · 32px/1.2 · tracking -0.03em

**Observed:** A 1120px-wide, 460px-tall composition splits into a 640px quote panel with 64px inset and a 480px portrait on Portrait ground. Attribution sits low in the text panel; the person is framed from the chest up.

**Transfer:** Use a real attributed customer statement and an equally deliberate portrait, preserving the unequal split.

### Story tile

**Use:** Link to customer stories or editorial proof.

**CSS:** `display: flex; flex-direction: column; gap: 20px`

**Text style:** `story-title` — GT America 400 · 22px/1.2 · tracking -0.02em

**Observed:** A 360px by 277px image sits above an unboxed title and tiny reading-time metadata. The image carries a centered white customer mark over a softly blurred landscape. Organization news uses a 24px grid gap, shorter 357px by 227px thumbnails and 20px titles.

### Footer link group

**Use:** Navigation over the scenic ending.

**CSS:** `display: flex; flex-direction: column; gap: 12px; color: #ffffff`

**Text style:** `detail` — GT America 400 · 16px/1.5 · tracking -0.01em

**Observed:** A Footer-heading label precedes short link rows. Six groups share the upper sky. Legal links use 60% white near the bottom; an auxiliary summary-link cluster sits opposite.

**States:** Declared: hover color #292421 and underline on footer text links; focus-visible not specified.

### Summary card

**Only for:** product capability summary cards

**Use:** A compact paired explanation without an interface demonstration.

**CSS:** `background: #f7f7f5; border-radius: 12px; padding: 24px; height: 240px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `card-title` — GT America 400 · 28px/1.2 · tracking -0.02em

**Observed:** A small 36px icon sits at the upper left; title and 18px support occupy the bottom portion.

### Closing form field

**Only for:** product conversion endings

**Use:** Short inquiry form in the teal band above the scenic navigation.

**CSS:** `background: rgba(187,187,187,0.15); border-radius: 451px; padding: 9px 24px 8px 24px; height: 43px; width: 380px`

**Observed:** Three rounded fields form a narrow stack with 12px gaps. A heading and support paragraph sit to the left; a white pill action sits beneath the fields.

**Transfer:** Ask only for information relevant to the next human conversation.

## Imagery and graphics

### Painted landscape opening

**Use:** The signature first impression for a general marketing landing page.

**Observed:** A luminous hand-painted meadow surrounds a winding reflective lake, with distant rounded mountains, pale peach and yellow clouds and small flowers. The scene fills the top width, then dissolves into white in the lower portion so the black headline remains clear. Brush texture is soft but visible; no device frame or border encloses the artwork.

**Transfer:** Commission or create an original optimistic landscape, not a literal depiction of software. The minimum version is a layered illustrated horizon, reflective water and textured cloud field fading naturally into the reading canvas.

**Build:** Use a full-width SVG with three irregular mountain path layers, distant low-contrast teal ridges, warmer foreground meadow banks and a pale reflective river opening toward the lower center. Scatter tiny muted flower marks along the banks. Place translucent peach and cream cloud masses behind the ridges, add a fine low-opacity turbulence texture, and overlay a white vertical gradient rising from fully opaque at the bottom to transparent through the lake. Keep the central lower area low-detail for text.

### Painted sky interlude

**Use:** A full-bleed emotional pause between dense proof and capability material.

**Observed:** A 740px-tall blue-teal sky is ringed by soft cream cumulus clouds along the left, right and bottom edges. Centered white heading and support occupy an open patch of sky, with a translucent category badge containing a lime square and a white pill action.

**Transfer:** Use an original cloud composition with clear central negative space. Preserve the painted atmosphere instead of replacing it with a generic abstract gradient.

**Build:** Start with a teal-blue field. Layer irregular SVG cloud silhouettes and overlapping cream ellipses outside the central text region, concentrating them at both sides and lower corners. Add softly shaded lower cloud contours, a restrained blur and a fine turbulence texture. Place the text layer above the art and a 10% white pill with an 8px lime square above the heading.

### Scenic footer

**Use:** Signature closing environment across marketing and organization pages.

**Observed:** A broad mountain valley recedes toward a lit central gap; two trees flank a flower meadow with rocks and a tiny seated figure. Teal sky joins the flat upper band, while deep green foreground gives pale legal text contrast. The painting runs edge to edge behind the entire footer, not inside a card.

**Transfer:** Create a different original landscape with a central view through distant mountains, darker side anchors and a readable sky. A simplified textured SVG valley with tree silhouettes and layered meadow banks is the minimum acceptable equivalent.

**Build:** Layer distant desaturated mountain paths below a solid teal upper field, add warm cloud clusters near the horizon, then place two asymmetrical tree silhouettes at the outer thirds and overlapping meadow paths along the bottom. Use progressively darker green-teal tones toward the foreground and a subtle dark lower overlay behind legal text. Keep the six-column navigation in the calmer upper area.

### Product vignettes

**Use:** Square visual companions to feature selectors.

**Observed:** Small white UI fragments float inside warm-stone square stages with 24px corners. Stacks, connecting arrows, timelines and isolated form controls explain one behavior at a time. Peripheral objects fade or blur while the active object remains legible; some stacks tilt in perspective. Pastel accents stay inside the miniature UI.

**Transfer:** Rebuild a reduced, believable fragment of the new product rather than a full dashboard. Use white layers, gentle depth and one visually selected object. Keep surrounding marketing surfaces neutral.

### Human portrait

**Use:** The large customer testimonial and smaller author attributions.

**Observed:** Natural color photography with restrained expression and neutral clothing; the large subject is cut out against a flat warm-gray field and aligned to the lower edge. Small attribution images are compact square portraits.

**Transfer:** Favor real people and relaxed credible poses. Match the warm neutral backing rather than using saturated portrait backgrounds.

### Blurred editorial landscape

**Use:** Story and news thumbnails.

**Observed:** Pastoral colors are heavily defocused into soft green, gold and teal fields beneath a crisp centered white customer or publication mark. Thumbnails have small corners and no surrounding border.

**Transfer:** Use a defocused original landscape or a few blended landscape-like fields. Keep the overlaid mark sharp and generous in scale.

**Build:** Fill a rectangular image with large overlapping teal, olive and warm-gold blurred shapes arranged like sky, hill and foreground; use a 40px soft blur at a 360px thumbnail width. Add a subtle dark wash and center the permitted white mark on a separate crisp layer.

### Icons

**Observed:** Monochrome, economical pictograms beside feature titles, generally 28px; 16px chevrons sit in exploration actions and 12px in the announcement. The visible pictograms read as thin outlined symbols despite being implemented as filled vector shapes.

**Transfer:** Choose simple outline-like icons with consistent apparent stroke and no colored badge backgrounds; reserve pastel icon tiles for miniature product UI.

## Section recipes

How recurring sections are built.

### First screen: Landscape promise opening

**Observed:** The first 855px is a single layered composition: full-width painted lake and meadow behind a transparent fixed navigation, then a white fade, then centered proof announcement, headline, support and dark Primary button. The mountains and sky dominate the upper half; the lake opens into a low-detail central foreground. The 72px Display headline spans about 800px and two lines in the lower half. Its support uses Lead in muted gray, separated by 32px; the button follows with 40px breathing room. All of the headline, support, action and main painted scene are visible within the first 900px; the customer-logo proof sits below.

**Transfer:** For a new product, retain the large original landscape and a concise promise rather than forcing the product UI into the opening. If no commissioned painting is available, use the layered textured landscape construction. Product detail pages can instead open on Paper band with a category pill, the same Display headline and Lead support in an 850px centered measure, about 587px tall. Organization narratives retain the landscape but switch to a 700px left-aligned reading column and continue into prose.

**Avoid:** Do not place a dashboard in a floating laptop over the lake, compress the headline into a small top-left box, or let busy foreground details compete with the action.

**Text style:** `display` — GT America 400 · 72px/1 · tracking -0.06em

### Heading and demonstration chapter

**Observed:** A Chapter container uses 128px or 140px vertical padding. Category pill, Heading or Chapter, and muted Body support form the upper group; an exploration link sits opposite the heading on the right. After 48px, Feature-pair places Product vignettes beside Feature selector. Alternate the side holding the scene from chapter to chapter.

**Transfer:** Give each chapter one outcome, one short support sentence and a few concrete capabilities. Preserve the square object stage and generous two-column gutter rather than adding a dense dashboard.

**Text style:** `heading` — GT America 400 · 44px/1.1 · tracking -0.05em

### Quantified proof

**Observed:** A left-aligned Heading is followed after 48px by three 80px Stat figures with 18px outcome captions. The figures are grouped toward the left rather than stretched as oversized cards. A faint horizontal rule separates the numerical row from three icon-led explanations with faint vertical dividers.

**Transfer:** Use verified product outcomes or operational measures. Keep numbers black, labels brief and supporting explanations in soft plum-gray; do not add colored stat backgrounds.

**Text style:** `stat` — GT America 500 · 80px/1

### Human-led trust

**Observed:** A centered Heading and short Caption introduce a muted monochrome logo row, then Portrait testimonial. The quote sits near the top left and the attribution near the bottom, balancing the large portrait on the right.

**Transfer:** Use customer or expert proof appropriate to the new product. Keep the testimony specific and the large neutral portrait treatment intact.

**Text style:** `quote` — GT America 400 · 32px/1.2 · tracking -0.03em

### Atmospheric interlude

**Observed:** Painted sky interlude runs full bleed for 740px. Centered heading, short white Body support and a reversed Compact conversion sit within an 800px measure. A translucent pill and lime square precede the heading.

**Transfer:** Place this device where the story benefits from an emotional reset. Use a capability promise relevant to the new product rather than a list of technical features.

**Text style:** `heading` — GT America 400 · 44px/1.1 · tracking -0.05em

### Quiet reassurance band

**Observed:** Paper band uses 140px vertical padding and a left-aligned Heading, muted support and exploration action. A compact group of three monochrome certification-style symbols sits to the right.

**Transfer:** Use substantiated trust markers or a concrete reliability explanation. Keep this section typographic and restrained rather than turning it into a colored badge wall.

**Text style:** `heading` — GT America 400 · 44px/1.1 · tracking -0.05em

### Editorial proof grid

**Observed:** Three Story tiles sit below a Chapter heading with a 56px gap. Organization news expands to two rows with 24px column gaps and 44px row spacing, using shorter thumbnails.

**Transfer:** Choose customer narratives, research or independent recognition that extends the product story; retain image-first, unboxed tile construction.

**Text style:** `story-title` — GT America 400 · 22px/1.2 · tracking -0.02em

### Scenic close

**Observed:** Scenic ground supports six Footer link groups over a full-width Painted footer environment. A 2px translucent white rule sits across the upper edge, and the navigation begins with an 80px inset. A roughly 300px open interval lets the landscape breathe before the bottom legal and utility row. The standard scenic ending is 644px tall. On product conversion endings it extends upward into a 1184px total band containing a two-column invitation and three Closing form fields.

**Transfer:** Retain the scenic ending on new pages. Keep the conversion form as a product-detail variant; a general landing page can conclude with editorial proof directly above the scenic navigation.

### Institutional roster

**Only for:** organization narratives

**Observed:** Institutional band uses 96px vertical padding. Heading and short introduction sit to the left of two umber-backed partner plaques. Beneath, a four-column roster uses small white names, softer role lines and translucent horizontal rules.

**Transfer:** Adapt to advisors, contributors or institutional partners without importing a dark theme into ordinary feature chapters.

**Text style:** `heading` — GT America 400 · 44px/1.1 · tracking -0.05em

### Paired quote cards and onward navigation

**Only for:** long product detail pages

**Observed:** Two Stone panels with 32px inset hold customer logos, 24px quote text and compact portrait attributions. An onward carousel follows, with a left-aligned Heading, wide cards with category labels and lower-edge titles, plus 56px circular previous/next controls.

**Transfer:** Use the paired testimonials to answer technical objections and the onward cards to connect adjacent capabilities. Each card needs meaningful finished media or a deliberate text-led composition, not empty visual space.

**Text style:** `lead` — GT America 400 · 24px/1.4 · tracking -0.03em

## Page flow

**Storyline:** Expansive promise → credible proof → concrete capability explanations → reassurance or editorial depth → scenic closing navigation.

### Broad product introduction and category positioning

1. **Promise** — Painted opening, centered headline, short explanatory line and one conversion action.
2. **Social proof** — Customer marks, quantified outcomes and icon-led benefits.
3. **Human validation** — Logo row and a large portrait testimonial.
4. **Emotional reset** — Full-bleed painted sky with a focused capability statement.
5. **Capability chapters** — Alternating square product vignettes and selected feature lists.
6. **Objection handling** — Quiet reassurance band and short editorial proof grid.
7. **Closing navigation** — Scenic footer with white link columns and a low legal row.

**Transfer:** Use this as a broad narrative toolkit, scaling the number of capability chapters to the product rather than repeating the original sequence mechanically.

### Explain a focused product capability in depth

1. **Focused promise** — Centered category pill, Display headline and support on a paper-colored field.
2. **Product demonstration** — Square interface vignette and an adjacent feature selector.
3. **External validation** — Partner marks and a large warm-stone quotation.
4. **Capability depth** — Alternating demonstration chapters, a process band and two compact summary cards.
5. **Objection handling** — Evidence-oriented explanations and paired customer quotations.
6. **Related capabilities** — Wide onward-navigation carousel with previous and next controls.
7. **Conversion and closing navigation** — A short inquiry form on teal transitions into the shared scenic footer.

**Transfer:** Start more directly than a broad landing page, using the same type system and neutral materials; keep the painted landscape at the end to maintain the emotional identity.

### Explain mission, people and institutional credibility

1. **Mission** — Landscape-backed left-aligned opening statement followed by a narrow long-form narrative.
2. **People** — Two paper biography cards with small portraits, names, roles and prose.
3. **Track record** — Muted prior-company marks below a brief introductory line.
4. **Institutional proof** — Dark band with partner plaques and a four-column roster.
5. **External recognition** — Two-row editorial thumbnail grid.
6. **Resource action** — Paper press-resource panel with a short download action.
7. **Closing navigation** — The shared scenic footer, without the product inquiry extension.

**Transfer:** Use the narrower editorial opening and scoped institutional band for a company story, while preserving the common typography, gentle surfaces and scenic close.

## Writing

Confident and practical, with an optimistic view of infrastructure. Technical language is allowed, but the main claims connect the mechanism to speed, quality, revenue or reduced work rather than sounding visionary for its own sake.

**Do not copy:** Do not reuse Duna's name, logo, customer or investor marks, proprietary artwork, numerical claims, customer quotations or attributed endorsements. Replace them with original assets and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader with you and your. The product is named when clarity requires it; we and our appear mainly in mission and trust statements.
- **Rhythm:** Headlines are compact statements, often 4–9 words, with natural two-line breaks. Follow with one practical support sentence. Longer narrative prose belongs in narrow editorial columns; actions are brief verbs or verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Define the change or turn an abstract problem into a concrete outcome. | 6–10 words | “Defining the future of business onboarding”<br>“Translate your regulatory programs into code” |
| Section heading | A direct outcome with a named mechanism or an economical contrast. | 4–9 words | “Agents collect the evidence. Analysts do the judgment.”<br>“Give your auditors peace of mind” |
| Support | Explain what improves and how, without repeating the heading. | 8–25 words | “High-converting onboarding journeys, no code required.”<br>“Run enterprise-grade programs - without writing a single line of code” |
| Action | A concrete next step, not a slogan. | 1–4 words | “Schedule a demo”<br>“Explore”<br>“Download media resources” |
| Reassurance | A short human statement followed by an actionable explanation. | One short statement and one supporting sentence | “Your trust is our foundation.” |

**Words and phrasing to use:** built for; automate; reduce; evidence; one platform; without writing code; every stage; first-time-right; your team

**Avoid:** revolutionary magic; game-changing; unleash your potential; best-in-class without proof; excessive exclamation marks; playful compliance puns

**Rules:**

- Lead with the operational benefit, then name the mechanism.
- Use concrete feature nouns in the selector rows and reserve broader ambition for the opening.
- Keep technical acronyms where the audience needs them; make surrounding sentences plain.
- Attach numerical claims to a clear measured outcome and use human testimony for qualitative impact.
- Let the artwork carry warmth; avoid overloading the prose with nature metaphors.

## Do's and Don'ts

### Do

- Keep opening headlines at 72px/1, weight 400 and -0.06em tracking at desktop.
- Use 44px/1.1 section leads and 40px/1.2 detailed chapter leads as distinct roles.
- Preserve a 1120px content area inside the 1200px wrapper with 40px side insets.
- Make the major product vignette 496px square with 24px corners and a warm neutral backing.
- Set 80px proof numbers in medium weight with normal tracking and small labels beneath.
- Keep the dominant reading field white, with paper and stone reserved for grouping.
- Give the scenic footer real vertical room: 644px for the standard ending.
- Use the 8px lime mark as a tiny signal within a translucent badge, not as a broad accent system.

### Don't

- Do not make every paragraph #222221; supporting lines need the softer #898683 hierarchy.
- Do not replace the regular-weight grotesk headline with a heavy geometric display face.
- Do not turn the 44px opening action into a tall rectangular enterprise button.
- Do not add strong shadows or outlined borders to ordinary stone cards.
- Do not fill product feature rows with different bright colors; the selected row uses one warm-stone fill.
- Do not move pastel product-UI icon colors into the marketing navigation.
- Do not stretch small interface fragments to fill the whole 496px stage; negative space is part of their scale.
- Do not convert the scenic footer into a short flat-color strip.

## Motion and responsive

### Motion

**Observed:**

- No action or surface transition timings are established. Product vignettes include selected, faded and perspective-layered object arrangements.
- Footer text links declare an underline and warm-ink hover color.

**Transfer:**

- Keep state changes tied to the feature selector and the corresponding miniature product object, rather than animating the entire page as a single spectacle.
- Maintain the legibility of the central message in scenic sections while treating surrounding art as atmosphere.

**Unknown:**

- Animation timing, easing, autoplay, selector cycling and scroll-reveal behavior are not established.

### Responsive

**Observed:**

- Width rules include boundaries around 720px, 810px, 1000px and 1200px; an additional 1600px rule appears for the broad marketing layout.

**Transfer:**

- On narrow layouts, keep the landscape full bleed and the headline over its low-detail fade, reducing type and measure together.
- Stack each product vignette with its matching feature list and reduce the 128px desktop gutter rather than shrinking miniature UI until unreadable.
- Wrap footer groups into fewer columns while preserving a readable sky region and the dark foreground behind legal text.

**Unknown:**

- Exact mobile font sizes, navigation behavior, image positioning and breakpoint-specific column counts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
