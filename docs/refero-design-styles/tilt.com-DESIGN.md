# Tilt — heavyweight with a human turn

## Overview

A bold, human-centered style that makes practical products feel empowering rather than institutional. Heavy, tightly packed sans-serif headlines turn unexpectedly into flowing italic serif words, while extended grotesk body text adds a distinctive breadth. Charcoal stages alternate with warm cream and white, with acid yellow actions and pastel-backed product illustrations. The overall density is spacious and theatrical, punctuated by compact factual details and candid human photography.

### Essentials

- Headlines change emotional register mid-sentence: Gravity 900 at 96px/1 with -1px tracking pairs with EmpowerSerif italic 600 at 96px/1 with -0.5px tracking; emphasize one meaningful word or phrase, not a decorative subtitle.
- The default opening is an axial product stage: a charcoal #171616 field, centered label and two-line headline about 877px wide, a 660px support measure, a small yellow pill, then a single 512×322px product object entering the first screen.
- Actions are small, bright punctuation against monumental type: #e4e24e pills, 45px tall with 19.2px horizontal padding and Suisse Intl 12.8px/19.2px at 600; keep their width content-led.
- Color is concentrated inside pictures and actions: broad page fields remain charcoal, #f7f5ef cream or white; pastel mint, blue and lilac occupy individual media wells rather than washing the entire page.
- Product benefits become tactile picture cards: 24px corners, an 8px inset around colorful artwork, 40px heavy benefit headings and 18px supporting text. Include at least one tangible product scene; a simplified white interface panel plus a softly painted object is the fallback when physical product media is unavailable.
- A second monumental statement provides a conversion pause: centered 96px mixed-family type, a restrained uppercase label and one pill, surrounded by 144px top and bottom breathing room. Carry this device into every landing page without requiring a fixed section order.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Chartreuse punctuation | `#e4e24e` | `--color-accent` | action, accent, text | Primary pills, small numbered discs and an occasional short highlighted benefit. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer black | `#0f0f0f` | `--color-footer` | background, text | Deep closing footer and text on primary pills. |
| Near-black ink | `#100f0f` | `--color-ink` | text, background, action | Text on cream and white; dark inset narrative panels and circular controls. |
| Charcoal stage | `#171616` | `--color-canvas` | background, surface | Default dark canvas and dark comparison cards. |
| Secondary action charcoal | `#252525` | `--color-secondary-action` | action, surface | Compact login pills beside the primary action. |
| Raised charcoal | `#262525` | `--color-raised` | surface, background, border | Dark feature cards and factual detail bands; also subtle dark object edges. |
| Footer hairline | `#333333` | `--color-footer-rule` | border | Visible white-at-15% separator against the footer black; implement using rgba(255,255,255,0.15). |
| Warm gray | `#64635c` | `--color-muted` | text, link, border | Eyebrows, secondary descriptions and underlined detail links. |
| Pale warm gray | `#c8c8b6` | `--color-light-muted` | text | Labels and supporting text on dark fields; detail descriptions also use this hue at 60% opacity. |
| Soft support white | `#ebeae1` | `--color-support` | text, surface | Dark-theme supporting paragraphs and inactive light control backgrounds. |
| Warm cream | `#f7f5ef` | `--color-paper` | background, surface | Light feature chapters, comparison backgrounds and short benefit strips. |
| Warm headline white | `#fffdf6` | `--color-warm-text` | text, action | Main dark-theme headlines and light circular controls. |
| Clear white | `#ffffff` | `--color-white` | surface, background, text, border | Cards on cream, question sections and white text or photographic frames. |

## Typography

