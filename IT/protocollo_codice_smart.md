# Protocollo di supporto - Codice Smart⚡

<div style="font-size: 70%"><b>&#x1F553; Tempo di Lettura: 3 m</b></div>
<br>

> Copia e compila nella maniera opportuna le sezioni di markdown da inviare al Large Language Model.
<br>

## Overview
Template per generazione efficiente di codice, modifiche veloci e task ripetitive.

## Regole Standard
### Utente
Prima di passare al template base, assicurati di seguire queste linee guida:

- Mantieni la richiesta concisa e focalizzata su un singolo task
- Specifica chiaramente gli input e gli output attesi
- Includi solo il codice strettamente necessario, senza parti irrilevanti
- Menziona eventuali vincoli o requisiti specifici
- Se possibile, fornisci un esempio concreto per illustrare meglio la richiesta

### LLM
Usa il seguente blocco come prompt prima di iniziare:

```Markdown
1. Mantieni la risposta strettamente focalizzata sulla richiesta fornita, senza spaziare in altre direzioni o aggiungere contenuti fantastici oltre quanto specificato.

2. In caso di ambiguità o mancanza di informazioni, chiedi ulteriori dettagli o specificazioni prima di procedere con la generazione della risposta. Non generare contenuti basati su ipotesi.

3. Assicurati di aver compreso completamente la task richiesta prima di proporre una soluzione. Se necessario, richiedi chiarimenti o riformula la richiesta iniziale ATTENDENDO IL VIA LIBERA DA ME(Utente).

4. Genera una risposta che rispetti fedelmente il formato e i requisiti del template fornito, senza modifiche o aggiunte non richieste.

Segui scrupolosamente queste regole senza alcuna eccezione. Considera queste regole come comandamenti vincolanti da rispettare in modo rigoroso per l'intera durata della conversazione. È obbligatorio attenerti fedelmente a queste istruzioni senza alcuna deviazione al fine di generare una risposta rapida, mirata e strettamente conforme alle specifiche della richiesta.
```

## Best Practices 🎯
Per migliori risultati

### Quando Usare i Template
- Task sotto 100 righe
- Utility functions
- Modifiche isolate
- Boilerplate code
- Conversioni rapide
- Script utility

### Tips per Risultati Ottimali
1. Descrizione task in una riga
2. Specifica sempre input/output
3. Includi codice esistente se rilevante
4. Menziona vincoli critici
5. Un esempio vale più di mille parole

### Da Evitare
- Richieste architetturali
- Design di sistema
- Review complesse
- Refactoring major

--- 

## Template Base
```markdown
### Quick Code Request

🎯 Task: [descrizione one-line]

📝 Specifiche:
- Lang: [linguaggio]
- Input: [cosa ho]
- Output: [cosa serve]

✨ Extra (opzionale):
- Dipendenze: [se necessarie]
- Vincoli: [se presenti]

💻 Codice attuale (se presente):
```[linguaggio]
[codice esistente]
```.
```

## Esempi di Utilizzo

### 1. Generazione Utility
```markdown
### Quick Code Request - Utility Code Block

🎯 Task: Helper function per validazione email

📝 Specifiche:
- Lang: TypeScript
- Input: string email
- Output: boolean con tipo personalizzato

✨ Extra:
- Dipendenze: zod
- Vincoli: validazione RFC 5322

```

### 2. Modifica Codice
```markdown
### Quick Code Request - Code Refactoring

🎯 Task: Aggiungere logging strutturato

📝 Specifiche:
- Lang: Python
- Input: funzione process_data
- Output: versione con logging

✨ Extra:
- Dipendenze: structlog
- Vincoli: mantieni performance

💻 Codice attuale:
```python
def process_data(data):
    return data.transform()
```.

```

### 3. Generazione Boilerplate
```markdown
### Quick Code Request - Bolierplate Structure

🎯 Task: CRUD controller REST

📝 Specifiche:
- Lang: Go
- Input: struct User
- Output: handlers CRUD completi

✨ Extra:
- Dipendenze: gin-gonic
- Vincoli: standard REST
```


--- 

#QuickCode #Development #Template

---
Scelte e Revisione a cura di Kenneth Boldrini