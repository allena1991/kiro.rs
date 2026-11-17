# Chatbase — gridded color, serif wit

## Overview

An off-white, architectural marketing style with fine ruled compartments and concentrated bursts of cobalt, magenta and orange. Tight grotesk headlines acquire personality through expressive italic serif words, while small, tangible interface scenes explain the product. It suits software platforms with several capabilities to demonstrate: spacious at the chapter level, compact inside demonstrations, and confident without feeling corporate.

### Essentials

- Headlines switch register mid-sentence: Geist 500 at 64px/1.1 with -0.04em tracking, interrupted by Proza Display 600 italic at the same size; section statements use 48px/1.1 and turn their explanatory second half gray.
- The opening is an unequal diptych, not a floating dashboard: a 1240px ruled frame contains a 710px text side and a 528px colored demonstration side, both 720px tall, beneath a 61px navigation bar.
- Actions feel like small physical controls: 48px high, 8px corners, 12px 20px padding, a near-black primary beside a white secondary with a faint gradient and 1px edge.
- Color is held inside deliberate compartments: most of the page remains #fafafa or white; cobalt and magenta occupy demonstration halves, orange and magenta carry proof cards, and one near-black trust band interrupts the light canvas.
- Geometry ties explanation to decoration: fine isometric cube networks, diagonal diamonds and grain sit behind compact white product panels. Include a geometric product scene; when no interface exists, use three SVG cube faces around a meaningful product symbol.
- The ending becomes an oversized piece of typography: a white directory panel sits on textured cobalt, above a nearly full-container-width white high-contrast serif word sculpture with round sticker-like accents. Use the new product's name or a short original word at about 1228px wide within a 1240px frame.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Royal blue | `#303faf` | `--color-blue` | background, accent, text | Footer backdrop, demonstration fields and a selected phrase in testimonials. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fa603b` | `--color-orange` | accent, border, background | Small trust icons and stat rules; a brighter alternate demonstration stage. |
| Deep magenta | `#ae008b` | `--color-magenta` | background, accent | Demonstration stages and alternate proof panels. |
| Burnt orange | `#c43e27` | `--color-proof-orange` | background | The default bright proof card. |
| Opening blue | `#2c41b3` | `--color-hero-blue` | background | Default opening demonstration backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#09090b` | `--color-ink` | text, background, action | Headings, primary controls and the inverse trust band. |
| Inverse rule | `#27272a` | `--color-dark-rule` | border | Hairlines inside inverse trust bands. |
| Secondary ink | `#3f3f46` | `--color-secondary` | text | Secondary utility text and compact proof descriptions. |
| Heading description | `#52525b` | `--color-description` | text | Hero support and closing paragraphs. |
| Paragraph gray | `#71717a` | `--color-muted` | text, link | Body copy, muted halves of section headings and directory links. |
| Light gray text | `#a1a1aa` | `--color-subtle` | text | Support text on inverse surfaces and low-emphasis metadata. |
| Hairline gray | `#e4e4e7` | `--color-rule` | border | Section frames, table dividers and panel edges. |
| Soft gray | `#f4f4f5` | `--color-panel` | surface, border | Subtle demonstration backing and inner edges. |
| Chalk canvas | `#fafafa` | `--color-canvas` | background | Default page and navigation background. |
| Raised white | `#ffffff` | `--color-white` | surface, text | Raised panels, closing call and text on colored surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interface-focused feature pages | Sky stage | `#59a7de` | `--color-sky` | background | Wide interface showcase backing. |

## Typography

