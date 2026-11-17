# Workflow — a designer’s white canvas

## Overview

A bright, almost gallery-like software style that pairs delicate literary serif headings with small, practical sans-serif text. White and pale gray carry the page, with color largely reserved for the work displayed inside product interfaces. Spacious compositions, softly elevated interface windows and human portraits make capable software feel approachable rather than technical. It suits creative tools and considered productivity products, with compact information inside very open page layouts.

### Essentials

- Headlines behave like modest editorial titles, not billboards: Crimson Pro 300 at 32px/1 with normal tracking, including the main promise and closing invitation.
- The opening leaves room to think: a centered promise around 296px down, 12px to supporting copy, 24px to one pale action, then 104px to a tabbed product stage approximately 1092px wide.
- Conversion is understated: default actions are #f6f6f6 rounded rectangles with 8px corners, 8px 16px padding and 14px Inter text; dark actions belong to paid-plan decisions.
- The page is a white exhibition wall: #ffffff dominates, #f6f6f6 backs capability demonstrations, and chromatic accents occupy small interface details rather than marketing bands. Richer color belongs inside the demonstrated work.
- Real work is the hero object: include a light interface window with an 8px radius, a faint 1px edge and diffuse shadow, plus enlarged, selectively faded UI fragments on square pale-gray tiles. If no interface is available, construct a credible task-and-output scene instead.
- Human proof interrupts the interface story: include a small circular portrait over a centered 26px/1 light-serif quotation, with 14px muted attribution 24px below; repeated proof uses white 12px-radius cards and 60px portraits.
- The closing invitation stays small while its stage stays expansive: a 32px serif line and pale button separated by 40px, followed by substantial white breathing room and a thin-rule, three-column utility footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#1a1a1a` | `--color-ink` | text, action | Headings, titles, active tabs and dark plan actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Tile gray | `#f6f6f6` | `--color-soft` | surface, action, text | Capability tile backing and default buttons; also reversed text on dark actions. |
| Secondary gray | `#6a6a6a` | `--color-muted` | text | Support lines and attributions; visible result of charcoal at 65% opacity over white. |
| Tab baseline | `#bababa` | `--color-tab-rule` | border | Visible charcoal-at-30% baseline beneath demonstration tabs. |
| Section hairline | `#e4e4e4` | `--color-rule` | border | Visible charcoal-at-12% separators over white for the footer, FAQs and update media. |
| Window edge | `#e8e8e8` | `--color-window-edge` | border | Visible charcoal-at-10% edge of the main demonstration window. |
| Pressed gray | `#ececec` | `--color-hover` | action, surface | Declared button hover fill; secondary gray planes inside product scenes. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Page canvas, interface windows and elevated proof cards. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Issue ink | `#923d56` | `--color-issue-ink` | text, accent | Muted burgundy issue text and outlined status symbols. |
| product demonstrations | Fine interior rule | `#f1f1f1` | `--color-fine-rule` | border | Visible charcoal-at-6% dividers inside staged interfaces. |
| product demonstrations | Interface canvas | `#f3f3f3` | `--color-ui-canvas` | surface | Neutral working canvas within the light demonstration window. |
| product demonstrations | Issue wash | `#fdf5f6` | `--color-issue-wash` | surface | Very pale rose backing for an issue callout. |

## Typography

