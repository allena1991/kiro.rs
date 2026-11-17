# Screen Studio — polished in motion

## Overview

A dark, cinematic product style with the friendliness of a native desktop application. Soft white system grotesk typography and cool gray explanations sit on black and charcoal, with electric violet reserved for actions and luminous moments. Large interface demonstrations, softly rounded frames and occasional glowing abstract art make the product feel tangible and effortless, while the surrounding layout remains sparse.

### Essentials

- A broad promise floats above a working product: centered 72px/76px semibold headline, 21px/29px support, a single violet action and a 1126px-wide demonstration entering the first screen.
- The interface behaves like a miniature cinema: major demonstrations span 1260px at approximately 16:9, with 44.8px outer rounding, glass playback controls and pill-shaped mode selectors.
- Color is concentrated rather than spread: black and #111112 occupy most of the page; #4d2ff5 marks conversion actions, #9d8bff marks labels and links, and richer color lives primarily within media.
- Explanations have two brightness levels, not two typefaces: gray 21px/29px medium-weight paragraphs contain soft-white phrases at the same size and weight; headings remain system-ui weight 600 with normal tracking.
- Controls feel native, not bubbly: primary buttons use 14.4px corners and 54px height, compact actions use 9.6px corners and 32px height, while only selectors, badges and playback controls become pills or circles.
- A luminous demonstration moment interrupts the interface chapters: a dark-centered violet light loop surrounds a short centered promise and a white play control; rebuild it with layered glowing SVG paths when equivalent interactive art is unavailable.
- Small proof follows big demonstrations: three-column caption strips with 20px gaps and hairline rules, human testimonial masonry with 32px cards, and a restrained four-column footer preserve a useful, app-like finish.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#4d2ff5` | `--color-action` | action, accent | Primary conversion buttons; not a full-page fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Purple light | `#8a5cff` | `--color-gradient-deep` | accent | Saturated end of violet text gradients and luminous art. |
| Lavender | `#9d8bff` | `--color-accent` | text, link, accent | Chapter labels, mentions, feature icons and focus outlines. |
| Lilac light | `#b194ff` | `--color-gradient-mid` | accent | Middle of violet text gradients. |
| Pearl lavender | `#e2d1ff` | `--color-gradient-light` | accent | Light end of highlighted text gradients and luminous art. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black canvas | `#000000` | `--color-canvas` | background | Default page canvas and dark inset panels. |
| Media black | `#0b0b0d` | `--color-media` | surface | Backing behind product demonstrations. |
| Navigation glass | `#0e0e0f` | `--color-glass` | surface | Visible black-backed appearance of rgba(22,22,23,0.635); navigation lets underlying media softly show through. |
| Subtle edge | `#0f0f0f` | `--color-subtle-edge` | border | White at 0.06 alpha outlines secondary actions; this is its appearance over black. |
| Charcoal band | `#111112` | `--color-band` | background, surface | Full-width chapter bands and testimonial cards. |
| Raised charcoal | `#1d1d1f` | `--color-raised` | surface | Pricing cards and selected instructional steps. |
| Hairline gray | `#242424` | `--color-rule` | border | White at 0.14 alpha separates caption strips, FAQ rows and footer tiers; appearance varies with the dark backing. |
| Selector glass | `#2a2a2c` | `--color-selector` | surface | Black-backed appearance of rgba(51,51,54,0.82) for mode controls. |
| Subdued gray | `#6e6e73` | `--color-faint` | text | Compatibility note and secondary metadata. |
| Cool gray | `#86868b` | `--color-muted` | text | Supporting paragraphs and explanatory captions. |
| Silver gradient | `#a1a1a6` | `--color-silver` | text | Darker end of the alternative pricing numeral gradient. |
| Footer gray | `#a3a3a3` | `--color-footer-link` | text, link | Footer links use white at 0.64 alpha; this is its appearance over black, brightening over the footer band. |
| Quote white | `#d8d8d9` | `--color-quote` | text | Testimonial text; rgba(245,245,247,0.88) produces this approximate appearance over black, slightly brighter over charcoal. |
| Soft white | `#f5f5f7` | `--color-text` | text, surface | Headlines, emphasized phrases, action labels and selected selector segments. |

## Typography