- **Geist** — Marketing headings, prose, navigation and actions. Compact contemporary grotesk with open counters and tightly fitted medium-weight headlines. Font stack: "Geist", ui-sans-serif, system-ui, sans-serif.
- **Proza Display** — Expressive italic headline interruptions. High-contrast, calligraphic display serif, with strongly shaped italic lowercase. If unavailable, use **Bodoni Moda**. Use 600 italic and tune word widths rather than loosening tracking. Font stack: "Proza Display", "Bodoni Moda", Georgia, serif.
- **Inter** (only for product demonstrations, FAQ sections and editorial letters) — Product interface text and FAQ controls; also the personal-letter body. Direct, utilitarian sans that keeps dense UI legible. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **Hathama** (only for personal editorial letters) — A personal signature at the end of a letter. Loose handwritten cursive. If unavailable, use **Caveat**. Use 400; preserve the contrast with the typeset letter. Font stack: "Hathama", "Caveat", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Geist | 500 | 64px | 1.1 | -0.04em | fixed | Opening and closing headline. |
| display-italic | Proza Display | 600 italic | 64px | 1.1 | -0.04em | fixed | Selected meaningful words within the opening headline. |
| heading | Geist | 500 | 48px | 1.1 | -0.02em | fixed | Chapter headings and long two-tone statements. |
| proof-number | Geist | 500 | 36px | 1.3 | -0.02em | fixed | White metrics on colored proof panels. |
| proof-title | Geist | 500 | 32px | 1.3 | -0.02em | fixed | Titles on large colored case cards. |
| card-heading | Geist | 500 | 24px | 1.3 | -0.02em | fixed | Capability titles and testimonial text. |
| subheading | Geist | 500 | 20px | 1.4 | -0.02em | fixed | Hero support and smaller card headings. |
| closing-support | Geist | 400 | 20px | 1.4 | -0.02em | fixed | Centered support beneath the closing display. |
| tile-intro | Geist | 500 | 20px | 1.3 | -0.02em | fixed | Inline dark title plus gray explanatory sentence inside suite tiles. |
| body-large | Geist | 500 | 18px | 1.5 | -0.02em | fixed | Standalone explanatory paragraphs. |
| body | Geist | 500 | 16px | 1.5 | -0.02em | fixed | Paragraphs and primary action labels. |
| caption | Geist | 500 | 14px | 1.4 | -0.02em | fixed | Directory links, small descriptions and metadata. |
| directory-heading | Geist | 600 | 14px | 1.4 | -0.02em | fixed | Directory category labels. |
| navigation | Geist | 400 | 14px | 1.4 | normal | fixed | Top navigation items. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| personal editorial letters | signature | Hathama | 400 | 54px | 1.01 | -0.02em | size clamp(42px, 14vw, 54px) | Handwritten sign-off. |
| pricing pages | price | Geist | 500 | 36px | 1.1 | -0.02em | fixed | Plan price or custom pricing label. |
| personal editorial letters | letter-body | Inter | 500 | 16px | 1.5 | -0.02em | fixed | First-person explanatory paragraphs. |
| FAQ sections | faq | Inter | 500 | 14px | 20px | normal | fixed | Question triggers in ruled accordion rows. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display tracking tightens to -0.04em; nearly all other marketing roles use -0.02em. Weight 500 supplies authority without bold slabs.
- A gray continuation is part of the same 48px heading, not a smaller subtitle. Hero italic words keep the surrounding headline's size and line rhythm.
- The giant closing word sculpture is artwork, not another ordinary heading. Use a high-contrast upright serif as outlined SVG, fitted to the container rather than added to the text scale.

## Layout

**Density:** Airy chapter framing with compact interface interiors; borders make generous empty margins feel structured.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card heading to body and tight icon groups. |
| 12px | Action-pair gap and short heading-to-description gap. |
| 16px | Letter paragraphs, compact form rows and utility groups. |
| 20px | Three-column card gutters and heading-to-hero-support gap. |
| 24px | Support-to-action gap and standard media-to-title spacing. |
| 32px | Suite tile padding and closing support-to-action gap. |
| 48px | Large proof-panel padding and heading-to-grid spacing. |
| 64px | Main heading-to-content gap. |
| 80px | Desktop section inset and separator-band height. |
| 120px | Closing-call vertical padding. |

### Containers and grids

- **Section frame**: max width 1240px · side padding 80px. Centered 1px ruled frame. At 1440px it leaves 100px outer gutters and about 1080px usable inner content.
- **Navigation frame**: max width 1280px · side padding 24px. Wide sticky header; brand left, compact menu centered, account action right.
- **Capability grid**: max width 1080px · 3 columns · gap 20px. Three equal 346px cards; illustrated top row can sit above smaller supporting rows.
- **Suite grid**: max width 1080px · 2 columns · gap 0px. Shared-border two-column demonstration grid, followed by a three-column strip.
- **FAQ frame**: max width 820px. Narrow centered accordion underneath a centered chapter title.
- **Story grid** (only for story directories): max width 1080px · 2 columns · gap 20px. Image-led stories in two columns with generous vertical separation.
- **Plan grid** (only for pricing pages): max width 1240px · 4 columns · gap 0px. Joined white plan columns, each about 310px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Marketing frames | 0px |
|  | Actions and inputs | 8px |
|  | Sticker accents | 50% |
| product demonstrations | Demo panels | 14px |
| product demonstrations | Chat shells | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Proof stage | `0px 10px 20px rgba(0,0,0,0.08), 0px 25px 50px rgba(0,0,0,0.06)` | Large overflowing case-study panels. |
|  | White action | `0px 1px 2px rgba(0,0,0,0.05)` | Secondary action edge lift. |
| personal editorial letters | Editorial paper | `0px 2px 2px rgba(0,0,0,0.02), 0px 4px 16px rgba(0,0,0,0.04)` | Soft lift under the textured paper. |

