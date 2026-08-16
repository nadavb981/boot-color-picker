# Colorway Studio

A single-page tool for shortlisting production colours on a moulded rubber dog boot.

Pick a colour and the whole boot takes it — shell, sole, clip and velcro band all mould
in one colour, so there is nothing to paint separately. Heart the ones worth keeping,
write notes against each, and switch the backdrop between white, 18% grey and charcoal —
the same colour reads differently against each, and 18% grey is what colour is normally
judged against.

Each colour carries the nearest Pantone FHI cotton standard (TCX), found by minimising
CIEDE2000 in CIELAB and checked by hand against pantone.com. The Pantone palette puts
your colour and the standard side by side so the ΔE between them has something to look
at.

"Copy my board" bundles the whole palette, favourites and notes into a link so someone
else opens exactly what you see, and can send one back.

Self-contained: one HTML file, no build step, no dependencies, no network requests.
The boot is a photograph recoloured live through per-region masks and a shading map.

## Note on accuracy

No screen is colour-accurate enough to sign off a production colour. This narrows a
shortlist; physical colour chips in the real material settle it.
