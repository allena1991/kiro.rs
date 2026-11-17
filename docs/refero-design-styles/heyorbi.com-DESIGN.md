# Orbi — spectrum and sidekick

## Overview

An almost-black software landing style with a luminous rainbow orbit, softly tiered charcoal interfaces and a friendly handmade streak. Tight, medium-weight sans-serif headlines alternate white and grey phrases, while small interface scenes make the product feel tangible rather than corporate. It suits lightweight tools and helpful automation products: sparse in content, atmospheric at the opening, and personable in its explanations.

### Essentials

- A rainbow perimeter frames a black reading island: an 8px page inset and 8px rounded opening surround a broad, tilted cyan–magenta–orange light band; the center stays almost black.
- Headlines speak in two tones, not two fonts: Instrument Sans 72px/1 at weight 500 with -2px tracking for the opening, then 48px/1.1 with the same tracking; alternate white phrases with 40% white.
- Conversion feels like a compact tool: a 480px-wide, 16px-radius email bar contains a 51px-high vermilion submit button with 12px corners; the navigation action is a smaller translucent version.
- Most of the page is charcoal, with color assigned specific jobs: #0a0a0a canvas, subtle white-alpha panels, #f63a22 actions and diagram highlights; the spectrum is concentrated around the opening rather than repeated across every section.
- Product proof is staged as a small floating artifact: a 440px-wide, 24px-radius charcoal interface card breaks past the light frame; later, overlapping tilted interface panels form a process collage. Use a simplified working-state illustration when a real interface is unavailable.
- Human marks temper the machine: a white handwritten benefit note with a loose arrow accompanies the hero artifact; small pill labels, 26px numbered red markers and a centered symbol-and-one-liner ending keep the rest intimate.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#f63a22` | `--color-accent` | action, accent, link | Submit controls, process number discs, isolated diagram highlights and a small footer link. |
| Orbit amber | `#f79200` | `--color-spectrum-amber` | background | Warm inner edge of the light band against the dark reading island. |
| Orbit cyan | `#20c8e3` | `--color-spectrum-cyan` | background | Cool outer part of the luminous opening band; match the soft light rather than a flat cyan area. |
| Orbit magenta | `#e42cb9` | `--color-spectrum-magenta` | background | Narrow middle band of the opening light spectrum. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#0a0a0a` | `--color-canvas` | background, surface | Main page canvas and inset form interior. |
| Low white wash | `#161616` | `--color-wash` | surface, border | Visible 5% white over the canvas; faint illustration panels, hairlines and the bottom of a section wash. |
| Charcoal artifact | `#232323` | `--color-panel` | surface | Main interface artifact backing; also the visible result of 10% white over the canvas for translucent actions. |
| White-alpha edge | `#232323` | `--color-edge` | border | Visible 10% white on the canvas; use the alpha recipe on raised panels so edges adapt to their backing. |
| Diagram charcoal | `#252525` | `--color-diagram` | surface | Small rounded cells and bars in conceptual graphics. |
| Receding headline grey | `#6c6c6c` | `--color-muted` | text | 40% white over the near-black canvas; subordinate phrases inside display headings. |
| Supporting grey | `#9d9d9d` | `--color-secondary` | text | 60% white over the near-black canvas; supporting paragraphs and footer copy. |
| White | `#ffffff` | `--color-foreground` | text | Primary headlines, short emphasized phrases and action labels. |

## Typography

