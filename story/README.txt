Scroll-story photographic plates
================================

The scroll sequence at the top of index.html can display one full-bleed
photographic plate per beat. The plates are OPTIONAL: if none of the files
below load, the engine adds a `.no-plates` class and every beat still reads
correctly on the data visualisation and typography alone.

To enable them, drop four images into this folder with these exact names:

  1942-chicago-pile.jpg
        Chicago Pile-1 under the west stands of Stagg Field, 2 Dec 1942.
        Graphite block / wooden scaffold. Monochrome works best.

  1960s-buildout.jpg
        A single-containment PWR on a river at low sun — the postwar
        commercial buildout. Wide, horizon-level framing.

  1979-three-mile-island.jpg
        Three Mile Island from the air: four cooling towers, two plumed,
        river fog on the Susquehanna.

  2026-advanced-reactors.jpg
        A present-day advanced-reactor site (e.g. the Valar Atomics
        Ward facility). Daylight, built environment.

Notes
-----
* Landscape, 2000px+ on the long edge, under ~500 KB each after compression.
* They are rendered behind a dark scrim and pushed through
  `grayscale(1) contrast(1.06) brightness(.62)` plus a vignette, so busy or
  low-contrast source images still sit quietly under the type.
* Filenames are referenced in the `.plate` elements near the top of
  index.html; change them there if you prefer different names.
