# Tana — work through a prism

## Overview

An editorial software style that pairs bookish serif headlines with matter-of-fact sans-serif explanations. The light, almost-white canvas opens into peach, rose and blue gradients, layered interfaces and atmospheric photographs touched by refracted light. It suits collaborative tools and complex products that need to feel human and immediately useful, with sparse copy around substantial visual demonstrations.

### Essentials

- Bookish promises stay surprisingly compact: Source Serif 4 at 48px/1.1, weight 500 and -0.045em tracking opens the default landing page; recurring feature headings use 32px/1.15 with the same tracking.
- The opening is a horizontal editorial strip above a product theater: a 544px copy column faces a right-aligned action, followed by a full-width 720px pastel stage with an 806×504px main window and an overlapping task panel.
- Actions are small dark objects, not colored pills: the principal button is warm black, 54px high, with 14px corners, 14px 28px padding and 17px/1.5 Inter at weight 500.
- Color belongs to demonstrations and light, not the reading canvas: keep the majority of text sections on #fbfbfb; contain stronger blue-to-peach and peach-to-mint gradients inside 14px-corner visual panels.
- Refracted light is a signature material: include rainbow-edged photographic light and a translucent faceted object, with a minimum fallback of layered SVG planes and soft spectral bands if original photographic media is unavailable.
- Proof is staged at two scales: narrow 15px/1.5 explanations beside wide interface scenes, then immersive 420×616px photo cards with 11px uppercase labels and bottom-anchored serif outcomes.
- The final conversion feels like an editorial invitation: an isolated 360×520px translucent object faces a 60px serif heading, brief explanation and frosted split action; the footer returns to four unboxed columns with 96px gutters.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty blue | `#c9cfe0` | `--color-stage-blue` | background | Cool end of the full-width demonstration stage. |
| Dusty rose | `#e2c9d3` | `--color-stage-rose` | background | Middle of the broad pastel stage; strengthened with a pink radial light at the upper right. |
| Stage peach | `#f1d2b0` | `--color-stage-peach` | background | Warm end of the opening stage. |
| Icy window blue | `#d9e3f7` | `--color-window-blue` | surface | Pale blue browser-window backing. |
| Spectral blue | `#3f62d8` | `--color-spectral-blue` | background | Saturated cool endpoint inside a feature demonstration, never a default action color. |
| Spectral purple | `#7d6bc9` | `--color-spectral-purple` | background | Transition between blue and warm hues inside feature panels. |
| Soft peach | `#f4c9b0` | `--color-peach` | background | Warm endpoint of peach-to-mint demonstration panels. |
| Pastel cream | `#f4dfb0` | `--color-cream` | background | Light yellow transition in feature panels. |
| Pastel mint | `#cfe7c9` | `--color-mint` | background | Green transition in feature panels. |
| Pastel aqua | `#a7dbe6` | `--color-aqua` | background | Cool endpoint in feature panels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Text over dark imagery and raised interface layers; translucent layers use white at 60%, 72%, 85% or 92% depending on backing. |
| Almost white | `#fbfbfb` | `--color-canvas` | background | Dominant page canvas and footer. |
| Panel gray | `#f6f6f6` | `--color-soft-panel` | surface | Flat trust cards and light explanation panels. |
| Hairline gray | `#eeeeee` | `--color-rule` | border | FAQ dividers and faint card outlines. |
| Secondary gray | `#6a6a6a` | `--color-muted` | text | Reassurance, captions, footer metadata and secondary answers. |
| Charcoal | `#3a3a3a` | `--color-body` | text | Paragraphs and navigation text. |
| Warm black | `#0c0805` | `--color-ink` | text, action, surface | Headlines, primary actions and contrasting explanation panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Brown ink | `#281a14` | `--color-pricing-ink` | text | Plan names, figures and feature lists. |
| people directories | Warm portrait ground | `#edeceb` | `--color-portrait-ground` | surface | Visible warm gray behind portrait media, built with rgba(32,16,0,0.063) over the canvas. |

## Typography

