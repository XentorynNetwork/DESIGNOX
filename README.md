# DESIGNOX

DesignoxWep

## Demos

| Ordner | Inhalt |
|---|---|
| `demos/cafe-goldjunge/` | Konzeptentwurf für Café Goldjunge, Köln (statische Seite, ohne Build-Schritt) |
| `demos/waxman-friseure/` | Konzeptentwurf für WAXMAN FRISEURE, Frankfurt (statische Seite, ohne Build-Schritt), live unter https://designox-waxman-friseure.vercel.app |

### Vor dem Livegang beim Kunden

Die Demo ist absichtlich als Entwurf markiert und nicht für Suchmaschinen freigegeben:

- `vercel.json` (Repo-Wurzel) und `demos/cafe-goldjunge/vercel.json` setzen `X-Robots-Tag: noindex, nofollow`, und `index.html` hat `<meta name="robots" content="noindex, nofollow">`. Für die echte Seite beides auf `index, follow` umstellen.
- Die `vercel.json` in der Repo-Wurzel leitet `/` je nach Domain um: `designox-waxman-friseure.vercel.app` auf `demos/waxman-friseure/`, alle anderen auf `demos/cafe-goldjunge/`. Sie greift nur, solange in Vercel kein Root Directory gesetzt ist. Mit Root Directory gilt die `vercel.json` im jeweiligen Demo-Ordner.
- Der Hinweisbalken `demo-note` steht in `index.html`, `impressum.html` und `datenschutz.html`. Für die echte Seite entfernen.
- Canonical, Open Graph, `robots.txt` und `sitemap.xml` zeigen auf die jeweilige `*.vercel.app`-Adresse. Durch die echte Domain ersetzen (bei WAXMAN: `https://www.waxman-friseure.de`, die Domain ist schon registriert).
- WAXMAN: Die Preise stammen von einem Foto der Preistafel im Salon und müssen vom Betrieb bestätigt werden.
- Impressum und Datenschutz enthalten gelb markierte Platzhalter, die der Betrieb ausfüllt.
