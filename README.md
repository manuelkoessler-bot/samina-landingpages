# schlafen.samina.com – SAMINA Landingpages

Zentrales Repo für alle SAMINA-Landingpages auf GitHub Pages unter der Domain **https://schlafen.samina.com** (DNS bei SAMINA: CNAME → manuelkoessler-bot.github.io).

- Jede Landingpage = eigener Unterordner, z. B. `hotels/` → https://schlafen.samina.com/hotels/
- Keine neuen github.io-Repos für SAMINA – immer hier einen Ordner anlegen.
- `CNAME` nicht löschen (sonst fällt die Domain weg).
- Vorschauen: `<meta name="robots" content="noindex, nofollow">` + `robots.txt` (Disallow) bis zur Freigabe.
- OG-/Canonical-URLs immer absolut mit `https://schlafen.samina.com/<ordner>/`.

| Ordner | Seite | Quelle (Claude-Projektordner) |
|---|---|---|
| `hotels/` | Vertriebs-LP Hotels „Ihr Upgrade mit SAMINA“ (noindex, 1:1-Akquise, ein Link, Kontakte durchklickbar) | `Projekte/LP_Hotels_v2/` (`build.py`) |
| `longevity-center/` | Vertriebs-LP Longevity-Center „Schlaf macht Ihr Longevity-Center komplett“ (noindex, Partner-Akquise, Green Room + A-Serie) | `Projekte/LP_Longevity_Center/` (`build.py`) |
| `hotelpraesentation/` | Hotelpräsentation (Deck, passwortgeschützt, StatiCrypt) – Philipp unter `/`, `/daniel`, `/mathias` | `Projekte/Praesentation_Hotels/` (`tools/deploy_hotels.sh`) |
