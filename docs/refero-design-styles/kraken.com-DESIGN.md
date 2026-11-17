# Kraken — chrome in violet orbit

## Overview

A confident financial-product style that balances pale lilac space with immersive purple stages. Rounded grotesk typography, polished metallic objects and enlarged interface details make complex tools feel tangible and approachable. The default is a light, spacious product landing page with dark bookends; a more exclusive variant stays near-black and uses pearlescent lettering.

### Essentials

- A bold, plainspoken promise sits above a floating object rather than beside it: centered 58px/66px, weight 700, -1px tracking, an 828px text measure and a 458×424px metallic scene beneath the action.
- Purple is concentrated into theatrical bookends, not spread over every panel: a charcoal-to-violet radial gradient frames the opening and a substantial closing stage, while the explanatory body uses #f6f5f9 and white cards.
- Controls are compact rounded rectangles, not pills: primary actions use #7132f5, white 16px/22px medium text, 48px height, 13px 16px padding and 12px corners; header actions shrink to 36px.
- The product becomes a physical exhibit: include a silver-and-violet floating sculpture with luminous edges and at least one enlarged, legible interface vignette. Without custom 3D art, use layered beveled discs or a rounded product-shaped solid with metallic gradients rather than flat clip art.
- Instruction becomes a gallery: white 20px-radius cards sit in a 1252px-wide field, with 20px gutters; text occupies the upper portion and large, selectively cropped product details fill the lower portion.
- The final invitation has its own atmosphere: repeat the 58px promise on a deep purple stage, pair it with one clear acquisition mechanism, and let a large device or product object rise from the bottom edge. The quiet directory footer remains a separate layer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#7132f5` | `--color-purple` | action, link | Primary buttons, links and compact brand accents. |
| Stage violet | `#543496` | `--color-stage-violet` | background, accent | Broad violet light concentrated toward the lower-right of the stage. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender lettering | `#a8a3ff` | `--color-label-violet` | text | Gradient endpoint of the opening product label. |
| Soft action lilac | `#e4dcf9` | `--color-soft-action` | surface, action | Visible soft-action fill: rgba(133,91,251,0.16) over lilac paper. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate text | `#686b82` | `--color-muted` | text | Supporting copy and directory links on light backgrounds. |
| Primary ink | `#101114` | `--color-ink` | text | Headings and primary text on light surfaces. |
| Stage charcoal | `#1f1b27` | `--color-stage-base` | background | Dark end of the opening and closing gradient. |
| Soft slate | `#9497a9` | `--color-subtle` | text | Small annotations; supporting text and input labels on the premium dark theme. |
| Lilac hairline | `#e5e4eb` | `--color-rule` | border | Visible footer separator made with rgba(104,107,130,0.12) over lilac paper. |
| Lilac paper | `#f6f5f9` | `--color-canvas` | background | Default explanatory page field and lower footer band. |
| White | `#ffffff` | `--color-white` | surface, text | Feature cards, navigation and directory footer; text on dark stages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| premium-service pages | Pearl lettering | `#cec7ff` | `--color-pearl` | text | Lavender end of premium gradient headlines. |
| premium-service pages | Premium panel glow | `#382e4b` | `--color-night-glow` | surface | Soft purple illumination at the bottom of premium benefit cards. |
| premium-service pages | Premium night | `#0b0611` | `--color-night` | background | Continuous near-black page field. |
| premium-service pages and dark product showcases | Premium panel | `#16121f` | `--color-night-panel` | surface | Base of premium cards, inputs and directory footer. |
| premium-service pages | Silver lettering | `#e9e9e9` | `--color-silver-text` | text | Light end of premium gradient headlines. |
| premium-service pages | Porcelain action | `#f7f7fa` | `--color-light-action` | action | High-contrast neutral action on dark backgrounds. |

## Typography