- **system-ui** — All marketing headings, descriptions, labels and controls. Native system grotesk, with a compact contemporary shape, medium explanatory text and semibold headlines. Font stack: "system-ui", -apple-system, "SF Pro Display", "SF Pro", Inter, "Inter Fallback", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | system-ui | 600 | 72px | 76px | normal | Main broad marketing promise, centered. |
| light-loop-heading | system-ui | 600 | 56.3px | 1.04 | normal | Two-line promise placed inside the luminous loop. |
| heading | system-ui | 600 | 56px | 60px | normal | Default major capability and proof heading. |
| heading-compact | system-ui | 600 | 48px | 1.083 | normal | Secondary chapters, paired gradient headings, FAQ and price numerals; also the use-case landing headline. |
| panel-heading | system-ui | 600 | 28px | 1.143 | normal | Titles of substantial two-column information panels. |
| lead | system-ui | 500 | 21px | 1.381 | normal | Main supporting paragraphs; gray base with same-weight soft-white phrases. |
| chapter-label | system-ui | 600 | 21px | 1.19 | normal | Lavender chapter labels, plan titles and small price units. |
| support | system-ui | 500 | 19px | 1.421 | normal | Short support text for proof, pricing and FAQ. |
| button | system-ui | 500 | 18px | 1.25 | normal | Opening conversion action. |
| body | system-ui | 400 | 17px | 1.47 | normal | Testimonials, plan feature lists and longer panel explanations. |
| caption | system-ui | 500 | 17px | 1.235 | normal | Explanations beneath media. |
| caption-strong | system-ui | 600 | 17px | 1.235 | normal | Inline caption titles, feature titles and FAQ questions. |
| small | system-ui | 400 | 14px | 1.43 | normal | Feature-grid descriptions and proof metadata. |
| badge | system-ui | 600 | 14px | 1.43 | normal | Announcement badge and numbered step markers. |
| compact-action | system-ui | 500 | 14px | 1.33 | normal | Navigation and footer conversion buttons. |
| compatibility | system-ui | 400 | 13px | 1.385 | normal | Single subdued note under the opening action. |
| footer | system-ui | 400 | 12px | 1.333 | normal | Footer navigation, tagline and supporting contact text. |
| footer-heading | system-ui | 600 | 12px | 1.333 | normal | Footer column headings. |

**Notes:**

- Keep normal tracking throughout rather than adding fashionable negative tracking to the display.
- Size and brightness do most of the hierarchy work. The primary explanatory text is weight 500; white emphasis changes color, not weight.
- Use 56px as the default major section heading and 48px for compact or secondary chapters, not an average between them.
- Keep the default opening headline broad and almost single-line at desktop. The light-loop promise instead wraps within a 528px text measure.

## Layout

**Density:** Airy chapter spacing around dense, useful demonstrations; small controls and captions remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Action-to-compatibility note and compact feature text separation. |
| 8px | Icon-label spacing and footer list gaps. |
| 10px | Section heading-to-support spacing. |
| 12px | Small grouped content and metadata. |
| 20px | Two- and three-column gutters and testimonial column separation. |
| 24px | Testimonial card padding. |
| 28px | Hero headline-to-support gap. |
| 32px | Caption-strip top padding and action corners' surrounding breathing room. |
| 36px | Hero support-to-action gap. |
| 40px | Feature-grid horizontal gaps. |
| 48px | Large information and pricing panel padding. |
| 56px | Media-to-caption-strip margin and showcase heading-to-media spacing. |
| 64px | Pricing and testimonial heading-to-content spacing. |
| 72px | Default capability heading-group-to-media spacing. |
| 96px | Expanded introduction-to-demonstration spacing. |
| 144px | Major chapter vertical padding. |

### Containers and grids

- **main-container**: max width 1260px. Centered primary chapters, media and caption strips; leaves 90px side margins at 1440px.
- **opening-media**: max width 1126px. Centered opening demonstration, narrower than the headline and later full-width demonstrations.
- **text-measure**: max width 760px. Centered section descriptions; opening support extends to 780px.
- **paired-panels**: max width 1260px · 2 columns · gap 20px. Equal 620px media or information panels.
- **caption-grid**: max width 1260px · 3 columns · gap 20px. Three concise explanations below one large demonstration.
- **feature-grid**: 3 columns · gap 40px. Icon feature grid within a 48px-padded inset panel; row gap is 44px.
- **pricing-pair**: max width 820px · 2 columns · gap 20px. Two equal 400px plan cards centered inside the main container.
- **faq**: max width 880px. Centered, full-width question rows with edge-aligned plus icons.
- **footer-grid**: max width 980px · 4 columns · gap 20px. Narrower footer with 230px desktop columns.

