# leaflet-gis-test

HTML and supporting CSS, javascript and GIS files to create an interactive Antarctic map using Leaflet <https://leafletjs.com/>.

Map tiles from Global Biodiversity Information Facility (GBIF) <https://tile.gbif.org/ui/>.

Built with a ton of high quality, open-source components:

- unpkg fast, global content delivery network <https://unpkg.com/>
- Leaflet <https://leafletjs.com/>
- Proj4.js <https://github.com/proj4js/proj4js>
- Proj4Leaflet <https://github.com/kartena/Proj4Leaflet>
- PouchDB <https://pouchdb.com/>
- Leaflet.TileLayer.PouchDBCached <https://github.com/MazeMap/Leaflet.TileLayer.PouchDBCached>
- Leaflet.Permalink <https://github.com/MarcChasse/leaflet.Permalink>
- Shapefile.js <https://github.com/calvinmetcalf/shapefile-js>
- Leaflet.EasyButton <https://github.com/CliffCloud/Leaflet.EasyButton>
- Leaflet.TileLayer.NoGap <https://github.com/Leaflet/Leaflet.TileLayer.NoGap>
- Leaflet.MousePosition <https://github.com/ardhi/Leaflet.MousePosition>

## To develop locally

Download this repo, and serve `index.html` (for instance, using Node module `http-serve` calling a command line like `http-server -c-1 -o`).

## Hosting with Render

This project is hosted for free as a Render static site at <https://project-basket-star.onrender.com/>.

Render's static sites provide features like caching, HTTPS, free bandwidth, pull from GitHub repo, HTTP/2 support and more.

To set up a static site on Render, follow documentation at <https://render.com/docs/static-sites>. To help the site better meet webhint (<https://webhint.io/>) guidelines, extend the caching of images like `/favicon.ico` and `/logo.png` using Render custom HTTP headers for `Cache-Control`, set to recommendation of `immutable, max-age=31536000`.

## To lint for development

Linting is useful during development to pick up functional and stylistic problems. Javascript in this project is linted using ESLint <https://eslint.org/>. 

ESLint typically requires Node to be installed. Specific rules are set up in the repo's [.eslintrc.json](.eslintrc.json) file.

To set up linting using ESLint and VS Code, do the following steps once:

- install ESLint and plugins locally `npm install --save-dev eslint eslint-plugin-html eslint-plugin-prefer-arrow`
  - `package.json` and `package-lock.json` files and `node_modules` directory will be created (these do not need to be deployed, used for development only)
- install VSCode ESLint extension, see <https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint>

## References

The following sites are useful references for Leaflet and were valuable in getting this demo working:

- Leaflet Tips and Tricks by Malcolm Maclean <https://leanpub.com/leaflet-tips-and-tricks>
- Dynamically Loading multiple External GeoJson data files and calling multiple layers dynamically using Leaflet <https://javascript.tutorialink.com/dynamically-loading-multiple-external-geojson-data-files-and-calling-multiple-layers-dynamically-using-leaflet/>
- Quantarctica <https://www.npolar.no/quantarctica/>
- Arctic Web Map by ArcticConnect <http://webmap.arcticconnect.ca/>