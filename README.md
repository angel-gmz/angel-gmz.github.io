# XcaliGames · Web de Torchbound

Sitio estático publicado con Firebase Hosting (proyecto `alamesapp`).

- `public/index.html` — página de Torchbound
- `public/app-ads.txt` — autorización de AdMob (debe quedar en la raíz: `https://<dominio>/app-ads.txt`)

## Publicar
- Automático: cada push a `main` despliega con GitHub Actions (`.github/workflows/`).
- Manual: `firebase deploy --only hosting`

## Importante
La URL del sitio debe ser la misma que aparece como "Sitio web" en la ficha de Play Store de cada app,
para que AdMob encuentre el `app-ads.txt`.
