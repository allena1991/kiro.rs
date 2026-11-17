# Pop Site — polished product parade

## Overview

An approachable, showroom-like style for self-serve software and creator tools. Mostly white and pale cool gray, it pairs tightly packed geometric sans headlines with glossy device mockups and generous breathing room. Small sky-blue actions punctuate the light canvas, while occasional saturated blue and violet chapters make the product feel tangible and premium.

### Essentials

- Headlines feel like compact spoken promises: Satoshi 69px, weight 500, line-height 0.9 and -3.9px tracking, usually centered and sentence case.
- The opening is a product parade rather than a text-and-image split: a centered badge, headline and 40px claim form sit above five glossy phones, with the middle phone taller and the outer phones clipped by the viewport.
- Conversion feels like claiming something personal: a joined name-and-suffix field beside a cyan-to-blue 40px button with 26px corners, followed by a small reassurance line.
- White owns most of the page; color is concentrated in 110deg blue action gradients and isolated full-width blue or charcoal-to-violet chapters, not every card.
- Proof is staged as a real object: black glossy devices, angled interface details and softly shadowed white panels; include a device parade and a perspective product composition even when the substitute is a simple framed interface.
- Tiny friendly badges introduce monumental statements: 15px medium text in 10px-radius translucent white rectangles with a 6px icon gap; colored hearts or paper-plane-like symbols supply the wink.
- The close reprises the product parade and conversion promise, then settles into pale 76px FAQ rows and a restrained 1000px-wide white footer; the reprise device matters more than any fixed section order.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky cyan | `#00a8f5` | `--color-sky` | action, background, accent | Start of the action gradient and bright center of the blue chapter. |
| Action blue | `#3b82f6` | `--color-blue` | action, link | End of action gradients and inline customer links. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#5d00d9` | `--color-violet` | background | Saturated endpoint of premium conversion chapters. |
| Deep blue | `#004ecc` | `--color-deep-blue` | background | Outer blue chapter gradient. |
| Headline lilac | `#f0e3ff` | `--color-lilac` | text | Pale endpoint of reversed gradient headline text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#171717` | `--color-ink` | text, background | Primary headings and text; dark endpoint of the violet chapter. |
| Support gray | `#545454` | `--color-body` | text | Large supporting sentences. |
| Caption gray | `#6e6e73` | `--color-muted` | text, link | Secondary labels, footer headings, reassurance and neutral link hover. |
| Navigation divider | `#d2d2d7` | `--color-divider` | border | Thin divider separating navigation groups. |
| Input edge | `#d7dde0` | `--color-field-edge` | border | Suffix-field outline. |
| Card hairline | `#e8e8e8` | `--color-edge` | border | Visible card edge on white; built with #222222 at about 10% opacity. |
| Toggle gray | `#eaeaea` | `--color-toggle` | surface | Visible FAQ toggle fill; near-black at 9% opacity over white. |
| Ice blue | `#edf4ff` | `--color-hero-tint` | background | Very pale lower glow beneath the device parade. |
| Navigation frost | `#f5f9ff` | `--color-nav-tint` | background | Subtle bottom-center navigation wash. |
| Cool gray wash | `#f8f9fb` | `--color-wash` | background, surface | Soft section gradient endpoints and compact icon tiles. |
| Porcelain | `#fafafc` | `--color-panel` | surface | FAQ rows and the fixed suffix segment. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Dominant canvas, cards and reversed text. Badges use white at 30% opacity over the light canvas. |

## Typography

- **Satoshi** — Headlines, navigation, body, buttons and footer. Rounded geometric sans with compact, friendly lowercase and strong negative tracking. If unavailable, use **DM Sans**. Use weights 400 and 500; retain tight display spacing. Font stack: "Satoshi", "DM Sans", Arial, sans-serif.
- **Inter** — Question labels in the FAQ. Matter-of-fact neo-grotesk contrasting subtly with the geometric main face. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Satoshi | 500 | 69px | 0.9 | -0.0568em | Main promise and major chapter headlines; centered by default, left aligned in split chapters. |
| support | Satoshi | 500 | 21px | 1.4 | -0.03em | Support lines and illustrated feature-card titles. |
| question | Inter | 500 | 18px | 1.4 | -0.04em | FAQ questions. |
| card-title | Satoshi | 500 | 17px | 1.2 | -0.01em | Compact capability cards. |
| compact | Satoshi | 500 | 15px | 1.3 | -0.03em | Navigation, buttons, badges, card descriptions and compact lists. |
| footer | Satoshi | 400 | 13px | 1.2 | -0.03em | Footer links and column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| blue capability chapters | reversed-display | Satoshi | 500 | 64px | 0.9 | -0.0503em | White compact headline beside the large demonstration panel. |
| closing conversion reprises | closing-support | Satoshi | 500 | 28px | 1.2 | -0.03em | Single-line urgency statement below the closing headline. |

