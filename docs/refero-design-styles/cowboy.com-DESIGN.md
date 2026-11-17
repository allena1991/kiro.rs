# Cowboy — sculptural city flow

## Overview

A cinematic, fashion-minded product style where useful technology feels physical and effortless. Regular grotesk typography sits over sunlit urban photography, then gives way to sculptural studio details on chalk, sand and charcoal. The overall density is low, with long visual chapters and compact practical information near conversion points.

### Essentials

- The product name becomes part of the scene: a centered 200px/1 regular grotesk title with -5.7px tracking overlays a full-bleed 900px photographic opening; price sits below and a white pill anchors the lower edge.
- Headlines sound and look effortless rather than engineered: weight 400, 72px/1 with -0.025em tracking for major chapters, and 48px/1 for closer feature explanations.
- Actions are soft capsules against hard-edged photography: 56px height, 9999px radius, 16px/1 medium text; explanatory actions contain a separate 40px circular plus at the right.
- Color belongs mainly to the world being photographed: marketing canvases alternate #f5f5f5 and #1d1d1d, with restrained sand gradients for product staging, not saturated interface-colored bands.
- The object is both a whole and a landscape: include a large isolated profile and extreme material close-ups in asymmetric 644px and 426px panels, with 8px corners and 10px gaps. For intangible products, stage a device or a beautifully lit physical representation instead.
- The story repeatedly moves between life and mechanism: full-width human scenes contrast with inset studio mosaics, 60px side gutters and 110.4px chapter breathing room; preserve both devices even when using still photography.
- The close returns to the object before becoming useful: a warm product stage pairs a 52px promise and capsule action with an oversized object, followed by a charcoal directory footer with four link columns and a double-width subscription area.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pure white | `#ffffff` | `--color-white` | text, surface, action, border | Reversed text, light actions and selected light cards. |
| Chalk canvas | `#f5f5f5` | `--color-canvas` | background, surface | Default light page canvas. |
| Studio chalk sand | `#f1eee9` | `--color-sand-top` | background, surface | Lighter end of the studio material gradient. |
| Studio warm sand | `#f1e8da` | `--color-sand-bottom` | background, surface | Warmer end of the studio gradient and closing product stage. |
| Light table rule | `#e5e7eb` | `--color-rule` | border | Technical specification separators. |
| Object grey | `#e5e5e5` | `--color-grey-stage` | background | Full-width physical feature demonstrations. |
| Soft charcoal edge | `#dfdfdf` | `--color-soft-rule` | border | Visible result of charcoal at 10% over the chalk canvas for FAQ and feature dividers. |
| Silver caption | `#d4d4d4` | `--color-pale-text` | text | Small labels on dark photographic cards. |
| Directory grey | `#a3a3a3` | `--color-secondary` | text, link | Footer headings and product chapter navigation. |
| Global navigation grey | `#878787` | `--color-nav-grey` | text, link | Global menu text in its subdued state. |
| Paragraph grey | `#737373` | `--color-muted` | text | Support paragraphs and feature labels on light sections; also subdued support inside dark chapters. |
| Charcoal ink | `#1d1d1d` | `--color-ink` | text, background, action | Primary text, dark chapters, footer and dark actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technology and companion-software stories | Warm editorial canvas | `#f3efe9` | `--color-warm-canvas` | background | Background for extended technology explanations and companion-software closing information. |
| companion-software demonstrations | Demo atmosphere blue | `#dff0fd` | `--color-demo-blue` | surface | Cool endpoint of the pale blue-to-cream backing behind device demonstrations; not an action color. |
| companion-software demonstrations | Demo atmosphere cream | `#faf3ea` | `--color-demo-cream` | surface | Dominant cream endpoint behind device demonstrations. |

## Typography

