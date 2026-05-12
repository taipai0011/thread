# doma thread assets

a twitter thread + notebook-style architecture diagram explaining how doma lets
ai agents buy and sell tokenized domains end-to-end.

## files

- `doma-notebook.svg` — the diagram. 720x930 (3:4 paper ratio). open in any
  browser or drop into figma. white background, asymmetric on purpose.
- `preview.html` — quick viewer. open locally to screenshot a clean PNG for
  twitter.
- `thread.md` — the 8-tweet thread text.

## turning the svg into a png

any of these work:

- open `preview.html`, zoom to fit, screenshot
- drag `doma-notebook.svg` into figma &rarr; export as PNG @2x
- `rsvg-convert -w 1440 doma-notebook.svg -o doma-notebook.png`
- online: cloudconvert, svgtopng, etc.

## the sources this is built from

- https://blog.doma.xyz/the-agentic-domain-part-2-agentic-payments-in-action/
- https://docs.doma.xyz/agentic-commerce
- https://doma.xyz/.well-known/skills/trade-tokens/SKILL.md
