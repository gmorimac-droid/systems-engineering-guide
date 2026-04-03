# Tracciabilità dei requisiti (Requirements Traceability)

## Scopo

La tracciabilità dei requisiti consente di stabilire, mantenere e analizzare le relazioni tra:

- stakeholder needs
- requisiti
- elementi architetturali
- attività di verifica
- risultati di validazione

L’obiettivo è garantire che ogni requisito sia:

- giustificato
- implementato
- verificato
- mantenuto sotto controllo lungo tutto il lifecycle

---

## Contesto

Nel Systems Engineering, la tracciabilità è un meccanismo fondamentale per:

- controllare la complessità
- supportare audit e certificazioni
- gestire modifiche (change management)
- garantire copertura completa del sistema

La tracciabilità è tipicamente realizzata tramite una **Requirements Traceability Matrix (RTM)**.

---

## Concetti chiave

### Tracciabilità

Capacità di seguire un elemento lungo il lifecycle del sistema.

---

### Tipi di tracciabilità

#### Backward Traceability
Collega un requisito alla sua origine.

## Collegamento con i requisiti

La tracciabilità si basa sugli ID definiti in:
- Requirements Specification

Esempio:
REQ-001 → NEED-001 → ARCH-01 → TC-001

Serve a rispondere alla domanda:
> Perché questo requisito esiste?

---

#### Forward Traceability
Collega un requisito alla sua implementazione e verifica.

REQ → ARCH → TEST


Serve a rispondere alla domanda:
> Questo requisito è stato implementato e verificato?

---

#### Bidirectional Traceability

Combinazione di backward e forward traceability.

Consente di navigare in entrambe le direzioni.

---

### Copertura

La copertura misura quanto i requisiti sono:

- implementati
- verificati
- validati

Un sistema corretto deve garantire:

- 100% forward traceability
- 100% backward traceability

---

## Requirements Traceability Matrix (RTM)

La RTM è lo strumento principale per rappresentare la tracciabilità.

---

## Struttura della RTM

Una RTM professionale include tipicamente:

- Requirement ID
- Source (Need)
- Derived From (opzionale)
- Architecture Element
- Verification Method
- Test Case
- Status

---

## Esempio di RTM

| Requirement ID | Source (Need) | Architecture Element | Verification Method | Test Case | Status |
|----------------|--------------|---------------------|---------------------|-----------|--------|
| REQ-001 | NEED-001 | ARCH-COMP-01 | Test | TC-001 | Planned |
| REQ-002 | NEED-002 | ARCH-COMP-02 | Analysis | TC-002 | Implemented |
| REQ-003 | NEED-001 | ARCH-COMP-03 | Inspection | TC-003 | Verified |

---

## Descrizione dei campi

### Requirement ID
Identificatore univoco del requisito.

---

### Source (Need)
Bisogno da cui deriva il requisito.

---

### Architecture Element
Elemento del sistema che implementa il requisito.

---

### Verification Method

Metodo utilizzato per verificare il requisito:

- Test
- Analysis
- Inspection
- Demonstration

---

### Test Case
Caso di test associato al requisito.

---

### Status

Stato del requisito nel lifecycle:

- Draft
- Approved
- Implemented
- Verified
- Validated

---

## Attività del System Engineer

Il System Engineer è responsabile di:

- definire la struttura della tracciabilità
- mantenere la RTM aggiornata
- garantire copertura completa
- identificare gap (requisiti senza test o senza implementazione)
- supportare impact analysis
- gestire modifiche e propagazione degli effetti

---

## Input

- stakeholder needs
- requirement specification
- architecture description
- verification & validation plan

---

## Output

- RTM aggiornata
- evidenza di copertura
- supporto alla verifica e validazione
- supporto alle decisioni tecniche

---

## Artefatti correlati

- Requirements Specification
- Architecture Description
- Interface Control Document (ICD)
- Verification Matrix
- Test Plan
- Risk Register
- Change Log

---

## Errori comuni

### 1. Tracciabilità incompleta
Requisiti senza collegamenti.

### 2. Requisiti senza verifica
Assenza di test associati.

### 3. Architettura non tracciata
Elementi non collegati ai requisiti.

### 4. RTM statica
Non aggiornata dopo modifiche.

### 5. Collegamenti manuali non controllati
Rischio di inconsistenza.

---

## Best practice

- usare identificativi univoci (REQ-001, NEED-001, TC-001)
- mantenere la RTM aggiornata continuamente
- verificare la copertura a ogni milestone
- integrare RTM con tool (es. DOORS, Jama)
- automatizzare dove possibile
- collegare ogni requisito a:
  - una fonte
  - un elemento architetturale
  - un metodo di verifica

---

## Checklist operativa

Un sistema è correttamente tracciato se:

- [ ] ogni requisito ha un NEED associato
- [ ] ogni requisito è implementato in architettura
- [ ] ogni requisito ha un metodo di verifica
- [ ] ogni requisito ha almeno un test case
- [ ] ogni test è collegato a un requisito
- [ ] non esistono requisiti orfani
- [ ] non esistono test senza requisito

---

## Impatto sul lifecycle

La tracciabilità è trasversale a tutto il lifecycle:

- nelle fasi iniziali → collega needs e requisiti
- nella progettazione → collega requisiti e architettura
- nell’integrazione → supporta verifica
- nella validazione → collega sistema e bisogni reali
- nel change management → abilita impact analysis

---

## Collegamenti

Questa sezione è strettamente collegata a:

- Requirements Engineering
- System Architecture
- Verification & Validation
- Configuration Management
- Risk Management

La tracciabilità è il meccanismo che tiene insieme tutte queste discipline.