- **Source Serif 4** — Promises, feature headings, photographic outcomes and editorial statements. Readable literary serif with tapered strokes and compact, tightly tracked display settings. Font stack: "Source Serif 4", Georgia, serif.
- **Inter** — Explanations, navigation, actions, captions and pricing figures. Neutral, high-x-height sans-serif; regular body text and medium actions keep the serif from becoming ornate. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading-lg | Source Serif 4 | 500 | 60px | 1.08 | -0.045em | fixed | Isolated closing invitation and expansive section leads. |
| display | Source Serif 4 | 500 | 48px | 1.1 | -0.045em | fixed | Default landing-page headline and large statements over photography. |
| heading | Source Serif 4 | 500 | 32px | 1.15 | -0.045em | fixed | Default feature chapters, audience statements and section headings. |
| photo-outcome | Source Serif 4 | 500 | 25.9px | 1.2 | -0.045em | size clamp(20px, 1.8vw, 26px) | Bottom-anchored text on photographic cards. |
| hero-support | Inter | 500 | 17px | 1.55 | normal | fixed | Opening explanation beneath the main headline. |
| action | Inter | 500 | 17px | 1.5 | normal | fixed | Principal conversion actions. |
| closing-support | Inter | 400 | 17px | 1.5 | normal | fixed | Explanation beside the faceted closing object. |
| faq-question | Inter | 500 | 16px | 1.4 | normal | fixed | Default FAQ summary rows. |
| trust-title | Inter | 600 | 16px | 1.3 | -0.01em | fixed | Short titles in flat trust cards. |
| body | Inter | 400 | 15px | 1.5 | normal | fixed | Feature explanations, standard text links, captions and footer links. |
| navigation | Inter | 500 | 14px | 1.5 | normal | fixed | Navigation items and compact utility actions. |
| reassurance | Inter | 400 | 13px | 1.5 | -0.005em | fixed | Short reassurance beneath an action. |
| metadata | Inter | 400 | 13px | 1.5 | normal | fixed | Footer copyright and social contacts. |
| photo-label | Inter | 400 | 11px | 1.5 | 0.08em, uppercase | fixed | Category marking at the top of photographic cards, not a universal section eyebrow. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| category explainer pages | category-display | Source Serif 4 | 500 | 72px | 1.05 | -0.045em | fixed | Centered two-line promise in a warm atmospheric opening. |
| calculator-led editorial pages | calculator-display | Source Serif 4 | 400 | 72px | 1.05 | -0.045em | size clamp(32px, 5.2vw, 72px) | Interactive statement with an inline linked figure. |
| pricing pages | pricing-display | Source Serif 4 | 400 | 60px | 1.05 | -0.045em | fixed | Two-line proposition with a linked, underlined inline figure. |
| company pages | company-display | Source Serif 4 | 400 | 52px | 1.15 | -0.015em | fixed | Left-aligned organizational statement above documentary photography. |
| editorial manifesto pages | essay-heading | Source Serif 4 | 400 | 50px | 1.15 | -0.045em | size clamp(28px, 4vw, 50px) | Photographic manifesto statement; the reading-column variant keeps the same desktop recipe. |
| editorial manifesto pages | editorial-closing | Source Serif 4 | 400 | 40px | 1.15 | -0.045em | size clamp(1.75rem, 3.5vw, 2.5rem) | Centered closing statement above a single action. |
| people directories | directory-heading | Source Serif 4 | 400 | 32px | 1.5 | -0.01em | fixed | Side-rail labels beside a people grid. |
| pricing pages | plan-name | Inter | 400 | 32px | 1.1 | -0.01em | fixed | Plan names in unboxed pricing columns. |
| pricing pages | price | Inter | 600 | 32px | 1.12 | -0.02em | fixed | Prices with currency and billing qualifier beneath. |
| category explainer pages | capability-title | Source Serif 4 | 500 | 25px | 1.2 | -0.01em | fixed | Card titles and three-part benefit lists. |
| category explainer pages | editorial-question | Source Serif 4 | 500 | 25px | 1.2 | normal | fixed | Large literary FAQ summaries. |
| editorial manifesto pages | essay-body | Inter | 400 | 18px | 1.65 | normal | fixed | Extended argument in a narrow reading column. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use the 48px opening and 32px chapter heading as the default, rather than inheriting the 72px category-explainer opening.
- The core serif scale holds -0.045em tracking across sizes; directory and company typography is looser and regular weight.
- Body text remains modest next to visual scenes. Reserve uppercase tracking for labels on imagery, rather than adding eyebrows to every section.
- Underline only an intentional inline link or a key linked figure; do not underline every headline.

## Layout

**Density:** Airy sections surrounding compact explanations and layered product scenes; the page alternates broad visual occupancy with long stretches of nearly white space.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer list gaps and compact heading-to-description gaps. |
| 12px | Trust-card internal rhythm. |
| 16px | Feature heading to explanation. |
| 24px | Hero heading to support; photographic-card padding and editorial paragraph gaps. |
| 28px | Trust-card padding. |
| 32px | Container side padding. |
| 40px | Opening strip bottom padding and larger panel interiors. |
| 48px | Feature-row vertical padding. |
| 56px | Explainer-card padding and major heading-to-content separation. |
| 86.4px | Default feature split gutter and opening strip horizontal inset inside the wide container. |
| 96px | Major section vertical padding and footer column gutters. |
| 152px | Loose centered openings, footer top padding and closing-object separation. |
| 192px | Deep separation before the pricing FAQ and space after editorial content. |

### Containers and grids

