# Shade — backstage neon utility

## Overview

A cinematic black stage for practical software, with white condensed grotesk headlines, cool gray explanations and small retro terminal markings. Violet light, layered dark interfaces and colorful photographic backings give the product a creative-workstation atmosphere without turning the whole page neon. The default is a spacious dark landing experience; lighter product and commercial variants feel like desktop windows and printed technical cards.

### Essentials

- The promise feels like a title above a workstation: centered Inter Tight at 80px/86px, weight 500, -1.4px tracking, a 700px headline measure and a 600px support measure, with the main product window entering the first screen from below.
- Black is the stage, not a card color: use #000000 across the main marketing canvas, #08090a at its underlying shell, white titles and #90959d explanations. Color is concentrated in the violet action, localized glow and framed media rather than full-width saturated bands.
- Actions stay small beside oversized claims: dark-page buttons are 40px tall with 12px side padding, 14px medium text and 6px violet or 8px translucent-gray corners; the header reduces them to 32px.
- Technical markings interrupt the polished sans: 14px/16.8px VCR-style mono labels precede 56px/62px section titles by about 14px, often with a tiny category icon.
- Product proof is a layered illuminated object: include a real interface window with 6px corners, faint edge and deep shadow, backed by violet light or a colorful abstract desktop. If no interface exists, create a credible task-specific panel rather than a generic dashboard.
- Chapters emerge from near-invisible bands: a 5% white top wash fades to transparent within 15% of the band, with 160px vertical padding and a 1024px inner stage. Include this subtle chapter boundary and a strong two-line closing statement with compact paired actions.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet action light | `#6c4bc8` | `--color-violet` | action, accent | Visible result of rgba(133,92,248,0.8) on near-black. Reserve for conversion and localized illumination. |
| Cyan media glow | `#054270` | `--color-cyan-glow` | surface, accent | Visible rgba(3,91,155,0.7) over near-black within specialty media cards. |
| Blue media glow | `#052e6c` | `--color-blue-glow` | surface, accent | Visible rgba(4,62,150,0.7) over near-black within specialty media cards. |
| Violet media glow | `#3c2469` | `--color-violet-glow` | surface, accent | Visible rgba(82,48,145,0.7) over near-black within specialty media cards. |
| Plum media glow | `#361138` | `--color-plum-glow` | surface, accent | Visible rgba(74,21,75,0.7) over near-black within specialty media cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-canvas` | background | Visible default marketing canvas. |
| Near-black shell | `#08090a` | `--color-shell` | background | Underlying page shell and translucent navigation base. |
| Charcoal ink | `#131315` | `--color-ink` | text, surface, action | Dark panels; primary text and buttons in the light variant. |
| Glass edge | `#272728` | `--color-glass-edge` | border | Visible white-at-12% edge over near-black; use the alpha recipe on layered windows. |
| Window edge | `#30343b` | `--color-window-edge` | border | Fine border around the opening product window. |
| Raised gray action | `#434444` | `--color-button-glass` | action | Visible white-at-24% action on the near-black base. |
| Cool support gray | `#90959d` | `--color-support` | text | Default secondary copy and technical labels. |
| Soft lead white | `#d4d4d8` | `--color-lead` | text | Hero support and small feature names on black. |
| Title white | `#ffffff` | `--color-white` | text, surface | Dark-stage headings and light-theme canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light product pages | Terminal charcoal | `#18181a` | `--color-terminal` | surface | Inverted resource panel on the pale footer. |
| light product and pricing pages | Light-theme secondary | `#717173` | `--color-muted` | text | Secondary headings and explanatory copy in light sections. |
| light product and pricing pages | Paper edge | `#f1f1f1` | `--color-paper-edge` | border, surface | Hard offset card shadows and pricing dividers. |
| light product and pricing pages | Off-white band | `#fafafa` | `--color-paper` | background, action | Light footer bands and pale pill actions. |

## Typography