**Notes:**

- Medium weight, not bold, carries almost every marketing role. The headline's close line spacing and negative tracking create the visual force.
- Use the same display size for the opening and major section leads rather than a descending staircase of heading sizes.
- Reversed premium headlines retain the display recipe and use pale lilac-to-white clipped gradient text. Keep body copy solid white.
- No viewport-relative typography formula is prescribed; maintain intentional line breaks within 600–800px heading measures.

## Layout

**Density:** Airy at section scale and compact within controls, cards and footer groups.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Badge icon-to-label spacing. |
| 10px | Grid gutters, field-to-button gap and short title-to-description gaps. |
| 12px | Footer label-to-link group and compact icon gaps. |
| 20px | Main heading stack gaps and feature card padding. |
| 24px | FAQ padding and horizontal button padding. |
| 30px | Longer heading-to-support separations and split composition gaps. |
| 40px | Outer desktop gutters and major internal stack separation. |
| 60px | Split demonstration-to-copy gap and secondary section rhythm. |
| 80px | Standard major section vertical padding and footer padding. |

### Containers and grids

- **main-container**: max width 1000px · side padding 40px. Centered desktop content for the main feature grid, split proof chapters and footer.
- **heading-measure**: max width 800px. Centered display stack; narrower 600px measures create deliberate two- or three-line headlines.
- **feature-grid**: max width 1000px · 3 columns · gap 10px. Three equal illustrated cards; approximately 327px wide at desktop.
- **compact-capabilities**: max width 900px · 3 columns · gap 10px. Short icon-led cards above one broad interface composition.
- **faq-stack**: max width 800px · gap 2px · side padding 4px. A tight column of pale question rows.
- **blue-split**: max width 1000px · gap 60px. Large 600px-wide interface panel beside a 300px copy column, bottom clipped at the band edge.

## Corner radius

| Element | Radius |
| --- | --- |
| primary action | 26px |
| cards and badges | 10px |
| FAQ rows | 12px |
| icon tiles | 8px |
| joined form ends | 9999px (pill) |
| footer upper corners | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating proof | `0px 1px 10px 0px rgba(0,0,0,0.1)` | Small testimonial and creator identity cards, not every feature card. |
| icon tile | `0px 1px 11px 0px rgba(0,0,0,0.05)` | Small raised icon squares. |

### Surfaces

#### White canvas · level 0

**Use:** Default page background.

**CSS:** `background: #ffffff; color: #171717`

#### Frosted light chapter · level 0

**Use:** Subtle separation between long white chapters.

**CSS:** `background: linear-gradient(#ffffff 0%, #f8f9fb 100%)`

**Observed:** The tint is near-neutral and subordinate to the product images.

**Transfer:** Use pale gradients rather than heavy gray bands.

#### Parade glow · level 0

**Use:** Lower background of the opening device arrangement.

**CSS:** `background: radial-gradient(50% 50% at 50% 100%, #edf4ff 0%, #ffffff 100%); overflow: hidden`

#### Outlined white card · level 1

**Use:** Illustrated feature cards.

**CSS:** `background: #ffffff; border: 1px solid rgba(34,34,34,0.102); border-radius: 10px`

#### Blue capability band · level 0

**Use:** A strongly differentiated proof chapter.

**CSS:** `background: radial-gradient(75% 71% at 65.9% 45.5%, #00a8f5 0%, #004ecc 100%); color: #ffffff; overflow: hidden`

#### Violet conversion band · level 0

**Use:** Premium offer or pricing conversion chapter.

**CSS:** `background: linear-gradient(62deg, #171717 0%, #5d00d9 100%); color: #ffffff; padding: 0px 40px 80px`

**Observed:** A tall suspended object enters from the top beside a short left-aligned promise.