- **main-container**: max width 1280px · side padding 32px. Centered desktop container with 1216px inner content width.
- **wide-stage**: max width 1440px · side padding 32px. Opening copy strip and wide visual scenes; visual backdrops themselves run edge to edge.
- **feature-split**: 2 columns · gap 86.4px. A 4:8 text-to-visual split, centered vertically; alternate which side carries the 753×472px visual.
- **trust-grid**: 3 columns · gap 20px. Three equal flat cards across the main container.
- **faq-split**: 2 columns · gap 96px. A 3:7 split with an introduction on the left and 784px question list on the right.
- **reading-column** (only for editorial pages): max width 604px · side padding 32px. Centered long-form argument, with generous empty side margins.
- **explainer-grid** (only for category explainer pages): max width 960px · 2 columns · gap 24px. Two-column integration proof cards; use a three-column, 56px-gutter variant for use-case cards.
- **pricing-columns** (only for pricing pages): max width 1400px · 3 columns · gap 43.2px · side padding 32px. Three unboxed plans with aligned actions and ample vertical space between figures and benefits.
- **directory** (only for people directories): 4 columns · gap 20px. Four 221px portrait columns beside a 160px section-label rail; 28px row gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-panels | 14px |
|  | photo-cards | 20px |
|  | photo-secondary-actions | 9999px (pill) |
| people directories | portraits | 12px |
| category explainer pages | explainer-cards | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | hero-window | `rgba(12, 8, 5, 0.08) 0px 4px 10px 0px, rgba(12, 8, 5, 0.17) 0px 44px 92px 0px` | Large pale-blue window floating on the pastel stage. |
|  | assistant-panel | `rgba(20, 22, 36, 0.12) 0px 2px 6px -2px, rgba(20, 22, 36, 0.3) 0px 24px 48px -20px` | Foreground product panel overlapping the main window. |
| category explainer pages | explainer-card | `rgba(20, 22, 36, 0.04) 0px 1px 2px 0px, rgba(20, 22, 36, 0.1) 0px 6px 18px -12px` | Barely raised capability cards. |

### Surfaces

#### Canvas · level 0

**Use:** Reading sections and footer.

**CSS:** `background: #fbfbfb`

#### Pastel theater · level 0

**Use:** Full-width opening product stage.

**CSS:** `background: radial-gradient(60% 70% at 85% 10%, rgba(236,196,210,0.9) 0px, rgba(236,196,210,0) 70%), radial-gradient(60% 80% at 10% 100%, rgba(244,209,178,0.95) 0px, rgba(244,209,178,0) 70%), linear-gradient(135deg, #c9cfe0, #e2c9d3 45%, #f1d2b0); overflow: hidden`

**Observed:** A broad, smooth, untextured field behind the main window; the warm and cool areas are large rather than spotlike.

**Transfer:** Keep this color outside the text strip and let it back a concrete product scene.

#### Spectral feature panel · level 1

**Use:** Framing demonstrations in alternating feature rows.

**CSS:** `background: linear-gradient(135deg, #f4c9b0, #f4dfb0 30%, #cfe7c9 60%, #a7dbe6); border-radius: 14px; overflow: hidden`

**Observed:** Other panels run from saturated blue through lavender and rose to gold, or from pale gold through pink to purple. White task fragments float inside with broad colored margins.

**Transfer:** Vary the spectral direction between related demonstrations without turning each card into a different visual system.

#### Flat proof panel · level 1

**Use:** Trust cards and one side of a paired explanation.

**CSS:** `background: #f6f6f6; border-radius: 14px`

**Observed:** No visible outline or drop shadow; dark paired variants invert to warm black with white text.

**Transfer:** Use the light/dark pair to distinguish two complementary layers, not competing plans.

#### Frosted utility · level 2

**Use:** Copy/export action beside the closing object.

**CSS:** `background: rgba(255,255,255,0.6); border-radius: 14px; box-shadow: rgba(255,255,255,0.6) 0px 1px 0px 0px inset; backdrop-filter: blur(12px) saturate(1.4); overflow: hidden`

**Observed:** A blurred spectral image sits behind a pale radial veil, producing a faint rainbow sheen rather than an opaque gradient button.

**Transfer:** Back the control with a blurred version of the adjacent spectral object.

#### Warm editorial wash · level 0

**Only for:** category explainers and editorial essays

**Use:** Atmospheric text-first openings, closing calls and long-form reading bands.

**CSS:** `background: linear-gradient(#fbfbfb 0px, rgba(0,0,0,0) 22%), linear-gradient(0deg, #fbfbfb 0px, rgba(0,0,0,0) 22%), linear-gradient(135deg, rgba(255,228,219,0) 0px, rgba(220,174,135,0.4) 54%, rgba(206,153,129,0.4) 67%, rgba(235,201,194,0.4) 78%, rgba(255,254,253,0.3) 89%), #fbfbfb`

**Observed:** A soft diagonal beige-to-rose wash disappears into the page at top and bottom.