- **Inter Tight** — Default marketing headlines, support, body and actions. Taut contemporary grotesk with a compact width; medium weight remains clean even at display sizes. Font stack: "Inter Tight", Inter, sans-serif.
- **VCR OSD Mono** — Dark-stage chapter labels and footer metadata. Pixel-edged broadcast-terminal monospace, deliberately rough beside the smooth grotesk. If unavailable, use **VT323**. 400; tune size for comparable cap height. Font stack: "VCR OSD Mono", "VT323", monospace.
- **Inter** — Navigation text on the dark stage. Neutral UI grotesk, slightly less condensed than the main text. Font stack: "Inter", sans-serif.
- **Inter Display** (only for light product and pricing pages) — Display headings, descriptions, navigation and pricing. Regular-weight, open grotesk with consistently slight negative tracking. If unavailable, use **Inter**. 400–500; retain the role-specific tracking. Font stack: "Inter Display", Inter, sans-serif.
- **Aux Mono** (only for light product and pricing pages) — Uppercase category labels, bracket links and resource commands. Compact technical monospace with tightened spacing. If unavailable, use **IBM Plex Mono**. 400; use -0.04em tracking for labels. Font stack: "Aux Mono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter Tight | 500 | 80px | 86px | -0.0175em | Centered opening promise. |
| heading | Inter Tight | 500 | 56px | 62px | -0.0268em | Major chapter titles and closing statement. |
| hero-support | Inter Tight | 500 | 20px | 1.5 | normal | Centered opening explanation and short customer-proof introduction. |
| subheading | Inter Tight | 500 | 20px | 1.2 | normal | Small benefit titles beneath large demonstrations. |
| body | Inter Tight | 500 | 16px | 1.5 | normal | Chapter descriptions with occasional white phrase emphasis. |
| card-copy | Inter Tight | 500 | 14px | 1.5 | normal | Compact capability and use-case explanations. |
| eyebrow | VCR OSD Mono | 400 | 14px | 1.2 | normal | Uppercase chapter markers and footer metadata. |
| action | Inter Tight | 500 | 14px | 1.2 | normal | Dark-stage buttons. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| light product and pricing pages | light-display | Inter Display | 400 | 56px | 1.1 | -0.01em | Two-tone centered opening title. |
| pricing pages | price | Inter Display | 500 | 48px | 1.1 | -0.04em | Price or custom-price word; tighter than adjacent plan names. |
| pricing pages | light-closing | Inter Display | 400 | 48px | 1.1 | -0.01em | Centered closing command on dark charcoal. |
| light product pages | light-heading | Inter Display | 400 | 44px | 1.1 | -0.01em | Left-aligned claim and gray expansion on the next line. |
| pricing pages | plan-title | Inter Display | 400 | 40px | 1.1 | -0.01em | Plan names. |
| light product and pricing pages | light-lead | Inter Display | 400 | 22px | 1.3 | -0.01em | Hero and chapter explanations. |
| light product pages | light-action | Inter Display | 400 | 18px | 1.3 | -0.01em | Larger opening pill actions. |
| light product and pricing pages | light-small | Inter Display | 400 | 16px | 1.25 | -0.01em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Navigation and compact proof-card title and description. |
| light product pages | light-body | Inter Display | 400 | 16px | 1.3 | -0.01em | Capability-card explanations. |
| light product and pricing pages | light-label | Aux Mono | 400 | 14px | 1 | -0.04em, uppercase | Eyebrows, bracketed footer links and comparison categories. |
| pricing pages | pricing-action | Inter Display | 400 | 14px | 1.3 | -0.01em | Full-width plan actions and billing label. |

**Notes:**

- Keep the default display and chapter titles at medium weight rather than bold. Their negative tracking differs: -1.4px at 80px and -1.5px at 56px.
- Dark-stage body text is medium weight with normal tracking. The light variant changes both family and weight: regular Inter Display with -0.01em tracking.
- Use a dark claim followed by a gray explanatory line in light sections. In dark paragraphs, reverse that relationship: gray prose with a short white benefit phrase.

## Layout

**Density:** Airy between chapters, compact inside the interface and action clusters; large demonstrations carry more area than explanatory copy.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight dark card-rail gap and icon-to-label pairing. |
| 12px | Paired hero actions and button side padding. |
| 14px | Visual separation between mono eyebrow and display title. |
| 24px | Default title-to-support separation. |
| 30px | Light-theme heading stacks, card-grid gaps and panel padding. |
| 32px | Support-to-action separation and small dark-card padding. |
| 40px | Header side inset and commercial card gutter. |
| 56px | Major within-chapter grouping and demonstration separation. |
| 64px | Closing-call and dark-footer vertical padding. |
| 120px | Light-theme chapter top spacing. |
| 152px | Default hero top padding beneath the navigation. |
| 160px | Default dark chapter top and bottom padding. |

