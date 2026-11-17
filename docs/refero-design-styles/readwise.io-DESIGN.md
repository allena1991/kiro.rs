# Readwise — paper in sunlight

## Overview

A bookish, optimistic light style that makes capable software feel personal and approachable. Warm ivory, charcoal and highlighter yellow meet peach-orange light fields, literary serif headlines and clear humanist sans-serif explanations. Layered interface scenes feel like small physical objects on soft paper; the surrounding page is spacious while proof cards stay densely useful.

### Essentials

- Literary headlines with a conversational wink: Source Serif 4 at 64px/1.1, weight 600 and -0.02em tracking; a single italic word gives the opening its inflection.
- An opening that sells through a sunlit product tableau: a 1344px-wide rounded stage inside 48px page gutters, centered two-line headline, 431px-wide support and one dark action above an overlapping desktop-and-phone scene.
- Small black lozenges rather than oversized conversion bars: the default action is 42px tall, radius 40px, with 16px/22px semibold sans text and 10px 24px padding.
- Color behaves like light and annotation, not corporate paint: most reading sections remain ivory; peach-orange atmosphere fills bounded opening, proof and closing stages, while yellow at 40% or 60% opacity marks only a short phrase.
- Interfaces have tactile edges: white panels, soft warm shadows, rounded frames and floating fragments on low-contrast pastel backings. Include a layered product tableau; without finished media, construct a credible task card and a smaller companion panel rather than an abstract stock illustration.
- The ending returns to the opening's sunlight: a 535px rounded banner with a left-aligned 64px serif promise and dark pill, balanced by a diagonal receding field of product cards. The footer stays on ivory, with four modest link columns and compact distribution badges.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft yellow annotation | `#f9ed9e` | `--color-highlight` | accent, background | Visible yellow mark on ivory, built from yellow rgba(247,220,31,0.4). |
| Strong yellow annotation | `#f9e874` | `--color-highlight-strong` | accent, background | Visible supporting-line mark on ivory, built from yellow rgba(247,220,31,0.6). |
| Useful blue | `#2675de` | `--color-link` | link | Inline educational links and integration-directory actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Panel white | `#ffffff` | `--color-white` | surface, text | Interface and testimonial panels; reversed action labels. |
| Ivory paper | `#fbf9f3` | `--color-canvas` | background | Continuous page canvas and the color into which media fades. |
| Warm recess | `#f5f1e8` | `--color-recess` | surface, border | Inset integration tiles, card gradients, testimonial outlines and FAQ rules. |
| Pebble button | `#e8e6e1` | `--color-neutral-action` | surface, action | Neutral header action fill. |
| Paper edge | `#dbd7cd` | `--color-edge` | border | Floating document edges and pricing comparison dividers. |
| Warm gray text | `#7b7a79` | `--color-muted` | text, border | Supporting copy, metadata, footer links and the inset outline of secondary pricing actions. |
| Charcoal text | `#333333` | `--color-ink` | text, border | Headlines, navigation and emphasized body text. |
| Near-black action | `#161616` | `--color-action` | action, text | Primary action fills and text inside marked phrases. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Recommendation orange | `#ff8904` | `--color-orange` | text, border, accent | Value badge and recommended-plan edge. |
| pricing pages | Recommendation wash | `#fbeedb` | `--color-orange-wash` | surface | Visible 10% orange tint over ivory for the value badge, using rgba(255,137,4,0.1). |

## Typography

