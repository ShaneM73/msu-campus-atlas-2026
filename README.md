# Missouri State 3D Atlas

An interactive 3D infographic of the Missouri State University campus in Springfield, Missouri, built from current OpenStreetMap data.

Map data © OpenStreetMap contributors, available under the Open Database License (https://www.openstreetmap.org/copyright).

## Files
- `index.html` - the page
- `msu-atlas-app.js` - page code with the 3D engine (three.js) bundled in
- `msu-map.json` - buildings, roads and parks converted from an OpenStreetMap export

Keep all three files together and serve them from a web server (GitHub Pages works). Opening `index.html` by double-clicking will not load the map data.

## Publish on GitHub Pages
1. Create a new, empty public repository and add these files (GitHub Desktop: File > Add local repository, then Publish with "Keep this code private" unchecked).
2. Settings > Pages > Deploy from a branch > `main`, `/ (root)` > Save.
3. The site appears at `https://<your-username>.github.io/<repository-name>/`.