**Transfer:** Keep it diffuse enough that charcoal paragraphs remain easy to read.

## Components

### Sticky navigation

**Use:** Persistent orientation with a compact conversion action.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 72px; background: rgba(251,251,251,0.212); backdrop-filter: saturate(1.33898) blur(11.9px)`

**Text style:** `navigation` — Inter 500 · 14px/1.5

**Observed:** Identity at left, two centered links, a muted secondary-product link and compact download action at right. Inner side padding is 32px; links use 8px 16px padding.

**Transfer:** Preserve the sparse three-zone arrangement rather than expanding to a dense menu.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 10px; background: #0c0805; color: #ffffff; border-radius: 14px; padding: 14px 28px; height: 54px`

**Text style:** `action` — Inter 500 · 17px/1.5

**Observed:** An 18px platform icon precedes the label. A centered reassurance line sits beneath. Pricing uses outlined equivalents on the outer plans and a solid action on the middle plan.

**States:** Declared: hover translateY(-1px) and background #000000; focus-visible 2px solid #0c0805 outline with 2px offset.

**Transfer:** Choose an accurate platform icon or a simple functional symbol; keep the warm-black action dominant.

### Navigation link

**Use:** Short header destinations.

**CSS:** `display: flex; align-items: center; padding: 8px 16px; border-radius: 14px; color: #3a3a3a`

**Text style:** `navigation` — Inter 500 · 14px/1.5

**Observed:** Text-only links occupy the center rather than filling the whole navigation bar.

**States:** Declared: hover color #0c0805 and a 6% warm-black background; focus-visible 2px solid #0c0805 outline with 2px offset.

### Trust card

**Use:** Specific reassurance in a three-column proof row.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 28px; background: #f6f6f6; border-radius: 14px`

**Text style:** `trust-title` — Inter 600 · 16px/1.3 · tracking -0.01em

**Observed:** Small outline icon, short sans-serif title, then a compact paragraph using body. Evidence badges form an unboxed row below the cards.

**Transfer:** Give each card one concrete control, protection or portability benefit.

### FAQ row

**Use:** Compact objection handling in a split layout.

**CSS:** `border-bottom: 1px solid #eeeeee; padding: 18px 0px; color: #0c0805`

**Text style:** `faq-question` — Inter 500 · 16px/1.4

**Observed:** Native disclosure construction, question on the left and an 18px chevron on the right; the list also has a top rule. Answers use body in muted gray. Category explainers instead use editorial-question in an 896px list; pricing uses 18px/1.5 medium Inter in a 720px centered list.

**States:** Declared: hover unspecified; focus-visible 2px solid #0c0805 outline with 2px offset.

### Photographic outcome card

**Use:** Immersive audience or use-case proof in a horizontal strip.

**CSS:** `position: relative; width: 420px; height: 616px; border-radius: 20px; overflow: hidden`

**Text style:** `photo-outcome` — Source Serif 4 500 · 25.9px/1.2 · tracking -0.045em

**Observed:** Cover photograph, dark gradient scrim, category label at top and a narrow outcome statement at bottom, all inset 24px. Cards continue off the right edge with 24px gaps. A reverse face contains a description, outcome list and translucent pill action.

**States:** Declared: hover unspecified; focus-visible 2px solid #0c0805 outline with 3px offset.

**Transfer:** Use a real activity photograph and an outcome that a new audience can recognize.

### Export split action

**Use:** Let readers take a product brief into another tool.

**CSS:** `display: flex; height: 52px; background: rgba(255,255,255,0.6); border-radius: 14px; backdrop-filter: blur(12px) saturate(1.4); box-shadow: rgba(255,255,255,0.6) 0px 1px 0px 0px inset; overflow: hidden`

**Text style:** `navigation` — Inter 500 · 14px/1.5

**Observed:** Copy icon and main label occupy the larger segment with 22px side padding; a narrow chevron segment offers more formats. Pale spectral light shows through the control.

**States:** Declared: hover background rgba(0,0,0,0.04); focus-visible 2px currentColor outline with -2px offset.

**Transfer:** Offer a portable brief or equivalent useful document rather than another generic signup button.

### Footer link columns

**Use:** The common ending after the page-specific closing content.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); column-gap: 96px; row-gap: 56px`

**Text style:** `body` — Inter 400 · 15px/1.5

**Observed:** Three text-link columns and one small related-product mark. Labels are muted 15px text with 14px below; link lists use 8px gaps. The 1280px outer container has 152px top and 56px bottom padding. A 96px gap separates columns from copyright at left and small social/contact links at right.

**Transfer:** Keep the footer on the same canvas, without a contrasting background or a large closing wordmark.

### Explainer capability card

**Only for:** category explainer pages

**Use:** Integration or use-case proof grouped into two- or three-column grids.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 56px; background: rgba(255,255,255,0.85); border: 1px solid #eeeeee; border-radius: 6px; box-shadow: rgba(20, 22, 36, 0.04) 0px 1px 2px 0px, rgba(20, 22, 36, 0.1) 0px 6px 18px -12px`