### Containers and grids

- **Main stage**: max width 1024px. Centered default chapter text and interface demonstrations; at desktop this leaves broad black side gutters.
- **Opening title**: max width 700px. Centered two-line opening title; its support copy is capped at 600px.
- **Dark capability rail**: 3 columns · gap 8px. 336px-wide use-case cards; some capability rails expose four cards and continue beyond the text stage.
- **Light content** (only for light product and pricing pages): max width 1280px · side padding 40px. Wide chapter stage with 80px visible desktop margins.
- **Light card grid** (only for light product pages): 4 columns · gap 30px. Four 298px-wide capability or proof cards; proof cards also form two rows.
- **Plan pair** (only for pricing pages): max width 900px · 2 columns · gap 40px. Two 430px-wide tall plan windows centered inside the photographic side collage.
- **Comparison matrix** (only for pricing pages): max width 1024px · 3 columns. Feature label column and two centered plan-value columns; repeated rows are 48px tall.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Product windows | 6px |
|  | Violet actions | 6px |
|  | Gray actions and dark tiles | 8px |
| pricing pages and light navigation | Commercial actions | 20px |
| light product pages | Opening pills | 35px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Dark demonstration | `rgba(0, 0, 0, 0.09) 0px 4px 24px 0px, rgba(0, 0, 0, 0.4) 0px 30px 50px 0px, rgba(255, 255, 255, 0.1) 0px 1px 0px 0px inset` | Floating interface panels. |
| light product pages | Paper offset | `#f1f1f1 8px 8px 0px 0px` | Sharp displaced backing on small proof cards. |
| pricing pages | Plan offset | `#f1f1f1 10px 10px 0px -2px` | Rigid backing behind tall pricing windows. |

### Surfaces

#### Black stage · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #000000; color: #ffffff`

#### Chapter wash · level 0

**Use:** Gentle boundary between long dark chapters.

**CSS:** `background-image: linear-gradient(rgba(255, 255, 255, 0.05) 0%, rgba(97, 106, 115, 0) 15%); padding: 160px 0px`

**Observed:** The top edge is barely brighter than the surrounding black; it does not read as a separate gray rectangle.

**Transfer:** Use it to restart visual attention without introducing a new theme.

#### Floating window · level 1

**Use:** Main product demonstrations.

**CSS:** `border: 1px solid rgba(255, 255, 255, 0.12); border-radius: 6px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.09) 0px 4px 24px 0px, rgba(0, 0, 0, 0.4) 0px 30px 50px 0px, rgba(255, 255, 255, 0.1) 0px 1px 0px 0px inset`

**Observed:** The opening window uses a finer 0.5px #30343b edge and 6px backdrop blur; later demonstrations nest a smaller dark interface inside a colorful backing.

**Transfer:** Preserve a visible frame and depth even with a simplified product mockup.

#### Dark tile · level 1

**Use:** Capability summaries and photographic use cases.

**CSS:** `background-image: linear-gradient(160deg, rgba(255, 255, 255, 0.05) 0%, rgba(0, 0, 0, 0) 100%); border-radius: 8px; overflow: hidden`

#### Chromatic tile · level 1

**Use:** Specialty capability media.

**CSS:** `background-image: radial-gradient(99.74% 100% at 50% 0%, rgba(74, 21, 75, 0.7) 0%, rgba(29, 5, 29, 0.42) 100%); border-radius: 8px; box-shadow: rgba(85, 0, 98, 0.1) 0px 0px 40px 20px, rgba(255, 255, 255, 0.1) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.5) 0px 30px 50px 0px`

**Observed:** 330px by 410px cards carry a short title and explanation above the media. Sibling cards shift the low-key glow from plum to violet, blue and cyan.

**Transfer:** Keep the colored illumination inside media rather than tinting adjacent body sections.

#### Paper canvas · level 0

**Only for:** light product and pricing pages

**Use:** Light commercial and feature presentation.

**CSS:** `background: #ffffff; color: #131315`

#### Paper card · level 1

**Only for:** light product pages

**Use:** Proof cards with physical-offset backing.

**CSS:** `background: #ffffff; box-shadow: #f1f1f1 8px 8px 0px 0px; padding: 20px`

