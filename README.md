# eeat-optimierung

Wiederverwendbare Knowledge-Basis für **E-E-A-T / YMYL / WordPress-SEO** über mehrere Projekte hinweg.

## Zwei Schichten (nicht vermischen)

| Schicht | Repo | Inhalt |
|---------|------|--------|
| Live-Wahrheit einer Domain | z. B. `naturheilpraxis-eeat` | Handoff, CURRENT, Archive, Snippets **dieser** Site |
| Leitfaden / LLM-Wissen | **dieses Repo** | Regeln, Entscheidungen, Checklisten, Fehlermuster |

Dieses Repo ist **kein** Live-Status. Es zitiert Fälle, kopiert sie nicht.

## Für Menschen

1. `playbooks/` in der Reihenfolge der Arbeit lesen  
2. `decisions/` wenn ein Zielkonflikt entsteht  
3. `cases/` nur als Lektion + Link zum Projekt-Repo  

## Für LLMs / Agenten

Zuerst `AGENTS.md` laden. Dann nur die Playbooks, die der Auftrag triggert. Nie Secrets. Nie Projekt-CURRENT hierher schreiben.

## Projekte (Stand 2026-08-14)

| Case | Domain | Live-Repo |
|------|--------|-----------|
| [rauch-heilpraktiker](cases/rauch-heilpraktiker.md) | rauch-heilpraktiker.de | https://github.com/redshift-three67/naturheilpraxis-eeat |
| [sunclinic](cases/sunclinic.md) | (separates Repo) | https://github.com/redshift-three67/sunclinic-eeat (nur lesend als Muster) |

## Direktive

Änderungen an einer Live-Site: immer im **Projekt-Repo** + Workflow dort.  
Änderungen an Regeln/Checklisten: hier, mit Datum und Quelle.