- **Instrument Sans** — Display headlines, section headings and short feature titles. Open contemporary sans-serif with a friendly, slightly geometric build; medium display weights and tightly joined headline spacing. Font stack: "Instrument Sans", sans-serif.
- **Inter** — Supporting copy, actions, labels and interface captions. Neutral UI grotesk with clear small-size forms and restrained weight changes. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Instrument Sans | 500 | 72px | 1 | -2px | Centered two-line opening promise; first phrase white, second phrase muted. |
| heading | Instrument Sans | 500 | 48px | 1.1 | -2px | Centered section statements with inline white and muted-grey clauses. |
| artifact-title | Inter | 600 | 24px | 1.5 | normal | Main status title inside the opening interface artifact. |
| feature-title | Instrument Sans | 600 | 18px | 1.4 | normal | Short titles beside conceptual illustrations and labels beside process numbers. |
| body | Inter | 400 | 18px | 1.5 | normal | Centered support paragraphs, with occasional white emphasis inside grey text. |
| action | Inter | 400 | 16px | 1.5 | normal | Navigation action, simple links and compact footer copy; use for new conversion labels. |
| step-number | Inter | 600 | 16px | 1.5 | normal | White numerals within small vermilion process discs. |
| small-body | Inter | 400 | 14px | 1.5 | normal | Explanations beside conceptual graphics. |
| caption | Inter | 400 | 12px | 1.5 | normal | One-line reassurance or incentive beneath an email form. |
| eyebrow | Inter | 500 | 12px | 1.5 | normal | Sentence-case pill label introducing a section. |

**Notes:**

- Both headline sizes retain -2px tracking; the smaller section statement consequently feels more tightly knit. Keep body and label tracking normal.
- White and grey are compositional parts of a headline, not a gradient text effect. Supporting text uses 60% white while display clauses use 40%.
- The handwritten annotation is artwork, not a second body-text family: keep it short and visibly hand-drawn.

## Layout

**Density:** Airy outside and compact inside: broad section breathing room surrounds a narrow column of explanations and tightly packed product artifacts.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Outer page inset and close title-to-copy spacing. |
| 12px | Pill horizontal padding and process number-to-label gap. |
| 16px | Illustration panel padding, artifact content gaps and form-to-caption separation. |
| 24px | Opening headline-to-support gap and gaps between explanatory rows. |
| 32px | Form offset below support text, artifact inner padding and illustration-to-copy gap. |
| 48px | Opening artifact offset after the sign-up block and explanatory list offset after its introduction. |
| 112px | Top and bottom padding of major narrative sections. |
| 160px | Opening top padding, leaving the small fixed navigation separate from the headline. |

### Containers and grids

- **page-shell**: max width 1800px · side padding 8px. Centered broad shell; rounded atmosphere sits inside a thin black perimeter.
- **main-container**: max width 1280px · side padding 71.2px. Desktop section content alignment inside the broad shell.
- **headline-column**: max width 768px. Centered opening headline and section introductions; support narrows to 560px and selected section headings to 416px.
- **explanation-list**: max width 608px · 2 columns · gap 32px. Each explanation row pairs a 288px illustration with a 288px text block; rows stack with 24px between them.
- **process-stage**: max width 832px · 3 columns. Three overlapping interface artifacts arranged as one centered composition rather than separate bordered marketing cards.
- **conversion-column**: max width 480px. Repeated centered email conversion bar; the opening artifact below it narrows to 440px.

## Corner radius

| Element | Radius |
| --- | --- |
| section-frame | 8px |
| action | 12px |
| form-and-illustration | 16px |
| hero-artifact | 24px |
| section-label-and-number | 48px |
| diagram-cell | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| form-rim | `rgba(255, 255, 255, 0.05) 0px 0px 0px 1px, rgba(255, 255, 255, 0.05) 0px 1px 2px 0px` | A low-contrast luminous rim rather than a dark drop shadow around the email bar. |
| label-rim | `rgba(255, 255, 255, 0.06) 0px 0px 0px 1px, rgba(255, 255, 255, 0.06) 0px 1px 2px 0px` | Delicate outline and shallow lift on small section labels. |

### Surfaces

#### Dark canvas · level 0

**Use:** Continuous marketing-page ground.

**CSS:** `background: #0a0a0a; color: #ffffff`

#### Faint narrative band · level 0

**Use:** Gentle separation for a longer explanatory chapter.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(255, 255, 255, 0.05)); border-radius: 8px`

**Observed:** A nearly imperceptible rise in brightness toward the bottom; it stays dark behind both text and diagrams.

**Transfer:** Use this for a sustained narrative chapter without switching to a light theme.

#### Charcoal artifact · level 1

**Use:** Backing for the principal product illustration.

**CSS:** `background: #232323; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 24px`

**Observed:** Flat charcoal with a faint light edge; depth comes from overlap and fading content, not glossy 3D bevels.

