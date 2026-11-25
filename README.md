# KEVINCHE-ZONE — revival

Archive reconstruction (2026) of **KEVINCHE-ZONE**, my personal site built with Tripod
SiteBuilder in **2005** at http://kevinchezone.tripod.com/.

Live: https://kevinch3.github.io/kevinchezone-tripod/

## Source

Only the home page survives, in the Wayback Machine capture of 2018-03-30 09:24:33 UTC:
https://web.archive.org/web/20180330092433/http://kevinchezone.tripod.com/
The images under `imagelib/` and `sitebuildercontent/` and the Flash banner (`ban2.swf`) come
from the same capture. The first commit of this repo has the raw archived HTML.

## What changed

- The SiteBuilder table soup and `<font>` tags were replaced with plain HTML plus `css/kzone.css`,
  which reproduces the "mkg_vision_blue" layout and collapses to one column on phones.
- The Tripod/Lycos toolbar, ads and tracking scripts are gone, along with the widgets whose services
  no longer exist (sitiosargentina news, miarroba, Nedstat, Bannerlandia, page counter).
  The guestbook links are kept as text, and the two "free domain" boxes are kept but no longer link.
- The Flash banner plays through [Ruffle](https://ruffle.rs) 0.8.0, loaded from unpkg.
- The original contact email address was removed.
- `id15.html` (Trabajos), `enviapostal.html` (postales) and `id4.html` (Contactame) were never
  archived, so they are **recreations**, written to fit what the home page says about them.
  Their forms send nothing.
- `.nojekyll` is there so GitHub Pages publishes the `.pond/` image folder.