- **Crimson Pro** — Main promise, section titles, quotations and editorial subheads. Fine, literary serif with a light weight and compact line spacing. Font stack: "Crimson Pro", "Times New Roman", serif.
- **Inter** — Body, navigation, actions, card labels and interface text. Small neutral sans-serif, predominantly regular weight; practical rather than decorative. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | Crimson Pro | 300 | 32px | 1 | normal | Main promise, section headings and closing invitation; centered by default. |
| quote | Crimson Pro | 300 | 26px | 1 | normal | Standalone customer quotation and the testimonial beside a paid plan. |
| tile-title | Inter | 400 | 15px | 22px | normal | Compact capability title at the top-left of a demonstration tile. |
| tile-body | Inter | 400 | 15px | 1.4 | normal | Capability explanation immediately below the tile title. |
| body | Inter | 400 | 14px | 1.5 | normal | Supporting paragraphs, navigation, actions and attribution. Use muted gray for support and charcoal for decisive text. |
| proof-copy | Inter | 400 | 14px | 1.4 | -0.004em | Short customer remarks and muted attribution inside proof cards. |
| caption | Inter | 400 | 12px | 21px | normal | Small utility footer line; subordinate to navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Crimson Pro | 300 | 32px | 21px | -0.05em | Currency and price, with the smaller billing unit aligned on the baseline. |
| release journals, plan titles and comparison articles | editorial-title | Crimson Pro | 300 | 24px | 1 | normal | Entry or plan title below media, or a compact article heading. |
| comparison articles | comparison-subhead | Crimson Pro | 400 | 24px | 1 | normal | Numbered contrast heading, slightly firmer than the ordinary editorial title. |
| release journals | journal-subhead | Crimson Pro | 200 | 20px | 1.5 | normal | Muted subsection heading inside a longer update. |

**Notes:**

- Do not enlarge the promise relative to section headings: both use the same 32px light-serif recipe. Scale comes from the surrounding space and the product object.
- Keep normal tracking on most text. The tightly tracked price is a scoped exception, not the headline style.
- Use sentence case and restrained weights. Interface artwork may contain expressive display typography, but that is not the marketing type system.

## Layout

**Density:** Airy at page level, compact inside text groups and interface demonstrations.

### Spacing

**Spacing system:**

- **layout step** 8px — Explains the dominant non-fluid layout gaps and padding; retain the 12px heading gap and 60px journal rhythm as explicit exceptions.

| Value | Use |
| --- | --- |
| 8px | Tight action groups and interface-related spacing. |
| 12px | Section title to supporting line. |
| 16px | Capability and proof grid gutters. |
| 24px | Tile and proof-card padding; support-to-action spacing in the opening. |
| 32px | Within capability tiles and between long-form paragraphs. |
| 40px | Closing title-to-action gap; footer padding. |
| 48px | Quote-block and proof-section vertical padding. |
| 60px | Proof-heading to card-grid gap; interval between journal entries. |
| 72px | Section heading group to capability module. |
| 104px | Opening text/action group to demonstration tabs. |
| 144px | Primary interval between marketing sections. |

### Containers and grids

- **marketing stage**: max width 1092px · side padding 16px. Centered main interface, capability modules, logo proof and testimonial grid. At 1440px it leaves approximately 174px of margin on either side.
- **capability grid**: 6 columns · gap 16px. Six underlying tracks: alternate a two-track narrow tile with a four-track wide tile, then reverse the proportions in the next row. Three equal two-track tiles form the compact variant.
- **proof grid**: 3 columns · gap 16px. Equal white cards, approximately 353px wide by 206px high at desktop.
- **quotation**: max width 650px · side padding 16px. Centered portrait and light-serif quotation with restrained line length.
- **decision pair** (only for pricing and FAQ sections): max width 934px · 2 columns · gap 16px · side padding 16px. Equal desktop columns approximately 459px wide: plan beside quotation, or section introduction beside question list.
- **manifesto column** (only for company stories): max width 459px · side padding 16px. Narrow centered body column below full-bleed editorial photography.
- **comparison prose** (only for comparison articles): max width 768px. Single left-aligned reading column below the summary table.
- **journal spread** (only for release journals): max width 1360px · 2 columns · gap 24px · side padding 40px. Equal columns with date at the far left and all media and prose in the right column, approximately 668px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and main window | 8px |
|  | proof cards and floating panels | 12px |
|  | portraits | 50% |
| product demonstrations | issue callouts | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| proof card | `drop-shadow(rgba(0, 0, 0, 0.07) 0px 4px 25px)` | Filter that gently separates white proof cards from the white page. |
| main window | `rgba(0, 0, 0, 0.03) 0px 9px 20px 0px, rgba(0, 0, 0, 0.03) 0px 37px 37px 0px, rgba(0, 0, 0, 0.02) 0px 83px 50px 0px, rgba(0, 0, 0, 0) 0px 147px 59px 0px, rgba(0, 0, 0, 0) 0px 229px 64px 0px` | Diffuse layered elevation under the main product stage. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #1a1a1a`