## Corner radius

| Element | Radius |
| --- | --- |
| primary-buttons | 14.4px |
| compact-actions | 9.6px |
| major-panels | 44.8px |
| testimonial-cards | 32px |
| navigation | 28.8px |
| selector | 9999px (pill) |
| playback | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| opening-media | `rgba(0, 0, 0, 0.45) 0px 30px 90px 0px` | Depth beneath the first product demonstration. |
| navigation-edge | `rgba(255, 255, 255, 0.07) 0px 0px 0px 1px` | Faint perimeter of the floating navigation. |
| media-edge | `rgba(255, 255, 255, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.5) 0px 30px 80px 0px` | Inset wide-format media presentation. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #000000; color: #f5f5f7`

**Observed:** Black extends through the opening and selected capability chapters.

**Transfer:** Let black negative space separate the product from its surroundings.

#### Chapter band · level 0

**Use:** Alternate chapter background, proof showcase and footer.

**CSS:** `background: #111112`

**Observed:** Full-width charcoal areas often contain several related chapters. Some boundaries have a very thin violet light seam.

**Transfer:** Group related ideas on one band rather than alternating every individual card.

#### Media stage · level 1

**Use:** Large demonstrations.

**CSS:** `background: #0b0b0d; border-radius: 44.8px; overflow: hidden`

**Observed:** Wide demonstrations use rounded outer panels; some wide stages additionally clip at 28px. Bottom fades keep overlaid explanatory text readable.

**Transfer:** Use actual product content inside the stage, not empty decorative rectangles.

#### Information panel · level 1

**Use:** Substantial explanatory content beside another panel.

**CSS:** `background: #111112; border-radius: 44.8px; padding: 48px`

**Observed:** Soft charcoal holds a title, divider and concise lists.

**Transfer:** Keep large panels visually quieter than the media.

#### Highlighted text · level 1

**Use:** A brief secondary promise or emphasized price.

**CSS:** `background-image: linear-gradient(95deg, #e2d1ff 0%, #b194ff 42%, #8a5cff 100%); background-clip: text; color: rgba(0, 0, 0, 0)`

**Observed:** A violet gradient is confined to selected words or numerals. Alternative price numerals fade from soft white to silver.

**Transfer:** Apply to a meaningful short phrase rather than an entire text block.

## Components

### Floating navigation

**Use:** Persistent desktop navigation.

**CSS:** `background: rgba(22, 22, 23, 0.635); border-radius: 28.8px; box-shadow: rgba(255, 255, 255, 0.07) 0px 0px 0px 1px; backdrop-filter: saturate(1.63679) blur(15.9px); max-width: 1024px; height: 52px; overflow: hidden`

**Observed:** Fixed and centered near the top; brand at left, a short cluster of links, a dropdown and compact violet action at right. The opening appears nearly transparent; the floating glass is more legible over subsequent chapters.

**Transfer:** Keep the link cluster short and reserve the most saturated item for conversion.

### Primary button

**Use:** Opening conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #4d2ff5; color: #f5f5f7; border: 1px solid transparent; border-radius: 14.4px; height: 54px; padding: 0px 32px; gap: 8px`

**Text style:** `button` — system-ui 500 · 18px/1.25

**Observed:** A platform symbol precedes the label. Plan buttons use a 48px-high variant with 17px medium text; the recommended plan gets violet, the alternative a faint white wash and edge.

**States:** Declared: hover appearance is unspecified; focus-visible outline #9d8bff solid 2px with 3px offset.

**Transfer:** Use a relevant platform or action symbol only when it helps explain the action.

### Compact conversion button

**Use:** Navigation and footer action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #4d2ff5; color: #f5f5f7; border: 1px solid transparent; border-radius: 9.6px; height: 32px; padding: 6px 12px`

**Text style:** `compact-action` — system-ui 500 · 14px/1.33

