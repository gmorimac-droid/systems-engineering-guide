# Safety vs Security

## Scopo

Chiarire la differenza tra safety e security e mostrare come entrambe influenzino il Systems Engineering, pur avendo obiettivi e logiche differenti.

---

## Contesto

Safety e security sono spesso citate insieme, ma non sono la stessa cosa.

Nel Systems Engineering è fondamentale distinguerle, perché:

- hanno driver diversi
- generano requisiti diversi
- influenzano l’architettura in modi diversi
- possono entrare in tensione tra loro

---

## Safety

La safety riguarda la prevenzione di condizioni pericolose e la riduzione del rischio di danno a persone, ambiente, asset o missione dovuto al comportamento del sistema.

Domande tipiche della safety:

- cosa può andare pericolosamente storto?
- quali failure o condizioni possono generare hazard?
- come si riduce o controlla il rischio?

---

## Security

La security riguarda la protezione del sistema da accessi non autorizzati, manipolazioni, attacchi, uso improprio o compromissioni intenzionali.

Domande tipiche della security:

- chi può attaccare il sistema?
- quali vulnerabilità possono essere sfruttate?
- come si protegge il sistema da minacce intenzionali?

---

## Differenza fondamentale

### Safety
Focus su:
- eventi accidentali
- guasti
- condizioni pericolose
- mitigazione del danno involontario

### Security
Focus su:
- attori malevoli
- attacchi intenzionali
- vulnerabilità
- protezione da compromissioni deliberate

---

## Relazione tra safety e security

Le due discipline non sono indipendenti.

Un problema di security può generare effetti di safety.  
Ad esempio, una compromissione intenzionale di un controllo critico può portare a una condizione pericolosa.

Allo stesso modo, alcune misure di safety possono influenzare la security e viceversa.

Per questo, nei sistemi critici, safety e security devono essere coordinate.

---

## Esempi

### Esempio safety
Un sensore errato fornisce dati sbagliati e il sistema prende una decisione pericolosa.

### Esempio security
Un attore esterno manipola i dati del sensore e induce il sistema a una decisione pericolosa.

Nel primo caso il problema è accidentale, nel secondo intenzionale.  
L’effetto operativo può però essere simile.

---

## Attività del System Engineer

- distinguere chiaramente safety e security requirements
- identificare dipendenze e possibili conflitti
- supportare l’integrazione delle due discipline nell’architettura
- valutare impatti di change su entrambi gli aspetti
- assicurare che verification e assurance considerino entrambe le prospettive

---

## Errori comuni

- usare safety e security come sinonimi
- trattarle come discipline isolate
- considerare una sola delle due in fase architetturale
- non analizzare gli effetti incrociati tra compromissioni e hazard

---

## Best practice

- esplicitare i confini e gli obiettivi delle due discipline
- definire requisiti separati ma coordinati
- riesaminare l’architettura rispetto a entrambe
- includere safety e security nelle review principali
- mantenere visibili i trade-off tra protezione, operabilità e rischio

---

## Collegamenti

Questa pagina è collegata a:

- Hazard Analysis
- Risk Management
- Requirements Engineering
- Architecture
- Verification & Validation