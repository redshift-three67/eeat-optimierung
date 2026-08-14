---
id: pat-wp-menu-selector
updated: 2026-08-14
source: naturheilpraxis-eeat QW-MENU-METATRON
---

# WordPress-Menü: Parent statt Item

Playwright `locator('.menu-item').filter({ hasText: /Metatron/ })` trifft den **ersten Vorfahren**, der den Text irgendwo in Kindern enthält – oft den Top-Punkt („Rauch“).

**Tun:** Item über eindeutige ID (`#menu-item-NNNN`) oder exakten Title-Vergleich im `evaluate` auf `.menu-item-title` der **selben** `li`, nicht `hasText` auf dem Container.

**Nach jedem Menü-Save:** Frontend-Navbar ersten Punkt prüfen, nicht nur den Ziel-String irgendwo im HTML.