**Transfer:** Keep the outer marketing artifact consistent even when its internal UI belongs to a different product.

#### Concept panel · level 1

**Use:** Small abstract diagrams accompanying feature or problem text.

**CSS:** `background: rgba(255, 255, 255, 0.05); border: 1px solid rgba(255, 255, 255, 0.05); border-radius: 16px; padding: 16px`

**Observed:** Low-contrast backing keeps the vermilion active mark more visible than the surrounding cells.

**Transfer:** Use as a restrained stage for simple geometric visual metaphors.

## Components

### Fixed navigation

**Use:** Persistent orientation and one conversion action.

**CSS:** `position: fixed; top: 8px; height: 72px; width: 100%; z-index: 1000; padding: 0px 24px; display: flex; align-items: center; justify-content: space-between`

**Observed:** Small white symbol at left, Glass action at right; no central menu or opaque full-width bar.

**Transfer:** Use the new product's compact symbol with one action; retain the sparse two-ended arrangement.

### Glass action

**Use:** Navigation conversion link.

**CSS:** `background: rgba(255, 255, 255, 0.1); border: 1.5px solid rgba(255, 255, 255, 0.1); border-radius: 12px; backdrop-filter: blur(5px); padding: 8px 20px; color: #ffffff`

**Text style:** `action` — Inter 400 · 16px/1.5

**Observed:** Translucency lets the opening spectrum show through; over the page body it reads charcoal.

### Primary button

**Use:** Email-form submission and main conversion.

**CSS:** `background: #f63a22; border: 1.5px solid rgba(0, 0, 0, 0.6); border-radius: 12px; height: 51px; padding: 12px 20px; color: #ffffff`

**Text style:** `action` — Inter 400 · 16px/1.5

**Observed:** A compact solid rectangle sits inside the right end of Email bar; the darker rim makes its saturated fill feel inset rather than floating.

### Email bar

**Use:** Single-field conversion repeated near the promise and near the close.

**CSS:** `background: #0a0a0a; border-radius: 16px; padding: 4px; display: flex; gap: 16px; max-width: 480px; box-shadow: rgba(255, 255, 255, 0.05) 0px 0px 0px 1px, rgba(255, 255, 255, 0.05) 0px 1px 2px 0px`

**Observed:** One email input then Primary button; a centered caption follows underneath. No labels or extra fields interrupt the compact visual bar.

**Transfer:** Provide an accessible email label without expanding the visual form into a multi-field panel.

### Email input

**Use:** Editable portion of Email bar.

**CSS:** `border: 1px solid #0a0a0a; height: 51px; padding: 8px 12px; min-width: 0px; flex: 1`

**Observed:** Field merges into the dark form shell and uses a short placeholder, leaving the red submit control dominant.

### Section pill

**Use:** Small label above a centered narrative heading.

**CSS:** `border-radius: 48px; padding: 4px 12px; box-shadow: rgba(255, 255, 255, 0.06) 0px 0px 0px 1px, rgba(255, 255, 255, 0.06) 0px 1px 2px 0px; color: #ffffff`

**Text style:** `eyebrow` — Inter 500 · 12px/1.5

**Observed:** Sentence case rather than tracked uppercase; a fine rim and no saturated background.

### Product artifact

**Use:** Primary concrete proof under the opening conversion block.

**CSS:** `background: #232323; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 24px; max-width: 440px; padding: 32px 32px 0px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `artifact-title` — Inter 600 · 24px/1.5

**Observed:** Status icon and title precede a count and compact repeated UI rows. The lower rows fade into the backing; the artifact extends below its atmospheric frame.

**Transfer:** Show one believable task being completed. If no application exists yet, draw a concise task-state illustration with real content rather than an entire dashboard.

### Process number

**Use:** Ordered labels around a linked product collage.

**CSS:** `background: #f63a22; border-radius: 48px; width: 26px; height: 26px; color: #ffffff; text-align: center`

**Text style:** `step-number` — Inter 600 · 16px/1.5

**Observed:** A white numeral sits alongside a short feature title; outer labels sit above their artifacts and the middle label below.

### Accent text link