- **Gravity** — Monumental headings and emphatic card titles. Extremely heavy compact sans with blunt terminals, tight counters and a forceful block silhouette. If unavailable, use **Barlow Condensed**. Use 900; tune width toward the compact, heavy original rather than a wide geometric sans. Font stack: "Gravity", "Barlow Condensed", Arial, sans-serif.
- **EmpowerSerif** — Emotional words embedded in major headings. Flowing high-contrast italic serif with broad gestures and pointed joins. If unavailable, use **Libre Caslon Display**. Use an italic treatment and tune width; this is a silhouette approximation, not an exact match. Font stack: "EmpowerSerif", "Libre Caslon Display", "Times New Roman", Times, serif.
- **GTAmericaExtendedRegular** — Body paragraphs, supporting headings and question labels. Wide grotesk with a low-key geometric construction, rendered in regular and medium cuts. If unavailable, use **Archivo**. Use its expanded width axis with weights 400 and 500. Font stack: "GTAmericaExtendedRegular", "Archivo", Arial, sans-serif.
- **GTAmericaExpandedRegular** — Uppercase section labels, compact proof numbers and institutional actions. Broad sans whose tracked capitals read as confident category markings. If unavailable, use **Archivo**. Use the expanded width axis, primarily 500. Font stack: "GTAmericaExpandedRegular", "Archivo", Arial, sans-serif.
- **Suisse Intl** — Navigation, primary product actions and footer links. Neutral compact grotesk that lets the display system dominate. If unavailable, use **Inter**. Use 400 and 600. Font stack: "Suisse Intl", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Gravity | 900 | 96px | 1 | -0.0104em, features "dlig" | Primary and major section statements. |
| display-italic | EmpowerSerif | 600 italic | 96px | 1 | -0.0052em, features "dlig" | One accent word or phrase within the primary statement. |
| heading | Gravity | 900 | 64px | 1 | -0.0156em, features "dlig" | Split benefit chapters, factual section headings and the question-section title. |
| heading-italic | EmpowerSerif | 600 italic | 64px | 1 | -0.0078em, features "dlig" | Italic partner to heading. |
| card-heading | Gravity | 900 | 40px | 1 | -0.0063em | Feature and comparison card titles. |
| support-heading | GTAmericaExtendedRegular | 500 | 36px | 40px | -0.007em | Centered reassurance card headings and recognition card titles. |
| strip-heading | GTAmericaExtendedRegular | 500 | 24px | 1.25 | -0.0104em | Short horizontal benefit strip titles. |
| lead | GTAmericaExtendedRegular | 400 | 21px | 31px | -0.019em | Centered support lines and major chapter introductions. |
| question | GTAmericaExtendedRegular | 500 | 21px | 31px | -0.019em, features "dlig" | Accordion prompts. |
| body | GTAmericaExtendedRegular | 400 | 18px | 24px | -0.028em | Feature descriptions and factual details. |
| eyebrow | GTAmericaExpandedRegular | 500 | 16px | 1.5 | 0.094em, uppercase | Section categories and factual group labels. |
| body-small | GTAmericaExtendedRegular | 400 | 16px | 22px | normal | Longer accordion answers and compact explanatory paragraphs. |
| proof-number | GTAmericaExpandedRegular | 500 | 16px | 1.25 | -0.0156em | Compact proof and commercial metrics below the product stage; numerals are deliberately restrained. |
| button | Suisse Intl | 600 | 12.8px | 1.5 | normal | Default product conversion pills. |
| footer-link | Suisse Intl | 400 | 12.8px | 1.5 | normal | Footer navigation. |
| navigation | Suisse Intl | 400 | 11.2px | 1.5 | normal | Top-bar menu links. |
| navigation-action | Suisse Intl | 600 | 11.2px | 1.5 | normal | Login and signup pills. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company manifesto openings | portrait-display | Gravity | 900 | 215px | 1 | -0.0093em | Monumental type layered around a person. |
| company manifesto openings | portrait-italic | EmpowerSerif | 600 italic | 215px | 1 | -0.0093em | Wide italic conclusion across the portrait. |
| company narrative and editorial cards | editorial-body | GTAmericaExtendedRegular | 400 | 26px | 36px | -0.0154em | Long-form mission text and article titles. |
| company, recognition and recruiting sections | institutional-action | GTAmericaExpandedRegular | 500 | 13px | 20px | -0.019em, uppercase | Editorial and recruiting pills. |

**Notes:**

- The heavy sans and italic serif share the same nominal size and line height; the change in construction supplies the contrast, not a different color.
- Keep body copy visibly broader and lighter than the headline. Utility navigation stays unusually small rather than competing with the stage.
- Use deliberate line breaks to preserve a compact two- or three-line silhouette. Tracking is negative for display and body; only category capitals open to 1.5px.

## Layout

**Density:** Airy theatrical chapters with compact controls, dense factual panels and roomy media cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Artwork inset within feature cards and small control gaps. |
| 16px | Between stacked benefit strips; also the outer inset around broad rounded chapters. |
| 24px | Default grid gutters and paragraph-to-heading group spacing. |
| 32px | Media-to-copy spacing inside cards and benefit-strip padding. |
| 40px | Support-to-action gap and gaps between accordion rows. |
| 64px | Between a heading group and product media or a feature grid. |
| 96px | Editorial chapter padding and generous internal separation. |
| 128px | Standard substantial product chapter top and bottom padding. |
| 144px | Top and bottom padding for a monumental conversion pause. |

