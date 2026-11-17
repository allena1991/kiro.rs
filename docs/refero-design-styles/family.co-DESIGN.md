# Family — friendly shapes, serious utility

## Overview

A bright, approachable product style pairs tightly set geometric headlines with practical grotesk body text. White and warm chalk surfaces give cheerful flat characters, colorful symbols and carefully framed interface demonstrations room to breathe. It suits consumer software that wants to feel capable without becoming technical or intimidating; the page is spacious, but its product explanations remain concrete.

### Essentials

- Friendly authority through tight geometric type: Family at 68px/1.1, weight 500 and -0.02em tracking for the opening; section headings settle at 44px/48px with -1.4px tracking.
- An illustrated embrace rather than a central device hero: a two-line centered promise and 408px-wide support sit between colorful, edge-clipped flat illustrations; the opening has 120px top and 96px bottom padding beneath a 95px header.
- Actions are soft, compact capsules: pair a charcoal primary with a warm cream secondary, both 48px high with 32px radii, 17px medium labels and leading solid icons; navigation uses 32px-high versions.
- Color lives in small expressive islands: white and #fbfaf9 dominate the marketing canvas, while blue, gold, green and orange identify chapter eyebrows, checklists and links. Saturated broad areas belong to illustrations, not section backgrounds.
- Product proof is cropped and tactile: upright black-rimmed devices emerge from 12px-radius chalk panels, alongside isolated enlarged interface fragments. Keep this device even without a finished app by showing one believable task in a simplified interface.
- A friendly graphic world carries the emotional story: use flat rounded characters, tiny stars and useful symbols at the opening and in a later reassurance or closing scene. A minimum equivalent is an original geometric character with expressive eyes, limbs and a handful of companion shapes.
- Proof extends past the content grid: two testimonial tracks use 204px-high white cards, 24px horizontal gaps, 28px between rows and faded outer edges; finish with an illustrated warm band and a restrained small-link footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Clear orange | `#ff5310` | `--color-orange` | text, accent, link | Activity chapter label, checks and FAQ onward link. |
| Helpful blue | `#3784f4` | `--color-blue` | text, accent, link | Core feature labels, reassurance checklists and final action. |
| Warm gold | `#ca9230` | `--color-gold` | text, accent | Rich-media chapter label, icons and short capability lists. |
| Fresh green | `#44c67f` | `--color-green` | text, accent | Ease-of-use chapter label and checks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action charcoal | `#171717` | `--color-action` | action, background | Primary capsules. |
| Heading ink | `#121212` | `--color-ink` | text | Section headings, card titles and secondary-action labels. |
| Navigation charcoal | `#282624` | `--color-nav-ink` | text | Navigation labels. |
| Soft charcoal | `#343433` | `--color-display-ink` | text | Opening headline and neutral social symbols. |
| Warm graphite | `#474645` | `--color-body` | text | Body paragraphs and explanatory text. |
| Muted graphite | `#7e7e7d` | `--color-muted` | text | Visible muted card copy; source graphite at 70% opacity over white. |
| Footer gray | `#a7a7a7` | `--color-footer-muted` | text, link | Visible footer links; #222222 at 40% opacity over white. |
| Chalk edge | `#f2f0ed` | `--color-edge` | border | Hairline rules, testimonial inset edges and FAQ separators. |
| Action cream | `#f6f4ef` | `--color-cream` | action, surface | Secondary capsules. |
| Warm chalk | `#fbfaf9` | `--color-chalk` | surface, background | Product panels, article images and full-width warm bands. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, header and testimonial cards; reversed primary-action text. |

## Typography