- **SuisseIntl** — All primary display, body and navigation text. Clean neo-grotesk with open counters, restrained proportions and deliberately unbold display settings. If unavailable, use **Inter**. Use 400 and 500; retain the tight display tracking. Font stack: "SuisseIntl", "Inter", Arial, sans-serif.
- **monospace** (only for technology explainers) — Equipment-like chapter labels and compact technical annotations. Plain, widely spaced uppercase monospace. Font stack: "monospace", ui-monospace, SFMono-Regular, Menlo, Consolas, monospace.
- **ui-monospace** (only for community proof counters) — Odometer-like aggregate numerals. Equal-width numerals that read as individual rolling cells. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | SuisseIntl | 400 | 200px | 1 | -5.7px | Single product name over the photographic opening. |
| chapter | SuisseIntl | 400 | 72px | 1 | -0.025em | Centered major chapter promises and large photographic statements. |
| intro | SuisseIntl | 400 | 52px | 1.25 | -0.025em | Editorial product introduction above the isolated object. |
| closing-heading | SuisseIntl | 400 | 52px | 1.1 | -0.025em | Short conversion promise beside the closing object. |
| heading | SuisseIntl | 400 | 48px | 1 | -0.025em | Feature explanations and destination cards. |
| panel-heading | SuisseIntl | 400 | 36px | 1.05 | -0.02em | Compact dark conversion panel headline. |
| card-heading | SuisseIntl | 400 | 32px | 1.25 | normal | Benefit statements inside portrait photographic cards. |
| eyebrow | SuisseIntl | 400 | 22px | 1.05 | -0.015em | Sentence-case topic label above chapter headings. |
| body-lead | SuisseIntl | 400 | 20px | 1.472 | normal | Feature explanation paragraphs, usually muted with a few medium-weight phrases. |
| utility-heading | SuisseIntl | 500 | 18px | 1.472 | normal | Specification labels and footer column headings. |
| body | SuisseIntl | 400 | 16px | 1.472 | normal | Card copy, utility links and ordinary supporting text. |
| button | SuisseIntl | 500 | 16px | 1 | normal | Capsule action labels. |
| navigation | SuisseIntl | 500 | 16px | 1 | -0.025em | Global navigation links. |
| chapter-navigation | SuisseIntl | 500 | 14px | 1 | normal | Fixed product chapter menu. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| service and technology landing pages | secondary-display | SuisseIntl | 400 | 100px | 1 | -0.0283em | Centered hero promise or service name. |
| multi-product campaign openings | campaign-display | SuisseIntl | 400 | 100px | 0.9 | -0.025em | Left-aligned two-line editorial promise over moving imagery. |
| service FAQs and software overview sections | faq-display | SuisseIntl | 400 | 100px | 1.05 | -0.0283em | Oversized utility section title; right-aligned for FAQ. |
| savings-oriented closing calls | savings-heading | SuisseIntl | 400 | 66px | 1 | normal | Centered final question on a warm canvas. |
| community proof counters | counter | ui-monospace | 400 | 64px | 1 | normal | Large aggregate number with a smaller explanatory label below. |
| service stories and technical specifications | service-heading | SuisseIntl | 400 | 46px | 1.05 | -0.015em | Service feature headings and the specifications section title. |
| service and companion-software stories | explanatory-intro | SuisseIntl | 400 | 30px | 1.375 | normal | Broad introductory statements, usually occupying 726px of the content width. |
| companion-software stories | feature-label | SuisseIntl | 400 | 24px | 1 | normal | Ruled feature titles beneath paired media. |
| service FAQs | faq-question | SuisseIntl | 400 | 24px | 1.472 | normal | Full-width accordion questions. |
| service and companion-software stories | body-detail | SuisseIntl | 400 | 18px | 1.472 | normal | Explanatory paragraphs beneath service and software features. |
| technology explainers | technical-eyebrow | monospace | 400 | 12px | 1 | 0.083em, uppercase | Small equipment-like labels above explanatory copy. |

**Notes:**

- Regular weight carries the visual hierarchy; medium is reserved for actions, navigation and short inline emphasis.
- Most large headings tighten by -0.025em. The monumental product name tightens slightly more, while body text stays normally spaced.
- Core topic labels are sentence case sans, not tiny uppercase labels. The uppercase monospace treatment belongs to technical storytelling.
- Keep explanatory paragraphs much smaller than chapter headlines and narrower than the media; centered support commonly uses a 620px maximum width.

## Layout

**Density:** Airy visual chapters with tightly organized utility rows and controls.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight stacked copy and media mosaic gaps. |
| 20px | Card grid gutters, navigation gaps and compact vertical stacks. |
| 24px | Service paragraph separation and horizontal capsule padding. |
| 30px | Heading stacks and specification cell padding. |
| 40px | Portrait card padding and separation before supporting actions. |
| 60px | Desktop side gutters and footer top padding. |
| 110.4px | Standard vertical chapter padding and major gaps. |
| 220.8px | Double chapter separation before an isolated physical feature. |