**Observed:** The small conversion action repeats at the top and at the footer's upper-right corner.

**States:** Declared: hover appearance is unspecified; focus-visible outline #9d8bff solid 2px with 3px offset.

### Announcement badge

**Use:** Small release cue above the opening headline.

**CSS:** `display: flex; align-items: center; background: rgba(42, 42, 45, 0.72); border-radius: 9999px; height: 34px; padding: 0px 16px; backdrop-filter: saturate(1.8) blur(20px); box-shadow: rgba(255, 255, 255, 0.1) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.3) 0px 1px 2px 0px, rgba(0, 0, 0, 0.22) 0px 6px 16px 0px; color: #f5f5f7`

**Text style:** `badge` — system-ui 600 · 14px/1.43

**Observed:** A subtle rotating perimeter glint and soft blurred halo make the small dark badge feel machined rather than flat.

**Transfer:** Use a short factual announcement; keep the light restrained.

### Mode selector

**Use:** Switch among demonstrations or product modes.

**CSS:** `background: rgba(51, 51, 54, 0.82); border-radius: 9999px; height: 44px; backdrop-filter: saturate(1.8) blur(20px)`

**Observed:** A 4px-padded inner row holds 36px-high segments with 14px regular text. Selected segment is soft white with dark text; other segments are transparent. It floats near the top-center of large media or sits beneath a centered interactive scene.

**States:** Declared: hover on inactive text segments uses white text and rgba(255,255,255,0.06) background; focus-visible outline #9d8bff solid 2px with -2px offset.

**Transfer:** Keep options short enough to scan as native segmented controls.

### Playback control

**Use:** Play and pause within demonstration frames.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; width: 44px; height: 44px; border-radius: 50%; background: rgba(68, 68, 68, 0.6); backdrop-filter: saturate(1.8) blur(10px)`

**Observed:** A small white glyph sits in a translucent circle near a media corner. Compact demonstrations and carousel arrows use 36px circles; disabled carousel controls are faded to 0.2 opacity. The luminous scene instead uses a white 65px circle with a black play triangle.

**States:** Declared: hover appearance is unspecified for the glass control; focus-visible outline #9d8bff solid 2px with 3px offset.

### Caption strip

**Use:** Concise subordinate explanations beneath media.

**CSS:** `border-top: 1px solid rgba(255, 255, 255, 0.14); padding-top: 32px; margin-top: 56px; display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); gap: 20px`

**Text style:** `caption` — system-ui 500 · 17px/1.235

**Observed:** Each column begins with a short soft-white semibold phrase, immediately followed by gray explanation. Carousel media captions instead sit directly beneath the individual image.

**Transfer:** Limit each column to one distinct consequence, not another headline.

### Testimonial card

**Use:** Human social proof in a staggered wall.

**CSS:** `background: #111112; border-radius: 32px; padding: 24px; margin-bottom: 20px`

**Text style:** `body` — system-ui 400 · 17px/1.47

**Observed:** A 40px circular avatar sits beside a semibold name and smaller gray handle; the quotation follows below with lavender inline mentions. Cards have unequal heights in four desktop columns. A bottom mask fades the initial wall into black above a small expansion control.

**Transfer:** Keep authentic voice and variable quotation lengths rather than equal-height promotional blurbs.

### Plan card

**Use:** Comparable purchase choices.

**CSS:** `display: flex; flex-direction: column; background: #1d1d1f; border-radius: 44.8px; padding: 48px; width: 400px; overflow: hidden`

**Text style:** `body` — system-ui 400 · 17px/1.47

**Observed:** Plan name and a small savings badge share the first row, followed by a 48px gradient price with 21px billing suffix, muted inclusion line, divider, lavender check list and bottom-aligned action. Two plans share the same feature list. One gets violet numerals and a violet button; the other silver numerals and a faint outlined button.

**Transfer:** Emphasize the recommended purchase cadence without making the other card a different size.

### FAQ row

**Use:** Objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 22px 0px; color: #f5f5f7`

**Text style:** `caption-strong` — system-ui 600 · 17px/1.235

**Observed:** The wrapper supplies a 1px white-at-0.14 bottom rule; the group also starts with a rule. Questions align left and a 22px gray plus aligns right. The collapsed rows are 67px including their separator.

