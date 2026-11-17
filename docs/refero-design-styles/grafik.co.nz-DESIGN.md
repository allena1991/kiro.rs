# Grafik — compressed type, expansive work

## Overview

A utilitarian portfolio style with a theatrical streak: compressed uppercase display lettering crosses oversized photography, while small grotesk text behaves like exhibition labels. Warm grey, black and white dominate, punctuated by fierce orange and a small violet invitation to play. It suits image-led products and independent creative businesses, combining dense editorial details with expansive, irregular media arrangements.

### Essentials

- The opening reads like a poster laid over a contact sheet: a half-width, tall photographic panel on warm grey, crossed by centered orange uppercase type at 108px/0.75.
- Two radically different type scales do the work: extremely condensed 108px display lettering and 15px/1.25 grotesk descriptions, with normal tracking rather than fashionable tight spacing.
- Controls are words, not capsules: a 43px black navigation strip, white uppercase 15px labels and plain contact links; the exceptional circular control is a 60px violet drawing trigger.
- Colour belongs to the work and the bookends: the long body stays #dad9d5 with black and white media backings, orange appears in the opening lettering and a full 720px closing field, and violet stays a small persistent accent.
- Proof is an uneven exhibition, not a card deck: two 558px media columns with 12px gutters mix tablet presentations and tall photography beside a small editorial text rail.
- Keep a human interruption in the system: include a playful drawing/remixing affordance and a monumental conversational closing line at 66px/0.75; for a product without rich media, stage a real use photograph and a simple interactive mark-making canvas.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff4f00` | `--color-orange` | text, background, action | Opening display text, full closing field and interactive text feedback. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Play violet | `#6320ee` | `--color-violet` | action, accent | Small circular creative-tool launcher and text selection, not an additional section background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background | Primary text, navigation and device-presentation backing; also the immersive detail canvas. |
| Warm grey | `#dad9d5` | `--color-canvas` | background | Default marketing canvas and the negative space between media. |
| White | `#ffffff` | `--color-white` | text, surface | Navigation text, reverse text and flat editorial or media panels. |

## Typography

- **Die Grotesk A** — Descriptions, labels, navigation and editorial lists. Direct neo-grotesk with regular and medium cuts; compact, unembellished and readable at small sizes. OpenType features: "calt", "dlig", "liga", "ss03". If unavailable, use **Inter**. Use regular for prose and medium for labels; preserve the compact 15px setting. Font stack: "Die Grotesk A", "Inter", Arial, sans-serif.
- **Founders Grotesk X Condensed** — Opening poster lettering and conversational closing display. Very narrow, heavy grotesk capitals with tightly stacked lines. OpenType features: "calt", "dlig", "liga", "ss03". If unavailable, use **Barlow Condensed**. Use 700 and tune horizontal compression to retain the extremely narrow silhouette. Font stack: "Founders Grotesk X Condensed", "Barlow Condensed", Impact, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Founders Grotesk X Condensed | 700 | 108px | 0.75 | normal, uppercase | Centered poster headline over the opening photograph. |
| closing-display | Founders Grotesk X Condensed | 700 | 66px | 0.75 | normal, uppercase | Left-aligned conversational statement within the orange close. |
| body | Die Grotesk A | 400 | 15px | 1.25 | normal | Compact descriptions, captions and supporting prose in the regular cut. |
| label | Die Grotesk A | 500 | 15px | 1.25 | normal, uppercase | Menu control, project titles and compact collection headings in the medium cut. |
| heading | Die Grotesk A | 500 | 15px | 1.25 | normal | Sentence-case editorial headings and metadata labels in the medium cut. |
| link | Die Grotesk A | 400 | 15px | 1.25 | normal | Contact, press and external project links in the regular cut. |

**Notes:**

- Display lines are unusually compressed vertically; keep their 0.75 line height while leaving ordinary text at 1.25.
- Small headings gain hierarchy from medium weight, uppercase or placement, not from a larger size. Prose retains regular-cut visual weight.
- The opening mixes bilingual lines into one centered poster composition rather than a primary headline with a smaller translation.

## Layout

**Density:** Dense editorial text against expansive media and long pauses between projects.

### Spacing

**Spacing system:**

- **gutter** 12px, horizontal — Outer margins, column gutters and panel insets.
- **half-gutter** 6px, vertical — Tight prose and metadata rhythm; combine into 12px full gutters.

