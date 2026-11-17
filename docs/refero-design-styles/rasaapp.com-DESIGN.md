# Rasa — lantern-lit inner space

## Overview

A low-density, forest-dark editorial style with warm ivory serif headlines and small pools of antique gold light. Rounded experience cards turn abstract benefits into tactile little objects rather than dashboard screenshots or lifestyle photography. It suits personal tools, learning products and considered services; a separate paper-and-handwriting treatment gives interactive explainers a more intimate, notebook-like character.

### Essentials

- A literary promise beside one luminous object: 60px/1.25 regular Playfair Display on the left and a 384×440px experience card aligned to the right, within a 1280px container.
- The night stays green, not black: #0b1d15 covers nearly the entire marketing page; #c5a059 is concentrated in small actions, thin edges and local glows rather than full-width bright bands.
- Every new landing page needs a lantern-like graphic: a small gold radial symbol above a 140px blurred halo, framed by a 28px rounded card. When there is no product artwork, use concentric rings or a radial SVG instead of a stock photograph.
- Actions feel like soft tokens: the main gold action is a 48px pill with 18px medium Inter; card actions are darker 48px pills with a small right arrow, while navigation uses a 40px gold pill.
- Reading alternates between breadth and intimacy: 1232px usable card rows contrast with 768px prose, 48px regular serif section headings, 16px heading-to-support gaps and 128px section padding.
- A thin-bordered serif ticker and a personal closing invitation temper the product grid: the ticker is 78px tall with 48px item gaps; the closing panel is 576px wide with 48px padding, a 36px serif line and tiny opt-out reassurance.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep forest | `#0b1d15` | `--color-canvas` | background, text | Default page canvas and text on gold actions. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Antique gold | `#c5a059` | `--color-gold` | action, accent, link | Primary conversion, tiny diagrams, local light and selected words. |
| Muted gold | `#a0864b` | `--color-gold-soft` | text, accent | 80% gold over forest; prose emphasis and symbols. |
| Gold-tinted forest | `#142418` | `--color-feature-wash` | surface | Visible 5% gold wash over forest; explanatory cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Inset action forest | `#0b261d` | `--color-card-action` | action | Visible 85% #0b281e over forest; card action. |
| Metadata green | `#12251d` | `--color-metadata` | surface | Visible 15% #38554b wash over forest; duration-and-category strip. |
| Footer forest | `#142720` | `--color-footer` | surface | Visible 30% #2a3f38 wash over the forest canvas. |
| Raised forest | `#1a2e26` | `--color-raised` | surface | Personal invitation panel. |
| Forest edge | `#1f3630` | `--color-rule` | border | One-pixel dividers and card edges. |
| Receding sage | `#69736d` | `--color-faint-text` | text | 40% ivory on forest; secondary annotations. |
| Caption sage | `#808983` | `--color-caption-text` | text | 50% ivory on forest; compact overlines and reassurance. |
| Muted sage | `#979f98` | `--color-body-text` | text, link | 60% ivory on forest; supporting copy and footer links. |
| Neutral gray | `#a0a0a0` | `--color-muted` | text | Alternative support text on catalog and reading introductions. |
| Reading gray | `#afb4ae` | `--color-reading-text` | text | 70% ivory on forest; long prose and navigation. |
| Light sage gray | `#c6cac4` | `--color-label-text` | text | 80% ivory on forest; small structural headings. |
| Pale ivory | `#dedfda` | `--color-action-text` | text | 90% ivory on forest; secondary card actions. |
| Soft ivory | `#e9eae5` | `--color-near-foreground` | text | 95% ivory on forest; card titles. |
| Warm ivory | `#f5f5f0` | `--color-foreground` | text | Primary headings and strong labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| hand-drawn interactive explainers | Notebook ochre | `#b97a1e` | `--color-ochre` | accent, border, link | Invitation rules, focus outlines and small actions. |
| reading indexes | Editorial gold | `#b29352` | `--color-gold-label` | text | 90% gold over forest; editorial overlines. |
| hand-drawn interactive explainers | Straw note | `#f2e7cf` | `--color-paper-yellow` | surface | First explanatory note card. |
| hand-drawn interactive explainers | Blue note | `#e7eaf0` | `--color-paper-blue` | surface | Second explanatory note card. |
| hand-drawn interactive explainers | Pencil charcoal | `#2a2824` | `--color-paper-ink` | text, border | Diagram strokes, notebook text and outlines. |
| hand-drawn interactive explainers | Pencil gray | `#8b8577` | `--color-paper-muted` | text | Translations and small annotations. |
| hand-drawn interactive explainers | Paper shadow | `#dcd6c6` | `--color-paper-shadow` | border, surface | Hard offset shadows and return-link outline. |
| hand-drawn interactive explainers | Stone note | `#edeae0` | `--color-paper-stone` | surface | Third explanatory note card. |
| hand-drawn interactive explainers | Warm paper | `#faf7ef` | `--color-paper` | background | Light explainer canvas. |
| messaging-channel invitations | Channel green wash | `#1b422e` | `--color-channel-wash` | surface | Visible 12% #25d366 on raised forest; messaging-channel action only. |

