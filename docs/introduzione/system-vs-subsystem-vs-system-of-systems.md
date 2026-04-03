# System, Subsystem e System of Systems

## Scopo

Chiarire i principali livelli di osservazione nel Systems Engineering: sistema, sottosistema e system of systems.

---

## Contesto

Nel Systems Engineering è fondamentale sapere a quale livello si sta ragionando.

Lo stesso oggetto può essere visto:

- come sistema, se osservato rispetto alla sua missione
- come sottosistema, se osservato come parte di qualcosa di più grande
- come parte di un system of systems, se contribuisce a una capacità emergente insieme ad altri sistemi autonomi

La chiarezza sul livello di analisi è essenziale per evitare confusione nei requisiti, nell’architettura e nella verifica.

---

## System

Un system è un insieme organizzato di elementi che cooperano per raggiungere uno scopo.

Un sistema può comprendere:

- componenti hardware
- componenti software
- operatori
- procedure
- dati
- interfacce
- ambiente operativo

Il sistema è definito rispetto a:

- missione
- confini
- interazioni
- stakeholder
- lifecycle

---

## Subsystem

Un subsystem è una parte del sistema che realizza una porzione delle sue funzioni o responsabilità.

Il sottosistema:

- ha confini propri
- può avere requisiti derivati
- partecipa all’architettura del sistema
- può essere a sua volta scomposto in elementi più piccoli

Un sottosistema deve essere letto sempre in relazione al sistema di cui fa parte.

---

## System of Systems

Un system of systems è un insieme di sistemi distinti che, cooperando, generano capacità emergenti non riconducibili a un singolo sistema isolato.

Caratteristiche tipiche:

- i sistemi componenti mantengono una certa autonomia
- esistono interazioni complesse e distribuite
- emergono comportamenti complessivi
- i confini decisionali e organizzativi sono più complessi

---

## Differenze principali

| Livello | Descrizione | Focus principale |
|--------|-------------|------------------|
| System | Entità completa rispetto a una missione | Missione e coerenza complessiva |
| Subsystem | Parte del sistema | Funzione o responsabilità allocata |
| System of Systems | Insieme di sistemi autonomi cooperanti | Capacità emergente e coordinamento |

---

## Implicazioni per il System Engineer

Il livello di osservazione influisce su:

- formulazione dei requisiti
- definizione dell’architettura
- gestione delle interfacce
- strategia di verifica
- definizione dei confini del sistema

Un requisito valido a livello system può non esserlo a livello subsystem, e viceversa.

---

## Attività del System Engineer

- definire chiaramente il system of interest
- esplicitare i confini
- distinguere requisiti di sistema e requisiti di sottosistema
- chiarire dove emergono le capacità complessive
- gestire le dipendenze tra livelli

---

## Errori comuni

- cambiare livello di analisi senza dichiararlo
- confondere requisito di sistema con requisito di sottosistema
- non esplicitare i confini del system of interest
- sottovalutare le interazioni emergenti nei system of systems

---

## Best practice

- dichiarare sempre il livello di osservazione
- associare requirements e architecture al corretto livello
- distinguere chiaramente system of interest e contesto esterno
- analizzare con attenzione le interfacce tra livelli

---

## Collegamenti

Questa pagina è collegata a:

- Architecture
- Interfaces & Integration
- Stakeholder & Needs
- Lifecycle dei sistemi