# schlafen.samina.com – SAMINA Landingpages

Zentrales Repo für alle SAMINA-Landingpages auf GitHub Pages unter der Domain **https://schlafen.samina.com** (DNS bei SAMINA: CNAME → manuelkoessler-bot.github.io).

- Jede Landingpage = eigener Unterordner, z. B. `schraegbett/` → https://schlafen.samina.com/schraegbett/
- Keine neuen github.io-Repos für SAMINA – immer hier einen Ordner anlegen.
- `CNAME` nicht löschen (sonst fällt die Domain weg).
- Vorschauen: `<meta name="robots" content="noindex, nofollow">` + `robots.txt` (Disallow) bis zur Freigabe.
- OG-/Canonical-URLs immer absolut mit `https://schlafen.samina.com/<ordner>/`.

| Ordner | Seite | Quelle (Claude-Projektordner) |
|---|---|---|
| `schraegbett/` | Pillar Schrägbett / Gravitas (Vorschau, noindex) | `Projekte/Pillar_Schraegschlaf/pillar/` (`deploy.py`) |
| `hotels/` | Vertriebs-LP Hotels „Ihr Upgrade mit SAMINA“ (noindex, 1:1-Akquise; `?von=philipp|daniel|mathias`) | `Projekte/LP_Hotels_v2/` (`build.py`) |