#### Capability backing · level 0

**Use:** Flat supporting plane behind enlarged interface fragments.

**CSS:** `background: #f6f6f6; border-radius: 0px; overflow: hidden`

**Observed:** Square outer edges; white windows and floating panels carry the rounded corners instead.

**Transfer:** Use a pale neutral plane to group a benefit title with one visible product behavior.

#### Window · level 1

**Use:** Main product demonstration.

**CSS:** `background: #ffffff; border: 1px solid rgba(26, 26, 26, 0.1); border-radius: 8px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.03) 0px 9px 20px 0px, rgba(0, 0, 0, 0.03) 0px 37px 37px 0px, rgba(0, 0, 0, 0.02) 0px 83px 50px 0px, rgba(0, 0, 0, 0) 0px 147px 59px 0px, rgba(0, 0, 0, 0) 0px 229px 64px 0px`

**Observed:** Very light chrome surrounds a large work canvas; the frame recedes behind the content.

**Transfer:** Retain credible toolbar, content and context, rather than turning the window into a decorative browser mockup.

#### Proof elevation · level 1

**Use:** Repeated customer proof.

**CSS:** `background: #ffffff; border-radius: 12px; filter: drop-shadow(rgba(0, 0, 0, 0.07) 0px 4px 25px)`

#### Journal media edge

**Only for:** release journals

**Use:** Flat image or video container.

**CSS:** `border: 1px solid rgba(26, 26, 26, 0.12); position: relative; margin-bottom: 8px`

**Observed:** Square thin-edged media contrasts with rounded marketing windows.

#### Issue annotation

**Only for:** product demonstrations

**Use:** Small contextual warning over a faded output example.

**CSS:** `background: #fdf5f6; color: #923d56; border: 1px solid rgba(206, 104, 120, 0.12); border-radius: 6px`

**Observed:** Rose warning and pale green success annotations remain inside product behavior illustrations.

**Transfer:** Use semantic color only for a meaningful result; leave the surrounding marketing section neutral.

## Components

### Navigation

**Use:** Persistent lightweight site navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 24px 40px; background: #ffffff`

**Text style:** `body` — Inter 400 · 14px/1.5

**Observed:** An 83px fixed white header carries a compact serif wordmark at left, three plain links in the center with 24px gaps, and login plus a pale action at right. No enclosing capsule or bottom rule.

**Transfer:** Use the new identity at compact wordmark scale and keep the center links sparse.

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #f6f6f6; color: #1a1a1a; border-radius: 8px; padding: 8px 16px; height: 40px; column-gap: 8px`

**Text style:** `body` — Inter 400 · 14px/1.5

**Observed:** Content-sized and understated; the opening uses a small right arrow, while closing actions are plain text.

**States:** Declared: hover background-color #ececec and outline 0px; focus-visible 2px solid #1a1a1a outline with 2px offset; active outline 0px.

### Text link

**Use:** Navigation and utility links.

**CSS:** `color: #1a1a1a; position: relative`

**Text style:** `body` — Inter 400 · 14px/1.5

**Observed:** Plain text links without a filled background. In editorial prose, help and installation links can be muted and underlined.

**States:** Declared: hover opacity 0.75 and outline 0px; focus-visible 2px solid #1a1a1a outline with 2px offset; active outline 0px.

### Demo tabs

**Use:** Change the type of work shown on the main product stage.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 16px; border-bottom: 1px solid rgba(26, 26, 26, 0.3); margin-bottom: 24px`

**Text style:** `body` — Inter 400 · 14px/1.5

**Observed:** Five 104px-wide, 48px-high text targets above the window; inactive text is muted, current text charcoal with a short dark underline on the baseline.

**Transfer:** Use a few genuine modes or outputs, not arbitrary feature categories.

### Product window

**Use:** Large tangible proof of the core experience.

**CSS:** `background: #ffffff; border: 1px solid rgba(26, 26, 26, 0.1); border-radius: 8px; display: flex; position: relative; overflow: hidden`

