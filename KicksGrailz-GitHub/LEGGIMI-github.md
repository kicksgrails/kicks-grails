# KICKS GRAILZ — Pubblicare su GitHub Pages (ripartenza pulita)

Niente più Netlify. GitHub Pages dà un link nuovo e pulito. La sincronizzazione tra dispositivi è già attiva (Supabase, configurato dentro `index.html`).

I file da caricare sono solo **5**:
- `index.html`  ← l'app (config Supabase già dentro)
- `manifest.json`
- `icon-192.png`
- `icon-512.png`
- `icon-180.png`

(Il `sw.js` è opzionale: serve solo all'offline. Puoi caricarlo o no.)

---

## PASSO 1 — Crea un account GitHub (gratis)

1. Vai su **https://github.com** → **Sign up** → registrati (email + password).
2. Verifica l'email.

## PASSO 2 — Crea il repository

1. In alto a destra clicca il **+** → **New repository**.
2. **Repository name**: scrivi `kg` (o quello che vuoi).
3. Metti la spunta su **Public**.
4. Spunta **Add a README file**.
5. Clicca **Create repository**.

## PASSO 3 — Carica i file

1. Nel repository appena creato, clicca **Add file** → **Upload files**.
2. Trascina dentro i 5 file (index.html, manifest.json, le 3 icone).
3. In basso clicca **Commit changes**.

## PASSO 4 — Attiva GitHub Pages

1. Nel repository, vai su **Settings** (in alto).
2. Menu a sinistra: **Pages**.
3. Sotto "Build and deployment" → **Source**: scegli **Deploy from a branch**.
4. **Branch**: scegli **main**, cartella **/ (root)** → **Save**.
5. Aspetta ~1 minuto. In cima alla pagina Pages comparirà il tuo link, tipo:
   `https://tuonome.github.io/kg/`

## PASSO 5 — Apri e installa

Apri quel link su Mac e sui due telefoni:
- **iPhone (Safari):** Condividi → Aggiungi a Home
- **Android (Chrome):** ⋮ → Installa app
- **Mac (Safari):** File → Aggiungi al Dock

In alto a destra nell'app deve esserci il pallino 🟢 **Sync** = dati sincronizzati su tutti i dispositivi.

---

## AGGIORNARE L'APP IN FUTURO
Vai nel repository → apri `index.html` → icona matita (Edit) → incolla la versione nuova → Commit. Il link resta lo stesso, l'app si aggiorna.

## SE NON SI APRE
A differenza di prima, qui non c'è la cache di Netlify. Se vedi problemi, apri il link in **finestra privata** la prima volta. Se persiste, scrivimi cosa vedi esattamente.
