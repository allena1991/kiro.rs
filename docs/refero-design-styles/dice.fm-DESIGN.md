# DICE — poster type, human energy

## Overview

A mostly white, black-ink identity with the punch of an independent gig poster and the ease of a friendly utility. Extremely condensed display lettering meets light, unshowy grotesk text, small pill actions and spacious editorial layouts. Candid people photography, close-cut product demonstrations and irreverent hand-drawn characters supply the energy rather than decorative interface chrome. It suits consumer products and culture-led services that want to feel useful without becoming corporate.

### Essentials

- Poster-heavy openings, light conversational chapters: Foggy at 106px/88px with normal tracking makes a compact uppercase headline, while Favorit section headings are only 28px/34px at weight 350.
- The opening is half invitation, half lived experience: two 624px columns separated by 48px, with vertically centered copy beside a 624×780px portrait. Keep headline, short support and a single compact action visible in the first 900px.
- Actions look like small stamped capsules, not giant conversion banners: the default is black, 40px high, 20px radius, 22px horizontal padding, with 12px/16px bold capitals tracked at 0.06em.
- White owns the page; black provides deliberate punctuation: the main canvas and most chapters are white, interrupted by a full-width black illustration band. Saturated color belongs inside media, not in headline fills or ambient gradients.
- Pictures stand as large plain rectangles, not floating card stacks: recurring chapters pair 441×551px media with 441px text across an 87px gap. Use candid human detail or a closely framed demonstration when no lifestyle film exists.
- Give the utility a mischievous human side: include a black-and-white hand-drawn benefit device, with three 296px illustrations and 18px/22px centered captions on black. Original expressive line drawings of the new product's objects are the minimum equivalent.
- End with lived proof rather than a wall of badges: a portrait-led endorsement and small action lead to an airy white footer, with a small character or symbol at left, right-aligned link columns and a thin #d9d9d9 utility divider.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action, link | Primary lettering, pill actions and full-width contrast bands. |
| Charcoal capsule | `#333333` | `--color-charcoal` | action, border | Platform download buttons and secondary actions on black. |
| Search text | `#595959` | `--color-search-text` | text | Search hint lettering. |
| Muted grey | `#808080` | `--color-muted` | text | Low-priority footer text, rendered as black at 0.5 alpha over white. |
| Utility rule | `#d9d9d9` | `--color-rule` | border | Footer utility divider; not a general media backing. |
| Search grey | `#f2f2f2` | `--color-soft` | surface | Search capsule and the light secondary business action. |
| White | `#ffffff` | `--color-canvas` | background, text | Dominant page canvas and reversed lettering on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| contact forms | Required red | `#d70015` | `--color-required` | text | Required-field asterisk only. |
| contact forms | Form hairline | `#f0f0f0` | `--color-field-rule` | border | Black at 0.06 alpha over white separates contact rows. |

## Typography