**Transfer:** Keep this as a distinct offer variant rather than recoloring the entire site.

#### Pale FAQ row · level 1

**Use:** Objection-handling list.

**CSS:** `background: #fafafc; border-radius: 12px; padding: 24px`

## Components

### Navigation

**Use:** Lightweight opening header.

**CSS:** `height: 72px; padding: 24px 40px; display: flex; justify-content: space-between; align-items: center; background: radial-gradient(50% 75% at 50% 100%, #f5f9ff 0%, #ffffff 100%)`

**Text style:** `compact` — Satoshi 500 · 15px/1.3 · tracking -0.03em

**Observed:** Small wordmark left; four plain text links right with a thin vertical separator between informational and account links. Navigation is visually much smaller than the hero.

**States:** Declared: hover text links change to #6e6e73 without underline; focus-visible not specified.

### Primary button

**Use:** Repeated conversion action.

**CSS:** `height: 40px; padding: 16px 24px; border-radius: 26px; background: linear-gradient(110deg, #00a8f5 0%, #3b82f6 100%); color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `compact` — Satoshi 500 · 15px/1.3 · tracking -0.03em

**Observed:** The button accompanies a joined input rather than a second competing CTA. In the violet band it sits underneath the field.

**Transfer:** Use a short ownership-oriented verb matched to the product.

### Claim field

**Use:** Inline personalized signup.

**CSS:** `height: 40px; width: 254px; display: flex; border-radius: 9999px; overflow: hidden`

**Text style:** `compact` — Satoshi 500 · 15px/1.3 · tracking -0.03em

**Observed:** Editable left segment is 169px wide with 20px left padding; fixed 85px suffix has a pale fill, right pill corners and a 1px cool-gray outline. The field and primary button are separated by 10px.

**Transfer:** Use a meaningful account, workspace or address suffix; preserve the joined structure.

### Proof badge

**Use:** Small chapter-introducing confidence cue.

**CSS:** `background: rgba(255,255,255,0.3); border: 1px solid rgba(34,34,34,0.102); border-radius: 10px; padding: 4px 12px 4px 6px; display: flex; gap: 6px; align-items: center`

**Text style:** `compact` — Satoshi 500 · 15px/1.3 · tracking -0.03em

**Observed:** A tiny colorful symbol precedes one short proof or category label. It is content-width, not a full-width announcement strip.

### Illustrated feature card

**Use:** A catalogue of tangible capabilities.

**CSS:** `background: #ffffff; border: 1px solid rgba(34,34,34,0.102); border-radius: 10px; padding: 20px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `support` — Satoshi 500 · 21px/1.4 · tracking -0.03em

**Observed:** Wide 287×210px device-detail image first, then title and a short compact description. Images sit on very pale backings with small rounded corners.

**Transfer:** Show one distinct action or output per image; use compact typography for descriptions.

### Capability card

**Use:** Short product benefit summaries.

**CSS:** `background: linear-gradient(124deg, #ffffff 0%, #f8f9fb 100%); border: 1px solid rgba(34,34,34,0.102); border-radius: 10px; padding: 20px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `card-title` — Satoshi 500 · 17px/1.2 · tracking -0.01em

**Observed:** Small 52px raised icon tile above a short title and compact two-line description. Three cards form a restrained strip above a large demonstration.

### FAQ item

**Use:** End-of-page objection handling.

**CSS:** `background: #fafafc; border-radius: 12px; padding: 24px; min-height: 76px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `question` — Inter 500 · 18px/1.4 · tracking -0.04em

**Observed:** Question left, 28px pale circular plus toggle right. The stack is almost contiguous, with 2px between rows; no heavy separators.

**Transfer:** Use direct buyer questions rather than keyword-heavy headings.

### Customer link

**Use:** Small verifiable customer reference.

**CSS:** `color: #3b82f6; text-decoration: none`

**Text style:** `compact` — Satoshi 500 · 15px/1.3 · tracking -0.03em

**Observed:** Lives next to customer attribution beneath a demonstration or quote.

**States:** Declared: hover color #5c9aff and underline; focus-visible not specified.

### Footer

**Use:** Quiet utility ending shared by long and short pages.

**CSS:** `max-width: 1000px; padding: 80px; background: #ffffff; border-radius: 24px 24px 0px 0px; display: flex; align-items: flex-start; justify-content: space-between`