### Surfaces

#### Canvas · level 0

**Use:** Default light background.

**CSS:** `background: #fafafa`

#### Ruled frame · level 0

**Use:** Chapter boundaries, grids and shared card containers.

**CSS:** `border: 1px solid #e4e4e7; border-radius: 0px`

**Observed:** Frames align vertically across chapters; internal lines remain fine and almost disappear into the canvas.

**Transfer:** Structure the page with thin compartments rather than independent rounded cards.

#### Colored stage · level 0

**Use:** Large product demonstration backing.

**CSS:** `background: #2c41b3; overflow: hidden`

**Observed:** A fine diagonal diamond network and dry paper-like grain sit beneath elevated white interface panels. Magenta and bright orange are alternate chapter colors.

**Transfer:** Keep the field saturated and flat enough for the white demonstration to remain the subject.

#### Inverse trust band · level 0

**Use:** A concentrated assurance chapter.

**CSS:** `background: #09090b; color: #ffffff; border: 1px solid #27272a`

**Observed:** Dark hairlines retain the light page's grid grammar, with bright diamond emblems and muted gray support.

**Transfer:** Use for a substantive trust or reliability argument, not every feature.

#### Raised white panel · level 1

**Use:** Closing call, directory and product interfaces.

**CSS:** `background: #ffffff; border: 1px solid #e4e4e7`

**Observed:** Marketing panels remain square. Rounded corners belong to the controls and interfaces inside them.

**Transfer:** Preserve the distinction between page architecture and product objects.

#### Editorial paper · level 1

**Only for:** personal editorial letters

**Use:** A tactile long-form interlude.

**CSS:** `background: #ffffff; padding: 48px; box-shadow: 0px 2px 2px rgba(0,0,0,0.02), 0px 4px 16px rgba(0,0,0,0.04)`

**Observed:** A 650px-wide sheet carries subtle folds and cloudy paper grain, with a circular magenta heart sticker overlapping its left edge.

**Transfer:** Use restrained texture and one seal-like accent to distinguish an authored argument from feature documentation.

## Components

### Primary button

**Use:** Default main conversion action.

**CSS:** `background-color: #09090b; background-image: linear-gradient(rgba(255,255,255,0) 0%, rgba(255,255,255,0.047) 100%); color: #ffffff; border: 1px solid rgba(255,255,255,0.24); border-radius: 8px; padding: 12px 20px; height: 48px; gap: 8px; box-shadow: 0px 1px 2px rgba(0,0,0,0.1), 0px 1px 3px rgba(0,0,0,0.1)`

**Text style:** `body` — Geist 500 · 16px/1.5 · tracking -0.02em

**Observed:** Text-only and content-width, paired with a light secondary action. A sales-led closing reverses which action gets the dark treatment.

**States:** Declared: hover background-color var(--bgBrandHover); focus-visible 2px solid var(--textHeading) outline with 2px offset; active background-color var(--bgInverse).

### Secondary button

**Use:** Adjacent lower-commitment action and proof-card link.

**CSS:** `background-color: #ffffff; background-image: linear-gradient(rgba(228,228,231,0.2) 0%, rgba(228,228,231,0) 50%); color: #09090b; border: 1px solid #e4e4e7; border-radius: 8px; padding: 12px 20px; height: 48px; box-shadow: 0px 1px 2px rgba(0,0,0,0.05)`

**Text style:** `body` — Geist 500 · 16px/1.5 · tracking -0.02em

**Observed:** Placed next to the primary, or at the bottom-left of a colored story panel. The account variant is 36px high with 8px 16px padding and caption text.

**States:** Declared: hover background-color var(--bgBrandSubtler); focus-visible 2px solid var(--textHeading) outline with 2px offset; active background-color var(--bgSurfaceRaised).

### Navigation item

**Use:** Compact central menu in the sticky bar.

**CSS:** `display: inline-flex; align-items: center; height: 36px; padding: 8px 12px; border-radius: 8px; color: #09090b`

**Text style:** `navigation` — Geist 400 · 14px/1.4

