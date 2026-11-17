# Superwhisper — dusk-lit desktop theatre

## Overview

A predominantly black, cinematic software style with blue-to-violet dusk light, soft silver edges, and compact desktop-like controls. Inter grotesk typography stays modest beside atmospheric photography, floating interface fragments, and tactile feature illustrations. Spacious product chapters give way to denser proof, pricing, and resource areas; a pale editorial variant makes browsing feel lighter without losing the dark frame.

### Essentials

- A small promise inside a large scene: a centered two-line 48px/51px, weight-600 headline floats between dark edge-cropped subjects in a 900px-tall dusk opening, rather than filling the screen with type.
- Controls feel like a miniature desktop dock: the floating navigation is 410px × 41px with 18px gaps, 5px backdrop blur, a rounded capsule outline and a white 33px-high conversion control.
- Black is the connective tissue, not another card color: #000000 carries most of the long page; blue, violet and mauve occupy the opening and one theatrical proof band, with smaller pink, mint, red and blue accents confined to capability art and short labels.
- Show capabilities as little objects, not flat icon boxes: 320px × 400px cards have 24px corners, 24px padding, large upper illustrations and near-black tinted bases. Include a tactile control or layered interface vignette; when no product media exists, construct a switch, input or output fragment.
- Use dusk light as a signature device: a black-to-navy-to-violet-to-mauve field reappears behind layered proof or a highlighted offer. Preserve that atmospheric return even when the new product has no photographic assets.
- Proof has physical depth: white quotation cards sit inside translucent, slightly tilted stacked sheets, with 8px outer and 24px inner corners, while surrounding copy remains restrained.
- The ending deliberately becomes small and useful: leave 144px before the black footer, arrange six link columns with 40px gaps, then a faint top rule and a 290px × 44px pill email field. Do not replace this with a giant closing slogan.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight blue | `#00052e` | `--color-navy` | background | Dark upper portion of atmospheric gradient fields. |
| Dusk indigo | `#29285e` | `--color-violet-deep` | background | Middle-dark gradient field. |
| Dusk violet | `#543c7b` | `--color-violet` | background | Lower-middle atmospheric field. |
| Dusk mauve | `#855a92` | `--color-mauve` | background | Warm lower part of the dusk field. |
| Horizon rose | `#c386ab` | `--color-rose` | background | Bottom glow of the theatrical proof field. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0088ff` | `--color-blue` | accent, link | Capability labels, small icons and selected interaction details, not the default button fill. |
| Orchid | `#dd55e7` | `--color-pink` | accent, text | Capability eyebrow and isolated feature highlights. |
| Mint signal | `#1cecbb` | `--color-mint` | accent, text | One capability's heading and illustration detail. |
| Coral signal | `#ff5252` | `--color-red` | accent, text | One capability's heading and illustration detail. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text, action | Bright buttons, inset quotation sheets and high-contrast text. |
| Soft white | `#fafafa` | `--color-heading` | text | Primary headings and prominent prices. |
| Icy display white | `#e9feff` | `--color-ice` | text | Theatrical social-proof headline. |
| Silver body | `#c4c5c9` | `--color-body` | text | Readable secondary copy and questions. |
| Footer silver | `#b8babf` | `--color-footer-heading` | text | Small footer group headings. |
| Mid silver | `#888b91` | `--color-muted` | text, link | Descriptions, supporting lines and quiet links. |
| Low silver | `#70757c` | `--color-subtle` | text, link | Footer links, subdued half of a headline and compact descriptions. |
| Newsletter charcoal | `#1c1d24` | `--color-newsletter-start` | surface | Left edge of the newsletter field gradient. |
| Control charcoal | `#1c1d1f` | `--color-control` | surface, border, text | Dark pill actions and pricing-card outlines. |
| Newsletter graphite | `#1a1b20` | `--color-newsletter-end` | surface | Right edge of the newsletter field gradient. |
| Black-canvas hairline | `#1a1a1a` | `--color-edge` | border | Visible white-at-10% separator on black; use rgba(255,255,255,0.1) when the surface beneath varies. |
| Raised charcoal | `#0f0f10` | `--color-panel` | surface | Pricing, sales and closing panels. |
| Black canvas | `#000000` | `--color-canvas` | background, text | Default page ground and ink on white actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| sales-led pages | Input edge | `#262626` | `--color-form-edge` | border | Sales form field boundaries. |
| resource and workflow directories | Editorial paper | `#f5f5f7` | `--color-paper` | background | Continuous light reading and directory body, not isolated white sections on ordinary landing pages. |
| resource and workflow directories | Editorial ink | `#111827` | `--color-paper-ink` | text | Headings and tile titles on the light variant. |