**Observed:** Square corners and a fine visible perimeter make these read as paper sheets, not rounded SaaS cards.

## Components

### Stage navigation

**Use:** Persistent navigation above dark marketing content.

**CSS:** `height: 64px; padding: 20px 40px; background: rgba(8, 9, 10, 0.5); backdrop-filter: blur(6px); display: flex; justify-content: space-between; align-items: center`

**Text style:** `action` — Inter Tight 500 · 14px/1.2

**Observed:** Logo left, compact text navigation in the center, login and violet conversion action at right. The wrapper is sticky; header actions are 32px tall. Navigation links use Inter at 14px/28px, weight 500, with white at 80%. Light variants use a 70px fixed white bar, 1280px inner width and regular 16px text.

### Violet button

**Use:** Default high-emphasis conversion on the dark stage.

**CSS:** `height: 40px; padding: 0px 12px; background: rgba(133, 92, 248, 0.8); color: #ffffff; border-radius: 6px; box-shadow: rgba(255, 255, 255, 0.2) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.24) 0px 0px 32px 2px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter Tight 500 · 14px/1.2

**Observed:** A compact luminous rectangle rather than a pill. It sits beside a neutral self-serve action; emphasis comes from the fill, not a larger size.

### Gray button

**Use:** Self-serve and contextual actions on black.

**CSS:** `height: 40px; padding: 0px 12px; background: rgba(255, 255, 255, 0.24); color: #ffffff; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0.09) 0px 1px 4px -1px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter Tight 500 · 14px/1.2

**Observed:** Lower-emphasis chapter actions use 12% white instead of 24%. Closing actions are neutral gray rather than repeating the bright violet.

### Capability tile

**Use:** Dense summary before deeper product demonstrations.

**CSS:** `background-image: linear-gradient(160deg, rgba(255, 255, 255, 0.05) 0%, rgba(0, 0, 0, 0) 100%); border-radius: 8px; padding: 32px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `card-copy` — Inter Tight 500 · 14px/1.5

**Observed:** A compact title, muted paragraph and replacement/proof markings occupy a low-contrast tile. Photographic use-case variants use 12px inset images and a circular arrow near the bottom.

**Transfer:** Give each tile one concrete capability and one outcome.

### Stage footer

**Use:** Default dark marketing ending.

**CSS:** `padding: 64px 65px; display: flex; flex-direction: column; gap: 56px; background: #000000`

**Text style:** `eyebrow` — VCR OSD Mono 400 · 14px/1.2

**Observed:** Brand and social icons occupy the left; four small link columns occupy the right. The lower left contains compact trust marks, a service-status line and two muted mono metadata lines. It is a broad flat footer, not another raised card.

### Proof card

**Only for:** light product pages

**Use:** Enterprise confidence or technical-proof grids.

**CSS:** `background: #ffffff; box-shadow: #f1f1f1 8px 8px 0px 0px; padding: 20px; display: flex; flex-direction: column; justify-content: space-between; min-height: 245px`

**Text style:** `light-small` — Inter Display 400 · 16px/1.25 · tracking -0.01em

**Observed:** Small line icon at upper left, colorful clipped ticket at upper right and title/description aligned near the bottom. The visual edge is square and faint.

**Transfer:** Use a small ticket-like illustration for a genuine proof point; keep text dominant in the lower half.

### Opening pill

**Only for:** light product pages

**Use:** Paired light-theme hero actions.

**CSS:** `background: #131315; color: #ffffff; border-radius: 35px; padding: 15px 30px; box-shadow: rgba(19, 19, 21, 0.12) 0px 1px 4px 0px`

**Text style:** `light-action` — Inter Display 400 · 18px/1.3 · tracking -0.01em

**Observed:** The paired self-serve button is off-white with charcoal text; both are 53px tall and separated by 20px.

### Plan window

**Only for:** pricing pages

**Use:** Side-by-side subscription offers.

**CSS:** `background: #ffffff; width: 430px; box-shadow: #f1f1f1 10px 10px 0px -2px; display: flex; flex-direction: column`

**Text style:** `plan-title` — Inter Display 400 · 40px/1.1 · tracking -0.01em

