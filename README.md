# cadeaux-reference
  come avere un riferimento per la redazione di un documento di analisi dei requisiti? Basta copiare. Un ottimo punto di partenza è costituito dalla documentazione dei comandi. Ad esempio, digita `man grep` e osserva il risultato. Di seguito trovi un riferimento che puoi personalizzare per le tue esigenze.

## Nome
*cadeaux-reference*, riferimento di esempio per i progetti cadeaux classe 4BINF AS1415
  
## Sintassi
    cadeaux-reference [opzioni] <lista_studenti> <progetto> <directory_studenti>
  
## Descrizione
Nella sezione "nome" troviamo la descrizione sintetica (una riga) di ciò che lo script fa. In questa sezione
riportiamo, invece, una descrizione più approfondita.
  
I parametri forniti nella sintassi si distinguono tra opzionali (tra paresentesi quadre) e obbligatori.
È opportuno assegnare un nome chiaro e rappresentativo del ruolo, almeno ai parametri obbligatori.
  
Ad essere precisi, un documento di Analisi dei Requisiti (AdR) è diverso da un manuale utente (MU). Entrambi adottano il punto di vista dell'utente, descrivendo il comportamento del sistema secondo quanto esso si aspetta. Il documento AdR aggiunge l'analisi, cioè una discussione sulla coerenza e sulla fattibilità delle richieste dell'utente. Se in generale AdR e MU sono distnti, nel nostro caso vengono a coincidere, in quanto non è necessario discutere i requisiti,  ma solo documentarli.
  
## Input
### Organizzazione directory studenti
Lo script assume che tutti i progetti degli studenti siano memorizzati in un'unica directory (`<directory_studenti>`). In essa, ogni studente ha la propria directory, col nome del proprio account GitHub. Dentro la directory dello studente, si trovano tante directory quanti sono i progetti, col nome relativo.
```
<directory_studenti>
 |-<github_username_studente1>
 |   |-<progetto1>
 |   |-<progetto2>
 |   |-...
 |   |-<progettoN>
 ...
 |-<github_username_studenteM>
     |-<progetto1>
     |-<progetto2>
     |-...
     |-<progettoN>```

### [opzioni]

### <lista_studenti>

### <Progetto>
## Output
