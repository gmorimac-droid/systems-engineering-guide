# Assurance Evidence

## Scopo

Descrivere il ruolo delle assurance evidence come insieme strutturato di evidenze che supportano la fiducia nel fatto che il sistema soddisfi i requisiti critici e mantenga un livello accettabile di safety, affidabilità o conformità.

---

## Contesto

Nel Systems Engineering, non basta dichiarare che il sistema è sicuro o conforme.  
Occorre costruire un insieme coerente di evidenze che dimostrino tale affermazione.

Le assurance evidence possono provenire da:

- analisi
- test
- inspection
- review
- audit
- tracciabilità documentata
- risultati di hazard analysis
- verifiche di processo e di prodotto

---

## Definizione

Le assurance evidence sono evidenze oggettive, organizzate e tracciabili, usate per supportare affermazioni sulla correttezza, sicurezza, affidabilità o conformità del sistema.

---

## Obiettivi delle assurance evidence

Le evidence servono a:

- supportare decisioni di accettazione
- dimostrare conformità a requisiti critici
- sostenere safety case o argomentazioni equivalenti
- rendere auditabile la fiducia nel sistema
- mantenere coerenza tra analisi, design e verifica

---

## Tipologie di evidence

Le assurance evidence possono includere:

- risultati di verification
- review tecniche
- test report
- inspection record
- tracciabilità requirements-to-test
- hazard mitigations verificate
- baseline approvate
- audit findings risolti
- modelli e analisi ingegneristiche

---

## Esempio di struttura delle evidence

| Evidence ID | Tipo | Claim supportato | Fonte | Stato |
|-------------|------|------------------|-------|------|
| EVD-001 | Test Report | REQ-021 soddisfatto | System Verification | Approved |
| EVD-002 | Hazard Review | Mitigazione HZD-003 efficace | Safety Analysis | Approved |
| EVD-003 | Audit Record | Baseline architetturale coerente | Configuration Audit | In Review |

---

## Relazione con il lifecycle

Le assurance evidence si costruiscono progressivamente:

- nelle fasi iniziali: analisi e requisiti
- nelle fasi centrali: architettura, hazard analysis, trade-offs
- nelle fasi tarde: verification reports, audit, validation evidence

Per questo l’assurance non è un pacchetto finale, ma una costruzione incrementale.

---

## Attività del System Engineer

- definire quali claim richiedono evidence
- assicurare coerenza tra evidence e artefatti sorgente
- collegare le evidence a requirements, hazards e verification
- controllare che le evidence restino valide dopo i change
- supportare review e audit con evidenze strutturate

---

## Errori comuni

- considerare le evidence come allegati scollegati
- non tracciare il claim che ogni evidenza supporta
- usare evidenze obsolete rispetto alla baseline corrente
- non collegare hazard mitigations e verification results
- accumulare documenti senza una struttura logica

---

## Best practice

- organizzare le evidence per claim o per requirement critico
- mantenere riferimenti chiari a baseline e versioni
- assicurare tracciabilità tra evidence, risk e verification
- riesaminare la validità delle evidence dopo ogni change rilevante
- trattare le evidence come parte attiva della governance tecnica

---

## Collegamenti

Questa pagina è collegata a:

- Hazard Analysis
- Verification Matrix
- Configuration Audit
- Risk Register
- Dependability