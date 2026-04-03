# Change Control

## Scopo

Descrivere come gestire le modifiche ai configuration items in modo controllato, tracciabile e coerente con l’integrità del sistema.

---

## Contesto

In un progetto di Systems Engineering, i cambiamenti sono inevitabili.

Possono derivare da:

- nuovi bisogni
- difetti nei requisiti
- problemi architetturali
- anomalie di integrazione
- esiti di verification
- vincoli esterni o normativi

Senza change control, anche modifiche apparentemente piccole possono introdurre incoerenza, regressioni o perdita di tracciabilità.

---

## Definizione

Il change control è il processo formale con cui una modifica proposta viene:

- registrata
- valutata
- approvata o rifiutata
- implementata
- tracciata

---

## Obiettivi del change control

Il processo serve a:

- evitare modifiche non controllate
- valutare impatti tecnici e sistemici
- preservare la coerenza delle baseline
- assicurare aggiornamento di artefatti collegati
- rendere la decisione auditabile

---

## Change Request

Ogni modifica significativa dovrebbe essere formalizzata tramite una Change Request (CR).

Esempio:

`CR-001 modifica REQ-001: tempo di risposta da 200 ms a 150 ms`

Una change request professionale include tipicamente:

- Change ID
- descrizione
- motivazione
- elementi impattati
- impatto atteso
- owner
- decisione
- stato

---

## Processo di change control

1. registrazione della change request
2. analisi di impatto
3. review tecnica / decisione
4. approvazione, rifiuto o defer
5. implementazione della modifica
6. aggiornamento degli artefatti correlati
7. verifica della modifica

---

## Impact Analysis

Ogni change deve essere valutato rispetto a possibili impatti su:

- requisiti
- architettura
- interfacce
- RTM
- verification matrix
- piani di test
- baseline attive
- rischi

---

## Esempio di Change Log

| Change ID | Descrizione | Elementi impattati | Decisione | Stato |
|-----------|-------------|--------------------|-----------|------|
| CR-001 | Modifica REQ-001 da 200 ms a 150 ms | Requirements, Architecture, Verification Matrix | Approved | In Progress |
| CR-002 | Aggiornamento IF-003 protocol version | ICD, Integration Plan, Test Cases | Under Review | Open |

---

## Attività del System Engineer

- supportare la formulazione della change
- condurre o contribuire all’impact analysis
- verificare coerenza con needs, requirements e architecture
- assicurare aggiornamento della tracciabilità
- controllare che la change sia verificata prima della chiusura

---

## Errori comuni

- accettare modifiche senza impact analysis
- aggiornare un artefatto senza aggiornare quelli collegati
- approvare change senza owner o piano di verifica
- non distinguere tra change minori e change sistemiche
- chiudere la change senza evidenza di implementazione e verifica

---

## Best practice

- formalizzare ogni change significativa
- eseguire impact analysis multidisciplinare
- collegare le change alle baseline interessate
- aggiornare RTM, architecture, ICD e verification artifacts quando necessario
- trattare il change control come meccanismo di integrità del sistema

---

## Collegamenti

Questa pagina è collegata a:

- Gestione del cambiamento dei requisiti
- Baseline
- Configuration Audit
- RTM
- Verification Matrix
- Risk Management