# systemvaruhuset.se

Statisk webbplats för Systemvaruhuset (EnnyPermit & EnnyTicket), publicerad med GitHub Pages.

## Förhandsgranska lokalt
    python3 -m http.server 8000
Öppna http://localhost:8000.

Tema: **Jord** (svart bakgrund med sand, olivgrön och blågrått enligt färgkartan; Fraunces + Instrument Sans).

## Publicera
1. Pusha till ett GitHub-repo och gå till **Settings → Pages**: *Deploy from a branch*, `main` / root.
2. Filen `CNAME` innehåller `systemvaruhuset.se`. Hos DNS-leverantören:
   - A-poster för `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME `www` → `<användarnamn>.github.io`
3. Aktivera **Enforce HTTPS** när certifikatet är klart.
