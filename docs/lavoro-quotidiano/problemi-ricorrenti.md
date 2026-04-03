# Problemi ricorrenti

## Scopo

Descrivere i problemi che il System Engineer incontra più frequentemente nel lavoro reale e mostrare come questi problemi siano spesso sistemici, non solo locali.

---

## Contesto

Molti problemi quotidiani del Systems Engineering non sono errori isolati, ma segnali di incoerenza tra:

- bisogni e requisiti
- requisiti e architettura
- architettura e interfacce
- change e baseline
- verification e configurazione reale

Riconoscere questi pattern è essenziale per intervenire in modo efficace.

---

## Problemi ricorrenti

### 1. Requisiti ambigui o instabili
Il requisito cambia spesso, non è verificabile o viene interpretato in modi diversi.

### 2. Interfacce non sufficientemente definite
Le due estremità dell’interfaccia hanno assunzioni differenti.

### 3. Disallineamento tra artefatti
RTM, architecture e verification matrix non raccontano la stessa storia.

### 4. Change non completamente propagati
Un requisito viene aggiornato ma architettura, test o ICD restano indietro.

### 5. Problemi di ownership
Non è chiaro chi sia responsabile di una decisione, di un’interfaccia o di una chiusura tecnica.

### 6. Verification tardiva
La verificabilità non è stata considerata abbastanza presto.

### 7. Problemi che emergono solo in integrazione
L’architettura teoricamente regge, ma le interazioni reali mostrano incompatibilità o comportamenti inattesi.

### 8. Contesto operativo sottovalutato
Il sistema soddisfa i requisiti formali ma non risponde davvero al bisogno reale.

---

## Cause profonde tipiche

Dietro questi problemi si trovano spesso cause sistemiche come:

- assunzioni implicite non rese visibili
- mancanza di tracciabilità
- change control debole
- decisioni non documentate
- eccessiva separazione tra team
- artefatti mantenuti come documenti statici invece che come strumenti vivi

---

## Attività del System Engineer

- riconoscere pattern ricorrenti
- collegare il sintomo alla causa sistemica
- evitare correzioni solo locali quando il problema è trasversale
- usare il problema per rafforzare coerenza, governance e tracciabilità
- trasformare anomalie in apprendimento strutturato

---

## Esempio

Sintomo:
un test fallisce in integrazione.

Analisi sistemica possibile:
- requisito ambiguo
- interfaccia non allineata all’ICD
- verification matrix non aggiornata
- baseline sbagliata usata in test

Il fallimento del test è solo il punto visibile.

---

## Errori comuni

- trattare ogni problema come bug locale
- risolvere senza root cause analysis
- non aggiornare gli artefatti dopo la correzione
- non diffondere la lezione appresa
- chiudere il problema senza verificare la coerenza end-to-end

---

## Best practice

- cercare sempre la causa sistemica oltre al sintomo
- collegare i problemi a requirements, architecture e configuration
- aggiornare gli artefatti coinvolti
- usare anomalie e problemi come input a risk e change control
- costruire una memoria tecnica condivisa dei problemi ricorrenti

---

## Collegamenti

Questa pagina è collegata a:

- Risk Management
- Change Control
- Interfaces & Integration
- Verification & Validation
- Pensiero sistemico