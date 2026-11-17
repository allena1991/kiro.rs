# Agiloft — intelligence in flowing lines

## Overview

An editorial enterprise style that pairs delicate, oversized serif promises with practical grotesk explanations and interface demonstrations. Black and blue-black stages alternate with white and warm paper, punctuated by orange rules and pale blue product backings. Thin routed lines, geometric data illustrations and monumental brand lettering give spacious software storytelling an architectural character.

### Essentials

- Delicate promises, practical explanations: Teodor 200 at 88px/1.05 with -0.01em tracking leads the opening; Messinasansweb 16px/1.5 carries the detail.
- The opening is a centered black theater rather than a conventional split hero: a 912px headline measure, 656px support measure, white 54px action, then tabs and a 1232px-wide pale-blue interface stage entering the first screen.
- Actions are crisp rectangular blocks, not capsules: 14px 24px padding, 1px matching borders and 54px height; white on dark stages and near-black on light sections.
- Color lives in punctuation and demonstration backings: #f9922f actions and #ee7501 rules against predominantly white, cream, black and #141c25 bands; reserve broad orange for treated imagery rather than the page canvas.
- Information feels physically connected: thin flowing SVG routes bend between horizontal runs behind text and media, while orange 2–4px progress rules anchor tabs and proof. Include this routed-line device even when the product has no native visual asset.
- Product interfaces are staged as white fragments on pale-blue or warm neutral rectangular fields, never buried in generic device mockups; a clean reconstruction of one useful workflow is the fallback.
- The ending is a brand-scale statement: a black footer combines a 48px light serif positioning line, small uppercase navigation and an oversized own-brand word sculpture across a 1232px field at 0.15 opacity.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ee7501` | `--color-orange-line` | accent, border | Progress lines, stat underlines, routed paths and orange action hover. |
| Action orange | `#f9922f` | `--color-orange` | action, link, text, accent | Announcement strip, accent headline words, orange actions and link highlights. |
| Story blue | `#7799c3` | `--color-story-edge` | border | Top edge on the customer story panel. |
| Product ice | `#d6e8ff` | `--color-blue` | surface | Marketing backings for interfaces and highlighted recognition cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, surface, action | Default reading canvas, interface fragments and reversed actions. |
| Trust blue-gray | `#afbfd3` | `--color-trust` | text | Small trust captions on the closing blue-black band. |
| Slate line | `#485768` | `--color-slate` | border, text | Edges on dark stages and muted proof text. |
| Stage black | `#000000` | `--color-black` | background, text | Opening theater, footer and immersive product chapters. |
| Integration black | `#080808` | `--color-integration-black` | background | Connection-network stage. |
| Near-black ink | `#0d0d0d` | `--color-ink` | text, action, background | Primary light-surface text, dark buttons and inset dark calls. |
| Blue-black | `#141c25` | `--color-navy` | background | Capability bands and the default closing call. |
| Question ink | `#1f2832` | `--color-question-ink` | text | Accordion questions. |
| Dark separator | `#3c3c3c` | `--color-dark-rule` | border, text | Footer separators and integration dividers. |
| Reading gray | `#606060` | `--color-secondary` | text, border | Secondary copy on light backgrounds and tab baselines. |
| Inactive label | `#979797` | `--color-inactive` | text | Inactive tabs. |
| Footer muted | `#999996` | `--color-footer-muted` | text | Visible result of rgba(255,255,250,0.6) on black; tertiary navigation only. |
| Feature stone | `#d7d4cb` | `--color-feature-stone` | surface, border | Compact benefit tiles and warm tab dividers. |
| Reverse secondary | `#dedede` | `--color-reverse-secondary` | text, border | Supporting copy on dark surfaces; hairline article separators on white. |
| Panel stone | `#edeae1` | `--color-stone` | surface | Tabbed demonstration panels and category tags. |
| Warm paper | `#f6f3ea` | `--color-paper` | surface, background | Default warm product panels, customer story cards and light platform opening. |
| Proof gray | `#f6f6f6` | `--color-soft-gray` | background | Large illustrated recognition band. |
| Question paper | `#faf8f1` | `--color-faq-paper` | background | Wide two-column question sections. |
| Chapter cream | `#fbf8f1` | `--color-cream` | background | Solution opening, warm capability chapters and plan sections. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| immersive AI product storytelling | Ember glow | `#532900` | `--color-ember-glow` | accent | Soft brown-orange light on black, built from rgba(238,117,1,0.37), blurred and faded; not a flat fill. |
| lead-generation pricing openings | Pricing slate | `#485867` | `--color-pricing-slate` | background | Dimmed interface collage behind the lead form. |
| solution capability grids | Raised navy | `#2c3947` | `--color-card-navy` | surface | Capability cards within blue-black bands. |
| self-service pricing sections | Plan edge | `#e5e5e5` | `--color-plan-edge` | border | Plan-card outlines. |
| lead-generation pricing pages | Pricing cream | `#fffbed` | `--color-pricing-cream` | background, surface | Pricing proof cards and expanded included-features panel. |

