# Netflix — cinematic abundance, instant access

## Overview

A cinematic, dark storefront pairs an immersive wall of imagery with unusually direct conversion copy. Black, white and vivid red carry the hierarchy, with midnight blue and plum reserved for soft atmospheric accents. Bold sans-serif headlines, colorful poster artwork and compact utility text make the page feel abundant without making the buying decision complicated.

### Essentials

- The opening sells abundance behind a single decision: a full-width, darkened image mosaic supports a centered 588px text column and a 56px, weight-700 headline at 1.25 line height.
- Red behaves like a conversion signal, not a page wash: #e50914 fills compact actions on a predominantly #000000 canvas; the main action is 56px high with 4px corners and a white chevron.
- A glowing horizon separates spectacle from browsing: a shallow curved 4px red-to-magenta edge sits above a blue atmospheric glow, spanning beyond the viewport.
- Images become a ranked shelf rather than generic cards: 185×259px portrait art with 8px corners carries overlapping 100px outlined numerals near its lower-left edge. Use ranked outcomes or product examples when no catalog exists.
- Supporting benefits live in midnight panels: 16px-radius cards use a 149deg navy-to-plum gradient, 24px medium headings, muted 16px descriptions and a small illustrative object at the lower right.
- Objections are given broad, blunt controls: full-width #2d2d2d accordion rows use 24px regular questions, 24px padding and 8px separation; the ending returns to the same email-and-action construction before a subdued four-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion red | `#e50914` | `--color-action` | action, accent | Primary and compact header actions; a concentrated accent rather than a large section fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Benefit navy | `#192247` | `--color-benefit-navy` | surface | Upper cool stop of benefit panels. |
| Benefit plum | `#210e17` | `--color-benefit-plum` | surface | Lower warm stop of benefit panels. |
| Offer plum | `#261733` | `--color-offer-plum` | surface | Left stop of the horizontal offer strip. |
| Offer navy | `#151a3f` | `--color-offer-navy` | surface | Right stop of the horizontal offer strip. |
| Horizon blue | `#1a275c` | `--color-horizon-glow` | accent, background | Visible rgba(64,97,231,0.4) over black in the glow below the curved divider. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White foreground | `#ffffff` | `--color-foreground` | text | Headlines, questions and action text. |
| Secondary white | `#b3b3b3` | `--color-muted` | text | Visible white at 70% over black; descriptions and footer links use rgba(255,255,255,0.7). |
| Fine-print gray | `#808080` | `--color-subtle` | text | Visible white at 50% over black for the final low-emphasis notice. |
| Field edge | `#5a5a5a` | `--color-field-edge` | border | Visible rgba(128,128,128,0.7) over black; outlines form controls. |
| Rank underlay | `#414141` | `--color-rank` | text | Underlying numeral color; the visible rank treatment reads black-faced with a thin pale outline. |
| Secondary action gray | `#333333` | `--color-secondary-action` | surface, action | Neutral baseline of rgba(128,128,128,0.4) over black; over the offer gradient this translucent action reads as a lighter violet-gray. |
| Accordion charcoal | `#2d2d2d` | `--color-accordion` | surface | Question rows and their expanded answer panels. |
| Translucent field black | `#0f0f0f` | `--color-field` | surface | Visible rgba(22,22,22,0.7) over black; allows hero imagery to remain faintly present beneath fields. |
| Black canvas | `#000000` | `--color-canvas` | background | Dominant page background and the visual backing for media. |

## Typography

- **Netflix Sans** — All marketing headings, body copy, numerals and controls. Clean, sturdy sans serif with a generous x-height and emphatic bold display cut. If unavailable, use **Roboto**. Use 400, 500 and 700; preserve normal tracking and the compact text widths. Font stack: "Netflix Sans", "Helvetica Neue", "Segoe UI", Roboto, Ubuntu, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| rank | Netflix Sans | 700 | 100px | 1 | normal | Oversized overlapping shelf numerals, not headings or statistics. |
| display | Netflix Sans | 700 | 56px | 1.25 | normal | Centered opening headline, usually two lines. |
| primary-action | Netflix Sans | 500 | 24px | 1 | normal | Main conversion button label. |
| form-prompt | Netflix Sans | 400 | 16px | 1.5 | normal | Conversion prompt and field label text. |
| secondary-action | Netflix Sans | 500 | 16px | 1 | normal | Offer strip secondary button. |
| compact-action | Netflix Sans | 500 | 14px | 1 | normal | Compact header action. |
| utility-link | Netflix Sans | 400 | 14px | 1.5 | normal | Underlined footer navigation. |

