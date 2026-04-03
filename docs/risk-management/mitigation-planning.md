# Mitigation Planning

## Scopo

Descrivere come pianificare azioni di mitigazione efficaci per ridurre probabilità, impatto o esposizione complessiva ai rischi del sistema e del progetto.

---

## Contesto

Identificare e valutare un rischio non è sufficiente.  
Occorre definire come trattarlo.

La mitigation planning trasforma il risk management da attività descrittiva a leva concreta di controllo del sistema.

---

## Obiettivi della mitigazione

Le azioni di mitigazione possono mirare a:

- ridurre la probabilità che il rischio si verifichi
- ridurre l’impatto se il rischio si verifica
- aumentare la capacità di rilevare precocemente il problema
- preparare un piano di risposta o contingenza

---

## Tipologie di risposta al rischio

Le risposte più comuni includono:

### Avoid
Eliminare la causa o cambiare la soluzione per rimuovere il rischio.

### Reduce / Mitigate
Ridurre probabilità o impatto con azioni specifiche.

### Transfer / Share
Trasferire o condividere parte del rischio, ad esempio verso un fornitore.

### Accept
Accettare il rischio, esplicitando il razionale e monitorandolo.

---

## Esempio di azioni di mitigazione

Rischio:
`RSK-001 Interfaccia IF-003 non stabilizzata prima dell’integrazione`

Possibili mitigazioni:
- anticipare ICD review
- introdurre test di interfaccia preliminari
- congelare baseline della interfaccia a milestone definita
- assegnare owner unico dell’interfaccia
- creare ambiente di test dedicato

---

## Piano di mitigazione

Un piano di mitigazione dovrebbe specificare:

- Risk ID
- azione di mitigazione
- owner
- scadenza
- criterio di successo
- stato
- rischio residuo atteso

---

## Esempio

| Risk ID | Mitigation Action | Owner | Due Date | Success Criterion | Status |
|---------|-------------------|-------|----------|-------------------|--------|
| RSK-001 | ICD review anticipata e test IF preliminare | Integration Lead | M3 | Interfaccia verificata prima della system integration | Open |
| RSK-003 | Workshop con operatori per completare needs | System Engineer | M2 | Need list aggiornata e validata | In Progress |

---

## Relazione con verification e integration

Le mitigazioni influenzano spesso:

- ordine di integrazione
- definizione dei test
- revisione dei requisiti
- scelta architetturale
- readiness delle milestone

Per questo la mitigazione va letta come parte del lifecycle, non come attività separata.

---

## Attività del System Engineer

- proporre mitigazioni tecnicamente efficaci
- verificare che le azioni siano realistiche e misurabili
- collegare le mitigazioni a requisiti, architettura e integration plan
- monitorare il rischio residuo
- supportare il decision-making nei casi di rischio accettato

---

## Errori comuni

- mitigazioni generiche o non verificabili
- azioni senza owner
- mitigazioni non integrate nella pianificazione reale
- chiudere il rischio senza evidenza
- non rivalutare il rischio dopo la mitigazione

---

## Best practice

- definire azioni specifiche, misurabili e con ownership chiara
- distinguere mitigazione e contingency
- collegare le mitigazioni a milestone e deliverable reali
- verificare l’efficacia della mitigazione
- aggiornare il rischio residuo dopo ogni azione significativa

---

## Collegamenti

Questa pagina è collegata a:

- Analisi probabilità / impatto
- Integration Strategy
- Verification Matrix
- Architectural Trade-offs
- Configuration Management