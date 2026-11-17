# Conductor — skyborne tools, human wit

## Overview

A bright, practical software style with a playful sky-blue opening and a warm charcoal-on-white editorial body. Compact sans-serif headlines sit above unusually large, readable interface demonstrations, while personal endorsements and monochrome documentary photography keep the technology human. It suits desktop tools and technical products that can show real work rather than rely on abstract promises.

### Essentials

- An atmospheric opening carries a small, confident headline rather than billboard type: 36px/40px, weight 600, -0.025em tracking, in a centered 576px column with left-aligned contents.
- Technical texture becomes scenery: a blue-to-cyan sky with pale character-built clouds and a white modular wordmark, 224×34px, sits behind the opening; recreate the character field and a new modular lettering treatment when no equivalent artwork exists.
- The product is physically bigger than the pitch: a broad, rounded desktop interface rises below the narrow opening copy, extends below the first 900px, and gives way to 704px-wide demonstrations in the body.
- Actions look like compact tool controls: 6px corners, a 40px-high white hero action with a right arrow, and a 32px-high dark navigation action; never pill-shaped conversion buttons.
- Color is concentrated in the opening scenery and actual media: the long middle is white, warm charcoal #2c2826, muted #756f6c and hairline #eae8e6; no recurring saturated section fills.
- Human proof is typographic, not boxed: 24px/32px semibold quotations in a 1152px-wide two-column grid with 96px gaps and 40px portrait circles.
- A feathered documentary image supplies a human-scale emotional counterpoint: a 1280×512px monochrome image, darkened by 40% black with white edge fades, supports a centered two-line closing invitation. Use a relevant human action photograph, or a staged monochrome working scene, for another product.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Clear sky blue | `#3598df` | `--color-sky` | background | Upper atmospheric opening; match the sky's soft color variation rather than a flat fill. |
| Airy cyan | `#56c9e6` | `--color-cyan` | background | Lower opening atmosphere before fading into white. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty brown | `#7d5e59` | `--color-label-ink` | text | Release tags and recommendation labels, not general body copy. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text, action | Main page, flat cards, inverse headlines and white actions. |
| Photographic black | `#000000` | `--color-black` | text, background | Closing-action lettering and the 40% black photo overlay. |
| Warm charcoal | `#2c2826` | `--color-ink` | text, action, link | Headlines, ordinary text and dark buttons. |
| Reduced charcoal | `#6b6967` | `--color-nav-ink` | text, link | Navigation text: charcoal at 70% opacity over white; use rgba(44,40,38,0.7). |
| Warm gray | `#756f6c` | `--color-muted` | text, link | Supporting paragraphs, dates, secondary attribution and footer category labels. |
| Warm hairline | `#eae8e6` | `--color-rule` | border | Header separator, panel edges, cards and footer boundary. |
| Label edge | `#f3ece7` | `--color-label-rule` | border | Fine outline around metadata badges. |
| Warm label fill | `#f8f7f6` | `--color-label-fill` | surface | Small metadata badges. |
| Chalk | `#fafaf9` | `--color-band` | background, surface | Footer band and subtle secondary-action hover. |

## Typography