**Observed:** Uses Window elevation, approximately 1092px by 699px at desktop. A slender toolbar sits over a split context-and-work area; natural creative work provides the visual richness.

**Transfer:** Show one complete useful operation with context rather than a collage of unrelated screens.

### Capability tile

**Use:** Explain one behavior through a short title and enlarged product fragment.

**CSS:** `background: #f6f6f6; display: flex; flex-direction: column; align-items: flex-start; row-gap: 32px; padding-top: 24px; padding-left: 24px; overflow: hidden`

**Text style:** `tile-title` — Inter 400 · 15px/22px

**Observed:** Title then muted tile-body text at top-left; media follows and can run into the lower and right edges. Narrow and wide tiles alternate. The equal three-column variant uses 24px padding on every side and 24px internal gaps.

**Transfer:** Crop to a legible interaction, leaving the rest of the interface visually subordinate.

### Testimonial card

**Use:** Dense, repeated human proof without a heavy surface color.

**CSS:** `background: #ffffff; border-radius: 12px; filter: drop-shadow(rgba(0, 0, 0, 0.07) 0px 4px 25px); padding: 24px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 16px`

**Text style:** `proof-copy` — Inter 400 · 14px/1.4 · tracking -0.004em

**Observed:** A centered 60px circular portrait appears above a left-aligned short remark and muted name-and-role line. Text pair uses a 4px gap; cards repeat in three columns.

### Footer

**Use:** Low-key utility ending.

**CSS:** `border-top: 1px solid rgba(26, 26, 26, 0.12); display: flex; flex-direction: column; justify-content: space-between; gap: 40px; padding: 40px`

**Text style:** `body` — Inter 400 · 14px/1.5

**Observed:** 432px-tall desktop footer: compact wordmark at left, three utility columns across the right half with 24px gaps and roughly 199px column widths. Link groups have no oversized labels. A 12px muted copyright line sits at bottom-left.

### Plan button

**Only for:** pricing pages

**Use:** Paid-plan conversion.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #1a1a1a; color: #f6f6f6; border-radius: 8px; padding: 8px 16px; height: 40px`

**Text style:** `body` — Inter 400 · 14px/1.5

**Observed:** Placed below the price, followed by muted risk-reversal text. Trial action uses the same dark construction with a 37px height.

**States:** Declared: hover background-color #ececec and outline 0px; focus-visible 2px solid #1a1a1a outline with 2px offset; active outline 0px.

### FAQ row

**Only for:** pricing and comparison sections

**Use:** Resolve practical objections beside a compact section introduction.

**CSS:** `border-bottom: 1px solid rgba(26, 26, 26, 0.12)`

**Text style:** `body` — Inter 400 · 14px/1.5

**Observed:** Question trigger has 16px vertical padding; charcoal question, muted answer beneath. Pricing uses collapsible rows with an initially open answer; comparison answers are presented as expanded text. Desktop question list is approximately 459px wide.

**States:** Declared: hover not specified; focus-visible on the question trigger is a 2px solid #1a1a1a outline with 2px offset.

### Journal media

**Only for:** release journals

**Use:** Demonstration at the top of an update entry.

**CSS:** `position: relative; border: 1px solid rgba(26, 26, 26, 0.12); margin-bottom: 8px`

**Observed:** A 668px outer frame contains an image or short demonstration video. Moving examples have a small pale circular pause control in the lower-right, inside a 48px action target.

**Transfer:** Keep each entry tied to one real improvement, with image, title and explanatory prose rather than a card summary.

## Imagery and graphics

### Work inside a light interface

**Use:** Required central product scene and recurring capability demonstrations.

