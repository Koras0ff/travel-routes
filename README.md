# Hachicho Routes — interactive map of 18th-century travellers

An interactive map of the routes of 18th-century English travellers to the Arab
Near East, extracted and geocoded from:

> Mohamad Ali Hachicho, *"English Travel Books about the Arab Near East in the
> Eighteenth Century"*, **Die Welt des Islams**, New Series, Vol. 9, Issue 1/4
> (1964), pp. 1–206. [JSTOR 1570430](https://www.jstor.org/stable/1570430)

## Reading the map
The map opens **empty** on purpose — all 27 routes at once is an unreadable hairball.
- Tick a **group** (Hachicho's categories) or an individual **traveller** to draw routes.
- **Click a traveller's name to spotlight it**: their route goes bold (with **direction
  arrows**), every other shown route fades, and a **traveller panel** opens with the
  work title(s), a Hachicho page reference, and the full **numbered itinerary** (dates /
  notes, unlocated stops marked). Click a located stop in that list to jump to its place.
  Click the name again, hit *Clear focus*, or click the map to release.
- Markers appear only for the travellers currently shown; size = how many passed through.
  Click a marker for its place details.
- *Show all* / *Clear* toggle everything; base-map chooser is bottom-right.
- **Export PNG** saves the current map view as an image for thesis figures (base-map tiles
  are captured too when online; controls and panels are excluded).

### Confidence levels
- **high** — unambiguous, well-known place.
- **med** — identifiable town; coordinates good to town level.
- **low** — approximate; desert watering placed along the known caravan track.
- **unlocated** — could not be placed (63 obscure desert stages; several are
  flagged *"not identified"* by Hachicho himself). These still appear in each
  route's stop list but are not plotted.

## Things to consider
- The OCR is imperfect; route lines were parsed and the place names normalised,
  but a few obscure tokens may still be mis-split.
- Coordinates for desert stages are deliberately approximate (see confidence).
- Lines are drawn between consecutive *located* stops; where a stop is
  unlocated the line simply skips it, so a segment may be schematic.