- **Foggy** — Opening poster headlines. Very heavy, tightly condensed, slightly irregular sans with blunt compact capitals; its declared regular cut is visually emphatic. OpenType features: "ss02", "ss03", "ss05", "ss06", "ss08". If unavailable, use **Anton**. Use weight 400; preserve condensed proportions and tight line stacking. Font stack: "Foggy", "Anton", sans-serif.
- **Favorit** — All supporting copy, section headings, navigation and controls. Clean grotesk with a light everyday voice; the contrast with the dense display face is essential. OpenType features: "ss02", "ss03", "ss05", "ss06", "ss08". If unavailable, use **Inter**. Use variable weight 350 for prose and headings, 400 for labels, 700 for small actions. Font stack: "Favorit", "Inter", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Foggy | 400 | 106px | 88px | normal | Compact stacked opening headline; visually uppercase. |
| heading | Favorit | 350 | 28px | 34px | normal | Default chapter heading, on white or black. |
| feature-title | Favorit | 400 | 28px | 34px | normal | Selectable benefit titles beside product media. |
| body | Favorit | 350 | 18px | 22px | normal | Hero support, benefit captions and feature descriptions. |
| navigation | Favorit | 400 | 16px | 19px | normal | Header links. |
| search | Favorit | 400 | 16px | 1.15 | normal | Search capsule hint. |
| label | Favorit | 400 | 16px | 1.25 | normal | Catalog titles and form labels. |
| footer-title | Favorit | 700 | 16px | 1.25 | normal | Footer navigation group titles. |
| footer-link | Favorit | 350 | 16px | 1.5 | normal | Footer navigation links. |
| metadata | Favorit | 400 | 14px | 1.25 | normal | Catalog date, location and price lines. |
| action | Favorit | 700 | 12px | 16px | 0.06em, uppercase | Default capsule action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and business landing pages | editorial-display | Foggy | 400 | 100px | 0.85 | normal | Centered identity headline or left-aligned two-line business promise. |
| contact and business conversion sections | closing-heading | Favorit | 400 | 48px | 56px | -0.01em | Contact invitation or black closing call. |
| company and business landing pages | editorial-heading | Favorit | 350 | 44px | 50px | normal | Long-form chapter and centered proof headings. |
| business testimonials | quote | Favorit | 400 | 38px | 1.3 | -0.03em | Large uninterrupted endorsement text. |
| business closing calls | closing-support | Favorit | 400 | 27px | 34px | -0.015em | Centered support beneath the closing heading. |
| company and business landing pages | editorial-body | Favorit | 350 | 24px | 28px | normal | Introductory statements and editorial paragraphs. |
| contact forms | eyebrow | Favorit | 700 | 16px | 22px | normal, uppercase | Contact invitation label. |
| business testimonials | quote-name | Favorit | 600 | 14px | 1.4 | 0.0025em, uppercase | Testimonial attribution name. |
| business testimonials | quote-role | Favorit | 400 | 14px | 1.4 | 0.0025em | Attribution job title below name. |
| business landing pages | business-action | Favorit | 600 | 13px | 44px | 0.03em, uppercase | Wide business conversion capsules. |

**Notes:**

- The opening face supplies density through its letterforms, not through extra tracking. Preserve normal tracking and the unusually short 88px line height at 106px.
- Body and default chapter headings share the light 350 weight. Do not turn all headings into bold grotesk.
- Tracking is reserved for small action capitals and a few larger business text roles; ordinary prose stays normal.
- The default headline uses a 500px text measure inside a wider column. Break into emphatic short lines rather than stretching each line across the full page.

## Layout

**Density:** Airy at page scale, compact inside text and controls; large media and long white intervals carry more weight than boxed modules.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Image-to-catalog-details gap and separation between form rows. |
| 16px | Illustration-to-caption gap and inner content-container side padding. |
| 24px | Heading-to-benefit-list gap and footer link rhythm. |
| 25px | Opening copy-column gaps. |
| 32px | Catalog card gap and lower-footer breathing room. |
| 40px | Three-column grid gaps and editorial headline-to-support interval. |
| 48px | Opening column gap and header horizontal padding. |
| 60px | Top of black benefit band and bottom of wide media chapters. |
| 87px | Alternating feature-column gap. |
| 120px | Main chapter separation and business black-band vertical padding. |
| 150px | Catalog section top and bottom breathing room. |

### Containers and grids

- **Opening spread**: max width 1440px · 2 columns · gap 48px · side padding 48px. Equal copy and portrait columns; at desktop the visible content spans 1296px with 72px outside margins.
- **Chapter container**: max width 1000px · side padding 16px. Centered wrapper with 968px usable width at desktop.
- **Alternating chapter**: 2 columns · gap 87px. Two equal 441px columns for image and copy; reverse their sides between chapters.
- **Benefit grid**: 3 columns · gap 40px. Three 296px illustrations or editorial thumbnails in the chapter container.
- **Wide media**: max width 1280px · side padding 40px. Near-full-width photographs and art, aligned with the footer's inner width.
- **Footer columns**: 3 columns · gap 24px. 200px-wide navigation groups occupy the right side; the left remains spacious for a small identity symbol.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Default capsule | 20px |
|  | Media | 5px |
|  | Catalog media | 8px |
|  | Search capsule | 100px |
| business landing pages | Business capsule | 44px |
| catalog cards | Save control | 40px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| business editorial grids | Editorial thumbnail | `0px 4px 16px 0px rgba(0, 0, 0, 0.08)` | Restrained depth on selected article thumbnails only. |

