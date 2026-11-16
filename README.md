# Web del CAU · AEiG Joan XXIII de Martorell

Web estàtica en català. Conté HTML, CSS i imatges; no necessita compilació, Node.js ni base de dades.

## Publicació al servidor

1. Descarrega el repositori des de **Code → Download ZIP** o clona’l amb Git.
2. Puja els fitxers `.html`, `styles.css` i la carpeta `assets/` al directori públic del servidor (habitualment `www/`, `public_html/` o `htdocs/`).
3. Mantén `index.html` a l’arrel pública i conserva els noms i l’estructura de `assets/`.
4. Obre el domini i comprova la navegació, les imatges i el calendari.

Si el proveïdor demana una carpeta de publicació, selecciona l’arrel del repositori (`.`). No cal cap ordre de compilació.

## Vista prèvia local

Des de la carpeta del repositori:

```sh
python3 -m http.server 8000
```

Obre `http://localhost:8000`.

## Fitxers

- `index.html`: portada.
- `qui-som.html`, `branques.html`, `noticies.html` i `sortida-de-passos-2026.html`: pàgines de contingut.
- `concepte-1.html`, `concepte-2.html`, `concepte-3.html` i `foulard-propostes.html`: propostes de disseny conservades.
- `styles.css`: estils compartits.
- `assets/`: imatges i logotips.

El calendari de Google, el mapa i algunes imatges dels conceptes es carreguen des de serveis externs i requereixen connexió a Internet. Per modificar l’agenda, actualitza el calendari de Google incrustat.