**Observed:** Dropdown entries carry tiny downward chevrons; direct links share the same rhythm. The enclosing bar is 61px high with a bottom hairline.

**States:** Declared: hover background-color var(--bgBrandSubtler), color var(--textParagraph2); focus-visible 2px solid var(--textHeading) outline with 2px offset.

### Suite tile

**Use:** Explain a feature through a small working interface.

**CSS:** `padding: 32px; border-right: 1px solid #e4e4e7; border-bottom: 1px solid #e4e4e7; overflow: hidden; display: flex; flex-direction: column; gap: 24px`

**Text style:** `tile-intro` — Geist 500 · 20px/1.3 · tracking -0.02em

**Observed:** Dark feature name runs directly into gray explanatory text. The illustration floats below and may fade into the canvas at its edges; larger tiles occupy two-column cells and smaller ones a three-column strip.

**Transfer:** Show one recognizable operation, not an entire dashboard.

### Bright proof panel

**Use:** The text half of a prominent customer result card.

**CSS:** `background: #c43e27; color: #ffffff; padding: 48px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px; overflow: hidden`

**Text style:** `proof-title` — Geist 500 · 32px/1.3 · tracking -0.02em

**Observed:** A large story title precedes two metrics and small translucent-white captions; a Secondary button anchors the bottom. It joins a darkened photograph on the right, making an approximately 1080px by 480px card. Neighboring cards peek outside the frame; magenta is the alternate panel color.

**Transfer:** Pair a real outcome with a context photograph; keep numbers subordinate to the story title.

### Directory link

**Use:** Small navigation links in the ending directory.

**CSS:** `color: #71717a`

**Text style:** `caption` — Geist 500 · 14px/1.4 · tracking -0.02em

**Observed:** Stacked at 8px gaps beneath stronger category headings, in four columns with 48px gutters. A separate brand/social area sits to the left.

**States:** Declared: hover color var(--textHeading).

### Stat rule

**Only for:** quantified proof sections

**Use:** Concise four-column outcome strip.

**CSS:** `border-left: 2px solid #fa603b; padding-left: 16px; display: flex; flex-direction: column; gap: 4px`

**Text style:** `proof-title` — Geist 500 · 32px/1.3 · tracking -0.02em

**Observed:** A dark number above a muted caption; the enterprise variant uses 32px numbers while the story-directory variant uses 24px. Columns have 32px gaps and no enclosing boxes.

### FAQ trigger

**Only for:** FAQ sections

**Use:** Objection handling in a narrow ruled accordion.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; padding: 24px; height: 72px; gap: 16px; border-radius: 8px; color: #09090b`

**Text style:** `faq` — Inter 500 · 14px/20px

**Observed:** Question left, 24px plus sign right; each trigger sits in a square row with a bottom hairline, inside an 820px outer frame.

**States:** Declared: hover text-decoration-line none; focus-visible border-color lab(65.6464% 1.53497 -5.42429), with zero-size shadow layers.

### Sales textarea

**Only for:** sales-led enterprise openings

**Use:** A prospect's short project description.

**CSS:** `background: #ffffff; border: 1px solid #e4e4e7; border-radius: 8px; padding: 12px; height: 104px; box-shadow: 0px 1px 2px rgba(0,0,0,0.051)`

**Observed:** Visible label above the field; companion text fields and the select are 40px high. A 428px-wide form stack ends with a full-width Primary button.

### Plan column

**Only for:** pricing pages

**Use:** Tier comparison at the opening.

**CSS:** `background: #ffffff; border: 1px solid #e4e4e7; border-radius: 0px`

**Text style:** `price` — Geist 500 · 36px/1.1 · tracking -0.02em

**Observed:** A thin colored top stripe precedes the plan name, price, small savings label, summary, usage allowance and action. Shared horizontal divisions align feature lists. Only the preferred self-serve plan has a dark button.

## Imagery and graphics

### Geometric product stage

**Use:** Opening, split chapters and small capability illustrations.

**Observed:** White interface cards float against blue, magenta or orange grainy fields, crossed by faint oversized diamonds. Smaller capability images use a pale isometric cube lattice with one brightly colored central cube, occupying about 346px by 296px above text.

**Transfer:** Use an accurate miniature of the new product's decisive task. Minimum version: one white panel with three useful rows and a real action on a colored geometric backing.

**Build:** Create a rectangular colored base; overlay an SVG diamond network with 1px white strokes at 0.12 opacity, repeating diamonds roughly 220px wide. Add an SVG feTurbulence grain layer at low opacity. Center a white rounded panel with a restrained shadow. For small cards, draw a 30-degree isometric lattice in #e4e4e7 and fill three faces of one central cube with blue, sky and magenta; add a simple functional symbol.

