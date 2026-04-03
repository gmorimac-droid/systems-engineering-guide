# Baseline

## Scopo

Descrivere il concetto di baseline come stato formalmente approvato e controllato di un insieme di configuration items.

---

## Contesto

Nel Systems Engineering, una baseline rappresenta un punto di riferimento stabile del sistema o dei suoi artefatti.

Senza baseline definite, il progetto rischia di lavorare su versioni implicite o divergenti, con conseguenze su:

- integrazione
- verification
- audit
- gestione delle modifiche
- tracciabilità del lifecycle

---

## Definizione

Una baseline è una configurazione formalmente approvata di uno o più configuration items, utilizzata come riferimento per sviluppo, integrazione, verifica o change control.

La baseline stabilisce:

- quale versione è valida
- quali artefatti sono inclusi
- quale stato del sistema è approvato
- da quale riferimento devono partire le modifiche future

---

## Tipi tipici di baseline

### Requirements Baseline
Stabilizza il set di requisiti approvati.

### Architecture Baseline
Stabilizza la descrizione architetturale e le principali interfacce.

### Product / Build Baseline
Stabilizza una configurazione implementativa del sistema o di suoi componenti.

### Verification Baseline
Stabilizza gli artefatti di verifica rilevanti per una milestone.

---

## Esempio di baseline record

| Baseline ID | Nome | Contenuto principale | Data | Stato |
|-------------|------|----------------------|------|------|
| BL-001 | Requirements Baseline | Requirement Spec v1.0, RTM v1.0 | 2026-04-03 | Approved |
| BL-002 | Architecture Baseline | Architecture Description v1.0, ICD set v1.0 | 2026-05-15 | Approved |

---

## Obiettivi della baseline

La baseline serve a:

- congelare uno stato di riferimento
- consentire verifiche e review coerenti
- abilitare change control formale
- evitare divergenze tra team
- supportare auditabilità del sistema

---

## Attività del System Engineer

- contribuire a definire quando una baseline è pronta
- verificare che gli artefatti inclusi siano coerenti
- supportare la formalizzazione della baseline
- assicurare che RTM, architecture e verification artifacts siano allineati alla baseline corretta

---

## Errori comuni

- dichiarare una baseline senza maturità sufficiente
- non sapere quali CI sono inclusi
- usare la baseline come snapshot informale
- non collegare baseline e change control
- non aggiornare i riferimenti di verification alla baseline corretta

---

## Best practice

- definire criteri di readiness per ogni baseline
- registrare chiaramente contenuto, versione e stato
- usare le baseline come riferimento per review e test
- impedire modifiche informali agli elementi baselined
- collegare ogni baseline alle milestone del lifecycle

---

## Collegamenti

Questa pagina è collegata a:

- Configuration Items
- Change Control
- Configuration Audit
- Verification Matrix
- Integration Strategy