- **Source Serif 4** — Expressive headlines and document-like content in imagery. Literary, substantial serif with expressive italics; semibold rather than hairline. Font stack: "Source Serif 4", Georgia, serif.
- **Albert Sans** — Body copy, navigation, actions, feature titles and pricing numerals. Open, friendly sans-serif with simple shapes and readable lowercase. Font stack: "Albert Sans", sans-serif.
- **Inter** (only for embedded social proof cards) — Compact social-post body and attribution text. Neutral platform-like sans-serif that distinguishes quoted material from the editorial page. Font stack: "Inter", "Albert Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Source Serif 4 | 600 | 64px | 1.1 | -0.02em | Opening and closing promises. |
| display-emphasis | Source Serif 4 | 600 italic | 64px | 1.1 | -0.02em | One inline word in the opening promise. |
| heading-lg | Source Serif 4 | 600 | 54px | 1.37 | -0.02em | Centered section leads and the substantial text-and-product chapter. |
| lead | Albert Sans | 400 | 22px | 28px | normal | Centered opening support and large plain text links. |
| body | Albert Sans | 400 | 22px | 1.27 | normal | Muted explanatory paragraphs beside product scenes. |
| summary-title | Albert Sans | 600 | 22px | 1.27 | normal | Short centered benefit-strip titles. |
| summary-body | Albert Sans | 400 | 20px | 28px | normal | Benefit-strip support and secondary capability descriptions. |
| card-body | Albert Sans | 400 | 20px | 1.25 | normal | Feature card explanations. |
| rating | Albert Sans | 500 | 17px | 22px | -0.006em | Compact proof capsule. |
| action | Albert Sans | 600 | 16px | 22px | normal | Default primary actions and header tabs. |
| footer-heading | Albert Sans | 600 | 16px | 28px | normal | Footer column labels. |
| footer-link | Albert Sans | 500 | 16px | 22px | normal | Footer navigation and copyright. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-heading | Source Serif 4 | 600 | 54px | 1.37 | -0.02em | Page title, social-proof title and FAQ title. |
| pricing pages | price | Albert Sans | 600 | 40px | 1 | -0.025em | Featured plan price. |
| pricing pages | faq-question | Albert Sans | 600 | 16px | 1.5 | normal | Accordion summaries. |
| pricing pages | faq-answer | Albert Sans | 400 | 16px | 1.5 | normal | Expanded answers. |
| embedded social proof cards | social-body | Inter | 400 | 14.5px | 17px | normal | Quoted post body. |
| pricing pages | pricing-small | Albert Sans | 400 | 14px | 20px | normal | Plan support, recommendation badge and compact labels. |
| pricing pages | cycle-label | Albert Sans | 500 | 14px | 22px | normal | Billing-period choices. |

**Notes:**

- Serif tracking is consistently -0.02em at 40px, 54px and 64px; sans prose retains normal tracking.
- Use serif for promises and chapter leads, not every small title. Feature cards and process summaries use semibold sans.
- The 54px section heading uses a 1.37 line box, matching the explicit pricing heading rhythm.
- Opening support is darker than the muted explanation paragraphs farther down the page.
- Compact feature heading recipe: Source Serif 4, 40px, weight 600, normal line-height, -0.02em tracking. Feature-card title recipe: Albert Sans, 24px, weight 600, normal line-height, normal tracking.

## Layout

**Density:** Airy editorial sections around dense, tangible product and proof objects.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Benefit title to its support. |
| 10px | Feature-card title to body. |
| 12px | Proof-card columns and footer link stacks. |
| 16px | Feature heading to paragraph; small card and integration-tile gaps. |
| 24px | Opening headline to support and rating capsule to heading. |
| 32px | Opening copy to action; closing heading to action. |
| 40px | Feature-card text inset and featured-plan padding. |
| 48px | Outer desktop gutter; section heading to card grid. |
| 64px | Standard vertical section padding and alternating feature-row gaps. |
| 96px | FAQ vertical padding. |
| 100px | Proof-stage top padding. |
| 160px | Closing-banner vertical inset. |

### Containers and grids

