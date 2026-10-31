# MAIM 09 — Webinar Knowledge Vault · Handover Document

> **Purpose of this doc:** a complete written inspection of the design artifact, so it can be reviewed without opening the (17 MB) standalone HTML file. Covers the brief, the system, every board section, the asset inventory, and technical/build notes.

---

## 1. What this is

A single **scrolling "volume board"** — the established MAIM design-document format (same layout language as *MAIM 00 Brand System* and *MAIM 05 Lead Magnets + Ebooks*). It is **not** a slide deck and not a web app. It is a long, dark, premium reference board that an operator scrolls top-to-bottom.

- **Source file:** `MAIM 09 Webinar Knowledge Vault.dc.html` (a Design Component — editable, streams live).
- **Standalone export:** `MAIM 09 Webinar Knowledge Vault — Standalone.html` (~17 MB, fully offline, all images + fonts inlined).
- **Volume position:** Subsystem of *MAIM 09 Media Vault + Merch Artifacts*. Draws on MAIM 00 (Brand), MAIM 03 (Learning Engine), MAIM 08 (Hanzo Powered-By).

### Core thesis
**The webinar is not an event. The webinar is the master asset.**

### Core formula (rendered as a horizontal strip on the board)
`Webinar → Transcript → Clips → Articles → Prompts → Lessons → Vault → Revenue`

### Closing line
**One live room. Infinite assets. Likkle by likkle, we build the future.**

---

## 2. Brand system applied (from MAIM 00)

| Token | Value | Job |
|---|---|---|
| Black Foundation | `#050505` | Primary background / authority |
| White Clarity | `#F7F4EA` | Body text / clean space (warm off-white) |
| Gold Authority | `#D8AF55` | Lead accent — labels, headlines accents, seals |
| Jamaican Green | `#1F7A3A` (text `#3FA45C`) | Legacy / archive / "grow" |
| Champion Blue | `#006BB6` (text `#3a9be0`) | Action energy / "attract & fill" |
| Knicks Orange | `#F58426` | CTA accent — used sparingly for the single most important action |
| Card surface | `#0c0c0e` | Card backgrounds, 1px `rgba(247,244,234,.1)` borders |

- **Type:** Archivo (display 800–900, body 400–600) + JetBrains Mono (labels/system, tracked + uppercase). No other fonts.
- **Signature device — the tri-bar:** `linear-gradient(90deg,#1F7A3A 0 33%,#D8AF55 33% 66%,#006BB6 66% 100%)` — green→gold→blue underline beneath headlines and CTAs.
- **Mark/seal:** the woven crown coin (`crown-coin.png`) and the "MD" monogram mark (`maim-mark.png`). Never re-typeset; supplied artwork only.
- **Section header pattern (consistent across the board):** mono `NN` number + tracked uppercase mono section title → Archivo-900 52px headline → optional 17px intro paragraph.
- **Layout frame:** `max-width:1240px`, 56px side padding, dark body, generous vertical rhythm. Footer with mark + tagline + "Powered by Hanzo · major@hanzo.ai".

### Color coding used throughout (a deliberate, repeated language)
- **Blue** = attract & fill the room
- **Gold** = capture & refine
- **Green** = archive & grow
- **Orange** = pull back to live / single CTA

---

## 3. Board structure — section by section

The board reads: **Cover → Formula strip → 01–10 → Closing → Footer.** Each `<section>` carries a `data-screen-label` for review/navigation.

### Cover
- Eyebrow `MAJOR AI MINDSET`; top-right meta `MEDIA VAULT SUBSYSTEM / VOLUME 09 · WEBINAR KNOWLEDGE VAULT · JUNE 2026`.
- Left: framed crown-coin seal in a radial-gradient tile. *(Note: the user directly swapped this image to `start-here-highlight-mqyobdq6.png` in the visual editor — an intentional edit, preserved.)*
- Right: kicker `THE MASTER ASSET ENGINE`, headline **WEBINAR / KNOWLEDGE VAULT**, tri-bar, thesis line "The webinar is not an event. **The webinar is the master asset.**"
- Three mono chips: "One Live Room. Infinite Assets." · "Capture once. Multiply forever." · "Powered by Hanzo".

### Formula strip
Centered horizontal flow of the core formula, color-accented at the endpoints (Webinar=blue, Vault=gold, Revenue=orange).

### 01 — The Master Asset Doctrine
- Headline: *"Stop making content. Start mining the room."*
- Four principle cards (each border-colored): **One Live Room** (blue), **Capture Everything** (gold), **Multiply Relentlessly** (green), **Archive Forever** (orange).
- Strategic-insight panel: promotion drives one action — fill the live room; after the live, Hanzo / Google Meet / ChatGPT / Claude turn the recording + transcript into content, curriculum, prompts, and Vault assets.
- Green doctrine block: **"Don't scale your effort. Scale your hour."**

### 02 — The Weekly Webinar Flywheel
- Headline: *"The room spins the wheel."*
- **Radial flywheel visual:** a 560×560 ring with the **Vault Engine / The Live Room** crown-coin hub at center, and 8 nodes positioned around the circle: Promotion → Live Attendance → Recording → AI Extraction → Distribution → Vault Archive → Community Pull → Next Promotion.
- Legend chips below explain the 4-color language (blue/gold/green/orange).