- **ui-sans-serif** — Default marketing headings, navigation, support copy and cards. System grotesk: direct, compact and slightly tightened at display sizes. Font stack: "ui-sans-serif", system-ui, sans-serif.
- **ui-monospace** — Platform choices and utility typography. Plain system monospace with regular weight. Font stack: "ui-monospace", SFMono-Regular, "SF Mono", Menlo, Consolas, "Liberation Mono", monospace.
- **Geist** (only for recruiting and editorial pages) — Long-form prose, linked chapter headings and biographies. Clean contemporary grotesk with open small text and a less tightened heading rhythm. Font stack: "Geist", -apple-system, system-ui, "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ui-sans-serif | 600 | 36px | 40px | -0.025em | Opening promise and page titles. |
| closing-heading | ui-sans-serif | 700 | 36px | 40px | -0.025em | Centered invitation over monochrome photography. |
| heading | ui-sans-serif | 600 | 24px | 32px | -0.025em | Feature leads, testimonial quotations and compact proof line. |
| body | ui-sans-serif | 400 | 16px | 1.5 | normal | Muted supporting copy beneath feature headings. |
| card-heading | ui-sans-serif | 600 | 16px | 1.5 | normal | Update-card titles. |
| small | ui-sans-serif | 400 | 14px | 20px | normal | Navigation, footer and compact explanatory text. |
| action | ui-sans-serif | 500 | 14px | 20px | normal | Dark navigation action and inline action links. |
| action-strong | ui-sans-serif | 600 | 14px | 20px | normal | Hero button and concise question headings. |
| aside-quote | ui-sans-serif | 400 italic | 14px | 24px | normal | Small testimonial under the opening action and update introduction. |
| closing-action | ui-sans-serif | 700 | 14px | 20px | normal | White download action over photography. |
| caption | ui-sans-serif | 400 | 12px | 20px | normal | Small attribution, compact plan lists and secondary metadata. |
| release-label | ui-sans-serif | 400 | 12px | 16px | 0.05em, uppercase | Release metadata badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | ui-sans-serif | 600 | 30px | 1.2 | -0.025em | Price or custom-plan value. |
| recruiting and editorial pages | article-heading | Geist | 500 | 24px | 32px | normal | Linked chapter headings. |
| pricing pages | plan-heading | ui-sans-serif | 600 | 18px | 28px | -0.025em | Plan names. |
| recruiting and editorial pages | article-body | Geist | 400 | 16px | 1.75 | normal | Long-form narrative paragraphs. |
| recruiting and editorial pages | article-quote | Geist | 500 italic | 16px | 1.75 | normal | Inset quotation with a left rule. |
| recruiting pages | person-name | Geist | 500 | 16px | 1.5 | normal | Name and role row in profiles. |
| platform choices and secondary-page footers | utility | ui-monospace | 400 | 14px | 20px | normal | Platform action text. |
| recruiting pages | biography | Geist | 400 | 14px | 24px | normal | Profile descriptions and inline links. |
| pricing pages | plan-action | ui-sans-serif | 700 | 12px | 16px | normal | Full-width plan buttons. |
| pricing pages | recommended-label | ui-monospace | 400 | 12px | 16px | 0.05em, uppercase | Recommended-plan badge. |

**Notes:**

- Display, section headings, plan names and prices share -0.025em tracking; body and utility text remain untracked.
- The default headline is only 36px, while interface imagery supplies the monumental scale. Quotations use the same 24px semibold recipe as feature headings.
- Use sentence case throughout; uppercase is reserved for tiny metadata labels. Default utility labels in the footer remain sans-serif; the secondary-page variant uses monospace.

## Layout

**Density:** Airy outer composition with compact inner controls: narrow feature chapters and long white pauses contrast with dense, realistic interface media.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Utility-link stacks, icon gaps and platform-action gutters. |
| 12px | Heading-to-support gap, profile content gap and footer category-to-links gap. |
| 16px | Profile padding and update-card gutters. |
| 20px | Plan-grid gutters and prose paragraph separation. |
| 24px | Panel content gaps, card padding and navigation gaps. |
| 32px | Desktop section side padding; wordmark-to-headline and headline-to-action separation. |
| 40px | Update-grid lead-in and secondary-page title-to-main-content spacing. |
| 48px | Footer column gutters and article chapter lead-in. |
| 64px | Feature chapter vertical padding and footer top padding. |
| 96px | Major section vertical padding and testimonial grid gaps. |
| 128px | Testimonial section vertical padding. |

### Containers and grids