**Observed:** Editorial websites, design boards and presentation work sit inside near-white tool chrome with thin dividers. The main window is wide and straight-on, not perspective-rendered. Capability scenes enlarge comment bubbles, share controls or tour panels; less important layers fade almost into the gray backing. Small circular video portraits and cursor labels introduce human activity.

**Transfer:** Use original output relevant to the new product. Without a polished interface, draw a credible toolbar, context sidebar and one useful output with a focused annotation; this is the minimum acceptable product scene.

**Build:** Use a white 8px-radius window on white with a 1px charcoal-at-10% edge and Window shadow. Divide a roughly 50px toolbar from the work area; use a pale neutral canvas and compact context column. For tiles, clip the window into a square #f6f6f6 plane, reduce secondary layers to about 20% opacity and leave the active white panel at full opacity. Keep the main scene about 1092px wide at desktop.

### Human proof portraits

**Use:** Standalone quotations and repeated proof cards.

**Observed:** Small natural-color headshots, circular and about 60px across, isolated on white. They anchor much larger fields of white space rather than becoming a photo wall.

**Transfer:** Use genuine portraits with ordinary natural lighting and simple face-centered crops. Match the modest scale.

### Monochrome customer marks

**Use:** Compact credibility block beneath the main demonstration.

**Observed:** Recognizable wordmarks in desaturated gray, evenly distributed across a wide multi-row field. A small muted trust line sits above.

**Transfer:** Use verified customer or partner marks in a consistent neutral treatment; without suitable marks, use short typeset customer names with the same measured spacing.

### Consolidation diagram

**Only for:** tool-consolidation stories

**Use:** A single conceptual interruption between interface chapters.

**Observed:** One 104px white app tile floats above a horizontal row of gray tool symbols crossed by a thin dark line. The upper tile has 12px corners, a faint outline and soft shadow; the lower row is deliberately subdued.

**Transfer:** Replace the symbols with the new product and the tools or steps it genuinely consolidates. If there are no integrations, use generic labeled process nodes.

**Build:** Center a 104px square with 16px inner padding and the new product symbol. Apply 12px corners, a 1px charcoal-at-12% outline and drop-shadow(rgba(0,0,0,0.06) 0px 4px 10px). Below it, distribute approximately nine 35px monochrome symbols across a 746px line. Run a 1px charcoal line through the centers; lower the symbols’ contrast, keeping the top symbol crisp.

### Archival working photograph

**Only for:** company stories

**Use:** A full-bleed human scene after a compact editorial statement.

**Observed:** Black-and-white documentary image of a designer thinking at a desk, high contrast with visible grain and surrounding working environment. It occupies the full width, approximately 1440px by 813px, with a centered muted credit 16px beneath.

**Transfer:** Choose an authentic image of focused work with an environmental composition and tactile grayscale treatment, followed by a short factual credit.

### Icons

**Observed:** Small restrained outline symbols: common utility icons are 16px with 1px rounded strokes in charcoal or muted gray. Checkmarks mark pricing benefits; comparison tables use 24px check/cross symbols. Portraits provide more personality than icons.

**Transfer:** Choose thin, neutral line icons with round caps and simple geometry. Reserve stronger symbol weight for tiny playback controls, not feature decorations.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and product stage

**Observed:** White canvas behind an 83px Navigation header. The centered text group starts around 296px from the top of a 900px desktop viewport: one restrained 32px light-serif promise, then a muted two-line 14px supporting statement 12px below, then Primary button after 24px. A 104px interval leads to Demo tabs, followed 24px later by the 1092px-wide Product window. Layers run from white page to diffuse window shadow, white tool chrome, pale working canvas and colored work with small human annotations. The first 900px shows the full promise and action, all tabs, toolbar and the upper portion of the work; the window’s lower content continues below the fold.

**Transfer:** Preserve the small promise/large object balance for a new product, using Work inside a light interface when original media is unavailable. Company stories open with just a centered statement and full-width photograph; pricing adds a small category label and benefit matrix; a release journal opens as an asymmetric title-and-description spread; comparison pages put a compact contrast table under the promise.

