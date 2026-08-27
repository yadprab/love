# love

A letter, instead of a profile.

A single-page invitation: a wax-sealed envelope that opens into a hand-written
letter. Built as one self-contained HTML file — no build step, no framework,
no dependencies beyond Google Fonts.

## Run it locally

```bash
python3 -m http.server 4173
```

Then open <http://localhost:4173>.

## Notes

- The envelope is a baronial fold (pointed flap, diagonal seams). The seal is
  Tyrian purple — the imperial murex dye — struck with a crowned cypher.
- The rose sprays are an Art Nouveau ornament from 1905, public domain, via
  Wikimedia Commons.
- Respects `prefers-reduced-motion`: the envelope is skipped and the letter is
  shown directly.
- Every text tone clears WCAG AA contrast against the paper.