- **Kraken-Brand** — Display, headings and opening support text; all principal text on the premium theme. Rounded contemporary grotesk with soft geometric construction and an open, approachable lowercase. If unavailable, use **DM Sans**. Use weights 400, 500 and 700; retain measured line breaks and tracking. Font stack: "Kraken-Brand", "DM Sans", "IBM Plex Sans", Helvetica, Arial, sans-serif.
- **Kraken-Product** — Explanatory body text, actions, form labels and footer links. Compact, highly readable grotesk that remains neutral beside expressive product imagery. If unavailable, use **IBM Plex Sans**. Font stack: "Kraken-Product", "IBM Plex Sans", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Kraken-Brand | 700 | 58px | 66px | -0.0172em | Opening and closing promises on purple stages. |
| heading-lg | Kraken-Brand | 700 | 48px | 56px | -0.0208em | Major explanatory introduction and acquisition invitation. |
| heading | Kraken-Brand | 700 | 36px | 44px | -0.014em | Process, benefit and question-section headings. |
| card-heading | Kraken-Brand | 700 | 24px | 32px | -0.021em | Centered benefit headings inside wide and half-width cards. |
| opening-support | Kraken-Brand | 400 | 24px | 32px | normal | Opening product label and support line; closing benefit summary. |
| step-heading | Kraken-Brand | 700 | 20px | 28px | normal | Left-aligned short process-card titles. |
| lead | Kraken-Product | 400 | 20px | 28px | normal | Centered introductory explanation. |
| support | Kraken-Product | 400 | 18px | 26px | normal | Section support and simple closing reassurance. |
| body | Kraken-Product | 400 | 16px | 22px | normal | Card explanations and accordion labels. |
| button | Kraken-Product | 500 | 16px | 22px | normal | Main and secondary conversion actions. |
| utility | Kraken-Product | 500 | 14px | 20px | normal | Compact actions, footer group titles and utility controls. |
| small | Kraken-Product | 400 | 14px | 20px | normal | Directory links and input labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| premium-service pages | premium-display | Kraken-Brand | 500 | 58px | 66px | -0.02em | Pearlescent opening and form invitation. |
| multi-product overview pages | portfolio-closing | Kraken-Brand | 400 | 58px | 66px | normal | Large light-background directory introduction and final invitation. |
| premium-service pages | premium-heading | Kraken-Brand | 500 | 48px | 56px | -0.02em | Benefit chapters and large editorial positioning statement. |
| multi-product overview pages | portfolio-opening | Kraken-Brand | 400 | 48px | 56px | normal | Restrained umbrella promise over a compact sign-up composition. |
| multi-product overview pages | portfolio-heading | Kraken-Brand | 400 | 36px | 44px | normal | Dark product-showcase headlines. |
| premium-service pages | premium-card-heading | Kraken-Brand | 500 | 20px | 28px | normal | Benefit card titles, often with a white-to-lavender fill. |
| premium-service pages | premium-body | Kraken-Brand | 400 | 16px | 22px | normal | Benefit descriptions and compact qualification figures. |
| premium-service pages | premium-button | Kraken-Brand | 500 | 16px | 22px | normal | Neutral high-contrast actions. |

**Notes:**

- Default product storytelling uses weight 700 headings against weight 400 explanatory text. Do not average this with the lighter multi-product or premium variants.
- Tracking is tight but modest: -1px on the two largest default sizes and -0.5px on smaller headings. Support and utility text keep normal tracking.
- Use sentence case and balanced lines. Large headings stay short enough to read as one thought; the main promise may wrap to two centered lines.
- The product label is unusually generous at 24px/32px and regular weight, not a tiny uppercase eyebrow.

## Layout

**Density:** Airy in section transitions, compact within controls and text groups; large media carry most of the visual weight.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Process title-to-copy and default opening headline-to-support gap. |
| 12px | Internal card stack and overview heading-to-copy gap. |
| 16px | Utility groups and paired actions. |
| 20px | Card-grid gutters and outer opening inset. |
| 28px | Process-card text inset. |
| 32px | Opening label-to-headline, support-to-action and section-heading-to-content gap. |
| 40px | Directory footer top padding and repeated acquisition gaps. |
| 48px | Main action-to-floating-object gap. |
| 56px | Top padding within overview showcase panels. |
| 72px | Overview action-to-device spacing. |
| 80px | Opening stage inner top padding. |
| 88px | Overview chapter separation. |
| 112px | Main product and premium chapter separation. |
| 144px | Expanded pause before questions after the acquisition scene. |

### Containers and grids