### 03 — Recording + Transcript Intake
- Headline: *"The moment the live ends, intake begins."*
- Three step cards: **Capture** (Google Meet, YouTube/Zoom backup, audio isolate) · **Transcribe** (Hanzo pipeline, speaker labels + timestamps, clean master doc) · **Tag** (week #, date, topic, A–Z letter, themes, auto-created Vault folder).
- **Intake SLA bar:** `recording_uploaded → transcript_ready → tagged_&_filed` — **within 24 hours of going live**.

### 04 — The Knowledge Extraction Layer
- Headline: *"AI reads the room so we don't have to."*
- Left: cinematic `keyart-datacenter.png` panel "Transcript in. Strategic brief out."
- Right: 6-cell grid of what AI pulls — **Key Insights, Frameworks, Quotables, Q&A + Objections, Teaching Moments, Strategic Cuts** (the last accented orange; timestamped clip-worthy segments).

### 05 — Clip + Social Repurposing Engine
- Headline: *"One hour. A week of feed."*
- Four 9:16 template previews on-brand by default (tri-bar / mark / palette): **Reels & Shorts**, **Quotable card**, **Carousel recap**, **CTA (pull to live)** using the founder image.
- Destinations bar: IG Reels · YouTube Shorts · TikTok · LinkedIn · Feed carousels — every cut tagged back to its Vault source.

### 06 — Newsletter + Article Engine
- Headline: *"The transcript becomes the written word."*
- Three cards: **Recap Newsletter** (gold), **SEO Article** (blue, 800–1,200 words, evergreen/internally linked), **Social Long-Post** (green, LinkedIn/X breakdown). Each lists its build recipe.

### 07 — Curriculum + Prompt Pack Engine
- Headline: *"Every live makes the school smarter."*
- Left: three icon rows — **Lesson Update** (maps to A–Z letter), **Weekly Prompt Pack** (the exact prompts demoed live), **Workbook Revision** (7-Day Asset Lab).
- Right (blue panel): feeds the **Learning Engine (Vol 03)** — "the curriculum is never written ahead of time, it is harvested from the lives." Tag chips: A–Z lessons, prompt library, workbook, cohort modules.

### 08 — The Vault Archive Structure
- Headline: *"A drawer for every week. Forever."*
- Left: monospace **vault tree** — `vault/ → wk-031_b-belief/ → recording.mp4, transcript.md, extraction-brief.md, clips/, written/, prompts/, signals/`.
- Right: **naming convention** `wk-[n]_[letter]-[topic]_[asset]_v[n]` with examples; inherits the Vol 00 file-naming system. Rule: the Vault is the single source of truth — nothing ships that isn't filed.

### 09 — Merch + Artifact Signal Layer
- Headline: *"The room tells us what to make."*
- Explicit guardrail line: `NO CHECKOUT · NO TOKEN GATING · SIGNALS ONLY`.
- Three signal cards: **Phrase → Apparel** (recurring quotable → tee/hoodie/sticker, culture lane) · **Moment → Artifact** (milestone lives → limited crown-coin artifact) · **Demand → Hanzo** (production routes through Hanzo Powered-By assets, Vol 08). The Vault hands off the signal, not the storefront.

### 10 — The Weekly Command Center
- Headline: *"The week, on rails."*
- **7-day cadence calendar:** SUN **GO LIVE** (blue, record+transcribe) · MON **EXTRACT** · TUE **CLIPS** · WED **WRITE** · THU **TEACH** · FRI **FILE** (green) · SAT **PROMOTE** (orange, fill tomorrow's room).
- Metrics footer: **1** live/week · **12+** assets/live · **52** vaults/year · "THE WHEEL NEVER STOPS TURNING".

### Closing
- Centered crown-coin, headline **ONE LIVE ROOM. / INFINITE ASSETS.**, tri-bar, "Likkle by likkle, **we build the future.**"

### Footer
- Mark + `MAJOR AI MINDSET · WEBINAR KNOWLEDGE VAULT · VOL 09`; right side "THE WEBINAR IS THE **MASTER ASSET.** / Powered by Hanzo · major@hanzo.ai".

---

## 4. Asset inventory

All in `assets/` unless noted. Copied from the MAIM 00 Brand System project.

| File | Used where |
|---|---|
| `crown-coin.png` | Cover seal, flywheel hub, closing seal |
| `maim-mark.png` | Section 09 card, footer |
| `maim-mark-subtle.png` | (available; watermark use) |
| `keyart-datacenter.png` | Section 04 cinematic panel |
| `founder-point.jpeg` | Section 05 CTA clip |
| `founder-portrait.jpg` | (available) |
| `icon-abcs.png`, `icon-ai-tools.png`, `icon-build.png` | Section 07 rows |
| `icon-webinar.png`, `icon-community.png`, `icon-start-here.png` | (available) |
| `start-here-highlight-mqyobdq6.png` *(project root)* | Cover seal — **user's direct swap, intentional** |

---

## 5. Technical & build notes

- **Format:** Design Component (`.dc.html`). Template-only — no logic class. All styling is **inline** (no stylesheets/classes), per the DC system, so it paints while streaming.
- **Fonts:** Archivo + JetBrains Mono via Google Fonts `<link>` in `<helmet>`.
- **No payment rails / token gating / ecommerce / Shopify** — explicitly excluded per brief; section 09 is signal-only.
- **Flywheel** is built with CSS absolute positioning of 8 nodes around a dashed ring + a radial-gradient center hub (no SVG illustration).
- **Standalone export** produced with the inliner; includes a `<template id="__bundler_thumbnail">` splash (crown-coin + tri-bar + "WEBINAR KNOWLEDGE VAULT / VOLUME 09" on `#050505`). Verified to render offline with no console errors.
- **Editing:** edit the `.dc.html` source and re-export; do not edit the compiled standalone file directly.

---

## 6. How to review

1. Open `MAIM 09 Webinar Knowledge Vault.dc.html` in the project (live, editable).
2. Scroll Cover → 10 → Closing. Each section is labeled via `data-screen-label`.
3. To regenerate the offline file after edits: re-run the standalone export on the `.dc.html`.

*One live room. Infinite assets. Likkle by likkle, we build the future.*
