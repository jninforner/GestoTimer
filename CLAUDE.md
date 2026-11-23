# GestoTimer (temporitzadors de cuina)

Respon sempre en català; Joan és principiant, explica pas a pas i una cosa cada vegada.

- App web instal·lable (PWA) de **temporitzadors**: fitxers `index.html` (tot el codi), `sw.js`, `manifest.json`, icones. Sense servidor, sense compilació, sense base de dades: les dades es desen al navegador (`localStorage`).
- Publicació: GitHub Pages, https://jninforner.github.io/GestoTimer/ (branca `main`).
- La versió és en **tres llocs** que s'han de canviar junts: `APP_VERSION` a `index.html`, `version` a `manifest.json` i el nom de la memòria cau `CACHE` a `sw.js` (si no es canvia `CACHE`, els mòbils continuen veient la versió vella).
- L’app abans es deia "Temporitzadors"; el nom intern de la dada desada (`nombreTemporitzadors` a localStorage) es manté per no perdre els ajustos.
