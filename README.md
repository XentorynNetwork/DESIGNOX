# DESIGNOX

DesignoxWep

## Demos

| Ordner | Inhalt |
|---|---|
| `demos/cafe-goldjunge/` | Konzeptentwurf für Café Goldjunge, Köln (statische Seite, ohne Build-Schritt) |

### Vor dem Livegang beim Kunden

Die Demo ist absichtlich als Entwurf markiert und nicht für Suchmaschinen freigegeben:

- `demos/cafe-goldjunge/vercel.json` setzt `X-Robots-Tag: noindex, nofollow`. Für die echte Seite diesen Header entfernen.
- Der Hinweisbalken `demo-note` steht in `index.html`, `impressum.html` und `datenschutz.html`. Für die echte Seite entfernen.
- Canonical, Open Graph, `robots.txt` und `sitemap.xml` zeigen auf `https://designox-cafe-goldjunge.vercel.app`. Durch die echte Domain ersetzen.
- Impressum und Datenschutz enthalten gelb markierte Platzhalter, die der Betrieb ausfüllt.