**Text style:** `capability-title` — Source Serif 4 500 · 25px/1.2 · tracking -0.01em

**Observed:** An integration mark or tiny pastel icon sits above a serif title, body explanation and subtle text link or small bordered result chip.

**States:** Declared: hover border #e5e5e5, translateY(-2px), and stronger two-layer shadow; focus-visible 2px solid #0c0805 outline with 2px offset.

### Unboxed plan

**Only for:** pricing pages

**Use:** Comparable subscriptions without a stack of bordered cards.

**CSS:** `display: grid; position: relative`

**Text style:** `plan-name` — Inter 400 · 32px/1.1 · tracking -0.01em

**Observed:** Name, bold price, billing qualifier, one-sentence value, feature list and bottom-aligned full-width action. Plans are 417px wide at desktop with 43.2px gutters. The featured plan has a small warm gradient offer badge and a struck-through former price; selection is not expressed as a large colored card.

**Transfer:** Align benefits and actions across plans while keeping the surrounding canvas open.

### Portrait tile

**Only for:** people directories

**Use:** Team members and organizational supporters.

**CSS:** `background: rgba(32,16,0,0.063); border-radius: 12px; overflow: hidden; width: 221px; height: 221px`

**Text style:** `body` — Inter 400 · 15px/1.5

**Observed:** Square image followed outside its frame by a name and role; names use 15px/1.35 medium Inter, roles 14px/1.4 regular Inter. The image-to-metadata gap is 10px, with 2px between name and role.

**Transfer:** Use consistent bust framing where possible, but allow documentary portraits for outside collaborators.

## Imagery and graphics

### Layered product theater

**Use:** Opening and capability demonstrations.

**Observed:** A large pale-blue desktop window contains two warmly lit human video portraits. A translucent white assistant panel overlaps its right side and carries three distinct result cards. The window is 806×504px, the foreground panel 432×408px; shadows separate them from a smooth full-bleed pastel ground.

**Transfer:** Show the new product's real working surface with a few legible outputs. If no polished UI exists, construct one plausible window and three concrete result cards rather than an empty mockup.

**Build:** Use Pastel theater behind a 14px-radius window with a pale-blue 168deg gradient. Add the hero-window shadow, then overlap a white-at-72% panel by roughly one tenth of the main window width. Keep the scene readable as a whole rather than enlarging every internal label.

### Spectral demonstration backings

**Use:** Alternating wide visual panels beside narrow explanations.

**Observed:** Smooth multi-stop fields in blue/lavender/rose/gold or peach/cream/mint/aqua. They fill 753×472px panels with 14px corners. White interface fragments occupy the center with substantial visible gradient around them.

**Transfer:** Use different spectral directions for different capabilities while retaining the same frame and scale.

**Build:** Use the Spectral feature panel gradient as the light variant. For the stronger variant use a 160deg linear gradient with rgba(63,98,216,1), rgba(125,107,201,1) at 32%, rgba(201,138,166,1) at 58%, rgba(231,180,138,1) at 82%, rgba(240,198,110,1). Center one coherent task UI; stagger auxiliary cards slightly rather than filling the frame.

### Refracted work photography

**Use:** Immersive photo cards and full-width editorial statements.

**Observed:** People working or conversing in real interiors, often seen through reflective glass. Deep forest shadows, warm sunlight and blue window reflections carry soft rainbow refractions across the foreground. Cover images remain recognizable, with a dark gradient behind white serif text.

**Transfer:** Commission or select candid images of the new audience doing meaningful work. The minimum alternative is a well-lit workplace photograph with restrained spectral overlays, not a generic abstract wallpaper.

**Build:** Layer a cover photograph, a left-to-right black scrim at 60%, 35% near 40% width and 10% at the far edge, then a few broad irregular SVG ribbons crossing the lower foreground. Fill ribbons with a low-opacity spectrum, blur their edges and use screen blending so they read as refracted light rather than stripes. For cards use a vertical scrim from 18% black at top to 70% at bottom.

### Faceted closing object

**Use:** The isolated final invitation before the footer.

**Observed:** A translucent vertical prism-like object floats directly on the almost-white canvas, with pale icy planes and a more saturated cyan-to-lavender side. Its media area is 360×520px and visually balances a compact text block across a 152px gap.

**Transfer:** Create a new faceted symbol related to the product's idea, retaining translucency and the asymmetry of light and color. A simple three-plane SVG is the minimum acceptable equivalent.

**Build:** Within a 360×520px SVG, assemble three large polygon faces meeting at one central vertex: a nearly white upper plane, a faint lavender left plane and a cyan/lavender/mint right plane. Use linear gradients with white at 60–90% alpha on the pale faces and aqua/mint at 50–85% on the colored face. Keep edges crisp, avoid a heavy outline, and use multiply blending against the canvas.

