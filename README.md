# Quadretti — Matematica da zero all'AFM

App web per esercitarsi in matematica: esercizi generati con l'API Anthropic,
soluzioni passo per passo stile Photomath, pulsante "Non ho capito" che spiega
i concetti sempre più alla base, chat con il tutor, progressi salvati in locale.

## Struttura
- `index.html` — tutta l'app in un unico file (HTML + CSS + JS, nessuna build)

## Deploy
GitHub Pages tramite GitHub Actions (`.github/workflows/deploy-pages.yml`).
Ogni push pubblica automaticamente il sito. Nessuna dipendenza, nessun build step.

Sito online: https://serxhiobiba26-ctrl.github.io/matematica/

## Dopo il deploy
Aprire il sito → ⚙️ Impostazioni → incollare la chiave API Anthropic (resta in localStorage).
