# DESIGNOX

DesignoxWep

## Demos

| Ordner | Inhalt |
|---|---|
| `demos/cafe-goldjunge/` | Konzeptentwurf für Café Goldjunge, Köln (statische Seite, ohne Build-Schritt) |

### Vor dem Livegang beim Kunden

Die Demo ist absichtlich als Entwurf markiert und nicht für Suchmaschinen freigegeben:

- `vercel.json` (Repo-Wurzel) und `demos/cafe-goldjunge/vercel.json` setzen `X-Robots-Tag: noindex, nofollow`, und `index.html` hat `<meta name="robots" content="noindex, nofollow">`. Für die echte Seite beides auf `index, follow` umstellen.
- Die `vercel.json` in der Repo-Wurzel leitet `/` auf `demos/cafe-goldjunge/` um. Sie greift, solange in Vercel kein Root Directory gesetzt ist.
- Der Hinweisbalken `demo-note` steht in `index.html`, `impressum.html` und `datenschutz.html`. Für die echte Seite entfernen.
- Canonical, Open Graph, `robots.txt` und `sitemap.xml` zeigen auf `https://designox-cafe-goldjunge.vercel.app`. Durch die echte Domain ersetzen.
- Impressum und Datenschutz enthalten gelb markierte Platzhalter, die der Betrieb ausfüllt.