- **content**: max width 1252px · side padding 16px. Centered explanatory body, grids and footer. At a 1440px viewport this leaves 94px side margins.
- **text measure**: max width 828px. Centered opening promise, explanatory introduction and accordion.
- **card text measure**: max width 404px. Centered copy inside wide benefit panels.
- **process grid**: max width 1252px · 3 columns · gap 20px. Equal 404px process cards at desktop.
- **benefit grid**: max width 1252px · 2 columns · gap 20px. One wide split panel followed by two equal benefit panels.
- **opening stage**: max width 1400px · side padding 16px. Inset 20px from the page edges at desktop, below the 64px navigation with a 20px breathing strip.
- **form** (only for premium-service pages): max width 404px · gap 8px. Narrow centered field stack within an expansive illustrated dark stage.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 12px |
|  | cards | 20px |
|  | opening stage | 32px |
| app acquisition sections | download code backing | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| accordion rule | `inset 0px 1px 0px 0px rgba(104,107,130,0.24)` | Fine separation without a filled accordion card. |

### Surfaces

#### Lilac canvas · level 0

**Use:** Default explanatory page field.

**CSS:** `background: #f6f5f9; color: #101114`

#### Violet stage · level 0

**Use:** Immersive opening and closing field.

**CSS:** `background: radial-gradient(132.58% 133.41% at 94.88% 121.07%, #543496 20.04%, #1f1b27 100%); color: #ffffff`

**Observed:** A broad diagonal atmosphere, almost charcoal at the upper left and visibly purple toward the lower right. The opening is clipped to 32px corners; the closing is full bleed.

**Transfer:** Use the same lighting field to unify unrelated product objects.

#### White exhibit · level 1

**Use:** Process cards, benefit panels and enlarged interface illustrations.

**CSS:** `background: #ffffff; border-radius: 20px; overflow: hidden`

**Observed:** Flat, borderless panels stand apart by tone rather than heavy shadow.

**Transfer:** Keep the card as a neutral exhibit backing; put visual complexity in its media.

#### Directory field · level 0

**Use:** Navigation-rich ending after the conversion stage.

**CSS:** `background: #ffffff; border-top: 1px solid rgba(104,107,130,0.12); padding-top: 40px`

**Observed:** A pale lower band uses the canvas color and 32px vertical padding. Premium pages switch the directory to dark panel and the lower band to night.

#### Premium night · level 0

**Only for:** premium-service pages

**Use:** Continuous dark setting.

**CSS:** `background: #0b0611; color: #ffffff`

**Observed:** Subtle purple pools and metallic objects provide light without introducing bright full-width cards.

#### Premium exhibit · level 1

**Only for:** premium-service pages

**Use:** Compact benefits and qualification panels.

**CSS:** `background: radial-gradient(at 51.43% 106.03%, #382e4b 0%, #16121f 100%); border-radius: 20px; padding: 32px`

**Observed:** A separate 1px padded wrapper fades a gray edge diagonally from upper-left to lower-right; inner content is softly illuminated from below.

**Transfer:** Use a thin gradient edge, not a uniform bright outline.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #7132f5; color: #ffffff; border-radius: 12px; height: 48px; padding: 13px 16px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `button` — Kraken-Product 500 · 16px/22px

**Observed:** Text-first action centered under the main support line. Compact header variants are 36px high with 8px 12px padding and utility text; overview showcase variants are 52px high with 15px 16px padding.

**States:** Declared: hover background #8a61ff, text white, background-image none; focus-visible solid 2px outline with -2px offset; active background #8a61ff. Compact header and some repeated actions use #5b1ecf instead.

### Soft action

**Use:** Repeated conversion after explanatory content, subordinate to the opening action.

**CSS:** `background: rgba(133,91,251,0.16); color: #7132f5; border-radius: 12px; height: 48px; padding: 13px 16px`

**Text style:** `button` — Kraken-Product 500 · 16px/22px

**Observed:** The same text and geometry as the main action with a much lighter fill. Compact login variant uses utility text at 36px height.

**States:** Declared: hover and active background rgba(133,91,251,0.32), text #7132f5; focus-visible solid 2px outline with -2px offset.

### Navigation bar

**Use:** Persistent cross-product and account navigation.

**CSS:** `background: #ffffff; height: 64px; backdrop-filter: blur(64px); display: flex; align-items: center; justify-content: center`

