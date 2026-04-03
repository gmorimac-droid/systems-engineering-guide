# Dependability

## Scopo

Descrivere il concetto di dependability e il suo ruolo nel Systems Engineering come capacità del sistema di fornire un servizio affidabile e accettabile nel tempo e nel contesto previsto.

---

## Contesto

Un sistema può essere formalmente corretto ma comunque non essere considerato affidabile dagli stakeholder se:

- fallisce troppo spesso
- è difficile da recuperare
- si degrada in modo non controllato
- non mantiene prestazioni accettabili
- non consente fiducia operativa

Il concetto di dependability aiuta a inquadrare queste proprietà in modo sistemico.

---

## Definizione

La dependability è la capacità del sistema di fornire un servizio di cui ci si possa ragionevolmente fidare.

Questa nozione comprende diverse proprietà correlate, tra cui:

- affidabilità
- disponibilità
- manutenibilità
- safety
- integrità
- robustezza

---

## Proprietà tipiche della dependability

### Reliability
Capacità del sistema di svolgere la funzione richiesta per un periodo di tempo dato, in condizioni definite.

### Availability
Capacità del sistema di essere operativo e disponibile quando richiesto.

### Maintainability
Capacità del sistema di essere mantenuto, corretto o aggiornato in modo efficace.

### Integrity
Capacità di mantenere correttezza e coerenza di dati e comportamento.

### Robustness
Capacità di tollerare condizioni anomale, carichi o variazioni senza degradazioni inaccettabili.

### Safety
Capacità di evitare stati pericolosi o di mantenere il rischio a un livello accettabile.

---

## Perché è importante

La dependability è importante perché collega il sistema:

- alla fiducia operativa
- alla sostenibilità del servizio
- alla percezione di qualità da parte degli stakeholder
- ai requisiti di lungo periodo, non solo alle verifiche puntuali

---

## Relazione con requirements e architecture

La dependability deve essere supportata da:

- requisiti appropriati
- architetture robuste
- gestione del rischio
- strategie di manutenzione
- verification continua
- gestione delle anomalie e dei change

Non è una proprietà emergente casuale: deve essere progettata e verificata.

---

## Attività del System Engineer

- identificare gli attributi di dependability rilevanti per il sistema
- collegarli ai needs e ai requisiti
- verificare che l’architettura supporti gli attributi critici
- collegare dependability, risk e verification
- supportare l’analisi delle implicazioni lungo il lifecycle

---

## Errori comuni

- trattare affidabilità e disponibilità come dettagli secondari
- non collegare dependability e operation
- misurare solo prestazioni istantanee ignorando comportamento nel tempo
- non considerare recovery, degradation modes e maintenance

---

## Best practice

- definire chiaramente quali attributi di dependability sono critici
- tradurre gli attributi in requisiti verificabili
- considerare dependability già nei trade-off architetturali
- collegare dependability a verification, maintenance e anomaly management
- monitorare dependability anche in operation

---

## Collegamenti

Questa pagina è collegata a:

- Requirements Engineering
- Risk Management
- Architecture
- Operations & Maintenance
- Verification & Validation
- Assurance Evidence