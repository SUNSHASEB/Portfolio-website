# Portfolio website

Sunil Sebastian's portfolio: a home page built from the Figma landing page, four brand design case studies and a showreel page. Plain HTML, CSS and JavaScript, no build step.

## Pages

| Page | Path |
| --- | --- |
| Home | `index.html` |
| Namma Farm | `namma-farm/` |
| Scooch Over | `scooch/` |
| APC | `accelerated-professional-center/` |
| Imagination Holdings | `imagination-holdings/` |
| Showreel | `showreel/` |

## Preview locally

```bash
python3 .claude/serve.py 4321 .
```

Then open http://localhost:4321. This server adds HTTP Range support to Python's built-in one, so videos can seek (the showreel chapters need it).
