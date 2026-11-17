# Alveos — blue-sky human science

## Overview

An airy, image-led style that makes technical products feel physically present and human. Pale blue and near-white chapters alternate with deep navy and sunlit, sky-backed photography; regular grotesk typography stays modest beside the imagery. Rounded glass overlays, sculptural product views and a monumental wordmark ending suit consumer technology and science-led services without the density of a dashboard.

### Essentials

- The human scene is bigger than the promise: a full-bleed 945px photographic opening carries a lower-left white 42px/1.05 headline and 24px/1.2 support, with the product visibly in use.
- Headlines speak rather than shout: Hanken Grotesk at 400, 32px/1.15 for feature chapters and 42px with -0.02em tracking for the opening; 34px/1.15 at 500 marks editorial section leads.
- The conversion control is a small dark capsule inside a floating translucent capsule: 45px action height, 40px radius, 8px 26px padding; navigation uses 26% white and 20px backdrop blur.
- Color belongs to chapter-sized environments, not decorative text: #def0ff and #bbddff fill entire bands, #05102b anchors a technical chapter, and most reading remains on #f7fafc or white. Preserve this mix of pale, photographic and occasional dark fields rather than a uniformly dark site.
- Interfaces become physical fans: layered rounded panels arc across the bottom of spacious light sections, with a sharp tall center and softer receding edges. Use real product views, or purpose-made conceptual panels with meaningful labels when no interface exists.
- Glass makes proof feel embedded in the world: stacked 398px metric panels use 40px corners, 28px padding and 10px blur over a blue-sky photograph; figures remain 32px rather than becoming giant billboards.
- The ending turns identity into architecture: an almost-black footer ends in a pale wordmark artwork spanning 1376px at desktop, in a 316px-high clipped stage. Give every new page an equivalent oversized typographic sign-off made from its own name.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft sky blue | `#bbddff` | `--color-sky-blue` | background | Process and everyday-use photographic card bands. |
| Notice blue | `#192642` | `--color-notice` | surface | Inset informational panel on the dark footer. |
| Technical navy | `#05102b` | `--color-navy` | background | Deep contrasting backdrop for physical product explanations. |
| Ice blue | `#def0ff` | `--color-pale-blue` | background | Insight, feature-grid and numbered-list chapter backgrounds. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer night | `#07090e` | `--color-night` | background, action, text | Footer background and default primary action fill. |
| Deep text | `#111112` | `--color-deep-ink` | text, link | Navigation and selected product chapter text. |
| Night hairline | `#202227` | `--color-footer-rule` | border | Visible result of 10% white over the footer; use a 1px separator. |
| Charcoal | `#262628` | `--color-ink` | text | Default headings and paragraphs on pale fields. |
| Muted white on night | `#b5b5b7` | `--color-footer-muted` | text, link | Visible result of 70% white over the near-black footer; implement the alpha text recipe. |
| Notice gray | `#d4d4d4` | `--color-notice-text` | text | Readable informational text in the dark notice panel. |
| Cool action | `#dce3f2` | `--color-secondary-action` | action | Light filled research action over photography. |
| Glass edge | `#ecedef` | `--color-glass-edge` | border | 20% alpha edge on metric glass, softly catching the light. |
| Cool canvas | `#f7fafc` | `--color-canvas` | background | Default reading canvas between immersive media chapters. |
| White | `#ffffff` | `--color-white` | surface, text | Feature cards, white editorial bands and text on dark or photographic fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| people directories | Portrait gray | `#575757` | `--color-portrait-caption` | text | Names and roles beneath portraits. |
| company storytelling | Editorial gray | `#55595a` | `--color-muted` | text | Secondary editorial body text. |
| company storytelling | Warm white | `#fcf9f7` | `--color-warm-white` | text | Invitation heading and status badge lettering. |

## Typography

