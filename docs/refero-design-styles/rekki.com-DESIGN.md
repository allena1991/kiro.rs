# REKKI — night shift optimism

## Overview

A black, photographic marketing style that makes automation feel grounded in real working lives. White, tightly packed grotesk headlines and electric blue actions sit against shadowy workplaces, with small equipment-like mono labels adding an industrial note. It suits practical business software and service platforms: spacious between chapters, dense and useful inside demonstrations and proof cards.

### Essentials

- Headlines feel compressed but not heavy: medium grotesk at 86px/1 with -0.064em tracking for the main promise; section leads use 72px/1 and -3px tracking.
- The opening is a night-lit workplace stage, not a floating app mockup: dark photography above and behind a centered two-line promise, one blue pill, and a faded monochrome logo ribbon; the next product frame starts within the first 900px.
- Actions change scale dramatically: 44px-high, 6px-radius navigation buttons; 96px-high, 59px-radius hero pills; a monumental 776×166px blue pill with 72px uppercase type and a white arrow.
- Black owns the page: saturated #0063e1 is concentrated in actions, with a broad blue plan panel reserved for commercial comparisons. Product explanations may introduce isolated #f6f6f6 panels, never a light page theme.
- Real work supplies the visual texture: environmental people photography is darkened into black, while testimonial photos carry inset charcoal glass with blur(30px), 24px side padding and 24px/32px quotations.
- Proof is architectural: 8px gutters lock together near-black feature cards, photo-backed proof panels and three-column 56px statistics. Include both human proof and a monumental conversion device, using original workplace imagery or a carefully lit still life when people photography is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0063e1` | `--color-action` | action, accent, surface | Primary actions; broad filled panels only for highlighted commercial offers. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-primary-text` | text, surface | Headlines, icons, action labels and inverse buttons. |
| Half-light text | `#858585` | `--color-muted-text` | text, link | Supporting text on black; white at 52% opacity produces this visible neutral. |
| Panel edge | `#313131` | `--color-panel-edge` | border | White at 12% over raised charcoal tiles and panels. |
| Device charcoal | `#2b2c2e` | `--color-device-rim` | surface | Outer rim around the main interface demonstration. |
| Charcoal glass | `#272828` | `--color-glass` | surface | Visible baseline of rgba(87,89,89,0.45) over black; testimonial glass varies with the photograph behind it. |
| Raised charcoal | `#151515` | `--color-dark-panel` | surface | Logo tiles and pricing panels. |
| Proof edge | `#11151c` | `--color-faint-edge` | border | White at 5% over blue-black feature cards. |
| Warm black ink | `#110f0e` | `--color-inverse-ink` | text | Text on light product panels and secondary buttons. |
| Blue-black | `#040910` | `--color-proof-card` | surface | Feature cards inside photographic proof stages. |
| Black canvas | `#000000` | `--color-canvas` | background, surface | Dominant page field and media fades. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product-focused landing pages | Soft white panel | `#f6f6f6` | `--color-light-panel` | surface | Isolated product explanation cards. |
| light product panels | Muted inverse ink | `#888786` | `--color-inverse-muted` | text | Visible rgba(17,15,14,0.48) over #f6f6f6. |
| categorized question lists | General green | `#18936f` | `--color-category-green` | accent | Small category dots, not broad fills. |
| categorized question lists | Payments orange | `#f35b05` | `--color-category-orange` | accent | Small category dots. |
| categorized question lists | Other purple | `#6146af` | `--color-category-purple` | accent | Small category dots. |

## Typography