- **Family** — Opening and section headlines. Friendly geometric sans with rounded forms, open counters and a compact, tightly fitted silhouette. If unavailable, use **DM Sans**. Use weight 500 and retain the tight headline tracking. Font stack: "Family", "DM Sans", -apple-system, system-ui, Segoe UI, Helvetica, Arial, sans-serif.
- **Inter** — Body copy, navigation, buttons, captions and smaller titles. Practical neutral grotesk; regular paragraphs balanced by medium and semibold utility labels. Font stack: "Inter", -apple-system, system-ui, Segoe UI, Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Family | 500 | 68px | 1.1 | -0.02em | Centered two-line opening promise. |
| heading | Family | 500 | 44px | 48px | -0.0307em | Section leads, including paired statements and closing call. |
| article-title | Inter | 500 | 23px | 25px | -0.019em | Editorial preview headlines. |
| body-lg | Inter | 400 | 19px | 27px | -0.016em | Capability chapter paragraphs and detail explanations. |
| question | Inter | 500 | 19px | 27px | -0.016em | FAQ question rows. |
| body | Inter | 400 | 17px | 26px | -0.013em | Feature summaries, testimonials and closing support. |
| body-emphasis | Inter | 500 | 17px | 26px | -0.013em | Hero support and icon-list labels. |
| button | Inter | 500 | 17px | 1 | -0.013em | Opening capsule labels. |
| card-title | Inter | 600 | 17px | 26px | -0.013em | Short benefit-card titles. |
| caption | Inter | 400 | 15px | 22px | -0.009em | Muted benefit descriptions and publication dates. |
| navigation | Inter | 500 | 15px | 10px | normal | Compact navigation anchors; padding supplies the click target. |
| eyebrow | Inter | 600 | 14px | 20px | -0.006em | Sentence-case chapter markers and compact feature headings. |
| small-label | Inter | 500 | 13px | 18px | -0.01em | Footer column headings and demo secondary labels. |

**Notes:**

- Keep the headline weight at 500 rather than substituting a bold cut. The geometric headline face supplies the personality; Inter supplies reading clarity.
- Large headings tighten more aggressively than paragraphs. Eyebrows remain sentence case, not spaced capitals.
- Section titles often combine two adjacent statements in the same 44px recipe; do not create a second, lighter typographic tier for the second statement.

## Layout

**Density:** Airy between chapters, compact within labels and actions; wide empty margins let the illustrations and product demonstrations feel approachable.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Small feature heading to paragraph. |
| 16px | Eyebrow to headline and gap between opening actions. |
| 20px | Typical chapter heading-to-support gap. |
| 24px | Container side padding, testimonial-track gaps and common support spacing. |
| 32px | Testimonial inset padding and three-card grid gaps. |
| 48px | Checklist column separation. |
| 92px | Main two-column chapter gutter. |
| 104px | Warm feature band's top and bottom padding and FAQ top padding. |
| 120px | Opening top padding below navigation. |

### Containers and grids

- **main-container**: max width 1072px · side padding 24px. Centered outer box; yields 1024px usable content at desktop.
- **chapter-grid**: 2 columns · gap 92px. Equal 466px columns for a demonstration and its explanation; alternate media sides.
- **three-up-proof**: 3 columns · gap 32px. Three 320px warm panels, usually containing cropped devices.
- **feature-text-grid**: 2 columns · gap 80px. Two 472px text columns with 97px vertical row gaps inside the warm band.
- **hero-support**: max width 440px · side padding 16px. Centered support wrapper, yielding 408px text width.

## Corner radius

| Element | Radius |
| --- | --- |
| capsules | 32px |
| product-panels | 12px |
| testimonial-cards | 10px |
| navigation-links | 6px |
| demo-thumbnails | 4px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| product demonstrations | floating-ui | `0px 1px 6px 0px rgba(0,0,0,0.04), 0px 0px 24px 0px rgba(0,0,0,0.05)` | Isolated interface detail floating within a demonstration, not ordinary marketing cards. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and sticky header.

**CSS:** `background: #ffffff; color: #474645`

#### Chalk panel · level 1

**Use:** Benefit cards, device backings and isolated product-detail stages.

**CSS:** `background: #fbfaf9; border-radius: 12px; overflow: hidden`

**Observed:** Soft warm backing without a heavy border or ordinary drop shadow.

**Transfer:** Use the same backing for a new product's proof rather than inventing a different colored panel for each feature.

#### Warm band · level 0

**Use:** Broad feature explanation and illustrated closing call.

**CSS:** `background: #fbfaf9`

**Observed:** Full-bleed background behind the centered content grid, with square outer corners.

**Transfer:** Use sparingly to mark an explanatory or emotional change of pace.

#### Outlined white card · level 1

**Use:** Social proof tracks.

**CSS:** `background: #ffffff; border-radius: 10px; box-shadow: 0px 0px 0px 1px #f2f0ed inset`

**Observed:** Fine inset boundary rather than a raised card.

## Components

### Sticky navigation

**Use:** Persistent orientation and compact conversion actions.