### Containers and grids

- **page-container**: max width 1440px · side padding 60px. Full-width desktop chapters with a 1320px content area inside matching side gutters.
- **centered-support**: max width 620px. Centered supporting paragraphs under chapter promises.
- **detail-mosaic**: 10 columns · gap 10px · side padding 60px. Inset asymmetric studio gallery; six-column tall object detail paired with a four-column short detail, then reversed.
- **portrait-trio**: 3 columns · gap 20px · side padding 60px. Three approximately 426px-wide portrait cards; carousel variants show a partial next card.
- **footer-grid**: 6 columns · gap 0px · side padding 60px. Four 220px link columns followed by a 440px subscription column spanning two tracks.
- **software-grid** (only for companion-software stories): 12 columns · gap 20px · side padding 60px. Alternate five- and seven-column media panels, 538px and 762px wide at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | media and cards | 8px |
|  | circular controls | 50% |
| companion-software stories | software chapter top edge | 16px |

## Surfaces and depth

### Surfaces

#### Chalk canvas · level 0

**Use:** Default light editorial background.

**CSS:** `background: #f5f5f5`

#### Charcoal chapter · level 0

**Use:** Dark feature storytelling and closing directory.

**CSS:** `background: #1d1d1d; color: #ffffff`

**Observed:** Used in full-width bands rather than as a universal dark theme.

**Transfer:** Alternate with light object stages to give each capability its own visual pace.

#### Sand studio · level 0

**Use:** Inset physical-product detail backings and full-width closing object stage.

**CSS:** `background: linear-gradient(#f1eee9, #f1e8da)`

**Observed:** The closing stage reverses the gradient, with warm sand above the paler chalk sand.

**Transfer:** Use low-contrast warmth to reveal dark matte or pale satin materials; keep the gradient secondary to the object.

#### White card · level 1

**Use:** Reviews and compact utility cards.

**CSS:** `background: #ffffff; border-radius: 8px`

**Observed:** Flat without a decorative shadow.

**Transfer:** Separate through canvas contrast and spacing.

#### Grey object stage · level 0

**Use:** Physical component demonstrations.

**CSS:** `background: #e5e5e5`

#### Dark translucent panel · level 1

**Use:** Device feature cards within dark chapters.

**CSS:** `background: rgba(255, 255, 255, 0.05); border-radius: 8px`

**Observed:** A faint lift in tone, not frosted glass.

**Transfer:** Keep device or object imagery dominant and copy below the stage.

#### Warm editorial canvas · level 0

**Only for:** technology and companion-software stories

**Use:** Long explanations, model comparison and final practical calls.

**CSS:** `background: #f3efe9`

#### Software atmosphere · level 1

**Only for:** companion-software demonstrations

**Use:** Backings behind isolated devices and enlarged interface fragments.

**CSS:** `background: linear-gradient(45deg, #dff0fd -60%, #faf3ea 45.65%); border-radius: 8px`

**Observed:** A reversed -45deg direction is also used. Most of the panel reads creamy, with coolness entering from a corner.

**Transfer:** Keep the cream dominant and the blue very pale; use the same backing across a family of demonstrations.

## Components

### Primary button

**Use:** Primary conversion on a light surface.

**CSS:** `background: #1d1d1d; color: #ffffff; border-radius: 9999px; height: 56px; padding: 20px 24px`

**Text style:** `button` — SuisseIntl 500 · 16px/1

**Observed:** Solid capsule without a leading icon. The same construction reverses to white on photography or dark bands; the final conversion has a 60px-high, 20px-label variant.

**Transfer:** Use a direct verb for the main commitment.

### Light button

**Use:** Primary conversion on photography and dark chapters.

**CSS:** `background: #ffffff; color: #1d1d1d; border-radius: 9999px; padding: 20px 24px; height: 56px`

**Text style:** `button` — SuisseIntl 500 · 16px/1

**Observed:** Centered at the bottom of the opening or beneath centered explanatory copy; no ornamental outline.

### Detail capsule

**Use:** Expand a feature or open an explanation.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 20px; background: #1d1d1d; color: #ffffff; padding: 8px 8px 8px 24px; height: 56px; border-radius: 9999px`