**States:** Declared: hover appearance is unspecified; focus-visible outline #9d8bff solid 2px with 4px offset and 4px radius.

### Footer link

**Use:** Dense, secondary navigation at the close.

**CSS:** `color: rgba(255, 255, 255, 0.64); transition: color 200ms`

**Text style:** `footer` — system-ui 400 · 12px/1.333

**Observed:** Text-only links stack beneath soft-white semibold column titles, with 8px list gaps.

**States:** Declared: hover color rgba(255,255,255,0.9), underline with 0.2em offset; focus-visible outline #9d8bff solid 2px with 2px offset and 2px radius.

### Numbered workflow step

**Only for:** use-case walkthroughs

**Use:** Connect a procedure to an adjacent demonstration.

**CSS:** `display: flex; align-items: baseline; gap: 16px; padding: 18px 20px; background: #1d1d1f; border-radius: 28.8px`

**Text style:** `caption` — system-ui 500 · 17px/1.235

**Observed:** The selected step has a filled light 28px number circle with black text, a semibold white title and gray explanation. Unselected steps have transparent backgrounds and outlined gray number circles. The text list occupies the smaller left column beside a wide video.

**Transfer:** Map each step to one visible change in the adjacent media.

## Imagery and graphics

### Cinematic interface demonstrations

**Use:** Primary product evidence, beginning in the opening and recurring through capability chapters.

**Observed:** Working desktop interfaces are presented within large rounded video frames, often over saturated violet, blue, pink or macOS-like flowing wallpapers. The UI remains recognizable and large; some scenes zoom close to cursor activity. Soft shadows and inset padding lift windows from their backgrounds. Color occupies the demonstration, not its surrounding chapter. A person may appear beside or within the interface as a webcam panel.

**Transfer:** Show a real workflow or a deliberately composed interface prototype with one legible focal action. Without video, supply a polished still with a large cursor or clearly highlighted result, maintaining wallpaper, inset space and depth.

### Luminous loop

**Use:** Signature experiential interlude around a short benefit and play control.

**Observed:** A violet, blue and lilac irregular light loop surrounds a nearly black center. Thin bright ribbons overlap a soft halo, with a pearl highlight along parts of the lower rim; it feels like glowing glass rather than a flat gradient disk. The scene occupies an 880px square, with the 528px-wide headline centered over it and controls beneath.

**Transfer:** Translate a product quality into a simple luminous contour while retaining the dark center and overlaid promise. A static layered SVG loop is the minimum acceptable version.

**Build:** Use an 880px square black stage. Draw three slightly different closed organic ellipse paths around its center, leaving the interior unfilled. Give the principal path a 3px stroke with a violet-to-lilac-to-pearl gradient, then duplicate it underneath at 12px and 28px widths with rgba(138,92,255,0.25) and rgba(77,47,245,0.16), blurred by 12px and 28px. Offset one thin path slightly, and add a faint translucent violet ribbon between two nearby contours. Concentrate the brightest pearl highlight on a short lower arc; keep most of the center black. Match the soft glow; exact stops are not essential.

### Customer work showcase

**Use:** Output proof in a horizontally overflowing gallery.

**Observed:** Large approximately 745px by 420px customer videos run edge-to-edge inside rounded cards; the next item extends beyond the content edge. An avatar or customer logo, name, handle and tiny external-link indicator sit beneath the media. Colored backdrops vary with the work rather than a unified brand filter.

**Transfer:** Use real outputs or plausible example artifacts and retain their own visual identity. Include attribution below each artifact.

### Native application shelf

**Only for:** platform-fit chapters

**Use:** Small tactile compatibility proof between text and a caption strip.

**Observed:** A short dark translucent shelf holds five glossy app icons, with the central product icon enlarged and raised. Small reflections, a thin light perimeter and a tiny indicator dot evoke a desktop dock; the object is much smaller than full-width demonstrations.

**Transfer:** Use a relevant ecosystem or integration cluster with one central product mark, keeping the shelf compact rather than turning it into a large logo grid.

**Build:** Create a dark translucent rounded tray about 446px wide and 101px high with rgba(58,58,62,0.42), 24px backdrop blur, a 1px inset white-at-0.14 edge and a soft black shadow. Arrange five square rounded icon tiles with 15px gaps; enlarge and lift the middle one. Add a tiny soft-white indicator below the center tile.

