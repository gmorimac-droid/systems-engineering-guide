# Qualità dei requisiti

## Scopo

Definire i criteri che un requisito deve soddisfare per essere considerato **corretto, utilizzabile e verificabile** all’interno di un processo di Systems Engineering.

La qualità dei requisiti è fondamentale per garantire:

- coerenza del sistema
- efficacia della verifica e validazione
- riduzione dei rischi di integrazione
- controllo delle modifiche

---

## Contesto

I requisiti rappresentano il collegamento tra:

- bisogni degli stakeholder
- architettura del sistema
- attività di verifica e validazione

Requisiti di bassa qualità introducono ambiguità, errori di implementazione e costi elevati nelle fasi successive del lifecycle.

---

## Concetti chiave

### Requisito

Un requisito è una dichiarazione che descrive una capacità, una condizione o un vincolo che il sistema deve soddisfare.

### Qualità del requisito

La qualità di un requisito è determinata dalla sua capacità di essere:

- compreso senza ambiguità
- implementato correttamente
- verificato in modo oggettivo
- tracciato lungo il lifecycle

---

## Caratteristiche di un buon requisito

Un requisito di qualità deve soddisfare i seguenti attributi.

### 1. Corretto (Correct)

Il requisito riflette fedelmente un bisogno reale o un vincolo valido.

### 2. Non ambiguo (Unambiguous)

Il requisito ha una sola interpretazione possibile.

❌ Esempio:
> Il sistema deve essere veloce

✅ Migliore:
> Il sistema deve rispondere entro 200 ms nel 95% dei casi

---

### 3. Completo (Complete)

Il requisito contiene tutte le informazioni necessarie per essere compreso e implementato.

---

### 4. Verificabile (Verifiable)

È possibile dimostrare in modo oggettivo che il requisito è soddisfatto.

Ogni requisito dovrebbe avere almeno un metodo di verifica associato:

- test
- analisi
- ispezione
- dimostrazione

---

### 5. Consistente (Consistent)

Non è in conflitto con altri requisiti.

---

### 6. Realizzabile (Feasible)

Può essere implementato entro i vincoli tecnici, economici e temporali.

---

### 7. Necessario (Necessary)

Esiste una ragione chiara per la sua presenza.

Ogni requisito dovrebbe avere una **fonte** (stakeholder, normativa, bisogno operativo).

---

### 8. Tracciabile (Traceable)

Può essere collegato a:

- un need
- altri requisiti
- elementi architetturali
- attività di verifica

---

### 9. Atomico (Atomic)

Il requisito esprime una singola idea.

❌ Errato:
> Il sistema deve essere sicuro e veloce

---

### 10. Indipendente dalla soluzione (Solution-free)

Il requisito descrive il **cosa**, non il **come**.

❌ Errato:
> Il sistema deve usare un database SQL

✅ Corretto:
> Il sistema deve memorizzare i dati in modo persistente e recuperabile

---

## Struttura di un requisito

Una struttura tipica e raccomandata è:

Esempio:

---

## Attività del System Engineer

Il System Engineer ha un ruolo chiave nella qualità dei requisiti:

- definire linee guida di scrittura
- effettuare review strutturate
- verificare coerenza e completezza
- garantire tracciabilità
- supportare la decomposizione
- gestire conflitti e ambiguità

---

## Input

- stakeholder needs
- contesto operativo
- vincoli tecnici e normativi
- missione del sistema

---

## Output

- set di requisiti di qualità
- requirement specification
- baseline dei requisiti
- collegamenti di tracciabilità

---

## Artefatti

- requirement specification document
- requirement database (es. DOORS, Jama)
- checklist di qualità
- review report
- traceability matrix (RTM)

---

## Errori comuni

### 1. Ambiguità linguistica
Uso di termini come:
- veloce
- robusto
- efficiente

### 2. Requisiti non verificabili
Mancanza di criteri misurabili.

### 3. Requisiti duplicati o inconsistenti

### 4. Mescolare requisito e soluzione

### 5. Mancanza di tracciabilità

### 6. Requisiti troppo complessi
Un requisito che contiene più condizioni.

---

## Best practice

- usare un linguaggio controllato
- evitare aggettivi non misurabili
- definire unità di misura
- associare sempre un metodo di verifica
- mantenere un identificativo univoco
- collegare ogni requisito a una fonte
- usare checklist di qualità nelle review
- mantenere aggiornati i requisiti durante il lifecycle

---

## Checklist di qualità (pratica)

Un requisito è accettabile se:

- [ ] è chiaro e non ambiguo
- [ ] è verificabile
- [ ] è atomico
- [ ] è coerente con gli altri
- [ ] è tracciabile
- [ ] è indipendente dalla soluzione
- [ ] ha una fonte definita

---

## Collegamenti

Questa sezione è direttamente collegata a:

- Requirements Engineering
- Traceability
- System Architecture
- Verification & Validation
- Configuration Management

La qualità dei requisiti influenza tutte le fasi successive del lifecycle.

## Collegamento operativo

I requisiti definiti qui sono utilizzati in:

- Tracciabilità (RTM)
- Verification Matrix
- Change Management