- **navigation-container**: max width 1280px · side padding 32px. Centered header wrapper with a small mark at left and compact links grouped at right.
- **opening-copy**: max width 576px · side padding 32px. Centered outer column; text remains left-aligned and the content width is 512px.
- **feature-chapter**: max width 768px · gap 24px · side padding 32px. Single-column feature text followed by a 704px-wide demonstration.
- **wide-proof**: max width 1152px · 2 columns · gap 96px. Two-column testimonial field without visible card shells.
- **updates**: max width 1152px · 3 columns · gap 16px. Three equal update cards.
- **footer-grid**: max width 1152px · 4 columns · gap 48px. Four equal utility columns; a separate low copyright and trust row.
- **plans** (only for pricing pages): max width 1280px · 4 columns · gap 20px · side padding 32px. Four equal plan cards, 289px wide at desktop.
- **questions** (only for pricing pages): max width 576px. Narrow text-only question-and-answer column.
- **article** (only for recruiting and editorial pages): max width 768px. Left-aligned long-form narrative and stacked profile cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 6px |
|  | media-panels | 12px |
|  | release-tags | 2px |
|  | portrait-circles | 50% |
| recruiting pages | profile-cards | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| photo-action | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | White action on the photographic closing scene. |

### Surfaces

#### Canvas · level 0

**Use:** Default page and chapter background.

**CSS:** `background: #ffffff; color: #2c2826`

**Observed:** Long uninterrupted white areas rather than alternating tinted chapters.

**Transfer:** Let typography and media separate the chapters.

#### Hairline panel · level 1

**Use:** Product demonstrations and grouped comparisons.

**CSS:** `background: #ffffff; border: 1px solid #eae8e6; border-radius: 12px; overflow: hidden`

**Observed:** Flat panel with warm fine edges; most panels have no external shadow.

**Transfer:** Use the edge to contain real content, not to decorate every paragraph.

#### Utility band · level 0

**Use:** Final footer.

**CSS:** `background: #fafaf9; border-top: 1px solid #eae8e6; padding: 64px 32px 48px`

**Observed:** A subtle tonal change below the white page.

**Transfer:** Keep it low contrast and informational.

#### Sky atmosphere · level 0

**Use:** Default landing opening backdrop.

**CSS:** `background: linear-gradient(to bottom, #3598df 0%, #56c9e6 65%, #ffffff 100%)`

**Observed:** Blue upper air, brighter cyan below, cloud-like character fields, then a soft white dissolve behind the interface.

**Transfer:** Match the soft glow; exact stops are not essential. Use the character-cloud build rather than a plain gradient alone.

#### Photographic scrim · level 1

**Use:** Readable copy over the monochrome closing scene.

**CSS:** `background: rgba(0,0,0,0.4)`

**Observed:** The image and scrim dissolve together at the top; white side fades are 96px wide.

**Transfer:** Keep text contrast central while the photo edges melt into the page.

## Components

### Sticky navigation

**Use:** Persistent lightweight site navigation.

**CSS:** `position: sticky; top: 0px; z-index: 40; background: #ffffff; border-bottom: 1px solid #eae8e6; height: 57px`

**Text style:** `small` — ui-sans-serif 400 · 14px/20px

**Observed:** Small modular symbol left, links right in a horizontally scrollable group, then Dark button. Inner container uses 24px link gaps. Link text is reduced charcoal rather than full ink.

**States:** Declared: hover links become #2c2826; focus-visible outline 2px solid #413030 with 3px offset.

### Dark button

**Use:** Compact high-contrast action in the header.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #2c2826; color: #ffffff; height: 32px; padding: 12px; border-radius: 6px; box-sizing: border-box`

**Text style:** `action` — ui-sans-serif 500 · 14px/20px

**Observed:** A short text-only control, visually subordinate to the hero action. Pricing uses a full-width 36px-high variant with plan-action type; the free option is white with a hairline edge.