### Surfaces

#### White canvas · level 0

**Use:** Default background for openings, alternating chapters and footer.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Continuous white space; images and copy are not individually enclosed.

**Transfer:** Make the page feel like a sequence of editorial spreads, not a dashboard.

#### Black punctuation band · level 0

**Use:** The signature illustrated benefit chapter; also business endorsements and closing calls.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Runs edge to edge with no rounded outer container or shadow.

**Transfer:** Use white lettering and monochrome line art; let the band make the contrast rather than adding an accent color.

#### Quiet search surface · level 1

**Use:** Search capsule in the header.

**CSS:** `background: #f2f2f2; border-radius: 100px`

#### Contact row surface · level 0

**Only for:** contact forms

**Use:** Understated input separation.

**CSS:** `border-bottom: 1px solid rgba(0, 0, 0, 0.06); padding: 16px 0`

**Observed:** Label and input share one unboxed horizontal row.

**Transfer:** Keep form structure legible with rules rather than filled input cards.

## Components

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0 22px; border: 2px solid transparent; border-radius: 20px; background: #000000; color: #ffffff; transition: opacity 200ms`

**Text style:** `action` — Favorit 700 · 12px/16px · tracking 0.06em · uppercase

**Observed:** Content-sized capsule below support copy; the same construction appears in the header and chapter calls.

**States:** Declared: hover opacity 0.75 and text-decoration underline; focus-visible outline 2px solid #000 with outline-offset 2px.

**Transfer:** Use a short imperative; keep the action physically smaller than its supporting paragraph.

### Header navigation

**Use:** Persistent desktop orientation.

**CSS:** `position: fixed; height: 96px; padding: 24px 48px; display: flex; align-items: center; width: 100%; box-sizing: border-box`

**Text style:** `navigation` — Favorit 400 · 16px/19px

**Observed:** Identity at far left, Search capsule beside it, plain navigation links pushed right and Primary button at the end. Link items have 20px horizontal margins. The business variant is 88px high and omits search.

**Transfer:** Retain one primary action rather than filling the bar with pill links.

### Search capsule

**Use:** Discovery entry in the consumer header.

**CSS:** `display: flex; align-items: center; width: 370px; height: 48px; padding: 12px 16px; box-sizing: border-box; border-radius: 100px; background: #f2f2f2; color: #595959; margin-left: 24px`

**Text style:** `search` — Favorit 400 · 16px/1.15

**Observed:** Small magnifier precedes the hint; no visible border or shadow.

**Transfer:** Name the objects people actually search for, not an abstract command.

### Catalog tile

**Use:** Horizontal discovery rail.

**CSS:** `width: 256px; position: relative`

**Text style:** `label` — Favorit 400 · 16px/1.25

**Observed:** Square cover media with 8px corners, then title after 8px and compact date, place and price lines using metadata. A black circular Save control sits over the lower-right image edge. Cards remain on the canvas without a surrounding border.

**Transfer:** Show real covers or documentary thumbnails. Use the rail for discoverable things rather than generic feature descriptions.

### Footer link

**Use:** Low-emphasis navigation in the closing footer.

**CSS:** `color: #000000; padding-bottom: 1px; background-image: linear-gradient(#000000, #000000); background-size: 0px 1px; background-position: 0px 100%; background-repeat: no-repeat; transition: background-size 150ms ease-in-out`

**Text style:** `footer-link` — Favorit 350 · 16px/1.5

**Observed:** Grouped beneath bold footer-title labels; each item occupies a loose row with 24px vertical margins.

**States:** Declared: hover text-decoration none; focus-visible text-decoration none.

### Download capsule