**CSS:** `position: sticky; top: 0px; height: 95px; background: #ffffff`

**Observed:** Small symbol and wordmark on the left, text menus nearby, login and dark conversion capsule at the far right. A faint rule follows the inner content width.

**Transfer:** Use the main container; keep the product logo modest.

### Navigation link

**Use:** Short menu labels.

**CSS:** `padding: 11px 10px; border-radius: 6px; background: #ffffff; color: #282624`

**Text style:** `navigation` — Inter 500 · 15px/10px

**Observed:** Dropdowns add a small down chevron; plain external navigation remains text-led.

**States:** Declared: hover on ancestor changes background to warm chalk and text to soft charcoal; focus-visible uses a 2px solid muted-gray outline.

### Primary button

**Use:** Opening conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; height: 48px; padding: 0px 24px 0px 22px; border-radius: 32px; background: #171717; color: #ffffff`

**Text style:** `button` — Inter 500 · 17px/1 · tracking -0.013em

**Observed:** Leading solid platform icon and a single-line label. Compact header variant is 32px high with 14px side padding.

**States:** Declared: hover background-color #121212.

### Secondary button

**Use:** Opening video or alternate action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 11px; height: 48px; padding: 0px 20px 0px 19px; border-radius: 32px; background: #f6f4ef; color: #121212`

**Text style:** `button` — Inter 500 · 17px/1 · tracking -0.013em

**Observed:** Leading solid play triangle; paired horizontally with Primary button.

**States:** Declared: hover background rgb(234, 230, 221).

### Benefit card

**Use:** Fast visual overview of product qualities.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #fbfaf9; border-radius: 12px; padding: 0px 22.8px 14px 22.8px; overflow: hidden`

**Text style:** `card-title` — Inter 600 · 17px/26px · tracking -0.013em

**Observed:** Large interface fragment above a short title and muted caption, separated by 3px. One tall card occupies the first column while four smaller cards fill two adjacent columns.

**Transfer:** Show specific task fragments rather than generic feature icons.

### Device panel

**Use:** Detailed capability demonstration.

**CSS:** `background: #fbfaf9; border-radius: 12px; overflow: hidden; height: 532px`

**Observed:** A front-facing black-rimmed phone is centered and extends below the backing's bottom boundary. It is shown larger than a complete device would fit.

**Transfer:** For desktop software use a similarly cropped upright application panel, keeping real interface content legible.

### Demo teaser

**Use:** Small video action below a capability checklist.

**CSS:** `display: flex; align-items: center; gap: 12.8px; height: 68px; padding: 12px 32px 12px 12px; border-radius: 12px; margin-left: -12px; margin-right: -12px`

**Text style:** `small-label` — Inter 500 · 13px/18px · tracking -0.01em

**Observed:** A 78px by 44px photographic thumbnail with play icon precedes two stacked lines: a 15px medium task title, then a muted 13px action. The invisible hit area extends left of the aligned thumbnail.

**States:** Declared: hover adds a 1px inset chalk-edge outline; focus-visible adds a 2px inset muted-gray outline.

### Testimonial card

**Use:** Human social proof in horizontally overflowing tracks.

**CSS:** `background: #ffffff; border-radius: 10px; box-shadow: 0px 0px 0px 1px #f2f0ed inset; padding: 32px; height: 204px; max-width: 475px`

**Text style:** `body` — Inter 400 · 17px/26px · tracking -0.013em

**Observed:** Avatar, name and handle at top left, small social glyph at top right, then conversational quote. Widths vary between 390px and 540px across the tracks.

**Transfer:** Use authentic feedback, maintaining varied quote lengths without star ratings or oversized quotation marks.

### FAQ row

**Use:** Compact objection handling.

**CSS:** `display: flex; align-items: flex-start; gap: 24px; padding-bottom: 28px; margin-bottom: 28px; border-bottom: 1px solid #f2f0ed`

**Text style:** `question` — Inter 500 · 19px/27px · tracking -0.016em

**Observed:** Small orange plus sits before the question, not at the far right; questions occupy the right half of a two-column section.

### Article preview

**Use:** Editorial proof of ongoing product development.

**CSS:** `border-radius: 12px; overflow: hidden; background: #fbfaf9`

**Text style:** `article-title` — Inter 500 · 23px/25px · tracking -0.019em