### Bright story diptych

**Use:** Large proof carousel.

**Observed:** A textured orange or magenta text panel takes about three fifths of a square-edged card; a context photograph takes the remainder, darkened enough to hold a white customer mark. The photo depicts real people, infrastructure or a recognizable product, not abstract stock decoration.

**Transfer:** Use real product context and a short result story; retain grain, contrast and the asymmetrical text/photo ratio.

**Build:** Use a two-column grid with a 39.35% photo column, 480px height and a 48px inset text panel. Add a low-opacity noise SVG over the flat color; place a black 0.5-alpha overlay over the image when a white mark needs contrast.

### Industry photo accordion

**Use:** Use-case storytelling.

**Observed:** One approximately 629px by 558px active photographic panel expands beside three narrow monochrome portraits. A cobalt bottom gradient supports the category name; translucent and white conversation bubbles float over the photo. Square edges and deep diffuse shadows distinguish it from UI cards.

**Transfer:** Show people in the environment where the new product matters, and overlay one plausible exchange or result.

**Build:** Lay out one wide photo and three 129px-wide photo strips with 20px gaps. Give inactive strips grayscale and a black 0.2 overlay. On the active image layer a bottom-up blue gradient fading by about 88% of its height; pin a white caption and small bubbles above the lower edge.

### Monumental footer word sculpture

**Use:** The required expressive ending beneath the directory.

**Observed:** Textured cobalt reaches the viewport edges while a white directory remains aligned to the central frame. Beneath it, huge white upright high-contrast serif letters fill almost the whole frame and run below the edge, with several colorful round sticker emblems overlapping the top of the letterforms.

**Transfer:** Create original oversized lettering from the new product's name or a short distinctive word. Retain the surprise of an editorial serif after the utilitarian directory; if there are no appropriate badges, use original symbolic round seals.

**Build:** Make a 250px-high overflow-hidden stage beneath the directory, using cobalt and faint SVG turbulence. Fit outlined high-contrast serif capitals across 99% of a 1240px container; set the artwork about 165px high and slightly below the bottom edge. Overlap 80px–112px circular SVG seals with a white rim, dark fine outline and warm orange, sky or yellow interiors. Fit the artwork by width, not by a fixed font-size.

### Paper letter and seal

**Only for:** personal editorial letters

**Use:** A founder or practitioner argument between product chapters.

**Observed:** An off-white, subtly creased sheet carries a strong opening sentence, compact paragraphs and a handwritten sign-off. A round magenta sticker with a white heart overlaps the left edge.

**Transfer:** Use a genuine authored point of view, not an extra sales paragraph. Preserve paper tactility and the solitary seal.

**Build:** Use the Editorial paper surface, overlay a very faint noise SVG and two broad translucent curved fold highlights; put a 96px circular magenta seal partly outside the left edge with a white inner symbol and double outline.

### Isometric integration network

**Only for:** integration sections

**Use:** A centered ecosystem chapter.

**Observed:** A wide, low SVG network of pale outlined cubes carries small colored app symbols on selected top faces. It sits below a centered two-line heading and gray support, rather than being a wall of logo pills.

**Transfer:** Draw a network of the new product's compatible tools or meaningful modules, retaining the sparse white lattice.

**Build:** Use an approximately 1080px by 266px SVG with repeating isometric cube outlines at 30-degree angles in #e4e4e7. Stagger top faces into two rows and place a small colored symbol on selected faces, keeping most geometry neutral.

### Icons

**Observed:** Most marketing symbols are 20px or 24px SVGs; outline controls use 1.5px strokes, with 16px supporting symbols and tiny 12px navigation chevrons. Dark ink is the default, with orange trust icons and occasional magenta capability symbols.

**Transfer:** Choose simple consistent outline icons at 1.5px, reserving solid silhouettes for brand marks and product-specific pictograms. Pair arrow controls with square hairline frames.

## Section recipes

How recurring sections are built.

### First screen: Unequal demonstration opening

**Observed:** A 61px sticky bar crowns a 1240px bordered opening. The 720px-tall diptych puts the headline in the wider left half, vertically centered with 80px inset, and a 528px-wide colored product stage flush to the right frame. Layers run from chalk canvas and fine frame to blue geometric texture, then a centered white interface. A small rating line sits above the three-line 64px headline; selected nouns change to italic serif. The support is about 497px wide at 20px/1.4, followed after 24px by Primary button and Secondary button separated by 12px. Within the first 900px, the complete headline, support, actions and main demonstration are visible, with the top of the logo grid appearing below; the rest of that grid falls below the fold.