## Typography

- **Messinasansweb** — Body copy, navigation, labels and actions; the Book cut shares this family role. Understated contemporary grotesk, compact but readable, with open counters and restrained weight contrast. If unavailable, use **Inter**. Use regular and semibold; preserve tight label tracking. Font stack: "Messinasansweb", "Inter", Arial, sans-serif.
- **Teodor** — Display promises, section headings, editorial titles and proof numerals; Light is the same family role. Fine high-contrast editorial serif with generous round forms, sharp hairlines and a light, literary presence. If unavailable, use **Cormorant Garamond**. Use 300 as the light substitute and tune measure to retain broad headline lines. Font stack: "Teodor", "Cormorant Garamond", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Teodor | 200 | 88px | 1.05 | -0.01em, capitalize | Default centered opening headline. |
| heading-lg | Teodor | 200 | 64px | 1.1 | normal | Primary section promises and closing call. |
| stat | Teodor | 300 | 64px | 1 | -0.0313em | Supporting proof numerals with an orange underline. |
| heading | Teodor | 200 | 56px | 1 | -0.02em | Split feature headings and light-theme product or solution openings. |
| footer-positioning | Teodor | 200 | 48px | 1 | -0.0417em | Two-tone footer positioning statement. |
| panel-heading | Teodor | 200 | 40px | 1.1 | -0.028em | Heading within a tabbed product panel. |
| quote | Messinasansweb | 400 | 28px | 1.4 | -0.02em | Prominent customer endorsement next to proof numerals. |
| article-title | Teodor | 200 | 28px | 1.1 | -0.04em | Editorial list titles. |
| intro | Messinasansweb | 400 | 18px | 1.5 | -0.01em | Opening support line. |
| support | Messinasansweb | 400 | 18px | 1.5 | -0.02em | Closing support and solution introductions. |
| question | Messinasansweb | 600 | 18px | 1.72 | -0.02em | Accordion question labels. |
| body | Messinasansweb | 400 | 16px | 1.5 | normal | Default paragraphs and regular-weight actions. |
| button-strong | Messinasansweb | 600 | 16px | 1.5 | normal | White hero action and self-service conversion actions. |
| tab | Messinasansweb | 400 | 16px | 1.2 | -0.03em | Horizontal product tabs. |
| answer | Messinasansweb | 400 | 16px | 1.4 | -0.02em | Accordion answers and compact benefit copy. |
| navigation | Messinasansweb | 400 | 14px | 1.5 | -0.028em | Compact main navigation. |
| footer-link | Messinasansweb | 400 | 14px | 1.4 | -0.01em | Dense tertiary navigation. |
| eyebrow | Messinasansweb | 400 | 12px | 1.5 | 0.05em, uppercase | Small chapter identifier above a serif promise. |
| tag | Messinasansweb | 600 | 12px | 1.5 | normal, uppercase | Compact article category tags. |
| footer-label | Messinasansweb | 600 | 12px | 1.1 | -0.02em, uppercase | Footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| platform and solution question sections | faq-heading | Teodor | 300 | 68px | 1.1 | -0.02em | Large left-hand heading in a two-column objection-handling section. |
| immersive AI product openings | product-display | Teodor | 200 | 64px | 1.1 | -0.01em | Smaller centered headline over a framed product scene. |
| self-service pricing sections | plan-title | Teodor | 200 | 48px | 1.1 | -0.0233em | Plan names. |
| lead-generation pricing pages | pricing-heading | Teodor | 200 | 48px | 1 | -0.0208em | Centered pricing proof and included-features headings. |
| lead-generation pricing openings | form-heading | Teodor | 200 | 28px | 1.2 | normal | Centered heading inside lead form. |

**Notes:**

- Serif headlines stay light even on black. Contrast comes from scale and line breaks, not bold weight.
- Keep sans text comparatively small: the 88px opening drops to 18px support, then 16px actions and tabs.
- The Book and Light declarations are family cuts, not invitations to add extra unrelated text faces. Use the core body and heading recipes when a near-identical role is needed.

## Layout

**Density:** Airy editorial bands with compact labels and deliberately sparse product demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-label and category-tag gaps. |
| 16px | Compact text stacks and plan-grid gutters. |
| 20px | Heading-to-support separation and article-card stacks. |
| 24px | Action groups, tab gaps and proof-card gutters. |
| 32px | Card content groups and trust-caption-to-logo spacing. |
| 40px | Support-to-action separation and compact tile padding. |
| 64px | Hero action-to-tabs gap and major internal section groups. |
| 80px | Opening top padding and broad header-to-demonstration separation. |
| 100px | Split capability chapter vertical padding. |
| 112px | Large section vertical padding. |
| 160px | Separation between customer story and quantified proof. |

