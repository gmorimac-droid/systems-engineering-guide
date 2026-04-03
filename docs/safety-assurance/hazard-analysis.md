# Hazard Analysis

## Scopo

Descrivere come identificare, valutare e controllare gli hazard nel Systems Engineering, in modo da ridurre il rischio di condizioni pericolose lungo il lifecycle.

---

## Contesto

Un hazard è una condizione o uno stato che può portare a un danno, se combinato con determinate circostanze.

La hazard analysis serve a individuare in anticipo:

- condizioni pericolose
- cause possibili
- effetti attesi
- misure di controllo o mitigazione

Nel Systems Engineering, la hazard analysis è strettamente collegata a requirements, architecture, operation e verification.

---

## Definizione di hazard

Un hazard non è necessariamente un incidente già avvenuto, ma una condizione che può contribuire a generare conseguenze indesiderate.

Esempi:
- perdita di controllo
- dati errati in funzione critica
- indisponibilità di una funzione di sicurezza
- comando non intenzionale
- ritardo non accettabile in decisione critica

---

## Obiettivi della hazard analysis

La hazard analysis serve a:

- identificare condizioni pericolose
- valutare severità e plausibilità
- supportare la definizione di requisiti di safety
- influenzare le scelte architetturali
- guidare verification e assurance evidence

---

## Passi tipici

1. identificazione degli hazard
2. descrizione del contesto operativo
3. analisi delle cause possibili
4. analisi delle conseguenze
5. classificazione della severità
6. definizione delle mitigazioni o dei controlli
7. collegamento ai requisiti e alla verification

---

## Esempio semplificato

| Hazard ID | Hazard | Possibile causa | Effetto | Mitigazione |
|-----------|--------|-----------------|---------|-------------|
| HZD-001 | Dato errato usato per decisione critica | Input non validato | Decisione operativa non sicura | Validazione input + alert operatore |
| HZD-002 | Timeout su funzione critica | Sovraccarico sistema | Ritardo oltre soglia di sicurezza | Monitoraggio timing + fallback mode |

---

## Relazione con i requisiti

Ogni hazard significativo dovrebbe poter portare a:

- safety requirements
- architectural constraints
- procedure operative
- verifiche specifiche

Questo crea il collegamento tra hazard analysis e il resto del sistema.

---

## Attività del System Engineer

- supportare l’identificazione degli hazard
- assicurare il collegamento con il contesto operativo
- collegare hazard, requisiti e architettura
- garantire che le mitigazioni siano verificabili
- mantenere aggiornata l’analisi quando cambiano sistema o missione

---

## Artefatti tipici

- hazard log
- hazard analysis report
- safety requirements
- traceability to verification
- mitigation status tracking

---

## Errori comuni

- trattare gli hazard in modo troppo astratto
- non collegare hazard a scenari operativi
- non trasformare gli hazard in requisiti o controlli
- considerare l’analisi chiusa troppo presto
- non aggiornarla dopo modifiche rilevanti

---

## Best practice

- identificare hazard già nelle prime fasi del lifecycle
- collegare ogni hazard a cause, effetti e mitigazioni
- usare scenari realistici e condizioni degradate
- verificare le mitigazioni con criteri oggettivi
- mantenere il hazard log allineato a change e baseline

---

## Collegamenti

Questa pagina è collegata a:

- Risk Management
- Requirements Engineering
- Architecture
- Verification & Validation
- Assurance Evidence