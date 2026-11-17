# ExpressVPN — reassuring serif theatre

## Overview

An approachable, editorial technology style that makes complex services feel useful and understandable. Mostly white and pale mint, it combines deep blue ink, green actions and occasional warm red accents with sturdy serif headlines and practical sans-serif text. Floating product scenes, softly shaded conceptual illustrations and spacious educational chapters give it a friendly, reassuring pace.

### Essentials

- Authority comes from a sturdy serif rather than oversized tech typography: FS Kim 64px/1 at weight 500 with -1px tracking for the opening, then 46px/50px section headings above Inter body copy.
- The opening is a centered promise over a pale mint product stage: a white-to-#dae8e7 gradient, paired 62px-high actions, a compact proof strip and a central device surrounded by floating information cards. Recreate the stage with a simplified product mockup if no polished product render exists.
- Actions are plump capsules, not rectangular controls: 34px corners, 14px 24px padding and Inter 20px/1.5 bold. Green leads the opening; warm red radial-gradient buttons punctuate the educational chapters.
- Color is concentrated into islands within a predominantly white reading experience: pale grey illustration trays, a green/mint/peach proof-card trio and occasional deep navy bands. Do not turn every section into a colored panel.
- Concepts become tangible objects: rounded browser windows, devices, shields, tools and spotlights use clean vector silhouettes with restrained gradient shading, typically 329px-wide artwork in a 377px tray. Include this explanatory illustration language even when the product has no physical object.
- Proof feels like a set of editorial clippings: 385px-wide cards with 20px corners, 30px padding, uppercase 16px labels tracked at 0.1em, quotation text and attribution. Carry the green, muted mint and peach contrast into at least one proof cluster.
- Long-form calm is part of the identity: 100px section padding, an 830px reading measure, three-column cards with 32px gaps and a deep navy directory ending keep extensive content legible rather than dashboard-dense.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action green | `#0f866c` | `--color-green` | action, link, surface, accent, border | Opening action, inline links, accent headline phrase and leading proof card. |
| Lit navy | `#0c3956` | `--color-band-blue` | background | Lighter end of dark spotlight bands. |
| Deep blue ink | `#001d2f` | `--color-ink` | text, background | Primary text, dark directory and deep end of promotional gradients. |
| Midnight blue | `#001827` | `--color-footer-bottom` | background | Footer bottom strip and dark-band gradient stop. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm red | `#da3940` | `--color-button-red` | action | Bright center of chapter action buttons. |
| Deep red | `#b0272d` | `--color-button-red-deep` | action | Outer stop of chapter action buttons. |
| Proof peach | `#ffe4d4` | `--color-proof-peach` | surface | Third proof card behind dark text. |
| Proof mint | `#b7d1d0` | `--color-proof-mint` | surface | Second proof card behind dark text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted slate | `#667782` | `--color-muted` | text | Supporting captions and small platform labels. |
| Blue grey rule | `#ccd2d5` | `--color-rule` | border, text | FAQ separators, footer secondary text and comparison-stage gradient. |
| Mist mint | `#dae8e7` | `--color-hero-wash` | background | Lower stop of the pale opening stage. |
| Illustration grey | `#f5f5f5` | `--color-tray` | surface, background | Concept-art trays and restrained utility bands. |
| Cool white | `#f7f8f9` | `--color-utility` | background | Compatibility strip beneath an opening. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, raised cards and reversed text. Navigation uses white at 0.557 alpha over the pale opening. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| time-limited promotions | Offer purple | `#9e55a9` | `--color-campaign-purple` | background | Promotional ribbon gradient only. |

## Typography