**Text style:** `footer` — Satoshi 400 · 13px/1.2 · tracking -0.03em

**Observed:** Small identity block left, three sparse link columns in the middle and a muted rights line to the right. Column labels are gray, links dark; vertical link spacing is 19px.

**States:** Declared: hover links become #6e6e73 without underline; focus-visible not specified.

## Imagery and graphics

### Glossy device parade

**Use:** Signature opening and closing product display.

**Observed:** Five upright black phones carry varied finished pages with real portraits, photography and distinct interface themes. The center phone is largest and highest, side phones step down, and the outer pair run off both edges. Rounded glass, metallic rims and soft rear shadows give a tangible showroom quality; media occupies the lower half of the opening.

**Transfer:** Present different outputs or workflows in repeated glossy frames. Without 3D art, use carefully clipped interface images in black rounded device shells with a thin highlight and soft shadow; retain the raised central frame.

**Build:** Create five vertical rounded black frames with inner interface masks and a narrow light inset rim. Center the largest, set neighboring frames about 15% smaller and lower, and clip the outer frames at the page edges. Add soft shadows cast down and right over the Parade glow; keep reflections subtle rather than neon.

### Perspective product details

**Use:** Feature illustrations and alternating proof chapters.

**Observed:** Close views of phones reveal only the relevant part of a page; several are tilted diagonally. Other compositions fan multiple page cards through space on a pale gray backdrop or float a phone between metallic forms. Color comes mainly from the demonstrated work, not the surrounding text.

**Transfer:** Use real interface content, mild perspective and a clean pale stage. Minimum version: rotate two or three framed interface panels over a cool neutral backing with believable shadows.

**Build:** On a pale canvas, place two or three rectangular interface planes with 8–22px corner rounding; rotate them in opposing directions and overlap front to back. Use soft low-opacity black shadows to separate planes. Keep surrounding space uncluttered and let the UI carry the accent colors.

### Broad interface demonstrations

**Use:** Editor, membership and measurement capability proof.

**Observed:** Wide interfaces sit inside subtly rounded white panels. One montage pairs a broad dashboard with a narrower phone overlapping its right edge; the blue chapter instead crops a large white dashboard at the lower band boundary. Editor examples form an edge-clipped horizontal strip on colorful photographic backings.

**Transfer:** Show complete product workflows with readable overall hierarchy, not a collage of tiny labels. Keep demonstration colors inside the product-ui layer and maintain the large panel-to-small-copy contrast.

### Human proof video

**Use:** Customer credibility chapter.

**Observed:** A large 800×448px video shows a person speaking directly to camera in a real workspace, subdued cinematic lighting, black clothing and visible playback controls. It sits under centered copy, not behind it.

**Transfer:** Use a natural customer or expert demonstration with a restrained workplace background; preserve the broad landscape framing.

### Suspended premium object

**Use:** Premium conversion band and compact pricing opening.

**Observed:** A dark metal pass hangs from a purple woven strap entering at the top. Rounded bevels, small screw details and a smoky dark inset face make it feel like a physical access credential. The 270×642px artwork balances a 400px text column on the violet gradient.

**Transfer:** Create an analogous premium access object for the new product. Minimum version: a beveled dark card hung from a flat violet ribbon, with subtle highlights and a small product mark.

**Build:** Draw a narrow vertical ribbon descending from the top edge into a rounded dark rectangle. Layer an outer metallic gray rim, a black recessed inner rectangle, four tiny circular fasteners and a translucent angular pattern. Apply a faint violet glow near the bottom of the inset and a soft black shadow behind the object.

### Icons

**Observed:** Marketing icons are mostly 20–24px, either solid near-black or 1.5px round-ended gray outlines. Blue chapters use small white check circles. Tiny colored badge symbols are softer and more playful than the utility icons.

**Transfer:** Use consistent compact utility icons; reserve colorful pictorial symbols for proof badges, not every list item.

## Section recipes

How recurring sections are built.

### First screen: Product parade opening

**Observed:** The Navigation occupies the first 72px. On the White canvas and Parade glow, a centered Proof badge begins the content after 80px of breathing room, followed by the display headline within an 800px measure, a support sentence and Claim field plus Primary button. Heading-stack gaps are 20px; a small gray reassurance sits below the controls. The main promise is one line at desktop. Five glossy phones rise into the lower half, with the central device highest and outer phones clipped. Within the first 900px, the entire text/action stack and upper parts of the phone parade are visible; device bottoms and subsequent capabilities lie below the fold.