**Text style:** `button` — SuisseIntl 500 · 16px/1

**Observed:** Label followed by a 40px round plus carrier with white at 15% opacity. White capsules on dark chapters use a darker plus carrier.

**Transfer:** Reserve the plus for deeper detail, not for ordinary navigation.

### Global navigation

**Use:** Persistent global identity and discovery.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 56px; padding: 4px 60px; position: fixed; top: 0px`

**Text style:** `navigation` — SuisseIntl 500 · 16px/1 · tracking -0.025em

**Observed:** Wordmark at left, centered text menu, account and bag icons plus a small test action at right. Over photography it reads white; light software openings use dark controls. A slim announcement strip can sit above it.

### Product chapter bar

**Use:** Orientation within a long flagship story.

**CSS:** `display: flex; align-items: center; gap: 40px; height: 56px; padding: 0px 60px; position: fixed; top: 0px; background: #1d1d1d; color: #a3a3a3`

**Text style:** `chapter-navigation` — SuisseIntl 500 · 14px/1

**Observed:** Product name at left, section anchors with 20px gaps, configuration and a light test action at right; replaces the global menu as the story advances.

### Portrait benefit card

**Use:** Capability discovery and practical next-step destinations.

**CSS:** `display: flex; flex-direction: column; justify-content: flex-end; position: relative; overflow: hidden; background: #1d1d1d; color: #ffffff; border-radius: 8px; padding: 40px; aspect-ratio: 2 / 3`

**Text style:** `card-heading` — SuisseIntl 400 · 32px/1.25

**Observed:** Edge-to-edge lifestyle photograph behind a bottom charcoal-to-transparent scrim. A small topic label precedes the benefit. Discovery cards place a 36px circular plus at top right; destination cards instead put a white action below the headline.

**Transfer:** Use one concrete use case per photograph, not a collage of unrelated benefits.

### Specification row

**Use:** Dense practical information after the visual story.

**CSS:** `border-top: 1px solid #e5e7eb`

**Text style:** `body` — SuisseIntl 400 · 16px/1.472

**Observed:** Rows occupy an 880px-wide table aligned right of a section title. Two equal cells use 30px top and bottom padding; medium 18px labels face regular 16px values.

### Footer link column

**Use:** Useful directory on the charcoal ending.

**CSS:** `display: flex; flex-direction: column; gap: 4px; margin-top: 10px; padding-right: 8px`

**Text style:** `body` — SuisseIntl 400 · 16px/1.472

**Observed:** A muted medium heading precedes a white link list; four columns sit beside a double-width subscription area. The brand mark is below the lists, followed by a fine-rule legal and locale strip.

### Subscription field

**Use:** Footer email signup.

**CSS:** `background: transparent; color: #ffffff; border: 0px; border-bottom: 1px solid #ffffff; padding: 8px 100px 8px 0px; width: 100%; height: 41px`

**Text style:** `body-detail` — SuisseIntl 400 · 18px/1.472

**Observed:** Underline-only field, with Subscribe aligned inside the right edge and small consent copy below. Social icons sit beneath the form.

**Transfer:** Keep it part of the directory, not a separate raised signup card.

### FAQ row

**Only for:** service FAQs

**Use:** Resolve purchase or subscription objections.

**CSS:** `display: flex; align-items: center; gap: 20px; width: 100%; text-align: left; border-top: 1px solid rgba(29, 29, 29, 0.1); padding: 20px 0px`

**Text style:** `faq-question` — SuisseIntl 400 · 24px/1.472

**Observed:** Question at left, small 18px plus at far right; closed desktop rows are about 76px tall.

**Transfer:** Keep answers in the same clean text system rather than adding colored panels.

## Imagery and graphics

### Sunlit urban cinema

**Use:** Opening and emotional transitions throughout a product story.

**Observed:** Human-scale street scenes, modern stone and glass architecture, warm cream clothing, olive shadows and blue sky. Camera positions range from a moving side view to low close-ups; directional sun gives long hard shadows and flowing fabric. Full-width media dominates the page and white type overlays darker regions.

**Transfer:** Photograph the product being used in a believable built environment, with one strong human gesture and room for text. A high-quality still with the same light and framing is the minimum equivalent when video is unavailable.

### Sculptural studio details

**Use:** Product overview, design mosaic and final conversion stage.