### Containers and grids

- **content**: max width 1232px · side padding 72px. Centered desktop container. At 1440px the max width produces 104px visible side margins; full-bleed backgrounds and routes extend outside it.
- **hero measure**: max width 912px. Centered headline over a 656px support block; the visual below spans the full content width.
- **split stage**: 2 columns · gap 64px. Broad product demonstration beside a narrower editorial promise; media and text are not forced into identical widths.
- **benefit grid**: 4 columns · gap 16px. 296px-wide compact benefit tiles.
- **proof grid**: 3 columns · gap 20px. Equal recognition cards, with one pale-blue card leading the group.
- **plans** (only for self-service pricing sections): 3 columns · gap 16px. 400px-wide aligned plan cards.
- **questions** (only for platform and solution question sections): max width 1232px · 2 columns · gap 40px. 493px headline column opposite a 643px accordion; align to the top.
- **lead form** (only for lead-generation pricing openings): max width 500px · side padding 32px. Single centered white card with a 436px form interior.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and editorial cards | 0px |
| immersive AI product demonstrations | framed product glass | 8px |
| self-service pricing controls | plan select | 8px |
| lead-generation pricing proof | pricing testimonial | 1px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| lead-generation pricing proof | pricing proof | `0px 4px 16px 0px rgba(0, 0, 0, 0.04)` | Very soft lift on cream testimonial cards. |

### Surfaces

#### Reading canvas · level 0

**Use:** Main editorial content.

**CSS:** `background: #ffffff; color: #0d0d0d`

#### Black theater · level 0

**Use:** Hero, connection network and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Broad uninterrupted fields; white content and subtle hairlines provide structure rather than floating cards.

#### Blue-black chapter · level 0

**Use:** Business capability bands and default closing call.

**CSS:** `background: #141c25; color: #ffffff`

#### Warm product panel · level 1

**Use:** Tabbed feature explanation.

**CSS:** `background: #edeae1; overflow: hidden; border-radius: 0px`

**Observed:** A compact serif story at left and an oversized interface fragment at right share one flat panel.

#### Pale-blue demonstration · level 1

**Use:** Interface backing and highlighted proof.

**CSS:** `background: #d6e8ff; overflow: hidden`

**Observed:** Cool, softly textured illustration fields with faint stepped linework; interfaces remain white.

#### Warm chapter · level 0

**Use:** Light product chapters and plan sections.

**CSS:** `background: #fbf8f1; color: #0d0d0d`

#### Question band · level 0

**Use:** Two-column objection handling.

**CSS:** `background: #faf8f1; color: #0d0d0d`

#### Dark capability card · level 1

**Only for:** solution capability grids

**Use:** Grouped product capabilities within blue-black bands.

**CSS:** `background: #2c3947; padding: 36px 32px 0px; overflow: hidden`

**Observed:** Pale-blue top rule, short sans title and support, then a white interface fragment cut off by the lower edge.

#### Ember light · level 1

**Only for:** immersive AI product storytelling

**Use:** Atmosphere behind isolated interface fragments.

**CSS:** `background: rgba(238, 117, 1, 0.37); filter: blur(100px); border-radius: 50%; opacity: 0.943901`

**Observed:** Wide low elliptical light pools on black, not bright multicolor gradients.

**Transfer:** Keep the luminous center behind the demonstration and away from reading copy; match the soft glow rather than chasing exact stops.

## Components

### Primary button

**Use:** Default main action on the black opening.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; background: #ffffff; color: #0d0d0d; border: 1px solid #ffffff; border-radius: 0px; padding: 14px 24px; height: 54px`

**Text style:** `button-strong` — Messinasansweb 600 · 16px/1.5

**Observed:** Centered label; arrowless in the opening. On ordinary dark feature and closing bands the same white construction uses regular-weight text.

**States:** Declared: hover border-color #f9922f, color #0d0d0d, transform scale(0.975); active transform scale(0.965).

### Dark button

**Use:** Primary action on light editorial surfaces.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; background: #0d0d0d; color: #ffffff; border: 1px solid #0d0d0d; padding: 14px 24px; height: 54px; border-radius: 0px`

**Text style:** `body` — Messinasansweb 400 · 16px/1.5

**Observed:** Often ends with a thin northeast arrow. Orange-filled variants serve product signup and selected solution calls; their background and border are action orange and their text is ink.

**States:** Declared: hover border-color #f9922f, color #0d0d0d, transform scale(0.975); active transform scale(0.965). Orange variant hover background-color and border-color #ee7501.

### Navigation

**Use:** Persistent orientation across marketing chapters.

**CSS:** `background: #000000; color: #ffffff; height: 69px; box-shadow: 0px 1px 0px 0px #485768`

**Text style:** `navigation` — Messinasansweb 400 · 14px/1.5 · tracking -0.028em

