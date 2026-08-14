---
id: pb-schema
updated: 2026-08-14
ymyl: true
---

# Schema (YMYL-Praxis)

**Ziel:** ein fachliches Praxisschema.  
**Bewährt:** HFCM-kontrolliertes `MedicalClinic` + `Physician`.  
**SEO-Technik:** Rank Math für Title, Meta, Sitemap – nicht als dritte Schema-Quelle.

Nacheinander, je Schritt Frontend-JSON-LD zählen:

1. Zusätzliche Schema-Plugins aus (`snip pro`, Schema & Structured Data).  
2. Rank Math Local-SEO-Modul aus, wenn es `LocalBusiness` / `HealthAndBeautyBusiness` neben MedicalClinic erzeugt.  
3. Ein Graph MedicalClinic+Physician muss Repo-Snippet entsprechen.

Nicht: Plugin aus **und** Rank Math an im selben Schritt.