- **Hanken Grotesk** — All principal headings, paragraphs, navigation, actions and captions. Open, unfussy grotesk with a human softness; regular weight dominates. Font stack: "Hanken Grotesk", Arial, sans-serif.
- **Inter** (only for company storytelling) — Small uppercase hero label and status pills. Compact, practical sans with firm semibold labels. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Hanken Grotesk | 400 | 42px | 1.05 | -0.02em | White two-line photographic hero promise. |
| section-lead | Hanken Grotesk | 500 | 34px | 1.15 | normal | FAQ lead and editorial section introductions. |
| heading | Hanken Grotesk | 400 | 32px | 1.15 | normal | Primary feature chapter headings and quantitative figures. |
| lead | Hanken Grotesk | 400 | 24px | 1.2 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Hero support and feature-card titles; also names in people directories. |
| card-heading | Hanken Grotesk | 400 | 20px | 1.4 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Titles in photo-overlay process and scenario cards. |
| body | Hanken Grotesk | 400 | 18px | 1.6 | normal | Paragraphs, navigation, numbered rows and FAQ questions. |
| action | Hanken Grotesk | 600 | 18px | 1.6 | normal | Conversion and secondary action labels. |
| caption | Hanken Grotesk | 400 | 16px | 1.5 | normal | Photo-card support, evidence kicker and short metric explanations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling | editorial-subhead | Hanken Grotesk | 500 | 28px | 1.15 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Paired present-day and future-facing explanations. |
| company storytelling | status | Inter | 600 | 14px | 1.4 | normal | Compact status badges above paired explanations. |
| company storytelling | eyebrow | Inter | 600 | 12px | 1.4 | 0.125em, uppercase | Small category label above the opening promise. |

**Notes:**

- Keep the display only moderately larger than section headings; scale comes chiefly from media and empty space, not oversized headline text.
- Only the opening display tightens tracking. Body and chapter headings use normal tracking.
- Use sentence case and regular weight for most titles. Uppercase belongs to the scoped category label, not the general navigation.

## Layout

**Density:** Airy: chapter-scale media and long intervals between text and imagery, with compact internal card spacing.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight title/support stacks and footer link spacing. |
| 16px | Photo caption inset and compact content stacks. |
| 20px | Hero title-to-support gap and navigation padding. |
| 25px | Feature mosaic gutters and card content gap. |
| 28px | Metric panel padding. |
| 32px | Page side inset and notice-panel padding. |
| 40px | Feature heading-to-paragraph gap and process-card gutters. |
| 48px | Editorial content stacks and footer groups. |
| 50px | Major split-layout gaps and FAQ title-to-action spacing. |
| 80px | Technical chapter vertical padding and deliberate action separation in proof chapters. |
| 120px | Editorial section padding and opening bottom breathing room. |
| 150px | FAQ and standalone video-section vertical padding. |
| 160px | Light interface-showcase top padding. |

### Containers and grids

- **wide-stage**: max width 1440px · side padding 32px. Full-width chapter stage; nested insets place working content about 64px from desktop edges.
- **content**: max width 1200px · gap 50px · side padding 0px. Centered FAQ and standalone 16:9 video content.
- **reading**: max width 680px · side padding 32px. Compact centered origin-story text block.
- **process-grid**: 4 columns · gap 40px. Four equal portrait-format process cards; scenario variant uses a 30px gutter.
- **editorial** (only for company storytelling): max width 1080px · 2 columns · gap 64px · side padding 32px. Paired narrative columns beneath a wide product view.
- **people-grid** (only for people directories): max width 1080px · 3 columns · gap 24px. Three-column portrait card directory.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | navigation | 80px |
|  | actions-and-feature-cards | 40px |
|  | photo-cards | 24px |
|  | faq | 32px |
| people directories | people-cards | 20px |
| recruiting invitations | invitation-action | 10px |
| company storytelling | status-pill | 100px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| people directories | portrait-card | `rgba(0, 0, 0, 0.1) 0px 1px 12px 0px` | A light lift against a white section. |

### Surfaces

#### Cool canvas · level 0

**Use:** Default reading field.

**CSS:** `background: #f7fafc`

#### Blue chapter · level 0

**Use:** Full-width product capability bands.

**CSS:** `background: #def0ff`

**Observed:** Process and scenario bands use the slightly stronger #bbddff variant.

**Transfer:** Let section changes carry the accent instead of adding colored ornaments.

