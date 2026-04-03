# Supportability

## Scopo

Descrivere la supportability del sistema, cioè la sua capacità di essere sostenuto efficacemente in esercizio attraverso manutenzione, logistica, diagnosi, risorse e processi adeguati.

---

## Contesto

Un sistema può essere tecnicamente corretto ma scarsamente supportabile se:

- è difficile da diagnosticare
- richiede tempi lunghi di ripristino
- dipende da risorse rare
- non ha strumenti adeguati di manutenzione
- non consente aggiornamenti gestibili

La supportability influenza direttamente:

- disponibilità
- costo operativo
- fiducia degli stakeholder
- sostenibilità nel tempo

---

## Definizione

La supportability è la capacità del sistema di essere supportato in modo efficace e sostenibile durante l’operazione e la manutenzione.

---

## Elementi della supportability

La supportability può includere:

- accessibilità ai componenti
- strumenti di diagnosi
- logging e osservabilità
- documentazione tecnica
- disponibilità di ricambi o risorse
- processi di manutenzione
- formazione del personale
- tempi di ripristino
- supporto software e configurativo

---

## Relazione con il Systems Engineering

La supportability non va aggiunta a posteriori.  
Deve essere considerata durante:

- requirements
- architecture
- trade-off analysis
- verification
- maintenance planning

---

## Esempi di requisiti collegati

- tempo massimo di ripristino
- disponibilità di logging diagnostico
- possibilità di sostituire un modulo senza fermo totale
- capacità di aggiornamento controllato
- supporto a rollback in caso di failure

---

## Attività del System Engineer

- tradurre bisogni di supporto in requisiti verificabili
- assicurare che l’architettura supporti diagnosi e manutenzione
- collegare supportability e dependability
- usare dati operativi per migliorare il sistema
- mantenere visibile il costo di supporto nelle decisioni

---

## Input

- operational concept
- maintenance concept
- architecture
- dependability goals
- operational feedback

---

## Output

- requisiti di supportabilità
- input per trade-off architetturali
- criteri di verifica della supportability
- miglioramento del supporto operativo

---

## Errori comuni

- considerare solo la funzionalità e non la sostenibilità del sistema
- non prevedere strumenti di diagnosi
- sottovalutare tempi e costi di supporto
- non collegare supportability a requirements e architecture

---

## Best practice

- considerare supportability come driver architetturale
- tradurre la supportabilità in requisiti misurabili
- includere operatori e manutentori nella definizione del sistema
- verificare la supportabilità con scenari realistici
- usare il feedback operativo per migliorare il supporto nel tempo

---

## Collegamenti

Questa pagina è collegata a:

- Maintenance Concept
- Dependability
- Risk Management
- Architecture
- Operations Feedback