**Observed:** A clean full side profile alternates with enormous close-ups of matte black components, satin pale finishes, joints, lights and soft-edged geometry. Cream-to-sand backings and careful directional highlights make material and form legible; details extend beyond panel edges.

**Transfer:** Use a transparent isolated object with a soft grounding shadow and at least two close-up material studies. For software, render a device as a physical object rather than filling every panel with flat UI.

### Human proof wall

**Use:** Community and review transitions.

**Observed:** Many narrow portrait photographs mix candid owners, product use and short clips in dense rows; 10px gutters keep the collage orderly, without colored frames.

**Transfer:** Collect consistent portrait-ratio customer or use-context photos; use real variations in pose and setting instead of repeating a single polished model shot.

### Device and interface pair

**Only for:** companion-software stories

**Use:** Feature demonstrations within alternating wide and square panels.

**Observed:** Black device frames rise from below the panel edge on a pale cream and blue backing; a neighboring panel enlarges one map, alert or status fragment. Separate captions and hairlines below the image explain the feature.

**Transfer:** Show one realistic screen in a physical device and one isolated explanatory fragment. Keep interface color contained inside the demonstration.

**Build:** Place a rounded black device silhouette centrally in an 8px-rounded Software atmosphere panel; inset a legible screen, then pair with a separate square panel containing one enlarged UI event. Let the device continue below the panel boundary, with overflow hidden.

### Technical object annotation

**Only for:** technology explainers

**Use:** Explain invisible mechanisms and measured performance.

**Observed:** A dark three-quarter object on charcoal gradients is surrounded by a magnified component inset, tiny mono labels, a fine leader line and compact ruled metric cells. A second treatment pairs two tall dark panels, each dominated by a single oversized mechanical detail.

**Transfer:** Isolate the relevant component and use only a few directly connected annotations; replace a complex render with a carefully lit cutout and a simple magnified inset.

**Build:** Layer a large transparent object image over a subtle dark-grey vertical gradient. Add a smaller rectangular detail image at upper left; draw a 1px pale leader line from the active component to a small light label. Put three equal-width metric cells at lower right, separated by low-opacity white rules.

### Coverage map

**Only for:** location and service conversion sections

**Use:** Translate availability into a practical next step.

**Observed:** A pale near-monochrome map with dark teardrop pins sits beside a charcoal text panel, or inside a white 6px frame with an inset dark conversion card.

**Transfer:** Use a geographically honest light map with a limited number of clear dark pins. Pair it with a short availability statement, not an unrelated colorful illustration.

### Icons

**Observed:** Mostly compact monochrome SVG symbols: 16px in actions, 24px utility icons and 28px feature symbols. Plus and arrow glyphs sit inside circles; feature symbols sometimes sit in translucent 80px circular disks above a centered label.

**Transfer:** Choose restrained geometric symbols with consistent optical weight. Keep UI icon color tied to surrounding text and reserve multicolor for actual interface content.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product opening

**Observed:** A 1440px-wide, 900px-tall photographic scene fills the first screen. Back to front: sunlit architecture, moving user and full product, then a centered white product-name display spanning about half the width, a small availability capsule above it and a 22px price below. The global navigation is shallow at the top, with a slim announcement above. The main object occupies the lower and central scene, while the 200px title crosses the user and product silhouette. A white Light button is centered near the lower edge with 50px breathing room beneath. Within the first 900px the name, price, action and real-world product are all visible; descriptive prose and the isolated studio profile begin below the fold.

**Transfer:** Stage a different product at human scale in an equally strong directional-light scene and use its short name as the monumental overlay. Without campaign footage, use a still of the object in use; do not reduce the product to a small floating thumbnail. Service openings use the 100px secondary-display over hands-on photography and a down arrow rather than a buying button. Companion software opens on a warm light backing with a 100px dark promise above a very large physical device.

**Avoid:** Do not turn this into a split text-and-thumbnail SaaS hero, put the main description above the product name, or let a long name force the title into tiny type.

**Text style:** `display` — SuisseIntl 400 · 200px/1 · tracking -5.7px

### Editorial object introduction

**Observed:** Chalk canvas with 110.4px top padding; an inset 52px intro spans about 836px with left-aligned prose. Below, an isolated full profile is approximately 990px wide, accompanied by circular finish choices, price and paired capsule actions. A compact icon grid summarizes practical attributes.