### Icons

**Observed:** Marketing controls use small white filled play and platform symbols, plus rounded-stroke arrows and plus signs. FAQ plus icons are 22px with 2px strokes; plan checks are 15px with 2.6px rounded strokes in lavender. The compact feature grid uses 30px lavender Material Symbols Rounded glyphs.

**Transfer:** Choose simple rounded-stroke SVGs for controls and sparse lavender outline icons for feature summaries. Keep iconography subordinate to demonstrations; do not use the icon font as a text face.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** A centered stack on Canvas begins with a small glossy product emblem, then Announcement badge, a broad single-line display promise, two lines of gray lead with soft-white inline emphasis, Primary button and compatibility note. The content spans a 1260px container, the 72px headline nearly its full width, and the support stays within 780px. Behind it is near-pure black; above it sits Floating navigation. The main text-and-action stack ends around 532px. The 1126px-wide rounded demonstration begins around 588px, so the first 900px show its upper portion as well as the complete promise and action. The full demonstration and later editor view continue below the fold.

**Transfer:** Use a small tactile product emblem above a concise outcome promise and show a vivid, credible product scene entering the fold. If no working media exists, compose a polished prototype still on a flowing dark wallpaper. Use-case landings open more directly: a 48px title, 19px support, one action, compatibility note and a subdued customer-logo strip, without the emblem and announcement stack.

**Avoid:** Do not replace the centered vertical stack with a split hero, multiple equally prominent actions or a full-screen violet background.

**Text style:** `display` — system-ui 600 · 72px/76px

### Capability chapter

**Observed:** A centered lavender chapter label can precede a 56px heading; support follows by 10px in a 760px measure. A Media stage follows by 72px, sometimes 96px. Mode selector floats above the demonstration and Playback control sits near a corner. A bottom black gradient supports overlay text. Caption strip provides three short details below. Related chapters share a Chapter band with 144px outer spacing.

**Transfer:** Show one outcome at a time; allow adjacent related outcomes to share a band. Keep the media much larger than its explanatory text.

**Text style:** `heading` — system-ui 600 · 56px/60px

### Paired media explanation

**Observed:** Two 620px-wide rounded demonstrations share a 20px gutter. Each has its own playback control and a caption directly beneath, beginning with caption-strong text followed inline by caption text. Small previous/next circles align at the far right beneath the row.

**Transfer:** Use for two comparable capabilities or a horizontal gallery with a partially visible following card.

### Portrait demonstration split

**Observed:** A left-aligned 48px heading, 21px support and one ruled explanatory caption occupy the left side of a charcoal chapter; a tall 440px by 587px rounded demonstration occupies the right.

**Transfer:** Use this quieter asymmetry for naturally vertical outputs rather than forcing every demonstration into a wide frame.

**Text style:** `heading-compact` — system-ui 600 · 48px/1.083

### Luminous benefit interlude

**Observed:** Luminous loop carries the two-line light-loop-heading and a central white play button; Mode selector and a short description sit below the art, followed by a larger centered lead and a ruled three-column caption strip.

**Transfer:** Preserve an experiential light moment within the page, adapting its contour and message to a quality the new product can actually demonstrate.

**Text style:** `light-loop-heading` — system-ui 600 · 56.3px/1.04

### Trust panels and small capabilities

**Observed:** A compact 48px section heading leads into two Information panels, each with a 28px icon-and-title row, divider and concise list. Another chapter uses a black rounded inset on charcoal, with six small lavender icons in a three-column grid, 40px horizontal gaps, 44px row gaps and 48px padding.

**Transfer:** Use panels for meaningful distinctions and the icon grid for supporting details that do not deserve full-screen demonstrations.

### Output proof carousel

**Observed:** A 56px centered heading and 21px support precede Customer work showcase by 56px. Large cards extend horizontally beyond the container; attribution sits outside the image rather than over it, and small carousel arrows sit beneath at the right.

**Transfer:** Let the work provide color and credibility; keep its surrounding furniture subdued.

### Human proof wall

**Observed:** A 48px heading and 19px support precede a four-column staggered wall of Testimonial cards by 64px. The visible wall is clipped to an 880px region, fading toward the bottom with a small Show more control.

