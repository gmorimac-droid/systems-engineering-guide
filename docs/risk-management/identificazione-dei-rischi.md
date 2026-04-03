# Identificazione dei rischi

## Scopo

Descrivere come identificare in modo sistematico i rischi che possono influenzare il sistema, il progetto e il lifecycle.

---

## Contesto

Un rischio è una condizione incerta che, se si verifica, può produrre un effetto negativo su obiettivi tecnici, operativi, economici o di pianificazione.

Nel Systems Engineering, l’identificazione dei rischi deve partire presto e continuare lungo tutto il lifecycle.

Un rischio identificato in ritardo è molto più difficile e costoso da gestire.

---

## Obiettivo dell’identificazione

L’identificazione serve a:

- rendere visibili le principali incertezze
- prevenire failure tardive
- supportare decisioni più robuste
- orientare mitigazioni e verification
- collegare le vulnerabilità agli elementi reali del sistema

---

## Categorie tipiche di rischio

### 1. Rischi sui requisiti
- requisiti incompleti
- requisiti ambigui
- requisiti instabili
- tracciabilità insufficiente

### 2. Rischi architetturali
- architettura non matura
- allocation debole
- interfacce non chiare
- dipendenze eccessive

### 3. Rischi di integrazione
- incompatibilità tra componenti
- versioni non allineate
- interfacce non verificate
- ambienti di integrazione non rappresentativi

### 4. Rischi di verification
- test non pianificati
- requisiti non verificabili
- gap di copertura
- acceptance criteria non misurabili

### 5. Rischi operativi
- contesto d’uso non compreso
- supportabilità insufficiente
- carichi reali sottostimati
- scenari degradati non considerati

### 6. Rischi organizzativi / di progetto
- responsabilità poco chiare
- dipendenze da fornitori
- ritardi nella disponibilità dei componenti
- carenza di competenze o risorse

---

## Fonti per l’identificazione dei rischi

I rischi possono essere identificati a partire da:

- stakeholder needs
- requirement reviews
- architecture reviews
- interface analysis
- integration planning
- verification planning
- historical lessons learned
- anomaly data
- workshop multidisciplinari

---

## Tecniche di identificazione

Le tecniche più comuni includono:

- brainstorming strutturato
- review tecniche
- checklists
- analisi delle interfacce
- analisi di scenari operativi
- studio di anomaly e progetti precedenti
- pre-mortem analysis

---

## Formulazione di un rischio

Un rischio ben formulato dovrebbe indicare:

- la condizione incerta
- l’evento potenziale
- la conseguenza sul sistema o sul progetto

Esempio:

> Se l’interfaccia IF-003 non viene stabilizzata prima dell’integrazione di sistema, esiste il rischio di ritardo nella system verification e di failure di test end-to-end.

---

## Attività del System Engineer

- identificare rischi tecnici e sistemici
- collegare i rischi a elementi architetturali e interfacce
- distinguere sintomi da cause profonde
- documentare il rischio con chiarezza
- assicurare che i rischi critici siano visibili ai decision-maker

---

## Input

- architecture description
- RTM
- interface list
- integration strategy
- verification planning
- lessons learned

---

## Output

- elenco dei rischi identificati
- prima classificazione dei rischi
- base per analisi probabilità / impatto
- alimentazione del risk register

---

## Errori comuni

- identificare solo rischi di scheduling
- registrare problemi già avvenuti come se fossero rischi
- formulare rischi troppo vaghi
- non collegare il rischio a un owner o a un contesto concreto
- ignorare i rischi di integrazione e interfaccia

---

## Best practice

- identificare i rischi fin dalle fasi iniziali
- collegare ogni rischio a una fonte o a un contesto
- formulare il rischio in termini di causa ed effetto
- rivedere periodicamente i rischi
- coinvolgere più discipline nell’identificazione

---

## Collegamenti

Questa pagina è collegata a:

- Architecture
- Interfaces & Integration
- Verification & Validation
- Mitigation Planning
- Risk Register