**States:** Declared: hover background color-mix(in oklab, #2c2826 90%, transparent); focus-visible outline 2px solid #413030 with 3px offset.

### Hero action

**Use:** Primary conversion on the sky opening.

**CSS:** `display: inline-flex; align-items: center; justify-content: space-between; width: 250px; height: 40px; padding: 16px 12px; box-sizing: border-box; background: #ffffff; color: #2c2826; border-radius: 6px; gap: 8px`

**Text style:** `action-strong` — ui-sans-serif 600 · 14px/20px

**Observed:** Label at left and 16px right arrow at the far edge; short testimonial immediately follows below.

**States:** Declared: hover background color-mix(in oklab, #fff 90%, transparent); focus-visible outline 2px solid #8c8c8c with 3px offset.

### Photo action

**Use:** Conversion inside the photographic invitation.

**CSS:** `display: inline-flex; align-items: center; justify-content: space-between; height: 40px; padding: 16px 20px; box-sizing: border-box; background: #ffffff; color: #000000; border-radius: 6px; gap: 8px; margin-top: 32px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Text style:** `closing-action` — ui-sans-serif 700 · 14px/20px

**Observed:** A download icon follows the label; the action is centered beneath a narrow two-line heading.

**States:** Declared: hover background #fff; focus-visible outline 2px solid #413030 with 3px offset.

### Update card

**Use:** Concise shipping proof.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid #eae8e6; border-radius: 0px; padding: 24px`

**Text style:** `card-heading` — ui-sans-serif 600 · 16px/1.5

**Observed:** Release badge and muted date share the top row, followed by a title after 20px. The whole card is linked; there is no image.

**States:** Declared: hover border color-mix(in oklab, #2c2826 30%, transparent); focus-visible outline 2px solid #413030 with 3px offset.

### Release badge

**Use:** Small technical metadata.

**CSS:** `display: inline-flex; align-items: center; background: #f8f7f6; color: #7d5e59; border: 1px solid #f3ece7; border-radius: 2px; padding: 2px 4px`

**Text style:** `release-label` — ui-sans-serif 400 · 12px/16px · tracking 0.05em · uppercase

**Observed:** A compact warm outlined label rather than a saturated chip. Recommended-plan variant uses 8px corners, 2px 8px padding and recommended-label type, straddling the plan's top edge.

### Footer columns

**Use:** Final information architecture on every page.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); column-gap: 48px; row-gap: 40px; max-width: 1152px; margin-left: auto; margin-right: auto`

**Text style:** `small` — ui-sans-serif 400 · 14px/20px

**Observed:** Bracketed muted category, 12px gap to a link stack with 8px gaps. Copyright and a small outlined trust symbol sit on a low separate row. Default text is sans-serif; pricing and recruiting variants use utility monospace.

**States:** Declared: hover links become color-mix(in oklab, #2c2826 70%, transparent); focus-visible outline 2px solid #413030 with 3px offset.

### Platform action

**Only for:** platform availability sections

**Use:** Equal-weight access choices below a device image.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; background: #ffffff; color: #2c2826; border: 1px solid #eae8e6; border-radius: 6px`

**Text style:** `utility` — ui-monospace 400 · 14px/20px

**Observed:** Three equal-width controls with 8px gutters align exactly to the media panel edges.

**States:** Declared: hover background #fafaf9; focus-visible outline 2px solid #413030 with 3px offset.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side commercial comparison.

**CSS:** `display: flex; flex-direction: column; position: relative; background: #ffffff; border: 1px solid #eae8e6; border-radius: 12px; padding: 24px`

**Text style:** `plan-heading` — ui-sans-serif 600 · 18px/28px · tracking -0.025em

**Observed:** Name, price with small billing suffix, full-width action and compact benefit tree. Price starts 16px below name; action block follows after 24px; benefits begin 32px later. All plans retain the same white shell; recommendation is a small badge, not a colored panel.

**Transfer:** Use branch-like └ markers with 8px text gaps and 12px/20px benefits, grouping inherited benefits under a brief lead-in.

### Question answer

**Only for:** pricing pages

**Use:** Detailed objection handling without an accordion.

**CSS:** `margin-bottom: 24px; color: #2c2826`

**Text style:** `action-strong` — ui-sans-serif 600 · 14px/20px

**Observed:** All answers stay open. A semibold question leads a muted 14px/20px answer after 4px; answers use a branch marker and 8px horizontal gap. Longer answers have 12px paragraph gaps.

### Person card

**Only for:** recruiting pages

**Use:** Human-scale profiles in a narrative page.

**CSS:** `border: 1px dashed #eae8e6; border-radius: 8px; padding: 16px; margin-top: 16px; margin-bottom: 16px`

**Text style:** `biography` — Geist 400 · 14px/24px

**Observed:** 56px portrait at left, 12px gap to name and muted role row, small social icon, then biographical paragraphs. Name row uses person-name type; descriptions are not truncated to equal heights.

**Transfer:** Pair concrete work history with one personal detail, allowing the card to grow naturally.

## Imagery and graphics

### Character sky and modular lettering

**Use:** Signature atmospheric opening for a new landing page.

**Observed:** Blue sky and cyan haze carry soft white clouds constructed from tiny code-like characters, not solid cartoon puffs. Density varies in diagonal billows at the far left and upper right, leaving the narrow copy column relatively clear. The white wordmark is a compact stencil of small rectangular modules.

**Transfer:** Use the new product's name rendered as modular lettering, with an airy technical cloud field behind it. Minimum version is an SVG glyph field masked into blurred cloud silhouettes over the Sky atmosphere.

**Build:** Fill a 1440×810 SVG with rows of 5–8px monospace punctuation and digits at 8–12px pitch. Use white glyphs at roughly 0.12–0.4 opacity; mask clusters with overlapping ellipses along broad diagonal cloud bands, lightly blur the mask rather than the lettering. Fade the whole field into white in the lower 40%. For lettering, stencil a 224×34px word silhouette with a repeated grid of small white rectangles and narrow gaps.

### Oversized working interface

**Use:** Primary product evidence, with narrower demonstrations throughout the body.

**Observed:** A light desktop application with visible window controls, sidebars, work content and a right detail pane. It floats over the sky-to-white dissolve, with 12px corners and a noticeable soft dark cast shadow. The visual is much wider than its opening copy; narrower demos use fine outlines rather than large shadows.

**Transfer:** Show a genuine complete workflow in the new product at readable scale. If no finished interface exists, make one coherent representative working view; preserve believable content and window structure rather than filling panels with decorative skeletons.

### Device detail

**Use:** Availability or ecosystem chapter.

**Observed:** A tight crop of the bottom of a phone, including colorful dock icons and curved metallic hardware, is backed by a pale neutral field inside a 704×334px outlined panel. It is an actual device detail rather than a whole floating mockup.

**Transfer:** Frame the portion of a device that makes the access story immediately recognizable; leave the product icon clear and align the action row below.

### Feathered documentary scene

**Use:** Signature human photographic invitation.

**Observed:** High-contrast black-and-white documentary photography of a person conducting an orchestra before a packed audience. The active figure sits near the center, while the crowd supplies dense texture. A dark scrim enables white copy; top and side fades join the image to the white page.

**Transfer:** Use a documentary or staged human work scene with an energetic central gesture and a textured environment. Minimum version is a monochrome photograph of real people using the new product, with sufficient room for the invitation.

**Build:** Place an object-fit:cover image in a 1280×512px overflow-hidden stage. Apply grayscale and a rgba(0,0,0,0.4) overlay. Mask the image group from transparent at top to opaque at 20% height, with intermediate alpha steps at 3%, 7%, 12% and 16%. Add 96px-wide white-to-transparent gradients on left and right. Put the centered heading and white action in an independent foreground layer.

### Editorial photo and portraits

**Only for:** recruiting and editorial pages

**Use:** Narrative interlude and profile introductions.

**Observed:** The monochrome documentary photograph appears as an unoverlaid 768×432px inline image with subtly rounded corners. Small color portraits remain candid and individual rather than uniformly art-directed.

**Transfer:** Use one full-width human image as a pause in the narrative, then authentic 56px portraits in profile rows.

### Icons

**Observed:** Small utility outlines are usually 16px with 2px rounded strokes, colored like their text. Right arrows and download symbols sit inside or immediately after actions. Social symbols are smaller solid marks; portraits are circular for endorsements and rounded squares for team profiles.

**Transfer:** Use a consistent rounded-stroke utility set. Keep decorative symbols out of feature headings unless they convey live presence or a real relationship.

## Section recipes

How recurring sections are built.

### First screen: Sky and working product opening

**Observed:** A 57px white Sticky navigation caps a full-width character sky. A centered 576px copy column is left-aligned inside 32px sides and begins with 96px top space. From back to front: sky gradient, pale glyph clouds, white modular wordmark, two-line 36px/40px promise, Hero action after 32px, a small italic endorsement and portrait attribution, then an oversized light working interface. The wordmark is 224×34px and is separated from the headline by 32px. Within the first 900px the entire pitch, action and endorsement are visible, plus the upper portion of the interface; the interface continues below the fold. The visible interface is broadly inset from the viewport sides, while the copy occupies about one third of the width.

**Transfer:** Keep the asymmetric scale relationship: narrow human-readable pitch over broad real product evidence. Rebuild the sky with the character-field recipe and modular lettering for the new identity. A comparison page instead opens with a centered display title and plan cards; a recruiting or editorial page opens with a left-aligned display title, muted introduction and long-form column on white.

**Avoid:** Do not replace this with a huge centered headline, a split-screen hero or a dark dashboard floating on a black page. Do not make the sky a repeating background for every chapter.

**Text style:** `display` — ui-sans-serif 600 · 36px/40px · tracking -0.025em

### Narrow capability chapter

**Observed:** A centered feature-chapter container uses 64px vertical padding, heading, 12px to muted body, then a 24px gap to a Hairline panel. Text and panel share the same left edge. A single underlined action with a right arrow can follow below.

**Transfer:** Explain one concrete outcome per chapter, then show the corresponding working view rather than adding a multi-card feature inventory.

**Text style:** `heading` — ui-sans-serif 600 · 24px/32px · tracking -0.025em

### Compact trust line

**Observed:** A centered 24px semibold line embeds the numerical proof directly in the phrase. Eight small customer marks form four columns and two rows, each slot 150×40px with 24px column spacing. Most marks are black, with occasional original brand color.

**Transfer:** Use a truthful compact proof statement and a small verified logo field. With no customer marks, provide equally compact real adoption or usage proof, not invented logos.

**Text style:** `heading` — ui-sans-serif 600 · 24px/32px · tracking -0.025em

### Unboxed endorsement field

**Observed:** A wide-proof grid uses two columns, 96px gutters and 128px section padding. Quotes use heading type; a 40px circle portrait and two small attribution lines follow. There are no testimonial card borders. A single underlined text action concludes the field.

**Transfer:** Let different quotation lengths create a natural editorial rhythm; retain the large gutters and modest author treatment.

**Text style:** `heading` — ui-sans-serif 600 · 24px/32px · tracking -0.025em

### Shipping proof row

**Observed:** A white band with a top rule and 96px vertical padding contains a heading, italic customer aside, then Update cards after 40px. Three equal cards span 1152px with 16px gaps, followed by a small archive link.

**Transfer:** Use this format for product progress, updates or concise dated evidence. Preserve the badge/date/title hierarchy instead of inventing a blog-image grid.

**Text style:** `heading` — ui-sans-serif 600 · 24px/32px · tracking -0.025em

### Photographic invitation

**Observed:** Feathered documentary scene contains a centered 240px-wide two-line closing-heading and Photo action. The image stage is 1280×512px and meets the Utility band directly below.

**Transfer:** End a landing narrative with a brief human invitation over relevant monochrome action photography. The headline refers conversationally to the image rather than restating a technical feature.

**Text style:** `closing-heading` — ui-sans-serif 700 · 36px/40px · tracking -0.025em

### Bracketed utility ending

**Observed:** Footer columns sit on Utility band, four columns at desktop with 48px horizontal gaps. The final copyright and trust row stays small and left-aligned. Pricing and recruiting end with this footer after informational content; the landing page places its photographic invitation before it.

**Transfer:** Provide a stable informational ending with bracketed categories and short link stacks, rather than another oversized brand statement.

**Text style:** `small` — ui-sans-serif 400 · 14px/20px

### Comparison and open answers

**Only for:** pricing pages

**Observed:** Centered display title starts 96px below navigation; 40px later four Plan cards form a 20px-gap grid. Compact trust line follows; a 576px-wide column of Question answer blocks handles details before the Utility band. No photographic conversion stage is appended.

**Transfer:** Keep comparison broad and answers narrow. Differentiate plans through benefits and actions, not increasingly colorful cards.

**Text style:** `display` — ui-sans-serif 600 · 36px/40px · tracking -0.025em

### Narrative and people

**Only for:** recruiting and editorial pages

**Observed:** Display title and muted introduction lead a 768px prose column after 40px. A dashed application callout with a small arrow tile appears early. Linked 24px medium chapter headings have 48px above and 24px below; 16px/28px paragraphs surround an inset italic quotation and inline monochrome photo. Stacked Person cards finish the content, followed by 96px of breathing room and the Utility band.

**Transfer:** Present a point of view, a concrete invitation and real people in document-like reading order. Keep this prose-led variant distinct from a media-led product landing.

**Text style:** `article-heading` — Geist 500 · 24px/32px

## Page flow

**Storyline:** Concrete promise → visible working proof → focused capability or rationale → human credibility → practical next step and utility ending.

### Product landing that makes a technical workflow tangible

1. **promise** — Atmospheric sky, modest white headline, action and a short personal endorsement.
2. **product demonstration** — Oversized desktop interface bridges the sky into the white page.
3. **social proof** — Compact numerical trust line and logo field.
4. **capability chapters** — Narrow repeated heading/support/demo compositions, ending with device access choices.
5. **human proof** — Large unboxed testimonial grid.
6. **shipping proof** — Small release cards with dated metadata.
7. **closing call** — Monochrome human-action scene with an informal invitation, then bracketed footer.

**Transfer:** Borrow the alternation of working evidence and human credibility, adapting the chapter count and placement to the new product.

### Commercial comparison with transparent explanations

1. **pricing** — Plain centered title above four equal white plan cards.
2. **social proof** — Compact trust statement and marks.
3. **objection handling** — Long fully expanded question-and-answer column with branch-like answer markers.
4. **utility ending** — Footer follows the last answer after generous breathing room; no extra CTA band.

**Transfer:** Keep the opening transactional and the lower page patiently explanatory.

### Recruiting narrative that turns a product thesis into a personal invitation

1. **invitation** — Left-aligned title, introduction, traction paragraph and small dashed application callout.
2. **rationale** — Prose chapter with inset quote and monochrome documentary interlude.
3. **human proof** — Team chapter and individually sized portrait biographies.
4. **utility ending** — Final biography leads into white breathing room and the shared footer.

**Transfer:** Use honest narrative and individual detail rather than a corporate values-card grid.

## Writing

Plainspoken, technically literate and personable. The product copy states what works; personality enters through musician-like metaphors, understated jokes and real people speaking naturally.

**Do not copy:** Do not reuse Conductor's name, modular logo asset, customer logos, named people, quotations, adoption figures, funding or growth claims, plan prices, security assertions or product-specific promises. Replace these with verified material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct verbs and 'your' in product copy, the product name when explaining mechanics, and 'we' for the team's perspective.
- **Rhythm:** Headlines are usually short sentence-case statements, often 4–8 words. Support is one or two concrete sentences; longer editorial passages use contractions and a conversational question-to-answer rhythm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Verb + concrete work + execution context. | 8–12 words | “Run a team of coding agents on your Mac.” |
| Capability heading | Short operational promise with an approachable metaphor or literal capability. | 4–8 words | “A cloud sandbox for every agent.”<br>“Bring your own subscriptions and keys.” |
| Supporting copy | Name the practical access or mechanism, avoiding a grand abstract claim. | 1–2 sentences | “Conduct from the desktop app, mobile, or your own integrations to the [Brand] API.” |
| Action | A direct acquisition or exploration verb; minimal urgency. | 2–5 words | “Get [Brand]”<br>“Learn more about Cloud” |
| Closing invitation | Casual reference to the image, then a short request to try the product. | 2 short sentences | “Be like this guy. Try [Brand].” |
| Editorial heading | Simple possessive label rather than a manifesto slogan. | 2 words | “Our plan”<br>“Our team” |

**Words and phrasing to use:** run; build; your own; in seconds; learn more; try; we think; under the hood

**Avoid:** revolutionize everything; unleash limitless potential; synergize; best-in-class; supercharge your journey

**Rules:**

- Tie each feature heading to a mechanism or visible workflow in its support text.
- Use restrained wit in a small number of memorable places, not every button.
- Preserve natural phrasing in genuine testimonials instead of rewriting every voice into marketing prose.
- Answer practical commercial questions directly; disclose relevant constraints in readable paragraphs.

## Do's and Don'ts

### Do

- Keep primary display text at 36px/40px with weight 600 and -0.025em tracking.
- Concentrate bright blue and cyan in the opening atmosphere; keep the body on white.
- Stage the main interface much wider than the 576px opening copy column.
- Use 704px content width for the focused capability demonstrations.
- Keep 6px action corners distinct from 12px media-panel corners.
- Set testimonial quotes at 24px/32px and give their grid 96px gutters.
- Use the feathered monochrome human image as a memorable landing-page counterpoint.
- End with bracketed footer categories and a very pale warm background.

### Don't

- Do not introduce a neon accent system for ordinary links or plan cards.
- Do not turn 32–40px actions into oversized 56px pill controls.
- Do not apply the hero interface's cast shadow to every card; most shells are flat hairlines.
- Do not use 64–96px marketing headlines; the product visual carries the scale.
- Do not wrap every endorsement in a bordered or tinted card.
- Do not convert the open pricing explanations into collapsed accordion rows.
- Do not use a huge footer wordmark in place of the four compact utility columns.
- Do not use monospace for the default marketing paragraphs or headings.

## Motion and responsive

### Motion

**Observed:**

- Color transitions are declared at 0.15s cubic-bezier(.4, 0, .2, 1) on utility actions and cards.
- The navigation's overflow mask has a linear scroll-linked animation.
- Hero entrance/parallax and demo animation names are declared; the testimonial wrappers declare opacity/translation transitions.

**Transfer:**

- Keep control motion confined to the measured color-state transitions and preserve the navigation's overflow affordance.
- Any entrance treatment should leave the working interface and quotations readable in their resting positions.

**Unknown:**

- Exact hero entrance, parallax trajectories and their runtime timing are not established.
- No observed mobile motion sequence is available.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- The footer declares two columns before four; plan cards declare two columns at the medium tier and four at the large tier.
- Feature wrappers declare 16px, 24px and 32px horizontal padding variants. Navigation's desktop link group is hidden below the medium tier.
- Update cards declare horizontal snapping and a min(82vw, 384px) card width before the desktop grid.

**Transfer:**

- Retain the narrow left-aligned pitch above the product visual as the viewport shrinks; keep media proportional rather than shrinking the entire desktop composition into unreadable miniature.
- Use the declared grid tiers for plans and footer, and preserve the update row's horizontal browsing behavior on narrow widths.
- Keep the monochrome image's central subject and invitation together when side fades disappear.

**Unknown:**

- Exact rendered mobile navigation and line wrapping are not verified.
- The hero headline has a conflicting class-level formula and resolved desktop value; no fluid formula is asserted.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
