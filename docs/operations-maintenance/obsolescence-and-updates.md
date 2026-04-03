# Obsolescence and Updates

## Scopo

Descrivere come gestire l’obsolescenza del sistema e i suoi aggiornamenti nel tempo, preservandone capacità, coerenza e sostenibilità operativa.

---

## Contesto

Ogni sistema, nel tempo, è soggetto a cambiamenti e pressioni evolutive, ad esempio:

- componenti non più disponibili
- dipendenze software non supportate
- nuovi requisiti operativi
- cambi normativi
- vulnerabilità o limiti emersi in esercizio

Ignorare obsolescenza e aggiornamenti significa compromettere progressivamente supportabilità, sicurezza, costo e disponibilità del sistema.

---

## Obsolescenza

L’obsolescenza riguarda la perdita di adeguatezza o disponibilità di elementi del sistema nel tempo.

Può riguardare:

- componenti hardware
- software e librerie
- protocolli
- strumenti di supporto
- interfacce
- competenze o processi

---

## Updates

Gli aggiornamenti possono essere necessari per:

- correggere difetti
- migliorare performance o supportabilità
- introdurre nuove capacità
- ripristinare conformità
- sostituire elementi obsoleti
- ridurre rischio operativo o tecnico

---

## Obiettivi della gestione di obsolescenza e aggiornamenti

- mantenere la capacità operativa del sistema
- ridurre il rischio di degradazione nel tempo
- controllare l’impatto dei cambiamenti
- preservare coerenza tra configurazione, architecture e verification
- supportare la sostenibilità del sistema nel lungo periodo

---

## Attività del System Engineer

- identificare elementi a rischio di obsolescenza
- valutare impatti degli aggiornamenti
- collegare update e change control
- supportare decisioni tra sostituzione, retrofit o re-design
- assicurare che gli update restino coerenti con requirements e verification

---

## Esempio di obsolescence log

| OBS ID | Elemento | Rischio | Impatto | Azione proposta | Stato |
|--------|----------|---------|---------|-----------------|------|
| OBS-001 | Libreria SW X | Fine supporto vendor | Alto | Sostituzione controllata con versione supportata | Open |
| OBS-002 | Modulo HW Y | Non più disponibile | Medio | Qualifica sostituto | In Review |

---

## Relazione con il lifecycle

La gestione di obsolescenza e aggiornamenti si collega a:

- maintenance
- supportability
- configuration management
- risk management
- verification regression
- operations feedback

---

## Errori comuni

- considerare l’obsolescenza solo quando il problema è già critico
- aggiornare senza impact analysis
- non rieseguire verification rilevante dopo update
- non mantenere traccia di dipendenze e versioni
- non coinvolgere operation e maintenance nelle decisioni

---

## Best practice

- monitorare proattivamente componenti e dipendenze critiche
- collegare gli aggiornamenti al change control
- valutare sempre rischio residuo e impatto operativo
- pianificare regression verification quando necessaria
- trattare obsolescenza e aggiornamenti come parte normale della vita del sistema

---

## Collegamenti

Questa pagina è collegata a:

- Maintenance Concept
- Supportability
- Configuration Management
- Risk Management
- Verification & Validation