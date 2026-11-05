# platsprites (web)

Versión web de platsprites, publicada en GitHub Pages: https://cacosted.github.io/platsprites-web/

Cambia los sprites del protagonista y de los rivales en ROMs de Pokémon Platino, HeartGold, SoulSilver, Negro, Blanco y Esmeralda. Todo corre en tu navegador con Pyodide: la ROM y los PNG nunca salen de la pestaña.

`index.html` se genera desde el repo privado `platinum-sprites`. Para actualizarlo:

```bash
cd ../platinum-sprites && uv run platsprites web ../platsprites-web/index.html
cd ../platsprites-web && git commit -am "Actualizar la página" && git push
```