## Typography

- **Inter** — All marketing headings, body copy, labels and navigation. Compact neutral grotesk with open counters; medium and semibold headings, regular descriptive text. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 600 | 48px | 51px | normal | Default centered opening promise and large integration statement. |
| proof-display | Inter | 600 | 48px | 1.07 | -0.0375em | Centered two-line headline over the atmospheric proof field. |
| heading | Inter | 600 | 31px | 1.2 | -0.04em | Standard section headings, left-aligned chapters and centered proof introductions. |
| body | Inter | 400 | 16px | 1.5 | normal | Main descriptions and supporting prose. |
| action | Inter | 500 | 16px | 1.5 | normal | Full-width conversion pills and medium-emphasis labels. |
| eyebrow | Inter | 500 | 14px | 20px | normal | Sentence-case colored capability labels. |
| navigation | Inter | 400 | 14px | 1.5 | -0.01em | Floating navigation and its compact conversion action. |
| small | Inter | 400 | 14px | 20px | normal | Footer links and secondary descriptions. |
| footer-label | Inter | 600 | 14px | 1 | normal | Footer column and newsletter headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing sections | price | Inter | 600 | 60px | 1 | -0.025em | Large price numeral or a short custom-price label. |
| customer proof directories | proof-page-display | Inter | 500 | 48px | 1.06 | -0.04em | Left-aligned proof-directory opening headline. |
| sales-led pages | enterprise-display | Inter | 600 | 48px | 51px | -0.04em | Narrow two-line sales-led opening headline. |
| resource and workflow directories | directory-display | Inter | 600 | 48px | 1.07 | -0.0333em | Editorial directory opening title. |
| customer proof directories | proof-stat | Inter | 500 | 31px | 1.1 | -0.04em | Compact headline statistics with smaller captions underneath. |
| sales-led pages | panel-heading | Inter | 500 | 24px | 1.25 | -0.02em | Title at the top of a sales form. |
| resource directories and sales-led pages | tile-title | Inter | 500 | 15px | 1.5 | normal | Directory tile title; also the compact question size in editorial and sales FAQs. |
| resource and workflow directories | tile-description | Inter | 400 | 13px | 1.5 | -0.01em | Two- or three-line directory tile descriptions. |

**Notes:**

- Default display type is not oversized: 48px, while most chapter headings are 31px. Tight -0.04em tracking belongs to section headings and scoped page titles; the opening display keeps normal tracking.
- Keep weight 400 for paragraphs, 500 for controls, and 600 for most headlines. Section eyebrows are usually sentence case, not widely tracked technical capitals.
- Use gray and white within one headline to isolate a decisive word or phrase, especially for integrations and tutorial titles; keep both parts on the same baseline and scale.

## Layout

**Density:** Airy at chapter scale and compact inside controls; black intervals separate dense product demonstrations, while forms and footer links remain tightly organized.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-heading gap and compact paired controls. |
| 12px | Editorial tile gutters and close vertical label spacing. |
| 16px | Body-to-detail gaps, compact card padding and icon group spacing. |
| 18px | Floating navigation gaps and closing-panel text groups. |
| 24px | Default card padding, outer side gutters and pricing gaps. |
| 32px | Pricing-card padding and heading-to-content intervals. |
| 40px | Footer grid gaps and tab-to-content intervals. |
| 48px | Section support-to-content gap and footer group separation. |
| 56px | Sales hero column separation. |
| 96px | Black inter-chapter breathing space and compact callout padding. |
| 128px | Page-title top padding and major pricing introduction space. |
| 144px | Footer separation from preceding content. |

### Containers and grids

- **marketing container**: max width 1024px · side padding 24px. Centered stage for most product chapters, proof directories and sales-led compositions.
- **reading column**: max width 700px · side padding 24px. Long-form capability descriptions, FAQs and directory sections.
- **footer container**: max width 1075px · 6 columns · gap 40px · side padding 24px. Footer frame with a brand/social row above evenly spaced link columns.
- **pricing row** (only for pricing sections): max width 1232px · 3 columns · gap 24px · side padding 16px. Three equal 384px-wide pricing cards extend wider than the ordinary marketing container.
- **directory tiles** (only for resource and workflow directories): max width 700px · 2 columns · gap 12px. Paired compact cards in a narrow editorial column.
- **sales hero** (only for sales-led pages): max width 1024px · 2 columns · gap 56px · side padding 24px. Flexible left text column and a 396px right form; both align at the top.
- **logo matrix** (only for customer proof directories): max width 1024px · 5 columns · gap 0px. Continuous bordered proof matrix with centered monochrome marks.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 9999px (pill) |
|  | feature and sales panels | 24px |
|  | media and accordion controls | 8px |
| pricing sections | pricing cards | 20px |
| resource and workflow directories | directory tiles | 12px |
| customer proof directories | trial actions | 9px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| quotation sheet | `0px 1px 4px 0px rgba(0,0,0,0.25), 0px 4px 59px 0px rgba(0,0,0,0.1)` | Bright inset proof cards. |
| translucent proof frame | `0px 0px 10px 0px rgba(0,0,0,0.3)` | Outer stacked testimonial sheets. |