**Notes:**

- Keep tracking normal throughout; the contrast comes from weight and scale, not letterspacing.
- Section and benefit headings use Netflix Sans, 24px, weight 500, normal line height and normal tracking. Questions and answers use the same family and size at weight 400 with normal line height and tracking. Opening reassurance and offer titles use 20px, weight 500, normal line height and tracking.
- Benefit descriptions use Netflix Sans, 16px, weight 400, normal line height and tracking. Muted color, rather than smaller size, separates them from primary copy.

## Layout

**Density:** Comfortable overall, with a tightly grouped conversion cluster and dense media shelves separated by clear black intervals.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Accordion row separation and input-to-button gap. |
| 12px | Footer item gaps and compact utility grouping. |
| 16px | Headline-to-support gap, benefit description offset, benefit column gap and form-row top spacing. |
| 24px | Accordion padding and main button horizontal padding. |
| 32px | Opening reassurance-to-form gap and offer strip side padding. |
| 64px | Separation between major content sections. |
| 96px | Black breathing room below the footer. |

### Containers and grids

- **content-shell**: max width 1920px · side padding 148px. Centered outer shell; at 1440px the content area is 1144px wide. Align shelves, benefit headings, questions and footer to the same edges.
- **opening-copy**: max width 588px. Centered narrow headline and first conversion form, floating over full-bleed imagery.
- **closing-form**: max width 783px · gap 8px. Centered final form; the field expands while the action retains its intrinsic width.
- **benefit-grid**: 4 columns · gap 16px. Equal 274px-wide cards at the desktop content width.
- **media-shelf**: 5 columns. Two visible rows of five portrait items. Each item occupies a 229px-wide slot with 22px side inset around 185px artwork; rows are scrollable shelves.
- **footer-grid**: 4 columns · gap 12px. Four equal utility columns with roughly 275px-wide items, aligned below the contact line.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 4px |
| media-tiles | 8px |
| benefit-and-offer-panels | 16px |
| accordion-rows | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| rank-legibility | `0px 0px 24px rgba(0, 0, 0, 0.5)` | Text shadow behind overlapping rank numerals; panels themselves remain shadowless. |

### Surfaces

#### Black canvas · level 0

**Use:** All content below and around imagery.

**CSS:** `background: #000000; color: #ffffff`

#### Cinematic scrim · level 1

**Use:** Darkens the full opening image behind navigation and text.

**CSS:** `background-image: linear-gradient(7deg, rgba(0,0,0,0.85) 10%, rgba(0,0,0,0.6) 97%)`

**Observed:** A broad, smoothly graded black overlay preserves the mosaic's color but suppresses detail beneath the headline; the top navigation has additional dark shading.

**Transfer:** Prioritize white-copy legibility over photographic brightness; keep the entire scene continuous rather than placing text in a separate box.

#### Midnight benefit panel · level 1

**Use:** Benefit cards.

**CSS:** `background-image: linear-gradient(149deg, #192247 0%, #210e17 96.86%); border-radius: 16px; backdrop-filter: blur(30px)`

**Observed:** Subtle cool-to-warm depth; no prominent border or drop shadow.

**Transfer:** Keep the gradient dark enough that white headings and muted descriptions remain the strongest elements.

#### Offer strip · level 1

**Use:** A compact highlighted value proposition.

**CSS:** `background-image: linear-gradient(91deg, #261733, #151a3f); border-radius: 16px`

**Observed:** A horizontal inset panel with a separate illustrative object sitting to its left.

**Transfer:** Use for a concise lower-friction option or valuable announcement, not for a full pricing table.

