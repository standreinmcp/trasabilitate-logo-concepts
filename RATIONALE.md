# Trasabilitate Sterilizare — Logo Concepts

Three distinct directions for the app logo, all anchored on the existing brand
indigo **#4f46e5**. Every file's text is converted to vector outlines
(Manrope ExtraBold / Medium), so the SVGs render identically everywhere with
no font installs.

## Recommended: Direction A — "The Verified Chain"

**Form.** Three stacked rounded bars — the visual language of instrument
packages on a sterilisation shelf, read top to bottom like a ledger. The
middle bar is punched with a QR finder pattern (two finder squares + timing
modules): the physical package literally becomes its digital record. The top
bar carries a status pair — one filled dot (cycle completed) and one open
ring (sterility valid now). The bottom bar ends short, followed by a receding
tint segment: the chain of custody continues past the edge of the mark.

**Colour.** Indigo gradient #6366f1 → #4338ca keeps #4f46e5 as the visual
centre of gravity; the tint segment uses #a5b4fc so depth = history.
Wordmark in ink #1e1b4b (indigo-950), subword letterspaced slate #64748b.

**Why it works.** It's specific to this product — packages + scanning +
history — rather than generic "medical". It's calm and grid-based, matching a
desktop-first, medical-grade UI. The QR punch gives it a signature detail
that survives as a texture at icon size.

## Direction B — "The Sterile Ledger"

Shield outline (protection/clinical safety) containing three ledger rows,
the third dashed — a reprocessing cycle still open. The most conventional of
the three: reads instantly as "medical + records", safest choice if the
owner wants zero ambiguity for clinic buyers. Slightly more "system" and
slightly less "product" than A.

## Direction C — "Scannable T"

Monogram built from QR structural grammar: a rounded crossbar with a knocked
notch (scan beam), a stem of two squares where the bottom one is an open
outline — data recorded, cycle continuing. Most compact and ownable at tiny
sizes; the most abstract. Works best if the brand ever needs a
single-glyph mark (avatars, favicons) more than a descriptive one.

## Files per direction

| File | Use |
|---|---|
| `primary-horizontal.svg/.png` | header, auth screen, landing (light backgrounds) |
| `primary-horizontal-reversed.svg/.png` | dark UI, footers on indigo |
| `app-icon-512.svg/.png` | PWA icon, social avatar (rounded-square tile) |
| `favicon-48/32/16.png` | browser tab (rendered from the same 512 tile) |

All PNGs have transparent backgrounds. The review board
(`review_board.png`) shows every lockup on light/tint/dark plus a simulated
16 px browser-tab strip and a 26 px app header.

## Palette

- #4f46e5 brand anchor (existing) · #6366f1/#4338ca gradient · #a5b4fc trail
- #1e1b4b wordmark ink · #64748b subword

**Recommendation: A.** It says the truest thing about the product — packages
that carry their own history — and its icon degrades best at 16 px.