**Observed:** A 60px window-chrome strip with three tiny circles precedes a 30px-inset body. Billing toggle sits at the top right of one window. Order: plan, short audience description, price, ruled separator, icon-led inclusions, bottom-anchored actions. Cards are 798px tall; the enterprise action is dark while self-serve is pale.

### Plan action

**Only for:** pricing pages

**Use:** Full-width actions inside plan windows.

**CSS:** `background: #fafafa; color: #131315; border-radius: 20px; padding: 10px 20px; box-shadow: rgba(19, 19, 21, 0.12) 0px 1px 4px 0px; height: 38px`

**Text style:** `pricing-action` — Inter Display 400 · 14px/1.3 · tracking -0.01em

**Observed:** The contact-sales variant inverts to charcoal fill and white type. A plain secondary feature link sits 10px below.

### Terminal resource panel

**Only for:** light product and pricing page footers

**Use:** A concrete next step embedded in the footer.

**CSS:** `background: #18181a; color: #ffffff; padding: 30px; max-width: 390px; box-shadow: rgba(64, 64, 64, 0.5) 10px 10px 0px -2px; display: flex; flex-direction: column; gap: 30px`

**Text style:** `light-label` — Aux Mono 400 · 14px/1 · tracking -0.04em · uppercase

**Observed:** Command title ends in a solid cursor block, followed by a small sans explanation and mono download rows with downward arrows. Against a dark footer the panel reverses to white.

**Transfer:** For products without an installer, make this a resource launcher or setup panel with a few concrete commands.

## Imagery and graphics

### Violet workstation light

**Use:** Signature illumination behind the opening demonstration; carry a localized lit-product scene into every new marketing page.

**Observed:** An intense blue-violet cloud rises from the lower-left side of the dark interface, blends through purple and dissolves into black. It stays behind the object rather than washing across the headline.

**Transfer:** Light a credible product artifact from below-left; a simple layered interface plus this glow is the minimum acceptable equivalent.

**Build:** Place an absolutely positioned ellipse about 900px wide and 600px high behind the product, offset toward its left edge. Layer radial gradients using rgba(133,92,248,0.8), rgba(4,62,150,0.7) and transparent black; blur the layer about 80px. Mask the outer edges to transparent and keep the title area black. Match the soft glow; exact stops are not essential.

### Abstract desktop and interface

**Use:** Large chapter demonstrations and paired detail panels.

**Observed:** A dark, information-rich app floats over a colorful abstract desktop made of overlapping broad translucent curves in lime, blue, plum and magenta. The outer framed backing is about 1024px wide; a roughly 901px-wide app is nested within it. Detail panels isolate one operation while retaining the same artwork behind them.

**Transfer:** Use a genuine interface or a focused HTML mockup of the new product's task; the backing should be more colorful than the interface, and remain bounded.

**Build:** Make an SVG backing from five or six oversized overlapping curved paths and cropped circles, mixing deep blue, muted lime and plum with translucent fills and a subtle noise texture. Place the dark application panel above it with 6px corners, a fine alpha-white edge and the Dark demonstration shadow. Keep color visible as a border around the app rather than a competing illustration.

### Creative work photography

**Use:** Use-case cards and media within demonstrations.

**Observed:** Square or landscape photographs show people editing, discussing work or using laptops in real environments. Images have natural light and subdued exposure on the black stage; movie stills and editorial thumbnails supply richer color inside the interface.

**Transfer:** Show real activities surrounding the new product. Use subject-specific documentary photography with comparable low-key grading; do not replace it with isolated smiling headshots.

### Clipped paper tickets

**Only for:** light product proof grids

**Use:** Tactile accent on technical proof cards.

**Observed:** Small saturated blue, teal, orange, yellow, green and lilac tickets overlap the upper-right card edge. Each has punched semicircular ends, a thin printed inner rectangle, a simple emblem and a silver wire paperclip. Slight rotation and tiny shadows make them feel attached rather than UI badges.

**Transfer:** Create original tickets for verified qualities of the new product. Minimum equivalent: a colored scalloped SVG ticket with a fine inset frame and a doubled-stroke paperclip.

**Build:** Draw a roughly 150px by 80px SVG rectangle with repeated semicircle cutouts at both short edges. Add a thin low-opacity white inset rectangle, a simple centered symbol and tiny mono edge marks. Rotate each ticket a few degrees. Overlay a narrow rounded hairpin path in gray, doubled with a lighter stroke and a small soft shadow to suggest wire.