**Observed:** The CSS describes the image backing only: 494px by 261px, followed outside the backing by date, headline and a short truncated paragraph on white. Two previews sit side by side.

### Footer columns

**Use:** Low-key resource navigation after the closing band.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); gap: 80px`

**Text style:** `small-label` — Inter 500 · 13px/18px · tracking -0.01em

**Observed:** A small isolated brand symbol precedes three link columns; copyright and social icons sit far right. Column heads are dark; 13px links are pale gray with 6px row gaps. The footer has 68px top and 96px bottom padding.

## Imagery and graphics

### Flat character constellation

**Use:** Signature opening surround and later emotional illustrations.

**Observed:** Cheerful flat-vector characters mingle with shields, locks, coins, checks, arrows, stars and soft cream shapes. Blue, green, yellow and orange-red solids have small tonal facets, dark curved limbs and simple faces. The opening artwork extends beyond both viewport edges while leaving a clear central text corridor.

**Transfer:** Create an original character vocabulary tied to the new product's benefits. Retain the surrounding constellation and a later small narrative scene; a few well-made geometric characters are better than many stock icons.

**Build:** Use SVG groups on a transparent background: combine rounded rectangles, circles and scalloped silhouettes into 2–3 characters, add dark oval eyes and curved strokes for limbs, then surround them with small four-point stars, discs, checks and arrows. Use sky blue, sunny yellow, vivid green and orange-red, with cream secondary shapes and darker facets at roughly 10–20% opacity. Place two asymmetrical clusters on opposite sides of the opening, clipping their outer edges; leave the middle third clear. Reuse one character in a roughly 435px-wide reassurance drawing and a roughly 495px-wide horizontal closing vignette.

### Cropped product devices

**Use:** Primary functional proof in grids and alternating chapters.

**Observed:** Black polished phone frames with white interfaces, directly front-facing rather than tilted. Large chapters show a 392px by 773px device in a shorter warm backing; smaller three-up panels show 237px by 468px devices. Screens are crisp and primarily neutral, with small colored status elements.

**Transfer:** Insert real screens with one clear task per image. Without finished screens, draw a plausible minimum interface with a title, a few meaningful rows and one task state; do not use empty placeholders.

### Enlarged interface fragments

**Use:** Benefit mosaic, details rail and editorial thumbnails.

**Observed:** One small interaction is isolated and enlarged: a status chip, a stacked notification, a compact control or a short menu. Warm neutral backings hold mostly white fragments with occasional charcoal surfaces and vivid functional color. Some fragments have subtle layered shadows.

**Transfer:** Show the new product's most reassuring microinteraction or clearest state change, not an entire illegible dashboard.

**Build:** Center one concise interface fragment inside a 12px-radius chalk stage. Layer two slightly offset white cards behind a foreground card for a stack, or use a single colored status capsule. Use the floating-ui shadow only on the fragment, preserving broad empty space around it.

### Demo thumbnails

**Use:** Compact action teasers.

**Observed:** Small landscape photographs show a hand interacting with a phone, with a white play mark overlaid. These are utility-sized rather than full-bleed lifestyle photography.

**Transfer:** Film or photograph the actual product in use and select a clear 78px by 44px frame.

### Icons

**Observed:** Small checklist checks are 18px by 14px with 2.3px strokes. Feature symbols are thin colored outlines; play and platform marks are solid. Menu chevrons are 10px with 2px round strokes.

**Transfer:** Use a consistent outline family for benefits and reserve filled glyphs for recognizable action symbols. Match each checklist's icon color to its eyebrow.

## Section recipes

How recurring sections are built.

### First screen: Illustrated embrace opening

**Observed:** A 95px white Sticky navigation sits above a white stage with 120px top and 96px bottom padding. Behind the text, a broad transparent illustration spreads beyond both side edges, with large friendly figures and small symbols framing the center. The 68px display headline occupies two centered lines in roughly the middle third, followed by a centered two-line 408px-wide support paragraph and the Primary button plus Secondary button with a 16px gap. All headline, support, actions and side art are visible within the first 900px. Beneath the stage, a centered 44px section title begins at about 723px and the tops of the benefit mosaic enter at about 829px; the rest of that grid is below the fold.

**Transfer:** Keep the central promise clear and surround it with an original flat character-and-symbol world rather than placing a device over the headline. If no illustration asset exists, construct the geometric SVG constellation. Editorial or narrower-purpose pages can use the 44px heading tier with a smaller illustration, retaining the white canvas and compact actions.

**Avoid:** Do not turn this into a giant centered phone hero, put the illustration behind the text at low opacity, or replace the two-line promise with a full-width uppercase slogan.

**Text style:** `display` — Family 500 · 68px/1.1 · tracking -0.02em

### Visual benefit mosaic

**Observed:** A centered heading leads into Benefit cards: one double-height panel at left and four smaller panels arranged in the next two columns, with 34px gaps. Titles and muted captions anchor the bottom of each card; enlarged product details occupy the majority above.

**Transfer:** Use five concise qualities backed by distinct visible interactions. Preserve the asymmetric hierarchy rather than duplicating five equal tiles.

### Three-up task showcase

**Observed:** A 44px heading pair sits above three 320px-wide warm Device panels, 32px apart. Devices rise from the panels and are clipped at their bottoms; small labels identify tasks.

**Transfer:** Group three related tasks or setup steps, keeping one demonstration per panel.

### Warm capability index

**Observed:** Warm band with 104px vertical padding; a two-column feature-text grid uses 80px horizontal and 97px vertical gaps. Colored 14px headings precede 17px explanatory paragraphs by 10px.

**Transfer:** Use for a compact set of functional promises that do not each need a large demonstration.

### Alternating capability chapter

**Observed:** A two-column chapter-grid pairs Device panel with a colored eyebrow, 44px heading, 19px paragraph, colored checklist and Demo teaser. Media alternates left and right. Eyebrow-to-title spacing is 16px; title-to-support is 20–26px. Short thin rules separate chapters.

**Transfer:** Give each chapter one benefit and one accent color. A later chapter can replace the device with a flat reassurance illustration without changing the text hierarchy.

**Text style:** `heading` — Family 500 · 44px/48px · tracking -0.0307em

### Editorial pair

**Observed:** A left-aligned section heading precedes two Article previews; imagery stays warm and product-focused. Dates are small and muted, titles use 23px Inter, and descriptions end after a few lines.

**Transfer:** Use for useful product stories or announcements rather than adding unrelated stock photography.

### Detail rail

**Observed:** The left half contains a 44px heading and one 19px support sentence; the right half contains a vertical succession of warm demonstration panels, small blue labels and explanatory paragraphs. Panels are 498px wide and about 223px high; items have roughly 71.4px gaps.

**Transfer:** Use the extended vertical rail to reward closer inspection of a few small interaction benefits rather than repeating the main chapter layout.

### Social proof tracks

**Observed:** A main-container heading and supporting line sit opposite a modest social follow link. Two overflowing tracks of Testimonial cards extend beyond the grid and fade into white at the viewport sides, separated by 28px.

**Transfer:** Preserve the sense of a wider conversation with authentic quotes and uneven card widths.

### Questions beside a heading

**Observed:** A 44px heading occupies the left half; three FAQ rows occupy the right half, followed by an orange text-and-arrow onward link. Section padding is 104px above and 92px below.

**Transfer:** Answer the few questions blocking adoption; keep additional detail behind the onward action.

### Illustrated closing and small footer

**Observed:** A 347px-high Warm band pairs a 44px heading, a short 17px paragraph and blue text-arrow action on the left with a 495px by 179px horizontal character-and-garden vignette on the right. It is followed immediately by the white Footer columns section, a small symbol on the left and pale copyright/social marks far right.

**Transfer:** Close with a warm invitation and a small visual resolution using the established character world. Keep the final conversion as a text link rather than introducing an oversized dark CTA slab.

**Text style:** `heading` — Family 500 · 44px/48px · tracking -0.0307em

## Page flow

**Storyline:** Friendly promise → visible task proof → capability explanations → reassurance → closer product details and human proof → objections → illustrated invitation.

### A consumer-product landing page that turns unfamiliar technology into approachable daily utility

1. **Promise** — Centered two-line benefit framed by playful illustration, with a primary conversion and video alternative.
2. **Product demonstration** — Asymmetric benefit mosaic and three-up cropped-device showcase.
3. **Capability chapters** — Warm text index followed by alternating device-and-copy chapters with colored markers.
4. **Reassurance** — Friendly character illustration and concise control or trust benefits.
5. **Depth** — Additional task grid, editorial previews and an extended rail of small interaction demonstrations.
6. **Social proof** — Two softly faded horizontal testimonial tracks.
7. **Objection handling** — A small FAQ list beside a section title.
8. **Closing call** — Illustrated warm invitation band followed by tiny resource columns.

**Transfer:** Choose enough proof to make the new product understandable; vary the number and order of chapters while retaining the illustrated embrace, cropped functional proof, human testimony and gentle illustrated close.

## Writing

Warm, confident and matter-of-fact. It makes complicated functionality sound familiar, with brief benefits followed by concrete explanations rather than technical showmanship.

**Do not copy:** Do not reuse Family's name, logo, characters, Ethereum claims, security assertions, customer names, testimonials, dates or product-specific facts. Source quotations below demonstrate voice only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your. Use we sparingly for care and responsibility; name the product when explaining how it works.
- **Rhythm:** Headlines favor short, rounded phrases and balanced pairs. Supporting paragraphs are one to three plain sentences; longer explanations remain specific. Exclamation marks and emoji are mainly confined to authentic customer quotes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A familiar personal preference expressed as a simple category promise. | 4–7 words | “Your favorite crypto wallet.” |
| Chapter heading | Pair capability with an emotional relief or effortless outcome. | 4–8 words | “Relentless protection. Restful ease.”<br>“Masterful management. Effortless onboarding.” |
| Supporting line | State the task or quality plainly, then make its benefit tangible. | 1–3 sentences | “We sweat the details, no matter how small.” |
| Primary action | Direct verb plus platform or specific next step. | 2–4 words | “Download on iOS”<br>“Watch the Video” |
| Eyebrow | One approachable quality in sentence case. | 1 word | “Seamless”<br>“Understandable” |

**Words and phrasing to use:** easy; simple; your; effortless; at a glance; details; care; full support

**Avoid:** revolutionary; disruptive; enterprise-grade jargon; all-caps urgency; vague superlative stacks

**Rules:**

- Use short chapter labels to orient rather than to shout.
- Follow a broad benefit with the actual user action or visible outcome.
- Balance capability and reassurance in paired headlines.
- Keep conversion labels literal and platform-aware.

## Do's and Don'ts

### Do

- Keep the opening display at 68px/1.1 with weight 500 and -0.02em tracking.
- Use 44px/48px headings consistently through the main narrative and close.
- Center content inside a 1072px container with 24px inner side padding.
- Let cropped demonstrations fill 12px-radius warm panels without heavy outer borders.
- Carry one accent through a chapter's 14px eyebrow and 18px checklist icons.
- Keep opening capsules 48px high and header capsules 32px high.
- Maintain 32px testimonial padding and subtle 1px inset edges.
- Resolve the page with a warm illustrated band and a small white footer.

### Don't

- Do not replace warm chalk panels with cold blue-gray dashboard surfaces.
- Do not use 700-weight headings to manufacture hierarchy; weight 500 and scale provide it.
- Do not spread colored backgrounds across every chapter; color is concentrated in art and small markers.
- Do not place dramatic drop shadows on every card; ordinary marketing panels are flat.
- Do not tilt devices into perspective or surround them with glowing neon effects.
- Do not replace the asymmetric benefit mosaic with a uniform icon-card grid.
- Do not make footer links as dark or prominent as the body paragraphs.
- Do not turn the small demo teaser into another 48px filled conversion button.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare 0.2s ease-out transitions; the demo teaser declares box-shadow 0.1s.
- Two testimonial animation declarations use 120s linear infinite timing.
- Other graphic transforms declare 220ms cubic-bezier(0.19, 1, 0.22, 1).

**Transfer:**

- Use the long linear movement for the overflowing social-proof tracks, preserving white edge fades.
- Keep small action changes subtle and fast; do not make button hover a large spatial event.

**Unknown:**

- Exact animation keyframe content and all scroll-trigger choreography are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 390px, 410px, 420px, 580px, 720px, 768px, 880px and 920px.

**Transfer:**

- On narrow screens, preserve the central promise first and move the side constellations outward rather than shrinking them into unreadable confetti.
- Stack text and device chapters into one column while retaining the deliberate bottom clipping and warm backing; allow proof tracks to remain horizontally overflowing.

**Unknown:**

- Mobile navigation, exact type scaling and breakpoint-specific reordering are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