**Observed:** Brand at left, compact center link group with small downward chevrons, 40px white demo action at right. A 33px orange announcement strip sits above it. Light product and solution themes reverse the bar to white or cream with dark text; lead-generation openings instead use a centered brand mark.

**Transfer:** Keep the compact utility strip subordinate to the expansive hero.

### Product tabs

**Use:** Switching product demonstrations without a wall of cards.

**CSS:** `display: flex; gap: 24px; padding: 0px 24px; max-width: 606px; border-bottom: 1px solid #606060`

**Text style:** `tab` — Messinasansweb 400 · 16px/1.2 · tracking -0.03em

**Observed:** Centered above the wide opening media. Each item pairs a small icon with text and has bottom clearance; an orange progress underline marks the active tab. Light editorial variants stretch across the container and can prefix labels with two-digit numbers.

**States:** Declared: hover label color #606060; focus-visible outline rgb(77, 101, 255) solid 2px, outline-offset 2px.

### Customer story panel

**Use:** Customer proof beside a video or portrait-based story.

**CSS:** `background: #f6f3ea; border-top: 4px solid #7799c3; padding: 60px; max-width: 484px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px`

**Text style:** `body` — Messinasansweb 400 · 16px/1.5

**Observed:** Customer logo at the top and a short outcome statement anchored low; adjoining landscape video occupies the larger share. A horizontal row of customer logos above acts as tabs.

**Transfer:** Use a genuine customer story with the same sparse top-to-bottom distribution.

### Article row

**Use:** Editorial resources without a thumbnail-card wall.

**CSS:** `border-top: 1px solid #dedede; padding: 40px 12px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `article-title` — Teodor 200 · 28px/1.1 · tracking -0.04em

**Observed:** Category tags and date precede the serif title, then a short gray summary; the entire row is linked. Rows sit to the right of a large heading and action, separated by a vertical hairline.

### Category tag

**Use:** Small editorial taxonomy.

**CSS:** `background: #edeae1; color: #000000; padding: 8px 12px; border-radius: 0px`

**Text style:** `tag` — Messinasansweb 600 · 12px/1.5 · uppercase

**Observed:** Compact flat labels beside dates; multiple tags wrap with small gaps.

### Question accordion

**Use:** Objection handling on a warm reading band.

**CSS:** `display: flex; flex-direction: column; border-bottom: 1px solid rgba(0, 0, 0, 0.15)`

**Text style:** `question` — Messinasansweb 600 · 18px/1.72 · tracking -0.02em

**Observed:** Question at left, small chevron at right, answer beneath in the answer recipe. The wide split variant has no enclosing card. The centered self-service variant uses a 795px list; its active white item has an 8px inset frame and a soft inset shadow.

**Transfer:** Keep questions concrete and open one relevant answer by default.

### Footer navigation

**Use:** Dense navigation beneath the closing statement.

**CSS:** `display: flex; flex-direction: column; gap: 12px; color: rgba(255, 255, 250, 0.6)`

**Text style:** `footer-link` — Messinasansweb 400 · 14px/1.4 · tracking -0.01em

**Observed:** Four narrow navigation columns sit beside a broader brand column. Small uppercase headings and subtle horizontal and vertical rules organize the links. A lower legal strip precedes the giant dark wordmark.

**States:** Declared: hover color #f9922f; color transition 0.2s.

### Assistant icon tile

**Use:** Alternative discovery actions in the footer brand column.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 44px; height: 44px; background: rgba(255, 255, 255, 0.05)`

**Observed:** Five small square tiles form a row beneath a two-line invitation to explore through an assistant. Separate social tiles above use white backgrounds; the graphic icons are small and monochrome.

**States:** Declared: hover color #0d0d0d; orange pseudo-element background; color transition 0.2s.

**Transfer:** Use relevant discovery or community destinations for the new product, preserving the square tile row.

### Plan card

**Only for:** self-service pricing sections

**Use:** Comparing a small set of adoption levels.

**CSS:** `background: #ffffff; border: 1px solid #e5e5e5; padding: 16px; display: flex; flex-direction: column`

**Text style:** `plan-title` — Teodor 200 · 48px/1.1 · tracking -0.0233em

**Observed:** Large serif plan name, small gray description, price, thin divider or usage selector, concise bullet list, then full-width dark button anchored to the bottom. Three equal cards share a cream band; no exaggerated recommended-plan badge.

### Lead input

**Only for:** lead-generation pricing openings