#### Question panel · level 1

**Use:** Accordion headings and answers.

**CSS:** `background: #2d2d2d; border-radius: 0px`

**Observed:** Flat, broad rectangular slabs are separated by black gutters; an expanded answer appears as a second slab directly below its question.

## Components

### Header navigation

**Use:** Minimal orientation without competing with the opening decision.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 88px`

**Observed:** A red wordmark sits left; a dark bordered language selector and Compact button sit right over the image. There is no long menu of product links.

**Transfer:** Use a compact brand identifier and one utility group; keep the header aligned with the content shell.

### Primary button

**Use:** Main conversion action beside an email field.

**CSS:** `background: #e50914; color: #ffffff; border-radius: 4px; height: 56px; padding: 12px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `primary-action` — Netflix Sans 500 · 24px/1

**Observed:** Text precedes a white right chevron. The opening and closing use the same action; width follows the label and icon.

**States:** Declared: hover changes background and foreground through local button variables and removes text decoration; active uses pressed variables. Exact resolved state colors and focus-visible treatment are unknown.

### Compact button

**Use:** Header account or utility action.

**CSS:** `background: #e50914; color: #ffffff; border-radius: 4px; height: 32px; padding: 4px 16px; display: flex; align-items: center`

**Text style:** `compact-action` — Netflix Sans 500 · 14px/1

**Observed:** A small solid action follows the language selector; it does not carry the large button's chevron.

### Secondary button

**Use:** Lower-emphasis action in the offer strip.

**CSS:** `background: rgba(128,128,128,0.4); color: #ffffff; border-radius: 4px; height: 40px; padding: 6px 16px; display: flex; align-items: center; justify-content: center`

**Text style:** `secondary-action` — Netflix Sans 500 · 16px/1

**Observed:** Sits at the right side of the offer strip, opposite its title and short description.

### Email field

**Use:** Low-friction first conversion step.

**CSS:** `height: 56px; background: rgba(22,22,22,0.7); border: 1px solid rgba(128,128,128,0.7); border-radius: 4px; color: #ffffff; padding: 24px 16px 8px; box-sizing: border-box`

**Text style:** `form-prompt` — Netflix Sans 400 · 16px/1.5

**Observed:** The label sits inside a translucent field; the field grows to use the remaining row width. A centered prompt sits above the row. The same surface is also used by the compact language selector.

**Transfer:** Use one essential field rather than a multi-input lead form.

### Ranked media tile

**Use:** Visual proof of breadth, popularity or range.

**CSS:** `position: relative; width: 185px; height: 259px; border-radius: 8px`

**Text style:** `rank` — Netflix Sans 700 · 100px/1

**Observed:** Portrait artwork fills the tile. A black-faced pale-outline numeral overlaps the lower-left edge and projects into the left inset; title artwork stays inside the image rather than becoming a separate caption card.

**States:** Declared: hover transform scale(1.05); focus-visible treatment unknown.

**Transfer:** Use meaningful ordered examples, projects or outcomes. Keep numerals as overlapping graphic labels rather than corner badges.

### Benefit card

**Use:** Short practical reasons to choose the product.

**CSS:** `width: 274px; min-height: 310px; border-radius: 16px; background-image: linear-gradient(149deg, #192247 0%, #210e17 96.86%); padding: 24px 16px; box-sizing: border-box; position: relative; overflow: hidden; font-size: 24px; font-weight: 500; line-height: normal`

**Observed:** A medium heading and muted body paragraph occupy the upper portion; substantial lower space is reserved for a 72px illustrative icon positioned toward the right.

**Transfer:** Describe a user outcome in the heading, then explain its practical scope in one short sentence.

### Question accordion

**Use:** Resolve practical objections without a separate help page.

**CSS:** `display: flex; justify-content: space-between; align-items: center; background: #2d2d2d; color: #ffffff; padding: 24px; min-height: 84px; box-sizing: border-box; width: 100%; border-radius: 0px; font-size: 24px; font-weight: 400; line-height: normal`