**Transfer:** Use genuine varied-length quotations, with readable authorship and a controlled initial wall height.

**Text style:** `heading-compact` — system-ui 600 · 48px/1.083

### Purchase comparison

**Observed:** A lavender label, 56px heading and 19px support sit on Chapter band. Two Plan cards follow by 64px, equal in width and separated by 20px. Discount/contact assistance sits below in lavender.

**Transfer:** Keep plans calm and directly comparable; distinguish the preferred choice through numeral color and button fill, not an oversized card.

### Questions and useful close

**Observed:** A centered 48px heading and 19px support with a lavender contact link introduce the 880px-wide FAQ group after 56px. The default question chapter sits on black; use-case pages continue charcoal from pricing. Both end with a charcoal footer: a brand-and-tagline row at left, Compact conversion button at right, a hairline, four columns of 12px navigation, a separate contact line and subdued note, then another hairline with copyright left and legal/social links right. Footer content is 980px wide and the full footer is 469px tall.

**Transfer:** Finish with practical confidence rather than a second giant hero. Re-state the action compactly, then make support and navigation easy to find.

**Text style:** `heading-compact` — system-ui 600 · 48px/1.083

### Guided procedure

**Only for:** use-case walkthroughs

**Observed:** A 48px centered heading sits above a two-column walkthrough after 72px. A 441px left column contains Numbered workflow step items; a 771px by 434px video occupies the right, with a 48px column gap.

**Transfer:** Explain a task through a short sequence of controllable steps paired to one changing demonstration.

**Text style:** `heading-compact` — system-ui 600 · 48px/1.083

## Page flow

**Storyline:** Outcome promise → visible product or procedure → output proof → capability depth → human reassurance → purchase choices → objections → useful compact close.

### Broad product marketing with cinematic demonstration depth

1. **Promise** — Emblem, announcement, broad centered headline, one action and a demonstration entering the fold.
2. **Product demonstration** — A large output scene develops into the native editing interface, followed by muted customer marks.
3. **Output proof** — A wide attributed gallery shows work made with the product.
4. **Capability chapters** — Large interactive demonstrations alternate with paired panels, a luminous experiential interlude and a portrait split.
5. **Trust and detail** — Paired explanatory panels, an icon feature grid and a small native ecosystem shelf.
6. **Social proof** — Staggered human quotation cards with an expandable fade.
7. **Pricing** — Two equal cards differentiate purchase cadence with violet and silver numerals.
8. **Objection handling** — Ruled collapsible question rows with contact support.
9. **Closing call** — Small repeated action in a practical four-column footer.

**Transfer:** Choose enough demonstrations to make the product credible without replicating the original chapter count. Preserve the contrast between huge media, short explanatory strips and a compact useful ending.

### Focused use-case acquisition with a guided procedure

1. **Task promise** — A smaller centered title and action, then muted customer marks.
2. **Procedure** — Numbered steps beside a wide demonstration.
3. **Capability support** — Horizontal feature-media cards followed by a compact exploration call.
4. **Output proof** — Attributed customer work gallery.
5. **Social proof** — Staggered quotation wall.
6. **Pricing** — The shared paired purchase cards.
7. **Objection handling** — Questions remain on the charcoal pricing background.
8. **Closing call** — The same compact action and four-column footer.

**Transfer:** Open with the task rather than the full brand spectacle; demonstrate how it works earlier, then reuse the same proof and purchasing language.

## Writing

Confident, friendly and concrete. The product promises polished results by describing the tedious work it handles, with occasional conversational warmth rather than grand technological rhetoric.

**Do not copy:** Do not reuse the brand name, logo, proprietary app imagery, customer logos, quotations, pricing, savings percentages, platform requirements or performance/privacy claims. Replace them with truthful assets and claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Name the product when explaining automatic behavior; use direct imperatives for tasks and actions.
- **Rhythm:** Headlines are usually short sentence-case statements with periods, often built from two balanced clauses. Supporting text is one or two sentences; captions begin with a short named capability and immediately explain its consequence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Desirable result plus reassuring speed or ease. | 5–9 words | “Beautiful screen recordings, in minutes.” |
| Capability headline | Explain a visible outcome in ordinary language; use contrast or paired clauses. | 4–9 words | “Movement that feels filmed, not captured.”<br>“Record once. Post everywhere.” |
| Supporting line | Name the action the reader takes, then the work the product takes over. | 1–2 sentences | “Pick the parts worth a closer look.” |
| Caption | Short capability label followed by a practical explanation. | One compact sentence after the label | “Plug in, pick your iPhone, record. The bezel and color match the model you hold.” |
| Primary action | Direct verb with destination or platform where useful. | 2–4 words | “Download for Mac”<br>“Get Started Now” |
| Reassurance | Short plain-language assurance, with technical detail beneath rather than in the headline. | 2–6 words for the heading | “Offline first.”<br>“Everything included.” |