- **Diatype REKKI** — All sentence-case marketing text and navigation; Regular and Medium cuts. Compact contemporary grotesk with open forms; medium headings gain force through tight spacing rather than bold weight. If unavailable, use **Inter**. Use 400 for prose and 500 for headings; preserve tight display tracking. Font stack: "Diatype REKKI", "Inter", Arial, sans-serif.
- **Diatype REKKI Bolder Rounded** — Uppercase actions and emphatic price numerals. Heavy rounded grotesk that gives buttons a blunt, friendly confidence. If unavailable, use **Nunito Sans**. Use 800; keep action labels compact rather than bubbly. Font stack: "Diatype REKKI Bolder Rounded", "Nunito Sans", Arial, sans-serif.
- **OCD-GARRI-V01** — Footer, organization captions and equipment-like section labels. Narrow technical lettering in uppercase with conspicuous spacing. If unavailable, use **Barlow Condensed**. Use 400 with 0.5px tracking to preserve the narrow label silhouette. Font stack: "OCD-GARRI-V01", "Barlow Condensed", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Diatype REKKI | 500 | 86px | 1 | -0.064em | Centered opening promise and monumental closing promise. |
| heading-lg | Diatype REKKI | 500 | 72px | 1 | -0.0417em, features "case" | Primary section headings, testimonial introductions and large commercial headings. |
| action-monumental | Diatype REKKI Bolder Rounded | 800 | 72px | 1 | normal, uppercase | Oversized conversion pill. |
| heading | Diatype REKKI | 500 | 56px | 1 | -0.0402em, features "case" | Proof panel leads, product card titles, statistics and compact plan titles. |
| quote | Diatype REKKI | 400 | 24px | 32px | -0.027em, features "case" | Testimonial quotations and product demonstration descriptions. |
| hero-support | Diatype REKKI | 400 | 20px | 1.4 | -0.015em | Centered supporting line on black. |
| action | Diatype REKKI Bolder Rounded | 800 | 20px | 1 | 0.04em, uppercase | Hero pill labels. |
| body | Diatype REKKI | 400 | 18px | 24px | -0.015em, features "case" | Descriptions, benefit rows and testimonial attribution. |
| card-label | Diatype REKKI | 500 | 18px | 24px | -0.015em, features "case" | Feature labels and product selector names. |
| navigation | Diatype REKKI | 500 | 16px | 1.25 | -0.015em | Desktop navigation links. |
| action-small | Diatype REKKI Bolder Rounded | 800 | 16px | 1 | 0.04em, uppercase | Secondary pills and plan actions. |
| technical-label | OCD-GARRI-V01 | 400 | 15px | 16px | 0.033em, uppercase | Compact footer and categorized question labels. |
| organization-caption | OCD-GARRI-V01 | 400 | 13px | 16px | 0.0385em, uppercase | Organization under a testimonial attribution. |
| action-compact | Diatype REKKI Bolder Rounded | 800 | 12px | 14px | 0.02em, uppercase | Fixed navigation action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| commercial comparisons | price | Diatype REKKI Bolder Rounded | 800 | 68px | 0.9 | normal | Bottom-anchored pricing numerals. |
| company and editorial pages | editorial-intro | Diatype REKKI | 500 | 44px | 1 | -0.0398em | Two substantial introductory paragraphs beside an environmental portrait. |

**Notes:**

- Sentence-case headlines and prose share a compact grotesk; only action labels and technical captions are uppercase.
- Tracking is tightest on the 86px display, then relaxes through section headings to -0.015em body text. Keep the complete recipes rather than applying one tracking value everywhere.
- Use white for hierarchy and half-light gray for explanation. Statistics use the heading recipe, not the heavy price face.

## Layout

**Density:** Airy between chapters, tightly assembled within proof grids and interface frames.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Repeated card gutters and title-to-support gaps. |
| 12px | Display-to-support separation. |
| 16px | Testimonial overlay inset and inner device bezel. |
| 24px | Overlay side padding, header side padding and utility grid spacing. |
| 32px | Heading-to-card separation and feature card padding. |
| 40px | Large panel side padding. |
| 56px | Proof stage to statistic row spacing. |
| 88px | Editorial chapter top and bottom padding. |
| 120px | Major marketing chapter gaps. |

### Containers and grids

