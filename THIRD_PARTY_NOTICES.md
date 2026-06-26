# Third-Party Notices

This project is a custom SciTopus Dashboard implementation. Production data is not included in this repository.

## D3.js

- Package: D3.js v7.9.0
- Website: https://d3js.org/
- Source: https://github.com/d3/d3
- Copyright: Copyright 2010-2023 Mike Bostock
- License: ISC

The bundled file `dashboard/vendor/d3.v7.min.js` is used as the visualization runtime.

ISC License:

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

## Bar Chart Race Reference

- Reference: Bar Chart Race / D3
- URL: https://observablehq.com/@d3/bar-chart-race
- Author: Mike Bostock
- License shown by Observable: ISC
- Related explained notebook: https://observablehq.com/@d3/bar-chart-race-explained

The Race mode follows the bar chart race visualization pattern and was initially checked against the Observable D3 reference above. The SciTopus Dashboard implementation is now a standalone custom dashboard rather than a direct fork: it includes custom data loading, custom controls, multiple visualization modes, theme handling, timeline behavior, filters, image toggles, and category-specific logic.

## Cyberpunk Visual Style Reference

- Reference: mplcyberpunk
- URL: https://github.com/dhaitz/mplcyberpunk
- Author: Dominik Haitz
- License: MIT License

The dashboard's night theme and early chart styling were visually informed by the cyberpunk-style dark background, bright cyan/magenta palette, glow, and underglow approach used by `mplcyberpunk`.

`mplcyberpunk` is not bundled in this repository and is not a runtime dependency of the dashboard. The attribution here is for visual inspiration and design reference, not for vendored source code.