**Transfer:** Make the headline's typographic contrast and the product's decisive operation equally legible. Without a polished interface, build a single meaningful white task panel over the geometric field. Feature-detail openings center the mixed-font headline above a wide sky-colored interface stage; story directories use a centered sans promise above a ruled logo grid; pricing opens with a left title and right billing control; sales-led pages replace the right illustration with a white inquiry form.

**Avoid:** Do not turn the opening into a centered giant dashboard with tiny copy, or spread the saturated backdrop behind the entire headline.

**Text style:** `display` — Geist 500 · 64px/1.1 · tracking -0.04em

### Two-tone chapter statement

**Observed:** A 48px heading begins in ink and continues in paragraph gray at identical size and weight. It spans roughly 734px or more within an 80px-inset frame; content follows at 48px–64px.

**Transfer:** Write one declarative benefit, then an explanatory continuation; let tone and color, not a different type size, separate them.

**Text style:** `heading` — Geist 500 · 48px/1.1 · tracking -0.02em

### Illustrated capability triptych

**Observed:** Capability grid places three geometric scenes above Card-heading titles and 16px body copy, with 24px between scene and text and 8px between title and body. Related feature pages instead use framed cards with miniature interfaces above 20px titles, followed by two rows of compact icon-led details.

**Transfer:** Dedicate each scene to a distinct outcome; use the shared geometric construction to make a family, not three unrelated stock images.

### Numbered split chapter

**Observed:** A square-edged half-width colored stage sits beside a light text panel with a 48px heading, numbered rows and a Primary button. The active row has a thin colored vertical rule and expanded body copy; the other rows collapse to number and title. The demonstration side reaches about 699px high.

**Transfer:** Use for a process or multiple channels; change which side holds the stage across chapters while retaining the frame.

### Suite mosaic

**Observed:** Two-tone chapter statement introduces a shared-border Suite grid with four large demonstration cells and a three-cell supporting strip. Suite tile intros remain at the top while small interfaces are centered below; edge fades keep the display light.

**Transfer:** Mix the product's primary tasks and supporting tools without assigning every item an identical independent card.

### Testimonial and logo rail

**Observed:** A white panel centers a 24px quote within a roughly 711px measure. A small portrait and quote symbol sit above; a key phrase changes to blue. Attribution sits below, followed by a shared-border rail of five logos.

**Transfer:** Keep the quote short enough to read as a single proof moment; use a real result phrase for the colored emphasis.

**Text style:** `card-heading` — Geist 500 · 24px/1.3 · tracking -0.02em

### Overflowing bright proof

**Observed:** A chapter heading shares its row with two small square arrow controls. Bright proof panel joins a context photo and overflows beyond the central frame with visible neighbors. The 480px-high carousel uses a deep soft shadow and about 60px–64px space after the heading. A rating and short platform statement can follow beneath.

**Transfer:** Use the large colored proof device even when there is only one result: retain its text/photo diptych and generous surrounding frame rather than inventing empty carousel neighbors.

### Inverse assurance chapter

**Observed:** Inverse trust band contains a 48px heading, 18px support and right-aligned link. Three 346px-wide bordered cards carry colored diamond emblems, 20px titles and gray body. A lower three-column strip uses orange outline icons and thin dark vertical separators.

**Transfer:** Translate this into concrete safeguards, quality standards or reliability commitments relevant to the new product. Render emblems as geometric symbols if formal credentials are not applicable.

### Closing call and expressive directory

**Observed:** A white bordered 543px-tall call uses 120px vertical inset, a centered two-line 64px headline within about 800px, 20px support within 601px, and a paired action row after 32px. It touches a white directory panel on cobalt: brand and social icons left, two tiers of four link columns right, a small AI-summary utility row and divided legal strip below. Monumental footer word sculpture completes the page beneath the white panel.

**Transfer:** Retain the contrast between restrained conversion panel, useful directory and theatrical serif ending. A sales-led page can promote the demo action instead of self-serve creation.

**Text style:** `display` — Geist 500 · 64px/1.1 · tracking -0.04em

### Quantified proof and index

**Only for:** enterprise and story-directory pages

