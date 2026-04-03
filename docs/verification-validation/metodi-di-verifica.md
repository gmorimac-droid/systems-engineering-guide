# Metodi di verifica

## Scopo

Descrivere i principali metodi di verifica utilizzati nel Systems Engineering per dimostrare la soddisfazione dei requisiti.

---

## Contesto

Ogni requisito deve essere associato a uno o più metodi di verifica appropriati.

La scelta del metodo dipende da:

- natura del requisito
- livello di sistema
- disponibilità di evidenze
- fattibilità tecnica della verifica
- costo e rischio della verifica stessa

---

## Metodi principali

Nel Systems Engineering i metodi di verifica più comuni sono:

- Test
- Analysis
- Inspection
- Demonstration

---

## Test

Il test verifica un requisito attraverso esecuzione controllata del sistema o di una sua parte.

È particolarmente adatto per requisiti relativi a:

- funzionalità
- performance
- interfacce
- comportamento osservabile

### Esempio
`REQ-001 Tempo di risposta ≤ 200 ms`

Metodo:
- esecuzione di test sotto carico controllato

---

## Analysis

L’analysis verifica un requisito attraverso calcoli, simulazioni, modelli, valutazioni ingegneristiche o elaborazioni di dati.

È adatta per requisiti come:

- affidabilità
- disponibilità
- capacità teorica
- margini prestazionali
- safety-related evaluations

### Esempio
`REQ-003 Disponibilità ≥ 99.9% mensile`

Metodo:
- analisi di architettura e modelli di availability

---

## Inspection

L’inspection verifica un requisito mediante esame visivo, review documentale, controllo di configurazione o verifica di conformità statica.

È adatta per requisiti relativi a:

- documentazione
- marcature
- configurazioni
- conformità formale
- caratteristiche osservabili senza esecuzione dinamica

### Esempio
verifica di presenza corretta di etichettature o elementi documentali richiesti

---

## Demonstration

La demonstration verifica un requisito mostrando il comportamento del sistema in una situazione rappresentativa, senza la formalità o la strumentazione completa di un test rigoroso.

È utile per:

- capacità operative
- interazioni utente-sistema
- funzioni osservabili in contesto realistico

### Esempio
dimostrazione di una sequenza operativa completa davanti allo stakeholder

---

## Selezione del metodo di verifica

La scelta del metodo deve considerare:

- oggettività richiesta
- disponibilità di misure
- criticità del requisito
- costo della verifica
- livello del sistema
- vincoli ambientali e di safety

In molti casi un requisito può richiedere più di un metodo.

---

## Esempio di assegnazione

| Requirement ID | Requirement Description | Verification Method |
|----------------|-------------------------|---------------------|
| REQ-001 | Tempo risposta ≤ 200 ms | Test |
| REQ-002 | Supporto ≥ 1000 utenti simultanei | Test + Analysis |
| REQ-003 | Disponibilità ≥ 99.9% | Analysis |
| REQ-004 | Presenza etichettatura conforme | Inspection |

---

## Attività del System Engineer

- assicurare che ogni requisito abbia un metodo di verifica appropriato
- valutare se il metodo scelto è sufficiente e proporzionato
- mantenere coerenza tra requisito, metodo e acceptance criteria
- supportare il collegamento tra metodo di verifica e verification matrix

---

## Errori comuni

- lasciare requisiti senza metodo di verifica
- scegliere un metodo non adatto alla natura del requisito
- usare demonstration dove serve test rigoroso
- non definire evidenza oggettiva sufficiente
- scegliere il metodo per comodità invece che per adeguatezza

---

## Best practice

- selezionare il metodo durante la definizione del requisito
- usare metodi combinati quando necessario
- definire criteri di accettazione coerenti con il metodo scelto
- mantenere tracciabilità tra requisito, metodo e test case
- documentare chiaramente le evidenze prodotte

---

## Collegamenti

Questa pagina è collegata a:

- Requirements Engineering
- Verification Matrix
- Test Levels
- V-Model