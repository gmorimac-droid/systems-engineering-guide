# Test Levels

## Scopo

Descrivere i principali livelli di test nel Systems Engineering e chiarire come la verifica si distribuisce progressivamente dai componenti al sistema completo.

---

## Contesto

La verification non avviene in un unico momento finale.  
Deve essere distribuita su diversi livelli, in modo coerente con:

- decomposizione del sistema
- architettura
- strategia di integrazione
- criticità dei requisiti

Ogni test level ha obiettivi, scope e criteri di successo differenti.

---

## Principali livelli di test

I livelli più comuni sono:

- Component / Unit Level
- Subsystem Level
- Integration Level
- System Level
- Acceptance / Validation-Oriented Level

---

## Component / Unit Level

### Obiettivo
Verificare che un singolo elemento o componente soddisfi i requisiti di dettaglio assegnati.

### Focus
- logica locale
- funzioni di dettaglio
- comportamento isolato
- correttezza di implementazione

### Esempio
verifica del corretto funzionamento del modulo di validazione input

---

## Subsystem Level

### Obiettivo
Verificare che un sottosistema composto da più elementi cooperi correttamente.

### Focus
- coerenza interna del sottosistema
- interazioni tra componenti locali
- primi aspetti di integrazione

### Esempio
verifica del sottosistema di elaborazione richieste

---

## Integration Level

### Obiettivo
Verificare che elementi o sottosistemi distinti interagiscano correttamente attraverso le interfacce definite.

### Focus
- compatibilità
- protocolli
- timing
- sequencing
- comportamenti emergenti all’interfaccia

### Esempio
verifica della comunicazione tra processing engine e notification module

---

## System Level

### Obiettivo
Verificare che il sistema completo soddisfi i requisiti di sistema.

### Focus
- requisiti end-to-end
- comportamento complessivo
- prestazioni globali
- conformità sistemica

### Esempio
verifica del tempo di risposta complessivo del sistema sotto carico operativo

---

## Acceptance / Validation-Oriented Level

### Obiettivo
Dimostrare che il sistema è accettabile rispetto a criteri di uso reale o contrattuali.

### Focus
- scenari operativi
- user perspective
- mission effectiveness
- contesto reale o rappresentativo

### Esempio
sessione di user acceptance o evaluation in scenario operativo

---

## Relazione tra i livelli

I test levels non sono indipendenti: si supportano a vicenda.

Una strategia corretta prevede che:

- i livelli bassi intercettino errori locali
- i livelli intermedi rivelino problemi di integrazione
- i livelli alti confermino la conformità complessiva
- acceptance e validation confermino l’adeguatezza del sistema

---

## Attività del System Engineer

- definire quali requisiti si verificano a quale livello
- collegare test levels e architecture
- coordinare integration strategy e verification strategy
- assicurare che esista copertura coerente tra livelli
- evitare sovrapposizioni inutili o gap di verifica

---

## Errori comuni

- concentrare tutta la verifica al system level
- non verificare presto le interfacce
- non definire responsabilità per i diversi livelli
- duplicare test senza aggiungere valore
- non collegare test level e requisito

---

## Best practice

- distribuire la verifica lungo la decomposizione del sistema
- verificare le interfacce ai livelli corretti
- collegare test levels a architecture e integration plan
- usare il livello più adatto per intercettare il problema prima possibile
- mantenere tracciabilità tra requisito, livello e evidenza

---

## Collegamenti

Questa pagina è collegata a:

- Architecture
- Integration Strategy
- Verification Matrix
- Verification vs Validation