#### Technical chapter · level 0

**Use:** Contrasting physical-product explanation.

**CSS:** `background: #05102b; color: #ffffff`

#### Photo caption glass · level 1

**Use:** Readable text at the bottom of photographic cards.

**CSS:** `background: rgba(0, 0, 0, 0.2); backdrop-filter: blur(10px); padding: 16px; color: #ffffff`

**Observed:** The photograph remains visible through the caption zone; the outer photo card clips the overlay.

#### Footer field · level 0

**Use:** Deep final stage for useful information and oversized identity.

**CSS:** `background: #07090e; color: #ffffff`

#### Notice inset · level 1

**Use:** Important bounded information before footer navigation.

**CSS:** `background: #192642; border-radius: 40px; padding: 32px; color: #d4d4d4`

**Transfer:** Use for genuine restrictions or operational information, not generic promotional copy.

#### White editorial field · level 0

**Only for:** company storytelling

**Use:** Origin narrative, paired explanations and portrait directory.

**CSS:** `background: #ffffff`

## Components

### Floating navigation

**Use:** Persistent top-level orientation and conversion.

**CSS:** `background: rgba(255, 255, 255, 0.26); backdrop-filter: blur(20px); border-radius: 80px; padding: 20px; height: 85px; display: flex; align-items: center`

**Text style:** `body` — Hanken Grotesk 400 · 18px/1.6

**Observed:** A compact wordmark sits left, four plain text links form the center, and Primary button sits right. The capsule floats 32px inside the top and side edges over the photograph.

**Transfer:** Keep the central labels short and the single conversion action distinct.

### Primary button

**Use:** Default conversion and contact action.

**CSS:** `background: #07090e; color: #ffffff; border-radius: 40px; padding: 8px 26px; height: 45px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Hanken Grotesk 600 · 18px/1.6

**Observed:** Text-only dark capsule; repeated in navigation and beside the FAQ introduction.

### Proof action

**Use:** Primary supporting research destination on a photographic field.

**CSS:** `background: #dce3f2; color: #07090e; border-radius: 40px; padding: 14px 30px; height: 57px`

**Text style:** `action` — Hanken Grotesk 600 · 18px/1.6

**Observed:** Paired with a transparent, fine light-outlined companion action, separated by 12px. These are larger than the navigation conversion control.

### Photo story card

**Use:** Process steps and recognizable use situations.

**CSS:** `border-radius: 24px; overflow: hidden; position: relative; height: 400px`

**Text style:** `card-heading` — Hanken Grotesk 400 · 20px/1.4

**Observed:** Portrait-format photograph or meaningful product view fills the card; Photo caption glass sits at the bottom with title, 10px gap and caption text. Process cards add a small white pictogram above the title.

**Transfer:** Use one clear moment or operation per card; retain photographic context instead of turning it into an icon tile.

### Metric glass

**Use:** A small group of credible numbers layered over a human photograph.

**CSS:** `background: radial-gradient(100% 124% at 2.7% 4.7%, rgba(207, 243, 255, 0.41) 0%, rgba(255, 255, 255, 0.04) 100%); border: 1px solid rgba(236, 237, 239, 0.2); border-radius: 40px; backdrop-filter: blur(10px); padding: 28px; width: 398px; color: #ffffff`

**Text style:** `heading` — Hanken Grotesk 400 · 32px/1.15

**Observed:** Two panels stack at the right of the photographic proof chapter with 16px between them. Each has a regular-weight figure above a caption-sized statement of conditions.

**Transfer:** Keep quantities tied to a clear denominator, result or test condition.

### Feature mosaic card

**Use:** Practical product details in an asymmetrical white-card mosaic.

**CSS:** `background: #ffffff; border-radius: 40px; padding: 30px 30px 0px; overflow: hidden`

**Text style:** `lead` — Hanken Grotesk 400 · 24px/1.2

**Observed:** One tall text-and-render card sits beside a wide image card and two smaller square cards. Titles precede body text; isolated product images occupy the remaining space.

**Transfer:** Give the most tangible benefit the tall card; let the small cards each carry one property.

### FAQ row

