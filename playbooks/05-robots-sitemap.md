---
id: pb-robots-sitemap
updated: 2026-08-14
---

# robots.txt und Sitemap

1. Live-`robots.txt` **Header** prüfen: `last-modified` + `content-length` + langes `max-age` ⇒ oft **physische Datei**.  
2. Physische Root-`robots.txt` schlägt Rank Math und Robots-Editor. Dann Plesk/Dateisystem, nicht Plugin-Workaround.  
3. Sitemap-URL immer **https**.  
4. Rank Math Sitemap-Modul: `/sitemap_index.xml` verifizieren (kein 301 auf Home), **dann** robots-Zeile umstellen.  
5. Statische Generator-`sitemap.xml` (alte lastmod) nicht als kanonisch belassen, wenn RM-Index existiert.

Siehe `patterns/robots-physische-datei.md`.