**Avoid:** Do not replace the small serif promise with giant bold sans-serif type, move the interface above the promise or hide the product entirely below the first screen.

**Text style:** `heading` — Crimson Pro 300 · 32px/1

### Heading pair and capability mosaic

**Observed:** Centered heading and muted support use a 12px gap. After approximately 72px, Capability tiles form alternating narrow/wide rows across Marketing stage; equal three-column tiles serve a compact capability group. Flat pale backings contrast with rounded white interface panels.

**Transfer:** Group related benefits by behavior and give the more complex demonstration the wider tile. Keep the titles short and the product detail larger than the prose.

**Text style:** `heading` — Crimson Pro 300 · 32px/1

### Portrait quotation pause

**Observed:** A 60px circular portrait precedes a centered Quote in a 650px maximum column; muted attribution follows after 24px. The block uses 48px vertical padding and is separated from adjacent chapters by the wider section rhythm.

**Transfer:** Use a real short outcome-focused quotation to interrupt a run of demonstrations, rather than adding another interface card.

**Text style:** `quote` — Crimson Pro 300 · 26px/1

### Wide demonstration chapter

**Observed:** Centered heading/support above one wide video in Capability backing, with 24px inset around the media and a 12px-radius inner frame. Media is approximately 1044px by 596px; a compact translucent dark playback control sits over it.

**Transfer:** Show a useful end-to-end action in one scene. Keep the surrounding heading low-key and let the work occupy the area.

### Proof gallery

**Observed:** Centered heading followed by a 60px gap to Testimonial cards in three columns, with 16px gutters. A full set forms three rows; the group uses 48px vertical padding.

**Transfer:** Use enough authentic proof to create a field rather than one oversized quotation. Shorten entries to keep the grid visually even.

### Plan and reassurance

**Observed:** Centered title and support, then a small billing switch. A Decision pair places an unboxed plan at left and a portrait quotation at right, separated by a very faint vertical rule. The plan stacks 24px editorial title, short audience description, checkmarked benefits, compact 32px price, Plan button and muted risk-reversal copy.

**Transfer:** Use the two columns for decision and reassurance rather than manufacturing multiple elaborate pricing cards.

**Text style:** `editorial-title` — Crimson Pro 300 · 24px/1

### Split objection handling

**Observed:** A Decision pair puts the 32px heading and contact invitation on the left; a thin-ruled FAQ row list sits on the right. Outer section padding is 40px vertically and 16px horizontally.

**Transfer:** Keep the introduction short and reserve most detail for answers. Use the expanded prose variant when the objections require comparison context.

**Text style:** `heading` — Crimson Pro 300 · 32px/1

### Asymmetric release entry

**Observed:** Journal spread opens with 150px vertical padding and title at left, short description at right. Entries place a sticky date in the left column; the right starts after 60px with Journal media, then a 24px editorial title and muted body. Paragraphs use 32px spacing; 20px light-serif subheads divide longer entries. The last entry leads directly to Footer, without a conversion stage.

**Transfer:** Keep dates aligned to entries and maintain the unusually open left side. Allow text-only entries to start with a simple rule instead of inventing missing media.

**Text style:** `editorial-title` — Crimson Pro 300 · 24px/1

### Editorial conviction

**Observed:** A single centered 32px statement precedes Archival working photograph. After a broad interval, a 459px centered column carries charcoal 14px body prose with short paragraphs and occasional one-line emphatic sentences. Closing invitation and Footer follow.

**Transfer:** Use this scoped composition for a company’s point of view, replacing biography detail with an authentic argument about the people it serves.

**Text style:** `heading` — Crimson Pro 300 · 32px/1

### Comparison argument

**Observed:** A centered 32px two-line contrast promise and short support introduce an open three-column comparison table with product marks, benefit rows and check/cross symbols. A 768px prose column follows with 24px numbered serif contrast headings and paired problem/solution paragraphs. FAQ, human proof and repeated small invitations carry the reader toward Footer.

**Transfer:** Compare a few consequential differences with verified facts; keep it typographic rather than turning every row into a colored card.