**Transfer:** Keep the same centered promise-to-object balance with product outputs in glossy frames; if no app exists, frame representative deliverables. A compact offer page instead opens with the Violet conversion band and a suspended premium object beside left-aligned copy.

**Avoid:** Do not replace the central parade with a small floating illustration beside a left-aligned hero or fit all device bottoms above the fold.

**Text style:** `display` — Satoshi 500 · 69px/0.9 · tracking -0.0568em

### Badge and monumental heading

**Observed:** Proof badge above a centered display statement, often two or three short lines, then support copy with 20px separation. Heading measures range from 600px to 800px. Standard chapter padding is 80px vertically.

**Transfer:** Introduce each major outcome with one short confidence cue and one direct promise; keep paragraph copy considerably narrower than the media.

### Illustrated capability catalogue

**Observed:** A centered heading pair leads into the feature-grid of Illustrated feature cards. The image/title/description order remains constant. A small overlapping symbol cluster and short continuation caption finish the catalogue.

**Transfer:** Group capabilities by the user's intended result; vary image content while preserving the uniform frame and narrow 10px gutters.

### Demonstration chapter

**Observed:** Centered heading and support above a wide video or edge-clipped horizontal editor strip. A short Capability card strip can lead into a 900px-wide interface montage with a phone overlapping a dashboard.

**Transfer:** Choose one broad workflow visual for the chapter, with compact summaries supporting rather than competing with it.

### Blue proof chapter

**Observed:** Blue capability band uses the blue-split layout: large white interface panel left, reversed-display heading and compact body right. The copy column has 24px stack gaps; small white check circles accompany a six-line capability list. The panel is bottom-clipped.

**Transfer:** Give one meaningful capability a saturated interruption with tangible product proof rather than a generic statistic wall.

**Text style:** `reversed-display` — Satoshi 500 · 64px/0.9 · tracking -0.0503em

### Alternating credibility split

**Observed:** A 1000px content row pairs a roughly 485×550px perspective demonstration with a left-aligned display headline, badge and support text. The side alternates between chapters. Small monochrome award marks sit beneath one text block.

**Transfer:** Use a focused testimonial, independent proof or demonstrable design quality; keep marks smaller than the headline and media.

### Premium offer

**Observed:** Violet conversion band contains the Suspended premium object and a 400px copy column. Display text is clipped to lilac-to-white gradient; solid white support names a free entry point and paid starting price. Claim field and Primary button stack vertically. Compact pricing adds a translucent category badge and proceeds directly to Footer.

**Transfer:** Explain the entry-level offer in one promise and one plain price sentence; do not force a plan grid when the offer needs no comparison.

**Text style:** `display` — Satoshi 500 · 69px/0.9 · tracking -0.0568em

### Conversion reprise and utility ending

**Observed:** The closing returns to a centered display promise, a closing-support urgency line and the Glossy device parade. A further badge, headline and claim form introduce the FAQ stack. FAQ item rows resolve objections before the white Footer; there is no giant final wordmark or dark footer.

**Transfer:** Echo the opening product display with a new conversion reason, answer the remaining practical concerns, then end with compact utilities.

**Text style:** `closing-support` — Satoshi 500 · 28px/1.2 · tracking -0.03em

## Page flow

**Storyline:** Promise → tangible product proof → capability chapters → credibility → offer → renewed conversion → objection handling → utilities.

### Long-form self-serve product landing page

1. **Promise** — Centered claim and inline signup over a glossy device parade.
2. **Capability catalogue** — Illustrated three-column cards show reusable outcomes.
3. **Human proof** — Customer video makes the benefit personal.
4. **Product demonstration** — Editor strip, focused feature art and an overlapping dashboard/phone montage.
5. **Capability spotlight** — Saturated blue chapter pairs a large panel with checked benefits.
6. **Credibility and offer** — Alternating perspective proof scenes surround a violet premium conversion band.
7. **Closing call** — Centered ownership promise reprises the device parade.
8. **Objection handling** — Another conversion cue and pale accordion stack lead to the quiet footer.

