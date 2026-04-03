# Decomposition and Allocation

## Scopo

Descrivere come il sistema viene scomposto in elementi architetturali e come requisiti e funzioni vengono allocati a tali elementi.

---

## Contesto

La decomposizione consente di suddividere il sistema in parti gestibili.  
L’allocation consente di collegare:

- requisiti
- funzioni
- elementi architetturali

Questa pagina rappresenta il punto in cui requirements e architecture si incontrano in modo esplicito.

---

## Decomposition

La decomposition consiste nello scomporre il sistema in livelli gerarchici più piccoli e controllabili.

La decomposizione può essere:

- funzionale
- fisica
- logica
- organizzativa

Una decomposizione corretta deve produrre elementi:

- coerenti
- comprensibili
- con confini chiari
- utili per implementazione e verifica

---

## Allocation

L’allocation consiste nell’assegnare una funzione o un requisito a uno o più elementi architetturali responsabili della sua implementazione.

Relazione tipica:

```text
Requirement / Function → Architecture Element
```

