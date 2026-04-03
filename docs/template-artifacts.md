# Template & Artifacts

## Scopo

Questa sezione raccoglie i principali artefatti utilizzati nel Systems Engineering e propone una struttura minima riutilizzabile per ciascuno.

L’obiettivo non è fornire modelli rigidi validi in ogni progetto, ma offrire una base coerente per costruire artefatti:

- chiari
- tracciabili
- governabili
- coerenti con il lifecycle

---

## Contesto

Nel Systems Engineering, gli artefatti non sono semplici documenti amministrativi.

Sono strumenti che servono a:

- strutturare il pensiero
- prendere decisioni
- mantenere tracciabilità
- supportare integrazione e verification
- governare il sistema nel tempo

La qualità del sistema dipende anche dalla qualità e coerenza dei suoi artefatti.

---

## Principi guida

Un buon artefatto dovrebbe essere:

- chiaro nel suo scopo
- collocato nel lifecycle corretto
- collegato agli altri artefatti rilevanti
- versionabile e auditabile
- mantenuto vivo nel tempo
- proporzionato al contesto del progetto

---

## Struttura della sezione

Questa pagina presenta template concettuali per i principali artefatti di sistema:

- Need Statement
- Requirement Specification
- Requirements Traceability Matrix
- Architecture Description
- Interface Control Document
- Verification Matrix
- Risk Register
- Change Request

---

# 1. Need Statement Template

## Scopo

Descrivere un bisogno o obiettivo di alto livello espresso da uno stakeholder.

## Quando si usa

Nelle prime fasi del lifecycle, durante stakeholder analysis e needs analysis.

## Struttura minima

- Need ID
- Stakeholder / Source
- Need Statement
- Contesto operativo
- Priorità
- Note / razionale

## Esempio

| Campo | Valore |
|------|--------|
| Need ID | NEED-001 |
| Stakeholder | Operatore |
| Need Statement | Il sistema deve supportare decisioni rapide durante la missione |
| Contesto operativo | Operazione ad alta intensità |
| Priorità | Alta |

---

# 2. Requirement Specification Template

## Scopo

Definire requisiti chiari, verificabili e tracciabili derivati dai needs o da vincoli di sistema.

## Quando si usa

Dalla fase di requirements definition e per tutto il lifecycle come artefatto di riferimento.

## Struttura minima

- Requirement ID
- Requirement Statement
- Tipo
- Fonte / Need
- Verification Method
- Status
- Note / rationale

## Esempio

| Campo | Valore |
|------|--------|
| Requirement ID | REQ-001 |
| Requirement Statement | Il sistema deve elaborare una richiesta entro 200 ms nel 95% dei casi |
| Tipo | Performance |
| Fonte | NEED-001 |
| Verification Method | Test |
| Status | Approved |

---

# 3. Requirements Traceability Matrix (RTM) Template

## Scopo

Collegare needs, requisiti, architettura e verification.

## Quando si usa

Dalla baseline dei requisiti in avanti, e va mantenuta lungo tutto il lifecycle.

## Struttura minima

- Need ID
- Requirement ID
- Architecture Element
- Verification Method
- Test Case ID
- Status

## Esempio

| Need ID | Requirement ID | Architecture Element | Verification Method | Test Case ID | Status |
|---------|----------------|----------------------|---------------------|--------------|--------|
| NEED-001 | REQ-001 | ARCH-COMP-01 | Test | TC-001 | Planned |

---

# 4. Architecture Description Template

## Scopo

Descrivere la struttura del sistema, i suoi elementi, le relazioni e le principali scelte architetturali.

## Quando si usa

Durante architecture and design e come riferimento per integration e verification.

## Struttura minima

- Architecture ID / Version
- Scope del sistema
- Vista funzionale
- Vista fisica
- Elementi principali
- Interfacce principali
- Allocation dei requisiti
- Decision rationale

## Esempio di sezioni

- Scopo
- Contesto
- Functional Architecture
- Physical Architecture
- Interfaces
- Allocation
- Trade-offs
- Baseline / Versione

---

# 5. Interface Control Document (ICD) Template

## Scopo

Definire in modo controllato una o più interfacce del sistema.

## Quando si usa

Durante architecture, integration e verification delle interfacce.

## Struttura minima

- Interface ID
- Source Element
- Target Element
- Tipo di interfaccia
- Descrizione
- Dati / segnali / formato
- Vincoli temporali
- Ownership
- Versione
- Verification reference

## Esempio

| Campo | Valore |
|------|--------|
| Interface ID | IF-001 |
| Source Element | ARCH-COMP-01 |
| Target Element | ARCH-COMP-02 |
| Tipo | Logica |
| Descrizione | Trasferimento richiesta validata |
| Ownership | Integration Lead |
| Verification reference | IF-TC-001 |

---

# 6. Verification Matrix Template

## Scopo

Definire come ciascun requisito viene verificato.

## Quando si usa

Durante verification planning, integration e verification execution.

## Struttura minima

- Requirement ID
- Requirement Description
- Architecture Element
- Verification Method
- Verification Level
- Test Case ID
- Acceptance Criteria
- Status

## Esempio

| Requirement ID | Verification Method | Level | Test Case ID | Acceptance Criteria | Status |
|----------------|---------------------|-------|--------------|---------------------|--------|
| REQ-001 | Test | System | TC-001 | ≤ 200 ms nel 95% dei casi | Planned |

---

# 7. Risk Register Template

## Scopo

Registrare, valutare e monitorare i rischi tecnici, operativi o di progetto.

## Quando si usa

Per tutto il lifecycle, con particolare intensità in fasi di architecture, integration, change e verification.

## Struttura minima

- Risk ID
- Descrizione
- Probabilità
- Impatto
- Priorità
- Owner
- Mitigation
- Status
- Residual Risk

## Esempio

| Risk ID | Descrizione | Probabilità | Impatto | Owner | Mitigation | Status |
|---------|-------------|-------------|---------|-------|------------|--------|
| RSK-001 | Interfaccia IF-003 non stabilizzata | Alta | Alto | Integration Lead | Early interface test | Open |

---

# 8. Change Request Template

## Scopo

Formalizzare una modifica proposta e valutarne l’impatto sul sistema e sugli artefatti collegati.

## Quando si usa

Ogni volta che una modifica significativa coinvolge requisiti, architettura, interfacce, verification, baseline o operation.

## Struttura minima

- Change ID
- Titolo
- Descrizione della modifica
- Motivazione
- Elementi impattati
- Impact analysis
- Decisione
- Owner
- Stato
- Verification della change

## Esempio

| Campo | Valore |
|------|--------|
| Change ID | CR-001 |
| Titolo | Riduzione tempo di risposta |
| Descrizione | REQ-001 cambia da 200 ms a 150 ms |
| Elementi impattati | Requirements, Architecture, Verification Matrix |
| Decisione | Approved |
| Stato | In Progress |

---

## Collegamenti tra artefatti

Gli artefatti non devono essere letti in isolamento.  
Una catena tipica è:

```text
Need → Requirement → Architecture → Interface → Verification → Evidence → Change