### Documentary workplace and portrait grid

**Only for:** company pages and people directories

**Use:** Human proof, team introductions and supporters.

**Observed:** A large rounded office photograph follows an editorial statement. Two 552×368px candid conversation images sit side by side with informal captions 12px below. The portrait grid uses warm gray grounds, relaxed clothing and soft rainbow highlights behind many subjects; supporter logos alternate with portraits in the same square format.

**Transfer:** Use actual workplaces, natural gestures and consistent bust portraits. Keep captions specific and human rather than promotional.

**Build:** For portrait light, place one or two soft diagonal spectral bands on a warm neutral background behind the subject, preserving natural skin tones. Do not lay saturated color across faces.

### Icons

**Observed:** Functional symbols are small and understated: 18px action icons and chevrons, 2px round strokes for disclosure chevrons, roughly 24–34px trust or integration marks. External product logos retain their own identity inside demonstrations.

**Transfer:** Use a consistent simple outline set for marketing benefits; keep filled platform marks only where they identify a real platform or integration.

## Section recipes

How recurring sections are built.

### First screen: Editorial strip and product stage

**Observed:** A 72px sticky navigation precedes a nearly white strip with 72px top and 40px bottom padding. The left-aligned display headline occupies about one third of the inner width, followed after 24px by a 544px-wide, three-line hero-support paragraph. A Primary button and reassurance sit at the far right, aligned toward the bottom of the copy. Beneath this strip the Pastel theater begins about 340px from the top of the viewport and fills the full width. Back to front: broad blue/rose/peach field, pale-blue 806×504px window with two human portraits, overlapping white assistant panel with finished output cards. Within the first 900px the headline, support, action and most of the main scene are visible; the lower edge of the window and integration-logo strip continue below the fold.

**Transfer:** Keep the headline modest and the proof object large. Replace the video-call content with a tangible working surface and a few output artifacts for the new product. Text-first category explainers open instead with a centered 72px promise over Warm editorial wash; company pages open with a 52px left-aligned statement and a wide documentary image; pricing uses an inline linked figure and open plan columns.

**Avoid:** Do not substitute a centered giant headline above a tiny isolated dashboard, or put all opening copy over the gradient.

**Text style:** `display` — Source Serif 4 500 · 48px/1.1 · tracking -0.045em

### Alternating capability chapter

**Observed:** Feature-split pairs a narrow heading/body block with a 753×472px Spectral feature panel, centered vertically. Heading uses heading, description uses body with 16px separation and about 321px reading width. Rows have 48px top and bottom padding; visual placement alternates.

**Transfer:** Let one demonstration prove one claim. Alternate the visual side to create rhythm without changing the construction.

**Text style:** `heading` — Source Serif 4 500 · 32px/1.15 · tracking -0.045em

### Before and after proof

**Observed:** A centered heading sits above a full-width pale blue horizontal wash that fades to the canvas at both edges. Two 588×645px translucent white, 14px-radius panels compare similarly framed schedules; changed outputs and recovered space provide the contrast.

**Transfer:** Choose a familiar before/after artifact for the new product and keep its framing identical across both sides. The proof should be visible in the content, not in exaggerated red/green marketing colors.

### Complementary explanation pair

**Observed:** A centered two-line 32px serif statement precedes two broad 14px-radius panels, one soft gray and one warm black. Each contains a small icon, 25px serif subhead and 15px body; text reverses to white on the dark panel.

**Transfer:** Explain a front-stage experience and its underlying system, or two complementary benefits, with balanced visual weight.

### Photographic audience strip

**Observed:** A left-aligned heading introduces Photographic outcome cards at 24px intervals. The next card is partly visible at the right edge. Photo labels sit high while outcomes sit low; reverse faces carry more details over a blurred image.

**Transfer:** Adapt to audience types or jobs-to-be-done, using a concrete outcome instead of a demographic slogan.

### Trust and objections

**Observed:** Trust cards form a flat three-column row with a low-key badge line below. The later FAQ uses the faq-split: short title and muted support at left, ruled FAQ rows at right.

**Transfer:** State controls and limits in plain language. Keep proof marks visually secondary to explanations.

### Photographic quantified statement

**Observed:** A 720px-tall edge-to-edge work photograph carries a left-anchored 48px white serif statement in a narrow column. A linked figure is underlined within the sentence; a small paragraph and underlined text action follow. A dark scrim protects the text while people and spectral foreground light remain prominent.

**Transfer:** Use a defensible metric or memorable statement tied to the new product's value; retain a human scene and a compact text column.

### Portable brief closing

**Observed:** The Faceted closing object faces a heading-lg title, closing-support paragraph and Export split action. A 1180px flex composition centers the two objects with a 152px gap; the section uses 96px 32px padding and remains on the Canvas.