**Observed:** Question text sits left, a thin plus sits right; the open item uses a cross. Answer text appears in a matching full-width panel beneath, with a narrow black separator. Rows have 8px gaps.

### Footer link

**Use:** Secondary support, account, corporate and legal navigation.

**CSS:** `color: rgba(255,255,255,0.7); text-decoration: underline`

**Text style:** `utility-link` — Netflix Sans 400 · 14px/1.5

**Observed:** Underlined links form four quiet columns beneath a contact line. A language selector and low-contrast security notice finish the page; there is no oversized closing logo.

## Imagery and graphics

### Immersive mosaic

**Use:** Full-bleed opening backdrop.

**Observed:** A dense wall of rectangular entertainment artwork is tilted diagonally, with black seams, varied portrait and landscape compositions, faces, dramatic scenes and saturated local colors. It fills the opening behind relatively little text, but heavy dark shading keeps it secondary.

**Transfer:** Create a wall of real product outcomes, customer work or use-case photography. Without an extensive image library, art-direct several distinct close-ups into a repeated but varied mosaic; avoid a solitary floating interface window.

**Build:** Place multiple rows of image rectangles with narrow black gutters inside an oversized clipped wrapper. Rotate the whole wall clockwise by about 12deg as a starting point, enlarge it to cover all corners, and layer the Cinematic scrim above it. Add darker top shading behind navigation. Keep the images identifiable but much dimmer than the white headline.

### Luminous horizon

**Use:** Signature threshold between the immersive opening and black content.

**Observed:** A shallow convex arc rises at the center, with a thin red and magenta rim and a soft navy-blue light immediately below. Its edges extend beyond both sides of the viewport.

**Transfer:** Retain this luminous threshold even when the opening uses product photographs rather than a media collage.

**Build:** Clip a 1872px-wide, 100px-high black element inside a 1440px-wide wrapper. Give its top corners elliptical radii of 50% 100% and a 4px top edge. Layer a rim gradient from rgba(33,13,22,1) through rgba(184,40,105,1), #e50914, then back symmetrically. Add radial-gradient(50% 500% at 50% -420%, rgba(64,97,231,0.4) 80%, rgba(0,0,0,0.1) 100%) inside the curve. Match the soft glow; exact intermediate stops are not essential.

### Portrait proof artwork

**Use:** Ranked media shelves.

**Observed:** Vivid portrait compositions are shown without the opening's global scrim, cropped to 185×259px with 8px corners. They combine large subjects and expressive title graphics, backed by pure black with no surrounding card chrome.

**Transfer:** Use strong vertical photographs, designed project covers or editorial use-case art. A minimum equivalent is a high-contrast subject crop with one restrained title treatment inside the image.

### Small illustrative objects

**Use:** Offer strip and benefit-card accents.

**Observed:** The offer has a small glowing, dimensional popcorn object outside its left edge. Benefit illustrations occupy 72px SVG boxes toward the lower-right corner; they are subordinate to the card text.

**Transfer:** Use compact dimensional objects that explain the benefit rather than repeating the product logo. A simple layered SVG with rounded filled shapes and a localized highlight is sufficient.

**Build:** Compose a recognizable object from a few solid SVG silhouettes and inset gradient faces. Fit benefit art within 72×72px; use one pale highlight and dark shaded edges, with a localized low-opacity glow rather than a card-wide shadow.

### Icons

**Observed:** Main conversion controls use 24×24px white chevrons. Accordion controls use thin white plus and cross marks at the far right. Larger benefit objects are filled gradient illustrations rather than outline interface icons.

**Transfer:** Keep directional controls simple and monochrome; reserve shaded, colorful shapes for the illustrative benefit layer.

## Section recipes

How recurring sections are built.

### First screen: Cinematic conversion opening

**Observed:** Back to front: Immersive mosaic, Cinematic scrim and top shading, Header navigation, then a centered conversion cluster. The headline spans a 588px column in two lines using display, followed by a 20px reassurance line after 16px, then a 16px form prompt after 32px. The Email field and Primary button sit side by side after 16px, separated by 8px. The cluster sits above the visual midpoint with ample imagery around it. At 900px high, the complete headline, reassurance, prompt and form are visible, followed by the Luminous horizon beginning near the lower portion; the offer strip starts at the bottom edge, while shelves and benefits remain below the fold.