- **outer frame**: max width 1728px · side padding 48px. Full marketing frame; at 1440px the bounded stage is 1344px wide.
- **reading sections**: max width 1200px · gap 64px. Centered feature chapters with a text half and a product-image half; the image is 536px by 405px and the text has a 500px readable measure.
- **feature grid**: max width 1200px · 3 columns · gap 16px. Three equal 389px feature cards, with varied media/text ordering.
- **integration cluster**: max width 670px · gap 16px. Centered wrapping rows of compact app tiles.
- **footer columns**: 4 columns · gap 24px. Four 200px link columns beside a 120px badge column, with brand block separated to the left.
- **offers** (only for pricing pages): max width 1040px · side padding 48px. Narrower decision-making container with 944px usable offer width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | stage | 32px |
|  | product scene | 24px |
|  | proof card | 16px |
|  | integration tile | 16px |
|  | primary action | 40px |
|  | annotation | 2px |
| pricing pages | recommended plan | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| proof paper | `rgba(42, 40, 34, 0.1) 0px 4px 4px 0px, rgba(42, 40, 34, 0.1) 0px 1.5px 1.5px 0px` | Small grounded shadows under social cards. |
| floating document | `rgba(0, 0, 0, 0.1) 0px 3px 5px 0px, rgba(0, 0, 0, 0.15) 0px 6px 24px 0px` | Lifted document fragments around the opening tableau. |
| tile recess | `rgba(0, 0, 0, 0.1) 0px 2px 10px 0px inset` | Integration tiles feel pressed into warm paper. |

### Surfaces

#### Paper canvas · level 0

**Use:** All reading areas and footer.

**CSS:** `background: #fbf9f3; color: #333333`

#### Sunlight stage · level 0

**Use:** Bounded atmospheric opening, proof and conversion banners.

**CSS:** `background: radial-gradient(ellipse at 58% 35%, rgba(255, 232, 175, 0.9), rgba(255, 232, 175, 0) 65%), radial-gradient(ellipse at 10% 70%, rgba(242, 143, 46, 0.85), rgba(242, 143, 46, 0) 65%), linear-gradient(120deg, rgba(245, 177, 124, 0.8), rgba(255, 219, 187, 0.8)); border-radius: 32px; overflow: hidden`

**Observed:** Soft peach and amber light pools with pale yellow luminous centers; not crisp gradient stripes. The opening fades into the canvas below the main device scene.

**Transfer:** Recreate the soft glow with layered gradients; exact stops are not essential. Keep strong color inside broad rounded stages.

#### Feature fade · level 0

**Use:** Three-up capability cards.

**CSS:** `background: linear-gradient(#f5f1e8 248px, #fbf9f3 518px); border-radius: 32px; overflow: hidden`

**Observed:** The upper surface is perceptible but its bottom dissolves into the page rather than ending with a strong border.

**Transfer:** Let light media and a short explanation share this fading backing.

#### Proof paper · level 1

**Use:** Social-post cards.

**CSS:** `background: #ffffff; border: 1px solid #f5f1e8; border-radius: 16px; box-shadow: rgba(42, 40, 34, 0.1) 0px 4px 4px 0px, rgba(42, 40, 34, 0.1) 0px 1.5px 1.5px 0px`

#### Recommended offer · level 1

**Only for:** pricing pages

**Use:** One visually preferred plan.

**CSS:** `background-image: linear-gradient(#f5f1e8 calc(100% - 308px), #fbf9f3), linear-gradient(#ff8904 calc(100% - 308px), #fbf9f3); background-clip: padding-box, border-box; border: 1px solid transparent; border-radius: 24px`

**Observed:** A warm interior and orange edge fade toward the bottom; it is not an orange-filled promotion.

**Transfer:** Reserve the warm edge for one recommendation.

## Components

### Product navigation

**Use:** Persistent light marketing header.

**CSS:** `display: flex; position: sticky; height: 76px; gap: 24px; padding: 4px 48px 0px; align-items: center; z-index: 10`

**Text style:** `action` — Albert Sans 600 · 16px/22px

**Observed:** Compact square brand symbol at left, followed by two product tabs; active tab has a 2px charcoal top rule. Neutral action is pushed to the right. The light header softly blurs artwork behind it.

