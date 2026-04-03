# Ruoli e artefatti nel lifecycle

## Scopo

Descrivere come ruoli, responsabilità e artefatti si distribuiscono lungo il ciclo di vita del sistema.

---

## Contesto

Nel Systems Engineering, il lifecycle non è solo una sequenza di fasi, ma anche una struttura di responsabilità.

Ogni fase coinvolge:

- ruoli specifici
- artefatti specifici
- decisioni specifiche

Il valore del lifecycle dipende anche dalla chiarezza con cui queste relazioni vengono definite.

---

## Principio generale

Per ogni fase occorre sapere:

- chi è responsabile
- quali artefatti produce o aggiorna
- come questi artefatti vengono usati nella fase successiva

---

## Mappa semplificata ruoli / artefatti

| Fase | Ruoli principali | Artefatti principali |
|------|------------------|----------------------|
| Concept | System Engineer, Stakeholder, Project Lead | Need list, concept description, operational scenarios |
| Requirements | System Engineer, Domain Experts | Requirement specification, RTM |
| Architecture | System Engineer, Architect, Domain Teams | Architecture description, allocation tables, ICD |
| Integration | Integration Team, System Engineer | Integration plan, anomaly reports |
| Verification | Test Team, System Engineer | Verification matrix, test reports |
| Validation | User Representatives, System Engineer | Validation evidence, acceptance records |
| Operation & Maintenance | Operations, Maintenance, System Engineer | Support plan, maintenance records, lessons learned |

---

## Ruolo del System Engineer

Il System Engineer è una figura trasversale che collega le fasi del lifecycle.

Le sue responsabilità tipiche includono:

- mantenere coerenza tra artefatti
- garantire tracciabilità
- supportare decisioni tra discipline
- assicurare continuità tra definizione, integrazione e verifica
- facilitare il collegamento tra bisogni iniziali e sistema finale

---

## Ruolo degli altri attori

### Stakeholder / Customer
Forniscono bisogni, vincoli, aspettative e criteri di accettazione.

### Architect
Definisce la struttura della soluzione e supporta allocazione e coerenza tecnica.

### Domain Teams
Realizzano e dettagliano elementi specialistici del sistema.

### Integration Team
Gestisce la convergenza degli elementi del sistema.

### Test / Verification Team
Produce evidenza oggettiva di conformità ai requisiti.

### Operations / Maintenance
Assicura utilizzo sostenibile del sistema e ritorno di esperienza verso il progetto.

---

## Catena degli artefatti

Una catena tipica è:

```text
Needs → Requirements → Architecture → Integration → Verification → Validation → Operations Feedback