# Configuration Items

## Scopo

Descrivere cosa sono i Configuration Items (CI) e come identificarli nel contesto del Systems Engineering.

---

## Contesto

Non tutto ciò che esiste in un progetto deve essere necessariamente controllato come configuration item.

I configuration items sono quegli elementi del sistema o del progetto che devono essere identificati, versionati e controllati in modo formale perché influenzano la definizione, l’implementazione, l’integrazione o la verification del sistema.

---

## Definizione

Un Configuration Item (CI) è un elemento selezionato per essere gestito sotto controllo di configurazione.

Un CI può essere:

- un documento
- un requisito baselined
- un elemento architetturale
- un componente hardware
- un modulo software
- un ICD
- un modello MBSE
- un test artifact
- una baseline stessa

---

## Criteri di identificazione di un CI

Un elemento dovrebbe essere considerato CI se:

- ha impatto sul comportamento del sistema
- influenza requisiti, architettura o verification
- richiede tracciabilità nel tempo
- deve essere soggetto a change control
- deve essere richiamabile in audit o review

---

## Esempi tipici di CI

### Artefatti documentali
- Requirement Specification
- Architecture Description
- Interface Control Document
- Verification Matrix
- Test Plan

### Elementi tecnici
- componenti hardware
- moduli software
- modelli di sistema
- dataset o configurazioni operative

### Elementi di supporto alla verification
- test procedures
- test scripts
- ambienti di test definiti
- risultati baselined

---

## Configuration Item List

Una CI list può includere:

| CI ID | Nome | Tipo | Versione | Owner | Stato |
|------|------|------|----------|-------|------|
| CI-001 | System Requirements Specification | Documento | v1.0 | System Engineer | Baselined |
| CI-002 | Architecture Description | Documento | v1.0 | Architect | Baselined |
| CI-003 | IF-001 ICD | ICD | v0.9 | Integration Lead | Draft |
| CI-004 | Verification Matrix | Documento | v0.7 | V&V Lead | In Review |

---

## Attività del System Engineer

- contribuire alla definizione della CI list
- identificare gli artefatti critici che devono essere controllati
- chiarire relazioni tra CI e lifecycle
- assicurare che i CI siano coerenti con RTM, architecture e verification
- supportare l’analisi di impatto quando un CI cambia

---

## Errori comuni

- trattare come CI troppi elementi senza criterio
- non porre sotto configurazione artefatti critici
- non assegnare owner ai CI
- non mantenere la CI list aggiornata
- non collegare i CI alle baseline e ai change

---

## Best practice

- identificare i CI in base al loro impatto sul sistema
- assegnare ID e ownership chiari
- mantenere la CI list semplice ma completa
- distinguere draft, in review e baselined
- collegare i CI alla struttura architetturale e documentale del progetto

---

## Collegamenti

Questa pagina è collegata a:

- Baseline
- Change Control
- Architecture
- Requirements Engineering
- Verification & Validation