# Analisi probabilità / impatto

## Scopo

Descrivere come valutare i rischi in termini di probabilità di accadimento e impatto sugli obiettivi del sistema o del progetto.

---

## Contesto

Dopo aver identificato un rischio, è necessario valutarne la rilevanza.

La valutazione probabilità / impatto consente di:

- confrontare i rischi tra loro
- definire priorità di trattamento
- allocare risorse di mitigazione in modo proporzionato
- rendere il rischio visibile nelle decisioni tecniche

---

## Probabilità

La probabilità rappresenta quanto è plausibile che il rischio si verifichi.

Può essere espressa in forma:

- qualitativa (bassa, media, alta)
- semi-quantitativa (1–5)
- quantitativa, quando disponibile evidenza sufficiente

---

## Impatto

L’impatto rappresenta la gravità delle conseguenze se il rischio si materializza.

L’impatto può riguardare:

- performance del sistema
- soddisfazione dei requisiti
- integrazione
- safety
- tempi
- costi
- compliance
- operatività

---

## Matrice probabilità / impatto

Una rappresentazione comune è la matrice rischio:

| Impatto \ Probabilità | Bassa | Media | Alta |
|-----------------------|------|-------|------|
| Basso | Basso | Basso | Medio |
| Medio | Basso | Medio | Alto |
| Alto | Medio | Alto | Critico |

Questa matrice aiuta a classificare la priorità del rischio.

---

## Esempio di valutazione

| Risk ID | Descrizione | Probabilità | Impatto | Priorità |
|---------|-------------|-------------|---------|----------|
| RSK-001 | Interfaccia IF-003 non stabilizzata | Alta | Alto | Critico |
| RSK-002 | Ritardo disponibilità ambiente di test | Media | Medio | Medio |
| RSK-003 | Requisiti operativi incompleti | Media | Alto | Alto |

---

## Fattori da considerare nella valutazione

### Per la probabilità
- maturità tecnica
- precedenti anomalie
- stabilità della baseline
- dipendenze esterne
- complessità dell’interfaccia

### Per l’impatto
- criticità del requisito coinvolto
- influenza sul percorso critico
- effetto su integrazione / verification
- impatto su safety / compliance
- costo di recupero

---

## Attività del System Engineer

- supportare la valutazione tecnica del rischio
- evitare stime arbitrarie o non motivate
- collegare la criticità del rischio a elementi reali del sistema
- riesaminare la classificazione quando il contesto cambia
- usare il rischio come criterio per prioritizzare verification e mitigazioni

---

## Errori comuni

- assegnare probabilità e impatto senza razionale
- sottostimare i rischi “noti ma non ancora esplosi”
- trattare tutti i rischi come uguali
- non rivalutare il rischio dopo mitigazioni o change

---

## Best practice

- definire scale condivise di probabilità e impatto
- documentare il razionale della classificazione
- riesaminare i rischi a ogni milestone
- usare la priorità del rischio per guidare le azioni
- distinguere chiaramente rischio grezzo e rischio residuo

---

## Collegamenti

Questa pagina è collegata a:

- Identificazione dei rischi
- Mitigation Planning
- Integration Strategy
- Architectural Trade-offs
- Verification Planning