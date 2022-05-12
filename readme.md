# leaflet-gis-test

HTML and supporting CSS, javascript and GIS files to create an interactive Antarctic map using Leaflet <https://leafletjs.com/>.

Built with a ton of high quality, open-source components:

- unpkg fast, global content delivery network <https://unpkg.com/>
- Leaflet <https://leafletjs.com/>
- Proj4.js <https://github.com/proj4js/proj4js>
- Proj4Leaflet <https://github.com/kartena/Proj4Leaflet>
- Global Biodiversity Information Facility (GBIF) map tiles <https://tile.gbif-uat.org/ui/>
- PouchDB <https://pouchdb.com/>
- Leaflet.TileLayer.PouchDBCached <https://github.com/MazeMap/Leaflet.TileLayer.PouchDBCached>
- Leaflet.Permalink <https://github.com/MarcChasse/leaflet.Permalink>

## To develop locally

Download this repo, and serve `index.html` (for instance, using Node module `http-serve` calling a command line like `http-server -c-1 -o`).

## Hosted with Render

This project is hosted for free as a Render static site at <https://project-basket-star.onrender.com/>.

Render's static sites provide features like caching, HTTPS, free bandwidth, pull from GitHub repo, HTTP/2 support and more.

To set up a static site on Render, follow documentation at <https://render.com/docs/static-sites>. To help the site better meet webhint (<https://webhint.io/>) guidelines, extend the caching of images like `/favicon.ico` and `/logo.png` using Render custom HTTP headers for `Cache-Control`, set to recommendation of `immutable, max-age=31536000`.