**Transfer:** Adapt the number and order of proof chapters to the product while retaining the parade, tiny badges, tangible perspective scenes and one strong color interruption.

### Short pricing and entry-offer page

1. **Offer** — Shared light navigation gives way to a violet two-column scene with suspended premium pass, free-entry promise, starting-price sentence and stacked claim form.
2. **Utilities** — The shared white footer immediately completes the page, without comparison tables or FAQ.

**Transfer:** Use this compact variant when pricing can be explained in one sentence; preserve its object-led presentation rather than inventing a dense plan matrix.

## Writing

Friendly, direct and visibly confident. The language makes professional results feel easy without turning into technical exposition.

**Do not copy:** Do not reuse Pop Site names, domains, customer identities, quotes, audience counts, geographical reach, awards, comparative claims or prices; replace them with substantiated content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. Name the product sparingly when it helps connect a benefit to the tool.
- **Rhythm:** Short sentence-case promises, usually four to twelve words; one explanatory sentence underneath. Periods are common, exclamation marks are not.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Simple imperative promising a desirable finished result. | 4–7 words | “Make a stunning site.” |
| Section heading | Concrete ability followed by an everyday convenience or outcome. | 5–12 words | “Customize from your phone or desktop.”<br>“You should look credible. [Brand] does that.” |
| Supporting line | One plain-language sentence explaining the capability or supplying credible proof. | 8–22 words | “Create, edit and publish from any device.” |
| Primary action | Ownership verb plus the thing the user receives. | 3–4 words | “Claim your site” |
| Offer | Lead with accessible entry, then disclose the paid starting point conversationally. | One short promise and one price sentence | “Free to create and share.”<br>“For pro-level features, plans start at just $10/mo” |
| FAQ | A direct question in the buyer's own words. | 5–12 words | “Can I use [Brand] as my portfolio?” |

**Words and phrasing to use:** your; make; create; claim; stunning; free; built-in; from any device; and more

**Avoid:** enterprise-grade transformation; synergize; revolutionary ecosystem; unlock limitless potential

**Rules:**

- Pair aspirational adjectives with a visible outcome rather than stacking adjectives.
- Write benefits as everyday actions, not abstract feature taxonomy.
- Use numbers only when they supply genuine proof or a clear price.
- Keep reassurance subordinate to the main action; a short risk-removal line is enough.

## Do's and Don'ts

### Do

- Keep main display type at 69px/0.9 with weight 500 and -3.9px tracking.
- Use 20px between headline, support and action groups.
- Keep the main desktop content width at 1000px and feature-grid gutters at 10px.
- Give primary actions the 40px cyan-to-blue pill construction.
- Use 10px-radius outlined cards with 20px internal padding.
- Use the blue band to contrast a large white interface panel with a narrow text column.
- End dense product storytelling with the 800px FAQ stack and compact white footer.
- Keep colored proof badges small and content-width.

### Don't

- Do not turn the near-black medium headlines into heavy 700-weight display type.
- Do not use violet as the ordinary page canvas; it belongs to the isolated premium offer.
- Do not replace faint card hairlines with dark 2px outlines.
- Do not add large drop shadows to the catalogue cards; elevation belongs to floating proof and small icon tiles.
- Do not make ordinary navigation links into filled buttons; the header uses small plain text.
- Do not scatter unrelated accent hues through marketing text; let demonstrated work carry varied colors.
- Do not stretch FAQ rows to the full viewport; hold their stack near 800px.
- Do not enlarge footer copy to the 21px support size; its light 13px scale is part of the quiet landing.

## Motion and responsive

### Motion

**Observed:**

- Customer and product demonstration videos provide moving content.
- No action or surface transition durations were specified; neutral links have declared gray hover states and customer links gain a brighter blue underline.

**Transfer:**

- Keep device arrangements and perspective compositions legible at rest; motion must not be needed to reveal the promise or action.

**Unknown:**

- Timing, scroll choreography and demonstration playback behavior are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px and 1200px.

**Transfer:**

- As a design adaptation, stack split chapters with the copy readable before the large panel, reduce the catalogue column count and retain the central raised device with side devices clipped.
- Let the claim form stack its action beneath the joined field when horizontal space is insufficient; preserve the 40px control height.

**Unknown:**

- Exact mobile font sizes, navigation replacement and narrow-screen device scaling are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
