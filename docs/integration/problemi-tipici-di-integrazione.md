# Problemi tipici di integrazione

## Scopo

Descrivere i problemi più frequenti che emergono durante l’integrazione di un sistema e fornire una prospettiva sistemistica per prevenirli e gestirli.

---

## Contesto

Molti problemi reali del progetto emergono non durante la definizione teorica del sistema, ma quando elementi diversi devono cooperare.

L’integrazione è il momento in cui:

- le ipotesi vengono messe alla prova
- le interfacce mostrano eventuali ambiguità
- le versioni divergenti entrano in conflitto
- le responsabilità diventano concrete

---

## Problemi ricorrenti

### 1. Interfacce incompletamente definite
Le due estremità dell’interfaccia interpretano in modo diverso il comportamento atteso.

### 2. Incompatibilità di versione
Componenti diversi evolvono in tempi diversi e non restano compatibili.

### 3. Assunzioni implicite
Un team assume condizioni non esplicitate agli altri team.

### 4. Timing e sincronizzazione
La logica funziona in teoria, ma fallisce per latenze, ordine degli eventi o carichi reali.

### 5. Ownership non chiara
Non è evidente chi debba correggere un comportamento inatteso.

### 6. Ambiente di integrazione non rappresentativo
Il problema non appare in laboratorio ma emerge nel contesto reale.

### 7. Dati di prova non realistici
Il sistema sembra funzionare finché non incontra dati reali o scenari degradati.

### 8. Requisiti o ICD non aggiornati
L’integrazione viene fatta su riferimenti non più coerenti con la baseline corrente.

---

## Cause profonde tipiche

Dietro i problemi di integrazione si trovano spesso cause sistemiche:

- scarsa qualità dell’architettura
- ICD deboli o non mantenuti
- change management insufficiente
- tracciabilità incompleta
- test progettati troppo tardi
- separazione eccessiva tra team

---

## Attività del System Engineer

- identificare precocemente i punti di rischio
- chiarire ownership e confini
- verificare la maturità degli artefatti prima dell’integrazione
- supportare l’analisi delle anomalie
- collegare il problema a requisiti, architettura e interfacce
- assicurare che la lezione appresa rientri nel sistema documentale

---

## Esempio di anomaly log semplificato

| Anomaly ID | Interfaccia | Descrizione | Impatto | Owner | Stato |
|------------|-------------|-------------|--------|-------|------|
| ANOM-001 | IF-001 | Formato messaggio incompatibile | Alto | Team A / Team B | Open |
| ANOM-002 | IF-003 | Timeout su carico elevato | Medio | Integration Team | Investigating |

---

## Errori comuni di gestione

- trattare ogni problema come bug locale
- non fare root cause analysis
- correggere il componente senza aggiornare ICD o requirements
- non diffondere la lezione appresa
- chiudere le anomalie senza evidenza sufficiente

---

## Best practice

- usare l’integrazione per validare assunzioni, non solo componenti
- registrare anomalie con contesto e ownership chiari
- fare root cause analysis sui problemi ricorrenti
- aggiornare architettura, ICD e verification artifacts quando necessario
- trattare l’integrazione come fonte di apprendimento sistemico

---

## Collegamenti

Questa pagina è collegata a:

- Interface Management
- Interface Control Document
- Integration Strategy
- Risk Management
- Configuration Management
- Verification & Validation