**Transfer:** End with an invitation to investigate or share a useful brief. Keep the isolated spectral object even when the action is adapted to a different product.

**Text style:** `heading-lg` — Source Serif 4 500 · 60px/1.08 · tracking -0.045em

### Common footer ending

**Observed:** Footer link columns sit on the Canvas after generous separation. A 152px top inset and 96px gap before the bottom metadata row give the ending unusual breathing room. Copyright is left aligned and social/contact destinations sit right aligned in 13px muted Inter.

**Transfer:** Use the same restrained ending across page types; let the preceding content determine whether a conversion call is appropriate.

### Editorial essay and closing

**Only for:** editorial manifesto pages

**Observed:** A calculator-led opening places a 72px serif statement and two actions opposite four spare horizontal sliders. Numeric outputs remain inline in the prose and are underlined. A full-width photograph leads into a 604px reading column on Warm editorial wash: 50px heading, 56px separation to 18px/1.65 paragraphs with 24px gaps. A centered 40px serif promise and single Primary button close the argument before the common footer.

**Transfer:** Use an honest adjustable model when readers can meaningfully explore value, then a coherent essay rather than a collection of feature cards.

### Company editorial directory

**Only for:** company pages

**Observed:** A 52px statement with an 880px maximum width introduces a broad office photograph. Employer marks and paired candid images lead into a directory. A 160px left rail holds 32px serif section labels; four portrait columns sit to its right. Backers use the same squares for logos and people. The final directory row passes directly into the common footer without a conversion banner.

**Transfer:** Make the people and their setting carry the story; preserve the human caption treatment and restrained metadata.

### Open pricing comparison

**Only for:** pricing pages

**Observed:** A two-line 60px serif proposition sits above a left-aligned yearly/monthly toggle. Three Unboxed plan columns share aligned baseline figures and actions, with no enclosing card fills. A tiny warm gradient offer badge distinguishes the featured plan. A compact reassurance row leads into a centered 720px FAQ with a 32px medium sans-serif title, then the common footer.

**Transfer:** Prioritize comparison and explicit terms over a visually inflated recommended plan.

## Page flow

**Storyline:** Concrete promise → visible product proof → capability or human context → credible outcomes → objections → an invitation to act or investigate → open directory footer.

### Flagship product landing page

1. **promise** — Compact editorial strip with a separate right-side action.
2. **product demonstration** — Large layered scene followed by integration marks and an audience statement.
3. **capability chapters** — Alternating gradient-backed demonstrations and a before/after comparison.
4. **system explanation** — Complementary light/dark panels explain the experience and underlying structure.
5. **outcome proof** — Horizontal photographic cards followed by trust cards and badges.
6. **closing argument** — Full-bleed human photograph with an inline linked figure.
7. **objection handling** — Split FAQ followed by a portable brief beside a faceted object.
8. **ending** — Four-column open footer and understated metadata.

**Transfer:** Borrow the contrast between brief explanation and substantial demonstration; choose only the beats needed for the new product.

### Category explainer

1. **promise** — Centered large serif title and action on a warm wash.
2. **definition** — Three-part explanation beside a framed product image.
3. **reframing** — Full-width photographic statement and narrow prose.
4. **capabilities** — Integration and use-case grids, then a sparse three-benefit row.
5. **objection handling** — Large serif disclosure questions.
6. **closing call** — Centered short three-part promise, action and reassurance on a fading warm wash.
7. **ending** — Common open footer.

**Transfer:** Use the larger, centered typography only when the page must explain a category before selling a workflow.

### Company and people introduction

1. **purpose** — Left-aligned literary statement and large office photograph.
2. **credibility** — Prior-organization logos and candid image pair with conversational captions.
3. **human proof** — Long side-labeled team directory followed by supporters using the same square system.
4. **ending** — Direct transition from the final portrait row to the common footer.

**Transfer:** Favor people and places over product conversion furniture.

### Value calculator and editorial argument

1. **quantified hook** — Linked inline figure in a large serif sentence opposite four adjustable sliders.
2. **purpose** — Human photographic band with a white serif statement.
3. **argument** — Narrow long-form prose over a soft warm wash.
4. **closing call** — Centered compact promise, single download action and reassurance.
5. **ending** — Open footer after substantial white space.

**Transfer:** Keep the calculation tied to a real reader decision and let the essay explain its implications.

### Plan selection

1. **value framing** — Serif proposition with an underlined figure and narrow promotional ribbon.
2. **pricing** — Billing toggle and three spacious unboxed plan columns.
3. **reassurance** — Small shared capability row and centered FAQ.
4. **ending** — Common footer, without another sales hero.

**Transfer:** Retain the sparse comparison and practical objections rather than importing every flagship visual device into pricing.

## Writing

Confident, practical and slightly irreverent about familiar workplace frustrations. Claims are grounded in visible actions and outputs rather than technological grandeur.