| Value | Use |
| --- | --- |
| 6px | Tight heading-to-copy and paragraph gaps in editorial and detail sections. |
| 12px | Media grid gaps, page edges and standard paragraph separation. |
| 24px | Immersive detail-page edges and larger control offsets. |
| 48px | Expanded inset within the detail composition. |
| 90px | Space after each immersive detail media panel. |
| 180px | Project chapter breathing room and the final detail-page tail. |

### Containers and grids

- **page-grid**: 12 columns · gap 12px · side padding 12px. Fluid full-width marketing grid; avoid a narrow centered site wrapper.
- **work-stage**: max width 1128px · 2 columns · gap 12px. At desktop the media stage occupies about four fifths of the page; each standard media column is 558px, with an editorial rail alongside.
- **description**: max width 400px · side padding 12px. Narrow paragraphs accompanying work; rail can be narrower within the overall composition.
- **closing-line**: max width 940px. Conversational closing display leaves the right third of the orange field open.
- **collection-grid** (only for participatory collections): 6 columns · gap 12px · side padding 12px. Uniform portrait tiles, 226px by 283px at desktop, without card captions beneath.
- **detail-stage** (only for immersive case studies): gap 12px · side padding 24px. Black full-width presentation with a 214px introductory text column and bottom-aligned metadata.

## Corner radius

| Element | Radius |
| --- | --- |
| drawing-trigger | 50% |

## Surfaces and depth

### Surfaces

#### Warm grey canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #dad9d5; color: #000000`

**Observed:** A flat, slightly warm grey rather than paper grain or a gradient.

**Transfer:** Let unoccupied grid cells reveal this canvas.

#### White editorial panel · level 1

**Use:** Prose alongside work and the manifesto spread.

**CSS:** `background: #ffffff; padding: 12px`

**Observed:** Square, flat and borderless; sits against the grey rather than floating above it.

**Transfer:** Use for editorial contrast, not for every small item.

#### Orange closing field · level 0

**Use:** Signature conversational ending.

**CSS:** `background: #ff4f00; color: #000000; min-height: 720px`

**Observed:** A full-width solid orange field, with no texture, gradient or elevation.

**Transfer:** Reserve the major brand-colour fill for a memorable human sign-off.

#### Black presentation canvas · level 0

**Only for:** immersive case studies

**Use:** Large sequential media studies.

**CSS:** `background: #000000; color: #ffffff; padding: 0 24px`

**Observed:** Small reverse text remains around oversized tablet and phone presentations.

**Transfer:** Keep the surrounding interface subdued so each demonstration owns its colour.

## Components

### Navigation strip

**Use:** Persistent orientation on ordinary marketing pages.

**CSS:** `position: fixed; top: 0px; left: 0px; width: 100%; background: #000000; color: #ffffff; padding: 12px; z-index: 150`

**Text style:** `label` — Die Grotesk A 500 · 15px/1.25 · uppercase

**Observed:** A slim 43px bar with identity at left, menu near the center-left grid line and a small audio control at the far right; not a conventional row of section links.

**Transfer:** Keep the three-point distribution even when the identity changes.

### Menu text control

**Use:** Open navigation without introducing a button-shaped object.

**CSS:** `color: #ffffff; background: transparent; font-size: 15px; line-height: 1.25; text-transform: uppercase; transition: color 0.2s`

**Text style:** `label` — Die Grotesk A 500 · 15px/1.25 · uppercase

**Observed:** Plain uppercase text in the black strip, with no enclosing capsule.

**States:** Declared: hover color #ff4f00.

### Contact link

**Use:** Direct contact and editorial resource links.

**CSS:** `color: #000000; font-size: 15px; line-height: 1.25; text-decoration: underline`

**Text style:** `link` — Die Grotesk A 400 · 15px/1.25

**Observed:** Text-only links sit in short stacked lists; the closing contact group is placed alongside the small statement rather than in a button row.

**States:** Declared: hover text-decoration none.

### Drawing trigger

**Use:** Persistent invitation to participate and play.

**CSS:** `position: fixed; left: 24px; bottom: 24px; width: 60px; height: 60px; border-radius: 50%; background: #6320ee; color: #ffffff; z-index: 150; transition: background 0.3s, color 0.3s`

**Observed:** A centered white pencil glyph is the only content; the control remains visible through the long scroll.

**States:** Declared: hover background #ffffff.

**Transfer:** Connect the launcher to a lightweight sketch, stamp or remix tool with an accessible name.

### Media mosaic