### Film and print collage

**Only for:** pricing pages

**Use:** Frames the opening offer and reappears around the closing conversion band.

**Observed:** Large photographic prints and black film strips tilt into the viewport from both edges, leaving the central promise and plan windows unobstructed. Subjects include outdoor action, live performance and behind-the-scenes production. White print borders alternate with black sprocket-hole strips; the final band uses photographic material against charcoal.

**Transfer:** Use photographs of the new product's real working context, with cropped edge placement and varied print formats rather than generic floating UI tiles.

**Build:** Layer 240px–700px photo rectangles beyond the left and right container edges. Alternate white mats with black film borders containing repeated small rectangular perforations. Apply small opposing rotations, thin shadows and intentional viewport clipping; reserve the central 900px offer area.

### Icons

**Observed:** Small monochrome utility symbols accompany labels and features; 16px and 24px are the common sizes. Category markers, arrows, folders and security symbols are visually light. Bracketed text and download arrows reinforce the terminal motif in light-theme footers.

**Transfer:** Choose a consistent compact utility set and pair it with text. Keep symbols white or muted gray on black and charcoal on paper; reserve colored pictorial treatment for the framed artwork.

## Section recipes

How recurring sections are built.

### First screen: Illuminated workstation opening

**Observed:** A 64px Stage navigation sits above a black field. The centered promise begins after 152px of hero top padding, occupies a 700px measure and breaks into two lines at 80px/86px. Its 600px-wide, 20px support line follows after 24px, then two compact actions after 32px with a 12px gap. Behind and below this stack, the Violet workstation light illuminates a wide Floating window. Its top appears around the lower third of the first screen and its large body extends below the fold. Within 900px, the complete headline, support, actions and upper portion of the product scene are visible. A small tilted promotional card sits to the right of the text, connected toward the action by a thin curved arrow.

**Transfer:** Recreate the centered title, small action pair and bottom-entering illuminated product artifact even if the new product needs a custom task mockup. A promotional aside belongs only when a real campaign supports it. Light product pages instead open on white with a 56px regular two-tone title, 22px support, 53px pills, a compact logo-proof row and the top of a large device demonstration. Pricing pages frame their centered title with a photographic edge collage and reveal the plan-window tops near the fold.

**Avoid:** Do not turn the default into a left-aligned split hero, fill the title with a gradient or shrink the product to a tiny card beside the copy.

**Text style:** `display` — Inter Tight 500 · 80px/86px · tracking -0.0175em

### Technical chapter heading

**Observed:** Chapter wash contains a 1024px stage. A small icon and mono eyebrow lead a 56px/62px two-line title; the support paragraph is 16px/24px with a white benefit fragment. Text can form a left title/right support pair or a narrow left-aligned stack before a large demonstration.

**Transfer:** Use the mono marker to categorize the problem, then state the outcome plainly. Alternate heading arrangements without changing type hierarchy.

**Text style:** `heading` — Inter Tight 500 · 56px/62px · tracking -0.0268em

### Oversized proof and paired details

**Observed:** A Floating window fills the 1024px stage below the chapter lead. Beneath it, two roughly 455px-wide detail panels sit across a fine central divider, with 20px/24px titles, 16px/24px explanations and framed media. Separation within the chapter commonly uses 56px.

**Transfer:** Demonstrate the full task first, then isolate two useful operations in close-up; retain the same image treatment across the set.

### Compact capability rail

**Observed:** Dark tile cards sit in a tight 8px-gap rail, with short names and 14px/21px explanations. Photographic variants are 336px by 450px; specialty Chromatic tile variants are 330px by 410px with 308px-tall media beneath a short text cap.

**Transfer:** Use rails to group related capabilities without making every chapter a grid. Preserve the low-contrast card edges and the contrast between large chapter text and compact card text.

### Light claim and proof grid

**Observed:** On Paper canvas, a mono label sits 30px above a 44px regular heading pair: charcoal claim first, gray expansion second. A 22px/28.6px explanation follows with 30px spacing. Four-column grids use 30px gutters. Capability cards lead with imagery; Proof card grids place clipped tickets at the top and text below.

**Transfer:** Apply this restrained paper/window language as a complete light-page variant, not mixed randomly among default black chapters.

**Text style:** `light-heading` — Inter Display 400 · 44px/1.1 · tracking -0.01em

