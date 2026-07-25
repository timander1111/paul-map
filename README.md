# Paul of Tarsus — A Life in Journeys

An interactive map and timeline of the life of the apostle Paul: fifty events
from birth in Tarsus to martyrdom in Rome, with the journeys drawn out, the
Roman provinces as they stood around AD 50, and the scripture behind each stop.

It is a single self-contained HTML file. No build step, no framework, no
external requests — open `index.html` and it works offline.

## Using it

- **drag** to pan, **scroll** or **pinch** to zoom
- **double-click** to zoom in, shift-double-click to zoom out
- <kbd>+</kbd> / <kbd>−</kbd> / <kbd>0</kbd> to zoom and reset
- <kbd>←</kbd> / <kbd>→</kbd> to step through the events
- toggles for modern borders and cities, if you want to see where these places
  are today

Zoom out past the eastern Mediterranean and the province layer fades — those
boundaries are schematic and only meaningful at Roman-world scale.

## What it claims, and what it doesn't

The events come from Acts and from Paul's own letters, and each panel links the
passage it rests on so you can check it. Where the two sources are hard to
reconcile, or where the dating turns on a contested reconstruction, the panel
says so under **Where scholars differ** — the early dating of Galatians, the
possible Ephesian imprisonment, and whether Galatians 2 describes the famine
visit or the Jerusalem council are the main ones.

Dates are approximate. Pauline chronology hangs off a small number of fixed
points — above all the Delphi inscription placing Gallio's proconsulship of
Achaia in 51/52 — and the rest is reasoned outward from those. This
map's overall sequence follows N. T. Wright, *Paul: A Biography* (HarperOne,
2018), which is one reconstruction among several. It is not affiliated with or
endorsed by the author or publisher.

Distances are rough great-circle estimates along the drawn route, running totals
from the Damascus road onward. They are there to give a sense of scale, not to
be measured against.

## Sources and credits

- Events and chronology: Acts, the Pauline letters, and Wright's *Paul: A
  Biography* for the ordering
- Basemap coastlines and modern borders: [Natural Earth](https://www.naturalearthdata.com/)
  50m data, public domain, baked into the page as SVG paths at build time
- Scripture links: [Bible Gateway](https://www.biblegateway.com/)
- Typefaces: Playfair Display, Source Serif 4, Inter, JetBrains Mono — subset to
  latin and latin-ext and bundled in `fonts/`

## Licence

The map, its text and its code are licensed
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — reuse or adapt it
freely, with attribution. Full text in [LICENSE](LICENSE).

The bundled fonts are **not** covered by that licence. Each is under the SIL
Open Font License 1.1; see [fonts/OFL.txt](fonts/OFL.txt).

Scripture quotations and the underlying biblical text are not claimed by this
project.