**Use:** Small footer credit or equivalent secondary link.

**CSS:** `color: #f63a22`

**Text style:** `action` — Inter 400 · 16px/1.5

**Observed:** Inline with muted footer text, without a button backing or decorative icon.

## Imagery and graphics

### Spectral orbit

**Use:** Signature atmospheric frame for the opening.

**Observed:** A large tilted black oval leaves a blurred rainbow band around opposing corners: cyan on the outer edge, magenta through the middle and amber nearest the dark center. The band sweeps from lower left toward upper right and returns along the lower-right perimeter; text occupies the clear black center. No photography or rendered device casing competes with it.

**Transfer:** Preserve the luminous perimeter and black center for a different product; the main object may change, but the light-frame device remains.

**Build:** Create an overflow-hidden 8px-radius stage. Place an oversized elliptical ring centered in it, wider than the stage and rotated about -25deg. Build the ring with nested elliptical layers colored cyan, magenta and amber from outside inward; blur the color layers by about 20–40px and cover their center with a #0a0a0a ellipse. Size and offset the ring so its center is a broad uninterrupted reading island while the colored band exits the frame on opposing sides. Match the soft glow; exact stops are not essential.

### Hand-drawn aside

**Use:** Signature human annotation beside the opening artifact and connecting the process collage.

**Observed:** A short white handwritten benefit note sits to the right of the hero interface with a loose curved arrow pointing down-left. The process scene uses much darker scribbled arrows between panels, so the labels remain primary.

**Transfer:** Write one specific outcome in the new product's voice; retain a hand-drawn note and arrow even if the main object is a simplified illustration.

**Build:** Draw the note as SVG paths or genuine pen lettering on transparent ground, with a thin irregular white stroke and no backing. Add a separate single-stroke curved arrow with an open V head, placed to lead the eye back into the object. Use low-opacity white for connecting arrows in the process scene.

### Concept diagrams

**Use:** Abstract visual metaphors inside Concept panel.

**Observed:** One graphic is a tight matrix of rounded dark cells with one vermilion cell; another is a sparse dark bar chart with a few bright red peaks; the last uses closely spaced vertical bars warming from charcoal toward red. These illustrations are approximately equal in width to their adjacent copy blocks.

**Transfer:** Choose analogous simple signals for the new product: isolated selection, uneven activity, or a changing distribution. Keep the geometry restrained and the active red marks scarce.

**Build:** Use CSS grid or SVG rounded rectangles with 6px corners in a 254px by 159px drawing area. For a matrix, repeat #252525 cells and replace one with #f63a22. For the chart, bottom-align narrow rounded bars with 6px gaps and vary their heights. For a density graphic, repeat narrow bars and interpolate only selected bars from charcoal toward vermilion.

### Tilted process collage

**Use:** A product explanation that feels like a set of working artifacts.

**Observed:** Three dark interface panels overlap across an 832px composition. Outer panels tilt slightly counterclockwise; the first uses -4deg. The middle tips in the opposite direction and recedes behind the right panel. Each has a red numbered label; small hand arrows link the steps. Interface rows fade downward, and tiny status colors remain confined to the UI.

**Transfer:** Use distinct input, transformation and result views for another tool; if real views are unavailable, assemble three simplified content-bearing panels with one active item each, not empty rectangles.

### Icons

**Observed:** The page uses a compact white organic symbol at both ends, a red radial loader in the hero artifact and small circular service marks within product UI. Navigation and footer symbols are 42px by 32px; the hero loader occupies 38px by 38px.

**Transfer:** Use an original compact monochrome product symbol for navigation and the close. Keep colorful third-party marks inside the product illustration rather than scattering icon badges through marketing copy.

## Section recipes

How recurring sections are built.

### First screen: Orbit-framed promise

**Observed:** An 8px-inset rounded atmospheric stage underlies a sparse Fixed navigation. From back to front: Spectral orbit, black central reading island, centered headline and support, Email bar with caption, then Product artifact with Hand-drawn aside. The headline begins after 160px top padding and spans a 768px column, with a white first line and 40%-white second line at 72px/1. Support is 560px wide with a 24px separation; Email bar follows 32px later. The 440px-wide artifact begins 48px below the sign-up block and occupies the lower central third of the first screen. Within 900px, the headline, support, conversion, note and most of the artifact are visible; the artifact's last rows and its lower edge fall below the fold. The atmospheric frame itself ends before the artifact does.