**Text style:** `comparison-subhead` — Crimson Pro 400 · 24px/1

### Closing invitation and utility ending

**Observed:** A small centered heading sits 100px into a spacious white closing stage, followed by Primary button after 40px. The overall desktop stage is 690px high and leads into Footer. Pricing and release journals instead end after their practical content and use Footer directly.

**Transfer:** Carry the final invitation on white with deliberate breathing room, while letting content-rich decision and journal pages finish more directly. Preserve the small scale of the invitation.

**Text style:** `heading` — Crimson Pro 300 · 32px/1

## Page flow

**Storyline:** Promise → tangible product behavior → human and customer proof → deeper capabilities or decision detail → reassurance → small invitation and utility ending.

### Product landing page that turns a broad promise into visible ease of use

1. **Promise** — Centered editorial title, muted support, pale action and tabbed product stage.
2. **Social proof** — Muted trust line and gray customer marks.
3. **Capability chapters** — Asymmetric interface mosaic, portrait quote, wide demonstration and a conceptual consolidation diagram.
4. **Expansion** — Compact three-column capability demonstrations with small semantic callouts.
5. **Human proof** — Three-column portrait-and-remark gallery.
6. **Closing call** — Small serif invitation on a spacious white stage, then utility footer.

**Transfer:** Lead with one clear promise and enough visible behavior to believe it; vary the scale of demonstrations and interrupt them with human proof.

### Company point-of-view story

1. **Conviction** — Single centered serif statement.
2. **Human context** — Full-width monochrome documentary photograph with credit.
3. **Argument** — Narrow centered manifesto in small charcoal paragraphs.
4. **Closing call** — Understated invitation and shared footer.

**Transfer:** Use a real human working context and a concise argument, not an expansive corporate timeline.

### Explain the value boundary and make a low-risk purchase decision

1. **Offer** — Small category label, light-serif promise and concise free-start explanation.
2. **Value inventory** — Three-column checkmarked capability list and trial action.
3. **Pricing** — Billing switch, open plan details and compact price beside a human quotation.
4. **Objection handling** — Split FAQ layout followed directly by shared footer.

**Transfer:** Separate what a reader can try from what they pay for; make reassurance as visible as the plan.

### Explain a product choice through practical contrasts

1. **Contrast promise** — Centered claim above a sparse product comparison table.
2. **Argument** — Narrow numbered editorial sections with problem/solution pairs.
3. **Conversion** — Small centered invitation on white.
4. **Objection handling** — Expanded answers in a split FAQ section.
5. **Human proof** — Portrait card gallery.
6. **Closing call** — Repeated invitation followed by shared footer.

**Transfer:** Use a stronger verbal stance but keep the same light, typographic visual language.

### Demonstrate continuing product improvement through a release journal

1. **Orientation** — Title on the left and short introduction on the right.
2. **Dated product proof** — Long series of sticky-date spreads, media, serif entry headings and small explanatory prose.
3. **Technical explanation** — Muted serif subheads and practical step lists within selected entries.
4. **Utility ending** — Final update article then the shared footer, without a closing conversion section.

**Transfer:** Give each release its own useful explanation and media, with a clear date rail instead of a conventional card index.

## Writing

Helpful, plainspoken and sympathetic to the reader’s daily friction. The default tone makes useful promises without sounding grand; comparative copy is a scoped, more candid and occasionally salty variant.

**Do not copy:** Do not reuse Workflow’s name, wordmark, customer logos, portraits, testimonials, product-specific claims, counts, prices or competitor assertions. Source quotations below illustrate tone only; replace them with truthful material for the new product.