**Transfer:** Keep the product-switcher character rather than adding a long menu.

### Primary button

**Use:** Single dominant conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #161616; color: #ffffff; border-radius: 40px; padding: 10px 24px; height: 42px; box-sizing: border-box`

**Text style:** `action` — Albert Sans 600 · 16px/22px

**Observed:** A compact text-only lozenge under centered opening copy. Closing action uses 18px text with 16px horizontal padding; featured pricing action expands across its column and is 44px tall.

**Transfer:** Use one clear verb-led label, not an icon-heavy action.

### Neutral button

**Use:** Secondary header action.

**CSS:** `background: #e8e6e1; color: #333333; border-radius: 40px; padding: 9px 20px; height: 40px; box-sizing: border-box`

**Text style:** `action` — Albert Sans 600 · 16px/22px

**Observed:** Soft pebble fill visually recedes behind the main dark action.

### Marker phrase

**Use:** Inline emphasis inside a section headline.

**CSS:** `background: rgba(247, 220, 31, 0.4); color: #161616; border-radius: 2px; padding: 0px 3px`

**Text style:** `heading-lg` — Source Serif 4 600 · 54px/1.37 · tracking -0.02em

**Observed:** A flat highlighter rectangle, not a capsule. Opening support instead uses 60% yellow and 3px vertical padding.

**Transfer:** Mark one useful noun phrase or outcome, not the whole heading.

### Integration tile

**Use:** Compact ecosystem proof.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 82px; height: 82px; background: #f5f1e8; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.1) 0px 2px 10px 0px inset`

**Observed:** Each tile centers a 48px app symbol; a centered wrapping cluster makes two rows.

**Transfer:** Use relevant partner symbols at comparable optical size.

### Social proof card

**Use:** Dense authentic endorsement in a wide staggered wall.

**CSS:** `display: flex; flex-direction: column; width: 363px; padding: 14.5px; gap: 15.5px; background: #ffffff; border: 1px solid #f5f1e8; border-radius: 16px; box-shadow: rgba(42, 40, 34, 0.1) 0px 4px 4px 0px, rgba(42, 40, 34, 0.1) 0px 1.5px 1.5px 0px; box-sizing: border-box`

**Text style:** `social-body` — Inter 400 · 14.5px/17px

**Observed:** Avatar and identity at top, platform mark at upper right, quote, optional attached image, muted date, then engagement metadata below a faint rule. Heights vary with content.

**Transfer:** Retain attributed, compact quotation formatting using genuine permissioned feedback.

### Rating capsule

**Use:** Small trust signal above a proof heading.

**CSS:** `display: flex; align-items: center; gap: 10px; background: rgba(255, 255, 255, 0.6); border-radius: 30px; padding: 8px 16px; height: 40px; box-sizing: border-box`

**Text style:** `rating` — Albert Sans 500 · 17px/22px · tracking -0.006em

**Observed:** Warm star symbols precede one short rating line; it floats on the atmospheric band.

### Footer link column

**Use:** Low-key navigation at the page ending.

**CSS:** `display: flex; flex-direction: column; gap: 12px; width: 200px; color: #7b7a79`

**Text style:** `footer-link` — Albert Sans 500 · 16px/22px

**Observed:** A darker semibold column heading sits above muted links. Brand block is left, four topical columns occupy the middle, distribution badges stack at right; copyright sits beneath the first link column.

### Billing switch

**Only for:** pricing pages

**Use:** Choose between two billing cadences.

**CSS:** `display: flex; width: 208px; height: 36px; padding: 3px; background: #f5f1e8; border-radius: 28px; box-sizing: border-box`

**Text style:** `cycle-label` — Albert Sans 500 · 14px/22px

**Observed:** Two equal choices; selected choice is white, radius 30px, with a small 0px 1px 4px shadow. Savings note is centered below.