**Use:** Platform-specific footer actions.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 8px 16px; box-sizing: border-box; background: #333333; color: #ffffff; border: 2px solid #333333; border-radius: 20px; margin-right: 16px`

**Text style:** `action` — Favorit 700 · 12px/16px · tracking 0.06em · uppercase

**Observed:** Platform icon before the label; paired beneath the identity symbol rather than alongside the footer column titles. The iOS label preserves mixed case.

**States:** Declared: hover opacity 0.75 and text-decoration underline; focus-visible outline 2px solid #333 with outline-offset 2px.

### Footer utility row

**Use:** Secondary information at the very end of the page.

**CSS:** `display: flex; flex-wrap: wrap; align-items: center; max-width: 1280px; padding-top: 24px; border-top: 1px solid #d9d9d9`

**Observed:** Copyright and language at left, legal controls and social icons across the right, with a muted trademark line beneath. Sits below a generous primary footer rather than in a dark bar.

### Save control

**Only for:** catalog cards

**Use:** Small overlay action on catalog media.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 30px; height: 30px; background: #000000; color: #ffffff; border: 2px solid transparent; border-radius: 40px`

**Observed:** White 24px outline icon, inset 8px from the image's lower-right edge.

**States:** Declared: hover opacity 0.8; focus-visible outline 2px solid #000 with outline-offset 2px.

### Contact field row

**Only for:** contact forms

**Use:** Sales or partnership inquiry forms.

**CSS:** `display: flex; align-items: center; padding: 16px 0; margin-bottom: 8px; border-bottom: 1px solid rgba(0, 0, 0, 0.06)`

**Text style:** `label` — Favorit 400 · 16px/1.25

**Observed:** Label at left and editable content at right; the form is 484px wide, with a 190px label region and 278px input region separated by 16px. Required asterisks are red. The message row expands vertically.

**Transfer:** Retain visible labels; do not replace them with placeholder-only inputs.

### Business button

**Only for:** business landing pages

**Use:** Paired self-serve and sales actions.

**CSS:** `width: 200px; height: 44px; padding: 0 20px; box-sizing: border-box; border-radius: 44px; background: #000000; color: #ffffff; text-align: center; transition: 0.25s cubic-bezier(0.55, 0.085, 0.68, 0.53)`

**Text style:** `business-action` — Favorit 600 · 13px/44px · tracking 0.03em · uppercase

**Observed:** Two equal-width actions share a row with 20px between them. On white, the secondary is light grey; in the black closing band, the primary reverses to white and the secondary uses charcoal. Closing labels become weight 700.

**States:** Declared: hover background-color #191919 and text-decoration none; focus-visible outline 2px solid #000 with outline-offset 2px and text-decoration none.

## Imagery and graphics

### Candid human portrait

**Use:** Main opening and lived-proof closing chapter.

**Observed:** Tall close-framed footage of people laughing, moving and inhabiting a real cultural setting; natural skin and clothing colors, imperfect gesture and very little staged polish. The opening image occupies half the spread, runs 780px tall and has subtly rounded corners. The closing proof focuses tightly on a person's tattooed arm.

**Transfer:** Show the new product's human consequence: a real moment, a hand using it or a personal artifact. If film is unavailable, use one strong documentary portrait with the same close framing, not a stock office team.

### Hand-drawn benefit characters

**Use:** Signature black illustrated benefit band.

**Observed:** Three playful monochrome figures with rubbery limbs, faces and gestures. White silhouettes, rough black inner lines and a second irregular white sticker-like edge float freely on black; no card boxes. Each drawing has a 296px square stage above a short centered caption.

**Transfer:** Invent characters from simple objects relevant to the new product. Preserve humor, imperfect linework and high-contrast white silhouettes rather than reproducing an existing mascot.

**Build:** Draw each object in a 296×296 SVG viewBox using an uneven polygon or rounded body, two bent limb paths, small eyes and a curved mouth. Use black interior strokes about 3px wide, white fill, round joins and a second offset white contour behind the silhouette. Vary the tilt and hand gestures; add two or three small outlined stars or motion marks. Keep all artwork monochrome and its baseline aligned across the trio.