### Surfaces

#### Black canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #000000; color: #fafafa`

**Observed:** The canvas continues between modules instead of becoming a grid of full-width colored bands.

**Transfer:** Let dark media edges dissolve into the canvas.

#### Dusk field · level 0

**Use:** Opening atmosphere and a theatrical proof return.

**CSS:** `background: linear-gradient(#000000 0px, #00052e 23%, #29285e 53%, #543c7b 73%, #855a92 88%, #c386ab 98%)`

**Observed:** Vertical midnight-to-mauve light, with a faint blue-to-violet lateral overlay; the upper edge merges with black.

**Transfer:** Keep the upper part much darker than the bottom; match the broad light field rather than making a rainbow.

#### Raised charcoal panel · level 1

**Use:** Contained calls to action and sales proof.

**CSS:** `background: #0f0f10; border-radius: 24px; border: 1px solid rgba(255,255,255,0.2)`

**Observed:** A brighter upper-left silver edge fades around the perimeter. Closing panels add a restrained, grainy blue-violet bloom near the lower-left corner.

**Transfer:** Use a masked 1px gradient edge from white at 40% through 20% to 10%; keep the interior mostly charcoal.

#### Translucent proof frame · level 2

**Use:** Outer layer of theatrical quotation stacks.

**CSS:** `background: rgba(255,255,255,0.4); border-radius: 8px; backdrop-filter: blur(10px); box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.3)`

**Observed:** Multiple offset glass-like sheets surround a bright quotation card; slight rotations make the group feel held rather than tiled.

**Transfer:** Layer two or three translucent sheets behind the main quotation and keep text on the opaque inset.

#### Bright quotation sheet · level 3

**Use:** Readable proof inside the layered stack.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 24px; box-shadow: 0px 1px 4px 0px rgba(0,0,0,0.25), 0px 4px 59px 0px rgba(0,0,0,0.1)`

**Observed:** Dark quote text, small avatar, name and attribution; the bright surface is localized rather than a page-wide theme.

**Transfer:** Use authentic short proof with human attribution and generous internal margins.

#### Editorial paper · level 0

**Only for:** resource and workflow directories

**Use:** Continuous reading body beneath a luminous blue-lavender header.

**CSS:** `background: #f5f5f7; color: #111827`

**Observed:** A pale body holds white tiles and a thin-rule FAQ; the page returns to black for its closing action and footer.

**Transfer:** Use for browse-heavy pages rather than changing the default landing-page theme.

## Components

### Floating navigation

**Use:** Persistent compact navigation over dark and light scenes.

**CSS:** `position: fixed; top: 24px; left: 50%; transform: translateX(-50%); display: flex; align-items: center; gap: 18px; padding: 4px 4px 4px 15px; height: 41px; border-radius: 9999px; background: linear-gradient(90deg, rgba(255,255,255,0.05), rgba(255,255,255,0.05)), linear-gradient(90deg, rgba(0,0,0,0.7), rgba(0,0,0,0.7)); backdrop-filter: blur(5px); box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.8)`

**Text style:** `navigation` — Inter 400 · 14px/1.5 · tracking -0.01em

**Observed:** Five short links precede a bright compact action. A fine gradient perimeter gives the capsule a metallic edge; inactive links are white at 35%, with the active link at 80%.

**States:** Declared: hover inactive link color rgba(255,255,255,0.6).

### Compact white action

**Use:** Conversion anchor inside the floating navigation.

**CSS:** `background: #ffffff; color: #000000; height: 33px; padding: 6px 12px; border-radius: 9999px; display: flex; align-items: center; gap: 8px`

**Text style:** `navigation` — Inter 400 · 14px/1.5 · tracking -0.01em

**Observed:** A small solid product mark sits before the label; the outer silhouette is a smoothly rounded capsule.

**States:** Declared: hover background rgba(255,255,255,0.9).

**Transfer:** Use the new product's small mark or a simple download glyph.

### Dark action

