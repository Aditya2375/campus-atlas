# Campus Atlas

An interactive **schematic planner**, not a geographic or navigational map. Its geometry, paths, zones, pins and highlighted areas are illustrative placeholders. Do not use for wayfinding. North Campus, South Campus, Maple House and Cedar House are fictional starter locations on an invented campus; every pin is an example, coordinates are not GPS, and the layer control separates example pins from your own notes.

Visitors can switch the four places, click sample unverified pins, toggle layers, zoom/pan the schematic, add private notes and place their own browser-local draft pin. Pin coordinates are canvas positions, not GPS. Notes live in localStorage only. Nothing syncs.

## Run
`npm install && npm run dev` then `npm run build`.

## Next steps
Collect actual campus floor plans and hostel maps, permission to use them, real landmark names and coordinates. Replace `src/places.js` with verified data and real base maps before offering navigation. For a real map, establish a georeferenced basemap and validation with the user; do not reuse this schematic as if it were spatially accurate.
