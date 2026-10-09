## INFORMAZIONI SUL DOCUMENTO

|                       |                    |
| --------------------- | ------------------ |
| **Prodotto**          | _ScuolaChill_      |
| **Autori**            | _Pegoraro Stefano_ |
| **Versione**          | _1.0_              |
| **Data di Creazione** | _21/09/2026_       |
| **Stato**             | _Bozza_            |

## STORICO VERSIONI

| Versione | Data         | Autore             | Cosa è cambiato e perché |
| -------- | ------------ | ------------------ | ------------------------ |
| 1.0      | _21/09/2026_ | _Pegoraro Stefano_ | _Prima stesura_          |
|          |              |                    |                          |

## PERCHÉ ESISTE SCUOLACHILL

#### Lato Business: permette di organizzare la scuola in modo completo, gestendo dove sono le classi in una specifica ora, poter gestire le assenze di una classe, i voti, i materiali da dare agli studenti, avvisi importanti ecc.

#### Non è inlcuso: Account per i Genitori, Svolgimento di verifiche All'interno del Software

## TIPO DI SCUOLA

|                    | Valore                                |
| ------------------ | ------------------------------------- |
| Numero di studenti | _500_                                 |
| Numero di docenti  | _12-15_                               |
| Numero di classi   | _20_                                  |
| Orario scolastico  | _8:00 – 14:00, dal lunedì al venerdì_ |
| Connettività       | _rete mobile_                         |

## ARCHETIPI

| ID      | Archetipo | Contesto d'uso                                                | Competenze digitali | Dispositivo principale | Frequenza d'uso |
| ------- | --------- | ------------------------------------------------------------- | ------------------- | ---------------------- | --------------- |
| ARC-001 | Direttore | _Poter organizzare come si svolgerà l'intero anno scolastico_ | _Medio-Basse_       | _Computer_             | _Ogni Giorno_   |
| ARC-002 | Docente   | _Fare l'appello/dare compiti_                                 | _Basse_             | _Computer_             | _Ogni Giorno_   |
| ARC-003 | Studente  | _Poter controllare i propri compiti/orari/voti ecc._          | _Medio-Alte_        | _Smartphone_           | _Ogni Giorno_   |

## USER STORY

| ID     | Storia                             | AC aggiunti dal team                                                                                                        | Note                                                                                                     |
| ------ | ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| DIR-01 | Creare account docente             | _La Password deve almeno avere 8 caratteri e gli da i permessi che solo i docenti possono avere_                            | _-_                                                                                                      |
| DIR-02 | Creare account studente            | _La Password deve almeno avere 8 caratteri e gli da i permessi che solo gli studenti possono avere_                         | _-_                                                                                                      |
| DIR-03 | Creare classi e comporle           | _Il Direttore deve avere la possibilità di organizzare l'orario e la posizione delle classi, con layout a drop down_        | _poi da vedere lo stile, avevo pensato a una planimetria della scuola semplificata_                      |
| DIR-04 | Vedere tutto                       | _Poter vedere tutte le classi, tutti i compiti/annotazioni/avvisi che ci sono per classi_                                   | _-_                                                                                                      |
| DIR-05 | Creazione del Calendario dell'anno | _Poter organizzare gli orari e poterli modificare velocemente in caso di imprevisti_                                        | _poter inviare messaggi di promemoria_                                                                   |
| DIR-06 | Eliminazione degli account         | _Poter Eliminare gli account degli studenti e docenti quando necessario_                                                    | _L'eliminazione degli account deve comprendere anche l'eliminazione di tutti i dati presenti su di essi_ |
| DOC-01 | Caricare materiale didattico       | _Un funzionamento simile a google classroom_                                                                                | _Mandare delle notifiche agli studenti quando il docente aggiunge del materiale?_                        |
| DOC-02 | Poter mandare avvisi agli studenti | _poter scrivere delle notifiche generali per gli sutdenti_                                                                  | _-_                                                                                                      |
| DOC-03 | Assegnare i voti                   | _Poter Decidere i voti e modificarli con un menu a cascata_                                                                 | _…_                                                                                                      |
| STU-01 | Consultare il materiale didattico  | _Avere a disposizione un abiente simile a google classroom/drive dove lo studente può visuallizzare il materiale assegnato_ | _-_                                                                                                      |
| STU-02 | Consultare il calendario           | _Avere accesso in qualunque momento al calendario_                                                                          | _Poter vedere i compiti assegnati su quel giorno nel calendario_                                         |
| STU-03 | Consultare i propri voti           | _Avere la possibilità di consultare i propri voti in qualunque momento_                                                     | _con medie ecc._                                                                                         |
| STU-04 | Comunicazioni di servizio          | _Avere una sezione notifiche dove arrivano notifiche dei docenti e comunicazioni di servizio_                               | _-_                                                                                                      |

