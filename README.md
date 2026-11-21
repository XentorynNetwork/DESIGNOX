# DESIGNOX

DesignoxWep

## Demos

| Ordner | Inhalt |
|---|---|
| `demos/waxman-friseure/` | Konzeptentwurf für WAXMAN FRISEURE, Frankfurt (statische Seite, ohne Build-Schritt), live unter https://designox-waxman-friseure.vercel.app |

### Vercel

Die `vercel.json` in der Repo-Wurzel leitet die Domain `designox-waxman-friseure.vercel.app` auf `demos/waxman-friseure/` um. Sie greift nur, solange im Vercel-Projekt kein Root Directory gesetzt ist. Mit Root Directory gilt die `vercel.json` im Demo-Ordner. Andere Domains bekommen keine Umleitung und zeigen 404.

### Vor dem Livegang beim Kunden

Die Demo ist absichtlich als Entwurf markiert und nicht für Suchmaschinen freigegeben:

- `vercel.json` (Repo-Wurzel und Demo-Ordner) setzt `X-Robots-Tag: noindex, nofollow`, und `index.html` hat `<meta name="robots" content="noindex, nofollow">`. Für die echte Seite beides auf `index, follow` umstellen.
- Der Hinweisbalken `demo-note` steht in `index.html`, `impressum.html` und `datenschutz.html`. Für die echte Seite entfernen.
- Canonical, Open Graph, `robots.txt` und `sitemap.xml` zeigen auf die `*.vercel.app`-Adresse. Durch `https://www.waxman-friseure.de` ersetzen (die Domain ist schon registriert).
- Die Preise stammen von einem Foto der Preistafel im Salon und müssen vom Betrieb bestätigt werden.
- Alle Fotos sind CC0-Platzhalter (Liste in `demos/waxman-friseure/img/CREDITS.md`) und zeigen nicht den Salon. Vor dem Livegang durch eigene Fotos des Betriebs ersetzen und den Satz „Alle Fotos sind Platzhalter“ entfernen.
- Impressum und Datenschutz enthalten gelb markierte Platzhalter, die der Betrieb ausfüllt.
