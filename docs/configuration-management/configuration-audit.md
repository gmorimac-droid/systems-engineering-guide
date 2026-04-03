# Configuration Audit

## Scopo

Descrivere il ruolo del configuration audit nel verificare che la configurazione del sistema e dei suoi artefatti sia completa, coerente e conforme allo stato approvato.

---

## Contesto

Avere configuration items, baseline e change control non è sufficiente se non esiste un meccanismo per verificare che ciò che è dichiarato corrisponda a ciò che è realmente presente e utilizzato.

Il configuration audit serve proprio a controllare:

- coerenza
- completezza
- conformità
- tracciabilità

---

## Definizione

Il configuration audit è una verifica sistematica della configurazione del sistema o degli artefatti, eseguita per accertare che:

- i CI corretti siano presenti
- le versioni siano quelle approvate
- le modifiche siano state controllate
- gli artefatti collegati siano allineati
- lo stato dichiarato sia effettivamente reale

---

## Tipi di audit

### Functional Configuration Audit (FCA)
Verifica che gli artefatti e le evidenze dimostrino la conformità funzionale ai requisiti.

### Physical Configuration Audit (PCA)
Verifica che la configurazione fisica o implementativa corrisponda a quanto approvato e documentato.

In molti contesti documentali o digitali, questi concetti possono essere adattati anche a modelli, documenti e baseline software-intensive.

---

## Obiettivi dell’audit

L’audit serve a:

- rilevare incoerenze di configurazione
- confermare la validità di una baseline
- supportare milestone, review e acceptance
- dimostrare auditabilità del progetto
- ridurre il rischio di verification su configurazioni errate

---

## Esempi di controlli

Un configuration audit può verificare, ad esempio, che:

- la Requirement Specification sia alla versione corretta
- la RTM sia coerente con i requisiti approvati
- la Verification Matrix riferisca la baseline corretta
- gli ICD usati in integrazione siano allineati all’architettura corrente
- i change approvati siano stati realmente incorporati

---

## Attività del System Engineer

- contribuire a definire lo scope dell’audit
- verificare coerenza tra artefatti tecnici
- supportare la raccolta delle evidenze
- analizzare le non conformità rilevate
- assicurare che le azioni correttive rientrino nel sistema di change control

---

## Esempio di Audit Findings Log

| Finding ID | Oggetto | Descrizione | Severità | Azione richiesta |
|------------|---------|-------------|----------|------------------|
| AUD-001 | RTM | REQ-004 non collegato a test case | Alta | Aggiornare Verification Matrix |
| AUD-002 | ICD IF-003 | Versione ICD non allineata alla baseline architetturale | Media | Riesaminare baseline e aggiornare riferimento |

---

## Errori comuni

- considerare l’audit come mera formalità
- eseguire audit troppo tardi
- non definire chiaramente lo scope
- non registrare le non conformità
- non collegare gli esiti dell’audit al change control

---

## Best practice

- pianificare audit in corrispondenza delle milestone principali
- definire scope e criteri in modo chiaro
- verificare sia contenuto sia coerenza tra artefatti
- registrare findings e action items
- usare l’audit come strumento di miglioramento, non solo di controllo

---

## Collegamenti

Questa pagina è collegata a:

- Configuration Items
- Baseline
- Change Control
- Verification Matrix
- Risk Register

Il configuration audit è il meccanismo che conferma che la configurazione dichiarata sia davvero quella in uso.