**Transfer:** Keep it small and centered beneath the page title.

### Value badge

**Only for:** pricing pages

**Use:** Identify the recommended offer.

**CSS:** `background: rgba(255, 137, 4, 0.1); color: #ff8904; border: 1px solid #ff8904; border-radius: 28px; padding: 4px 8px`

**Text style:** `pricing-small` — Albert Sans 400 · 14px/20px

**Observed:** Small outlined label at the upper-right of the preferred plan; orange also appears in its checkmarks.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling before the footer.

**CSS:** `padding: 16px 0px; border-bottom: 1px solid #f5f1e8`

**Text style:** `faq-question` — Albert Sans 600 · 16px/1.5

**Observed:** Native disclosure structure. Summary uses 16px top and bottom padding and reserves 56px at right for a small downward chevron; answer is muted 16px/24px with blue links. Rows are visually collapsed by default.

**Transfer:** Use direct customer questions rather than promotional mini-headlines.

### Outline plan button

**Only for:** pricing pages

**Use:** Lower-emphasis actions for individual plans.

**CSS:** `display: flex; align-items: center; justify-content: center; color: #333333; border-radius: 64px; padding: 8px 16px; height: 40px; width: 216px; box-shadow: #7b7a79 0px 0px 0px 1px inset; box-sizing: border-box`

**Observed:** Transparent pill with 14px/22px semibold text, aligned at the right end of a comparison row.

## Imagery and graphics

### Sunlit product tableau

**Use:** Signature opening illustration and its closing echo.

**Observed:** A large desktop library panel and a smaller upright phone overlap against peach, amber and pale yellow light. Translucent white rims, warm shadows and floating document cards make the UI feel physical. The opening scene occupies most of the stage width below the copy; the closing scene becomes a low-contrast diagonal card field on the right.

**Transfer:** Stage the new product's central task in one broad panel plus a smaller companion view. If no production interface exists, draw a restrained, believable task panel with content and controls; keep the light framing and foreground/background separation.

**Build:** Use Sunlight stage as the base. Center a broad white panel with a 24px rounded inner edge, a translucent 8px outer rim and a soft warm shadow; overlap a narrow portrait panel on the right. Put small white document cards behind at alternating shallow angles and reduce their contrast with a peach overlay. Fade the bottom into ivory. For the closing echo, repeat a two-column card grid, rotate it about -35deg and compress its vertical perspective toward the upper right, then overlay a translucent warm wash.

### Focused task vignettes

**Use:** Alternating capability chapters and the larger advanced-use chapter.

**Observed:** 536px by 405px rounded scenes isolate a feed, review card or annotation workflow. Pastel blush, cream or cool gray backing is extremely pale. UI fragments float forward, sometimes with tags tilted across edges; bottoms fade into the page. The larger chapter uses a tall pale-pink-backed conversational panel beside a substantial text stack.

**Transfer:** Show one useful operation per scene, not a whole dashboard. Let a detached tag, control or message explain the action with minimal surrounding chrome.

**Build:** Place two or three white rounded panels inside a 24px rounded pastel field. Use soft edge shadows, one overlapping control or tag, and a vertical ivory gradient mask over the lower quarter. Keep the focal text readable while peripheral details recede.

### Capability card scenes

**Use:** Three-up feature grid.

**Observed:** One card pairs a physical book photo with a floating extracted-content card; another shows a white statistics panel with compact orange/yellow counters and a pale yellow bar chart; another combines a simple white character and a floating prompt box. The middle card reverses the text/media order. Media is prominent but low-contrast.

**Transfer:** Combine one real-world input, one outcome visualization and one interaction example for the new product. Statistics remain a small product demonstration, not giant marketing numerals.

### Sunlit proof wall

**Use:** Broad social-proof stage.

**Observed:** Five visible staggered columns of white social cards extend beyond the stage's side edges and are clipped. Warm orange-peach light is strongest behind the cards, with a centered serif lead and small rating capsule above.

