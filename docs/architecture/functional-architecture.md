# Functional Architecture

## Scopo

Descrivere il sistema in termini di funzioni, comportamenti e flussi logici, indipendentemente dalla sua implementazione fisica.

---

## Contesto

L’architettura funzionale rappresenta il livello in cui il sistema viene descritto in termini di:

- cosa deve fare
- quali trasformazioni deve realizzare
- come interagiscono le funzioni
- quali flussi di informazione, energia o controllo attraversano il sistema

Questo livello è fondamentale perché permette di collegare i requisiti alla struttura logica del sistema prima di decidere come implementarlo.

---

## Definizione

La functional architecture è la rappresentazione organizzata delle funzioni del sistema e delle loro relazioni.

Le funzioni descrivono attività o capacità del sistema, ad esempio:

- acquisire dati
- elaborare informazione
- prendere decisioni
- emettere comandi
- fornire output all’operatore

---

## Obiettivo dell’architettura funzionale

L’obiettivo principale è:

- strutturare il comportamento del sistema
- identificare funzioni e sottofunzioni
- chiarire dipendenze e flussi
- preparare la successiva allocation alla physical architecture

---

## Elementi tipici

Una functional architecture può includere:

- funzioni principali
- sottofunzioni
- flussi di input / output
- relazioni funzionali
- condizioni operative
- trigger e dipendenze

---

## Esempio semplificato

Un sistema di elaborazione eventi può essere descritto con le seguenti funzioni:

1. acquisizione evento
2. validazione dato
3. elaborazione richiesta
4. generazione output
5. notifica operatore

Queste funzioni non implicano ancora come il sistema sia fisicamente costruito.

---

## Relazione con i requisiti

La functional architecture deriva direttamente dai requisiti, in particolare da:

- functional requirements
- performance requirements
- interface-related requirements

Ogni funzione dovrebbe contribuire alla soddisfazione di uno o più requisiti.

---

## Attività del System Engineer

- identificare le funzioni principali del sistema
- decomporre funzioni complesse in sottofunzioni
- definire i flussi tra funzioni
- mantenere coerenza tra requisiti e funzioni
- verificare che la functional architecture sia completa e consistente

---

## Artefatti tipici

- functional decomposition
- functional flow diagrams
- activity diagrams
- sequence descriptions
- function-to-requirement mapping

---

## Errori comuni

- confondere funzione e componente fisico
- introdurre dettagli implementativi troppo presto
- definire funzioni troppo generiche o troppo dettagliate
- non collegare le funzioni ai requisiti

---

## Best practice

- descrivere le funzioni con verbi chiari
- separare il “cosa” dal “come”
- mantenere tracciabilità tra requisiti e funzioni
- verificare completezza rispetto agli scenari operativi
- usare la functional architecture come base per allocation e verification

---

## Collegamenti

Questa pagina è collegata a:

- Requirements Engineering
- Physical Architecture
- Decomposition and Allocation
- Verification & Validation