- **Addressing the reader:** Speak directly to you and your collaborators. Use we for the team behind the product, especially in release notes; name the product when explaining a concrete behavior.
- **Rhythm:** Short sentence-case benefit titles, usually one sentence of support, then concrete demonstration. Longer prose alternates practical explanations with brief emphatic sentences; release notes often finish with a friendly invitation or team sign-off.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Promise | Name the work and compress the relief into a plain outcome. | 6–12 words | “Design feedback and revisions, all in one place” |
| Section heading | Describe ease or a useful result rather than announcing a feature category. | 4–10 words | “Easy for any reviewer”<br>“Makes revisions effortless” |
| Support | Explain the actual reader action in one direct sentence. | 12–25 words | “They just open the link, then click anywhere to leave feedback” |
| Action | Short invitation with low commitment; arrow can add a light directional cue. | 2–5 words | “Try for free”<br>“Join the waiting list” |
| Company conviction | A clear statement about what the audience needs; follow with human-scale prose. | One short sentence | “All creatives need time for deep, creative work.” |
| Release explanation | Start with a practical change, then explain where to find it and what it saves. | Short paragraphs of 1–3 sentences | “You can now move comments after placing them.” |
| Closing invitation | A short benefit-oriented invitation rather than a fresh sales argument. | 3–6 words | “Find your flow, today” |

**Words and phrasing to use:** your work; just; in one place; easy; share; simplify; you can now; without the back-and-forth; give it a try

**Avoid:** revolutionary ecosystem; enterprise-grade synergy; unlock limitless potential; disrupt everything; dominate

**Rules:**

- Attach benefits to observable actions instead of relying on superlatives.
- Keep capability titles and body explanations distinct: the title names the benefit, the body says what happens.
- Use low-risk language near decision actions only when the offer genuinely supports it.
- For release notes, acknowledge the old friction, explain the change and give a practical next step.
- Reserve adversarial humor for comparison content; the ordinary landing page is welcoming.

## Do's and Don'ts

### Do

- Use the same 32px/1 Crimson Pro 300 recipe for the opening promise and section titles.
- Keep the main product stage near 1092px wide at desktop so it dominates the modest text.
- Maintain 16px grid gutters and 24px tile padding.
- Use the pale 8px-radius action as the default marketing button.
- Include enlarged product fragments on square #f6f6f6 backings, with active panels crisp and secondary content subdued.
- Alternate compact 14px utility prose with 26px serif human quotations.
- Keep the three-column proof gallery white-on-white with diffuse shadows.
- Finish utility navigation with a faint 1px top rule and 40px padding.

### Don't

- Do not turn the 8px-radius actions into fully rounded pills.
- Do not use the dark paid-plan button as the default action throughout an ordinary landing page.
- Do not fill marketing sections with the burgundy or green used for interface statuses.
- Do not round every capability tile to 12px; the outer pale backing is square.
- Do not apply tight price tracking to ordinary serif headings.
- Do not turn the small circular portraits into large team-photo banners on product pages.
- Do not add a dark or gradient footer; the ending remains on white.
- Do not replace the date-rail journal layout with a dense card feed on release pages.

## Motion and responsive

### Motion

**Observed:**

- Declared button background transitions use 0.2s cubic-bezier(0.455, 0.03, 0.515, 0.955); plain-link opacity uses the same duration and curve.
- Demonstration playback has pause/play controls; the consolidation diagram declares 0.6s animations with the same curve, a 0.2s line delay and 0.8s icon delays.
- Navigation has declared reveal/hide animations; pricing has declared accordion fade animations.

**Transfer:**

- Keep action feedback small and local: background change for pale buttons, opacity for plain links.
- Give moving product demonstrations an explicit pause control; the still composition should remain a legible explanation.

**Unknown:**

- Complete scroll-trigger choreography, automatic tab timing and the exact navigation reveal logic are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 768px, 991px, 1440px and 1920px; some product and comparison layouts also declare 1280px.

**Transfer:**

- On narrow screens, retain the small-serif promise and visible product object rather than scaling a desktop interface until its details disappear; show a focused interaction.
- Collapse asymmetric capability tiles and decision pairs into a single reading column; preserve titles before media and 24px tile padding where space permits.
- Bring journal dates above their corresponding entry when two equal columns no longer fit; preserve date-to-entry association.

**Unknown:**

- Exact mobile font sizes, navigation layout and breakpoint-specific grid behavior are not established. These narrow-screen adaptations are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