## USER FLOW

### DIR-01

- Il Direttore Accede a scuolachill
- Apre la sezione Docenti
- Preme Aggiungi Docente

### DIR-02

- Il Direttore Accede a scuolachill
- Apre la sezione Studenti
- Preme Aggiungi Studente

### DIR-03

- Il Direttore Accede a scuolachill
- Apre La Sezione Classi
- Aggiugne all'interno delle classi gli studenti e i docenti per materia

### DIR-04

- Il Direttore Accede a scuolachill
- apre l'overview della scuola
- clicca su una qualsiasi classe dove può vedere tutti gli studenti, i docenti, i materiali assegnati, i voti, ecc.

### DIR-05

- Il Direttore Accede a scuolaChill
- Apre la Sezione Calendario
- Decide gli orari di tutte le classi della scuola

### DIR-06

- Il Direttore Accede a scuolachill
- apre la sezione degli studenti/docenti
- clicca sull'icona del cestino per eliminare l'account

### DOC-01

- Il Docente Accede a scuolachill
- apre la sezione per caricare i materiali agli studenti
- carica il materiale selezionando il file o trascinandolo sopra

### DOC-02

- Il Docente Accede a scuolachill
- Clicca sulla sezione degli avvisi agli studenti
- clicca su manda avviso
- scrive l'avviso da mandare per poi inviarlo

### DOC-03

- Il Docente Accede a scuolachill
- Apre la sezione studenti
- decide lo studente a cui assegnare il voto

### STU-01

- Lo Studente Accede a scuolachill
- apre la sezione materiali assgenati (della materia giusta)
- visualizza i materiali assegnati e li scarica

### STU-02

- Lo Studente Accede a scuolachill
- apre il calendario
- visualizza gli orari della settimana e i compiti assegnati per i giorni

### STU-03

- Lo Studente Accede a scuolachill
- Apre la sezione voti
- visualizza i voti assegnati per le diverse materie

### STU-04

- Lo Studente Accede a scuolachill
- apre la sezione notifiche
- visualizza le tute notifiche

## STAKEHOLDER

| Stakeholder                 | Cosa fa                                                               | Cosa gli interessa                                       | Come lo coinvolgete                        |
| --------------------------- | --------------------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------ |
| Direttore                   | _Usa il Software Organizzare Lezioni_                                 | _Organizzare la scuola con facilità tramite il software_ | _Interviste sulle attività genrali e test_ |
| Docenti                     | _Usano Scuola Chill per fare l'appello assegnare compiti e materiali_ | _facilmente accessibile/veloce/facile da capire_         | _Interviste sulle attività genrali e test_ |
| Studenti                    | _Guardano i compiti assegnati e i voti_                               | _facilmente accessibile in dispositivi mobili_           | _Interviste sulle attività genrali e test_ |
| Docente del corso           | _Valida il PRD_                                                       | _avere un prodotto affidabile_                           | _Presentazione e domande_                  |
| Collaudatori del primo anno | _Usano ScuolaChill come utenti reali_                                 | _trovare eventuali problemi_                             | _Intervista, collaudo_                     |

## REQUISITI NON FUNZIONALI

| ID     | Famiglia                   | Requisito                                                                                                      | Soglia e condizione                                                                                                              | Come si verifica                                                                                       | Storie collegate |
| ------ | -------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------- |
| NFR-01 | Prestazioni                | _Apertura del calendario nel picco_                                                                            | _meno di 2 s per il 95% delle richieste_                                                                                         | _Test di carico_                                                                                       | _STU-02_         |
| NFR-02 | Sicurezza                  | _Il software ha bisogno di una pagina di login_                                                                | _se qualcuno prova ad accedere l'app senza aver fatto il login la prima cosa che spunta è la pagina di login_                    | _provando a entrare nell'app senza eseguire l'accesso_                                                 | _DIR-02/03_      |
| NFR-03 | Usabilità                  | _Renderlo Utilizzabile per il maggior numero di persone possibile anche persone con problematiche particolari_ | _…_                                                                                                                              | _…_                                                                                                    | _…_              |
| NFR-04 | Disponibilità/Affidabilità | _Poter essere accessibile il 99% del tempo, cercando di ridurre le interruzioni per manutenzione al minimo_    | _-_                                                                                                                              | _-_                                                                                                    | _STU-01/02/03_   |
| NFR-06 | Supporto                   | _l'applicazione deve funzionare sia su pc che su smartphone_                                                   | _l'applicazione deve essere visualizzabile sia su pc che su smartphone (magari consentendo la modifica solo su pc)_              | _-_                                                                                                    | _STU-01--DOC-01_ |
| NFR-07 | Interazione                | _il software deve essere facile da capire e responsivo_                                                        | _il software deve avere delle interazioni dove si capisce subito cosa fa una operazione_                                         | _quando si fanno delle operazioni ci sono delle animazioni e nei pulsanti compaiono delle descrizioni_ | _-_              |
| NFR-08 | Conformità                 | _il GDPR per i dati personali (controllare bene Quali sono le legislazioni in questo settore)_                 | _Cancellazione Completa di tutti dati che sono stati salvati nell'account, nel caso in cui uno studente/docente lasci la scuola_ | _Controlli_                                                                                            | _DIR-06_         |