- **marketing-container**: max width 1240px · side padding 24px. Centered desktop content, leaving 100px outside each side at 1440px; side padding is the minimum outer protection.
- **utility-container**: max width 1232px · side padding 24px. Categorized question rows and supporting layouts.
- **three-column-proof**: 3 columns · gap 8px. 408px-wide testimonial and statistic columns within the marketing container.
- **feature-grid**: 2 columns · gap 8px. Two-by-two feature cards occupy the right two thirds of a photo-backed proof stage.
- **editorial-split** (only for company and editorial pages): 3 columns · gap 8px. One third for section lead, two thirds for a four-column tile or portrait grid, with 40px inner left padding on the wider side.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature cards and glass | 8px |
|  | photo testimonials | 16px |
|  | large stages | 24px |
|  | hero pills | 59px |
|  | navigation action | 6px |
|  | monumental pill | 90px |
|  | device top corners | 38px |
| photo-backed suite offers | pricing overlay | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| commercial panels | benefit separator | `0px -1px 0px 0px rgba(255,255,255,0.12)` | Thin top rule on dark pricing benefit rows. |
| commercial comparisons | highlight benefit separator | `0px -1px 0px 0px rgba(255,255,255,0.2)` | Thin top rule on blue pricing benefit rows. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page field.

**CSS:** `background: #000000; color: #ffffff`

#### Proof card · level 1

**Use:** Feature explanations over photographic stages.

**CSS:** `background: #040910; border: 1px solid rgba(255,255,255,0.05); border-radius: 8px; padding: 32px`

**Observed:** Almost black with a cool cast; fine outline replaces raised shadow.

**Transfer:** Keep the image visible around tightly packed cards.

#### Testimonial glass · level 2

**Use:** Readable quotation layer over customer photography.

**CSS:** `background: rgba(87,89,89,0.45); backdrop-filter: blur(30px); border-radius: 8px; padding: 0px 24px`

**Observed:** The photograph subtly colors the charcoal; the glass remains dark enough for white prose.

**Transfer:** Use real translucency, not a uniform gray rectangle.

#### Device frame · level 1

**Use:** Wide main product demonstration.

**CSS:** `background: #2b2c2e; border-radius: 38px 38px 0px 0px; padding: 8px 8px 0px`

**Observed:** A black inner frame with 30px top corners and 16px inset surrounds a bright interface.

**Transfer:** Use the frame as a transition from atmospheric photography into clear product detail.

#### Raised panel · level 1

**Use:** Dark logo tiles and commercial cards.

**CSS:** `background: #151515; border: 1px solid rgba(255,255,255,0.12); border-radius: 8px`

#### Light product panel · level 1

**Only for:** product-focused landing pages

**Use:** Product explanation with integrated interface imagery.

**CSS:** `background: #f6f6f6; color: #110f0e; border-radius: 16px; overflow: hidden`

**Observed:** A discrete island within the black page; text above imagery, not an all-page light mode.

**Transfer:** Reserve light surfaces for demonstrating functional clarity.

#### Highlighted offer · level 1

**Only for:** commercial comparisons

**Use:** The dominant offer in an asymmetric comparison.

**CSS:** `background: #0063e1; color: #ffffff; border-radius: 24px; padding: 24px 40px 36px`

**Observed:** Spans two thirds of the container beside a one-third charcoal offer.

**Transfer:** Concentrate the broad color in one decisive commercial block.

## Components

### Navigation

**Use:** Fixed desktop orientation bar.

**CSS:** `position: fixed; top: 0px; height: 64px; width: 100%; z-index: 3; padding: 20px 24px; display: flex; align-items: center; gap: 20px`

**Text style:** `navigation` — Diatype REKKI 500 · 16px/1.25 · tracking -0.015em

**Observed:** White symbol and wordmark at left, muted audience links centered with 24px gaps, Compact action at right. A black fade protects it over media.

**Transfer:** Keep the bar thin and persistent rather than turning it into a large masthead.

### Primary button

**Use:** Main hero action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #0063e1; color: #ffffff; border-radius: 59px; padding: 39px 56px 37px; min-height: 96px`

**Text style:** `action` — Diatype REKKI Bolder Rounded 800 · 20px/1 · tracking 0.04em · uppercase

**Observed:** A solitary centered action beneath the support line; no extra border or drop shadow.

### Secondary button

