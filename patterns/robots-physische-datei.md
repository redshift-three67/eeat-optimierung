---
id: pat-robots-file
updated: 2026-08-14
source: naturheilpraxis-eeat QW-SITEMAP
---

# Physische robots.txt im Root

**Erkennung:** Response mit `last-modified`, `content-length`, oft `max-age` sehr groß, `accept-ranges` – typisch nginx-Datei, nicht WP-virtual.

**Folge:** Rank Math: „Inhalt gesperrt, weil sich im Stammordner eine robots.txt-Datei befindet.“ Plugin-Textarea speichert Options, ändert Live nicht.

**Tun:** Datei in Plesk/Document-Root ändern oder löschen, dann WP/Rank Math. Sitemap-Zeile `https://…/sitemap_index.xml` wenn Rank Math Sitemap an ist.

**Nicht:** die Option speichern und annehmen, Live sei geändert.
