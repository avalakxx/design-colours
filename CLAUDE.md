# CLAUDE.md

This repo is the user's colour reference: Sanzo Wada's *A Dictionary of Color Combinations* (Vol. 1). Whenever a task involves choosing colours (UI, pages, artifacts, charts, images, logos, etc.), take them from here.

- `color-combinations.json`: 159 colours (`name`, `name_jp`, book `cmyk`, screen `hex`, `combinations`) and 348 combinations (`colors` = colour ids). #1–120 are pairs, #121–240 triads, #241–348 four-colour sets.
- `color-combinations.md`: the same data as readable tables.
- `preview.html`: visual preview of every combination.

How to use it:

1. Pick a whole combination from the book rather than mixing colours from different ones. Cite it by number (e.g. "combination #348") so the choice is traceable.
2. Use `hex` for screens; `hex_cmyk` is a naive conversion and usually too saturated. For print, use `cmyk`.
3. Suggest 2–3 candidate combinations that fit the mood of the task, and let the user choose before building around one.
4. Neutrals for text and backgrounds may come from the White / Gray / Black group (ids 154–159) if the chosen combination has no suitable light or dark colour. Check text contrast (WCAG AA) and pick a darker or lighter colour from the same combination when it fails.