**Text style:** `utility` — Kraken-Product 500 · 14px/20px

**Observed:** Small purple symbol and a compact horizontal product list sit left; locale, search, login and sign-up sit right within the content container. The full-width bar stays above the page. The premium variant is night-colored with white links.

**Transfer:** Use a small identity mark, short destination labels and a clear compact account pair rather than a large logo masthead.

### Process card

**Use:** Explain a short sequence using text and product evidence.

**CSS:** `background: #ffffff; border-radius: 20px; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; gap: 12px`

**Text style:** `step-heading` — Kraken-Brand 700 · 20px/28px

**Observed:** Title and body are left aligned in a text block inset 28px at top and sides, with 8px between them. A 404px-square illustration occupies the lower region of a 404×580px card; image contents deliberately cross or clip against card edges.

**Transfer:** Give each step one recognizable interface outcome, not a decorative icon.

### Benefit panel

**Use:** Make one quantitative or operational benefit tangible.

**CSS:** `background: #ffffff; border-radius: 20px; overflow: hidden; display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr))`

**Text style:** `card-heading` — Kraken-Brand 700 · 24px/32px · tracking -0.021em

**Observed:** The wide panel pairs an enlarged interface vignette on the left with centered copy on the right, limited to 404px. Two half-width panels below put text over media. A small centered qualification caption sits outside the wide panel.

**Transfer:** Use product-specific outcomes and a simplified real control or status state. Keep caveats outside the promotional card.

### Question row

**Use:** Compact objection handling.

**CSS:** `background: transparent; color: #686b82; min-height: 56px; padding: 16px 0px; box-shadow: inset 0px 1px 0px 0px rgba(104,107,130,0.24); display: flex; align-items: center; justify-content: space-between`

**Text style:** `body` — Kraken-Product 400 · 16px/22px

**Observed:** One full-width question and a right-hand 24px chevron; eight rows fit an 828px-wide column without enclosing cards.

**States:** Declared: hover transparent background; focus-visible solid 2px outline and 4px radius.

**Transfer:** Use actual questions as labels, with the whole row acting as the control.

### Directory link

**Use:** Footer destination lists.

**CSS:** `color: #686b82; text-decoration: none`

**Text style:** `small` — Kraken-Product 400 · 14px/20px

**Observed:** Repeated links sit in narrow columns under darker medium-weight titles with small right arrows. A separate right column holds stacked account actions and a row of social marks. On premium pages links become soft slate.

**States:** Declared: hover underline.

### Premium benefit card

**Only for:** premium-service pages

**Use:** Dense service benefits without losing the luxurious dark atmosphere.

**CSS:** `background: radial-gradient(at 51.43% 106.03%, #382e4b 0%, #16121f 100%); border-radius: 20px; padding: 32px; display: flex; flex-direction: column; gap: 4px`

**Text style:** `premium-card-heading` — Kraken-Brand 500 · 20px/28px

**Observed:** White-to-lavender title above soft slate body copy; a separate 1px gradient-edge wrapper encloses each card. Three columns with 20px gaps, with the final row allowed to be incomplete.

**Transfer:** Keep each benefit to a short title and two or three compact lines; do not force every card to carry a large illustration.

### Premium field

**Only for:** premium-service inquiry forms

**Use:** Narrow centered inquiry form.

**CSS:** `background: rgba(104,107,130,0.16); color: #9497a9; height: 48px; border-radius: 12px; padding: 2px 12px; display: flex; align-items: center; gap: 8px`

**Text style:** `small` — Kraken-Product 400 · 14px/20px

**Observed:** The translucent input sits over a dark panel base; required labels begin inside the field. Select controls use a small right chevron. Phone prefix and number form adjacent pieces; the stack ends with a full-width neutral action.

### Premium neutral button

**Only for:** premium-service pages

**Use:** High-contrast inquiry action on near-black stages.

**CSS:** `background: #f7f7fa; color: #101114; border-radius: 12px; height: 48px; padding: 13px 16px`

**Text style:** `premium-button` — Kraken-Brand 500 · 16px/22px

**Observed:** The form submit spans the 404px form width; opening actions hug their labels.