### Containers and grids

- **page-stage**: max width 1440px · side padding 24px. Center the full page composition; broad fields extend to the viewport.
- **feature-content**: max width 1200px · side padding 0px. Main feature grids sit about 120px from either desktop edge.
- **support-measure**: max width 660px · side padding 0px. Centered introductions and conversion supporting paragraphs.
- **feature-grid**: 2 columns · gap 24px. Large media-first feature cards, each about 588px wide at desktop.
- **three-up**: 3 columns · gap 24px. Small dark feature cards, reassurance cards and comparison options.
- **detail-columns**: 3 columns · gap 40px. Icon-led factual groups within a charcoal band.
- **recognition-rail** (only for company and recruiting proof sections): gap 24px · side padding 120px. A narrow left title block beside a horizontally clipped row of 490px cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 9999px (pill) |
|  | feature-cards | 24px |
|  | inset-chapter | 32px |
| recognition sections | recognition-cards | 16px |
| recruiting benefit and listings chapters | culture-panel | 40px |

## Surfaces and depth

### Surfaces

#### Dark stage · level 0

**Use:** Default opening, benefit chapters and monumental conversion pauses.

**CSS:** `background: #171616; color: #fffdf6`

**Observed:** A flat warm charcoal field, not a gradient or illuminated technical space.

**Transfer:** Let typography and objects supply drama.

#### Cream chapter · level 0

**Use:** Product progress, reassurance and comparisons.

**CSS:** `background: #f7f5ef; color: #100f0f`

**Observed:** Alternates with the dark stage; can be an inset chapter with 16px outer gutters and 32px corners.

**Transfer:** Use a broad light interruption to reset the reading pace.

#### White card · level 1

**Use:** Feature and reassurance content on cream.

**CSS:** `background: #ffffff; border-radius: 24px; box-shadow: none`

**Observed:** Flat painted surface, separated by background contrast rather than shadow.

**Transfer:** Keep the interface material simple so the pictured objects feel tactile.

#### Raised dark card · level 1

**Use:** Feature explanations on a dark stage.

**CSS:** `background: #262525; border-radius: 24px; box-shadow: none`

**Observed:** One modest tonal step above the canvas; image wells do most of the color work.

**Transfer:** Do not introduce glass or a glowing border.

#### Detail band · level 0

**Use:** Compact, grouped product facts.

**CSS:** `background: #262525; color: #fffdf6`

**Observed:** Full-width tonal band with three factual columns and a compact product thumbnail.

**Transfer:** Use for specifications or credible operational detail.

#### Question field · level 0

**Use:** Objection handling.

**CSS:** `background: #ffffff; color: #100f0f`

**Observed:** An unboxed two-column section, not a stack of outlined cards.

**Transfer:** Let the question text and round controls define rows.

#### Footer field · level 0

**Use:** Shared ending.

**CSS:** `background: #0f0f0f; color: #fffdf6; border-top: 1px solid rgba(255,255,255,0.15)`

**Observed:** Deep flat field with a hairline separating the upper navigation area from disclosures.

**Transfer:** Use substantial negative space before the lower information tier.

## Components

### Primary button

**Use:** Main product conversion.

**CSS:** `background: #e4e24e; color: #0f0f0f; border-radius: 9999px; padding: 0px 19.2px; height: 45px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `button` — Suisse Intl 600 · 12.8px/1.5

**Observed:** A content-width pill with a short sentence-case label. It sits alone below centered support copy or at the end of a benefit introduction.

**States:** Declared: hover background-color color-mix(in oklab, #e4e24e 80%, transparent); focus-visible outline-style none and transparent border, with zero-size box-shadow layers.

### Secondary button

**Use:** Compact login action adjacent to signup.

**CSS:** `background: #252525; color: #ffffff; border-radius: 9999px; padding: 0px 16px; height: 35px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `navigation-action` — Suisse Intl 600 · 11.2px/1.5

**Observed:** Paired with an equally compact yellow signup pill. Footer versions are 32px tall.

