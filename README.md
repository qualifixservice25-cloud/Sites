# Sites (non più usato)

Questo repository conteneva una pagina indice e il sito di Sviluppo Lamiera
(branch `sviluppo-lamiera`, pubblicato in `gh-pages`).

**Tutti i siti delle app ora stanno nel sito unico:**
https://qualifixservice25-cloud.github.io/
(repository [`qualifixservice25-cloud.github.io`](https://github.com/qualifixservice25-cloud/qualifixservice25-cloud.github.io)).

- Sviluppo Lamiera: https://qualifixservice25-cloud.github.io/sviluppo-lamiera/

Il workflow che pubblicava ogni branch in una sottocartella di `gh-pages` è
stato tolto. `index.html` rimanda al sito unico.

Dopo l'unione di questo branch in `main`:
1. Settings → Pages: imposta la sorgente su `main` / root, così `/Sites/` rimanda al sito unico. In alternativa disattiva Pages.
2. Quando nessun link punta più qui, archivia il repository (Settings → Archive).