**Use:** Full-width conversion control on ordinary dark pricing panels.

**CSS:** `background: #1c1d1f; color: rgba(255,255,255,0.6); border-radius: 9999px; padding: 14px 20px; height: 52px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `action` — Inter 500 · 16px/1.5

**Observed:** Label aligns left and a fine arrow sits at the far right. On the luminous recommended plan the action reverses to black with bright text. Sales-led callouts instead use a white 42px pill; proof-directory trial controls use a white-to-light-gray 47px button with 9px corners.

**States:** Declared: hover color rgba(255,255,255,1).

### Demo action

**Use:** Centered invitation within the contracted opening stage.

**CSS:** `background: rgba(255,255,255,0.1); color: #ffffff; border: 1px solid rgba(255,255,255,0.2); border-radius: 9999px; padding: 4px 16px 4px 4px; height: 50px; display: flex; align-items: center; gap: 10px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** A 40px translucent circular inset holds the play glyph, followed by the text label.

**States:** Declared: hover background rgba(255,255,255,0.2).

### Capability object card

**Use:** Horizontal gallery of illustrated product capabilities.

**CSS:** `width: 320px; height: 400px; padding: 24px; border-radius: 24px; background: rgba(221,85,231,0.08); backdrop-filter: blur(16px); overflow: hidden`

**Text style:** `eyebrow` — Inter 500 · 14px/20px

**Observed:** The upper 256px is dominated by a tactile switch, form fragment or mode selector. The lower area contains a small square colored icon, matching title, muted 14px description and a brighter concluding phrase. Other cards use near-black mint, red and blue tints; the row has 32px gutters and fades into black at the right edge.

**Transfer:** Turn each capability into one recognizable interaction object, with a different restrained accent per card.

### FAQ row

**Use:** Short objection handling before the footer or closing panel.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 16px 0px; border-radius: 8px; border-bottom: 1px solid rgba(255,255,255,0.1); color: #c4c5c9`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Default product FAQ questions are 18px/28px in 60px rows, with a small downward chevron at the right; the general body recipe is for surrounding support copy. Sales and editorial FAQ questions use the compact 15px Tile-title recipe in a 700px column; the light version has pale-gray dividers.

**Transfer:** Keep the question on the left and a discreet chevron on the right; pair the product variant with a documentation prompt.

### Newsletter field

**Use:** Small subscription action at the very bottom of the footer.

**CSS:** `background: linear-gradient(to right, #1c1d24, #1a1b20); border-radius: 9999px; width: 290px; height: 44px; padding: 0px 48px 0px 16px; box-shadow: 0px 0px 0px 1px rgba(255,255,255,0.08) inset; color: #ffffff`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** A 32px circular arrow submit control is inset at the right. The group has a small semibold invitation and muted explanatory line above it, aligned to the footer's left edge.

### Footer link column

**Use:** Dense utility navigation in the shared ending.

**CSS:** `display: grid; grid-auto-rows: 32px; margin-top: 20px; color: #70757c`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** Each group has a separate Footer-label heading above the links. Six columns share a 40px gutter. The header row combines a small wordmark and copyright at left with four social icons at right.

**States:** Declared: hover link color rgba(255,255,255,0.8).

### Pricing card

**Only for:** pricing sections

**Use:** Comparison of ordinary and highlighted offers.

**CSS:** `background: #0f0f10; border: 1px solid #1c1d1f; border-radius: 20px; padding: 32px; display: flex; flex-direction: column; width: 384px`

**Text style:** `price` — Inter 600 · 60px/1 · tracking -0.025em

**Observed:** Plan name, large price with a smaller currency and fractional suffix, one-line summary, divider, feature list and bottom-aligned Dark action. The recommended middle card replaces charcoal with a midnight-to-pale-blue-to-pink gradient and uses a black action. A pill segmented billing selector sits above the row.

**Transfer:** Keep equal card heights and line up actions even when feature counts differ.

### Directory tile

**Only for:** resource and workflow directories

**Use:** Clickable paths to a role, workflow, platform or resource.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 16px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.06)`

**Text style:** `tile-title` — Inter 500 · 15px/1.5

**Observed:** A 15px title is followed after 4px by a 13px description. Two columns fit within the reading column; tiles are text-first without oversized icons.

**Transfer:** Group related routes beneath compact subheadings and keep description lengths balanced.

### Logo cell

**Only for:** customer proof directories

**Use:** Dense but orderly organization proof.

**CSS:** `background: #000000; min-height: 104px; padding: 18px; display: flex; align-items: center; justify-content: center; border-right: 1px solid rgba(255,255,255,0.09); border-bottom: 1px solid rgba(255,255,255,0.09)`

