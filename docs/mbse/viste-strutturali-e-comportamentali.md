# Viste strutturali e comportamentali

## Scopo

Distinguere le viste strutturali e comportamentali del sistema e chiarire come queste due prospettive si completano nel MBSE.

---

## Contesto

Un sistema complesso non può essere compreso da una singola rappresentazione.

Per descriverlo correttamente è necessario osservare almeno due dimensioni fondamentali:

- la **struttura** del sistema
- il **comportamento** del sistema

Le viste strutturali e comportamentali rispondono a domande diverse ma complementari.

---

## Vista strutturale

La vista strutturale descrive:

- da quali elementi è composto il sistema
- come questi elementi sono organizzati
- quali relazioni esistono tra gli elementi
- quali interfacce li collegano

Domande tipiche a cui risponde:

- quali sono i componenti principali?
- come è decomposto il sistema?
- quali elementi comunicano tra loro?
- dove è allocata una funzione o un requisito?

Diagrammi tipici:
- Block Definition Diagram
- Internal Block Diagram

---

## Vista comportamentale

La vista comportamentale descrive:

- cosa fa il sistema
- come reagisce agli eventi
- come fluisce l’informazione
- come interagiscono nel tempo i componenti

Domande tipiche a cui risponde:

- quali attività compie il sistema?
- in che sequenza avvengono?
- come reagisce a una condizione?
- come cambia stato un componente?

Diagrammi tipici:
- Activity Diagram
- Sequence Diagram
- State Machine Diagram
- Use Case Diagram

---

## Relazione tra le due viste

Le viste non devono essere trattate come mondi separati.

Una funzione descritta in una vista comportamentale deve poter essere:

- collegata a elementi strutturali
- allocata a componenti fisici o logici
- verificata rispetto ai requisiti

Allo stesso tempo, una struttura senza comportamento associato rischia di essere solo un elenco statico di componenti.

---

## Esempio semplificato

### Vista strutturale
Il sistema comprende:
- Input Adapter
- Processing Engine
- Notification Module

### Vista comportamentale
Il flusso è:
1. ricezione evento
2. validazione dato
3. elaborazione richiesta
4. notifica operatore

Il valore sistemistico emerge quando il flusso viene allocato ai componenti strutturali.

---

## Attività del System Engineer

- definire quali viste servono davvero
- mantenere coerenza tra struttura e comportamento
- evitare contraddizioni tra diagrammi
- usare le viste per supportare allocation, integration e verification
- verificare che le viste coprano gli scenari operativi rilevanti

---

## Errori comuni

- descrivere solo la struttura e ignorare il comportamento
- descrivere solo il comportamento senza sapere dove è implementato
- usare viste incoerenti tra loro
- produrre diagrammi senza collegamento ai requisiti

---

## Best practice

- modellare struttura e comportamento come viste complementari
- esplicitare le relazioni tra funzioni e componenti
- verificare copertura rispetto a scenari reali
- usare le viste per supportare decisioni, non solo documentazione
- mantenere allineamento con requirements e architecture

---

## Collegamenti

Questa pagina è collegata a:

- Functional Architecture
- Physical Architecture
- Decomposition and Allocation
- Verification Matrix
- SysML Overview