**Transfer:** Make endorsement volume tangible through varied card heights and cropped side columns, while preserving a readable center.

**Build:** Use the Sunlight stage backing with a centered heading stack. Build fixed 363px card columns with 12px gutters, offset the column tops, center the overwide track, and clip it inside the 32px rounded stage. Allow the bottom background to wash into ivory rather than ending in a hard stripe.

### Icons

**Observed:** Marketing benefit icons are small glossy pastel rounded-square tiles with white line symbols. Integration tiles instead use full-color partner marks; proof cards retain compact platform marks. FAQ affordances are understated thin chevrons.

**Transfer:** Use simple white outline metaphors on softly beveled pink, amber and blue tiles for high-level benefits. Reserve recognizable brand marks for actual integrations; do not make every small icon glossy.

## Section recipes

How recurring sections are built.

### First screen: Sunlit opening

**Observed:** A 76px Product navigation sits above a rounded stage inside 48px gutters. The stage begins 8px below the header and continues for 1400px, with a peach-light backdrop, floating document fragments behind, centered copy above and device panels in front below. The 64px display headline wraps into two lines in about 511px, with one italic word. Support sits 24px below in a 431px measure, including a yellow Marker phrase; the Primary button follows after 32px. The large desktop panel enters around the lower half of the first 900px, and a smaller phone overlaps at right; their lower content and the three-benefit strip continue below the fold.

**Transfer:** Keep the headline and action readable before the tableau, but show a substantial part of the main product object within the first screen. Build the layered panel fallback described in Sunlit product tableau if polished media is unavailable. Pricing opens more plainly: centered 54px title, Billing switch, then a narrower Recommended offer rather than this immersive opening.

**Avoid:** Do not replace this with a left-copy/right-stock-photo split, an isolated headline on empty ivory, or a device scene that starts entirely below the first screen.

**Text style:** `display` — Source Serif 4 600 · 64px/1.1 · tracking -0.02em

### Three-benefit bridge

**Observed:** Three centered icon-and-copy groups span the 1200px section with 64px gaps. A glossy pastel icon sits above a semibold sans title; title and 20px support are separated by only 4px. The group overlaps the opening's fading lower edge.

**Transfer:** Reduce the product's value to three short verbs or outcomes; keep the strip visually lighter than the main feature chapters.

**Text style:** `summary-title` — Albert Sans 600 · 22px/1.27

### Alternating task chapter

**Observed:** Reading sections alternate text left/image right and image left/text right, with 64px row gaps. A 40px serif heading and muted 22px support sit 16px apart and are vertically centered against a 536px by 405px Focused task vignette.

**Transfer:** Pair one user benefit with one clearly demonstrated operation, alternating the visual weight rather than repeating identical boxes.

### Ecosystem cluster

**Observed:** Centered 54px serif heading with one short yellow-marked phrase, then a 670px wrapping cluster of Integration tiles and a plain blue directory link. Section padding is 64px and heading-to-cluster spacing is 48px.

**Transfer:** Use this compact cluster to show compatibility or source diversity without making a full-page logo wall.

**Text style:** `heading-lg` — Source Serif 4 600 · 54px/1.37 · tracking -0.02em

### Atmospheric proof

**Observed:** Sunlit proof wall combines 100px top padding, Rating capsule, centered 54px heading and an overwide staggered card track. Small post typography gives the stage an authentic dense center without turning the whole page dense.

**Transfer:** Use genuine proof with varied lengths; do not force every quotation into the same card height.

**Text style:** `heading-lg` — Source Serif 4 600 · 54px/1.37 · tracking -0.02em

### Fading capability triptych

**Observed:** A centered 54px heading sits 48px above three Feature fade cards. Each is 389px wide and 518px tall, with 40px text insets, 24px sans titles and 20px/25px support. Media and text order vary across the row.