**Use:** Detailed product or offer action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #110f0e; border-radius: 59px; padding: 32px 44px; min-height: 80px`

**Text style:** `action-small` — Diatype REKKI Bolder Rounded 800 · 16px/1 · tracking 0.04em · uppercase

**Observed:** White pill beside the demonstration description or inside the blue highlighted offer.

### Compact action

**Use:** Right edge of the navigation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 10px; background: #0063e1; color: #ffffff; border-radius: 6px; padding: 12px 14px 12px 13px; height: 44px`

**Text style:** `action-compact` — Diatype REKKI Bolder Rounded 800 · 12px/14px · tracking 0.02em · uppercase

**Observed:** Small white ticket-shaped icon with a dark right arrow precedes the label; the commercial variant reads Log in.

### Monumental action

**Use:** Signature conversion device.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 38px; background: #0063e1; color: #ffffff; border-radius: 90px; padding: 39px 58px 39px 88px; height: 166px`

**Text style:** `action-monumental` — Diatype REKKI Bolder Rounded 800 · 72px/1 · uppercase

**Observed:** A broad 776px pill pairs a very heavy uppercase label with a large white right arrow. It visually outweighs ordinary buttons.

**Transfer:** Use a short conversion verb and scale arrow and label as one composition.

### Feature card

**Use:** Practical assurance or capability inside a proof stage.

**CSS:** `background: #040910; border: 1px solid rgba(255,255,255,0.05); border-radius: 8px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `card-label` — Diatype REKKI 500 · 18px/24px · tracking -0.015em

**Observed:** Bold white pictogram at top; label and muted Body text group at bottom, separated by 4px. Four 392×272px cards fit a two-by-two grid.

### Testimonial card

**Use:** Human social proof.

**CSS:** `background: #000000; border-radius: 16px; overflow: hidden; display: flex; flex-direction: column; justify-content: flex-end; height: 460px`

**Text style:** `quote` — Diatype REKKI 400 · 24px/32px · tracking -0.027em

**Observed:** 408px-wide photo card with an approximately 320px-high environmental image at top. Testimonial glass overlaps the lower image, inset 16px from the sides and bottom; identity with round logo precedes the quote and a fine divider. Attribution uses Body and Organization caption.

**Transfer:** Select a quote specific enough to earn several lines, not generic praise.

### Statistic

**Use:** Quantified proof beneath the media stage.

**CSS:** `display: flex; flex-direction: column; gap: 6px; color: #ffffff`

**Text style:** `heading` — Diatype REKKI 500 · 56px/1 · tracking -0.0402em

**Observed:** Three equal columns pair a large medium-weight numeral with a muted Body caption; subtle vertical dividers mark the columns.

**Transfer:** Use independently verifiable numbers and short explanations.

### Footer strip

**Use:** Compact page ending.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 20px 24px; min-height: 56px; background: #000000; color: rgba(255,255,255,0.52)`

**Text style:** `technical-label` — OCD-GARRI-V01 400 · 15px/16px · tracking 0.033em · uppercase

**Observed:** Copyright sits at left; grouped inline navigation, slash separators, social links, utility links and a small cookie control line up at right. It is a strip, not a multi-column sitemap.

**States:** Declared: hover links become #ffffff with no underline; focus-visible not specified.

### Logo tile

**Only for:** company and ecosystem sections

**Use:** Dense customer or integration proof.

**CSS:** `background: #151515; border: 1px solid rgba(255,255,255,0.12); border-radius: 8px; display: flex; align-items: center; justify-content: center; height: 127px`

**Observed:** 190px-wide tiles form a four-column grid. White partner marks float centrally with generous internal air.

**Transfer:** Normalize marks by visual area rather than forcing equal widths.

### Pricing panel

**Only for:** commercial offers

**Use:** Concrete offer with benefit list and conversion action.

