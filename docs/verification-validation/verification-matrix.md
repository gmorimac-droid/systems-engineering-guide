# Verification Matrix

## Scopo

La Verification Matrix definisce come ogni requisito del sistema viene verificato, specificando:

- metodo di verifica
- livello di test
- test case associati
- criteri di accettazione

L’obiettivo è garantire che tutti i requisiti siano:

- verificabili
- verificati in modo coerente
- coperti da attività di test o analisi

---

## Contesto

La Verification Matrix è strettamente collegata a:

- Requirements Specification
- Requirements Traceability Matrix (RTM)
- Test Plan

Nel lifecycle, rappresenta il collegamento operativo tra:

REQ → verifica → evidenza


---

## Concetti chiave

### Verification

La verification risponde alla domanda:

> Il sistema è stato costruito correttamente rispetto ai requisiti?

---

### Metodi di verifica

I metodi standard sono:

- **Test** → esecuzione su sistema reale o simulato  
- **Analysis** → calcoli, simulazioni, modelli  
- **Inspection** → revisione documentale o visiva  
- **Demonstration** → dimostrazione operativa  

---

### Livelli di verifica

- Unit / Component
- Subsystem
- System
- Acceptance

---

## Struttura della Verification Matrix

Una Verification Matrix professionale include:

- Requirement ID
- Requirement Description
- Verification Method
- Verification Level
- Test Case ID
- Acceptance Criteria
- Status

---

## Verification Matrix (Esempio)

| Requirement ID | Requirement Description | Method | Level | Test Case | Acceptance Criteria | Status |
|----------------|------------------------|--------|-------|-----------|---------------------|--------|
| REQ-001 | Tempo risposta ≤ 200 ms (95%) | Test | System | TC-001 | ≤ 200 ms nel 95% dei casi | Planned |
| REQ-002 | Supporto ≥ 1000 utenti | Test/Analysis | System | TC-002 | ≥ 1000 utenti simultanei | Planned |
| REQ-003 | Disponibilità 99.9% | Analysis | System | TC-003 | ≥ 99.9% uptime mensile | Planned |

---

## Descrizione dei campi

### Requirement ID
Identificatore univoco del requisito.

---

### Requirement Description
Descrizione sintetica del requisito.

---

### Verification Method
Metodo utilizzato per verificare il requisito.

---

### Verification Level
Livello a cui viene eseguita la verifica.

---

### Test Case
Identificatore del test associato.

---

### Acceptance Criteria
Condizione che determina il successo della verifica.

---

### Status

Stato della verifica:

- Planned
- In Progress
- Passed
- Failed

---

## Attività del System Engineer

Il System Engineer è responsabile di:

- definire la strategia di verifica
- assicurare che ogni requisito sia verificabile
- assegnare metodi di verifica appropriati
- garantire copertura completa
- coordinare con test team
- analizzare risultati di verifica

---

## Input

- Requirements Specification
- RTM
- Architecture Description
- Test Plan

---

## Output

- Verification Matrix
- Test coverage
- Verification evidence
- Supporto alla validazione

---

## Artefatti correlati

- Requirements Specification
- Traceability Matrix (RTM)
- Test Plan
- Test Cases
- Test Reports

---

## Errori comuni

### 1. Requisiti senza metodo di verifica

### 2. Test non collegati ai requisiti

### 3. Acceptance criteria non definiti

### 4. Verifica pianificata troppo tardi

### 5. Confondere verification e validation

---

## Best practice

- definire il metodo di verifica durante la scrittura dei requisiti
- usare criteri misurabili
- mantenere collegamento con RTM
- garantire copertura completa (100%)
- aggiornare lo stato continuamente
- separare chiaramente test levels

---

## Checklist operativa

- [ ] ogni requisito ha un metodo di verifica
- [ ] ogni requisito ha un test case
- [ ] ogni test ha acceptance criteria
- [ ] esiste copertura completa
- [ ] i livelli di test sono definiti
- [ ] lo stato è aggiornato

---

## Collegamenti

Questa sezione è collegata a:

- Requirements Engineering
- Requirements Traceability Matrix
- System Architecture
- Test Plan
- Validation

La Verification Matrix è il passo che trasforma i requisiti in evidenza oggettiva.