**Do not copy:** Do not reuse Tana names, logo or prism identity, named people, customer examples, quoted claims, compliance promises, prices or career-hour figures. Source phrases illustrate cadence only; replace them with truthful language and proof for the new product.

- **Addressing the reader:** Speak directly to you and your team. Refer to the product by name when describing an action; use we sparingly in organizational writing.
- **Rhythm:** Short outcome headlines followed by one compact explanation. Fragments and lists of completed actions create pace; longer editorial passages use ordinary sentences and specific examples.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A familiar activity plus an unexpected concrete outcome. | 3–6 words | “Meetings that ship”<br>“Meetings that do the work” |
| Feature heading | Promise a resolved frustration, often through a conversational phrase. | 4–7 words | “Aligned without another meeting”<br>“Done before you hang up” |
| Card title | Name the artifact, then its finished state. | 2–3 words | “Issues, filed”<br>“PRs, drafted” |
| Supporting explanation | Identify a concrete artifact and explain where it goes or what the reader no longer needs to do. | 1–3 short sentences | “The Linear issue, with the screenshot attached. The follow-up email, drafted. The deal note in HubSpot. The decision, logged with an owner.” |
| Trust heading | A plainspoken reassurance instead of a security slogan. | 4–8 words | “Your IT department won’t freak out”<br>“Take all of it with you.” |
| Primary action | Literal verb plus destination, platform or useful object. | 2–4 words | “Download for Mac”<br>“Get product description” |
| Caption | Name the people and say what is happening, with gentle humor when it is true. | One sentence | “Stian trying to convince Asgeir about an amazing feature. Asgeir needs more convincing.” |

**Words and phrasing to use:** done; drafted; filed; before; without; your team; the work; No need to; Not X. Y.

**Avoid:** revolutionary; unlock limitless potential; seamless synergy; supercharge everything; magical AI; exclamation-heavy slogans

**Rules:**

- Lead with the work completed, not a list of model capabilities.
- Use recognizable objects, destinations and owners to make benefits tangible.
- Acknowledge control and limits explicitly in answers.
- Let short negative constructions remove a familiar burden.
- Use a memorable linked statistic only when the underlying calculation is defensible.

## Do's and Don'ts

### Do

- Keep the default opening at 48px with 500-weight serif and a separate right-side action.
- Pair 32px serif feature headings with 15px/1.5 Inter explanations.
- Let 753×472px visual panels outweigh their narrow copy columns.
- Use 14px corners for primary actions and demonstration frames.
- Keep 96px section padding as the main breathing rhythm.
- Include refracted light and a translucent faceted object as recurring material cues.
- Use 1px #eeeeee rules for FAQ separation.
- Preserve 152px footer top padding and four open columns.

### Don't

- Do not turn the nearly white reading canvas into a continuous saturated gradient.
- Do not use the 72px explainer headline as the default on every new landing page.
- Do not replace warm-black actions with bright blue marketing buttons.
- Do not make the primary 14px-radius action a fully rounded pill.
- Do not add strong shadows to the flat #f6f6f6 trust panels.
- Do not place all feature explanations inside equal-sized generic cards; the default is an asymmetric split.
- Do not render spectral light as sharp opaque rainbow stripes.
- Do not add a giant footer wordmark or dark footer band; the ending remains open and light.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare transform and background-color transitions of 0.12s; text links use opacity 0.15s.
- Reassurance text declares a 10s ease-in-out repeating cycle.
- Integration-logo strips declare a 48s linear infinite marquee.
- Photo cards include front and reverse faces with perspective(1000px); only the settled front and the existence of reverse content establish the construction.

**Transfer:**

- Keep reassurance changes subordinate to the action, with a stable reserved line beneath it.
- Use a slow logo procession rather than a fast promotional ticker.
- If photographic cards reveal details, keep their front-face composition intact and provide a deliberate accessible reveal action.

**Unknown:**

- Reveal timing and easing for photographic cards, exact scroll choreography and interactive animation playback are not established.

### Responsive

**Observed:**

- Desktop layouts use capped 1280px and 1440px containers; CSS contains breakpoints around 480px, 640px, 768px, 1024px and 1280px.
- Some editorial and photo-card type uses explicit clamp formulas; the default 48px opening has no established fluid formula.

**Transfer:**

- On narrow screens, place the opening action beneath the copy while preserving the separate text strip above the pastel stage.
- Reduce and simplify the layered scene as one composition, keeping a main window and one legible foreground output.
- Stack asymmetric feature rows without losing the gradient backing; retain the photo strip as a horizontally navigable sequence.
- Bring side-rail directory labels above the grid and keep the faceted closing object paired with the invitation in a vertical composition.

**Unknown:**

- Mobile rendering, exact breakpoint-to-layout behavior and mobile navigation construction were not observed; these are adaptation recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