**Transfer:** Explain the product in one fluid paragraph, then let the isolated object carry the next screen. Use a short, scannable attribute grid instead of another paragraph.

**Text style:** `intro` — SuisseIntl 400 · 52px/1.25 · tracking -0.025em

### Chapter promise and explanation

**Observed:** Topic eyebrow and centered 72px chapter headline precede a large cinematic or studio demonstration. The explanation is narrow, commonly 620px, in 20px muted text with selective medium emphasis; 40px spacing leads to a Detail capsule and a plain secondary test link beneath it. Three 80px icon disks can sit between title and explanation.

**Transfer:** Pair an experiential promise with a real mechanism, then offer deeper detail and a low-commitment trial action.

**Text style:** `chapter` — SuisseIntl 400 · 72px/1 · tracking -0.025em

### Asymmetric material mosaic

**Observed:** Sand studio panels in a 10-column inset grid with 10px gutters: a 644px-wide tall detail beside a 426px-wide short one, then the proportions reverse. The chapter is introduced with a centered promise; panels use 8px corners and tightly framed material details.

**Transfer:** Reveal finish, construction and use through two or three deliberately different magnifications. Preserve asymmetric balance rather than making equal feature tiles.

### Alternating product explanation

**Observed:** An eyebrow and 48px heading sit to one side of a large product or device image. Short support copy and a Detail capsule follow; subsequent feature chapters reverse sides or use a centered object above the text. Chapters commonly occupy 900px in height.

**Transfer:** Give each capability a different view of the object while keeping the same restrained type and action hierarchy.

**Text style:** `heading` — SuisseIntl 400 · 48px/1 · tracking -0.025em

### Inset trial invitation

**Observed:** An approximately 1080px by 494px image banner contains a 320px-wide charcoal copy panel at left with 40px padding, a 36px headline, short copy and a white capsule. The overall banner has 8px corners.

**Transfer:** Place a human-scale trial or consultation invitation between longer explanatory chapters, with imagery showing the experience.

**Text style:** `panel-heading` — SuisseIntl 400 · 36px/1.05 · tracking -0.02em

### Practical comparison and specifications

**Observed:** A centered choice prompt and capsule lead into profile images, names and fine ruled comparison rows. The later specification section shifts to a left title and an 880px table at right, with Specification row components and a plain technical-details link.

**Transfer:** Distinguish guidance for choosing from the exhaustive specification list; keep dense data late in the narrative.

### Warm product return

**Observed:** A 795px-high Sand studio stage reverses the gradient. A 360px copy stack sits at left with a 52px/1.1 closing promise, price, a prominent dark capsule and a plain secondary link. An isolated product approximately 990px wide dominates the right and extends toward the page boundary. The stage leads directly into the charcoal footer.

**Transfer:** Reintroduce the complete object after the close-ups and practical detail, now paired with a simple next step rather than new technical claims.

**Text style:** `closing-heading` — SuisseIntl 400 · 52px/1.1 · tracking -0.025em

### Utility directory ending

**Observed:** Charcoal chapter with 60px side and top padding. Four Footer link columns face a double-width Subscription field area. A white brand mark anchors the lower left; a 1px low-opacity light rule divides the final locale, legal and review strip. Total desktop footer height is 544px.

**Transfer:** Close with genuine routes to products, services, company and help, then a modest signup. Keep the footer visually connected to the story rather than turning it into another campaign.

### Service FAQ ending

**Only for:** service information pages

**Observed:** A 100px FAQ title is aligned right above six full-width FAQ rows. A separate 36px terms disclosure follows, then the Utility directory ending without a final product stage.

**Transfer:** Resolve the questions that block use of the service, keeping the large title and thin-rule accordions.

**Text style:** `faq-display` — SuisseIntl 400 · 100px/1.05 · tracking -0.0283em

### Warm savings call

**Only for:** technology and companion-software stories

**Observed:** After a local trial map and comparison table, a centered 66px question, muted support and dark capsule sit on Warm editorial canvas with 110.4px vertical padding. The Utility directory ending follows immediately.

**Transfer:** Use a relevant practical value question or eligibility check as the last call; keep this informational close distinct from the flagship object return.

**Text style:** `savings-heading` — SuisseIntl 400 · 66px/1