**CSS:** `background: #151515; color: #ffffff; border-radius: 12px; padding: 24px 24px 36px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `heading` — Diatype REKKI 500 · 56px/1 · tracking -0.0402em

**Observed:** A 471×612px overlay sits on the right of a photo stage; a large title and support lead into divided benefit rows with white circular checks, then a full-width blue action. Comparison variants use 24px corners, 40px side padding and a bottom-anchored Price.

### Question row

**Only for:** categorized question lists

**Use:** Compact objection handling after an offer.

**CSS:** `display: flex; align-items: flex-start; gap: 24px; padding: 16px 0px 15px; min-height: 48px`

**Text style:** `technical-label` — OCD-GARRI-V01 400 · 15px/16px · tracking 0.033em · uppercase

**Observed:** Full-width hairline-separated rows contain a 160px category column with a 12px colored dot and a question to its right. Closed questions remain a single line; answer prose uses Body.

**Transfer:** Keep categories narrow and put explanatory detail in expanded content rather than always-visible cards.

## Imagery and graphics

### Night workplace stage

**Use:** Primary atmospheric imagery, including the opening.

**Observed:** A desk, laptop, pencil cup and task lamp emerge from cool green-black darkness. The image spans most of the width but dissolves into black at the sides and below. Small rounded activity labels float over the desk above the main headline; their contrast diminishes upward.

**Transfer:** Photograph the new product's real place of use with one practical light source. If people or locations are unavailable, use a real tool still life with a dim screen and lamp; retain the photographic night-stage and activity-label device.

**Build:** Use a full-width object-fit:cover photograph, a black top fade about 180px deep, a strong bottom fade into the canvas and horizontal black edge masks. Center a narrow vertical stack of compact charcoal status chips above the title, with 8px corners and restrained white text; progressively lower opacity upward. Match the soft fade rather than adding colored glow.

### Environmental proof photography

**Use:** Assurance stages, customer cards and photo-backed offers.

**Observed:** Candid working people in kitchens, offices and warehouses, plus tactile close-ups of bread and produce. Cool shadows mute the palette; proof panels darken the photo strongly while testimonial tops retain warmer color. Wide stages use 24px corners and pair a person on the left with dark explanatory layers on the right.

**Transfer:** Use documentary images of real users doing ordinary work, with visible surroundings and believable light. Let human activity—not futuristic machinery—carry the product story.

### Interface demonstration

**Use:** The main functional explanation and scoped light product cards.

**Observed:** A broad, bright operational interface is staged in the Device frame. A row of bold monochrome product symbols and 18px names identifies the selected capability; explanation and a white pill sit beneath. Light product cards integrate their interface scene below the heading.

**Transfer:** Show an actual workflow at useful scale, with one selected task and one concise explanation. Keep screenshot internals faithful to the new product rather than borrowing the surrounding site's marketing type.

### Monochrome proof ribbon

**Use:** Bridge between the opening and product content.

**Observed:** A horizontal row of varied customer wordmarks in dim white-gray stretches almost edge to edge, with black fading over the ends. It is subdued compared with the hero action.

**Transfer:** Use authorized customer or compatible ecosystem marks. If those are unavailable, supply a row of original typographic workflow labels with the same restrained contrast and edge fade.

**Build:** Arrange single-color marks in a horizontal flex row on black, give each similar visual area and around 40px separation, then mask left and right edges with black-to-transparent gradients. Do not put them in tiles in this ribbon.

### Photo-backed benchmark chart

**Only for:** quantified performance stories

**Use:** Evidence-heavy product proof.

**Observed:** A 1240×500px rounded blue-black stage places a stacked white heading and small explanation on the left, and a fine-grid line chart across the right. One green trajectory is strong while several comparison lines are dim; narrow uppercase annotations feel technical. Three big statistics sit below.

**Transfer:** Use real data in an original chart. Keep the dominant trend legible without converting every line into a bright rainbow.

**Build:** Layer a dim workplace photograph on the left under a black horizontal fade; place a near-black SVG plot over the right three fifths, with low-opacity white grid lines, narrow labels, subdued series and one thicker saturated comparison line. Finish with 24px outer corners and a faint edge.

### Team portraits

**Only for:** company and editorial pages

**Use:** People-led organization introduction.

**Observed:** A tall candid workplace image opens the story. Later, square 190px portraits form four columns with 16px separation before the name and a muted role beneath; backgrounds mix authentic workplaces and pale studio backings.

**Transfer:** Favor approachable real people over uniform stylized avatars; keep square framing consistent even when backgrounds differ.

### Icons

**Observed:** Chunky filled monochrome pictograms, often 48–64px, stand alone above labels. Feature symbols include targets, bars, currency and trade imagery. Pricing uses white circular check marks; navigation uses a tiny arrow inside a white ticket shape. These are not thin outlined icon sets.

**Transfer:** Choose a coherent family of filled symbols with simple silhouettes. Keep pictograms white on dark panels and dark on light panels; arrows must feel as robust as the uppercase action type.

## Section recipes

How recurring sections are built.

### First screen: Night-stage opening

**Observed:** The first screen layers Canvas, a cool dim desk photograph with activity chips, black edge and bottom fades, Navigation, then centered display type. The two-line promise spans about two thirds of the width and begins around 320px down; it uses Display, not bold action type. Hero support follows at 12px, then one Primary button after 32px. The subdued Monochrome proof ribbon sits below the action. Within 900px the full promise, support, action and ribbon are visible, plus the top of the Device frame beginning at 812px; its main explanation falls below the fold.

**Transfer:** Keep the night-lit stage, activity chips, centered promise and single blue action for an ordinary landing page. An original desk or tool photograph is sufficient when bespoke media is unavailable. Audience pages can use a full-bleed environmental workplace scene with a higher headline; editorial pages instead open with a one-third portrait beside two 44px introductory paragraphs.

**Avoid:** Do not replace this with a bright dashboard-first split hero, neon abstract gradient, or a white background with a small isolated headline.

**Text style:** `display` — Diatype REKKI 500 · 86px/1 · tracking -0.064em

### Product demonstration chapter

**Observed:** Device frame occupies the 1240px container. Product symbols and Card label names form a horizontal selector with one white active label and muted inactive labels. A Quote-sized explanatory sentence and Secondary button sit beneath the demonstration; a black fade binds the interface to the page.

**Transfer:** Give the user one understandable workflow to inspect; let the action sit beside the explanation rather than crowding the selector.

### Photographic assurance stage

**Observed:** A 1240×600px photo-backed rounded stage has a one-third left zone with a 56px multiline heading over a person at work. The right two thirds contain four Feature cards with 8px gutters; each has an icon, short label and muted description. Three Statistic columns follow after 56px.

**Transfer:** Combine human context, concrete assurances and measurable outcomes without requiring the same topics or card count.

**Text style:** `heading` — Diatype REKKI 500 · 56px/1 · tracking -0.0402em

### Customer proof gallery

**Observed:** A centered Heading lg introduction is followed after 32px by three Testimonial cards with 8px gutters. Photo and glass carry more visual area than the section title; identity precedes the quoted result.

**Transfer:** Use the same documentary treatment for customers, practitioners or domain experts. Let evidence determine quote length.

**Text style:** `heading-lg` — Diatype REKKI 500 · 72px/1 · tracking -0.0417em

### Monumental closing call

**Observed:** A centered two-line Display promise on black is followed by a muted Hero support line and the Monumental action. The blue pill becomes the dominant graphic; substantial black breathing room separates it from the Footer strip.

**Transfer:** Include this large-scale conversion device in a new marketing composition, using a short action and a strong final benefit rather than a generic contact box.

**Text style:** `display` — Diatype REKKI 500 · 86px/1 · tracking -0.064em

### Light capability pair

**Only for:** product-focused landing pages

**Observed:** Two 616px Light product panels sit side by side with an 8px gap; 56px titles and Body explanations occupy a 32px by 40px text inset above functional imagery. Three icon-led assurances follow on black.

**Transfer:** Use the light islands to distinguish related capabilities, while retaining the surrounding dark system.

**Text style:** `heading` — Diatype REKKI 500 · 56px/1 · tracking -0.0402em

### Editorial heading and evidence split

**Only for:** company and editorial pages

**Observed:** The left third holds a 72px heading and optional Body support at 8px separation. The right two thirds hold a two-column value grid, a four-column portrait grid, a four-column Logo tile wall or press rows. Chapters use 88px vertical padding and fine separators. The final chapter pairs a 56px integration promise with a three-row logo wall, then ends directly in Footer strip.

**Transfer:** Make organizational credibility feel like a structured catalog. Keep section headings aligned in the same left column across changing evidence types.

**Text style:** `heading-lg` — Diatype REKKI 500 · 72px/1 · tracking -0.0417em

### Photo-backed suite offer

**Only for:** single-suite product offers

**Observed:** A 1240×660px environmental photograph with 24px corners carries a large left-aligned section title. Pricing panel overlays the right side with 24px inset; checked benefit rows precede a blue action. The Footer strip follows after black space, without another large call.

**Transfer:** Use this ending when one concrete offer can resolve the page's promise.

**Text style:** `heading-lg` — Diatype REKKI 500 · 72px/1 · tracking -0.0417em

### Asymmetric commercial comparison

**Only for:** commercial comparisons

**Observed:** A blue Highlighted offer spans 824px beside a 408px charcoal alternative, both 756px high and 24px-rounded. Large offer headings lead into checkmarked rows; prices anchor to the bottom and the preferred plan has a white Secondary button. Categorized Question rows follow a 72px heading; Footer strip closes the page.

**Transfer:** Make one offer visually decisive and use the quieter plan as contrast, then resolve adoption questions without adding another promotional band.

**Text style:** `heading-lg` — Diatype REKKI 500 · 72px/1 · tracking -0.0417em

## Page flow

**Storyline:** Practical promise → visible workflow → operational proof → human endorsement → decisive next step, with company and commercial variants adapting the ending.

### Broad product-platform introduction

1. **Promise** — Night workplace stage, centered promise, single action and subdued logo ribbon.
2. **Product demonstration** — Wide framed interface with capability selector and description.
3. **Operational proof** — Photographic assurance stage, feature cards and a three-number proof row.
4. **Social proof** — Large centered introduction over photographic testimonial cards.
5. **Closing call** — Monumental benefit line and oversized arrow pill, then compact utility footer.

**Transfer:** Introduce the whole platform through one tangible workflow and let human proof bridge into the final conversion.

### Organizational trust and ecosystem credibility

1. **Origin** — Workplace portrait beside two large paragraphs.
2. **Principles** — Left heading and right icon-led explanations.
3. **People proof** — Square portraits with names and roles.
4. **Adoption proof** — Monochrome logo wall.
5. **External validation** — Press names and linked headlines in aligned rows.
6. **Compatibility reassurance** — Integration promise and logo tile wall end directly at the utility footer.

**Transfer:** Substitute the new organization's own origin, people and ecosystem; use structured editorial splits rather than a conversion-heavy close.

### Audience-specific product and offer explanation

1. **Promise** — Full-bleed workplace image with a centered benefit and blue action.
2. **Capabilities** — Two light product cards followed by three dark icon-led assurances.
3. **Quantified proof** — Photo-backed trend chart and large statistics.
4. **Social proof** — Testimonial gallery introduced by a short quoted heading.
5. **Offer** — Photo-backed suite and pricing overlay, then utility footer.

**Transfer:** Center the audience's daily workload, show the relevant tools, then resolve with one tangible offer.

### Transactional product adoption and commercial clarity

1. **Promise** — Colorful real-world produce photograph dimmed behind a terse centered headline and one join action.
2. **Product demonstration** — White rounded explanation panel with benefit rows and a large interface scene, followed by statistics on black.
3. **Social proof** — Three environmental testimonial cards.
4. **Commercial comparison** — Wide blue offer and narrower charcoal alternative.
5. **Objection handling** — Categorized compact question rows finish before the utility footer.

**Transfer:** Use a concise outcome promise, immediately clarify the mechanism, and make the adoption choice legible before answering common questions.

## Writing

Plainspoken, commercially confident and sympathetic to daily work. Technical capability is translated into time, accuracy, growth and personal service rather than speculative futurism.

**Do not copy:** Do not reuse REKKI names, wordmarks, proprietary product names, customer logos, employee identities, quotations, prices, statistics, guarantees or other claims. Replace them with authorized assets and substantiated facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we for accountable commitments. Product names appear as compact nouns, while the surrounding copy stays conversational.
- **Rhythm:** Short benefit headlines, occasional clipped lists, and single-sentence support lines. Longer company prose remains direct and compact; quotations retain a natural spoken rhythm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the practical outcome or contrast automation with a human benefit. | 4–9 words or one compact two-line sentence | “Office robots built for wholesale distributors”<br>“Cut the manual work, keep the personal service”<br>“Orders. Customers. Payments. Sorted.” |
| Supporting line | State tasks and benefits with active verbs. | One sentence, about 10–18 words | “Automate orders, grow sales, and serve customers with our suite of AI robots” |
| Feature label | A compact operational principle, not a grand slogan. | 2–4 words | “Accuracy first”<br>“Practical innovation” |
| Primary action | Verb plus a simple next step. | 2–4 words | “Get a Demo”<br>“join the marketplace” |
| Closing promise | Pair an upside with the cost or friction it avoids. | 6–10 words | “Scale your business without growing costs” |
| Proof caption | Explain what a number means in everyday operational language. | One short phrase | “reduction in manual work” |

**Words and phrasing to use:** your team; manual work; real conversations; accuracy; results; built for; without changing how you work; risk-free

**Avoid:** revolutionary ecosystem; seamless synergy; unlock limitless potential; AI-powered everything; magical transformation

**Rules:**

- Lead with the job the reader needs done, then name the mechanism.
- Pair automation claims with human control or service benefits.
- Give numbers a plain-language denominator or context.
- Keep action labels short enough to remain a single bold line.
- Use guarantees only when the actual offer supports them.

## Do's and Don'ts

### Do

- Set the main promise at 86px/1 with -0.064em tracking and medium weight.
- Keep ordinary content inside 1240px and repeated proof columns separated by 8px.
- Pair white headings with 52%-white support on black.
- Make testimonial quotes 24px/32px with -0.7px tracking inside blurred charcoal glass.
- Use 32px padding in blue-black feature cards and keep their labels close to descriptions.
- Keep chapter gaps around 120px while internal heading-to-card gaps stay 32px.
- Make the closing action a graphic-scale blue pill, not just another standard button.
- Preserve the 56px-tall utility footer as a compact horizontal strip.

### Don't

- Do not set sentence-case display headings in the heavy rounded action face.
- Do not give every button the 6px navigation radius; hero actions use 59px.
- Do not introduce broad orange, green or purple bands; those hues belong to small category dots.
- Do not turn fine card outlines into thick gray borders or cast heavy black shadows.
- Do not brighten every partner mark to headline white; the opening proof ribbon stays subdued.
- Do not make all proof cards light; the core assurance cards are blue-black.
- Do not replace filled pictograms with thin, multicolored outline illustrations.
- Do not expand the footer into a tall sitemap with large headings.

## Motion and responsive

### Motion

**Observed:**

- Footer links declare a hover color change to white and no underline.
- No action or surface transition timings or keyframe animations are established.

**Transfer:**

- Keep any activity-chip progression subordinate to the static hero promise and blue action.

**Unknown:**

- Activity-chip timing, media playback behavior, selector transitions and easing durations are unspecified.

### Responsive

**Observed:**

- Desktop composition uses 1240px and 1232px centered containers with 24px outer protection.
- Width rules include boundaries around 860px, 1200px, 1280px and 1600px.

**Transfer:**

- On narrower layouts, preserve the night-stage, single action and faded proof ribbon rather than reducing the opening to text alone.
- Stack photo stages and card groups when necessary; maintain identity-before-quote order and keep the monumental pill's label and arrow together.
- Use the established 24px side protection as a starting point while reducing headline size enough to preserve deliberate line breaks.

**Unknown:**

- Exact narrow-screen typography, navigation replacement, stacking order and breakpoint-specific dimensions are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
