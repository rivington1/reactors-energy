Scroll-story images
===================

Plates (full-bleed, one per beat)
---------------------------------
beat1.jpg .. beat4.jpg are the four transition slides, shown full-bleed
behind each beat's text. They come from the author's source document:

  beat1.jpg   Chicago Pile-1, cutaway drawing by Melvin A. Miller, 1946.
  beat2.jpg   Single-containment PWR on a river at low sun (1960s-70s buildout).
  beat3.jpg   Three Mile Island from the air, cooling towers plumed.
  beat4.jpg   Valar Atomics Ward facility (present-day advanced reactor site).

The plates are still optional at runtime: if none load, the engine adds a
`.no-plates` class and the sequence reads on the data graphic and type alone.
Rendered at `saturate(.94) contrast(1.03) brightness(.82)` under a light
vignette so the text stays legible.

Minis (small cards pinned to the timeline)
------------------------------------------
story/minis/*.jpg are small photographs of individual reactors. Each card is
pinned to a year on the shared time axis (`data-y` on the `.mini` elements in
index.html) and rides the story camera: it appears once the reveal front
passes its date and pans with the axis. Hidden on narrow viewports and under
prefers-reduced-motion.

Mini sources — lead images of the corresponding English Wikipedia articles,
fetched 2026-08-22 (largely NRC / DOE / TVA public-domain photographs;
see each article's file page for exact license):

  ebr1.jpg          Experimental Breeder Reactor I
  shippingport.jpg  Shippingport Atomic Power Station
  dresden.jpg       Dresden Generating Station
  indianpoint.jpg   Indian Point Energy Center
  brownsferry.jpg   Browns Ferry Nuclear Plant
  tmi.jpg           Three Mile Island Nuclear Generating Station
  diablo.jpg        Diablo Canyon Power Plant
  paloverde.jpg     Palo Verde Nuclear Generating Station
  shoreham.jpg      Shoreham Nuclear Power Plant
  wattsbar.jpg      Watts Bar Nuclear Plant
  vogtle.jpg        Vogtle Electric Generating Plant