**Use:** Low-friction objection handling.

**CSS:** `background: #ffffff; border-radius: 32px; padding: 20px 25px; min-height: 69px; display: flex; align-items: center`

**Text style:** `body` — Hanken Grotesk 400 · 18px/1.6

**Observed:** Question is left-aligned; a 24px dark downward chevron is pinned right. Rows form a 690px-wide stack with 15px gaps.

**Transfer:** Use direct customer questions. Expanded layout and interaction states need separate definition.

### Footer navigation

**Use:** Utility links below the notice inset and above the wordmark stage.

**CSS:** `display: flex; gap: 64px; align-items: flex-start`

**Observed:** Four slim utility columns sit to the right of a wider company-description column. Links are 14px/20px regular with 70% white, column labels are bold white. A 1px 10%-white divider separates the main content from a small copyright row.

**Transfer:** Keep the utility region compact so the final identity artwork remains the dominant closing gesture.

### Portrait card

**Only for:** people directories

**Use:** Human credibility and team introductions.

**CSS:** `background: #ffffff; border-radius: 20px; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 12px 0px; width: 344px; height: 400px; overflow: hidden`

**Text style:** `lead` — Hanken Grotesk 400 · 24px/1.2

**Observed:** Inset 313px by 260px portrait above a name, smaller role and small professional-profile glyph near the lower right. Natural portraits have soft off-white backgrounds.

**Transfer:** Keep the human face primary and titles secondary; avoid colorful profile-card backgrounds.

### Invitation action

**Only for:** recruiting invitations

**Use:** Direct email contact in a photographic closing invitation.

**CSS:** `background: #ffffff; color: #07090e; border-radius: 10px; padding: 14px 28px; height: 57px`

**Text style:** `action` — Hanken Grotesk 600 · 18px/1.6

**Observed:** A single white, softly rectangular action sits under centered invitation copy; this is not the default pill shape.

## Imagery and graphics

### Sky-backed human scene

**Use:** Opening, proof and immersive narrative chapters.

**Observed:** Bright natural daylight, blue sky, honest skin texture and close framing. The opening cuts the face at the top and places neck, shoulder and product across the right two-thirds; empty sky supports white copy at lower left. Other scenes show an extended hand or a runner rather than literal laboratory stock imagery.

**Transfer:** Photograph the new product in an ordinary human context with clear sky or a similarly uncluttered cool background. For an intangible service, show a real person doing the relevant task, with a restrained meaningful screen or object. Preserve natural hard light and off-center framing.

### Product sculpture

**Use:** Physical explanation and practical feature mosaic.

**Observed:** Small metallic and dark product parts float apart on navy; a much larger portrait crop shows the product worn on pale blue fabric. White cards hold isolated close-up renders with clean edges and generous backing space.

**Transfer:** Create honest close-ups of the new object. If no object exists, use a few purposeful interface layers or a small exploded process diagram instead of inventing decorative hardware.

### Interface fan

**Use:** Signature bridge between benefit copy and detailed product views.

**Observed:** Multiple rounded app panels rise from the bottom edge in an arc. A taller central panel is upright, neighbors rotate outward, edge panels recede and soften. Colorful experience cards and dark data panels are separate variants; most section area above remains pale and empty.

**Transfer:** Stage the new product's screens in the same curved arrangement. Minimum equivalent: five meaningful rounded panels with a tall central panel, progressively rotated neighbors and restrained edge blur.

**Build:** Use an overflow-hidden full-width stage below centered copy. Position five to seven rounded panel images on a shared low baseline; raise the center, rotate left neighbors about -8deg and -16deg and right neighbors about 8deg and 16deg. Layer center above neighbors, reduce outer scale and apply a soft 2px to 6px blur only toward the outer edges. Keep pale canvas behind them; chart colors stay inside actual interface imagery.

### Monumental identity sign-off

**Use:** Required final graphic gesture beneath footer utilities.

**Observed:** A pale lowercase sans wordmark spans almost the entire width on near-black. Its 1376px by 376px artwork sits in a 316px-high clipped stage with 32px side insets, making the bottom edge feel intentionally monumental.