### Close product demonstration

**Use:** Alternating capability chapters.

**Observed:** A tall phone demonstration is enlarged within a 441×551px rectangular media area, on a very pale neutral field. The device often extends beyond the lower frame; it is not a tiny screenshot centered in a huge decorative scene. Black product UI contrasts with the white page.

**Transfer:** Show one recognizable workflow at readable scale. For a non-app product, use a similarly close object or process shot; keep product colors inside the media.

### Monochrome proof wall

**Use:** Partner or ecosystem proof within a chapter.

**Observed:** Many varied marks are normalized to white on black within a 441×551px rectangle. The business-page variant spreads black marks across a much wider white field in loose rows.

**Transfer:** Arrange genuine ecosystem or compatibility marks at balanced optical sizes. When there are no marks, use a monochrome collection of meaningful product artifacts or integration names, preserving the dense proof against spacious surrounding copy.

**Build:** Create a plain rectangular field, then arrange 12–16 short word marks or simple symbolic silhouettes in four or five loose rows. Use white on black for the portrait chapter and black on white for the wide business variant. Vary intrinsic logo widths but balance perceived area; do not add individual tiles or outlines.

### Wide documentary photograph

**Only for:** business landing pages

**Use:** Emotional context immediately after the business promise.

**Observed:** A 1280×854px photograph of a crowded dance floor, shot from within the crowd with flash-like highlights, raised hands, deep shadows and full natural color. Slight 5px corners; no text overlay.

**Transfer:** Use a real group actively experiencing the outcome, photographed at participant height rather than as a staged lineup.

### Ink drawing interlude

**Only for:** company stories

**Use:** Wide graphic expression between intro and editorial argument.

**Observed:** A giant loose black line drawing on white depicts two smiling anthropomorphic musical forms holding hands. The image reads as informal animation art rather than a polished vector infographic.

**Transfer:** Use one oversized, sparse, hand-drawn scene about connection or the product's purpose.

**Build:** On a white 1280×720 SVG canvas, draw two large slightly skewed object silhouettes in irregular black paths about 4px wide. Add small sleepy eyes, simple mouths and long arms meeting at the center. Leave ample white around the figures; keep the drawing unfilled except for facial details.

### Thermal culture image

**Only for:** company stories

**Use:** High-energy full-width interlude before contact.

**Observed:** Two performers behind equipment are rendered in saturated orange-red, green-black shadows and yellow-hot contour lines. The rectangular image has radial smear, repeated fine lines and an analog video feel, within a 1280px-wide frame.

**Transfer:** Apply an equally bold duotone or thermal treatment to relevant documentary activity. Keep it as artwork, not a page-wide brand gradient.

**Build:** Use a high-contrast activity photo; posterize luminance into dark green shadows, red midtones and orange highlights. Overlay a thin bright edge trace, then blend several slightly scaled copies at low alpha to produce outward radial echoes. Add fine vertical displacement lines. Match the analog energy; exact color stops are not essential.

### Icons

**Observed:** Utility icons are mostly simple 24px monochrome marks; outline SVGs use 1px strokes with butt caps. Footer social symbols are 28px solid marks, and the selectable benefit list uses 32px image icons. White icons sit inside black controls.

**Transfer:** Use restrained black outline icons for utilities; reserve expressive drawing for the larger benefit artwork. Keep social and platform marks optically small.

## Section recipes

How recurring sections are built.

### First screen: Portrait invitation opening

**Observed:** A white spread begins below a 96px desktop Header navigation. Two equal columns have a 48px gap: left is a centered-in-height copy group, right is an upright 624×780px Candid human portrait. In the left column the black display headline uses a 500px measure and three close-packed lines at 106px/88px; short connective words share the middle line. Support sits about 37px below the headline and the Primary button follows by 25px. Back to front: white canvas, rectangular portrait, uninterrupted black type and small action. Within the first 900px the entire headline, two-line support, action and full portrait are visible; the discovery rail starts below the fold.

