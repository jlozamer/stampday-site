# stampday.app

Public site for the Stampday iPhone app (KorePudo Ltd): landing page, privacy policy, support page, and the signed
residence rules the app can download (`rules.json` + `rules.json.sig`, Ed25519). Served by GitHub Pages at
https://stampday.app. Never edit `rules.json` without signing it again.

## Languages
`index.html` is the English landing page and `es/index.html` the Spanish one, section for section; each links to
the other in its menu and footer. Change both together. The Spanish page's app pictures are in `img/es/`.
Privacy and support are in English only for now (the Spanish page says so on its links).