**Transfer:** Use the new product's own name as an equally expansive typographic sculpture; fit the name to width rather than choosing a fixed headline size.

**Build:** Render the new name as a single-line SVG text or outlined wordmark in a regular grotesk. Size the SVG to fill the available width, use pale gray-white lettering over #07090e and clip its lowest portion inside a shallow overflow-hidden stage. Keep it separate from functional footer links.

### Working-life strip

**Only for:** company storytelling

**Use:** Visual evidence between origin narrative and principles.

**Observed:** A horizontal, edge-clipped row of candid workshop, meeting, desk and prototype photographs. Images share a 340px height but vary in width, with softly rounded corners and no visible captions.

**Transfer:** Use candid process documentation with real tools and environments; retain varied framing rather than a uniform staged team shoot.

### Portrait directory

**Only for:** people directories

**Use:** Team credibility.

**Observed:** Chest-up natural portraits against pale neutral indoor backgrounds; evenly framed, softly lit, inset into Portrait card.

**Transfer:** Use consistent neutral backing and framing while allowing individual posture and expression.

### Photographic invitation

**Only for:** recruiting invitations

**Use:** Closing human invitation before the shared footer.

**Observed:** A full-height sky-blue photograph places a side-profile person in the lower-left area. Centered warm-white heading and a narrow supporting paragraph float near the top, with Invitation action below.

**Transfer:** Keep the subject below the copy's reading region and use a clear sky field; retain one direct contact destination.

### Icons

**Observed:** Small utilitarian filled SVG glyphs, not a decorative icon system: 24px dark FAQ chevrons, 32px light process pictograms and 20px professional-profile marks.

**Transfer:** Choose compact familiar symbols in a single color; use them only where they clarify a control or a process step.

## Section recipes

How recurring sections are built.

### First screen: Human-scale opening

**Observed:** A 945px full-bleed Sky-backed human scene fills the first screen. Behind everything is the blue-sky photograph, then lower-left white text, then Floating navigation at the top. The close-cropped torso and product dominate the right side; the head extends beyond the upper edge. The 42px display wraps into two short lines near the lower third, with a 20px gap to 24px support limited to 600px. Text begins about 64px inside the left edge. Within 900px the navigation, complete headline, support and worn product are visible; the image continues below the fold and the short logo strip follows beneath it. The sole first-screen action is in the navigation.

**Transfer:** Open a new marketing page with a real human-use scene, a two-part outcome promise and one support paragraph, preserving the image-to-text imbalance. If original product photography is unavailable, art-direct a simple human scene with a relevant object or screen; do not substitute an empty gradient. Company narratives retain the same photographic opening but use a small uppercase label and a mission-led promise.

**Avoid:** Do not replace the photo-dominant scene with a centered giant headline, a dashboard collage on a plain background or a second hero button cluster.

**Text style:** `display` — Hanken Grotesk 400 · 42px/1.05 · tracking -0.02em

### Heading and showcase

**Observed:** A regular 32px centered heading sits above an 18px paragraph limited to roughly 680px–800px. Title-to-copy gaps range from 10px in process introductions to 40px in interface showcases. Large media follows after 50px or more; light showcases use 160px top padding and the Interface fan at their base.

**Transfer:** Explain one benefit before revealing its visual proof. Choose either compact introduction spacing or the open interface-showcase variant rather than averaging them.

**Text style:** `heading` — Hanken Grotesk 400 · 32px/1.15

### Photo-card band

**Observed:** Blue chapter in its stronger sky-blue variant carries a centered heading and paragraph, then four Photo story cards in a row. Cards are 400px high with 30px–40px gutters; captions sit over the lower image area.

**Transfer:** Use a process or a family of recognizable situations; the number of cards can follow the new content.

### Physical mechanism split

**Observed:** Technical chapter uses 80px vertical padding, a 50px split gap, white heading and body at left and a large rounded portrait image at right. A small exploded Product sculpture appears beneath the left copy.

**Transfer:** Pair an explanation of the mechanism with a visibly real result or context; keep the small technical illustration subordinate to the large human image.

### Left-led insight chapter