**Transfer:** Center a short two-part promise in a black reading island and retain the light frame and handmade aside. Substitute a compact illustrated product result when no UI exists. Other marketing page types can use a more specific task or outcome as their promise while preserving this same centered opening hierarchy.

**Avoid:** Do not turn this into a left-copy/right-dashboard split or place readable text directly over the bright spectrum.

**Text style:** `display` — Instrument Sans 500 · 72px/1 · tracking -2px

### Breathing-room bridge

**Observed:** A centered 768px-wide one-line bridge sits in a dark band, with 80px above its text. Grey wording gives way to a short white conclusion; faint edge fades blend the surrounding strip into the page.

**Transfer:** Use a brief transition from the opening outcome to the next explanatory idea; avoid introducing a new visual theme.

**Text style:** `body` — Inter 400 · 18px/1.5

### Two-tone chapter introduction

**Observed:** Section pill sits above a centered 48px statement that mixes white and grey clauses. The pill-to-heading separation is 16px; supporting 18px copy follows about 24px later. Major chapters use 112px top and bottom padding.

**Transfer:** Give each sustained chapter a small functional label and a concise two-tone statement. White identifies the central point, grey connects the sentence.

**Text style:** `heading` — Instrument Sans 500 · 48px/1.1 · tracking -2px

### Diagram and explanation rows

**Observed:** Inside Faint narrative band, a narrow 608px list stacks paired rows with 24px between them. Each row has a 288px by 193px Concept panel at left, a 32px gutter and short text at right, vertically centered. Feature titles use 18px semibold Instrument Sans; explanations use 14px Inter with about 8px below the title.

**Transfer:** Explain distinct frictions or capabilities with one restrained diagram each; keep copy shorter than the illustration height.

**Text style:** `feature-title` — Instrument Sans 600 · 18px/1.4

### Artifact process and conversion

**Observed:** A two-tone introduction leads into Tilted process collage. Process number labels follow the panels' angles and alternate above and below them. The Email bar and caption repeat beneath the collage, with enough darkness around them to restore a calm reading axis.

**Transfer:** Explain how an input becomes an outcome through overlapping artifacts, then offer the same conversion as the opening instead of introducing a competing action.

**Text style:** `heading` — Instrument Sans 500 · 48px/1.1 · tracking -2px

### Symbol-and-one-liner ending

**Observed:** The last 200px forms a sparse centered footer rather than a column grid. A white 42px by 32px symbol sits above two compact lines: a muted benefit reminder and a muted credit with Accent text link. It is separated from the final form by generous black space, with about 48px top and bottom footer padding.

**Transfer:** Close with the product's own compact symbol, a warm one-sentence reminder and a small secondary link where appropriate; keep the ending intimate.

**Text style:** `action` — Inter 400 · 16px/1.5

## Page flow

**Storyline:** Outcome promise → tangible product proof → brief transition → reader friction → simple mechanism → repeated conversion → personable sign-off.

### Introduce a lightweight helper and convert interest into early-access sign-ups

1. **Promise** — Orbit-framed centered outcome statement and immediate single-field conversion.
2. **Product demonstration** — A small working-state artifact overlaps the opening frame, accompanied by a handwritten outcome note.
3. **Transition** — One centered line connects scattered inputs to a unified result.
4. **Problem recognition** — A two-tone heading and three diagram-and-copy rows articulate the reader's frustrations.
5. **Mechanism** — A numbered tilted collage shows input, transformation and output.
6. **Closing call** — The same email conversion bar repeats with a small incentive caption.
7. **Sign-off** — Centered symbol, benefit reminder and small inline credit finish the page.

**Transfer:** Borrow the narrative balance of outcome, empathy and a visible mechanism; adapt the number and order of chapters to the new product rather than reproducing every topic.

## Writing

Friendly, direct and helpfully matter-of-fact. The product behaves like a useful sidekick, naming irritating chores and promising more room for the reader's real work.

