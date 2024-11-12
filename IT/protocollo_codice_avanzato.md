# Protocollo di supporto - Codice Avanzato🎛️
 
<div style="font-size: 70%"><b>&#x1F553; Tempo di Lettura: 5 m</b></div>

> Copia e compila nella maniera opportuna le sezioni di markdown da inviare al Large Language Model.

## Overview
Template per generazione efficiente di codice tramite, query strutturate e modifiche avanzate.

## Indice
- [Template per Debugging](#Template-per-Debugging)
- [Template per Code Review](#Template-per-Review)
- [Template per Ottimizzazione](#Template-per-Ottimizzazione)
- [Template per Testing](#Template-per-Testing)
- [Template per Documentazione](#Template-per-Documentazione)

## Procedura Standard

### Utente
Prima di passare al template base, assicurati di seguire queste linee guida:

- Mantieni la richiesta concisa e focalizzata su un singolo macro task
- Specifica chiaramente gli input e gli output attesi
- Includi solo il codice strettamente necessario, senza parti irrilevanti
- Menziona eventuali vincoli o requisiti specifici
- Se possibile, fornisci un esempio concreto per illustrare meglio la richiesta

### LLM

>Prima di ogni sessione manda questo al tuo LLM

```Markdown
1. Mantieni la risposta strettamente focalizzata sulla richiesta fornita, senza spaziare in altre direzioni. E' possibile aggiungere contenuti metodi di risoluzione creativi oltre quanto specificato solo nella sezione: 📈 Apertura a suggerimenti di miglioramento oltre le specifiche.

2. In caso di ambiguità o mancanza di informazioni, chiedi ulteriori dettagli o specificazioni prima di procedere con la generazione della risposta. Non generare contenuti basati su ipotesi.

3. Assicurati di aver compreso completamente la task richiesta prima di proporre una soluzione. Se necessario, richiedi chiarimenti o riformula la richiesta iniziale ATTENDENDO IL VIA LIBERA DALL' UTENTE (Me).

4. Genera una risposta che rispetti fedelmente il formato e i requisiti del template fornito, senza modifiche o aggiunte non richieste.

Segui scrupolosamente queste regole senza alcuna eccezione. Considera queste regole come comandamenti vincolanti da rispettare in modo rigoroso per l'intera durata della conversazione. È obbligatorio attenerti fedelmente a queste istruzioni senza alcuna deviazione al fine di generare una risposta rapida, mirata e strettamente conforme alle specifiche della richiesta.
```

## Best Practices 🎯
Per migliori risultati

### Tips per Risultati Ottimali
1. Descrizione task in una riga
2. Specifica sempre input/output
3. Includi codice esistente se rilevante
4. Menziona vincoli critici
5. Un esempio vale più di mille parole
6. Task sotto 100 righe o porzioni di codice limitato

### Da Evitare
- Richieste architetturali estensive
- Design di sistema estensivi
- Review complesse
- Refactoring major

--- 
## Template per Debugging

###### Best Practices 🎓
Quando Usare Ogni Template

- Problemi in produzione
- Performance issues
- Memory leaks
- Race conditions



```markdown
### Debug Request

🔍 Descrizione Problema:
[descrizione dettagliata]

⚠️ Comportamento Attuale:
[cosa sta succedendo]

✅ Comportamento Atteso:
[cosa dovrebbe succedere]

💻 Codice Problematico:
``'[linguaggio]
[codice]
``'

📋 Log Errori:
``'
[log]
``'

🛠️ Ambiente (Opzionale):
- OS: [sistema operativo]
- Versione: [versione linguaggio/framework]
- Dipendenze: [dipendenze rilevanti]

📊 Metriche Rilevanti (Opzionale):
- Performance: [metriche]
- Risorse: [utilizzo]
- Frequenza: [occorrenza]

📈 Apertura a suggerimenti di miglioramento oltre le specifiche:
- [ ] Si
- [ ] No
```


## Template per Code Review

###### Best Practices 🎓
Quando Usare Ogni Template

- Pull requests
- Design review
- Security audit
- Architecture validation

```markdown
### Review Request

📦 Contesto Progetto:
- Repo: [repository]
- Branch: [branch]
- Scope: [ambito]

💻 Codice da Revisionare:
``'[linguaggio]
[codice]
``'

🎯 Focus Review: (- [X] Esempio Focus argomento attivo)
- [ ] Architettura
- [ ] Performance
- [ ] Sicurezza
- [ ] Manutenibilità
- [ ] Test Coverage
- [ ] ...

📋 Standard da Verificare:
1. [standard 1]
2. [standard 2]
3. [standard 3]
4. ...

📈 Apertura a suggerimenti di miglioramento oltre le specifiche:
- [ ] Si
- [ ] No
```

## Template per Ottimizzazione

###### Best Practices 🎓
Quando Usare Ogni Template

- Performance tuning
- Resource optimization
- Scalability improvements
- Cost optimization

```markdown
### Optimization Request

📊 Metriche Attuali:
- Latenza: [tempo]
- Memoria: [utilizzo]
- CPU: [utilizzo]
- Throughput: [operazioni/sec]

💻 Codice Target:
``'[linguaggio]
[codice]
``'

🎯 Obiettivi:
1. [obiettivo 1 con metrica]
2. [obiettivo 2 con metrica]

⚠️ Vincoli:
- Budget risorse
- Backward compatibility
- SLA da mantenere

🔍 Profiling:
- Bottlenecks identificati
- Hot paths
- Resource leaks

📈 Apertura a suggerimenti di miglioramento oltre le specifiche:
- [ ] Si
- [ ] No
```

## Template per Testing

###### Best Practices 🎓
Quando Usare Ogni Template

- New features
- Refactoring
- Critical paths
- Integration points

```markdown
### Testing Request

🎯 Scope Testing:
- [ ] Unit Tests
- [ ] Integration Tests
- [ ] E2E Tests
- [ ] Performance Tests
- [ ] Security Tests

💻 Codice da Testare:
``'[linguaggio]
[codice]
``'

📋 Scenari Test:
1. Happy path:
   - [scenario 1]
   - [scenario 2]

2. Edge cases:
   - [case 1]
   - [case 2]

3. Error cases:
   - [error 1]
   - [error 2]

🔧 Setup Richiesto:
- Ambiente
- Mock/Stub
- Fixtures
- Tools

📊 Coverage Target:
- Statements: [%]
- Branches: [%]
- Functions: [%]

📈 Apertura a suggerimenti di miglioramento oltre le specifiche:
- [ ] Si
- [ ] No
```

## Template per Documentazione

###### Best Practices 🎓
Quando Usare Ogni Template

- New services
- Major changes
- Complex systems
- Critical processes

```markdown
### Documentation Request

📚 Tipo Documentazione:
- [ ] Technical Spec
- [ ] API Reference
- [ ] Implementation Guide
- [ ] Architecture Doc
- [ ] Runbook

💻 Sistema/Componente:
[descrizione componente]

👥 Target Audience:
- [audience 1]
- [audience 2]

📋 Sezioni Richieste:
1. Overview
   - Contesto
   - Obiettivi
   - Scope

2. Architettura
   - Componenti
   - Flussi
   - Integrazioni

3. Implementazione
   - Setup
   - Configurazione
   - Deployment

4. Operazioni
   - Monitoring
   - Troubleshooting
   - Disaster Recovery

📈 Apertura a suggerimenti di miglioramento oltre le specifiche:
- [ ] Si
- [ ] No
```

---

#Engineering #Development #BestPractices #Documentation

---
Scelte e Revisione a cura di Kenneth Boldrini