### Aggregate community proof

**Only for:** community-led marketing stories

**Observed:** A portrait wall is followed by a centered odometer-like row of 64px monospaced numerals and a small collective-activity caption, with generous 176px separation around the counter.

**Transfer:** Use a verified aggregate that expresses shared participation, presented as discrete numeric cells rather than a dashboard chart.

**Text style:** `counter` — ui-monospace 400 · 64px/1

## Page flow

**Storyline:** Experiential promise → whole-object introduction → capability chapters and material proof → human reassurance → practical choice and detail → renewed invitation → useful directory.

### Flagship physical-product landing page

1. **Promise** — Full-screen lifestyle scene with monumental product name, price and bottom capsule.
2. **Product introduction** — Editorial paragraph, isolated profile, finish selector, purchase and trial actions, then compact attributes.
3. **Capability chapters** — Portrait discovery cards followed by alternating cinematic scenes, studio mosaics and app demonstrations.
4. **Decision support** — Trial banner, comparison, local service reassurance, accessory personalization and reviews.
5. **Proof and detail** — Craft photography followed by the ruled technical specifications.
6. **Closing call** — Practical destination cards, warm oversized object return and charcoal directory footer.

**Transfer:** Use this as the default for a considered product purchase; vary chapter order to fit the product while retaining the contrast between use and material.

### Multi-product brand gateway

1. **Promise** — Two cinematic campaign promises alternate with huge studio product views and compact model switches.
2. **Capability proof** — Media endorsements, natural-language technology promise and a split feature-list/image demonstration.
3. **Community proof** — Portrait wall and odometer-like shared-activity counter.
4. **Trust and discovery** — Trial, choice prompt, cinematic craft and protection chapters, then three editorial cards.
5. **Closing discovery** — Large dark exploration scene with four pale destination cards, continuing into the directory footer.

**Transfer:** Use for a product family or brand introduction; make the ending a choice of useful destinations rather than a single buy action.

### Service subscription explanation

1. **Promise** — Hands-on service photograph, centered name and small service label.
2. **Explanation** — Short intro followed by a large real-world service image opposite text.
3. **Inclusions and process** — Plain grouped lists, then a photograph with overlapping phone and explanatory copy.
4. **Availability** — Monochrome map beside a dark local-service panel.
5. **Objection handling and ending** — Oversized right-aligned FAQ, separate terms disclosure and directory footer.

**Transfer:** Use compact inclusion lists and a believable service process instead of a long product specification narrative.

### Deep technology explainer

1. **Promise** — Full-bleed lifestyle opening with a centered short promise and tiny mono label.
2. **Context** — Warm centered prose, a large demonstration and a compact update statement.
3. **Mechanism proof** — Alternating cinematic 95px-headline chapters and dark annotated mechanical renders, compact metrics and paired detail panels.
4. **Experience** — A first-person device view connects the mechanism back to use.
5. **Closing call** — Local trial map, model comparison, centered savings question and dark directory footer.

**Transfer:** Keep the equipment-like mono annotations scoped to a genuine mechanism story; contrast technical proof with life-sized use scenes.

### Companion-software capability story

1. **Promise** — Warm light hero with a centered promise above an oversized device on the physical product.
2. **Capability chapters** — Short editorial introductions alternate with asymmetric device/interface pairs and full-bleed photographic interludes.
3. **Human context** — Lifestyle photos with overlapping narrow phone views and concise feature captions.
4. **Support** — Warm section for service and accessory utilities.
5. **Decision support and ending** — Local trial map, monumental overview title, ruled feature comparison, savings call and directory footer.

**Transfer:** Group a broad feature catalog into a few experiential chapters. Keep interface illustrations on pale repeated backings instead of adopting their internal colors as the page theme.

## Writing

Assured, tactile and lightly playful. Technical benefits are translated into ordinary sensations, with practical reassurance close behind the promise.