**States:** Declared: hover and active background #e5e6ec, text #101114; focus-visible solid 2px outline with -2px offset.

## Imagery and graphics

### Orbiting metallic sculpture

**Use:** Signature opening artwork and a later standalone product reminder.

**Observed:** Several floating silver discs tumble around a prominent violet-faced central disc. Faces are smooth, edges ribbed or beveled, with pearly cyan and lavender reflections. The 458×424px scene sits below the action and is dramatically lit against purple; a larger light-background version repeats the material without a frame.

**Transfer:** Model an abstract token, rounded instrument or small collection of product-shaped objects in the same polished silver-and-violet material. Minimum version: layered beveled SVG ellipses with white rim highlights and dark purple undersides.

**Build:** Arrange 6–8 ellipse groups in a roughly square field, with varying rotations and scale. Use narrow offset ellipses behind each face for thickness, a pale silver-to-slate face gradient, and a saturated violet inset on the main face. Add thin white rim arcs, low-opacity cyan edge reflections, and a blurred purple shadow beneath the cluster. Keep objects separate with open gaps; no bounding illustration panel.

### Purple atmospheric light

**Use:** Signature backdrop behind opening and closing content.

**Observed:** Charcoal fades into violet across a huge softly blended radial field. It acts as stage lighting, not a visible circular spotlight or rainbow mesh.

**Transfer:** Preserve the dark upper-left reading zone and the lower-right violet lift; exact stops are less important than the soft atmospheric scale.

