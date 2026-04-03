# Multi-Criteria Analysis

## Scopo

Descrivere come valutare alternative rispetto a più criteri contemporaneamente, in modo da supportare decisioni complesse nel Systems Engineering.

---

## Contesto

Molte decisioni di sistema coinvolgono criteri che non possono essere ridotti a una singola misura.

Ad esempio, una soluzione può essere:

- migliore in performance
- peggiore in costo
- più rischiosa da integrare
- più difficile da mantenere

La multi-criteria analysis serve a rendere questo bilanciamento esplicito e comparabile.

---

## Definizione

La multi-criteria analysis è un approccio che confronta alternative rispetto a più criteri, tenendo conto di priorità, pesi o soglie, per supportare una decisione strutturata.

---

## Passi tipici

1. definire le alternative
2. definire i criteri
3. assegnare pesi o priorità
4. valutare ogni alternativa rispetto a ciascun criterio
5. sintetizzare i risultati
6. interpretare i compromessi
7. formulare una raccomandazione

---

## Esempio di matrice semplificata

| Alternative | Performance | Cost | Risk | Maintainability | Valutazione complessiva |
|-------------|-------------|------|------|-----------------|-------------------------|
| ALT-001 | Alta | Alto | Medio | Medio | Forte su performance, penalizzata dai costi |
| ALT-002 | Media | Medio | Basso | Alta | Buon equilibrio generale |
| ALT-003 | Alta | Medio | Alto | Bassa | Prestazioni elevate ma rischio residuo alto |

---

## Uso dei pesi

I pesi servono a rappresentare la diversa importanza dei criteri.

Esempio:

- performance: 30%
- rischio tecnico: 25%
- costo: 20%
- manutenibilità: 15%
- verificabilità: 10%

I pesi devono essere giustificati dal contesto e non scelti per “forzare” un risultato.

---

## Interpretazione dei risultati

La multi-criteria analysis non sostituisce il giudizio ingegneristico.

Serve a:

- strutturare il confronto
- rendere esplicite le priorità
- evidenziare compromessi
- mostrare alternative dominanti o deboli

La decisione finale deve comunque considerare:

- vincoli non numerici
- rischi residui
- fattibilità reale
- maturità tecnica
- impatti sul lifecycle

---

## Attività del System Engineer

- costruire una matrice coerente con il problema
- verificare che i dati siano confrontabili
- evitare semplificazioni fuorvianti
- documentare assunzioni e limiti dell’analisi
- usare i risultati come supporto, non come automatismo

---

## Errori comuni

- attribuire numeri senza significato reale
- usare pesi arbitrari
- confrontare alternative immature con alternative già mature senza esplicitarlo
- ignorare il rischio residuo o gli effetti sul lifecycle
- trattare il punteggio finale come verità assoluta

---

## Best practice

- mantenere la matrice semplice e leggibile
- usare dati e assunzioni documentati
- affiancare la matrice a un commento qualitativo
- evidenziare chiaramente i compromessi principali
- collegare sempre i risultati al decision rationale

---

## Collegamenti

Questa pagina è collegata a:

- Trade Studies
- Decision Criteria
- Architectural Trade-offs
- Risk Management
- Decision Rationale