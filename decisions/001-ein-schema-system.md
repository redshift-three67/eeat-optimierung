---
id: adr-001
updated: 2026-08-14
source: naturheilpraxis-eeat SCHEMA-01…04
---

# Ein fachliches Schema-System

**Entscheidung:** HFCM `MedicalClinic`+`Physician` behalten. Rank Math für Meta/Titles/Sitemap. `snip pro` und „Schema & Structured Data“ aus. Rank Math Local SEO aus, wenn es `HealthAndBeautyBusiness`/`LocalBusiness` daneben legt.

**Warum:** Drei JSON-LD-Quellen erzeugen Duplikate und widersprüchliche Typen (Beauty-Business vs. Heilpraktiker-Praxis). Nach dem Abschalten fiel Home von 7 auf 1 fachlichen Graph plus kontrollierten RM-Rest.

**Nicht:** alle drei gleichzeitig „optimieren“. Immer ein Plugin/Modul pro Schritt, JSON-LD zählen.