**Transfer:** Use complementary examples, changing the position of media to avoid a rigid catalog appearance.

### Deep capability chapter

**Observed:** A tall rounded product conversation occupies one side of a 1200px row; the other side has a 54px serif headline with a marked phrase, a 22px support sentence and three smaller icon-led capability explanations.

**Transfer:** Use the taller scene for a more advanced workflow and let compact text entries unpack it without introducing heavy cards.

**Text style:** `heading-lg` — Source Serif 4 600 · 54px/1.37 · tracking -0.02em

### Sunlit closing and paper footer

**Observed:** A 1344px by 535px Sunlight stage carries a left-aligned two-line 64px promise with a compact dark action, 128px horizontal inset and 160px vertical padding. Low-contrast diagonal product cards occupy the right half. After 48px of separation, the ivory footer aligns brand, four link columns and stacked store badges; copyright sits below the links. The pricing ending instead proceeds from FAQ rows directly to this footer with 64px top padding and no duplicate conversion banner.

**Transfer:** Echo the opening materials in the final promise rather than introducing a new theme. Utility decision pages can end with resolved objections and the same lightweight footer.

**Text style:** `display` — Source Serif 4 600 · 64px/1.1 · tracking -0.02em

### Offer and comparison

**Only for:** pricing pages

**Observed:** Centered 54px title and Billing switch precede a 944px-wide Recommended offer, divided into two columns with a 48px gap and 40px padding. Identity, plan name, 40px price, support and a dark column-width action sit left; feature checks sit right, with Value badge above. Below, individual plans become horizontal rows with icon, explanation, small right-aligned price and Outline plan button.

**Transfer:** Emphasize one complete recommendation and let alternatives behave as legible comparison rows rather than equally loud cards.

**Text style:** `pricing-heading` — Source Serif 4 600 · 54px/1.37 · tracking -0.02em

### Questions before exit

**Only for:** pricing pages

**Observed:** A centered 54px title leads into 1104px-wide FAQ rows, separated from the heading by 64px. The whole section uses 96px vertical padding and returns directly to the paper footer.

**Transfer:** Answer concrete purchase and account concerns with restrained disclosures, ending in a human contact route.

**Text style:** `pricing-heading` — Source Serif 4 600 · 54px/1.37 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible product value → supporting capabilities and proof → decision or closing invitation → lightweight navigation.

### Product marketing and broad discovery

1. **Promise** — Centered literary headline and single action above a sunlit layered product scene.
2. **Value summary** — Three small icon-led benefit statements bridge into the main reading sections.
3. **Product demonstration** — Alternating compact task chapters connect an outcome with a focused interface scene.
4. **Compatibility and social proof** — Recessed app-tile cluster followed by a warm, staggered endorsement wall.
5. **Capability expansion** — Fading three-card grid and a taller advanced-workflow chapter.
6. **Closing call** — Sunlit banner repeats the visual promise, then gives way to the ivory column footer.

**Transfer:** Use the immersive opening and closing as emotional anchors, with understandable task scenes between; adapt the number and order of chapters to the product.

### Offer selection and purchase reassurance

1. **Pricing** — Plain centered title, compact billing choice, one recommended bundle and horizontal alternatives.
2. **Social proof** — Overlapping portrait cluster with a small reader-count line, then the same atmospheric endorsement wall.
3. **Objection handling** — Centered serif question heading above quiet disclosure rows.
4. **Navigation ending** — Paper footer with four link groups, distribution badges and copyright; no additional hero-style closing call.

**Transfer:** Keep comparison more compact than general marketing while retaining the same serif identity, pill actions and sunlit proof.

## Writing

Friendly, practical and quietly enthusiastic about a better everyday habit. Claims are explained through concrete actions and familiar frustrations rather than enterprise jargon.

**Do not copy:** Do not reuse the Readwise or Reader names, logos, recognizable product artwork, quoted customer posts, ratings, reader counts, prices or product-specific claims. Examples illustrate voice only; replace them with truthful content for the new product.