**Transfer:** Use one broad outcome promise over an abundant product-world mosaic. When dedicated media is unavailable, repeat varied detail photographs or authored outcome covers behind the same dark scrim. A narrower informational page can replace the input with one main action while retaining the centered promise and luminous threshold.

**Avoid:** Do not turn the opening into a bright image gallery with unreadable overlaid copy, or split it into equal text and image columns.

**Text style:** `display` — Netflix Sans 700 · 56px/1.25

### Inset value strip

**Observed:** Offer strip sits across most of the content width, with an illustrative object occupying a separate 100px area to its left. Title and one-line support sit together; Secondary button anchors the right. The panel is 78px high at desktop and separated from the next major block by 64px.

**Transfer:** Use a concise alternative entry point, new offer or useful reassurance; preserve its subordinate scale.

### Ranked proof shelf

**Observed:** A left-aligned 24px heading introduces portrait Ranked media tiles. Five tiles are visible across each of two rows, with large outlined ranks crossing the lower-left corners. Black gutters keep the shelf visually separate from subsequent cards.

**Transfer:** Curate a short ranked or sequenced set of compelling examples. The shelf device matters more than reproducing the same number of items.

### Practical benefit grid

**Observed:** A left-aligned heading precedes a four-column Benefit card grid by 16px. The cards share Midnight benefit panel, medium 24px titles and muted 16px body text with a 16px offset. Leave the lower area open for small illustrative objects.

**Transfer:** Explain distinct practical outcomes rather than splitting one claim into several near-identical cards.

### Broad objection handling

**Observed:** A modest 24px heading precedes Question accordion rows by 16px. Each control spans the content width; regular 24px text carries both question and answer. The expanded answer remains a flat charcoal slab.

**Transfer:** Turn the real barriers to purchase into direct questions with plain answers, allowing one answer to demonstrate the expanded state.

### Conversion reprise and utility ending

**Observed:** After a 64px interval, a centered form prompt and the same Email field plus Primary button return without another giant headline or image. This version expands to 783px. A further 64px interval leads into a muted contact line, four columns of Footer links, a compact language selector and a faint final notice; 96px of black padding closes the page.

**Transfer:** Repeat the same small first step after objections, then end with useful service navigation and restrained legal reassurance. Keep the footer visually quieter than the conversion form.

**Text style:** `form-prompt` — Netflix Sans 400 · 16px/1.5

## Page flow

**Storyline:** Immersive promise → low-friction offer → visual breadth proof → practical benefits → objection handling → repeated first step → utility ending.

### Convert a new visitor into a first-step signup while showing both emotional appeal and practical value

1. **Promise** — Dark image wall, centered bold headline, price reassurance and immediate single-field action.
2. **Offer** — A compact gradient strip introduces an accessible entry point with a secondary action.
3. **Visual proof** — Ranked portrait shelves demonstrate breadth through actual examples.
4. **Benefits** — Four midnight-gradient cards describe concrete usage outcomes.
5. **Objection handling** — Wide accordion questions answer cost, usage and commitment concerns.
6. **Closing call** — The original email prompt and red action return on black.
7. **Service navigation** — Muted contact details, four link columns, language control and a fine-print ending.

**Transfer:** Adapt this as emotional immersion followed by increasingly practical reassurance. Keep the luminous divider, ranked visual proof and repeated conversion device while choosing the sequence and content that fit the new product.

## Writing

Direct, familiar and benefit-led, with the confidence of a widely useful service. Emotional breadth is paired with practical reassurance rather than elaborate brand storytelling.

**Do not copy:** Do not reuse Netflix names, logos, entertainment artwork, program titles, prices, phone numbers, service claims or legal wording as claims for another product. Examples illustrate voice and structure only.