**Build:** Fill the stage with radial-gradient(132.58% 133.41% at 94.88% 121.07%, #543496 20.04%, #1f1b27 100%). Clip only the opening to 32px corners; leave the final stage full bleed.

### Enlarged interface vignettes

**Use:** Process cards and benefit panels.

**Observed:** A few real controls, account summaries, progress graphs and status messages are enlarged until readable. White mockups use delicate gray edges and soft shadows; black summaries use high-contrast type and green outcomes. Cropped neighboring cards and partial phones imply a larger product without showing an entire dashboard.

**Transfer:** Rebuild only the task-relevant interface fragment for the new product. Use authentic content hierarchy, not a tiny unreadable screenshot. Restrict status colors to the interface; they do not become marketing accents.

### Hand-held product close

**Use:** The large final acquisition stage.

**Observed:** A realistic hand holds a front-facing phone with a bright white interface. The phone rises from the bottom of the purple field and is cut off at the section edge; the promise and acquisition control float above with generous separation.

**Transfer:** Use a tightly isolated hand-held device or a credible product object rising from the bottom. For a non-device product, use its polished physical metaphor with a clearly rendered result on its face.

### Liquid chrome ribbons

**Only for:** premium-service pages

**Use:** Opening surround and bottom corners of the inquiry stage.

**Observed:** Large inflated purple-chrome loops and rounded star-like forms intrude from the edges, with bright pearl streaks, black reflective hollows and occasional warm reflections. They frame rather than obscure a narrow central text or form column.

**Transfer:** Use a small family of sculptural loops around a dark central service story. Minimum version: SVG rounded tubes with multiple highlight strokes, not flat outlined stars.

**Build:** Draw broad, closed, rounded paths around the outer corners; layer a dark purple thick stroke, a narrower lavender gradient stroke and a thin offset white highlight. Add a blurred violet duplicate behind the paths. Vary scale and crop forms beyond the section boundaries, keeping the central 404px form corridor clear.

### Device showroom

**Only for:** multi-product overview pages

**Use:** Wide dark product chapters and paired feature tiles.

**Observed:** Laptops, fans of phones and physical payment cards sit under centered copy. Media grow toward and beyond the lower boundary of 20px-rounded dark panels; local purple, gray or restrained warm glows distinguish products. A paired tile uses a shiny oversized toggle as a functional metaphor.

**Transfer:** Give each product one theatrical object or a small device fan, preserving the centered text-over-object hierarchy and restrained localized lighting.

### Icons

**Observed:** Functional chevrons and utility symbols use mostly 20px or 24px boxes and 2px rounded strokes in slate or lavender. Social marks in the footer are stronger solid silhouettes, around 28px.

**Transfer:** Use simple rounded outline utility icons; reserve solid marks for platform identities. Keep illustration separate from the icon system.

## Section recipes

How recurring sections are built.

### First screen: Violet product opening

**Observed:** A 64px white Navigation bar sits above a 20px pale gap. The Violet stage is inset 20px from the page edges, 1400px wide and 988px tall, with 32px corners. Back-to-front layers are the radial lighting field, the centered 828px text stack, the action, then the metallic sculpture below. An 80px top inset precedes a 24px gradient product label; 32px later the white 58px/66px weight-700 promise occupies two lines and about three fifths of the page width. Its 24px/32px support is separated by 8px and wraps within the same measure. The Primary button follows after 32px, then the 458×424px Orbiting metallic sculpture after 48px. Within the first 900px the full label, promise, support, button and most of the sculpture are visible; the sculpture's lowest objects and small attribution continue below the fold.

**Transfer:** Replace the subject with a short benefit-first promise and one tangible product metaphor. If custom 3D is unavailable, construct the beveled-disc fallback and give it equally deliberate lighting. Multi-product overview pages instead open compactly on lilac paper with regular-weight 48px text, an email action and a small proof strip; premium-service pages use 58px medium pearlescent type above a wide framed video and edge-cropped chrome loops.

**Avoid:** Do not turn this into a generic left-text/right-dashboard hero, stretch the promise across the entire width, or reduce the main artwork to a tiny icon.

**Text style:** `display` — Kraken-Brand 700 · 58px/66px · tracking -0.0172em

### Centered explanation and demonstration

**Observed:** Lilac canvas supports a centered heading-lg and lead paragraph within 828px, with 8px between them. A 40px gap leads to a 1252×704px demonstration; a repeated action sits 40px below the media. Main chapter pauses are 112px.

**Transfer:** Define the product in direct language, then show one concrete workflow at a scale that can be understood without zooming.

### Process gallery

**Observed:** A centered heading sits 32px above three Process cards in the process grid. Each card leads with left-aligned step-heading and body text, then an oversized square interface illustration. All cards align at their upper and lower edges.

**Transfer:** Use a short sequence of distinct user actions, allowing the illustrations to show the outcomes rather than adding ornamental numbering.

**Text style:** `heading` — Kraken-Brand 700 · 36px/44px · tracking -0.014em

### Benefit exhibit cluster

**Observed:** A centered heading and 18px support introduce a wide Benefit panel after 32px. Its two halves balance illustration and centered copy. A fine caveat caption sits below, followed by two equal White exhibits with text above interface details; a Soft action finishes the group.

**Transfer:** Lead with the clearest demonstrable benefit, then use smaller paired cards for secondary operational advantages.

### Acquisition pause

**Observed:** A centered heading-lg and lead sit above a compact white-backed download code, a 16px explanatory line and a 592px-square metallic animation on Lilac canvas. The object creates a spacious visual pause before questions.

**Transfer:** Use the most appropriate acquisition mechanism: scan, direct link or a single action. Keep its instruction near the control and the large artwork below it.

### Plain question stack

**Observed:** A centered 36px heading sits 32px above Question rows in an 828px measure. The rows have hairlines, no white outer panel and right-edge chevrons.

**Transfer:** Resolve practical uncertainty with concise questions, retaining the restrained appearance even when answers expand.

**Text style:** `heading` — Kraken-Brand 700 · 36px/44px · tracking -0.014em

### Monumental closing invitation

**Observed:** The full-width Violet stage returns at 988px height. A centered display promise begins about 107px into the stage; a 24px support line follows. A white-backed 128px code and a 16px instruction sit between text and the large Hand-held product close. The lower 450px of the stage is occupied by the edge-clipped device scene.

**Transfer:** Reprise the opening outcome more briefly and make the acquisition method unambiguous. Carry the same purple light and physical material language into a new bottom-rising product scene.

**Text style:** `display` — Kraken-Brand 700 · 58px/66px · tracking -0.0172em

### Directory and corporate tail

**Observed:** The Directory field has a 1252px inner container, multiple narrow link columns and a right-hand account/social column. Group titles use utility text; destinations use small text with 8px list spacing. A privacy/compliance strip precedes a separate lilac band with 32px vertical padding, a small parent identity line, compact product-family links and subdued legal copy. The premium variant uses dark panel above night instead of white above lilac.

**Transfer:** Separate the emotional closing from the functional directory. Keep the final corporate band visually subordinate rather than extending the dramatic stage to the end.

### Premium service chapters

**Only for:** premium-service pages

**Observed:** A large left-aligned 48px medium editorial positioning block uses an 828px measure. Centered premium-heading chapters alternate tabbed three-column Premium benefit cards, a hand-held product demonstration and a narrow qualification table. Numbers remain compact at 16px rather than becoming giant statistics; faint horizontal lines separate categories.

**Transfer:** For high-touch products, emphasize access and service detail through quiet tables and concise benefits, not a loud pricing grid.

**Text style:** `premium-heading` — Kraken-Brand 500 · 48px/56px · tracking -0.02em

### Sculptural inquiry ending

**Only for:** premium-service pages

**Observed:** A 58px gradient heading and short centered support lead to a 404px-wide form of 48px Premium fields, ending in a full-width Premium neutral button. Liquid chrome ribbons enter the lower corners over a broad purple floor glow. Disclosures then lead into the dark Directory field.

**Transfer:** Keep the central form unobstructed and use edge decoration to make a narrow conversion path feel substantial.

**Text style:** `premium-display` — Kraken-Brand 500 · 58px/66px · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible product demonstration → mechanics and benefits → practical reassurance → acquisition invitation → functional directory.

### Focused product adoption

1. **Promise** — Purple stage with a centered benefit promise, primary action and floating metallic metaphor.
2. **Product demonstration** — Plain-language definition above a large video.
3. **Mechanics** — Three illustrated process cards.
4. **Benefit proof** — Wide split panel and two half-width interface exhibits.
5. **Acquisition** — Download invitation and a freestanding metallic scene.
6. **Objection handling** — Hairline question stack and clearly separated disclosures.
7. **Closing call** — Full-width purple promise, download control and bottom-rising hand-held device.
8. **Directory** — White link field and lilac corporate tail.

**Transfer:** Use a vivid promise, understandable mechanics and one clear acquisition path; adapt the number and order of proof blocks to the product.

### Introduce a portfolio and route visitors to products

1. **Promise** — Compact pale opening with regular-weight type, sign-up input, social options and a three-part proof strip.
2. **Capability chapters** — Large inset dark showcases with centered text over device scenes.
3. **Focused capabilities** — Two dark tiles with a technical demonstration and a physical control metaphor.
4. **Browsable proof** — Light tabbed directory and market table.
5. **Closing call** — Small metallic icon above a 58px regular invitation and short support.
6. **Directory** — Disclosures, white destination columns and lilac corporate tail.

**Transfer:** Use the restrained opening and repeated showrooms when the goal is product selection rather than selling one offer.

### Explain a premium relationship and qualify inquiries

1. **Promise** — Pearlescent centered text, neutral action, chrome surround and wide framed video on near-black.
2. **Positioning** — Large left-aligned editorial statement with a quieter inquiry action.
3. **Capabilities** — Tabbed, softly illuminated benefit cards.
4. **Product demonstration** — Hand-held device in an open dark field.
5. **Eligibility** — Compact tabbed qualification table and explanatory notes.
6. **Reassurance** — Subtly raised dark invitation band with a small chrome object.
7. **Closing call** — Centered form framed by metallic sculptures and floor light.
8. **Directory** — Detailed disclosures and a dark two-tier footer.

**Transfer:** Use the all-dark variant for selective or high-touch services; replace eligibility facts with genuine requirements and keep the inquiry form central.

## Writing

Direct, confident and practically encouraging. Benefits sound concrete and attainable, while limits and risks are stated plainly in a separate supporting register.

**Do not copy:** Do not reuse Kraken or associated product names, logos, distinctive marks, proprietary artwork, testimonials, eligibility thresholds, performance figures, rewards, pricing or claims. Source examples illustrate cadence only; substitute the new product's verified facts.

- **Addressing the reader:** Speak to the reader as you and your. The product may speak as we or our when taking responsibility, while explanatory passages name the product and state what it does.
- **Rhythm:** Short sentence-case headlines; crisp verb-led actions; support lines often chain two or three brief clauses. Longer explanatory paragraphs remain factual and avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the outcome and contrast it with the familiar constraint. | 6–10 words | “Trade crypto with [Brand]’s money, not yours”<br>“Own the power of your money” |
| Support | A sequence of short action-to-outcome statements. | 2–3 short sentences | “Pass a challenge. Unlock a funded account. Keep 80% of the profits you make.” |
| Chapter heading | Plain question or paired emphatic fragments. | 2–6 words | “Simple rules. Clear costs.”<br>“What you’ll receive” |
| Process label | Start with a familiar imperative and one object. | 2–4 words | “Pick your tier”<br>“Hit the target” |
| Action | Specific next step rather than abstract exploration. | 1–3 words | “Start your challenge”<br>“Confirm eligibility” |
| Reassurance | State the boundary or condition without burying it in promotional phrasing. | One concise sentence | “Illustrative example. Passing a challenge isn’t guaranteed, and only some clients receive a payout.” |

**Words and phrasing to use:** your; start; choose; keep; clear; simple; access; available; direct; no commissions; no time limit

**Avoid:** revolutionary; game-changing; moonshot hype; guaranteed returns; unlimited success; excessive luxury superlatives

**Rules:**

- Lead with what the user can do, then explain the mechanism.
- Use numbers when they clarify a real outcome or condition, not as decoration.
- Pair a positive benefit with its meaningful constraint nearby.
- Keep action labels consistent when they lead to the same destination.
- Reserve detailed contractual language for disclosures; retain a short human-readable caveat beside illustrative benefits.

## Do's and Don'ts

### Do

- Use the 58px/66px bold display for the default promise and closing reprise.
- Maintain an 828px text measure within the wider 1252px content field.
- Keep the middle chapters predominantly lilac paper and white, with purple concentrated in the stages and controls.
- Use 20px card corners and gutters, with 28px text insets for process cards.
- Give major product chapters about 112px of separation while keeping heading-to-support gaps at 4px–8px.
- Repeat the metallic material language in at least one freestanding object and connect it to a legible interface exhibit.
- Keep the final directory distinct: 40px top padding, compact 14px links and a separate 32px-padded corporate band.
- On premium-service pages retain the narrower 404px form and the softer weight-500 headline hierarchy.

### Don't

- Do not replace the 12px rectangular control geometry with fully pill-shaped conversion buttons.
- Do not give every white card a thick purple border or heavy drop shadow; separation is chiefly tonal.
- Do not promote green and red interface status colors into the marketing palette.
- Do not replace 24px product labels with widely tracked uppercase micro-eyebrows.
- Do not mix the weight-400 overview hierarchy and weight-500 premium hierarchy into the default bold product story.
- Do not fill the pale middle body with busy gradient meshes; large color fields belong to the stages.
- Do not render entire dashboards at thumbnail scale inside every card; enlarge one understandable fragment.
- Do not turn compact premium qualification figures into giant promotional statistics.

## Motion and responsive

### Motion

**Observed:**

- Color-related transitions use 0.15s cubic-bezier(0.4, 0, 0.2, 1); the navigation shares this declaration.
- Input labels declare all-property transitions of 0.2s cubic-bezier(0.4, 0, 0.2, 1).
- The technical overview demonstration declares a 12s ease-in-out infinite idle animation.

**Transfer:**

- Let color feedback remain quick and unobtrusive so metallic scenes remain the visual focus.
- If a product metaphor animates, retain a composed, readable static arrangement at rest.

**Unknown:**

- Exact entrance timings, scroll thresholds and playback choreography are not established.

### Responsive

**Observed:**

- The process grid declares a one-column small-screen variant; the wide benefit panel declares a one-column medium-screen variant.
- The full desktop utility cluster is declared visible from 1170px; the main content wrapper uses 16px or 18px side padding at smaller widths. Opening inner top padding has a 56px small-screen variant and an 80px desktop variant.

**Transfer:**

- Stack process exhibits and split benefit panels while preserving text-before-media order.
- Keep the sculpture below the opening copy; scale its scene to the available width rather than moving it beside the headline.
- On narrow premium inquiry layouts, keep chrome decoration outside the form corridor and let the form fill the padded width.

**Unknown:**

- Exact mobile typography, opening artwork scale and compact navigation presentation are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