- **FS Kim** — Opening headlines, section headings and small editorial leads. Sturdy, personable serif with broad proportions, wedge-like serifs and substantial contrast. OpenType features: "palt". If unavailable, use **Lora**. Use weight 500; preserve the broad measure and compact headline leading. Font stack: "FS Kim", "Lora", Georgia, "Times New Roman", serif.
- **Inter** — Body copy, navigation, actions, labels and card headings. Straightforward, high-x-height sans-serif; bold utility headings balance the expressive serif. OpenType features: "palt". Font stack: "Inter", Tahoma, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | FS Kim | 500 | 64px | 1 | -1px | Opening promise; one short phrase can switch to green without changing the recipe. |
| heading | FS Kim | 500 | 46px | 1.087 | normal | Main section leads and large split-row headings. |
| editorial-lead | FS Kim | 500 | 32px | 1.25 | normal | Small editorial proof leads above logo rows. |
| subheading | Inter | 700 | 24px | 1.333 | normal | Opening support line and explanatory subsection titles. |
| action | Inter | 700 | 20px | 1.5 | normal | Large marketing capsule actions. |
| card-heading | Inter | 700 | 18px | 1.444 | normal | Centered capability and use-case card headings. |
| faq-question | Inter | 700 | 18px | 1.333 | normal | Questions within the narrow accordion. |
| footer-heading | FS Kim | 700 | 18px | 1 | normal | Directory group titles in reversed blue-grey text. |
| body | Inter | 400 | 16px | 1.75 | normal | Paragraphs, explanations and card descriptions. |
| proof-label | Inter | 400 | 16px | 1.5 | 0.1em, uppercase | Source-category labels at the top of colored proof cards. |
| navigation | Inter | 600 | 14px | 1.715 | normal | Main navigation labels. |
| footer-link | Inter | 400 | 14px | 1 | normal | Compact links in the dark directory. |
| caption | Inter | 400 | 12px | 1.75 | normal | Supporting proof captions and fine explanatory notes. |
| micro-assurance | Inter | 400 | 10px | 2 | 0.14em, uppercase | Brief reassurance immediately beneath opening actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | FS Kim | 400 | 48px | 0.583 | normal | Single-line centered plan-selection heading; give the surrounding block generous separation. |
| pricing pages | price | Inter | 700 | 46px | 1 | normal | Main monthly price numerals, with smaller currency and period labels. |
| pricing pages | pricing-action | Inter | 600 | 20px | 1.4 | normal | Plan selection buttons; slightly lighter than marketing actions. |

**Notes:**

- Serif headings carry the emotional promise; bold sans-serif headings carry the practical explanation. Do not substitute one treatment for the other.
- Only the 64px display tightens tracking. Section headings and body remain normally tracked; uppercase proof labels and assurances deliberately open out.
- The pricing display uses the same serif family under a differently cased declaration; it is not a second visual font.

## Layout

**Density:** Airy editorial chapters with compact text rhythm inside each block.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Action icon gap and small price-stack gaps. |
| 16px | Opening action-to-assurance separation. |
| 20px | Card heading separation and navigation item gaps. |
| 24px | Paragraph rhythm, heading-to-support spacing, action-pair gap and illustration tray padding. |
| 30px | Proof-card padding. |
| 32px | Capability-card padding, grid gaps and container side padding. |
| 40px | Proof-card gaps and larger heading-to-media separation. |
| 60px | FAQ heading-to-questions separation. |
| 100px | Standard chapter top and bottom padding. |
| 130px | Desktop separation between illustration and text in split chapters. |

### Containers and grids

- **Primary container**: max width 1234px · side padding 32px. Centered general marketing container with 1170px of usable width.
- **Reading column**: max width 830px. Single-column explanations and centered section-heading groups.
- **Split chapter**: max width 1034px · 2 columns · gap 130px · side padding 32px. Centered 970px inner composition: approximately 463px text beside a 377px illustration tray; alternate sides.
- **Capability grid**: 3 columns · gap 32px. Equal 369px cards within the primary container; center the group.
- **Proof grid**: 3 columns · gap 40px. Equal 385px editorial cards in a slightly wider presentation.
- **FAQ column**: max width 628px · side padding 24px. 580px usable accordion centered within a broad white section.
- **Plan grid** (only for pricing pages): max width 1280px · 3 columns · gap 40px. Three 400px plan frames; center plan is visibly recommended.
- **Comparison table** (only for pricing pages): max width 1240px · 4 columns · gap 0px. One feature column and three 310px plan columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Marketing buttons | 34px |
|  | Capability cards | 24px |
|  | Proof cards | 20px |
|  | Illustration trays | 32px |
| pricing pages | Plan cards | 15px |
| pricing pages | Plan recommendation frame | 18px |
| pricing pages | Plan buttons | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Capability lift | `0px 0px 32px 0px rgba(0, 0, 0, 0.12)` | Diffuse all-around lift on white capability cards. |
|  | Proof lift | `0px 0px 15px 0px rgba(0, 0, 0, 0.1)` | Smaller halo under colored proof cards. |
| company-story pages | Timeline lift | `0px 0px 35px 0px rgba(0, 0, 0, 0.1)` | White chronology and quote cards. |