**Transfer:** Use a short provocative invitation beside documentary evidence of the product's benefit. Without film, use a single intimate photograph or close process image with the same tall aspect and visual weight. Company pages open with centered 100px/85px poster type and 24px support above wide art; business pages use that display size left-aligned, paired actions and a wide photograph below.

**Avoid:** Do not replace the portrait half with a tiny floating app mockup, center the whole default opening, or make the support line compete with the poster headline.

**Text style:** `display` — Foggy 400 · 106px/88px

### Discovery rail

**Observed:** A spacious white section uses 150px vertical padding, a compact bold local heading, short explanatory copy and Primary button above a horizontally overflowing rail. Catalog tiles are 256px wide with 32px gaps; media is square and text stays unboxed.

**Transfer:** Use a browseable row of real inventory or examples when the product offers discovery. Preserve partial neighboring tiles and horizontal movement rather than squeezing six cards into a centered grid.

### Illustrated black benefit band

**Observed:** Black punctuation band with 60px top and 80px bottom padding. A centered heading precedes a three-column Benefit grid by 24px; each 296px drawing has a centered body caption 16px below it.

**Transfer:** Translate three everyday benefits into expressive original monochrome drawings and short reader-focused captions.

**Text style:** `heading` — Favorit 350 · 28px/34px

### Alternating capability spread

**Observed:** Within Chapter container, a 441×551px media rectangle and 441px copy column are separated by 87px and vertically centered. The media side alternates between chapters. Headings use heading, support uses body, and actions appear only where a next step is meaningful. White chapters have 120px bottom space.

**Transfer:** Use each spread to explain one capability or one human outcome; alternate product demonstration, proof wall and documentary detail rather than repeating an identical screenshot.

### Selectable benefit list

**Observed:** A heading and three 28px benefit titles sit opposite tall product media. Each title is indented 42px to accommodate a small icon. The selected row is black; inactive rows are visually subdued. The business version adds a short 16px description to each title and pairs the list with 441px square workflow media.

**Transfer:** Use a few concrete capabilities as linked labels for the accompanying demonstration; preserve one clear active state, not three equally loud panels.

**Text style:** `feature-title` — Favorit 400 · 28px/34px

### Lived proof and airy footer

**Observed:** The default ending pairs human portrait media with a 28px heading, conversational endorsement paragraph and Primary button. Beneath it, the white footer has 50px padding, a small identity character on the left and three right-aligned columns of links. Download capsules sit low at left; Footer utility row ends the page. The company story reaches the same footer after its contact form; business pages use two link groups after a Black punctuation band closing call.

**Transfer:** Close with tangible human proof and an appropriately small action, then a useful airy footer. Create a small original identity symbol if the product lacks a mascot rather than enlarging its wordmark into a background graphic.

### Editorial argument and wide interlude

**Only for:** company and business stories

**Observed:** A 44px/50px heading and 24px/28px support use a centered narrow container; long paragraphs have 24px separation. Wide media expands to 1280px with 5px corners and 60px bottom padding. Proof and news intros use centered heading pairs, while the company argument is left-aligned.

**Transfer:** Alternate readable explanation with a decisive wide image or graphic; allow the page's purpose to determine text alignment.

**Text style:** `editorial-heading` — Favorit 350 · 44px/50px

### Black testimonial

**Only for:** business testimonials

**Observed:** Full-width Black punctuation band with 120px padding around a 968px text measure. A 38px quote is left-aligned with a hanging opening quotation mark. Attribution follows after 40px, with an uppercase 14px name above a regular 14px role.

**Transfer:** Use one substantial customer explanation rather than several small review cards; preserve the hanging punctuation and editorial scale.

**Text style:** `quote` — Favorit 400 · 38px/1.3 · tracking -0.03em

### Editorial three-up

**Only for:** business editorial grids

**Observed:** A centered heading and support introduce three 296px square thumbnails separated by 40px. Body captions are centered below the pictures; small uppercase read-more links sit beneath. Selected thumbnails have a subtle 5px radius and Editorial thumbnail shadow.

