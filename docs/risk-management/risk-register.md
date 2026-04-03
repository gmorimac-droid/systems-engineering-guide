# Risk Register

## Scopo

Descrivere il Risk Register come artefatto principale per registrare, monitorare e governare i rischi del sistema e del progetto lungo il lifecycle.

---

## Contesto

Il Risk Register è lo strumento operativo che rende il rischio:

- visibile
- tracciabile
- aggiornabile
- discutibile in review e decisioni

Non è un archivio statico, ma un artefatto vivo che supporta governance, mitigazione e priorità.

---

## Obiettivo del Risk Register

Il Risk Register serve a:

- centralizzare i rischi identificati
- registrarne valutazione e owner
- monitorare azioni di mitigazione
- evidenziare il rischio residuo
- supportare review tecniche e di progetto

---

## Struttura tipica

Un Risk Register professionale include tipicamente:

- Risk ID
- titolo / descrizione del rischio
- causa
- effetto / impatto
- probabilità
- impatto
- priorità
- owner
- mitigation action
- status
- rischio residuo

---

## Esempio di Risk Register

| Risk ID | Descrizione | Probabilità | Impatto | Priorità | Owner | Mitigation | Status | Residual Risk |
|---------|-------------|-------------|---------|----------|-------|------------|--------|---------------|
| RSK-001 | IF-003 non stabilizzata prima dell’integrazione | Alta | Alto | Critico | Integration Lead | ICD review + early interface test | Open | Medio |
| RSK-002 | Ambiente di system test non disponibile in tempo | Media | Medio | Medio | Test Manager | Preparazione ambiente anticipata | In Progress | Basso |
| RSK-003 | Needs operativi incompleti | Media | Alto | Alto | System Engineer | Workshop con stakeholder | Open | Medio |

---

## Campi principali

### Risk ID
Identificatore univoco del rischio.

### Descrizione
Formula chiara del rischio, con causa ed effetto comprensibili.

### Probabilità / Impatto / Priorità
Valutazione del rischio.

### Owner
Responsabile del monitoraggio e del follow-up.

### Mitigation
Azione o piano per ridurre il rischio.

### Status
Stato corrente del rischio:
- Open
- Monitoring
- Mitigated
- Closed
- Accepted

### Residual Risk
Rischio che rimane dopo la mitigazione.

---

## Attività del System Engineer

- contribuire alla popolazione del risk register
- assicurare che i rischi tecnici siano ben descritti
- collegare i rischi agli elementi del sistema
- supportare la revisione periodica del registro
- usare il register per orientare decisioni e priorità di verification / integration

---

## Governance del Risk Register

Il register deve essere:

- rivisto periodicamente
- aggiornato dopo change rilevanti
- allineato a milestone e review
- leggibile sia dai tecnici sia dai decision-maker

---

## Errori comuni

- trattare il register come adempimento formale
- non aggiornare gli status
- chiudere i rischi senza evidenza
- non distinguere rischio attivo da rischio residuo
- usare descrizioni troppo vaghe

---

## Best practice

- mantenere il register semplice ma rigoroso
- assegnare ownership chiara
- riesaminare i rischi nelle review principali
- usare il register come base per decisioni e trade-off
- collegare il register a mitigazioni reali e misurabili

---

## Collegamenti

Questa pagina è collegata a:

- Identificazione dei rischi
- Analisi probabilità / impatto
- Mitigation Planning
- Architectural Trade-offs
- Integration Strategy
- Verification Planning

Il Risk Register è la vista operativa e governabile del rischio lungo il lifecycle.