## Typography

- **Playfair Display** — Display headlines, section headings, experience titles and ticker. High-contrast literary serif with delicate hairlines and expressive capitals. OpenType features: "calt", "rlig". Font stack: "Playfair Display", Georgia, serif.
- **Inter** — Body copy, actions, metadata and navigation. Clear contemporary sans, often light in introductions and regular in prose. OpenType features: "calt", "rlig". Font stack: "Inter", Arial, sans-serif.
- **ui-monospace** — A compact timer illustration, not the general interface. System monospace numerals. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.
- **Kalam** (only for hand-drawn interactive explainers) — Notebook headings, diagram labels and annotation. Slanted, friendly pen lettering with varied stroke rhythm. Font stack: "Kalam", cursive.
- **Karla** (only for hand-drawn interactive explainers) — Compact explanatory paragraphs and translations. Open, humanist sans that sits naturally beside pen lettering. Font stack: "Karla", system-ui, sans-serif.
- **Noto Serif Devanagari** (only for multilingual reading features) — Devanagari text in featured quotations. Formal script serif with generous vertical leading. Font stack: "Noto Serif Devanagari", Noto Sans Devanagari, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Playfair Display | 400 | 60px | 1.25 | normal | fixed | Default split marketing opening. |
| section-heading | Playfair Display | 400 | 48px | 1 | normal | fixed | Centered section leads. |
| closing-heading | Playfair Display | 400 | 36px | 40px | normal | fixed | Personal invitation headline. |
| experience-title | Playfair Display | 600 | 24.8px | 1.25 | normal | fixed | Centered title inside the tall experience card. |
| feature-title | Playfair Display | 400 | 24px | 32px | normal | fixed | Explanatory feature-card headings. |
| editorial-aside | Inter | 300 italic | 24px | 32px | normal | fixed | Centered reflective line between prose passages. |
| timer | ui-monospace | 400 | 24px | 32px | normal | fixed | Small numeric proof graphic. |
| lead | Inter | 300 | 20px | 1.625 | normal | fixed | Opening supporting paragraph. |
| prose | Inter | 400 | 20px | 1.625 | normal | fixed | Narrow editorial paragraphs. |
| mechanism-title | Inter | 600 | 20px | 28px | normal | fixed | More factual or technical proof-card headings. |
| section-support | Inter | 400 | 18px | 28px | normal | fixed | Centered one- or two-line section introductions. |
| button | Inter | 500 | 18px | 28px | normal | fixed | Primary marketing action. |
| body | Inter | 400 | 16px | 1.625 | normal | fixed | Explanatory paragraphs. |
| question | Inter | 500 | 16px | 24px | normal | fixed | FAQ questions. |
| card-copy | Inter | 400 | 14px | 1.5 | normal | fixed | Two-line experience descriptions. |
| small-action | Inter | 500 | 14px | 20px | normal | fixed | Navigation and card actions. |
| link | Inter | 400 | 14px | 20px | normal | fixed | Footer links and secondary metadata. |
| reassurance | Inter | 300 | 14px | 20px | normal | fixed | Low-emphasis friction-removing copy. |
| structural-label | Inter | 500 | 14px | 20px | 0.05em, uppercase | fixed | Footer column labels and detail subsections. |
| card-overline | Inter | 400 | 12px | 16px | 0.025em | fixed | One-line situational prompt at the top of experience cards. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| catalog and reading indexes | index-display | Playfair Display | 400 | 72px | 1 | normal | fixed | Centered content-led opening. |
| single-experience launch screens | detail-display | Playfair Display | 600 | 72px | 1.25 | normal | fixed | Two-line title in a narrow phone-like stage. |
| hand-drawn interactive explainers | notebook-display | Kalam | 700 | 38px | 1.15 | normal | size clamp(26px, 5vw, 38px) | Compact left-aligned headline above the diagram. |
| detail documentation and editorial feature panels | detail-heading | Playfair Display | 400 | 30px | 1.2 | normal | fixed | Small section lead. |
| reading indexes | chapter-title | Playfair Display | 400 | 24px | 1.25 | normal | fixed | Title of each numbered entry. |
| multilingual reading features | script-quotation | Noto Serif Devanagari | 400 | 24px | 1.9 | normal | fixed | Centered original-language quotation. |
| multilingual reading features | serif-translation | Playfair Display | 400 italic | 18px | 1.625 | normal | fixed | Centered translation below the original text. |
| hand-drawn interactive explainers | notebook-section | Kalam | 400 | 18px | 1.55 | normal | fixed | Small centered related-resource heading. |
| hand-drawn interactive explainers | notebook-body | Karla | 400 | 14.5px | 1.55 | normal | fixed | Short note-card explanations. |
| hand-drawn interactive explainers | notebook-label | Kalam | 400 | 14px | 1.55 | normal | fixed | Pencil-gray annotations on cards. |
| reading indexes | editorial-overline | Inter | 400 | 12px | 16px | 0.2em, uppercase | fixed | Gold label on featured reading panels. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep serif tracking normal; elegance comes from contrast and regular weight, not compressed letter spacing.
- Use 600 only for experience titles and the immersive launch title. Major marketing headings remain 400.
- Long editorial passages use 20px Inter, while factual card copy uses 16px and tall-card summaries use 14px.
- Use the 48px/60px section-heading variant for prose-led chapters; retain 48px/48px for compact heading-and-support pairs.
- The ticker uses 20px/28px regular Playfair Display in muted ivory.