**Use:** Main proof component for project or product chapters.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); gap: 12px; position: relative`

**Observed:** Two equal media columns occupy six grid tracks each; selected images span both. Tall portraits coexist with landscape tablet frames and smaller paired images. Text lives in the rail, not below every image.

**Transfer:** Mix actual outputs, close details and a photographed use case rather than repeating one thumbnail.

### Editorial rail

**Use:** Explain a media chapter without competing with it.

**CSS:** `padding: 12px 12px 0px`

**Text style:** `body` — Die Grotesk A 400 · 15px/1.25

**Observed:** Uppercase underlined title, two compact paragraphs, then disciplines and year. The rail is white against the grey media field and is much smaller than the imagery.

**Transfer:** Use context, a concrete design or product decision and the resulting benefit.

### Conversational close

**Use:** A recognizable human final impression on marketing, profile and collection pages.

**CSS:** `padding: 12px; min-height: 720px; background: #ff4f00; color: #000000; display: flex; flex-direction: column`

**Text style:** `closing-display` — Founders Grotesk X Condensed 700 · 66px/0.75 · uppercase

**Observed:** A large uppercase conversational report sits at the top, followed by a long pause and a small statement/contact pair around the middle. A tiny rights line sits near the lower edge.

**Transfer:** Write a fresh present-tense observation with a human voice, not a sales slogan.

### External detail link

**Only for:** immersive case studies

**Use:** Visit the presented product.

**CSS:** `color: #ffffff; text-decoration: underline; transition: color 0.2s, text-decoration-color 0.2s`

**Text style:** `link` — Die Grotesk A 400 · 15px/1.25

**Observed:** A single understated text action appears with the bottom metadata, not as a prominent conversion button.

**States:** Declared: hover color #ff4f00 and text-decoration none; focus-visible outline 2px solid #ff4f00, outline-offset 2px, border-radius 1px and text-decoration none; active color #ff4f00, underline #ff4f00 and opacity 0.75.

## Imagery and graphics

### Poster photograph

**Use:** Main opening object beneath the display lettering.

**Observed:** A tightly framed monochrome portrait on a deep black photographic background fills a tall panel on the left half; the right half remains grey. Orange lettering bridges both halves.

**Transfer:** Use a close, high-contrast photograph of a person, object or genuine product use. A simple carefully lit monochrome object photograph is the minimum equivalent.

### Framed digital work

**Use:** Repeated proof throughout media chapters.

**Observed:** Real interfaces sit inside dark, rounded tablet or phone hardware, centered on rectangular black or white backings. These alternate with unframed fashion, architecture, art and object photography; media takes far more area than its supporting prose.

**Transfer:** Present real product screens in restrained dark hardware and pair them with a context photograph; keep hardware rounding inside the image, not on the outer tile.

### Remixed material drawings

**Only for:** participatory collections and the creative tool

**Use:** Playful user-made works in a dense portrait grid.

**Observed:** Extruded, ridged tubes and repeated stamps form faces and abstract doodles in silver, black, ochre, terracotta and cyan; small googly eyes lend a deliberately mischievous tone. Backings are pale neutral and tiles have no decorative frames.

**Transfer:** Offer a limited set of tactile stamps or brush marks that produce varied results while keeping the surrounding gallery neutral.

**Build:** Use an SVG drawing canvas on warm grey. Form thick looping paths from repeated small elliptical stamps, alternate light and dark ridges for relief, and layer white circles with smaller black pupils. Supply a few warm, cool and metallic material presets; a flat stamped approximation with visible repetition is sufficient.

### Backlit portrait

**Only for:** profile and manifesto spreads

**Use:** Large image beside a narrow personal argument.

**Observed:** A frontal torso portrait fills about two thirds of the spread, face almost silhouetted against a beige-grey wall, warm orange light on the pale shirt and rim of the head. The image is rectangular within a white spread.

**Transfer:** Photograph the maker or a real participant with restrained orange side or rim light; preserve the intimate, imperfect character rather than using corporate headshots.

### Icons

**Observed:** Small white filled SVG utility marks: 22px audio control in the header, 28px pencil in the circular launcher. Immersive detail views use a thin white diagonal cross at the upper right.

**Transfer:** Keep iconography limited to utility controls; use a simple filled pencil and audio mark, and a two-line cross for close rather than a full feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Poster opening

**Observed:** The Warm grey canvas supports a 43px Navigation strip. Below a 12px gap, a tall photograph fills the left half and continues beyond the first 900px; the right half is open grey. Centered orange display text crosses the seam, spanning roughly three quarters of the width in four tightly stacked bilingual lines at 108px/0.75. The Drawing trigger sits at lower left. Within the first 900px the identity, menu, audio control, photograph and full poster statement are visible; a small image caption and the first work chapter fall below. There is no supporting paragraph or large CTA button in this opening.