**Transfer:** Use actual stories, case studies or resources; maintain the image-led grid instead of turning each story into a heavily bordered card.

### Contact invitation

**Only for:** contact forms

**Observed:** Two 484px columns fill the 968px Chapter container: uppercase eyebrow and a 48px invitation at left, an eight-row unboxed inquiry form at right. Consent and processing copy follow the fields, then a small Primary button. The white section retains 120px below.

**Transfer:** Pair a human invitation with the form; keep the field count tied to the actual inquiry rather than copying a source's qualification questions.

**Text style:** `closing-heading` — Favorit 400 · 48px/56px · tracking -0.01em

### Business closing call

**Only for:** business landing pages

**Observed:** An edge-to-edge black band, 424px tall, has 120px vertical padding. A centered 48px heading, 27px support line and two Business buttons form one compact cluster. Support is about 20px below the heading and actions follow by 30px; primary is white and secondary charcoal.

**Transfer:** Offer one direct start and one conversational alternative, then transition cleanly into the white footer.

**Text style:** `closing-heading` — Favorit 400 · 48px/56px · tracking -0.01em

## Page flow

**Storyline:** Invitation → concrete discovery or demonstration → easy-to-grasp benefits → deeper capabilities and human proof → contextual next step → spacious utility footer.

### Consumer product discovery and adoption

1. **Promise** — Split poster headline and tall human portrait with one small action.
2. **Product discovery** — Horizontal catalog rail shows the real offering.
3. **Benefit summary** — Black illustrated band turns practical advantages into playful characters.
4. **Capability chapters** — Alternating media-and-copy spreads explain workflows and ecosystem breadth.
5. **Social proof and closing action** — Personal documentary detail and a conversational endorsement lead to a repeated compact action.
6. **Utility ending** — White footer with identity symbol, navigation groups, platform actions and thin-rule utility row.

**Transfer:** Use the contrast between powerful opening type and modest explanatory chapters to turn a practical tool into a human invitation.

### Company narrative and inquiry

1. **Identity promise** — Centered condensed heading and a short belief statement.
2. **Emotional expression** — Wide monochrome drawing introduces warmth.
3. **Editorial argument** — A readable heading and several larger prose paragraphs explain the purpose.
4. **Energy interlude** — Wide thermal-treated documentary artwork supplies a burst of color.
5. **Closing inquiry** — Split contact invitation and lightly ruled form.
6. **Utility ending** — The shared airy white footer follows the form without an extra conversion banner.

**Transfer:** For an organization story, let the belief and imagery do more work than feature lists, then give interested readers a direct contact path.

### Business platform conversion

1. **Promise** — Left-aligned poster headline, larger support and two equal capsule actions.
2. **Human context** — A near-full-width crowded documentary photograph.
3. **Capability demonstration** — Selectable tool benefits beside a square workflow image.
4. **Ecosystem proof** — Centered heading pair followed by a wide monochrome mark wall.
5. **Customer proof** — Large white testimonial on a full-width black field.
6. **Freshness and resources** — Centered news intro and an image-led three-up story grid.
7. **Closing conversion** — Black call-to-action band with reversed paired capsules.
8. **Utility ending** — White footer with two navigation groups and shared utility row.

**Transfer:** Balance operational detail with human context, then close with self-serve and conversational routes rather than duplicating the consumer action.

## Writing

Confident, friendly and slightly cheeky; practical benefits are delivered with the warmth of someone recommending a good night out. The voice likes short plain claims, personal taste and a quick self-aware aside more than institutional authority.

**Do not copy:** Do not reuse DICE names, logos, mascots, partner marks, event inventory, customer quotations, audience claims or company facts. Examples illustrate voice and structure, not claims another product may make.

