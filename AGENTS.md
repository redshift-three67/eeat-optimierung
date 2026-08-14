---
purpose: LLM/agent entrypoint
updated: 2026-08-14
---

# Agenten-Regeln für eeat-optimierung

## Laden

1. Diese Datei  
2. Das Playbook, das der Auftrag trifft (`playbooks/`)  
3. Zugehörige `decisions/` nur bei Zielkonflikt  
4. `cases/<projekt>.md` nur wenn an **dieser** Domain gearbeitet wird  

Nicht das ganze Repo in den Kontext ziehen.

## Harte Grenzen

- Keine Passwörter, App-Passwords, CDP-Sessions aus Chats übernehmen.  
- Projekt-Live-Status steht im **Projekt-Repo**, nicht hier.  
- Ein logischer Live-Schritt. Prewrite → Write → Verify → Archiv oder Rollback.  
- YMYL: keine Heilversprechen, keine irreführenden Titel/Anker.  
- CDP-Port nie mit einer anderen lokalen Chrome-Session teilen.  

## Bekannte Fallen (nicht wiederholen)

| Falle | Datei |
|-------|--------|
| Drei Schema-Plugins parallel | `decisions/001-ein-schema-system.md` |
| YOOtheme-Builder per CDP (leere Slider-Folie) | `patterns/yootheme-cdp-risiko.md` |
| Physische Root-`robots.txt` schlägt Plugin-Editor | `patterns/robots-physische-datei.md` |
| Playwright `hasText` trifft Parent-Menüpunkt | `patterns/wp-menu-selektor.md` |

## Writes

Live-Site: nur im Domain-Repo dokumentieren und pushen.  
Dieses Repo: nur Leitfaden-Dateien, keine Secrets.