- **Addressing the reader:** Speak directly to you and your work. Name the product when explaining what it does; use we sparingly in conversational explanations and questions.
- **Rhythm:** Headlines are usually short verb-led benefits; support uses one or two plain sentences. A conversational question can introduce a frustration before a direct explanation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar aspiration phrased as getting more from something the user already does; one word can carry italic emphasis. | 7–12 words | “Get the most out of what you read” |
| Feature title | Verb plus the user's object or outcome. | 3–6 words | “Revisit your highlights”<br>“Organize your ideas” |
| Support | Name a real problem, then explain the operation that resolves it. | 1–2 sentences | “Reading something once isn't enough to remember it.”<br>“Snap a photo of any page. Your highlights and annotations save automatically.” |
| Action | Simple verb plus low-friction next step. | 3–5 words | “Get started for free” |
| Pricing reassurance | Short, natural question in the customer's own language. | 5–12 words | “Can I cancel [Brand]?”<br>“What happens to my data if I change plans?” |
| Closing promise | Return to the core activity with a modest burst of imaginative energy. | 4–7 words | “Start reading with superpowers” |

**Words and phrasing to use:** your; easy; save; remember; connect; instantly; everything in one place; get started

**Avoid:** revolutionary ecosystem; leverage synergies; unparalleled; enterprise-grade transformation; unlock limitless potential

**Rules:**

- Explain the task before naming the mechanism or technology.
- Keep technical nouns in advanced-workflow explanations rather than the opening promise.
- Make benefits concrete enough to demonstrate in the neighboring scene.
- Use one short highlighted phrase as a verbal focal point, not a series of disconnected slogans.

## Do's and Don'ts

### Do

- Keep the main reading canvas ivory and use white for tangible panels, not the entire page.
- Use 64px/1.1 semibold serif for major promises and 40px serif for compact feature chapters.
- Constrain opening support to 431px and keep it 24px below the headline.
- Keep default primary actions 42px tall with 40px radius and dark fill.
- Use 64px section spacing and a centered 1200px reading container.
- Let feature-card backgrounds fade from warm recess into ivory across their 518px height.
- Retain the 12px-gutter staggered proof wall and its clipped outer columns.
- Carry the opening light treatment into a 535px closing banner on broad marketing pages.

### Don't

- Do not turn the entire site into an orange background; reserve broad warm light for bounded stages.
- Do not use bold grotesk headlines in place of the literary serif hierarchy.
- Do not tighten body tracking just because the serif uses -0.02em.
- Do not enlarge every action to 56px or turn compact pills into rectangular slabs.
- Do not use highlighter yellow as the default button fill; it belongs behind short phrases.
- Do not apply strong borders and drop shadows to every section; the surrounding canvas remains flat.
- Do not convert the small in-product statistics scene into an unsupported oversized marketing-stat wall.
- Do not invert the footer into a dark block or enlarge its link type to compete with chapter headings.

## Motion and responsive

### Motion

**Observed:**

- No declared transitions or animations were identified on actions and surfaces; the header remains sticky while scrolling.

**Transfer:**

- The layered scenes must communicate their hierarchy in a static settled state; do not make the product explanation depend on movement.

**Unknown:**

- Timing, easing, reveal behavior and any interactive movement of the proof track are unspecified.

### Responsive

**Observed:**

- The desktop composition uses 48px outer gutters and a 1200px reading container. No narrow-screen layout rules are established.

**Transfer:**

- For narrower layouts, preserve headline → support → action → product-scene hierarchy. Stack alternating chapters and capability cards; retain the small companion panel overlap only while its content stays legible.
- Allow the integration cluster to wrap; keep atmospheric artwork bounded and clip decorative fragments rather than creating horizontal page overflow.

**Unknown:**

- Exact breakpoints, mobile type sizes, navigation collapse and narrow-screen card-track behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