## Layout

**Density:** Airy overall, with compact text and controls contained inside richly framed cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing and compact card gaps. |
| 12px | Title-to-body gaps and stacked reading-entry separation. |
| 16px | Section heading to support; stacked reassurance lines. |
| 20px | Tall-card inner padding and numbered-row content gap. |
| 24px | Page side padding and experience-grid gaps. |
| 32px | Hero copy-block gaps, feature padding and proof-grid gaps. |
| 48px | Heading group to cards, invitation-panel padding and ticker item spacing. |
| 64px | Hero column gap, footer vertical padding and detail-documentation padding. |
| 128px | Default desktop section top and bottom padding. |
| 160px | Reflective editorial chapter top and bottom padding. |

### Containers and grids

- **marketing-container**: max width 1280px · side padding 24px. Centered outer container; usable width is 1232px at desktop.
- **opening-grid**: 2 columns · gap 64px. Equal columns; copy occupies the left and a maximum 384px object is right-aligned in the right.
- **experience-grid**: 4 columns · gap 24px. 290px-wide tall cards on the desktop marketing container.
- **feature-grid**: 3 columns · gap 24px. Equal-width explanatory cards.
- **proof-grid**: 3 columns · gap 32px. Factual mechanism cards.
- **editorial-container**: max width 896px · side padding 24px. Centered section shell with long prose narrowed to 768px.
- **invitation-container**: max width 576px. Centered conversion panel.
- **reading-container** (only for reading indexes): max width 768px · side padding 24px. Produces a 720px usable stack of entry cards.
- **documentation-container** (only for single-experience detail pages): max width 672px · side padding 24px. Plain left-aligned information beneath the immersive opening.
- **notebook-container** (only for hand-drawn interactive explainers): max width 900px · side padding 18px. 864px usable drawing field and three-note row with 14px gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | experience-card | 28px |
|  | feature-and-invitation | 20px |
|  | proof-and-reading-panels | 24px |
|  | faq-and-miniature | 16px |
| hand-drawn interactive explainers | notebook-tabs | 3px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | gold-card-edge | `inset 0px 0px 0px 2px rgba(197,160,89,0.25), 0px 0px 40px 0px rgba(197,160,89,0.15), 0px 0px 80px 0px rgba(197,160,89,0.08)` | Delicate lit perimeter of experience cards. |
| hand-drawn interactive explainers | paper-offset | `3px 3px 0px 0px #dcd6c6` | Hard offset shadow, no blur. |

### Surfaces

#### Forest canvas · level 0

**Use:** Default full-page background.

**CSS:** `background: #0b1d15; color: #f5f5f0`

#### Lantern card · level 1

**Use:** Experience objects.

**CSS:** `background: linear-gradient(rgba(16,45,35,0.8) 0%, rgba(0,0,0,0.3) 100%); border-radius: 28px; box-shadow: inset 0px 0px 0px 2px rgba(197,160,89,0.25), 0px 0px 40px rgba(197,160,89,0.15), 0px 0px 80px rgba(197,160,89,0.08); overflow: hidden`

**Observed:** A deep translucent green gradient, a fine gold perimeter and light pooled behind a central symbol. Catalog variants shift the top tint toward slate, charcoal or warm brown without becoming bright.

**Transfer:** Treat each offering as a small luminous object, not a screenshot tile.

#### Gold-wash feature · level 1

**Use:** Explanatory feature cards.

**CSS:** `background: rgba(197,160,89,0.05); border: 1px solid #1f3630; border-radius: 20px`

#### Glass proof · level 1

**Use:** Factual support cards.

**CSS:** `background: rgba(11,29,21,0.5); border: 1px solid #1f3630; border-radius: 24px; backdrop-filter: blur(8px)`

