# design-colours

Sanzo Wada's *A Dictionary of Color Combinations*, Vol. 1 (配色総鑑, 1933–34; Seigensha reprint), as data.

- 159 colours with Japanese and English names, book CMYK and screen HEX
- 348 combinations: #1–120 pairs, #121–240 triads, #241–348 four-colour sets

| File | Contents |
|---|---|
| `color-combinations.json` | All colours and combinations, machine-readable |
| `color-combinations.md` | The same as readable tables |
| `preview.html` | Every combination as swatches, filterable by size |
| `colors-source.txt` | Raw transcription of the book's colour index |

`hex` is sampled from the scanned swatches in the book's index (white-balanced to the paper), so it approximates the printed colour on screen. `hex_cmyk` is a naive CMYK→RGB conversion and is usually too saturated. `cmyk` is exactly as printed in the book.