**Observed:** Five columns share a continuous faint matrix outline. Marks are monochrome light gray with reduced opacity and generous breathing space. Filter chips above use translucent black-ground pills with a white selected chip.

**Transfer:** Normalize logos optically, not by forcing identical widths.

### Sales field

**Only for:** sales-led pages

**Use:** Lead-qualification fields inside a right-hand form panel.

**CSS:** `background: #000000; border: 1px solid #262626; border-radius: 8px; padding: 12px; color: #ffffff`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** A short label sits above each field, with muted placeholder text. Name, email, organization, a team-size select and an open question stack vertically. The enclosing panel is 396px wide with 26px padding and a full-width white 52px action beneath the fields.

**Transfer:** Ask only the minimum qualifying questions; preserve compact labels and black inset controls.

## Imagery and graphics

### Cinematic edge silhouettes

**Use:** The default opening's main visual.

**Observed:** A deeply shadowed human profile is cut off by the upper-left edge, facing inward; the opposing lower-right edge holds part of a dark laptop. Blue rim light traces both against a soft navy-to-muted-lavender field. The center remains empty enough for a small two-line promise and paired actions; there is no large dashboard occupying the center.

**Transfer:** Photograph or render the new product's human gesture and tool as edge fragments, underexposed with blue rim light. Without photography, use two dark abstract object silhouettes at opposite edges over the same light field; retain the open center.

**Build:** Layer a full-height dark blue-to-violet vertical gradient, then two near-black masked shapes: one entering from the top-left and one angled from the bottom-right. Add a narrow low-opacity blue rim using a duplicate mask offset inward and blurred 4px–8px. Keep the center free of opaque shapes.

### Dusk light and grain

**Use:** Signature atmosphere repeated in the opening, proof theatre and restrained closing-panel bloom.

**Observed:** Broad midnight blue and purple light warms to mauve near the lower edge. Theatrical proof uses a full-width field; contained closing panels reveal only a faint bloom through charcoal with fine overlay grain.

**Transfer:** Carry the light field into at least one later focal module; match the soft glow, not exact gradient stops.

**Build:** Use Dusk field as the base. Overlay a horizontal blue-to-purple gradient at 15% opacity and subtle monochrome SVG feTurbulence grain at low opacity with overlay blending. For a panel, confine the field to the lower-left with a large radial mask and reduce opacity to about 0.32; keep text above it.

### Tactile interface vignettes

**Use:** Feature cards and alternating product chapters.

**Observed:** Oversized switches, stacked dark app windows, small form fragments and glossy mode icons sit in near-black environments. Upper illustrations fade into the card color; angled windows extend beyond their backing rather than sitting inside generic browser mockups. A separate integration scene uses a dark physical keyboard with raised beveled keys.

**Transfer:** Show one meaningful interaction per vignette and one larger layered interface scene per product chapter. A simplified dark window with two or three readable controls is the minimum acceptable substitute.

**Build:** Construct overlapping rounded rectangles with black and charcoal fills, 1px translucent edges and faint inset white highlights. Tilt the full window group slightly, lower contrast toward its edges with a black gradient mask, and use one accent-colored selected control.

### Stacked human proof

**Use:** Theatrical social-proof module.

**Observed:** Bright social quotations with avatars sit inside several silver translucent sheets, slightly rotated and offset; compact supporting text sits beside the stack. The scene is backed by the dusk field, not a conventional uniform testimonial grid.

**Transfer:** Use a genuine quotation or result card, two translucent backing sheets and a short adjacent proof label; retain the physical layering even when there are no social-post assets.

**Build:** Place two 8px-radius translucent panels behind an opaque 24px-radius card. Offset the back panels by roughly 12px steps, rotate the front sheet by -2deg, add Translucent proof frame and Bright quotation sheet shadows, and keep avatars circular.

### Landscape sales stage

**Only for:** sales-led pages

**Use:** Atmospheric support for a lead form opening.

**Observed:** A nearly black rolling landscape spans the lower half of a navy-purple horizon, behind left-aligned copy and a dark right-hand form. The horizon drops into the black body.

**Transfer:** Use a subdued landscape or abstract terrain rather than competing office stock photography.

**Build:** Draw two overlapping low SVG hill silhouettes in black at the lower edge of Dusk field, with a slightly lighter distant ridge and a vertical black fade at the bottom.

### Tutorial media strip

**Only for:** educational sections

**Use:** A horizontally overflowing gallery of short product lessons.