#### Invitation panel · level 1

**Use:** Personal closing conversion.

**CSS:** `background: #1a2e26; border: 1px solid #1f3630; border-radius: 20px`

#### Footer band · level 0

**Use:** Low-contrast end matter.

**CSS:** `background: rgba(42,63,56,0.3); border-top: 1px solid #1f3630`

#### Reading feature · level 1

**Only for:** reading indexes

**Use:** Featured quotation or diagnostic invitation.

**CSS:** `background: linear-gradient(rgba(197,160,89,0.12) 0%, rgba(0,0,0,0.25) 100%); border-radius: 24px; box-shadow: inset 0px 0px 0px 1px rgba(197,160,89,0.3), 0px 0px 40px rgba(197,160,89,0.06)`

#### Notebook paper · level 0

**Only for:** hand-drawn interactive explainers

**Use:** Entire light explainer environment.

**CSS:** `background: #faf7ef; color: #2a2824`

**Observed:** Flat warm paper rather than a photographic paper texture.

**Transfer:** Keep the paper clean and let imperfect strokes provide the hand-made character.

## Components

### Fixed navigation

**Use:** Persistent marketing navigation.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 65px; z-index: 50; background: rgba(11,29,21,0.8); border-bottom: 1px solid #1f3630; backdrop-filter: blur(16px)`

**Text style:** `small-action` — Inter 500 · 14px/20px

**Observed:** Compact serif identity at left; right-aligned navigation with 32px gaps and a 40px gold action. Content follows the marketing container.

**States:** Declared: hover navigation text becomes #f5f5f0.

### Primary button

**Use:** Main low-commitment conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 24px 32px; box-sizing: border-box; background: #c5a059; color: #0b1d15; border-radius: 9999px`

**Text style:** `button` — Inter 500 · 18px/28px

**Observed:** One main action rather than a pair of equally loud buttons. Navigation variant uses 14px/20px medium text, 10px 20px padding and 40px height. The immersive variant fills its narrow stage and uses a 20px radius.

