# Marshall Foiles Pulling Archive

A sourced archive of Marshall Foiles' two-wheel-drive truck pulling career — Xenia, Ohio,
competing with the Chevrolet modified truck *Kickstart My Heart* from at least 2015 to 2025.

Live site: https://tfoiles.github.io/marshall-foiles-pulling/

## What this is

Every result on the page comes from a primary sanctioning-body results sheet — NTPA
(National Tractor Pullers Association) or OSTPA (Ohio State Tractor Pullers Association) —
or, in one flagged case, a dated newspaper article. Distances are reproduced exactly as the
sheets record them. Where a sheet left a class unranked or cancelled, the page says so
rather than guessing.

The headline result: an **NTPA Grand National class win at the Preble County Fair on
5 August 2022**, 342.655 ft, first of five.

## How it was assembled

- The complete NTPA static results archive for 2009–2022 (~6,600 class result sheets) was
  crawled and searched. Foiles appears only from 2017 onward.
- All 269 posts in the OSTPA results blog (which begins January 2021) were crawled and searched.
- OSTPA season standings for 2016–2018 were recovered from Internet Archive captures of
  published Google Sheets that OSTPA has since deleted.

Known gaps are listed on the page itself rather than hidden: 2023–2026 NTPA results sit
behind an account, individual 2015–2016 runs were never published in detail, and the truck's
engine and chassis are undocumented.

## Technical

`index.html` is a single self-contained file. Blueprint v6 CSS is inlined, all images are
data URIs, and there are no external scripts, stylesheets, fonts or runtime network calls.
It runs from any static host or straight off disk, and nothing on it can break because a
CDN went away.