### Surfaces

#### White canvas · level 0

**Use:** Default long-form page ground.

**CSS:** `background: #ffffff; color: #001d2f`

#### Mint opening stage · level 0

**Use:** Default product landing opening.

**CSS:** `background: linear-gradient(#ffffff 0%, #dae8e7 100%); overflow: hidden`

**Observed:** Full-width pale wash with no hard panel edge; the device rises out of its lower boundary.

**Transfer:** Keep the wash broad and low-contrast behind both copy and product scene.

#### Illustration tray · level 1

**Use:** Contain small explanatory artwork in split chapters.

**CSS:** `background: #f5f5f5; border-radius: 32px; padding: 24px`

**Observed:** Soft-edged, unoutlined backing gives disparate illustrations the same visual footprint.

**Transfer:** Center one readable object, not a busy collage.

#### Capability card · level 1

**Use:** Reusable illustrated benefit groups.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 32px; box-shadow: 0px 0px 32px 0px rgba(0, 0, 0, 0.12)`

#### Navy spotlight · level 0

**Use:** Occasional high-contrast product or audience spotlight.

**CSS:** `background: linear-gradient(261deg, #0c3956 21.96%, #001827 82.57%); color: #ffffff; padding: 100px 0px`

**Observed:** White serif text on the left and a dimensional product illustration on the right.

**Transfer:** Use as an interruption to a white page, not its prevailing theme.

#### Compatibility band · level 0

**Use:** Low-key platform or integration strip.

**CSS:** `background: #f7f8f9`

#### Directory base · level 0

**Use:** Main marketing footer.

**CSS:** `background: #001d2f; padding: 25px 0px`

#### Offer ribbon · level 1

**Only for:** time-limited promotions

**Use:** Slim promotional announcement above navigation.

**CSS:** `background: linear-gradient(270deg, #001d2f 0px, #9e55a9 100%); height: 66px; color: #ffffff`

**Observed:** Short serif offer centered beside an underlined action; decorative seasonal silhouettes stay at the edges.

**Transfer:** Keep campaign decoration subordinate to the main page identity.

#### Pricing stage · level 0

**Only for:** pricing pages

**Use:** Background to the initial plan selection area.

**CSS:** `background: linear-gradient(#ffffff 0px, #ccd2d5 1121px)`

**Observed:** A cooler grey downward wash replaces the mint landing stage; the comparison area returns to white.

**Transfer:** Keep the transactional view visually denser and more neutral than a product story.

## Components

### Navigation

**Use:** Site-wide orientation above the product story.

**CSS:** `display: flex; align-items: center; gap: 20px; padding: 24px 33px; background: rgba(255, 255, 255, 0.557)`

**Text style:** `navigation` — Inter 600 · 14px/1.715

**Observed:** Brand mark at left; centered link group with dropdown chevrons; account, globe and small outlined conversion action at right. On a dark opening, navigation reverses its text.

**States:** Declared: hover changes the default light navigation label to #0f866c; focus-visible styling is unknown.

### Primary button

**Use:** Default opening conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; background: #0f866c; color: #ffffff; border: 1px solid #0f866c; border-radius: 34px; padding: 14px 24px; height: 62px; box-sizing: border-box`

**Text style:** `action` — Inter 700 · 20px/1.5

**Observed:** Text followed by a small right arrow. Width follows the label; align a secondary capsule alongside in the opening.

**States:** Declared: hover background-color #d4e301, color #001d2f, text-decoration none and box-shadow none; focus-visible styling is unknown.

### Secondary button

**Use:** Alternative action next to the primary opening action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: transparent; color: #0f866c; border: 2px solid #0f866c; border-radius: 34px; padding: 14px 24px; height: 62px; box-sizing: border-box`

**Text style:** `action` — Inter 700 · 20px/1.5

**Observed:** No arrow in the large opening alternative. The navigation uses a smaller outlined capsule.

**States:** Declared: hover background-color #d4e301, color #001d2f, text-decoration none and box-shadow none; focus-visible styling is unknown.

### Chapter button

**Use:** Conversion action following educational explanations and dark spotlights.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 10px; background: radial-gradient(circle, #da3940 0px, #b0272d 100%); color: #ffffff; border-radius: 34px; padding: 14px 24px; height: 58px; box-sizing: border-box`

**Text style:** `action` — Inter 700 · 20px/1.5

**Observed:** Same white label and right arrow as the opening action, with a warm red surface instead of green.

**States:** Declared: hover background-color #d4e301, color #001d2f, text-decoration none and box-shadow none; focus-visible styling is unknown.

### Capability card

**Use:** Small reusable illustrated benefits and scenarios.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 32px; text-align: center; box-shadow: 0px 0px 32px 0px rgba(0, 0, 0, 0.12)`

**Text style:** `card-heading` — Inter 700 · 18px/1.444

**Observed:** Compact conceptual illustration above the heading; longer variants add body copy beneath. Cards align in equal-width groups, with their heights set by content.

**Transfer:** Use a distinct visual metaphor per benefit while maintaining consistent image scale.

### Proof card

**Use:** Editorial social proof cluster.

**CSS:** `display: flex; flex-direction: column; gap: 24px; background: #0f866c; color: #ffffff; border-radius: 20px; padding: 30px; box-shadow: 0px 0px 15px 0px rgba(0, 0, 0, 0.1)`

**Text style:** `body` — Inter 400 · 16px/1.75

**Observed:** Uppercase proof-label, optional bold rating lead, quote, attribution and source mark; small italic disclosure sits at the bottom. Companion cards use proof mint and proof peach with deep blue text.

**Transfer:** Keep each card's source category visible; differentiate types of proof rather than repeating identical testimonials.

### FAQ row

**Use:** Narrow late-page objection handling.

**CSS:** `padding: 20px 0px 22px; border-bottom: 2px solid #ccd2d5`

**Text style:** `faq-question` — Inter 700 · 18px/1.333

**Observed:** Semantic expandable row with bold question and a small downward chevron aligned to the right. Collapsed rows are 68px high.

**Transfer:** Use concise questions whose answers resolve a real purchasing uncertainty.

### Directory footer

**Use:** Dense but calm ending to marketing and editorial pages.

**CSS:** `background: #001d2f; padding: 25px 0px; color: #ccd2d5`

**Text style:** `footer-link` — Inter 400 · 14px/1

**Observed:** A slim related-reading rail and rule precede three grouped link columns. Small serif group headings separate compact sans links; a lower #001827 strip holds copyright, policy links and social icons. Pricing instead ends with a small white legal-link row.

**Transfer:** Organize by practical reader tasks; preserve the contrast between spacious body chapters and compact directory.

### Plan card

**Only for:** pricing pages

**Use:** Compare subscription tiers before the detailed matrix.

**CSS:** `background: #ffffff; border-radius: 15px; padding: 21px; display: grid; gap: 20px`

**Text style:** `subheading` — Inter 700 · 24px/1.333

**Observed:** Tier name, large sans-serif price with smaller currency/period, term and billing details, full-width pill action, assurance and feature list. The recommended center tier sits inside a 4px navy-to-green frame with an 18px outer radius and a label above; its action is filled green while neighbouring plans are outlined.

**Transfer:** Make the commercial differences readable before the feature checklist.

### Plan action

**Only for:** pricing pages

**Use:** Primary selection within the recommended plan and final pricing assurance.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 15px; background: #0f866c; color: #ffffff; border-radius: 9999px; padding: 15px 35px; height: 55px; box-sizing: border-box`

**Text style:** `pricing-action` — Inter 600 · 20px/1.4

**Observed:** Wide capsule spans the plan content. Compact comparison-header versions use smaller vertical padding.

## Imagery and graphics

### Floating product theatre

**Use:** Signature product scene in the light opening.

**Observed:** A central upright phone with bright interface artwork is surrounded by small translucent white information cards. The scene is roughly 770px wide and 370px tall, rising from the bottom of the mint stage; its lower edge extends beyond the first viewport. Soft white halos, subtle shadows and partial overlaps make the information feel weightless.

**Transfer:** Stage the new product's central working surface with small, meaningful outputs around it. If no device is relevant, use a single clean application panel with three to five small result cards.

**Build:** Place a centered 220px-wide rounded device or app panel inside a 770px scene. Arrange compact 100–160px-wide white cards at staggered heights on both sides, behind and in front; use rgba(255,255,255,0.8), 16px corners, a 20px white glow and a soft low-alpha dark shadow. Keep the product itself sharp and the outer cards visually lighter; use actual meaningful labels, not decorative fake charts.

### Shaded conceptual illustrations

**Use:** Signature recurring language for capability cards and alternating chapters.

**Observed:** Simple vector-like objects—devices, lamps, globes, tools and shields—combine deep navy silhouettes, cream/mint accents and selective bright color. Shading is smooth and directional, with little surface texture. Standalone chapter objects sit inside illustration trays; card illustrations occupy a compact upper zone rather than edge-to-edge photography.

**Transfer:** Translate abstract benefits into one legible everyday metaphor. A simple, well-composed SVG with two or three tones is the minimum acceptable version.

**Build:** Use a 329px SVG artboard; construct the object from rounded rectangles, circles and a few clean paths. Use deep blue outlines or silhouettes, pale mint/cream secondary shapes and one colored focal shape. Apply linear gradients only to broad surfaces and a faint ground ellipse; avoid elaborate perspective. Position centrally with 24px breathing room inside the Illustration tray.

### Dimensional spotlight object

**Use:** Large object on the right side of a navy spotlight band.

**Observed:** An isometric laptop is ringed by translucent glass-like panes and a low oval platform. The display is luminous, while blue-green translucent shapes tie the object to the dark background.

**Transfer:** Use a simplified product perspective render or SVG with three floating panes. Keep the object self-contained rather than adding a whole futuristic environment.

**Build:** Create a tilted device from parallelograms over a broad low-opacity blue ellipse, layer two or three blue translucent rounded panes around its rear edge and place a brighter product surface in front. Confine soft glow to the immediate object.

### Human-use photography

**Only for:** company-story openings and feature-page closing calls

**Use:** Make a trust story or final reassurance human.

**Observed:** Wide domestic scenes show people with devices: a couple relaxing together or a close-up of hands using a laptop. Deep navy tint lowers contrast and saturation; text occupies the left while faces or hands remain readable to the right.

**Transfer:** Choose natural, unposed usage photography with open space for text. Darken sufficiently for white serif headlines without making the subject disappear.

### Chronology illustrations

**Only for:** company-story pages

**Use:** Milestone carousel and long-term credibility.

**Observed:** White 20px-radius cards carry a bold year, a rectangular red, green or cream illustration field, and a brief milestone caption. Cards use diffuse shadows and sit beneath small year tabs with a thin active underline.

**Transfer:** Show meaningful changes in the new product's development with simplified artifacts; do not turn the timeline into a dense historical table.

### Assurance emblem

**Only for:** pricing and risk-reversal sections

**Use:** Tangible visual counterpart to a trial or guarantee.

**Observed:** A pale desk calendar is overlapped by a green or navy shield with large white serif numerals. It appears on white in the pricing close and as a smaller trust illustration in the company story.

**Transfer:** Represent a real assurance with a calendar, shield or clearly labelled certificate; substitute the new product's truthful terms.

**Build:** Draw a cream rounded calendar rectangle with a muted blue top bar, dark binder rings and a grid of white squares; overlap a green shield path on its upper-right side. Center one short serif numeral or promise in the shield and a tiny spaced uppercase caption below.

### Icons

**Observed:** Small functional chevrons and arrows are restrained; 16–24px utility icons accompany links and navigation, with larger illustrated symbols reserved for cards. Pricing checkmarks use a 12px white stroke at 2px with round caps inside 20px green circles; social marks are solid 24px glyphs.

**Transfer:** Use clean two-stroke chevrons and arrows, not chunky app icons. Keep elaborate shaded artwork separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Centered product-stage opening

**Observed:** The Mint opening stage spans the full width beneath a 66px promotional strip when a campaign is active. Navigation occupies a 103px band over the same light ground. A centered 64px serif promise stretches across roughly two-thirds of the viewport; the short final phrase turns green. Below it sit a bold 24px support line, Primary button and Secondary button separated by 24px, then Micro-assurance and a compact horizontal ratings/recognition strip. Back-to-front layers are mint wash, floating white information cards, sharp central device, then the unobstructed copy stack. In the first 900px the entire copy/action/proof stack and upper product scene are visible; the central device continues below the fold. The scene fills much of the lower third rather than competing beside the headline.

**Transfer:** Use one concise product promise with a highlighted outcome, two complementary actions and truthful proof. Recreate Floating product theatre with a simplified panel when no hero render exists. Feature-detail openings instead use a dark split composition with left-aligned 64px white headline and one large symbolic object at right; company-story openings can place the same left-aligned stack over tinted human-use photography. Pricing opens with a minimal brand/language header, centered 48px serif heading and plan grid rather than this product stage.

**Avoid:** Do not replace the central product scene with a generic stock-photo rectangle or put the copy and device into a conventional equal-width split hero. Do not scale the serif promise into a huge all-caps wall.

**Text style:** `display` — FS Kim 500 · 64px/1 · tracking -1px

### Editorial heading and reading chapter

**Observed:** Centered Heading within the Reading column; support copy starts 24px beneath. Longer prose becomes left-aligned below, using Body with 24px paragraph separation and Subheading for practical subtopics. Sections generally have 100px vertical padding; diagrams can sit centered between the heading and explanation.

**Transfer:** Explain the product in small conceptual chapters; vary the amount of prose without losing the narrow reading measure.

**Text style:** `heading` — FS Kim 500 · 46px/1.087

### Alternating illustrated chapter

**Observed:** Split chapter pairs roughly 463px of copy with the Illustration tray across a 130px horizontal gap. Artwork is about 329px wide inside its backing; heading, paragraphs and optional Chapter button align as one vertical text stack. Reverse sides between adjacent chapters and vertically center the object against the copy.

**Transfer:** Use the same structure for mechanisms, benefits or setup steps. Prefer one meaningful metaphor over a full UI wall.

### Capability card group

**Observed:** A centered Heading leads the Capability grid. Capability card places a small illustration above Card-heading; longer scenario versions add Body. Equal columns and shared upper image zones keep a large set readable.

**Transfer:** Group related benefits or situations; use the number of cards justified by the content rather than reproducing a fixed count.

### Colored editorial proof

**Observed:** A centered Heading sits above three Proof cards in green, proof mint and proof peach, with 40px inter-card gaps. Category labels are uppercase and tracked; attribution and source marks anchor the lower portion. A separate Editorial-lead and horizontal publication-logo row can extend the proof section.

**Transfer:** Use verified review, user and expert proof categories or equivalent independent sources. Preserve both typographic category markings and varied card colors.

### Dark spotlight interruption

**Observed:** Navy spotlight combines left-aligned white Heading, Body and Chapter button with Dimensional spotlight object on the right. The full band is about 570px high with 100px top/bottom padding.

**Transfer:** Use for a distinct audience, advanced offer or major capability. Keep it a purposeful visual interruption rather than wrapping every benefit in navy.

### Narrow FAQ ending

**Observed:** Heading centers over the FAQ column; questions begin 60px beneath and use FAQ row. The white space around the 580px inner column is much broader than the questions themselves. The section flows directly into Directory footer.

**Transfer:** Resolve final objections using a short, focused group of questions; adapt the count to the new product.

### Transactional comparison

**Only for:** pricing pages

**Observed:** Plan grid first gives fast tier selection. A four-column comparison matrix follows, with a persistent compact price/action header, grouped feature headers, thin row rules and a subtly tinted recommended column. Check circles and small green values carry the comparison rather than oversized icons. A related-product carousel uses rectangular colored image tops on white cards with 16px corners and small circular previous/next controls.

**Transfer:** Keep plan choice readable without studying the matrix; use the detailed comparison only for the distinctions that matter.

### Risk-reversal close

**Only for:** pricing and feature-detail pages

**Observed:** The pricing variant is a white split row: 32px serif lead and plain reassurance copy on the left, green Plan action beneath and Assurance emblem on the right. It ends in a compact white legal row. The feature-detail variant uses a 650px full-width photograph darkened with navy, white 46px Heading and Body on the left plus Chapter button, immediately followed by Directory footer.

**Transfer:** Match the close to the page's intent: transactional reassurance for a purchase view; human-use reassurance for a detailed product story. State actual trial or cancellation terms.

### Tabbed milestone story

**Only for:** company-story pages

**Observed:** Centered Heading above compact year tabs on a full-width grey rule; the active tab receives a darker underline. Three white cards with 20px corners and 30px padding show a year, rectangular artwork and caption. Circular previous/next controls sit nearby; a later tabbed proof group reuses the same calm horizontal organization.

**Transfer:** Use when a longer product or company story benefits from tangible milestones, not as a generic landing-page requirement.

## Page flow

**Storyline:** Promise → tangible explanation → capabilities and independent proof → deeper practical chapters → objections or risk reversal → page-appropriate footer.

### Broad product landing story

1. **Promise** — Centered pale product stage, paired actions and compact proof.
2. **Orientation** — Compatibility strip, product-family markers and a short explanation with illustration.
3. **Capabilities** — Illustrated three-column benefits, geographic breadth band and dark audience spotlight.
4. **Social proof** — Green/mint/peach editorial cards followed by recognition logos.
5. **Education** — Alternating benefit illustrations, scenario cards and a narrow mechanism explanation with diagrams.
6. **Objection handling** — Taxonomy cards and narrow FAQ.
7. **Ending** — Deep navy related-reading rail, grouped directory and darker legal/social strip.

**Transfer:** Use the broad arc to balance conversion with explanation; shorten educational detail to suit the new product.

### Transactional plan selection

1. **Choice** — Minimal brand/language header, promotional panel, centered serif title, term selector and three plan cards.
2. **Audience variant** — Compact dark team-oriented offer with illustration.
3. **Detailed comparison** — Persistent plan summary over grouped feature rows in a four-column matrix.
4. **Related products** — Horizontal illustrated product-card carousel.
5. **Risk reversal** — Plain-language guarantee beside a calendar/shield illustration and return-to-plans action.
6. **Ending** — Small white copyright and support/policy link row instead of the directory.

**Transfer:** Make this a denser scoped variant, with explicit terms and a clearly recommended middle option.

### Detailed capability landing page

1. **Specific promise** — Dark split hero with symbolic speedometer, white serif headline and red action.
2. **Navigation** — Slim sticky chapter-link rail beneath the main navigation.
3. **Demonstration** — Illustrated split explanation, annotated product image and practical examples.
4. **Technical depth** — Narrow prose chapters, bold sans subheads, green inline links and device diagrams.
5. **Ease of adoption** — Numbered setup chapter and focused outcome illustration.
6. **Trust and qualification** — Practical privacy explanation and bordered service-use note.
7. **Closing call** — Tinted human-use photographic reassurance with white copy and red action.
8. **Ending** — Full deep navy directory and darker legal/social strip.

**Transfer:** Use for one capability that deserves a sustained explanation; retain chapter navigation only when the content is long enough.

### Company and trust story

1. **Human promise** — Navy-tinted domestic photograph with left-aligned serif heading, mission line, green action and assurance.
2. **Context** — Compatibility strip then centered introductory and purpose chapters with small product imagery.
3. **Credibility** — Alternating illustrations and concrete explanations of operational safeguards.
4. **History** — Tabbed chronology with illustrated milestone cards.
5. **External trust** — Partner/impact cards, tabbed reviews and recognition logo strip.
6. **Objection handling** — Narrow FAQ.
7. **Ending** — Deep navy directory and darker legal/social strip.

**Transfer:** Replace institutional claims with the new organization's actual methods and proof; preserve the human opening and tangible credibility devices.

## Writing

Confident and reassuring, with a practical consumer-friendly explanation beneath each ambitious promise. Technical subjects are translated into everyday consequences rather than left as jargon.

**Do not copy:** Do not reuse ExpressVPN names, logos, product-family names, proprietary artwork, customer quotations, rankings, audit claims, country/device counts, discounts, prices or guarantee terms. Replace them with truthful material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' for accountable promises and the product name for capabilities. Explain what changes for the reader.
- **Rhythm:** Headlines are often short questions or benefit promises; support lines are direct and explanatory. Body paragraphs commonly use two or three medium-length sentences. Short standalone reassurances break up denser technical material.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Lead with a concrete category advantage or ask the reader's main evaluative question. | 5–12 words | “World's #1 VPN now up to”<br>“Fastest VPN: Just how fast is [Brand]?” |
| Supporting line | Summarize a cluster of reader benefits in one plain sentence. | 8–18 words | “Your all-in-one app for online privacy, security, and freedom”<br>“Privacy protection you can trust, built by experts who care” |
| Section heading | Ask a plain-language question or name an outcome with an active verb. | 3–10 words | “What is a VPN?”<br>“Protect your privacy”<br>“Kiss video buffering goodbye” |
| Primary action | Verb-led invitation to obtain, try or compare; longer labels can lower perceived risk. | 2–6 words | “Get the Deal Now”<br>“Start Your Risk-Free Trial”<br>“Compare Plans” |
| Practical explanation | Explain a mechanism, then its visible benefit to the reader. | One to three sentences | “As you connect to a secure VPN server, your internet traffic goes through an encrypted tunnel that nobody can see into—including hackers, governments, and your internet service provider.” |
| Closing reassurance | State the promise, then explain the simple next step if it does not work out. | Two short sentences | “If you’re not satisfied with [Brand], cancel anytime within 30 days and get a full refund.” |

**Words and phrasing to use:** your; works; easy; reliable; peace of mind; take control; try; protect; how it works

**Avoid:** disruptive ecosystem; military-grade hype without explanation; vague transformation promises; developer-only shorthand; forced irreverence

**Rules:**

- Pair a broad promise with an understandable mechanism or a relevant independent proof point.
- Use bold emphasis for a key term within an explanation, not whole paragraphs.
- Explain technical terms when first introduced; a short analogy can do more than a list of specifications.
- Keep reassurance close to the action and disclose material limits near the relevant claim.
- Seasonal wordplay belongs to a promotional ribbon, not the permanent educational voice.

## Do's and Don'ts

### Do

- Keep the default serif opening at 64px/64px, weight 500 and -1px tracking.
- Use 46px serif section leads and reserve 24px bold sans for practical subheads.
- Keep Body at 16px/28px with 24px paragraph spacing.
- Preserve 34px-radius marketing capsules and the 24px opening action-pair gap.
- Use 100px vertical chapter padding and the 830px reading measure to pace complex explanations.
- Use 32px gaps and 32px padding for white capability cards.
- Include a colored editorial proof cluster with 20px corners and 30px padding.
- Give the long-form marketing ending a navy directory with a darker bottom strip.

### Don't

- Do not render the main headline in a geometric sans; the sturdy serif is the source of its editorial authority.
- Do not track body copy like the 0.1em proof labels; normal tracking is the default.
- Do not make pale illustration trays look like elevated cards: their 32px corners have no heavy shadow.
- Do not flatten all actions into one treatment: the green opening and red chapter actions serve different moments.
- Do not replace diffuse card halos with a sharp directional black drop shadow.
- Do not fill every content section with mint or navy; white is the prevailing reading ground.
- Do not force marketing cards to the 15px pricing radius; the default capability radius is 24px.
- Do not add the full marketing navigation and directory to the transactional variant, which uses a minimal header and legal ending.

## Motion and responsive

### Motion

**Observed:**

- Marketing actions declare --color1 250ms ease, --color2 250ms ease and all 250ms ease transitions.
- Navigation labels declare 250ms transitions. Inline animated link backgrounds declare 0.4s background-size transitions.
- A slider animation is declared at 20s linear; its runtime behavior is not established.

**Transfer:**

- Keep the capsule shape stable while its color changes; use the declared short transition for the green/red-to-lime interaction.
- Use restrained horizontal carousel movement for proof and milestone groups rather than turning the editorial reading column into a moving scene.

**Unknown:**

- Focus-visible and active appearance are not established.
- Scroll-trigger timing and complete animation sequences are not established.

### Responsive

**Observed:**

- Desktop composition is defined at 1440px wide. Source rules include 768px, 992px, 1024px and 1200px breakpoints among many component-specific widths.
- Plan markup declares a single-column grid before its desktop three-column treatment.

**Transfer:**

- On narrow layouts, stack the copy above the conceptual object, reduce the 130px split gap and preserve the pale tray as a separate readable visual.
- Keep the central product scene centered; remove peripheral overlap before shrinking meaningful interface labels beyond legibility.
- Turn long chapter navigation and proof/milestone groups into horizontally navigable strips rather than squeezing their labels into many tiny columns.

**Unknown:**

- Exact mobile headline sizes, spacing and menu behavior are not established; the stacking guidance is a design recommendation rather than a measured mobile specification.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