**Do not copy:** Do not reuse Orbi's name, logo, hand-lettered artwork, source-specific service marks, agency credit, freelance statistics, lead counts, scores or limited-sign-up discount claims. Replace these with truthful product-specific content and original artwork. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you. Describe the product by name as an agent or helper that performs concrete tasks, rather than speaking in a grand corporate we.
- **Rhythm:** Short conversational headings, mostly one-sentence explanations, contractions and a few purposeful dashes. Support copy often moves from the chore to the relief in two clauses.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the useful recurring result, without a slogan or technical preamble. | 6–10 words | “Your daily list of fresh freelance leads” |
| Problem statement | A familiar truth followed by a plainspoken reversal. | 6–12 words | “Being great at what you do isn’t enough” |
| Feature title | Name a friction or describe a concrete action. | 3–7 words | “It kills your creative momentum”<br>“Rates each lead for quality” |
| Supporting line | Say what the product does and what the reader gets back. | 15–30 words | “[Brand] scans the internet for new freelance opportunities and drops the best ones into a clean, searchable feed.” |
| Primary action | Short invitation tied to the current product stage. | 3–4 words | “Join the beta” |
| Sign-off | Restate the relief with a conversational contrast. | 10–16 words | “[Brand] does the boring stuff, so you don’t have to.” |

**Words and phrasing to use:** you; your; so you can; clean; best ones; sidekick; boring stuff; doing great work

**Avoid:** revolutionary; unlock your potential; enterprise-grade ecosystem; synergize; disrupt; AI-powered everything

**Rules:**

- Lead with a recurring useful result, then name the mechanism.
- State pains as recognizable everyday situations rather than abstract market categories.
- Use white inline emphasis for a short meaningful phrase, not an entire support paragraph.
- Make numeric proof and incentive captions specific and verifiable.

## Do's and Don'ts

### Do

- Keep the outer dark inset at 8px and atmospheric frame corners at 8px.
- Use 72px/1 opening type and 48px/1.1 section type, both weight 500 with -2px tracking.
- Constrain supporting copy to 560px while allowing the opening headline 768px.
- Repeat the same 480px email bar near the promise and conversion close.
- Keep diagram panels at 16px corners with 16px inner padding and faint white-alpha edges.
- Use 32px between diagram and text, but only about 8px between feature title and explanation.
- Carry one original handwritten note and loose arrow into the product staging.
- Finish with a compact centered symbol and short muted copy, not an expanded sitemap.

### Don't

- Do not apply the 48px pill radius to primary controls; their measured shape is a 12px rounded rectangle.
- Do not use the spectrum as headline text fill; headings rely on white-versus-grey phrases.
- Do not flood every chapter with colored backgrounds; keep most surfaces close to #0a0a0a.
- Do not make supporting paragraphs white at full opacity; reserve that contrast for short emphasis.
- Do not add heavy black drop shadows to the form or pill; use the thin 5–6% white rims.
- Do not replace conceptual diagrams with generic colorful feature icons; preserve dark geometry with isolated red signals.
- Do not enlarge process labels to compete with section headings; they stay at 18px.
- Do not turn the sparse fixed navigation into a dense menu or a solid opaque header band.

## Motion and responsive

### Motion

**Observed:**

- A radial loader has a declared 2.2s linear infinite spin.
- Diagram elements declare height 1s and background-color 0.4s transitions.

**Transfer:**

- Keep loading motion confined to the small working-state artifact and use height/color changes for the conceptual bars rather than moving whole sections.

**Unknown:**

- Hover, focus-visible and active appearance are not established.
- Scroll-animation timing and easing are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 991px, 767px and 479px.

**Transfer:**

- On narrow screens, preserve the black reading island, two-tone headline and rainbow perimeter before scaling the artifact.
- Stack diagram-and-copy pairs and the process artifacts when their content stops fitting; retain numbered labels and the handmade connective marks.
- Allow the email bar to narrow with its parent while keeping the submit label intact.

**Unknown:**

- Mobile type sizes, gutters, exact stacking behavior and navigation changes are not established; these are adaptation rules rather than alternate measured layouts.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