**Observed:** A broad Two-tone chapter statement leads into four Stat rule items. The sales-led variant follows with a fine upward-sloping blue line chart and floating white outcome chips; the directory variant follows with 67px ruled story rows containing a logo, short outcome, category and Read link.

**Transfer:** Use the stat strip to summarize verified outcomes, then choose a chart for scale or a compact index for breadth.

### Personal letter

**Only for:** editorial feature launches

**Observed:** A centered 48px chapter title sits above Editorial paper with a 24px thesis, 16px Inter paragraphs, a handwritten signature and one overlapping seal. The sheet is about 650px wide with 48px insets.

**Transfer:** Make a reasoned first-person case for why this product approach exists, with a concrete contrast between the old and new way.

### Plans and comparison

**Only for:** pricing pages

**Observed:** A left-aligned 64px title and right billing switch precede the joined four-column Plan grid. A two-column add-on grid follows; the detailed comparison uses four 310px columns, 65px body rows with 20px 24px insets, and 67px white category rows. Plan names and prices remain visible in the comparison header during scrolling.

**Transfer:** Separate the quick choice from the exhaustive comparison and keep the latter visually tabular rather than turning each cell into a card.

### Narrow questions

**Only for:** FAQ sections

**Observed:** A centered 48px title introduces FAQ frame after 48px. Square ruled rows each contain FAQ trigger, with no filled pill treatment.

**Transfer:** Use direct customer questions and concise answers specific to the page's decision.

## Page flow

**Storyline:** Promise → tangible demonstration → breadth of capability → customer outcomes → assurance and objections → renewed action → useful directory and expressive typographic ending.

### Broad product landing page

1. **Promise** — Unequal demonstration opening plus a ruled logo grid.
2. **Capability chapters** — Illustrated triptych, numbered lifecycle and suite mosaic, with a testimonial pause.
3. **Product reach** — Reversed split chapter demonstrates multiple delivery channels.
4. **Social proof** — Overflowing bright result cards and a rating statement.
5. **Assurance** — Inverse assurance chapter and photographic use-case accordion.
6. **Closing call** — Centered white conversion panel, directory and monumental serif ending.

**Transfer:** Use the contrast between architectural explanation and colored demonstration as the default landing-page rhythm.

### Customer outcome directory

1. **Promise** — Centered sans title and support over a joined logo grid.
2. **Featured proof** — Bright photo-and-result carousel.
3. **Proof collection** — Two-column photographic story grid with small bordered outcome captions.
4. **Quantified proof** — Four orange-rule metrics and a dense ruled story index.
5. **Closing call** — Shared centered conversion panel, directory and expressive ending.

**Transfer:** Make proof browseable at three scales: featured story, image card and compact index.

### Plan selection and detailed comparison

1. **Pricing** — Left title, billing switch and joined plan columns.
2. **Expansion options** — Two-column white add-on cards followed by a logo rail.
3. **Detailed comparison** — Long shared-border table with persistent plan summaries.
4. **Assurance** — Inverse assurance band and narrow questions.
5. **Social proof** — Bright result carousel.
6. **Closing call** — Demo-first paired action followed by directory and serif artwork.

**Transfer:** Keep the offer legible first, then allow exhaustive evaluation below without diluting the grid language.

### Sales-led high-trust solution page

1. **Promise and conversion** — Unequal split opening with left promise and reassurance bullets, white inquiry form right.
2. **Quantified proof** — Four orange-rule metrics, rising line illustration and customer quote.
3. **Capability chapters** — Illustrated benefits grid and an isometric integration network.
4. **Social proof** — Bright result carousel.
5. **Assurance and objections** — Inverse safeguards, photographic use cases and narrow questions.
6. **Closing call** — Shared white conversion panel, directory and monumental type ending.

**Transfer:** Move the qualification form into the first screen and use proof to answer the buying team's operational concerns.

### Detailed feature launch

1. **Promise** — Centered mixed sans-and-italic headline above a wide blue interface scene.
2. **Demonstration** — Logo proof followed by an orange split task scene and three compact benefit descriptions.
3. **Capability exploration** — Filtered horizontal gallery of practical widget examples.
4. **Editorial rationale** — Textured personal letter explains the product decision.
5. **Capability chapters** — Illustrated grid, deployment-context miniatures and isometric integrations.
6. **Assurance and objections** — Bright results, dark safeguards, questions and related-feature cards.
7. **Closing call** — Shared centered conversion panel, directory and expressive ending.

**Transfer:** Use real task examples to make the feature concrete, then use the authored letter to explain why the approach is different.

## Writing