### Commercial offer and matrix

**Observed:** Two Plan windows sit inside the Film and print collage with a 40px gutter. Large plan names and tightly tracked prices precede compact inclusions; actions share a lower baseline. A pale customer-quote band follows. The later 1024px matrix uses uppercase mono category dividers and 48px rows with centered values or checks for the two offers.

**Transfer:** Keep offer comparison legible and vertically aligned; use one strong numeric treatment and actual verified customer proof rather than decorative statistics.

**Text style:** `plan-title` — Inter Display 400 · 40px/1.1 · tracking -0.01em

### Closing promise

**Observed:** The default ending returns to black with a 1024px horizontal composition: a two-line 56px statement on the left and two Gray button actions at right, with 64px top and bottom padding. A fine separation leads into the Stage footer. The commercial variant instead uses a charcoal 537px band, centered mono prompt, a 48px two-part command, paired actions and a photographic collage reaching toward the footer.

**Transfer:** Resolve the page into one memorable outcome and two clear ways forward. Use the horizontal version by default; keep the centered collage version for commercial offers.

**Text style:** `heading` — Inter Tight 500 · 56px/62px · tracking -0.0268em

### Utility-rich footer ending

**Observed:** Default Stage footer keeps the logo and social group at left, four compact link columns at right, and trust/status/metadata low on the left. Light product pages finish directly after the proof grid with an off-white footer: two directory columns of bracket links, a dark Terminal resource panel at right, then logo/socials and address/status at lower left with five small trust cells at lower right. The pricing footer keeps that directory arrangement but inverts the whole band to charcoal and the resource panel to white.

**Transfer:** Finish with useful navigation and a tangible next step. Use the directory-and-terminal variant only with the light/commercial page language; retain real status and trust information only when applicable.

## Page flow

**Storyline:** Outcome promise → tangible product proof → capability chapters → confidence and comparison → concise next step → practical utility ending.

### Broad product marketing landing experience

1. **Promise** — Centered large title, paired actions and glowing product window.
2. **Social proof** — Muted customer marks with a short endorsement-style introduction and customer-story action.
3. **Orientation** — Short two-line title and compact capability rail.
4. **Capability chapters** — Alternating oversized app demonstrations, split detail panels, photographic use cases and low-key chromatic feature cards.
5. **Closing call** — Left-aligned two-line outcome with neutral actions at right.
6. **Utility ending** — Broad black link-column footer with socials, trust marks and status.

**Transfer:** Choose chapters that prove the new promise; preserve the illuminated opening, technical markers and closing compression without copying the chapter count.

### Focused feature explanation with a lighter technical-commercial presentation

1. **Promise** — Two-tone centered title, explanation, pill actions, customer marks and large device demonstration.
2. **Capability proof** — Four image-led paper cards beneath a paired claim heading.
3. **Product demonstration** — A narrow command-list window beside a larger image-and-metadata window.
4. **Objection handling** — Two-row proof-card grid with clipped tickets and concise guarantees.
5. **Utility ending** — Pale directory footer and dark resource launcher; no separate oversized closing-call band.

**Transfer:** Explain one capability through examples and a clear operation before addressing risk. Let the utility footer finish this page type.

### Commercial decision and plan comparison

1. **Value promise** — Centered benefit and savings explanation framed by tilted photographic prints.
2. **Pricing** — Two desktop-window offers with aligned actions and compact inclusion lists.
3. **Social proof** — Customer quote on a pale band with supporting photographic material.
4. **Detailed comparison** — Long, categorized three-column matrix with mono labels and repeated 48px rows.
5. **Closing call** — Charcoal centered command and paired actions with a photographic edge.
6. **Utility ending** — Dark directory footer with inverted white resource panel, metadata, status and trust cells.

**Transfer:** Separate the quick plan decision from detailed comparison. Keep commercial photography at the margins so offer text remains the visual center.

## Writing

Direct, slightly irreverent and operational. The confident promise is quickly grounded in named tasks, familiar workflow friction and a clear outcome rather than abstract futurism.