**Observed:** Blue chapter uses a left-aligned heading and paragraph in the upper half-width, then a nearly full-width rounded photograph of a hand using the product interface. The wide image is about 1312px by 711px inside nested side insets.

**Transfer:** Use for a capability that needs context and a close view, not a whole grid of unrelated features.

### Photographic proof

**Observed:** A 900px full-bleed scene has a short caption kicker, 32px heading, explanatory paragraph and two research actions on the left. Two Metric glass panels sit over the subject at right. Text and panels occupy the middle vertical region, leaving the photograph legible around them.

**Transfer:** Use a verifiable result or benchmark and link to its basis. Keep the glass treatment even when proof is a count, duration or qualitative test result rather than a percentage.

### Practical feature mosaic

**Observed:** A pale-blue chapter holds Feature mosaic card in a tall-left, wide-upper-right and paired-small-lower-right composition with 25px gaps.

**Transfer:** Group tangible practical advantages into a mixed-size mosaic; prioritize one benefit rather than giving every fact identical emphasis.

### Split FAQ

**Observed:** A centered 1200px container uses 150px vertical padding. At left a 460px-wide section lead sits above Primary button with 50px separation; at right FAQ row forms the question stack. The left introduction is sticky in the desktop layout.

**Transfer:** Answer the major adoption questions with plain language and keep the contact action available beside them.

**Text style:** `section-lead` — Hanken Grotesk 500 · 34px/1.15

### Utility-to-monument ending

**Observed:** Footer field starts with Notice inset inside a 1200px container, then Footer navigation and a company-information column separated by 48px group gaps. A fine rule and small copyright line precede Monumental identity sign-off. The same 1115px-tall closing construction accompanies both product and company narratives.

**Transfer:** Preserve useful compact information above the expansive final name. Include a bounded notice only when the product genuinely needs one; always retain the monumental typographic ending.

### Editorial proof and principles

**Only for:** company storytelling

**Observed:** White editorial field holds a centered 34px heading, a 1080px-wide product view and paired explanatory columns with 64px gap. Status pills differentiate present capability from research. Later, a pale-blue split places a short lead at left and a 640px-wide numbered list at right; each row is about 77px tall with fine separators and 18px numbers.

**Transfer:** Separate what exists now from what is being developed. Use the numbered treatment for concise operating ideas, not generic feature cards.

### Human invitation

**Only for:** recruiting invitations

**Observed:** Photographic invitation fills a 900px chapter. Centered heading, 560px support paragraph and Invitation action form a narrow top-centered stack with 24px gaps over the sky field.

**Transfer:** Close a company or community narrative with a personal invitation and a single practical contact route.

## Page flow

**Storyline:** human promise → understandable mechanism → lived benefits → deeper product proof → confidence and practical details → useful answers or invitation → monumental identity

### Product marketing and adoption

1. **Promise** — Photographic opening and compact floating conversion navigation.
2. **Orientation** — Short logo strip and visual process cards.
3. **Mechanism** — Navy split pairs a technical explanation with product-in-use photography.
4. **Capability chapters** — Everyday-use cards, interface fan, insight photograph and deeper data views alternate pale fields.
5. **Quantified proof** — Full-bleed human photograph supports glass metrics and research destinations.
6. **Practical confidence** — Standalone 16:9 video and white feature mosaic explain the tangible experience.
7. **Objection handling** — Split FAQ with a contact action.
8. **Closing identity** — Dark utility footer, important notice and oversized wordmark.

**Transfer:** Use this as a library of persuasive beats, selecting the needed demonstrations and proof for the new product rather than repeating every chapter.

### Company narrative and human trust

1. **Purpose** — Sky-backed portrait opening with small category label and mission promise.
2. **Credibility** — Product view and paired present-versus-research explanations.
3. **Underlying belief** — Full-bleed runner scene supports a short foundational explanation.
4. **Origin** — Narrow prose and a candid working-life photo strip.
5. **Operating approach** — Pale-blue numbered principle list.
6. **Human proof** — Three-column portrait directory.
7. **Invitation** — Full-bleed sky photograph, centered copy and direct email action.
8. **Closing identity** — Shared dark utility footer and monumental wordmark.

