# Requirements Engineering

La gestione dei requisiti è una delle attività centrali del Systems Engineering.

## Scopo

Definire requisiti chiari, coerenti, verificabili e tracciabili che traducano i bisogni degli stakeholder in una base tecnica utilizzabile da progettazione, integrazione e test.

## Tipi di requisiti

Tra i livelli più comuni troviamo:

- stakeholder requirements
- system requirements
- subsystem requirements
- functional requirements
- non-functional requirements
- interface requirements
- constraints

## Caratteristiche di un buon requisito

Un requisito dovrebbe essere:

- chiaro
- non ambiguo
- verificabile
- necessario
- coerente
- tracciabile
- realizzabile

## Attività del System Engineer

- derivazione dei requisiti dai needs
- decomposizione per livelli
- verifica di qualità dei requisiti
- gestione della tracciabilità
- analisi di impatto delle modifiche
- supporto alla baseline

## Artefatti tipici

- requirement specification
- requirement database
- traceability matrix
- change record
- review comments

## Errori comuni

- requisiti scritti come soluzioni
- requisiti non verificabili
- duplicazioni
- conflitti non risolti
- assenza di rationale

## Best practice

- usare una sintassi controllata
- mantenere un identificativo univoco
- collegare ogni requisito a una fonte
- definire il metodo di verifica
- separare requisito, nota e motivazione

## Collegamenti

I requisiti guidano la **System Architecture**, la **Verification & Validation** e la **Configuration Management**.

# Requirements Engineering

## Scopo

Questa sezione descrive il processo di Requirements Engineering nel Systems Engineering, includendo:

- definizione dei requisiti
- qualità
- tracciabilità
- gestione delle modifiche

---

## Contesto

I requisiti rappresentano il collegamento tra:

- bisogni degli stakeholder (needs)
- architettura del sistema
- attività di verifica e validazione

Un errore nei requisiti si propaga lungo tutto il lifecycle.

---

## Processo di Requirements Engineering

Il processo si articola in:

1. Identificazione dei needs
2. Derivazione dei requisiti
3. Classificazione
4. Verifica qualità
5. Tracciabilità
6. Gestione del cambiamento

---

## Struttura dei requisiti

Formato standard:

REQ-XXX Il sistema deve <azione> <condizione> <vincolo>


---

## Esempio

### REQ-001  
Il sistema deve elaborare una richiesta utente entro 200 ms nel 95% dei casi.

---

## Collegamenti interni

- [Tipi di requisiti](tipi-di-requisiti.md)
- [Qualità dei requisiti](qualita-dei-requisiti.md)
- [Tracciabilità](tracciabilita.md)
- [Gestione del cambiamento](gestione-del-cambiamento.md)

---

## Artefatti principali

- Requirements Specification
- RTM (Traceability Matrix)
- Change Log

---

## Ruolo del System Engineer

- garantire qualità
- mantenere coerenza
- controllare modifiche
- assicurare tracciabilità

---

## Best practice

- partire dai needs
- evitare ambiguità
- mantenere ID univoci
- collegare sempre requisiti → test