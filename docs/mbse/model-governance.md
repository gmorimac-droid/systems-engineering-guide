# Model Governance

## Scopo

Descrivere come governare il modello di sistema affinché resti coerente, utile, aggiornato e affidabile lungo il lifecycle.

---

## Contesto

Un modello non governato tende a degradarsi rapidamente.

Senza governance, il modello rischia di diventare:

- incoerente
- ridondante
- incompleto
- scollegato dai documenti e dalla realtà del progetto
- inutilizzato dal team

La model governance è quindi essenziale quanto la modellazione stessa.

---

## Obiettivi della governance del modello

La governance del modello serve a:

- definire ownership e responsabilità
- stabilire convenzioni condivise
- controllare qualità e coerenza
- gestire versioni e baseline
- mantenere allineamento con requirements, architecture e verification

---

## Elementi chiave della governance

### 1. Scope del modello
Deve essere chiaro cosa il modello rappresenta e cosa no.

### 2. Ownership
Ogni parte del modello deve avere un owner chiaro.

### 3. Convenzioni
Devono essere definite regole per:
- naming
- identificativi
- livelli di dettaglio
- tipi di relazione
- struttura dei package

### 4. Quality control
Il modello deve essere sottoposto a review e controlli di consistenza.

### 5. Versioning e baseline
Il modello deve evolvere in modo controllato, con baseline coerenti con quelle documentali.

### 6. Allineamento con altri artefatti
Il modello deve restare coerente con:
- requirements
- architecture descriptions
- RTM
- verification artifacts

---

## Attività del System Engineer

- definire le regole di modellazione
- chiarire ownership delle viste
- verificare la qualità del modello
- assicurare la sincronizzazione con gli artefatti principali
- supportare il team nell’uso corretto del modello
- gestire modifiche e impatti sul modello

---

## Criteri di qualità del modello

Un modello ben governato dovrebbe essere:

- coerente
- leggibile
- tracciabile
- aggiornato
- utile alle decisioni
- non ridondante

---

## Errori comuni

- creare modelli senza ownership
- modellare senza convenzioni condivise
- non aggiornare il modello dopo i change
- usare il modello come archivio passivo
- duplicare nel modello informazioni già inconsistenti altrove

---

## Best practice

- trattare il modello come configuration item
- definire un model management plan
- fare review periodiche del modello
- limitare il dettaglio a ciò che produce valore
- integrare la governance del modello con configuration management e change management

---

## Collegamenti

Questa pagina è collegata a:

- Configuration Management
- Change Management
- Requirements Engineering
- Architecture
- Verification & Validation