**Observed:** Wide 16:9 dark thumbnails combine interface views, large app marks and a small presenter portrait. Three cards span beyond the page edges, each with a small caption and duration; a capsule progress indicator sits beneath.

**Transfer:** Use real interface demonstrations with one clear visual cue, dark backing and concise captions rather than decorative stock imagery.

### Icons

**Observed:** Most functional glyphs are 12px–20px, with 1.5px rounded strokes; download marks and social symbols are solid. Arrows and chevrons are small and right-aligned in controls. Capability titles pair with 24px colored rounded-square icons.

**Transfer:** Choose a consistent rounded 1.5px stroke set; reserve solid shapes for product marks, platforms and social links. Match icon color to the adjacent label rather than introducing extra accent colors.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise opening

**Observed:** The first 900px is an edge-to-edge dusk-lit scene. A dark profile enters from the upper-left and part of a laptop rises from the lower-right, framing open central space. A centered two-line 48px/51px semibold white promise takes only about one fifth of the width. Two compact platform actions sit side by side below: one light, one black, both with small leading platform marks and softly rounded rectangular edges. A quiet availability link and a short supporting line follow. The opening is a visual stage, not a dashboard hero; proof and capability sections remain below the first screen. As the introduction progresses, the scene contracts into a roughly 1024px-wide, 18px-radius panel on black, exposing Floating navigation above it and replacing the promise with a short invitation and Demo action.

**Transfer:** Use the same centered, compact promise and opposing edge subjects for a different product. Without source-quality media, compose dark interaction silhouettes over Dusk field and make the central text equally legible. Proof directories open with a left-aligned headline and compact statistics; editorial directories use a 700px reading column over a brighter blue-lavender header fading into paper; sales-led pages pair left copy with the Sales field panel.

**Avoid:** Do not substitute a giant 80px headline, a centered full dashboard, a bright white hero canvas or a busy collage. Do not show the demo invitation and opening promise simultaneously as competing headings.

**Text style:** `display` — Inter 600 · 48px/51px

### Eyebrow and capability chapter

**Observed:** A sentence-case colored eyebrow precedes a 31px Heading by 8px–16px. A text column pairs with a larger product vignette; the next chapter can reverse the balance. Supporting feature rows have small accent icons and compact gray descriptions, not separate heavy cards.

**Transfer:** Explain a new capability through one visible interaction and two or three short consequences.

**Text style:** `heading` — Inter 600 · 31px/1.2 · tracking -0.04em

### Object gallery

**Observed:** Capability object cards sit in a horizontal row with 32px gutters, preceded by a compact eyebrow and 24px lead. The row extends beyond its centered container and fades into black at the right. A four-column strip of tiny secondary features sits beneath.

**Transfer:** Make each card's upper illustration distinct while retaining the same lower text baseline; use smaller features as a quiet supplement rather than another full card row.

### Theatrical proof return

**Observed:** Dusk field fills a 900px-high band. A colored eyebrow and centered Proof-display introduce Stacked human proof, with the card stack lower-left and a compact adjacent label. The palette expands here while the text remains spare.

**Transfer:** Use the signature layered proof device to give one real endorsement visual importance without filling the whole page with testimonials.

**Text style:** `proof-display` — Inter 600 · 48px/1.07 · tracking -0.0375em

### Scoped closing calls

**Observed:** Sales-led and proof-directory pages end their main content in Raised charcoal panel with a faint lower-left dusk bloom and silver edge. The sales variant pairs heading and actions with a two-column list of benefits; the proof variant is a shorter left-aligned prompt. Editorial directories instead use a centered black call with 160px vertical breathing room, a 31px heading, subdued support and a white pill. The default long product page finishes its main narrative with tutorials and FAQ rather than a separate oversized closing billboard.

**Transfer:** Choose the closing treatment that matches the page's decision: consultation panel, short trial prompt or direct self-serve action.

### Utility footer ending

**Observed:** All page types return to Black canvas. After 144px separation, the footer places the small brand and copyright at left and four social icons at right, then six Footer link columns after 48px. A white-at-6% rule separates a final newsletter group with 40px top padding. The Newsletter field remains a small left-aligned 290px control; nothing monumental follows it.

**Transfer:** Retain the small final subscription and utility links as the actual ending, even if a conversion panel precedes them.

### Offer comparison

**Only for:** pricing sections

**Observed:** A compact capsule billing selector precedes a three-card Pricing card row by about 80px. The center offer receives the luminous gradient, while the outside offers stay charcoal. Large numerals contrast with small descriptions, thin rules and bottom-aligned actions.

**Transfer:** Use the gradient for one clear recommendation, not all offers at once.

