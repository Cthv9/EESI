# Documenti ISEE 2026 (PWA statica)

Questa è una copia “gemella” dell’app 730, adattata al caricamento dei documenti ISEE 2026.

## Come pubblicarla su GitHub Pages
1. Crea un nuovo repository (es. `isee`).
2. Carica **tutti** i file di questa cartella (index.html, manifest.json, service-worker.js, icons/…).
3. Repository → **Settings** → **Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`
4. Apri l’URL di GitHub Pages del repo.

## Note
- I file caricati restano nel browser finché la pagina è aperta (come nella tua app originale).  
- Il download genera ZIP separati per sezione, spezzando gli ZIP in pezzi da 5MB.