**Words and phrasing to use:** polished; beautiful; pick; bring; your; ready; smooth; right on; automatically; the parts that matter

**Avoid:** revolutionary; disruptive; unleash; synergy; next-generation ecosystem; effortless magic without explanation

**Rules:**

- Connect every benefit to a visible behavior or a concrete consequence.
- Use white inline emphasis to identify the important mechanism within gray support, not to highlight random adjectives.
- Write chapter labels as functional categories and headlines as human outcomes.
- Keep technical terms in captions and details; let the headline stay conversational.
- Use factual contact and compatibility notes to reduce friction near actions.

## Do's and Don'ts

### Do

- Keep the default hero at 72px semibold and major section headings at 56px semibold with normal tracking.
- Set main support at 21px/29px medium and retain the gray-to-white phrase emphasis.
- Give major chapters 144px outer vertical space and 72px between heading groups and media.
- Stage actual product work in 1260px-wide demonstrations with soft rounding and discreet controls.
- Use 20px gutters for paired panels and three-column explanatory strips.
- Reserve saturated violet for conversion, selected details and luminous art; keep the surrounding canvas neutral.
- Keep testimonial padding at 24px and information/pricing panel padding at 48px.
- End with an 880px FAQ measure and a narrower 980px practical footer rather than another oversized sales scene.

### Don't

- Do not switch the marketing font to a geometric custom face merely because the product is creative software; the native system grotesk is central.
- Do not add negative tracking across the headline scale; the type uses normal tracking.
- Do not turn 54px primary buttons into full pills; preserve 14.4px corners.
- Do not give every panel a bright outline or strong white shadow; most separation comes from #000000, #111112 and #1d1d1f.
- Do not place long feature paragraphs inside media captions; retain 17px concise title-and-explanation treatments.
- Do not flatten testimonial masonry into uniform equal-height quote tiles.
- Do not color-filter all customer output to violet; varied work provides credible visual texture.
- Do not add a gratuitous statistics counter or enormous closing wordmark; proof here comes from work, people and demonstrations.

## Motion and responsive

### Motion

**Observed:**

- The opening stack declares 1s entrance animations with cubic-bezier(0.23,1,0.32,1) and staggered delays from 0.12s through 0.44s.
- The announcement perimeter declares a 1.96s linear infinite spin and 0.6s ease fade-in.
- Text links use color 200ms; many button backing layers use background-color 0.3s and fill 0.3s.
- Navigation surface changes use 420ms transitions, including cubic-bezier(0.32,0.72,0,1) for the grouped glass and corner treatment.
- Video demonstrations expose explicit play/pause controls and mode selectors.

**Transfer:**

- Let motion explain product behavior inside the large frames rather than animating every piece of surrounding copy.
- Retain the small perimeter glint as a concentrated touch of polish rather than using glowing borders on every card.
- Keep explicit playback controls visible on product scenes.

**Unknown:**

- Exact canvas-loop animation implementation and product-video timing.
- The entrance keyframes' exact path and full scroll choreography.

### Responsive

**Observed:**

- Declared width breakpoints are 734px, 884px and 1068px; the broader marketing layout also declares 1600px.

**Transfer:**

- On narrow layouts, retain the centered promise/action stack and let the first product scene remain visible soon after it.
- Reduce paired panels and three-column caption strips to a readable vertical sequence; retain carousel overflow where the next item provides a useful cue.
- Scale the luminous loop to the available width while keeping the heading and play control legible inside its dark center.
- Reflow footer columns and preserve its top action row as a clear closing destination.

**Unknown:**

- Exact mobile font sizes, container padding, navigation collapse and breakpoint-specific column changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