**Do not copy:** Do not reuse the Cowboy name, product names, proprietary technology names, wordmarks, award artwork, campaign photography, testimonials, prices, performance figures or geographic claims. Replace them with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your; use we for helpful service and protection. The product is described as an active companion rather than an impersonal platform.
- **Rhythm:** Short two-to-five-word chapter promises, sometimes split into fragments with periods; longer plain-language explanations follow in a narrow paragraph. Questions and understated wordplay provide energy without shouty punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero | A short name or compact promise that carries the scene. | 1–5 words | “Cruiser”<br>“Super. Natural.”<br>“Level up your ride” |
| Chapter heading | A benefit framed as an everyday feeling, often using clipped parallel phrases or a question and answer. | 2–6 words | “Hills? What hills?”<br>“Beautiful. Simple. Connected.”<br>“Portable. Power full.” |
| Supporting line | Begin with a useful mechanism, then describe its human consequence. | 1–3 sentences | “If we detect your bike is on the move without you, we'll notify you right away.”<br>“Meet the e-bike that thinks for itself.” |
| Action | Specific verb, small commitment, occasionally possessive. | 2–5 words | “Configure yours”<br>“Design in detail”<br>“Check now” |
| Service reassurance | Human, concrete and direct about what happens next. | 3–8 word heading | “We come to you”<br>“Relax. We've got you.” |

**Words and phrasing to use:** natural; flow; effortless; connected; built to; wherever; your; try it; nearby; simple

**Avoid:** revolutionary platform; synergize; best-in-class solution; disruptive ecosystem; unlock your potential; hurry!!!

**Rules:**

- Put the felt benefit in the headline and the mechanism in support copy.
- Use a small number of concrete technical nouns rather than stacking jargon.
- Make trial and service actions welcoming and explicit.
- Use occasional compact wordplay, not a pun in every heading.
- Prefer direct questions to elaborate sales introductions.

## Do's and Don'ts

### Do

- Use weight 400 for display and chapter headings; keep 500 for action and utility emphasis.
- Maintain 60px desktop side gutters even as full-bleed imagery crosses the canvas.
- Keep primary actions 56px high with fully rounded ends.
- Give material close-ups 8px corners and 10px mosaic gutters.
- Separate major chapters with the actual 110.4px rhythm rather than rounding it to a generic spacing token.
- Keep support paragraphs near 620px wide under centered promises.
- Pair a complete product profile with close-ups so the object remains understandable.
- Finish utility content with fine 1px rules rather than heavy boxed sections.

### Don't

- Do not make every heading bold; the oversized regular type is the hierarchy.
- Do not turn pale atmospheric blue into a saturated marketing action color.
- Do not replace 8px media corners with oversized 24px card rounding.
- Do not add floating drop shadows to every content card; separation is usually tonal.
- Do not spread the 12px uppercase mono labels across ordinary product sections.
- Do not convert every narrative chapter into an equal three-card grid.
- Do not put every supporting paragraph in pure white or charcoal; muted grey creates the intended two-tone hierarchy.
- Do not shrink physical objects to fit neatly inside all media panels; intentional overscale and edge clipping carry the material drama.

## Motion and responsive

### Motion

**Observed:**

- Opacity and transform reveal classes specify 0.6s and 0.9s durations; some headings use a 400ms delay.
- Action classes specify 300ms color transitions; product chapter links specify 200ms color transitions.
- The global header declares a 300ms box-shadow and transform transition.
- The detail capsule's plus carrier has hover rotation of 180deg and scale 1.2 in its classes; a matched timing curve for that behavior is not established.

**Transfer:**

- Use restrained text reveals while keeping the photographic scene legible before and after the reveal.
- Let chapter navigation take over from global navigation during a long product story.
- Keep carousel movement subordinate to the imagery; stationary compositions should still communicate the benefit.

**Unknown:**

- Playback, reveal triggers and exact relationship between scrolling and media progress are not established.
- Focus-visible and active button treatments are not established; no new interaction timing curve is prescribed.

### Responsive

**Observed:**

- Desktop layouts use multi-column mosaics and wide full-bleed scenes.
- Responsive classes indicate column stacking for service image/text sections and hidden desktop navigation at narrower widths.
- Hero campaign type declares stepped sizes including 44px, 52px, 66px and 100px; numeric breakpoint widths are not established.

**Transfer:**

- On narrow layouts, preserve the order of promise, large object and action; keep the object substantial rather than shrinking the desktop scene wholesale.
- Stack asymmetric image/text sections while retaining one strongly framed detail at a time.
- Allow practical comparison tables their own horizontal reading area rather than compressing all columns into unreadable text.

**Unknown:**

- Only the desktop composition is established; exact mobile gutters, menu design and breakpoint thresholds remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
