# High-resolution hero portraits

## Clovis teeth correction — 2026-10-06

`clovis.png` now has natural human teeth in place of the elongated fangs, retaining his battle expression. It is a 1254 × 1254 transparent master edited with built-in image generation. `../clovis-v2.png` is the matching 516 × 258 transparent UI export, produced using the same reduction and padding as Silas. Previous versions are saved in `archive/clovis-before-teeth-fix.png` and `archive/clovis-v2-before-teeth-fix.png`. The exact prompt and current checksums are in `clovis-teeth-prompt.txt` and `clovis-teeth-validation.json`; the original batch validation below predates this edit.

## Silas update — 2026-10-06

Silas has now been remade with head-only framing at the user's request. `silas.png` is the native 1254 × 1254 transparent master from the built-in image generation tool. `../silas-v2.png` is its Lanczos reduction to 258 × 258, centered on a transparent 516 × 258 canvas to match the existing UI asset dimensions. The previous v2 asset is backed up at `archive/silas-v2-before-head-only.png`.

The exact prompt is in `silas-head-only-prompt.txt`; current dimensions, alpha ranges and checksums are in `silas-head-only-validation.json`. The original preservation checks below describe the earlier generation batch, before this requested Silas replacement. Tabletop Simulator import has not been tested.

## Original batch — 2026-10-05

15 head-only portraits generated with the built-in image generation tool, using `../silas-v2.png` as the visual style reference and original Zombicide illustrations as character references. Silas itself was not regenerated or modified.

All final PNGs are **1254 x 1254 RGBA**, with real transparency. The prompt requested 2048 x 2048 or the highest supported resolution; the tool returned 1254 x 1254. Files were copied verbatim with no resizing or postprocessing.

## Deliverables

- Black Plague: ann.png, baldric.png, clovis.png, nelly.png, samson.png. Existing Silas retained at ../silas-v2.png.
- Wulfsburg: ariane.png, karl.png, morrigan.png, theo.png.
- Green Horde: asim.png, berin.png, johannes.png, megan.png, rolf.png, seli.png.

The previous portraits remain in the parent directory. These square master images have not been integrated into the existing interface or reduced to its dimensions.

## References and generation record

The user clarified that the full-size official originals were acceptable character references and requested head-only framing. All 15 heroes therefore proceeded.

- Official gallery: https://www.zombicide.com/zombicide-fantasy-survivors-gallery/
- Individual official page and artwork URLs with measured dimensions: references/sources.json.
- Larger Green Horde promotional illustrations: https://zombicide.eren-histarion.fr/zombicide-green-horde/ and https://the-dark-templar.blogspot.com/2017/04/ . Downloaded files and measured dimensions are recorded in references/alternate-sources.json.
- Black Plague and Wulfsburg generation used the official 950 x 800 character references. Green Horde generation used matching 1200 x 1200 promotional character artwork for clearer face detail (Berin from alternate-ZGT_s_Berin.jpg; the others from alternate-ZGH_Name_01.jpg).
- Exact per-character prompts and generated source paths: prompts.json.
- Dimensions, alpha checks, hashes, and Silas preservation result: validation.json.
- Original Silas checksums: silas-preserved.sha256.

Visual review checked character identity cues, head framing, readable names, and the shared Silas-inspired ring and parchment treatment. These are generated reinterpretations rather than exact reproductions; the shared frame is visually matched, not pixel-identical between portraits.