**Transfer:** For company or community pages, trade some product demonstrations for origin, people and a direct invitation; keep the photographic opening and typographic ending.

## Writing

Calm, concrete and quietly optimistic. Technical explanations earn trust by saying what is measured, how it works and where the reader keeps control.

**Do not copy:** Do not reuse Alveos names, logos, artwork, people, study results, patents, performance numbers, institutional affiliations or health claims. Source examples demonstrate sentence construction only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you; use we for commitments and research. Name the product when explaining what it actually does.
- **Rhythm:** Headlines are usually short sentence-case statements or two linked clauses. Support alternates a crisp benefit with a longer mechanism paragraph; occasional questions invite rather than pressure.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Two linked statements: understanding followed by an achievable action. | 6–12 words | “Understand your state. Change it with breath.” |
| Capability heading | Plain-language outcome with a permissive tone. | 4–9 words | “Dive into the data if you want.”<br>“Know what works for you” |
| Technical explanation | Name the mechanism, then connect it to a practical benefit. | 2–4 sentences | “[Brand] uses a patented ACM-sensor technology to capture signals directly from the chest.” |
| Action | Short verb-led instruction with a concrete destination. | 2–4 words | “See the science”<br>“Ask a question!” |
| Invitation | Human question followed by an approachable direct request. | 4–8 word heading | “Feel this mission too?” |

**Words and phrasing to use:** notice; understand; choose; check in; what changed; for you; over time; what works; research

**Avoid:** revolutionary; biohack your life; guaranteed transformation; superhuman; unlock limitless potential

**Rules:**

- Keep benefits tied to an observable behavior or product operation.
- Distinguish current capabilities from research or future possibilities.
- Describe agency: the product informs or cues; the person chooses.
- Use technical terms only when the next sentence explains their significance.
- Write customer questions as customers would ask them, not as sales headlines.

## Do's and Don'ts

### Do

- Keep the hero display at 42px/1.05 and 400 weight, with -0.02em tracking.
- Preserve 24px/1.2 hero support against a full-bleed human scene.
- Use 32px regular feature headings and 18px/1.6 body copy.
- Give the floating navigation 32px outer breathing room and 20px backdrop blur.
- Use 40px rounding for metric glass, feature cards and default action capsules.
- Reserve 120px–160px vertical intervals for chapter-level breathing space.
- Stage interface panels as a bottom-anchored arc, not a flat row.
- Close with a nearly full-width identity sculpture on the near-black footer.

### Don't

- Do not enlarge every chapter title to 64px or make it bold; imagery carries the scale.
- Do not turn the entire page navy; the pale reading chapters are essential counterweights.
- Do not scatter saturated interface colors into marketing headings or primary controls.
- Do not put heavy drop shadows under product feature mosaics; the white cards are flat against pale blue.
- Do not turn photographic metric glass into opaque white statistic tiles.
- Do not apply the 10px invitation-action corners to ordinary conversion buttons.
- Do not use uppercase tracked labels for all navigation and body headings; that treatment is confined to the small editorial eyebrow.
- Do not make the final wordmark a small centered logo beneath a conventional short footer.

## Motion and responsive

### Motion

**Observed:**

- No action or surface transition declarations were matched. A source easing declaration uses ease-out, but no applicable duration or interaction is established.
- Media includes video and layered product views; visible settled compositions are the design target.

**Transfer:**

- Keep the interface fan and exploded product arrangement legible as static compositions; motion must not be needed to understand their content.

**Unknown:**

- Hover, focus-visible and active styling; animation durations and exact scroll choreography.

### Responsive

**Observed:**

- Declared width breakpoints include 767px, 810px and 1439px; company layouts also include a 1200px boundary.

**Transfer:**

- On narrow screens, retain the person/product focal point and a separate clear region for white hero copy.
- Reduce multi-column card layouts to fewer columns while preserving portrait framing; retain the centered fan's tallest panel and clip receding edges.
- Scale the closing identity to available width rather than wrapping it into normal text.

**Unknown:**

- Exact mobile typography, navigation replacement, stacking order and narrow-screen section heights.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