**Do not copy:** Do not reuse the brand name, logo, product names, customer marks, promotional gifts, competitor comparisons, prices, performance ratios, audience counts, compliance claims or customer quotations as claims for another product. Replace these with true product-specific content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to you and your team; refer to the product by name when explaining an operation. Use we sparingly, mostly for a conversational aside.
- **Rhythm:** Headlines tend to be short outcome statements or punchy two-part commands. Support is usually one or two compact sentences. Eyebrows are clipped uppercase markers, sometimes with conversational punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Concrete category plus an unexpectedly active benefit. | 5–9 words | “Media storage that works harder” |
| Chapter headline | Everyday phrase or instruction, often split into two short lines. | 4–9 words | “Stay on the same page.”<br>“Search your assets with natural language.” |
| Technical explanation | Name the operation, then remove a specific source of friction. | 1–2 sentences | “Find what you need, without scrubbing through content. Search full sentences using your own words.” |
| Eyebrow | Short technical category or dry conversational aside. | 2–9 words | “COMMENTING & REVIEW”<br>“YEAH...WE DIDN’T STOP THERE...” |
| Action | Literal verb plus destination or next step. | 2–5 words | “Get started”<br>“Book a demo” |
| Closing command | Stop the friction, start the desired activity. | 2 short clauses | “Stop waiting. Start creating.” |

**Words and phrasing to use:** work harder; your team; directly; without; instantly; automate; what actually matters; no downtime

**Avoid:** revolutionary paradigm; unleash limitless potential; synergistic ecosystem; delightful magic; vague AI-first superlatives

**Rules:**

- Lead with the useful result; explain the mechanism immediately below.
- Contrast an unwanted chore with a specific productive activity.
- Use technical file, format or workflow terms when they establish real usefulness.
- Allow a blunt aside in a small label, not in every paragraph.
- Keep action labels literal; distinct buttons should lead to distinct next steps.

## Do's and Don'ts

### Do

- Use 80px/86px medium Inter Tight for the centered dark opening and 56px/62px for its chapter titles.
- Keep default chapter content inside a 1024px stage and let framed product media carry most of the visual weight.
- Use 160px chapter padding and the subtle 5% white top wash to make long black pages breathe.
- Maintain 40px dark actions with 12px horizontal padding; reserve the 32px version for navigation.
- Keep body descriptions cool gray at 16px/24px and highlight only the key benefit fragment in white.
- Include localized violet light and a credible framed product artifact, even when original product imagery must be made.
- Carry the paper variant as a coherent system: regular display type, square cards, 30px gutters and hard offset shadows.
- Finish with a strong compressed outcome and practical footer utilities rather than a second long explanation.

### Don't

- Do not use 700-weight headlines; the brand's large type relies on 500 on black and 400 in the light variant.
- Do not turn 6px or 8px dark actions into oversized 9999px pills; pill geometry belongs to the light commercial system.
- Do not paint whole default sections bright violet; keep saturation in actions, bounded media and localized light.
- Do not replace 14px terminal-style chapter markers with widely tracked luxury-serif labels.
- Do not apply soft floating shadows and rounded corners to the square paper-card variant; its offset backing is rigid.
- Do not enlarge explanatory copy to match the headlines; the characteristic contrast is 56px titles against 16px descriptions.
- Do not lay colorful abstract art behind long text; it is a bounded backing for the product object.
- Do not reuse the compact directory-and-terminal footer as a random feature card in an ordinary dark chapter.

## Motion and responsive

### Motion

**Observed:**

- Dark navigation links declare hover color #ffffff with no underline. The default text uses white at 80%.
- Sticky navigation and a sticky opening text group coexist with perspective transforms on product panels.

**Transfer:**

- Keep the illuminated product composition legible as a still scene. If adding depth movement, preserve the text/action hierarchy and bounded product frame.

**Unknown:**

- No action transition timing or running keyframe sequence is established.
- Exact scroll-linked trajectories, duration and easing are unknown.

### Responsive

**Observed:**

- Desktop composition uses a 1024px main stage; the light variant uses a 1280px stage.
- Styles declare width boundaries around 810px and 1200px, with an additional 1600px boundary in the light variants.

**Transfer:**

- On narrow screens, retain the title-above-product composition and bring the glow behind the reduced product window rather than behind the text.
- Stack paired detail panels and plan windows; collapse four-column proof grids while keeping ticket art attached to its card.
- Keep photographic collage pieces at the outer edges or reduce their extent so they cannot overlap offer text.

**Unknown:**

- Mobile type sizes, exact grid breakpoints and mobile navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
