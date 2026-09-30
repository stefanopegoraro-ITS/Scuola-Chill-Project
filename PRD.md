## INFORMAZIONI SUL DOCUMENTO

|                       |                    |
| --------------------- | ------------------ |
| **Prodotto**          | ScuolaChill        |
| **Autori**            | _Pegoraro Stefano_ |
| **Versione**          | _1.0_              |
| **Data di Creazione** | _21/09/2026_       |
| **Stato**             | _Bozza_            |

## STORICO VERSIONI

| Versione | Data         | Autore             | Cosa è cambiato e perché |
| -------- | ------------ | ------------------ | ------------------------ |
| 1.0      | _21/09/2026_ | _Pegoraro Stefano_ | Prima stesura            |
|          |              |                    |                          |

## PERCHÉ ESISTE SCUOLACHILL

#### Lato Business: permette di organizzare la scuola in modo completo, gestendo dove sono le classi in una specifica ora, poter gestire le assenze di una classe, i voti, la cronologia

 #### Non è inlcuso: avvisi per le famiglie?, Account per i Genitori?

## TIPO DI SCUOLA

|  | Valore |
| --- | --- |
| Numero di studenti | *500* |
| Numero di docenti | *12-15* |
| Numero di classi | *20* |
| Orario scolastico | *8:00 – 14:00, dal lunedì al venerdì* |
| Connettività | *rete mobile* |

## Direttore

### User Story 1

Il Direttore ha la possibilità di organizzare l'orario e la posizione delle classi, con layout a drop down (poi da vedere lo stile, avevo pensato a una planimetria della scuola semplificata) con la possibiltà di creare l'orario per tutto l'anno scolastico (dove puoi vedere esattamente in che aula sono le classi in quell'ora), e in caso di bisogno modificare l'orario o la posizione delle classi per una specifica ora (inviando anche una notifica agli studenti e docenti in caso di variazione)

### User Story 2

Il Direttore ha la possibilità di decidere dove devono essere i Docenti e in che orario devono essere presenti a Lezioni, inviandogli anche un messaggio di promemoria

### User Story 3

Il Direttore può interagire con tutte le assenze, note, voti

## Docenti

### User Story 1

Il Docente può segnalare, con il bottone apposito, se uno studente è assente o meno

### User Story 2

Il Docente ha una sezione apposita per mettere le annotazioni (inviando anche una notifica allo studente)

### User Story 3

Il Docente ha una sezione apposita per mettere i voti (inviando anche una notifica allo studente)

## Studenti

### User Story 1

Lo Studente ha la possibilità di poter guardare i suoi voti con anche la media di quei voti

### User Story 2

Lo Studente ha la possibilità di guardare le prossime lezioni e i propri compiti sul calendario

### User Story 3

Lo studente ha la possibilità di vedere le comunicazioni di servizio nella sezione delle notifiche importanti

## REQUISITI NON FUNZIONALI

| ID | Famiglia | Requisito | Soglia e condizione | Come si verifica | Storie collegate |
| --- | --- | --- | --- | --- | --- |
| NFR-01 | Prestazioni | *es. Apertura della verifica nel picco* | *es. meno di 2 s per il 95% delle richieste, 75 utenti nello stesso minuto* | *Test di carico* | *STU-02* |
| NFR-02 | Sicurezza | *Il software ha bisogno di una pagina di login* | *se qualcuno prova ad accedere l'app senza aver fatto il login la prima cosa che spunta è la pagina di login* | *provando a entrare nell'app senza eseguire l'accesso* | *…* |
| NFR-03 | Usabilità | *…* | *…* | *…* | *…* |
| NFR-04 | Disponibilità | *…* | *…* | *…* | *…* |
| NFR-05 | Ambientale | *…* | *…* | *…* | *…* |
| NFR-06 | Supporto | *…* | *…* | *…* | *…* |
| NFR-07 | Interazione | *…* | *…* | *…* | *…* |
| NFR-08 | Conformità | *…* | *…* | *…* | *…* |


## STAKEHOLDER

| Stakeholder                 | Cosa fa                             | Cosa gli interessa | Come lo coinvolgete     |
| --------------------------- | ----------------------------------- | ------------------ | ----------------------- |
| Direttore                   | _…_                                 | _…_                | _…_                     |
| Docenti                     | _…_                                 | _…_                | _…_                     |
| Studenti                    | _…_                                 | _…_                | _…_                     |
| Docente del corso           | Valida il PRD                       | _…_                | Presentazione e domande |
| Collaudatori del primo anno | Usano ScuolaChill come utenti reali | _…_                | _Intervista, collaudo_  |
| _Altri?_                    |                                     |                    |                         |

## Scelte tecnologiche

| Area             | Scelta | Alternativa considerata | Perché avete scelto così |
| ---------------- | ------ | ----------------------- | ------------------------ |
| Backend          | C# (Asp.Net )    | _…_                     | _…_                      |
| Frontend         | React?    | _…_                     | _…_                      |
| Database         | _…_    | _…_                     | _…_                      |
| Provider cloud   | _…_    | _…_                     | _…_                      |
| Servizi cloud    | _…_    | _…_                     | _…_                      |
| Regione          | _…_    | _…_                     | _…_                      |
| Servizio esterno | _…_    | _…_                     | _…_                      |