## ASSUNZIONI

| ID     | Assunzione                                            | Cosa succede se è falsa         |
| ------ | ----------------------------------------------------- | ------------------------------- |
| ASS-01 | _La Scuola è formata da 500 studenti e 12-15 Docenti_ | _Il dimensionamento va rifatto_ |
|        |                                                       |                                 |

## VINCOLI

| ID     | Vincolo                                                       | Da dove viene                   |
| ------ | ------------------------------------------------------------- | ------------------------------- |
| VIN-01 | _Grandezza massima del server/dei file caricabili sul server_ | _Fondi per costruire il server_ |
|        |                                                               |                                 |

## DIPENDENZE

| ID     | Dipendenza                                     | Serve entro          | Chi se ne occupa                    |
| ------ | ---------------------------------------------- | -------------------- | ----------------------------------- |
| DIP-01 | _Registrarsi con l'account email della scuola_ | _Prima del collaudo_ | _La persona che deve fare il login_ |
|        |                                                |                      |                                     |

## UTENTI CONCORRENTI

| Situazione                                                                   | Utenti concorrenti | Da dove viene il numero                                                                                        |
| ---------------------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------------------------------- |
| Uso normale durante la giornata                                              | _400~500_          | _ogni giorno i docenti e gli studenti devono usare l'applicazioni per voti o l'utilizzo dei materiali_         |
| Picco delle 7:00-8:00 (L'ora tra l'arrivo a scuola e l'inizio delle lezioni) | _515_              | _Tutti gli studenti e docenti controllano gli orari che hanno il giorno stesso_                                |
| Fine quadrimestre (voti)                                                     | _101_              | _Le pagelle vengono alle classi una per anno (quindi partendo da tutte le prime per poi arrivare alle quinte)_ |

## PROFILO DI CARICO

| Operazione              | Frequente?                      | Pesante?                   | Critica?       | Note                                                                                                  |
| ----------------------- | ------------------------------- | -------------------------- | -------------- | ----------------------------------------------------------------------------------------------------- |
| Login                   | _Solo i primi giorni di scuola_ | _no_                       | _si_           | _-_                                                                                                   |
| Apertura Calendario     | _Molto_                         | _no_                       | _no_           | _-_                                                                                                   |
| Consegna Compiti        | _Abbastanza_                    | _no_                       | _no_           | _-_                                                                                                   |
| Dashboard del Direttore | _Raro_                          | _no_                       | _si_           | _-_                                                                                                   |
| Caricamento materiale   | _Almeno due volte al mese_      | _Dipende dal tipo di file_ | _semi-cirtico_ | _inteso che: se non c'è non impedisce al software di funzionare, ma mancherebbe una parte importante_ |

## Scelte tecnologiche

| Area             | Scelta                    | Alternativa considerata | Perché avete scelto così                                                      |
| ---------------- | ------------------------- | ----------------------- | ----------------------------------------------------------------------------- |
| Backend          | _C# (Asp.Net)_            | _Rust?_                 | _Voglio imparare il linguaggio e ho visto che è molto potente per il backend_ |
| Frontend         | _React_                   | _…_                     | _Lo sto imparando in questo momento e ho visto che funziona bene con C#_      |
| Database         | _Azure SQl_               | _…_                     | _Ho visto che è la migliore scelta con C#_                                    |
| Provider cloud   | _>Microsoft Azure_        | _…_                     | _…_                                                                           |
| Servizi cloud    | _AzureSQL,Blobstorage_    | _…_                     | _…_                                                                           |
| Regione          | _verso centro europa_     | _…_                     | _vicinanza dei server_                                                        |
| Servizio esterno | _SendGrind (InvioEmail?)_ | _…_                     | _…_                                                                           |