- **Addressing the reader:** Speak directly to the reader using you and your, with imperatives for actions. Name the product when explaining what it is; otherwise keep attention on what the reader can do.
- **Rhythm:** Short headline phrases, short reassurance statements and one-sentence benefit descriptions. The main promise can run across two lines; questions sound like things a person would actually ask.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Lead with breadth and the core desirable outcome rather than a technical category explanation. | 6–10 words | “Unlimited movies, TV shows, and more” |
| Reassurance | Pair a concrete starting commitment with a brief reduction of perceived risk. | Two short statements | “Starts at $8.99. Cancel anytime.” |
| Conversion prompt | A short readiness question followed by an explicit instruction and explanation of the next step. | One question plus one sentence | “Ready to watch? Enter your email to create or restart your membership.” |
| Benefit heading | An action or outcome in everyday language. | 2–8 words | “Enjoy on your TV”<br>“Download your shows to watch offline” |
| Objection | Use direct first-person questions about price, access or commitment. | 3–7 words | “How much does [Brand] cost?”<br>“How do I cancel?” |
| Action | A familiar verb phrase that states the next step without theatrical persuasion. | 2 words | “Get Started”<br>“Learn More” |

**Words and phrasing to use:** your; enjoy; ready to; anytime; everywhere; create; start

**Avoid:** revolutionary ecosystem; synergy; industry-leading solution; unlock unprecedented potential; technical acronyms in benefit headings

**Rules:**

- Put the user's practical result in the heading and the scope or mechanics in the supporting sentence.
- State price and cancellation terms plainly when they are relevant and verified.
- Use the same action label for the same next step at the opening and ending.
- Answer objections directly before expanding into detail; do not disguise them as promotional slogans.

## Do's and Don'ts

### Do

- Keep the opening headline at 56px/1.25 and weight 700 within a narrow centered column.
- Align below-opening headings and footer columns to the same 1144px desktop content area.
- Use 4px corners on red actions and dark form controls.
- Pair each portrait proof tile with a 100px overlapping outlined numeral.
- Keep benefit surfaces dark navy-to-plum with 16px corners and 16px column gaps.
- Use 24px regular text and 24px padding for full-width question controls.
- Repeat the same 56px-high conversion action after objection handling.
- Preserve the luminous 4px curved threshold as a graphic signature.

### Don't

- Do not fill whole sections with conversion red; its power comes from small action areas against black.
- Do not apply negative tracking or an uppercase editorial label system to the normal-tracked sans hierarchy.
- Do not turn every control into a pill; control corners remain 4px.
- Do not wrap portrait examples in bordered caption-heavy white cards; the artwork itself is the tile.
- Do not add broad gray drop shadows to benefit cards; their depth comes from the dark gradient.
- Do not make the footer another high-contrast promotional section; use muted underlined 14px links.
- Do not shrink question text to body size to make the accordion denser; preserve the 24px reading scale.
- Do not replace the final single-field step with a large multi-field sales form.

## Motion and responsive

### Motion

**Observed:**

- Media tiles declare transform 0.2s ease-in-out and hover scale(1.05).
- Field labels declare top, font-size and line-height transitions of 250ms with cubic-bezier(0.32,0.94,0.6,1).
- Buttons declare background-color and border-color transitions; accordion background, icon transform and panel transitions use local duration and easing variables.

**Transfer:**

- Use the small shelf zoom to reinforce that the artwork is clickable without moving the grid.
- Keep the conversion cluster spatially stable while labels float and accordion answers expand.

**Unknown:**

- Resolved button and accordion transition timings are unknown.
- No hero movement or autonomous shelf animation is established.

### Responsive

**Observed:**

- The desktop composition is defined at 1440×900px. Source styles include width breakpoints at 600px, 960px, 1280px and 1920px among others; their exact role assignments are not established.

**Transfer:**

- For narrow layouts, retain a full-width dark mosaic and luminous curve, let the conversion controls stack, and preserve the chevron action.
- Reduce benefit columns and keep portrait shelves horizontally scrollable rather than compressing the artwork into tiny thumbnails.
- Reduce side insets while retaining common left edges for questions and utility links.

**Unknown:**

- Mobile type sizes, exact column transitions and mobile header behavior are not established; the narrow-layout transfers are design guidance, not measured variants.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