**Text style:** `price` — Inter 600 · 60px/1 · tracking -0.025em

### Directory and quantified proof

**Only for:** customer proof directories

**Observed:** A left-aligned 48px medium headline sits over three compact 31px statistics with 6px caption gaps and 40px group spacing. Below, filter chips lead into the five-column Logo cell matrix. A 1024px-wide Raised charcoal panel closes the directory, with trial and sales actions and a quiet individual-use link.

**Transfer:** Use verified proof metrics and recognizable entities relevant to the new product; keep the matrix continuous and monochrome.

**Text style:** `proof-page-display` — Inter 500 · 48px/1.06 · tracking -0.04em

### Editorial browse body

**Only for:** resource and workflow directories

**Observed:** Editorial paper begins beneath a luminous blue-lavender opening. A 700px column contains blue eyebrows, Heading titles, brief explanatory paragraphs and repeated two-column Directory tile groups separated by 32px. Two larger visual resource links precede a thin-rule FAQ.

**Transfer:** Organize a product's routes by reader intent, then add a small pair of deeper resources; preserve the narrow reading width.

**Text style:** `heading` — Inter 600 · 31px/1.2 · tracking -0.04em

### Sales reassurance chapter

**Only for:** sales-led pages

**Observed:** A 700px column carries category tabs, a 24px use-case subheading, a before-and-after text demonstration and a small sales action. A customer-story panel follows with a logo, 21px quotation, avatar attribution and a three-stat strip separated by a faint rule; stat values are 27px semibold with 13px captions. Further reassurance uses two-column feature groups and compact FAQ rows.

**Transfer:** Let real output establish usefulness before administrative details; use a single attributed story to bridge the two.

## Page flow

**Storyline:** Compact promise in an atmospheric stage → visible usefulness → credible proof → deeper capabilities or routes → decision support → restrained utility ending.

### Flagship product landing page

1. **Promise** — Cinematic centered introduction that contracts into a playable demonstration stage.
2. **Social proof** — Small centered heading, supporting line and monochrome organization marks.
3. **Capability chapters** — Alternating interface vignette and text, tactile object gallery, quieter secondary-feature strip.
4. **Breadth** — Large integration statement, a specialized workflow scene and a compact cross-device callout.
5. **Human proof** — Dusk-backed layered quotation theatre.
6. **Decision support** — Three-offer comparison, horizontally overflowing tutorials and a split FAQ/documentation section.
7. **Utility ending** — Black six-column footer and small newsletter field.

**Transfer:** Use the cinematic stage and physical proof device as recurring focal moments; adapt the chapters and their order to the new product's story.

### Customer and adoption proof directory

1. **Quantified promise** — Left-aligned headline on dusk light with three short statistics and a trial action.
2. **Browsable proof** — Filter chips and a continuous five-column monochrome logo matrix.
3. **Closing call** — Contained charcoal trial-and-sales prompt with a subtle lower-left bloom.
4. **Utility ending** — Shared footer with subscription below a fine rule.

**Transfer:** Use a compact introduction and verifiable proof collection rather than reproducing a full product tour.

### Workflow and resource discovery

1. **Orientation** — Bright atmospheric header with compact title, short summary and paired actions.
2. **Route selection** — Pale 700px reading column with explanatory copy and grouped two-column tiles.
3. **Further exploration** — Two visual resource links followed by compact FAQs.
4. **Closing call** — Centered self-serve action on black.
5. **Utility ending** — Dark shared footer and newsletter.

**Transfer:** Keep this page type lighter and more editorial while preserving the floating dock and black ending.

### Sales-led organizational landing page

1. **Promise and qualification** — Two-column atmospheric opening with trust badges, brief copy and a dark lead form over a shadowy landscape.
2. **Demonstrated fit** — Tabbed audience examples with before-and-after output.
3. **Customer proof** — One attributed story in a charcoal panel with a three-stat strip.
4. **Procurement reassurance** — Two-column administrative and security capabilities followed by a narrow FAQ.
5. **Closing call** — Gradient-edged charcoal panel pairing sales/trial actions with a benefit list.
6. **Utility ending** — Shared black footer and small subscription field.

**Transfer:** Bring qualification forward for complex purchases, but demonstrate a practical result before detailed procurement reassurance.

## Writing

Plainspoken and outcome-first, with a little maker humor in tiny labels. Confidence comes from concrete interactions, straightforward availability and attributed proof rather than inflated category language.

