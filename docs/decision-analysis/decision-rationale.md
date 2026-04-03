# Decision Rationale

## Scopo

Descrivere come documentare il rationale di una decisione, cioè la motivazione tecnica e sistemica che spiega perché una determinata alternativa è stata scelta.

---

## Contesto

Una decisione non documentata tende a perdere valore nel tempo.

Senza rationale esplicito diventa difficile:

- capire perché una scelta è stata fatta
- riesaminare la decisione in caso di change
- difendere la soluzione in review o audit
- trasferire conoscenza a nuovi membri del team

Il decision rationale è quindi parte essenziale della governance tecnica.

---

## Definizione

Il decision rationale è la motivazione documentata che collega:

- problema decisionale
- alternative considerate
- criteri usati
- compromessi accettati
- decisione finale

---

## Contenuti tipici del rationale

Un rationale ben documentato dovrebbe includere:

- contesto della decisione
- opzioni considerate
- criteri decisionali
- vincoli rilevanti
- rischi principali
- sintesi della valutazione
- decisione adottata
- implicazioni e compromessi
- condizioni che potrebbero richiedere revisione futura

---

## Esempio sintetico

Decisione:
adozione di architettura distribuita per il modulo di elaborazione.

Rationale:
la soluzione distribuita è stata scelta perché offre migliore resilienza e scalabilità rispetto alla soluzione centralizzata, pur introducendo maggiore complessità di integrazione. Il rischio aggiuntivo è stato accettato in considerazione dei requisiti di disponibilità e del contesto operativo distribuito.

---

## Valore del rationale nel lifecycle

Il rationale è utile per:

- change management
- configuration audit
- architecture review
- risk review
- onboarding del team
- future re-use della decisione

---

## Attività del System Engineer

- assicurare che le decisioni rilevanti abbiano rationale esplicito
- collegare il rationale a requirements, risks e architecture
- mantenere la motivazione della scelta accessibile e comprensibile
- aggiornare il rationale se il contesto cambia in modo significativo

---

## Errori comuni

- registrare solo la decisione finale senza spiegazione
- documentare motivazioni vaghe o non tecniche
- non menzionare le alternative scartate
- non evidenziare i compromessi e i rischi residui
- non aggiornare il rationale dopo change importanti

---

## Best practice

- documentare il rationale al momento della decisione
- mantenere il testo sintetico ma sufficiente
- collegare la decisione agli artefatti del progetto
- evidenziare le ipotesi su cui si basa la scelta
- registrare quando e perché la decisione dovrebbe essere riesaminata

---

## Collegamenti

Questa pagina è collegata a:

- Trade Studies
- Decision Criteria
- Multi-Criteria Analysis
- Architectural Trade-offs
- Change Control
- Risk Register

Il decision rationale è ciò che rende una decisione non solo presa, ma anche spiegabile, tracciabile e governabile nel tempo.