**Transfer:** Use a short identity-and-offer statement, split into comparably forceful lines over a half-width photograph; a second language or parallel formulation can supply the second voice. If no campaign image exists, use one strong monochrome object or use-case photo. Collections open with a small label and explanatory sentence; profiles open with prose beside a portrait; immersive studies open with small reverse text over black.

**Avoid:** Do not replace the seam-crossing poster with a standard left-copy/right-illustration hero or add a pair of pill CTAs.

**Text style:** `display` — Founders Grotesk X Condensed 700 · 108px/0.75 · uppercase

### Image-led chapter

**Observed:** Media mosaic on Warm grey canvas occupies about four fifths of the width, with Editorial rail at the right. Mixed-height media is separated by 12px, with occasional full-width landscape images. Chapters have 180px bottom breathing room and visible strong black horizontal separations.

**Transfer:** Use each chapter to substantiate one promise through a small set of complementary views, while the rail explains the decision in ordinary language.

**Text style:** `body` — Die Grotesk A 400 · 15px/1.25

### Human closing field

**Observed:** Conversational close fills a 720px Orange closing field. The 66px/0.75 line is left aligned to a 12px edge and constrained to 940px. Small statement and Contact link groups form two columns below, with broad unused orange space and a rights line at the foot.

**Transfer:** Retain the dramatic colour change and personal present-tense voice wherever the closing device appears; use a true observation related to the people behind the product.

**Text style:** `closing-display` — Founders Grotesk X Condensed 700 · 66px/0.75 · uppercase

### Immersive study

**Only for:** immersive case studies

**Observed:** Black presentation canvas holds a small 214px-wide introduction near upper left, an upper-right cross, and metadata labels along the viewport bottom. Huge centered tablet images scroll behind this persistent text, separated by 90px. The ending stays black: one study finishes on a tablet view, another on a narrower 924px-wide strip of phones, followed by 180px of space; neither switches to the orange marketing close.

**Transfer:** Keep scope, implementation and outcome available while the product demonstration unfolds. End with a useful alternate-device view rather than inventing an unrelated footer.

**Text style:** `heading` — Die Grotesk A 500 · 15px/1.25

### Manifesto spread and index

**Only for:** profile pages

**Observed:** White editorial panel pairs a roughly 340px prose column with a large Backlit portrait to the right. Below, compact profile, client, press and recognition columns sit directly on grey; their headings stay at 15px, the same scale as prose. The orange close follows the lists.

**Transfer:** Replace biography and client names with an authentic point of view, credible associations and linked proof; keep the multi-column small-type index rather than making credential cards.

**Text style:** `heading` — Die Grotesk A 500 · 15px/1.25

### Participatory collection

**Only for:** participatory collections

**Observed:** A small uppercase heading and one short explanatory line precede a 90px pause and a six-column collection grid. Portrait image buttons fill the width in 12px gutters. The collection ends directly in the orange conversational close.

**Transfer:** Use this for user creations or remixes, with opening instructions that invite viewing and participation without a long onboarding explanation.

**Text style:** `label` — Die Grotesk A 500 · 15px/1.25 · uppercase

## Page flow

**Storyline:** visual identity → concrete work and explanatory context → deeper proof or personal perspective → human sign-off

### Image-led marketing landing page

1. **promise** — Half-width photographic object and seam-crossing bilingual poster.
2. **proof chapters** — Repeated uneven media mosaics with small editorial rails explaining context, decisions and scope.
3. **human close** — Orange conversational report, contact and small statement.

**Transfer:** Choose enough chapters to prove the offer; the media variety and human bookend matter more than the number of projects.

### Participatory collection

1. **orientation** — Small uppercase title and a brief invitation to open or remix.
2. **community proof** — Six-column grid of tactile user drawings.
3. **human close** — Shared orange conversational ending.

**Transfer:** Keep instructions minimal and make the work itself the main invitation.

### Research-oriented immersive case study

1. **context** — Small reverse introduction and attribution on black.
2. **demonstration** — Large tablet presentations showing the work from opening through detail.
3. **outcome** — Persistent deliverables, technology and impact information; final tablet image and black tail.

**Transfer:** Tell a complex product story through actual views while retaining succinct context.

### Identity and directory immersive case study

1. **context** — Small reverse introduction and bottom scope metadata.
2. **demonstration** — Tablet views progress through identity, content, directory and interactions.
3. **cross-device proof** — A narrower row of phone presentations closes on black, with the visit link still available.