**Do not copy:** Do not reuse the Superwhisper name, product marks, customer logos, named endorsements, quotations, prices, adoption numbers, performance claims, certifications or platform promises as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team. Name the product naturally in explanations; use imperatives for actions and short benefit headings.
- **Rhythm:** Headlines often use two short clauses or a concise practical outcome. Support is usually one or two sentences; small feature descriptions lead with an action and finish with the consequence. Playful micro-labels are rare accents, not the whole voice.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A simple action followed by a faster or easier result. | 4–8 words | “Just speak. Write faster.” |
| Capability heading | Specific benefit in everyday language, often reader-directed. | 3–8 words | “Build it yourself”<br>“Communication isn't one-size-fits-all” |
| Support | Say what changes in the reader's work, then remove a practical concern. | 12–30 words | “Roll it out to your team in a day. Volume discounts, SSO, and a free trial.” |
| Action | Literal verb and destination, with ownership when it clarifies the next step. | 2–5 words | “Start my team trial”<br>“Talk to sales”<br>“Download free” |
| Directory orientation | A conversational summary followed by a concrete route-finding instruction. | 12–22 words | “One app, a lot of jobs. Find the workflow that matches how you actually work.” |
| Small playful label | A tiny aside above otherwise practical content. | 2–3 words | “Beep boop”<br>“What's inside” |

**Words and phrasing to use:** works; your team; in any app; faster; ready; get started; pick; built for; free trial; without typing

**Avoid:** revolutionary; unleash; synergize; world-class ecosystem; paradigm shift; limitless magic

**Rules:**

- Lead with an observable action or outcome rather than a broad mission statement.
- Follow a capability with the concrete place or task where it helps.
- Use ordinary sentence case in headings, buttons and eyebrows.
- Keep humorous language isolated in tiny labels; keep purchase and security language literal.
- Attach quantitative claims to attributable proof and explain what the number measures.

## Do's and Don'ts

### Do

- Keep the opening promise at 48px/51px and let the scene, not the type, supply the scale.
- Use 31px/1.2 section headings with -0.04em tracking for most chapters.
- Keep the floating navigation compact at 41px high, with 18px internal gaps and a bright 33px action.
- Use 24px corners for illustrated feature panels and 20px corners for pricing cards.
- Retain black breathing space around media; 96px is a useful chapter interval.
- Give each tactile capability card a 256px illustration zone before its compact text.
- Make the recommended offer luminous while adjacent offers remain #0f0f10.
- Finish with 14px utility text, six columns at 40px gaps and a small 290px newsletter pill.

### Don't

- Do not turn electric blue into the default full-page background or the standard conversion-button fill.
- Do not apply -0.04em tracking to every text style; the main opening has normal tracking.
- Do not use 24px corners for every control: actions are capsules, media is often 8px and editorial tiles are 12px.
- Do not place all capabilities in identical flat gray boxes with a small icon floating above the title.
- Do not make the floating dock a full-width opaque header or add a second oversized logo row to it.
- Do not brighten footer links to primary-white emphasis; their default is #70757c.
- Do not flatten layered quotation sheets into a three-column uniform testimonial grid.
- Do not mix paper directory tiles into the ordinary black product chapters as a default card style.

## Motion and responsive

### Motion

**Observed:**

- The opening scene contracts into a rounded stage as the introduction progresses; the central promise gives way to a demo invitation.
- Declared: the dusk layer transitions opacity over 1.2s ease-in-out.
- Declared: the Demo action and Dark action use color/background-related transitions of 0.15s cubic-bezier(0.4,0,0.2,1).
- Declared: the highlighted pricing field transitions background-position over 0.8s.
- Declared: repeated marquees use a linear infinite animation with duration supplied by a variable; tutorial indicators include an elongated active capsule.

**Transfer:**

- Preserve the opening's change from immersive scene to contained playable stage rather than animating every section equally.
- Use subtle opacity and color changes on controls; keep the theatrical movement concentrated in the opening and proof/media devices.

**Unknown:**

- Exact scroll interpolation, marquee durations and complete playback behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 640px, 768px, 1024px, 1150px, 1280px, 1400px and 2000px.
- Customer headline declarations change from 36px to 48px; sales-led headlines from 34px to 48px; editorial titles from 40px to 48px.
- Directory tiles declare one column before the two-column variant; logo matrices declare two, three, four and five columns. Footer declarations progress from one to two to three to six columns.

**Transfer:**

- On narrow screens, stack text and media while preserving dark edge fades and the compact headline treatment.
- Keep object-card and tutorial strips horizontally browsable rather than shrinking their illustrations into illegibility.
- Stack the sales form below its promise and keep the newsletter field within its 290px maximum width.

**Unknown:**

- Exact narrow-screen navigation replacement, opening-image framing and touch interaction behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