**States:** Declared: hover background-color color-mix(in oklab, #252525 80%, transparent); focus-visible outline-style none and transparent border, with zero-size box-shadow layers.

### Fixed navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; z-index: 50; background: #171616; color: #ffffff`

**Text style:** `navigation` — Suisse Intl 400 · 11.2px/1.5

**Observed:** Product links are grouped on the left, a small white wordmark is independently centered, and login/signup sit on the right. The declared header box is 86px tall; the visible bar is compact and can retract while scrolling.

**Transfer:** Keep the logo centered independently of unequal side content.

### Media feature card

**Use:** Visual explanation of a capability.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 8px 8px 40px 8px; display: flex; flex-direction: column; gap: 32px; align-items: center`

**Text style:** `card-heading` — Gravity 900 · 40px/1 · tracking -0.0063em

**Observed:** Large pastel-backed artwork fills the upper portion; left-aligned title and supporting body sit underneath with additional inner side spacing. A dark version uses raised charcoal and white text in a three-up grid.

**Transfer:** Explain one benefit per card; use a legible diagram rather than a whole application screen.

### Benefit strip

**Use:** Short supporting benefits beside an editorial heading.

**CSS:** `background: #f7f5ef; color: #100f0f; border-radius: 24px; padding: 32px; display: flex; gap: 20px; max-width: 660px`

**Text style:** `strip-heading` — GTAmericaExtendedRegular 500 · 24px/1.25 · tracking -0.0104em

**Observed:** Title and short description occupy the left; a small isolated illustration occupies the right. Strips form a vertical stack with 16px gaps.

**Transfer:** Use a concrete object to distinguish each short benefit.

### Comparison card

**Use:** Product selection and commercial detail.

**CSS:** `background: #171616; color: #ffffff; border-radius: 24px; padding: 40px 32px; display: flex; flex-direction: column; gap: 40px; max-width: 448px`

**Text style:** `card-heading` — Gravity 900 · 40px/1 · tracking -0.0063em

**Observed:** Small product artwork first, heavy title, aligned icon-and-value rows, primary pill, then understated underlined terms links. Three cards share a cream field; short highlighted benefit text can use chartreuse.

**Transfer:** Keep comparable attributes in the same vertical order, not differently designed plans.

### Question row

**Use:** Common objections and decision support.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 40px; color: #100f0f`

**Text style:** `question` — GTAmericaExtendedRegular 500 · 21px/31px · tracking -0.019em

**Observed:** Broad text row with a dark circular plus at the far right. Rows have 40px vertical separation; answers use body-small. A mixed-serif two-line title sits in a separate left column.

### Round next control

**Use:** Advance recognition, people or narrative panels.

**CSS:** `background: #100f0f; color: #fffdf6; border-radius: 9999px; width: 48px; height: 48px; padding: 8px; display: flex; align-items: center; justify-content: center`

**Observed:** Simple 24px arrow centered within the circle; the previous control is pale and visually quieter. Paired controls have 16px between them.

**States:** Declared: hover background-color #262525; focus-visible outline-style none and transparent border, with zero-size box-shadow layers.

### Footer navigation

**Use:** Utility links in the shared ending.

**CSS:** `display: flex; flex-direction: column; gap: 12.8px; color: #fffdf6`

**Text style:** `footer-link` — Suisse Intl 400 · 12.8px/1.5

**Observed:** Product, company and legal link columns sit beside a small logo; signup/login occupy the far right. App-store badges, copyright and small social icons form a lower utility row before disclosures.

### Recognition card

**Only for:** company and recruiting proof sections

**Use:** Third-party recognition in a horizontal rail.

**CSS:** `background: #f7f5ef; border-radius: 16px; padding: 64px 40px; max-width: 490px; display: flex; flex-direction: column; align-items: center; justify-content: space-between; gap: 24px`

**Text style:** `support-heading` — GTAmericaExtendedRegular 500 · 36px/40px · tracking -0.007em

**Observed:** A contained publisher or award logo sits above a centered broad sans title and uppercase yellow pill. A narrow title column and paired round arrows anchor the left side of the rail.

### Editorial card

**Only for:** editorial resource sections

**Use:** Resource discovery within a dark closing chapter.

**CSS:** `background: #262525; border-radius: 24px; padding: 8px 24px 20px 8px; display: flex; gap: 32px; overflow: hidden`

**Text style:** `editorial-body` — GTAmericaExtendedRegular 400 · 26px/36px · tracking -0.0154em

**Observed:** Portrait-oriented image on the left, small uppercase reading-time metadata above the title on the right, and a chartreuse circular arrow below. Two columns with 32px gutters.

**Transfer:** Give editorial images a different subject per article, while preserving consistent framing.

## Imagery and graphics

### Hero product object

**Use:** The central object below the opening action.

**Observed:** A large pale physical card shown front-on, about 512×322px, floats without a pedestal on charcoal. Soft ivory tonal graphics, subtle physical edges and a small chip provide material detail; no surrounding app frame.

**Transfer:** Use a single recognizable object or a cleanly isolated product panel, wide enough to balance the headline but substantially narrower. Keep its surface pale against the dark field.

**Build:** Use an approximately 1.59:1 rounded rectangle with an ivory base, layer oversized diagonal translucent ivory forms inside it, add a restrained edge and small functional markings. Use original product geometry and text, not a branded replica; keep the object frontal and its lighting soft.

### Pastel product tableaux

**Use:** Media wells inside feature cards; a signature counterpart to the dark type-led stage.

**Observed:** Mint and aqua backdrops hold white rounded interface fragments; lilac holds a stack of merchant rows; warm stone supports a payment tile and calendar. Small painted or softly modeled coins and gauges project above the interface. Each scene is simplified, generously spaced and fills roughly the upper two thirds of a large feature card.

**Transfer:** Isolate a single outcome into one or two white panels with minimal readable data. Use a small dimensional metaphor instead of densely reproducing software.

**Build:** Create a rounded pastel rectangle in mint, aqua, lilac or warm stone. Center a white rounded panel at roughly two thirds of its width; use sparse dark text and pale rules. Overlap the panel's top edge with a small shaded SVG object, using a light face, darker side face and a soft rgba(0,0,0,0.12) local shadow. Keep the surrounding marketing card itself shadowless.

### Painted reassurance objects

**Use:** Centered within light reassurance cards and at the ends of benefit strips.

**Observed:** A turquoise lock, magnifying glass with lime detail, card and small cash stack have soft painterly shading, skewed perspective and slightly imperfect contours. Objects sit in generous white space without a full background scene; main reassurance art is 240×240px.

**Transfer:** Choose familiar real-world metaphors with a friendly, tactile finish rather than wireframe security icons.

**Build:** Draw a simple SVG silhouette with two or three uneven highlight and shade shapes, restrained aqua or lime accents and a light upper-left highlight. Tilt slightly in perspective and leave the rest of the square transparent. The minimum version is a carefully shaded vector object, not a generic outline icon.

### Floating human collage

**Only for:** brand-led home openings

**Use:** A human recognition statement rather than a product pitch.

**Observed:** Natural-color portraits and everyday work or family moments float as separate softly rounded landscape windows around a small centered sentence on near-black. Windows enter and leave the viewport edges; the composition is asymmetric, with extensive negative space and a small review proof line near the bottom.

**Transfer:** Use candid glimpses of the people affected by the product. Preserve visual separation around the central line instead of building a regular photo grid.

### Monochrome manifesto photography

**Only for:** company storytelling

**Use:** Portrait-led opening and long-form mission section.

**Observed:** A large black-and-white standing portrait sits inside a thin rectangular white frame; very large words pass behind and in front of the figure. A later kitchen family photograph is a tall monochrome image beside broad sans prose.

**Transfer:** Use a real human subject with a clear silhouette for typography overlap, then a documentary scene to ground the claim. Retain natural tonal detail, not harsh posterization.

### Team and editorial photography

**Only for:** recruiting and editorial sections

**Use:** Culture, leadership and resource proof.

**Observed:** Wide color team photos form an edge-clipped horizontal strip with thin pale borders. Leadership portraits are tall, natural-light outdoor photographs with 2px dark frames. Editorial cards mix documentary photos and abstract technical art in tall image wells.

**Transfer:** Use real environments and candid social situations; give leadership portraits consistent proportions without forcing identical poses.

### Painted milestone narrative

**Only for:** company narrative panels

**Use:** Illustrated chapter slider.

**Observed:** A softly brushed full-color scene of hands passing keys sits in a 520×474px rounded well, next to progress bars, a numbered yellow disc, heading, paragraph and circular arrows on near-black.

**Transfer:** Illustrate an ordinary moment made possible by the product rather than abstract corporate teamwork.

**Build:** Compose a close-up of hands and one consequential object, with diagonal environmental framing behind it. Use broad opaque brush shapes, muted aqua, warm brown and a small red or yellow focal accent. Keep the scene rectangular with rounded corners; a simplified flat gouache-like vector scene is the minimum equivalent.

### Icons

**Observed:** Marketing symbols are mostly solid SVG forms, 24px for benefit rows and arrows and 16px for compact social or utility links. They are cream or white on dark, near-black on light. Recruiting benefit symbols sit inside colored 48px discs.

**Transfer:** Use compact filled pictograms with clear silhouettes; reserve painterly dimensional objects for media wells, not utility actions.

## Section recipes

How recurring sections are built.

### First screen: Centered object opening

**Observed:** A flat Dark stage backs a fixed navigation bar with left menus, centered white logo and right account pills. Below a generous upper pause, a muted uppercase eyebrow introduces a centered two-line statement about 877px wide: display sans carries the factual phrase and display-italic completes it on the second line. A 660px-wide lead follows, then Primary button with 40px separation. The single pale Hero product object appears 64px below the action, 512px wide. Within the first 900px the label, complete headline, two-line support and action are visible; the product object enters the lower quarter and continues below the fold. Compact proof metrics sit farther down rather than competing at the top.

**Transfer:** Use the same centered hierarchy and one pale product artifact for a new offer. If there is no physical object, isolate a simple result panel with tactile detail. Recruiting opens with the same mixed-type promise and a rounded 800×450px video below; company manifesto openings use the scoped portrait display instead.

**Avoid:** Do not turn this into a conventional left-copy/right-dashboard split, put a photograph behind all the text, or add multiple competing hero buttons.

**Text style:** `display` — Gravity 900 · 96px/1 · tracking -0.0104em

### Mixed headline chapter

**Observed:** Centered display and display-italic form one grammatical phrase above a 660px support measure. Light chapters invert to ink; dark chapters retain warm-white type. A 64px or 96px gap separates the introduction from the supporting content.

**Transfer:** Give each major chapter a single benefit statement; let the italic word carry its emotional or outcome emphasis.

### Pastel feature chapter

**Observed:** Cream chapter is inset 16px within charcoal with 32px corners. A major centered headline precedes a two-column Media feature card grid; 24px gutters and 8px artwork insets keep the outer structure crisp. Large cards are about 588×666px.

**Transfer:** Use a broad light chapter to explain progress, workflow or outcomes with visually distinct but consistently built scenes.

### Dark three-card explanation

**Observed:** A mixed 96px headline and short centered lead sit above three raised dark Media feature cards with 24px gutters. Artwork is pastel, titles heavy and white, descriptions short. A lone Primary button follows the group.

**Transfer:** Use this for a small family of related capabilities rather than unrelated selling points.

### Split benefit stack

**Observed:** Dark stage with 128px vertical padding. A 64px mixed-family heading occupies a narrower left column, with support and action anchored lower; three Benefit strips form the right column, separated by 16px.

**Transfer:** Use the left column for the shared outcome and the strips for practical everyday mechanisms.

### Reassurance triptych

**Observed:** Cream chapter with a centered mixed-family statement, then three white cards at 24px gaps. Each card places a 36px broad sans title above a 240px painted object and centered 18px muted supporting copy; padding is 48px vertically and 32px horizontally.

**Transfer:** Treat safety, reliability or convenience as concrete approachable benefits rather than dense policy prose.

### Compact fact band

**Observed:** Detail band with 128px top and bottom padding. Product thumbnail, 64px heading and a right-aligned pill introduce three 40px-gutter columns of labeled groups. Small solid icons sit beside bright values and pale muted descriptions.

**Transfer:** Use an organized technical or commercial summary after the benefits; keep numbers compact instead of turning every fact into a giant statistic.

### Monumental action pause

**Observed:** Dark stage with 144px top and bottom padding, a 660px centered content column and muted eyebrow. Three lines of 96px mixed-family type lead to a short support paragraph and one Primary button, separated by 48px gaps.

**Transfer:** Restate the central outcome at a commitment point; preserve the scale and calm isolation even when the supporting claim changes.

### Option selection and questions

**Observed:** Three Comparison cards occupy a cream field below a large mixed-family title. The following white Question field uses a 64px serif/sans title in the left column and Question rows in a 688px right column.

**Transfer:** Move from choosing an option to resolving hesitation; keep factual rows aligned across options.

### Shared deep footer

**Observed:** Footer field spans at least a desktop viewport. The top row aligns small logo, three link groups and account actions; a large flexible empty interval leads to app badges, copyright and six social links. A faint hairline introduces a left disclosure label and a right-aligned narrow disclosure column. Horizontal padding is 64px; top padding 51.2px and bottom padding 76.8px.

**Transfer:** Keep the spacious upper utility structure and a visibly separate disclosure tier. Adapt disclosure length to the product without shrinking the whole footer into a thin strip.

### Recognition rail

**Only for:** company and recruiting sections

**Observed:** On white, a narrow left column stacks eyebrow, a 96px heavy title broken into short lines and Round next control pair. Two Recognition cards extend across the remaining width and clip at the right edge.

**Transfer:** Use outside validation as editorial content, retaining source logos at modest size and generous space around each title.

### Culture and listings chapter

**Only for:** recruiting pages

**Observed:** A dark value sequence uses small yellow numbered discs, centered 64px titles and short pale body lines. A 40px-rounded raised charcoal panel holds benefit groups with colored 48px icon discs. A separate cream inset panel combines a 96px mixed heading with grouped role listings: title left, location middle and small yellow Apply pill right.

**Transfer:** Translate values into concrete working conditions and then actionable opportunities; retain the visual distinction between culture and listings.

### Narrative proof panel

**Only for:** company storytelling

**Observed:** A dark inset panel on white pairs a 96px mixed-family heading with Painted milestone narrative media on the left and progress, a yellow numbered disc and copy on the right. Compact icon-and-number metrics form a row underneath.

**Transfer:** Explain a small set of differentiators through scenes and concrete proof, not long abstract text.

## Page flow

**Storyline:** Human promise → tangible product or people proof → benefit chapters → practical credibility → commitment point → decision support → deep utility ending.

### Brand introduction through human recognition

1. **Human promise** — Small centered recognition sentence surrounded by floating people windows on black, with compact review proof.
2. **Product orientation** — Chapter-based presentation introduces product families and personal outcomes through pale and dark stages.
3. **Utility ending** — Deep footer with product/company/legal links, badges, socials and a substantial disclosure tier.

**Transfer:** Use a short experiential brand presentation when the emotional position matters more than a single offer; do not stretch the opening into a dense pitch.

### Flagship product conversion; default landing-page model

1. **Promise** — Centered mixed-type headline, supporting offer, yellow action and isolated pale product object.
2. **Capability chapters** — Dark three-card explanation followed by a broad cream product-scene grid and split benefit strips.
3. **Reassurance** — Approachable painted objects and concise safety claims.
4. **Practical credibility** — Dense but organized three-column detail band.
5. **Commitment point** — Monumental centered action statement on charcoal.
6. **Decision support** — Dark comparison cards on cream, then unboxed questions on white.
7. **Utility ending** — Shared deep footer with a product-specific disclosure column.

**Transfer:** Adapt the sequence to the complexity of the new offer; preserve mixed display type, tangible media, contrast changes and a monumental action pause.

### Recruitment through culture and opportunity

1. **Promise** — Centered mixed headline and uppercase yellow action over a rounded team video.
2. **Human proof** — Edge-clipped team photo strip and numbered values.
3. **Capability chapters** — Large rounded dark benefit panel with colored icon discs.
4. **Outside validation** — Recognition rail on white.
5. **Actionable inventory** — Cream listings chapter with category labels and aligned title, location and action rows.
6. **People proof** — Natural-light leadership portrait rail.
7. **Editorial credibility** — Dark resource chapter with tall images, reading-time labels and yellow arrow actions.
8. **Utility ending** — Shared footer after editorial content, not a repeated product pitch.

**Transfer:** Build confidence through specific ways of working before exposing a clean opportunity inventory.

### Company mission and differentiation

1. **Human manifesto** — Monumental mixed type layered around a monochrome portrait inside a thin frame.
2. **Problem and purpose** — Tall documentary photograph beside 26px broad sans narrative.
3. **Differentiation and proof** — Dark illustrated narrative panel and compact metrics.
4. **Outside validation** — Recognition rail with cream cards on white.
5. **Closing invitation** — Centered 96px hiring invitation and uppercase yellow pill on charcoal.
6. **Utility ending** — Shared deep footer.

**Transfer:** Pair editorial imagery with candid explanation, then offer one relevant next step before the footer.

## Writing

Confident, empathetic and plainspoken. The tone recognizes effort and possibility, then explains the practical mechanism without drifting into institutional language.

**Do not copy:** Do not reuse Tilt names, wordmarks, card artwork, proprietary illustrations, customer quotes, ratings, awards, financial terms, numerical claims or mission claims; examples illustrate tone only.

- **Addressing the reader:** Speak directly to 'you' about outcomes and choices; use 'we' for commitments and candid explanations of the company.
- **Rhythm:** Headlines are usually short fragments with one expressive word. Supporting lines are one or two direct sentences; functional details become scannable rows, while company prose allows longer conversational paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the desired outcome and end on an emotionally meaningful word suited to italic emphasis. | 5–10 words | “The credit and rewards you deserve” |
| Section headline | A direct action or result, often completed by one italic word. | 3–8 words | “Build credit securely”<br>“Watch your progress in the [Brand] app” |
| Supporting line | Combine a concrete benefit with a brief explanation of how it works. | One or two sentences | “Boost cash back, keep your payments on time, and change it up to fit your style.” |
| Primary action | Short low-friction verb phrase; product actions use sentence case, institutional actions use capitals. | 2–3 words | “Get started”<br>“SEE OPEN ROLES” |
| Human statement | Recognize the person before describing the system. | One short sentence | “We see you and know you're more than a credit score.” |
| Company narrative | Mix ambition with a candid admission rather than claiming perfection. | Short conversational paragraph | “We won't pretend we've perfected it. We're still learning, refining our approach, and striving to improve — just like anyone pushing for something better.” |

**Words and phrasing to use:** you; we; build; simple; real-time; deserve; control; progress; with a tap; designed to

**Avoid:** revolutionary ecosystem; seamlessly leverage; best-in-class solutions; disruptive synergy; guaranteed success

**Rules:**

- Lead with the person's outcome; explain the enabling mechanism immediately after.
- Keep feature titles active and literal, while allowing the large chapter statement more emotional range.
- Put conditions and qualification next to precise claims rather than obscuring them with enthusiasm.
- Use a light conversational aside sparingly; do not turn every sentence into a slogan.

## Do's and Don'ts

### Do

- Pair 96px heavy sans with a same-size italic serif phrase, keeping both at line-height 1.
- Use #171616 as the default stage and #f7f5ef for broad light chapters.
- Keep product conversion pills 45px tall and their utility type at 12.8px.
- Give feature cards 24px corners, an 8px media inset and 24px grid gutters.
- Keep centered support copy within 660px and main desktop feature content near 1200px.
- Use 128px vertical chapter padding and 144px around the monumental action pause.
- Keep proof metrics restrained at 16px/20px when grouped below a stage.
- End with a spacious dark utility area and a hairline-separated disclosure tier.

### Don't

- Do not substitute a regular-weight geometric headline for the dense 900-weight display silhouette.
- Do not make the italic accent a separate thin subtitle; it completes the headline at the same nominal size.
- Do not spread chartreuse across whole marketing backgrounds; it belongs chiefly to small actions and markers.
- Do not add drop shadows to marketing card containers; the hierarchy comes from charcoal, cream and white fills.
- Do not turn 24px rounded media cards into tiny-radius technical dashboard panels.
- Do not enlarge the 11.2px navigation to body scale; the contrast between tiny utilities and huge statements matters.
- Do not use neon gradients, glass panels or dark-mode glow as a substitute for the flat warm charcoal material.
- Do not render all icons as outline glyphs; filled utility symbols and painted illustrative objects serve different roles.

## Motion and responsive

### Motion

**Observed:**

- Primary product actions declare color, background-color, border-color and opacity transitions at 0.25s cubic-bezier(0, 0, .2, 1).
- The fixed header declares transform 0.2s ease-out.
- Institutional buttons declare color transitions at .15s cubic-bezier(.4, 0, .2, 1).
- A horizontal media strip declares an 80s linear infinite-scroll animation; chapter indicators can expand from 6px to 32px width with a 0.3s cubic-bezier(.4, 0, .2, 1) width transition.

**Transfer:**

- Use restrained action color changes; preserve the slow, continuous character when carrying the photo-strip device into a culture page.
- Reserve chapter indicators for an actual chapter-based presentation, rather than adding decorative carousel dots to ordinary sections.

**Unknown:**

- Exact scroll choreography and media entrance timing are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 320px, 400px, 425px, 426px, 530px, 550px, 600px, 640px, 768px and 896px.
- Heading classes distinguish 48px and 96px treatments, and manifesto classes distinguish 72px and 215px treatments.

**Transfer:**

- On narrow screens, stack feature grids and split benefit sections while retaining the single centered opening action and object.
- Keep the serif emphasis attached to its sentence when reflowing. Use horizontal rails for recognition and people instead of compressing every card into a multi-column grid.

**Unknown:**

- Exact breakpoint-to-layout assignments and complete mobile compositions are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
