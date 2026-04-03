# Requirements Traceability Matrix (RTM)

## Scopo

La Requirements Traceability Matrix (RTM) consente di stabilire e mantenere collegamenti tra:

- stakeholder needs
- requisiti
- architettura
- test e verifica
- validazione

La RTM è uno strumento fondamentale per garantire:

- completezza
- coerenza
- verificabilità
- controllo delle modifiche

---

## Contesto

Nel Systems Engineering, ogni requisito deve essere:

- giustificato (derivato da un need)
- implementato (architettura)
- verificato (test)
- validato (bisogno reale)

La RTM rende espliciti questi collegamenti.

---

## Concetti chiave

### Tracciabilità

Capacità di seguire un elemento lungo il lifecycle:

- backward (verso il bisogno)
- forward (verso implementazione e test)

---

### Tipi di tracciabilità

#### Backward traceability
Requisito → Need

#### Forward traceability
Requisito → Architettura → Test

#### Bidirectional traceability
Combinazione delle due

---

## Struttura della RTM

Una RTM tipica include:

- ID requisito
- fonte (need)
- elemento architetturale
- metodo di verifica
- test case
- stato

---

## Esempio di RTM

| Requirement ID | Source (Need) | Architecture Element | Verification Method | Test Case | Status |
|----------------|--------------|---------------------|---------------------|-----------|--------|
| REQ-001 | NEED-001 | ARCH-COMP-01 | Test | TC-001 | Planned |
| REQ-002 | NEED-002 | ARCH-COMP-02 | Analysis | TC-002 | Planned |

---

## Descrizione dei campi

### Requirement ID
Identificatore univoco del requisito.

### Source (Need)
Bisogno da cui deriva il requisito.

### Architecture Element
Elemento del sistema che implementa il requisito.

### Verification Method
Metodo utilizzato per verificare il requisito:

- Test
- Analysis
- Inspection
- Demonstration

### Test Case
Caso di test associato.

### Status
Stato del requisito:

- Planned
- Implemented
- Verified
- Validated

---

## Attività del System Engineer

- definire la struttura della RTM
- mantenere aggiornati i collegamenti
- verificare copertura completa
- analizzare impatti dei cambiamenti
- identificare gap o duplicazioni

---

## Input

- stakeholder needs
- requirement set
- architecture
- test plan

---

## Output

- RTM aggiornata
- evidenza di copertura
- supporto alla verifica e validazione

---

## Artefatti

- RTM
- requirement specification
- architecture description
- test documentation

---

## Errori comuni

- RTM incompleta
- collegamenti mancanti
- requisiti senza test
- architettura non tracciata
- RTM non aggiornata

---

## Best practice

- mantenere la RTM viva
- aggiornare ad ogni modifica
- garantire copertura 100%
- usare identificativi univoci
- integrare RTM con tool (es. DOORS, Jama)

---

## Checklist

- [ ] ogni requisito ha una fonte
- [ ] ogni requisito è collegato a un elemento architetturale
- [ ] ogni requisito ha un metodo di verifica
- [ ] ogni requisito ha almeno un test
- [ ] nessun requisito è isolato

---

## Collegamenti

Questa sezione è collegata a:

- Requirements Engineering
- System Architecture
- Verification & Validation
- Configuration Management