**Transfer:** Show multiple meaningful states and end with the product working at another format.

### Personal perspective and credibility

1. **point of view** — Narrow manifesto prose beside a large backlit portrait on white.
2. **credibility** — Small-type multi-column profile, affiliations, press links and recognition on grey.
3. **human close** — Orange personal report and contact.

**Transfer:** Lead with a specific belief and support it with compact, verifiable references.

## Writing

Independent, thoughtful and sometimes mischievous. The voice explains a creative decision with confidence and concrete imagery, rather than presenting a list of superlatives.

**Do not copy:** Do not reuse the studio name, client identities, project claims, contact details, local cultural statement, proprietary imagery or the named-recipient weather monologue. Replace all with truthful content and original assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Personal first person for the maker's beliefs; third person for project context; occasional direct second person in playful instructions.
- **Rhythm:** Compact paragraphs alternate with short, emphatic sentences. Titles are plain names or direct descriptions; the closing statement is deliberately conversational and longer than a slogan.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| opening statement | Identity, discipline and place; a parallel second-language expression gives it a poster rhythm. | Short clauses across several display lines. | “[Brand], Design & Development Wellington, New Zealand” |
| project explanation | Describe the problem, then connect one design decision to the experience it creates. | Two compact paragraphs. | “A yearlong study is a dense thing to hand a city. The site turns it into one continuous scroll, the whole argument unfolding section by section as you move.” |
| invitation | Plain verbs with a light, slightly subversive twist. | One or two sentences. | “Drawings made by people who came here for something else. Open one to view it, or remix it to ruin it.” |
| action | A direct verb or destination, with no promise inflation. | One or two words. | “Visit”<br>“Menu” |
| point of view | A clear belief expressed through a concrete contrast. | One to three sentences. | “I believe the website is the brand, not a container for it. It’s the one that’s alive, and everything else is just paper.” |

**Words and phrasing to use:** built; drawn; work; the thing itself; identity; rhythm; a little mischievous; form follows function

**Avoid:** revolutionary platform; seamless solutions; unlock your potential; best-in-class; enterprise-grade innovation

**Rules:**

- Explain why a decision was made, not just which service was delivered.
- Use a concrete metaphor tied to the experience, not an abstract brand adjective.
- Keep technical scope separate from the narrative paragraph.
- Let the personal ending sound like a person speaking now rather than a conversion headline.

## Do's and Don'ts

### Do

- Use 108px condensed uppercase lettering with 0.75 line height for the opening poster.
- Keep ordinary headings and prose at 15px/1.25; distinguish them through cut, casing and position.
- Maintain 12px media gutters and page edges.
- Let tall photographs interrupt the landscape screen rhythm.
- Use 180px chapter pauses instead of adding decorative card padding.
- Make the orange closing field at least 720px tall with a 940px-wide display line.
- Keep the violet launcher a small 60px circle with a centered utility glyph.
- Use genuine product views with neutral hardware backings.

### Don't

- Do not add rounded outer media cards; the rectangular tile and the rounded device inside it are different layers.
- Do not turn every 15px label into a 32px feature heading.
- Do not apply orange to every proof section; most of the long body belongs to grey and imagery.
- Do not introduce drop shadows or glass panels into the flat editorial canvas.
- Do not expand the tiny utility icons into a decorative feature-icon system.
- Do not replace the 12px gutter with a roomy 32px card-grid gap.
- Do not make the contact area a large filled sales button.
- Do not use the black immersive detail theme as the default marketing canvas.

## Motion and responsive

### Motion

**Observed:**

- Navigation colour transitions are declared at 0.2s; the drawing launcher transitions background and colour at 0.3s.
- External detail links declare 0.2s colour and text-decoration-colour transitions.
- The closing field uses a vertical reveal; the opening contains changing media and blinking headline lines.

**Transfer:**

- Keep interface feedback colour-based and brief; reserve larger movement for the media presentation and closing reveal.
- Preserve a stable text hierarchy while the opening media changes.

**Unknown:**

- Exact opening slideshow, blink and reveal timings and easing assignments are not established.

### Responsive

**Observed:**

- The desktop composition uses a fluid 12-column grid and 12px gutters.

**Transfer:**

- On narrow screens retain the photograph/type overlap, reduce display size to preserve whole phrases, and place the editorial rail after its media rather than shrinking prose below 15px.
- Reduce the participatory grid column count while retaining portrait tiles and 12px gutters.
- Keep the drawing affordance accessible without covering the primary content.

**Unknown:**

- Mobile layouts, breakpoints and viewport-relative type formulas are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