Confident, practical and outcome-led, with occasional conversational wit. Specific tasks and concrete results do most of the persuasion; the tone grows more personal only in authored editorial passages.

**Do not copy:** Do not reuse the brand name, logos, customer identities, quotations, certification seals, ratings, customer counts, savings, performance numbers or unverified product claims. Source examples below illustrate syntax and tone only.

- **Addressing the reader:** Speak directly to 'you' and 'your team'; refer to the product as an active helper. Use 'we' for commitments and first-person singular only for signed editorial writing.
- **Rhythm:** Short declarative chapter titles, followed by one or two explanatory sentences. Lists of three verbs create momentum; compact labels name recognizable tasks rather than abstract categories.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product's role and the experience it changes; italicize only the key conceptual words. | 5–10 words | “Your agent replies with real interfaces, not just text” |
| Section statement | Lead with a confident outcome, then continue with the practical explanation in the same sentence. | 8–20 words | “One agent for every customer interaction,”<br>“Build once and deploy everywhere” |
| Supporting line | Say what the reader can finish, where it happens and what friction disappears. | 15–40 words | “Pick a date, choose a time, confirm. Same component, same position.” |
| Primary action | Verb plus a concrete object or low-friction next step. | 2–4 words | “Start free trial”<br>“Create agent”<br>“Get a demo” |
| Editorial thesis | A candid contrast between what is useful and what fails in practice. | 15–25 words | “Conversation is a great way to ask for something, and often a bad way to receive it” |

**Words and phrasing to use:** build, deploy, optimize; ready to be used; your team; across every channel; out of the box; gets done; same knowledge, same voice

**Avoid:** revolutionary; unleash limitless potential; synergy; magical AI; generic future-of-everything slogans

**Rules:**

- Tie each capability to a task or result rather than a technology adjective.
- Use concrete nouns in labels and active verbs in headings.
- State reassurance as a direct commitment, not a fog of institutional language.
- Reserve a longer conversational argument for an authored letter; keep surrounding marketing modular.

## Do's and Don'ts

### Do

- Keep ordinary chapter frames square with 1px #e4e4e7 edges.
- Use 64px mixed-family opening type, with 48px sans chapter headings.
- Keep text and illustration together in a 1240px frame with 80px desktop insets.
- Pair 48px-high dark and white controls at a 12px gap.
- Give large colored proof panels 48px insets and readable white text.
- Make geometric artwork share the same pale ruled construction across chapters.
- Use a 120px vertical inset for the final conversion panel.
- End with a white directory over textured cobalt and oversized serif artwork.

### Don't

- Do not round all marketing cards to 16px; those soft corners belong inside product demonstrations.
- Do not make the primary CTA cobalt simply because the artwork is cobalt; actions are near-black.
- Do not set the italic interruptions in a generic oblique sans.
- Do not replace the gray continuation of a 48px heading with a small detached subtitle.
- Do not put loud gradients across the default page canvas; reserve color for bounded stages and proof.
- Do not use a wall of floating logo pills where an isometric network or ruled logo grid carries the brand grammar.
- Do not use heavy shadows on the entire layout; preserve the difference between flat frames and raised product objects.
- Do not shrink the closing word artwork into an ordinary footer logo.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions cover background-color, color, border-color and box-shadow at 0.15s cubic-bezier(0,0,.2,1).
- The navigation bar declares color transitions at 0.3s cubic-bezier(0,0,.2,1).
- Numbered demonstration chapters, horizontal case cards, use-case panels and interface galleries have selection controls; some demonstration media changes within its fixed field.

**Transfer:**

- Keep interaction changes inside stable ruled frames; active steps can swap the white interface scene while preserving the colored stage.
- Use the declared short action transition rather than a dramatic scale or glow on conversion buttons.

**Unknown:**

- Autoplay timing, scroll-entry choreography and video duration are not specified.

### Responsive

**Observed:**

- Responsive classes use 24px side insets before 80px desktop insets; the opening split is a desktop flex layout.
- The opening media uses an aspect-ratio field before becoming a 528px-wide, 720px-high desktop panel. Action groups are stacked before becoming an inline row.
- The monumental footer art is hidden outside the desktop layout.

**Transfer:**

- On narrow pages, preserve the headline's serif interruption and put the colored task scene below the promise. Stack joined grids into a readable sequence while retaining fine separators.
- Use the white directory as the narrow-screen ending when the desktop word sculpture is hidden.

**Unknown:**

- Exact mobile headline sizes, navigation interaction and breakpoint-specific artwork composition are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