**States:** Declared: hover background is color-mix(in oklab,#c5a059 90%,transparent); focus-visible border-color is #c5a059, with no visible added shadow.

### Experience card

**Use:** Hero object and catalog choices.

**CSS:** `height: 440px; padding: 20px; border-radius: 28px; position: relative; overflow: hidden; background: linear-gradient(rgba(16,45,35,0.8) 0%, rgba(0,0,0,0.3) 100%); box-shadow: inset 0px 0px 0px 2px rgba(197,160,89,0.25), 0px 0px 40px rgba(197,160,89,0.15), 0px 0px 80px rgba(197,160,89,0.08)`

**Text style:** `experience-title` — Playfair Display 600 · 24.8px/1.25

**Observed:** Whole card is a link. Centered situational overline, reserved title area, gold symbolic art, two-line clipped summary, Metadata strip, then a dark pill with arrow. Hero width is 384px; repeated cards are 290px. Dark action height is 48px, generally 200px wide in the grid and wider in the hero.

**Transfer:** Use one consistent symbolic visual language across offerings; do not turn every offering into a different illustration style.

### Metadata strip

**Use:** Duration and category inside an experience card.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 10px 16px; height: 42px; background: rgba(56,85,75,0.15); border: 1px solid rgba(56,85,75,0.2); border-radius: 9999px; margin-bottom: 12px`

**Text style:** `link` — Inter 400 · 14px/20px

**Observed:** Clock icon and duration at left, category at right; stretches across the available inner width. Its tint follows the parent card.

### Explanatory card

**Use:** Make a benefit concrete through a miniature demonstration.

**CSS:** `padding: 32px; background: rgba(197,160,89,0.05); border: 1px solid #1f3630; border-radius: 20px`

**Text style:** `feature-title` — Playfair Display 400 · 24px/32px

**Observed:** Three equal cards with an 80px miniature first, then a serif title and body. Miniatures include a gold monospace timer with check, concentric tactile rings and a clipped stack of short labels.

**Transfer:** Replace abstract benefit icons with simple demonstrations of time, interaction or variety.

### Mechanism card

**Use:** Explain why the product works.

**CSS:** `padding: 32px; background: rgba(11,29,21,0.5); border: 1px solid #1f3630; border-radius: 24px; backdrop-filter: blur(8px)`

**Text style:** `mechanism-title` — Inter 600 · 20px/28px

**Observed:** A 48px tinted icon backing sits above a sans heading and a short regular paragraph. Less decorative than experience cards.

### Personal invitation

**Use:** Closing conversion framed as an invitation, not a sales pitch.

**CSS:** `max-width: 576px; padding: 48px; background: #1a2e26; border: 1px solid #1f3630; border-radius: 20px; text-align: center`

**Text style:** `closing-heading` — Playfair Display 400 · 36px/40px

**Observed:** Headline and support precede a channel action; tiny frequency and opt-out lines follow. A separated lower note with a small lock explains what comes next. Messaging variant has a 52px green-tinted action, 2px translucent green border and a 32px circular channel icon.

**Transfer:** Keep a bounded, reassuring closing panel even when conversion is email, trial or download; use gold unless the action genuinely belongs to a messaging channel.

### FAQ row

**Use:** Answer doubts without adding a heavy information section.

**CSS:** `border: 1px solid #1f3630; border-radius: 16px; overflow: hidden; margin-bottom: 16px`

**Text style:** `question` — Inter 500 · 16px/24px

**Observed:** Two desktop columns of collapsed rows. Inner button is full width with 20px 24px padding, left-aligned question and a 20px down-chevron at right; closed outer height is 66px.

**States:** Declared: hover inner button background is color-mix(in oklab,#2a3f38 50%,transparent).

### Footer link

**Use:** Low-emphasis navigation in the final band.

**CSS:** `display: block; color: rgba(245,245,240,0.6); margin-bottom: 12px`

**Text style:** `link` — Inter 400 · 14px/20px

**Observed:** Links sit under uppercase structural labels; contact entries pair a small outline icon with text.

**States:** Declared: hover color becomes #f5f5f0.

### Numbered reading entry

**Only for:** reading indexes

**Use:** Browsable chapters, lessons or reference entries.

**CSS:** `display: flex; align-items: flex-start; gap: 20px; padding: 24px; margin-bottom: 12px; border-radius: 24px; background: linear-gradient(rgba(30,40,55,0.5) 0%, rgba(0,0,0,0.25) 100%); box-shadow: inset 0px 0px 0px 1px rgba(197,160,89,0.18), 0px 0px 30px rgba(197,160,89,0.05)`

**Text style:** `chapter-title` — Playfair Display 400 · 24px/1.25

**Observed:** 44px circular gold-wash number at left. Right side has serif title with a faint italic secondary name, one-line description and tiny count. Entries are usually 130px tall but grow for long titles.

**Transfer:** Use for sequenced content, not ordinary marketing features.

### Notebook note

**Only for:** hand-drawn interactive explainers

**Use:** Explanations linked to the diagram and related resources.

**CSS:** `background: #f2e7cf; border: 1.5px solid #2a2824; border-radius: 4px 7px 5px 6px / 6px 4px 7px 5px; box-shadow: 3px 3px 0px 0px #dcd6c6; padding: 14px 14px 16px; display: flex; flex-direction: column; gap: 6px`

**Text style:** `notebook-body` — Karla 400 · 14.5px/1.55

**Observed:** Three pastel notes use straw, pale blue and stone. Each starts with a handwritten role, then a bolder handwritten term with small translation, then sans explanation. Related-resource notes instead use paper fill and dashed borders in a two-column arrangement.

**States:** Declared: hover transform translate(-1px, -1px), shadow 4px 4px 0 #dcd6c6; focus-visible outline 2px dashed #b97a1e with 3px offset and 2px radius.

### Notebook lens tab

**Only for:** hand-drawn interactive explainers

**Use:** Switch the conceptual lens of a diagram.

**CSS:** `padding: 3px 12px; border: 1.5px solid #2a2824; border-radius: 3px; box-shadow: 2px 2px 0px 0px #dcd6c6; color: #2a2824`

**Text style:** `notebook-label` — Kalam 400 · 14px/1.55

**Observed:** Centered row with 8px gaps and 15px handwritten labels. Selected control has ink outline and hard shadow; unselected controls have transparent borders and pencil-gray text.

**States:** Declared: hover color #2a2824; focus-visible outline 2px dashed #b97a1e, outline-offset 3px and border-radius 2px.

## Imagery and graphics

### Lantern symbols

**Use:** Required visual signature in the opening object and repeated offering cards.

**Observed:** Small antique-gold flowers, spirals, wave lines, rings and luminous dots sit centrally on dark green, slate or brown gradients. Art is typically 72px, with substantial empty space around it; no photographic scene competes with the text.

**Transfer:** Use a radial or rhythmic symbol related to the new product. Minimum version: a small center point and concentric SVG rings over the same soft halo.

**Build:** Place a 140px circle behind the symbol with radial-gradient(circle, rgba(197,160,89,0.4) 0%, rgba(0,0,0,0) 70%) and blur(24px). Above it, draw a 72px SVG: concentric circles or 12 narrow ellipses rotated around a central point, filled or stroked with gold at 0.4–0.8 alpha. Add a separate full-card radial wash, 60% by 50% centered at 50% 30%, gold at 0.25 alpha fading to transparent at 60%, layer opacity 0.6. Keep the bright core small.

### Miniature proof objects

**Use:** Explanatory-card lead visuals.

**Observed:** Dark 80px-high miniature panels contain a timer and check, press-like rings, or vertically stacked gold-wash labels; these are little working metaphors rather than large product screens.

**Transfer:** Show a reduced interaction, short metric or content variety in the new product's own terms.

**Build:** Use a forest rectangle with 16px corners and a 1px forest edge; add gold monospace numerals or 2–3 small tinted label strips. For touch feedback use nested translucent gold circles with a central gold dot.

### Pen-drawn conceptual diagram

**Only for:** hand-drawn interactive explainers

**Use:** Dominant interactive teaching graphic.

**Observed:** A house occupies an 864×728px field on warm paper: doubled uneven roof strokes, upright posts, boxed foundation, rotated handwritten labels and faint sans translations. Small reddish annotations sit below the foundation. The drawing dominates the first screen, with the title kept compact.

**Transfer:** Choose a structural metaphor appropriate to the new topic, such as a map, tree or machine. The minimum acceptable treatment is a clearly labeled SVG with slightly irregular double strokes, not a polished isometric rendering.

**Build:** Create an SVG viewBox matching an 864×728px field. Draw charcoal polylines with subtly offset duplicate paths and irregular 2–3px strokes; keep fills transparent. Attach Kalam labels along the relevant lines and smaller gray Karla translations nearby. Preserve generous paper around the diagram and use pastel notes below rather than filling the drawing with color.

### Icons

**Observed:** Utility icons are predominantly 16px outline SVGs, 1.5–2px strokes with round caps; FAQ chevrons are 20px, proof symbols 24px on 48px tinted backings. Gold denotes concept and emphasis, muted ivory denotes utility.

**Transfer:** Use a consistent rounded outline family for arrows, clocks, locks and chevrons. Reserve custom radial symbols for the central art.

## Section recipes

How recurring sections are built.

### First screen: Promise beside a lantern

**Observed:** Forest canvas behind a 65px Fixed navigation. The opening uses a 1280px shell with 24px sides and 128px vertical padding, two equal columns with 64px gap. A two-line 60px regular serif promise fills most of the left column; its light 20px support sits 32px below, then the gold Primary button after another 32px. A secondary channel link and reassurance descend in 16px steps. A single 384×440px Experience card is anchored to the far right, vertically centered against the copy. Layers run from forest canvas to card gradient, gold edge, radial halo, central symbol and text. The whole 696px opening, the 78px bordered ticker and some breathing room fit inside the first 900px; the first explanatory heading is below that fold.

**Transfer:** Keep the asymmetry between a broad verbal promise and one intimate object. Without product media, make a Lantern symbol and a concise experience summary instead. Catalog and reading pages open with a centered 72px serif title and narrower support; single-experience pages use the narrow immersive stage; notebook explainers open with a compact handwritten title above the drawing.

**Avoid:** Do not center a giant headline over an oversized dashboard, stretch the object across half the page, or turn the opening into a full-bleed gold gradient.

**Text style:** `display` — Playfair Display 400 · 60px/1.25

### Bordered whisper ticker

**Observed:** Full-width 78px band, 1px top and bottom forest edges, 24px vertical padding. Repeated 20px/28px muted serif labels flow horizontally with 48px gaps and tiny gold separators.

**Transfer:** Include a restrained ticker of use cases, outcomes or offering names. It should feel like a passing index rather than a loud news banner.

### Heading pair and proof trio

**Observed:** Centered 48px section heading, 16px to 18px support within 768px, then 48px to three Explanatory cards. A more factual version uses Mechanism cards with sans headings and 32px grid gaps.

**Transfer:** Introduce a concept with one short statement, then make it tangible through three compact demonstrations or mechanisms.

**Text style:** `section-heading` — Playfair Display 400 · 48px/1

### Reflective prose chapter

**Observed:** 896px shell with 768px prose; centered 48px/60px serif heading, up to 64px before paragraphs. Text is 20px/1.625 with 24–32px paragraph spacing and occasional muted gold emphasis. A centered light italic line closes or interrupts the passage; the more reflective chapter uses 160px vertical padding.

**Transfer:** Use to explain a meaningful product distinction or philosophy without forcing every thought into cards.

### Choice gallery

**Observed:** Heading pair above four Experience cards with 24px gaps, followed by a centered browse link and a faint alternative path line. The catalog variant expands to a multirow grid after a centered title and simple category links.

**Transfer:** Show contrasting entry points, each with its own situational prompt and the same card anatomy.

### Bounded invitation and questions

**Observed:** Personal invitation is centered within a full-width breathing interval. After the closing offer, an optional FAQ section uses a 48px serif heading and two columns of FAQ rows.

**Transfer:** Make the invitation personal, explain cadence and reversibility, then answer practical objections without escalating urgency.

### Understated footer

**Observed:** Footer band is 386px tall at desktop with 64px vertical padding, four columns and 32px horizontal gaps. First column combines small identity, concise promise, place line and tiny italic sentiment. Remaining columns carry uppercase labels and muted Footer links. A final hairline separates copyright.

**Transfer:** End with a small human detail and useful paths, not a giant repeated hero or a sales countdown.

### Reading index

**Only for:** reading indexes

**Observed:** Centered 72px title and 20px support; a 720px-wide search capsule leads to a Reading feature with small tracked gold overline and centered multilingual quotation. A second feature invitation precedes Numbered reading entries separated by 12px. After the final entry, a hairline and compact attribution block lead into the standard footer.

**Transfer:** Adapt to a course, publication or knowledge library; keep chapter order and metadata clear while preserving the editorial pacing.

**Text style:** `index-display` — Playfair Display 400 · 72px/1

### Immersive detail and practical ending

**Only for:** single-experience detail pages

**Observed:** A centered 430×868px phone-like stage has 20px corners, a close control, gold light, 72px semibold serif title and bottom-mounted 48px gold action. Below the 900px opening, a 672px documentation shell uses a 30px serif heading and uppercase sans subheads for purpose, instructions, rationale and limitations. The ending is plain questions and related text links, not the marketing footer.

**Transfer:** Use for a focused interactive tool with honest operating guidance. Keep the launch stage distinct from the explanatory text below.

**Text style:** `detail-display` — Playfair Display 600 · 72px/1.25

### Notebook explainer and resource ending

**Only for:** hand-drawn interactive explainers

**Observed:** A compact 38px handwritten heading precedes the Pen-drawn conceptual diagram. Notebook lens tabs follow the drawing, then a thin ochre invitation band, a three-note pastel row, a small centered related-resources heading and dashed Notebook notes in two columns. Ending consists of a tiny centered process note, gratitude line and a floating bottom-right pill return link; no dark footer.

**Transfer:** Use this distinct paper environment for interactive teaching, not as the default marketing theme.

**Text style:** `notebook-display` — Kalam 700 · 38px/1.15

## Page flow

**Storyline:** Concrete promise → immediate taste → explanation and choice → rationale → personal invitation or useful next step → low-pressure end matter.

### Broad product marketing

1. **Promise** — Split serif promise and one luminous experience object.
2. **Range** — Thin moving index of offerings.
3. **Explanation** — Heading pair with three miniature-led cards.
4. **Differentiation** — Narrow prose chapter.
5. **Product choice** — Four contrasting tall experience cards.
6. **Rationale** — Three factual mechanism cards.
7. **Meaning** — Reflective prose with italic closing thought.
8. **Closing call** — Small personal invitation with reassurance and a forward-looking note.
9. **Objection handling** — Two-column FAQ, followed by four-column footer.

**Transfer:** Alternate direct product utility with a slower editorial passage; adapt the number and order of blocks to the product.

### Launch one interactive experience

1. **Immediate use** — Phone-like centered launch card with gold action.
2. **Operating guidance** — Plain narrow documentation with purpose, duration, instructions and rationale.
3. **Limitations** — Compatibility and suitability stated directly.
4. **Next step** — Common questions and related experiences as plain text links.

**Transfer:** Keep a focused use screen separate from documentation and conclude with alternatives rather than another campaign.

### Interactive conceptual explainer

1. **Orientation** — Compact handwritten title and one-line invitation.
2. **Exploration** — Large pen-drawn diagram with lens controls.
3. **Participation** — Ochre bordered self-assessment invitation.
4. **Explanation** — Three pastel note cards.
5. **Further learning** — Dashed related-resource notes.
6. **Acknowledgment** — Small process and gratitude lines plus a floating return link.

**Transfer:** Let the diagram be the main event and the labels carry the teaching; keep the paper theme scoped.

### Reading collection

1. **Promise** — Centered editorial title with restrained gold overline.
2. **Discovery** — Search capsule and featured quotation.
3. **Participation** — Small reflective invitation.
4. **Content index** — Numbered entries with title, summary and count.
5. **Attribution** — Small centered credits after a rule.
6. **End matter** — Shared forest footer.

**Transfer:** Replace the corpus with a course or publication while preserving the narrow serial reading rhythm.

### Browsable offering catalog

1. **Orientation** — Centered 72px title, light supporting line and simple category links.
2. **Product choice** — Four-column grid of consistent 440px experience cards.
3. **End matter** — Breathing room after the final row, then shared forest footer.

**Transfer:** Let situational prompts and metadata distinguish items, not a new component design per category.

## Writing

Warm, reflective and practical. Confidence comes from naming small, concrete experiences while acknowledging that people respond differently.

**Do not copy:** Do not reuse the brand name, logo, named practices, religious text, quotations, biological claims, geographic origin, channel identity or timing promises as facts about another product. Source examples illustrate tone only.

- **Addressing the reader:** Speak directly to you; use we sparingly for ongoing work and intentions. Describe the product as an aid, not an authority over the reader.
- **Rhythm:** Headlines are short, sentence-like and unforced. Support is usually one or two sentences; reassurance uses clipped parallel phrases. Longer passages move through calm contrasts and occasional em dashes without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name a felt change and a concrete boundary. | 6–10 words | “Shift your state in 60–180 seconds.” |
| Supporting line | Explain what the product does, then remove a burden. | 15–25 words | “Short, intentional experiences designed to help you pause and reset — without commitment or complexity.” |
| Primary action | Plain verb plus a small unit of experience. | 2–4 words | “Try a reset”<br>“Start Reset” |
| Reassurance | Short parallel negatives followed by permission. | 5–12 words | “No signup. No beliefs. Skip what doesn't work.”<br>“No account. No streaks. Just begin.” |
| Section heading | Conversational framing, not a feature inventory. | 3–7 words | “A Place to Start”<br>“If You're Curious” |
| Situational prompt | Describe a moment in which the item is useful. | 4–8 words | “For a quick grounding reset”<br>“When grief is heavy” |
| Closing invitation | Human-scale metaphor plus a clear expectation of contact. | 5–10 words for headline | “Your day has a reset button.”<br>“A few messages a week. No noise.” |

**Words and phrasing to use:** pause; begin; small; a moment; at your own pace; what helps; without commitment; presence

**Avoid:** crush your goals; life-changing guarantee; ultimate solution; unlock your potential; limited time; must-have; hustle

**Rules:**

- Give the reader permission to decline or choose another route.
- Use concrete duration or scope only when the new product can substantiate it.
- Explain mechanisms plainly and state limitations beside guidance.
- Let emotional language describe an experience, not promise a cure.
- Keep action labels quieter than advertising slogans.

## Do's and Don'ts

### Do

- Keep the forest canvas continuous across the default marketing page.
- Pair 60px regular serif display with 20px light sans support.
- Stage one 384×440px object against the opening copy rather than filling the whole right column.
- Keep card art near 72px with a broader 140px halo.
- Use 128px desktop section padding and 24px gallery gaps.
- Distinguish 20px feature corners, 24px proof corners and 28px experience corners.
- Keep the closing invitation within 576px and include small reassurance.
- Use the paper variant as a complete scoped environment, including its ending.

### Don't

- Do not replace forest with pure black or ivory with stark white throughout.
- Do not flood a full section with solid gold; preserve it for actions and small light sources.
- Do not make all headings bold sans; the 400-weight serif hierarchy carries the identity.
- Do not use fluorescent neon glows or hard laser beams around the central symbols.
- Do not put a 72px catalog title recipe on every marketing section.
- Do not turn factual proof cards into elaborate screenshot mosaics.
- Do not apply notebook scribbles or pastel notes to ordinary forest marketing cards.
- Do not replace the modest footer with a monumental wordmark or a second oversized sales pitch.

## Motion and responsive

### Motion

**Observed:**

- Color and action transitions are declared at 0.15s cubic-bezier(.4,0,.2,1); explanatory surfaces also declare 0.3s transitions.
- Small demonstration circles declare pulse at 2s cubic-bezier(.4,0,.6,1) infinite and ping at 1s cubic-bezier(0,0,.2,1) infinite.
- A miniature stacked-label demonstration declares scroll-up at 10s linear infinite.
- Notebook cards declare transform and box-shadow transitions of 0.15s; their hover moves -1px on each axis.

**Transfer:**

- Keep motion attached to light, small demonstrations and the thin ticker; do not animate the entire editorial composition.
- Preserve the notebook's small physical lift instead of applying luminous forest hover effects.

**Unknown:**

- Ticker timing and complete glow-keyframe trajectories are not established.
- No reliable reduced-motion or touch-state behavior is established.

### Responsive

**Observed:**

- Main styles declare width breakpoints at 640px, 768px, 1024px, 1280px and 1536px.
- Opening grid classes switch to two columns at 768px, with centered copy below that width and left alignment above.
- Experience-grid classes specify two columns at 768px, three at 1024px and four at 1280px.
- Notebook styles declare 480px and 640px breakpoints; its headline scales with clamp(26px, 5vw, 38px).

**Transfer:**

- On narrow landing pages stack the promise and lantern card while retaining the card's intimate maximum width.
- Preserve the drawing's proportions and legible labels in the notebook variant; do not squeeze the desktop label density into a narrow fixed box.

**Unknown:**

- Exact mobile navigation and narrow diagram interaction behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
