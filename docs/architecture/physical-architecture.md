# Physical Architecture

## Scopo

Descrivere il sistema in termini di elementi fisici o realizzativi, delle loro responsabilità e delle relazioni tra di essi.

---

## Contesto

Se la functional architecture descrive cosa fa il sistema, la physical architecture descrive dove e in quali elementi del sistema tali funzioni vengono implementate.

La physical architecture rappresenta quindi la struttura concreta della soluzione.

---

## Definizione

La physical architecture è la rappresentazione del sistema in termini di componenti o elementi reali, come ad esempio:

- moduli hardware
- componenti software
- unità logiche
- dispositivi
- sottosistemi
- nodi di rete
- interfacce fisiche o logiche

---

## Obiettivo della physical architecture

L’obiettivo è:

- definire la struttura implementativa del sistema
- identificare componenti e confini
- assegnare responsabilità
- chiarire relazioni e interfacce
- supportare integrazione e verifica

---

## Elementi tipici

Una physical architecture include:

- componenti
- sottosistemi
- connessioni
- interfacce
- responsabilità implementative
- dipendenze strutturali

---

## Esempio semplificato

Per un sistema di gestione eventi, la physical architecture potrebbe includere:

- modulo di acquisizione dati
- motore di elaborazione
- database di persistenza
- interfaccia utente operatore
- modulo di notifica

Questi elementi rappresentano l’implementazione concreta delle funzioni definite a livello funzionale.

---

## Relazione con i requisiti

La physical architecture deve:

- implementare i requisiti allocati
- supportare vincoli prestazionali e operativi
- mantenere coerenza con i confini del sistema
- rendere gestibile integrazione e verification

---

## Relazione con la functional architecture

La physical architecture non sostituisce quella funzionale.  
Le due devono restare collegate tramite allocation:

```text
Function → Physical Element
```