- **Addressing the reader:** Use you and your for the reader; we for the people behind the product. The product is a helpful facilitator, not an impersonal platform speaking in jargon.
- **Rhythm:** Headlines are often 2–7 words. Support is usually one short sentence or several brisk fragments. Longer endorsements and company arguments earn their space through concrete detail, contractions and a conversational close.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | An invitation or compact human outcome, rendered as poster type. | 4–7 words | “Welcome to the alternative”<br>“Let’s get people out more” |
| Supporting line | Name the practical advantages in short fragments, then resolve into an easy outcome. | One short paragraph | “Incredible live shows. Upfront pricing. Relevant recommendations. [Brand] makes going out easy.” |
| Chapter heading | Familiar language with one unexpected adjective or affectionate shorthand. | 2–5 words | “Weirdly easy ticketing”<br>“Familiar favs, new crushes” |
| Benefit caption | Describe a concrete action and make the speed or reassurance feel personal. | 8–15 words | “Get tickets in less time than it took to read this”<br>“See the full price upfront, with no surprises at checkout” |
| Primary action | Direct verb and concrete object; no elaborate promise. | 2–3 words | “Get the app”<br>“Talk to sales” |
| Closing invitation | A short readiness question, or a human invitation to talk. | 3–6 words | “Ready to go live?”<br>“Talk to us” |

**Words and phrasing to use:** easy; upfront; your favourite; a few taps; we blush; let’s; people; get started

**Avoid:** synergy; enterprise-grade transformation; revolutionary ecosystem; unlock limitless potential; best-in-class solutions

**Rules:**

- Lead with what someone can do or feel, then explain how the product helps.
- Use contractions and affectionate everyday language without making every sentence a joke.
- Name the friction removed: price surprises, waiting or unnecessary steps.
- Let one small aside humanize a section; do not pepper every heading with exclamation marks.

## Do's and Don'ts

### Do

- Keep the default opening at 106px/88px condensed display type, with normal tracking.
- Use 350-weight Favorit for 28px chapter headings and 18px body copy.
- Keep primary marketing capsules 40px high with 20px corners and 12px bold labels.
- Pair recurring 441px media and text columns with an 87px gap.
- Preserve 120px chapter intervals so the compact text has room to breathe.
- Give the black benefit band three 296px drawing stages with 40px between them.
- Keep colored photography and product UI inside clean rectangular media frames.
- End with a white footer whose utility tier has a 1px #d9d9d9 top rule.

### Don't

- Do not extend the display font into paragraph text or ordinary navigation; those stay in the grotesk family.
- Do not inflate all body copy to the 24px editorial variant on an ordinary consumer landing page.
- Do not turn default actions into 56px-high rounded rectangles; the baseline action is a small 40px capsule.
- Do not surround alternating chapters with tinted cards, outlines and shadows; the white canvas is continuous.
- Do not use vivid accent colors for button fills or gradient headline lettering; saturation belongs in imagery.
- Do not apply the article shadow to every photo or demo; most media is flat.
- Do not make the footer black merely because a nearby section is black; the footer returns to white.
- Do not give logos individual equal-sized bordered tiles; balance their optical weight on one field.

## Motion and responsive

### Motion

**Observed:**

- Default buttons declare opacity 200ms transitions; footer links declare background-size 150ms ease-in-out.
- Opening words declare a 250ms reveal animation with cubic-bezier(0.390, 0.575, 0.565, 1.000), clipped by word wrappers.
- The header is fixed and can translate out of view while scrolling.
- Business capsules declare a 0.25s transition with cubic-bezier(0.55, 0.085, 0.68, 0.53).

**Transfer:**

- Keep the poster headline reveal word-based and clipped, rather than animating individual letters.
- Let demonstration media and selected benefit emphasis provide movement; keep layout framing visually stable.

**Unknown:**

- Exact reveal stagger, video loops and interactive carousel timing are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 767px, 768px, 960px, 991px, 992px and 1280px; the consumer page also declares 419px and 420px.

**Transfer:**

- On narrow layouts, preserve the hierarchy between poster type and small capsule actions; stack the portrait and copy rather than shrinking both into miniature desktop columns.
- Keep catalog tiles horizontally browseable, while three-up benefits can become a vertical sequence. These are adaptation recommendations, not a prescribed mobile layout.

**Unknown:**

- Actual mobile typography sizes, navigation behavior and column stacking rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