**Use:** Compact inquiry form.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.3); height: 40px; padding: 10px 16px; border-radius: 0px`

**Observed:** Email is full width, followed by paired identity and organization fields and full-width selects. The white form card uses a small centered serif heading and black full-width submit action.

## Imagery and graphics

### Routed intelligence lines

**Use:** Required connective graphic across the opening and at least one later chapter.

**Observed:** Long hairline paths run horizontally, slope through broad rounded bends and return to parallel tracks. Orange and muted gray versions pass behind content, bleed beyond the viewport and occasionally terminate in tiny squares or dots.

**Transfer:** Use paths to imply flow between product inputs and outcomes; keep them subordinate to the serif language.

**Build:** Use an oversized SVG with no fill and 1px strokes. Draw two or three parallel paths with horizontal runs, diagonal transitions and quadratic rounded corners. Use #ee7501 at low opacity on white, #485768 at low opacity on black; add a 4px orange square at selected ends. Clip to the section and route around the reading area.

### Interface fragments

**Use:** Primary visual proof in the opening, tabs and capabilities.

**Observed:** White workflow, approval, search and analysis fragments float on pale-blue, stone or orange-backed rectangular stages. The scene is much larger than individual text; portions of interfaces extend beyond the frame. Fine stepped grids and mild texture soften the backing.

**Transfer:** Reconstruct one meaningful action with a few real-looking rows or controls. If native interface media is unavailable, use a clean white process panel and a result card rather than a blank frame.

**Build:** Place a flat pale-blue or warm panel behind two white UI fragments, one larger and one offset. Add low-opacity routed grid lines beneath them, clip the stage, and keep the media's internal color subordinate to its white surfaces.

### Geometric data sculpture

**Use:** Abstract explanation of a product's connected architecture.

**Observed:** Fine orange isometric cubes and lattices, mostly outline with a few solid orange faces, occupy broad white or cream fields. A vertical orange spine with square endpoints can connect short explanatory groups around the central object.

**Transfer:** Represent the new product with a small family of connected geometric modules; the minimum version is five outlined isometric boxes surrounding one central module.

**Build:** Draw SVG isometric diamonds and vertical edges with 1px #ee7501 strokes at restrained opacity. Repeat modules with offset coordinates; fill one central face with #f6f3ea and one emphasis module with #f9922f. Add a 2px vertical spine and small square endpoints, leaving text outside the object.

### Professional photography

**Use:** Audience, industry and customer context.

**Observed:** Candid working people and industrial settings use generous rectangular framing. Industry carousel photographs are grayscale and portrait-proportioned; audience chapters use landscape imagery strongly washed in golden orange. Captions remain outside the image or on a small white lower-left tab.

**Transfer:** Use work-in-context images, not isolated stock portraits; keep either the grayscale carousel treatment or the orange chapter treatment according to context.

### Ruler carousel

**Use:** Navigable image-based exploration.

**Observed:** Tall grayscale image cards overflow both sides of a full-width track. Square arrow controls sit above at right. A thin baseline underneath carries dense short ticks, occasional taller ticks and an orange diamond progress marker.

**Transfer:** Keep the ruler and monochrome photography for a new set of audience or use-case categories.

**Build:** Use a horizontal SVG baseline with 1px neutral ticks every 14px, every fifth tick taller. Position an orange 8px diamond above the active tick. Render portrait cards about 411px by 513px with 20px gaps and white inset caption tabs.

### Closing data horizon

**Use:** Low-intensity graphic beneath the default closing call.

**Observed:** A 172px-high full-width field of faint horizontal tracks and staggered gray and brown-orange bars sits at the bottom of the blue-black call; the graphic is subdued at 0.16 opacity.

**Transfer:** Make a quiet data horizon that grounds the call without competing with the action.

**Build:** In an SVG spanning the section, draw parallel horizontal 1px slate lines and sparse short rectangular bars at varied lengths. Mix #afbfd3 and #ee7501, apply 0.16 opacity to the group and clip to a 172px-high strip.

### Monumental word sculpture

**Use:** Required final brand-scale gesture below footer utilities.

**Observed:** An own-brand logotype spans 1232px by roughly 416px on black at 0.15 opacity, appearing as dark gray typography rather than a bright sign.

**Transfer:** Use the new brand's own wordmark or a bold typeset name sized to fill the width; retain the monumental low-contrast silhouette.

**Build:** Place an SVG wordmark or heavy sans text below the legal row, width 100% of the content container, white fill with opacity 0.15 and 60px top separation. Scale its height to its natural letter proportions.

### Ember route and portal

**Only for:** immersive AI product storytelling

**Use:** A dark product timeline and inset closing conversion scene.

**Observed:** Orange paths trace a sequence of isolated UI outcomes over black, with warm blurred pools behind white fragments. The closing panel places serif copy left and a fine perspective grid curving into a glowing orange doorway at right.

**Transfer:** Keep the connected route and the warm point of arrival rather than replacing this look with a generic purple AI gradient.

**Build:** For the timeline, use a 1px orange SVG route with rounded rectangular turns, small endpoint dots, and blurred orange ellipses behind UI cards. For the portal, draw a perspective grid of many thin orange curves converging at the right edge; layer a narrow bright orange rectangle and a broad rgba(238,117,1,0.2) glow blurred 104px behind it, fading into the black panel.

### Dimmed interface collage

**Only for:** lead-generation pricing openings

**Use:** Backdrop to a focused inquiry form.

**Observed:** Large product panels hover near the edges of a slate-blue field, heavily dimmed. A subtle warm halo sits behind the centered white form, with a monochrome customer logo row near the bottom.

**Transfer:** Use a few low-contrast fragments from the new product around the periphery, leaving the form as the only high-contrast object.

### Icons

**Observed:** Small monochrome SVGs: 10px by 6px filled dropdown chevrons, 13px thin northeast arrows, 20–24px utility and capability symbols, and approximately 19px social or assistant marks centered in 44px squares.

**Transfer:** Choose spare line symbols for workflows and filled marks for destinations. Use orange only for active states, with white or slate on dark surfaces.

## Section recipes

How recurring sections are built.

### First screen: Black product theater opening

**Observed:** A 33px orange announcement and 69px black navigation establish a shallow utility layer. The black hero begins with 80px top clearance. A centered 88px light serif headline spans about two thirds of the viewport in three lines, followed after 20px by a two-line 18px gray support statement and after 40px by the Primary button. Fine routed paths run behind the text's outer edges and bend toward the media. After 64px, Product tabs sit above a 1232px by 514px pale-blue demonstration. Within the first 900px the complete headline, support, action, tabs and upper portion of the product scene are visible; the rest of the scene and logo strip sit below the fold.

**Transfer:** Give another product one expansive outcome promise and one concrete interface or process demonstration. Without native media, build the Interface fragments recipe. Light product overviews use a 56px centered promise on warm paper over a landscape video; solution pages use the same 56px recipe in a left column beside a square demonstration. Immersive AI launches use the 64px product-display recipe, paired orange and white actions, and a framed dark media stage. Lead-generation pricing opens with the centered Lead input form instead of the marketing navigation.

**Avoid:** Do not compress the opening into a short banner, substitute a bold sans headline, or place a tiny product thumbnail beside the headline.

**Text style:** `display` — Teodor 200 · 88px/1.05 · tracking -0.01em · capitalize

### Eyebrow and promise

**Observed:** A 12px uppercase eyebrow with a short orange rule precedes a 64px serif heading; body support is constrained beneath it and the Dark button follows after 40px. Routed lines occupy the open side of the section.

**Transfer:** Use a short category label and an outcome-led promise, allowing the visual to take the next full-width panel.

**Text style:** `heading-lg` — Teodor 200 · 64px/1.1

### Tabbed product panel

**Observed:** Product tabs sit on a thin baseline above the Warm product panel. The left story occupies roughly 507px and separates its serif heading from low-anchored support; the right media occupies roughly 725px. The combined panel spans the content container.

**Transfer:** Give each tab a meaningful outcome and one distinct demonstration rather than repeating generic feature cards.

**Text style:** `panel-heading` — Teodor 200 · 40px/1.1 · tracking -0.028em

### Dark split capability

**Observed:** Blue-black chapter uses 100px vertical padding, a large pale-blue product scene on one side and a 56px white serif heading, gray support, Primary button and compact tabs on the other. Flow lines remain behind the content.

**Transfer:** Alternate media and text orientation where needed while retaining the same contrast and image scale.

**Text style:** `heading` — Teodor 200 · 56px/1 · tracking -0.02em

### Proof with orange rules

**Observed:** Recognition alternates between a wide illustrated gray band and three-card groups on cream. Pale blue marks the leading credential. Large serif numerals and headings sit above orange underlines and small captions; customer proof pairs the Customer story panel with landscape media, then a separate stat-and-quote composition.

**Transfer:** Use credible evidence in the same hierarchy: institution or outcome first, short caption second, with one orange line to anchor each unit.

**Text style:** `stat` — Teodor 300 · 64px/1 · tracking -0.0313em

### Architecture spine

**Observed:** A centered 56px serif introduction and action lead into a spacious geometric sculpture on white. A thin orange vertical spine and square endpoints organize alternating side explanations with small sans headings and gray body text.

**Transfer:** Adapt the diagram to the new product's conceptual architecture; preserve the open central field and the contrast between sparse geometry and short practical explanations.

### Editorial index and image exploration

**Observed:** The Ruler carousel presents grayscale categories in an edge-clipped track. A separate editorial index puts a large serif heading and Dark button on the left and stacked Article rows on the right, divided by a hairline.

**Transfer:** Use the carousel for visual categories and the index for reading content; do not force both into identical card grids.

### Default closing call and footer

**Observed:** Blue-black chapter centers a two-line 64px serif call on a roughly 657px measure with 18px support constrained to 480px, a white Primary button, then a trust caption and three logos separated by vertical rules. Closing data horizon sits low behind generous clearance. Black footer follows with 80px top padding, Footer navigation beside a wider brand column, social tiles and Assistant icon tiles. A ruled legal strip precedes the Monumental word sculpture.

**Transfer:** Close with a decisive outcome and one action, then let the brand-scale footer finish the experience. A lead-generation page can pass from its connection stage directly into this footer. Immersive AI product pages use the inset Ember route and portal call before the same footer.

**Text style:** `heading-lg` — Teodor 200 · 64px/1.1

### Audience chapters

**Only for:** multi-audience platform overviews

**Observed:** A blue-black band holds a sticky left introduction and vertical icon navigation. The right column scrolls through 657px-wide landscape orange-treated photographs, a 24px semibold title and short gray description. Active navigation receives an orange vertical marker.

**Transfer:** Use one chapter per genuinely different audience, maintaining the warm photo treatment and repeated visual proportion.

### Question split

**Only for:** platform and solution question sections

**Observed:** Question band has 112px vertical padding, a large 68px light serif heading in a 493px left column and Question accordion in a 643px right column. A highlighted first word can use action orange.

**Transfer:** Answer practical fit, adoption and integration objections. Self-service product pages instead center a smaller serif introduction above the single-column accordion.

**Text style:** `faq-heading` — Teodor 300 · 68px/1.1 · tracking -0.02em

### Pricing comparisons

**Only for:** self-service pricing sections

**Observed:** Warm chapter with centered 64px serif promise, small uppercase eyebrow and three aligned Plan cards with 16px gutters. White cards keep their dark actions aligned along the bottom.

**Transfer:** Let the names and included capacity explain progression without importing a saturated recommended-plan treatment.

**Text style:** `heading-lg` — Teodor 200 · 64px/1.1

## Page flow

**Storyline:** Promise → concrete demonstration → credibility → capability and audience chapters → adoption or objection handling → decisive call → monumental brand ending.

### Broad marketing landing page that introduces a platform and its value

1. **Promise** — Black product theater with centered editorial headline and tabbed demonstration.
2. **Social proof** — Compact logo strip, illustrated recognition band and customer story with quantified proof.
3. **Capability chapters** — Light tabbed product narrative, dark split demonstration and black connection-network stage.
4. **Conceptual explanation** — Geometric architecture spine on white.
5. **Exploration** — Grayscale ruler carousel and editorial index.
6. **Closing call** — Centered blue-black conversion band and black monumental footer.

**Transfer:** Use the contrasts and evidence hierarchy as a flexible narrative, not a fixed section count.

### Lead-generation pricing page focused on starting a sales conversation

1. **Conversion** — Centered white inquiry form over a dim slate interface collage; no full marketing navigation.
2. **Quantified proof** — Three cream testimonial cards with orange serif figures.
3. **Benefits** — Black benefit area with one wide expanded card and narrow adjacent headings.
4. **Objection handling** — Included-features accordion with a warm expanded panel.
5. **Compatibility proof** — Dark connection stage with logo tiles and short feature columns.
6. **Brand ending** — Shared black footer and giant low-contrast wordmark; no separate blue-black call.

**Transfer:** Make inquiry friction low and surround the form with evidence, benefits and scope clarity.

### Role-specific solution page translating platform capabilities into practical outcomes

1. **Promise** — Cream split hero with eyebrow, 56px serif promise and square interface scene.
2. **Problem framing** — Orange-treated work photograph beside a warm story card with an orange top rule.
3. **Capability demonstration** — Blue-black band with explanation at left and staggered navy interface cards at right.
4. **Benefits** — Four stone tiles, followed by a three-card credential group.
5. **Education** — Resource grid and warm two-column questions.
6. **Closing call** — Role-specific blue-black call followed by shared monumental footer.

**Transfer:** Ground the opening in the audience's pressures, then prove specific workflows before handling adoption questions.

### Self-service AI product launch with immersive explanation and adoption choices

1. **Promise** — Black 64px centered serif opening with paired signup and login actions and framed media.
2. **Problem framing** — Sparse dark narrative connected by thin orange routes.
3. **Product demonstration** — Large framed video followed by cream feature accordion and layered interface fragments.
4. **Outcome chapters** — Orange checkpoint labels and white UI fragments follow a routed timeline with ember glows.
5. **Trust and adoption** — White trust chapter, customer quote and cream three-plan comparison.
6. **Objection handling** — Centered white accordion with inset active item.
7. **Closing call** — Inset glowing portal scene followed by shared black footer.

**Transfer:** Scope the immersive glow treatment to a flagship launch and balance it with practical trust and pricing information.

### Platform overview combining architecture, proof and audience fit

1. **Promise** — Warm centered 56px heading above a broad orange-treated landscape video.
2. **Credibility** — Logo strip and pale-blue recognition card beside navy stat panels.
3. **Reframing** — Blue-black two-column editorial statement over stepped linework.
4. **Capability chapters** — Cream introduction beside stacked architecture cards.
5. **Audience fit** — Long blue-black chapter with sticky audience index and orange-treated work scenes.
6. **Objection handling** — Cream split FAQ.
7. **Closing call** — Centered blue-black call and shared monumental footer.

**Transfer:** Use repeated audience chapters only when the platform genuinely serves several roles; keep architecture concrete.

## Writing

Confident, commercially literate and outcome-led, with a light editorial touch. It moves between expansive business promises and plain descriptions of everyday work rather than sounding like a technical specification.

**Do not copy:** Do not reuse Agiloft or Astra names, logos, customer or analyst marks, proprietary phrases, awards, percentages, pricing, security promises or testimonials. Supply the new product's own verified claims and assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to teams through you and your; use we sparingly when offering help. Product-led descriptions explain what the platform does before asking for commitment.
- **Rhythm:** Headlines combine short imperative clauses or a before-and-after contrast. Support is usually one compact paragraph; capability copy favors short sentences and concrete verbs. Calls to action are brief and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Turn a familiar operational object into a strategic outcome. | 7–14 words | “Turn Contracts Into Catalysts For Growth” |
| Section promise | Contrast routine management with higher-value use. | 5–10 words | “Stop managing contracts. Start leveraging them.”<br>“Too much process. Not enough progress.” |
| Supporting line | Name real actions in a parallel verb sequence, then connect them to the outcome. | 20–40 words | “Ask questions, review contracts, uncover risk, and make every contract improve the next with AI that works the way contract teams actually need it to.” |
| Capability label | Verb plus a practical improvement, avoiding vague feature names. | 3–6 words | “Compare terms with less friction”<br>“Customization without technical hassles” |
| Action | Literal verb and destination or commitment. | 2–4 words | “Schedule a Demo”<br>“Read the Report”<br>“Join free” |

**Words and phrasing to use:** turn into; visibility; business value; structured data; workflows; standards; point-and-click; faster; measurable outcomes

**Avoid:** magic; revolutionary; disrupt everything; effortless perfection; supercharge; excessive exclamation marks

**Rules:**

- Lead with the business improvement and then explain the mechanism.
- Use specific work nouns and verbs rather than a string of abstract AI adjectives.
- Keep proof captions terse and separate the numeral from its explanation.
- Match the action label to the actual next step; distinguish a demo request from self-service signup.
- Let a contrasting pair of clauses carry a major headline instead of stacking unrelated benefits.

## Do's and Don'ts

### Do

- Keep the opening headline at 88px/1.05 and weight 200 rather than increasing weight for emphasis.
- Use the 1232px desktop container to align text, media and footer rules.
- Carry fine routed paths into both opening and later content so the connective motif feels systemic.
- Use 54px rectangular actions with 14px 24px padding; compact header actions are 40px high.
- Pair 64px proof numerals with orange rules and small explanatory labels.
- Use 100px or 112px vertical chapter padding to preserve the expansive editorial rhythm.
- Finish with a giant low-contrast own-brand wordmark on black.
- Keep interface fragments white against pale-blue or warm neutral backing, with purposeful clipping.

### Don't

- Do not turn all section headings into bold grotesk text; the high-contrast light serif is the main voice.
- Do not make ordinary actions pill-shaped or add rounded corners to every panel.
- Do not wash the entire page in orange; neutral stages should dominate and broad orange belongs mainly to imagery.
- Do not flatten black, #080808 and #141c25 into one undifferentiated dark surface.
- Do not add generic floating shadows to the editorial panels; most surfaces are flat and ruled.
- Do not use rainbow gradients or purple neon to signal AI; the scoped immersive treatment is warm ember light.
- Do not replace the ruler carousel's portrait grayscale images with colorful rounded icon cards.
- Do not brighten the footer word sculpture to the same white as navigation; retain 0.15 opacity.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94) transitions, with hover scale 0.975 and active scale 0.965.
- Product tab progress declares 8s linear fills; the pricing logo marquee declares a 24s linear infinite animation.
- Footer links declare color 0.2s. Accordion question padding declares 0.5s cubic-bezier(0.215, 0.61, 0.355, 1).
- The scoped ember portal overlay declares a 3s ease-in infinite breathing animation.

**Transfer:**

- Keep tab progress on a thin orange line rather than animating the entire panel border.
- Use the restrained button contraction and routed visual continuity; keep editorial text settled and readable.

**Unknown:**

- Exact scroll-trigger choreography, full video sequences and route-drawing timings are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479/480px, 767/768px and 991/992px, with additional layout-specific thresholds.

**Transfer:**

- For narrow layouts, stack the editorial promise above the demonstration, preserving the routed path behind both.
- Let the word sculpture scale to the content width; keep its low contrast and natural letter proportions.
- Stack plans and split questions while retaining flat edges, orange rules and the distinction between serif promises and sans detail.

**Unknown:**

- Mobile type sizes, navigation behavior and exact breakpoint-specific stacking were not established; these transfer rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
