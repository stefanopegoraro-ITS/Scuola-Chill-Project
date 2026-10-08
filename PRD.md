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

| ID     | Storia                             | AC aggiunti dal team                                                                                                        | Note                                                                                |
| ------ | ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| DIR-01 | Creare account docente             | _La Password deve almeno avere 8 caratteri?_                                                                                | _-_                                                                                 |
| DIR-02 | Creare account studente            | _La Password deve almeno avere 8 caratteri?_                                                                                | _-_                                                                                 |
| DIR-03 | Creare classi e comporle           | _Il Direttore deve avere la possibilità di organizzare l'orario e la posizione delle classi, con layout a drop down_        | _poi da vedere lo stile, avevo pensato a una planimetria della scuola semplificata_ |
| DIR-04 | Vedere tutto                       | _Poter vedere tutte le classi, tutti i compiti/annotazioni/avvisi che ci sono per classi_                                   | _…_                                                                                 |
| DIR-05 | Creazione del Calendario dell'anno | _Poter organizzare gli orari e poterli modificare velocemente in caso di imprevisti_                                        | _poter inviare messaggi di promemoria_                                              |
| DOC-01 | Caricare materiale didattico       | _Un funzionamento simile a google classroom_                                                                                | _Mandare delle notifiche agli studenti quando il docente aggiunge del materiale?_   |
| DOC-02 | Assenze, Presenze, Ritardi         | _Poter mettere se un alunno è presente o assente con pochi click_                                                           | _…_                                                                                 |
| DOC-03 | Assegnare i voti                   | _Poter Decidere i voti e modificarli con un menu a cascata_                                                                 | _…_                                                                                 |
| STU-01 | Consultare il materiale didattico  | _Avere a disposizione un abiente simile a google classroom/drive dove lo studente può visuallizzare il materiale assegnato_ | _…_                                                                                 |
| STU-02 | Consultare il calendario           | _Avere accesso in qualunque momento al calendario_                                                                          | _Poter vedere i compiti assegnati su quel giorno nel calendario_                    |
| STU-03 | Consultare i propri voti           | _Avere la possibilità di consultare i propri voti in qualunque momento_                                                     | _con medie ecc._                                                                    |
| STU-04 | Comunicazioni di servizio          | _Avere una sezione notifiche dove arrivano notifiche dei docenti e comunicazioni di servizio_                               | _-_                                                                                 |

## Direttore

### User Story 1

() con la possibiltà di creare l'orario per tutto l'anno scolastico (dove puoi vedere esattamente in che aula sono le classi in quell'ora), e in caso di bisogno modificare l'orario o la posizione delle classi per una specifica ora (inviando anche una notifica agli studenti e docenti in caso di variazione)

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

## STAKEHOLDER

| Stakeholder                 | Cosa fa                               | Cosa gli interessa | Come lo coinvolgete       |
| --------------------------- | ------------------------------------- | ------------------ | ------------------------- |
| Direttore                   | _…_                                   | _…_                | _…_                       |
| Docenti                     | _…_                                   | _…_                | _…_                       |
| Studenti                    | _…_                                   | _…_                | _…_                       |
| Docente del corso           | _Valida il PRD_                       | _…_                | _Presentazione e domande_ |
| Collaudatori del primo anno | _Usano ScuolaChill come utenti reali_ | _…_                | _Intervista, collaudo_    |
| _Altri?_                    |                                       |                    |                           |

## REQUISITI NON FUNZIONALI

| ID     | Famiglia                   | Requisito                                                                                                   | Soglia e condizione                                                                                                 | Come si verifica                                                                                       | Storie collegate |
| ------ | -------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------- |
| NFR-01 | Prestazioni                | _es. Apertura della verifica nel picco_                                                                     | _es. meno di 2 s per il 95% delle richieste, 75 utenti nello stesso minuto_                                         | _Test di carico_                                                                                       | _STU-02_         |
| NFR-02 | Sicurezza                  | _Il software ha bisogno di una pagina di login_                                                             | _se qualcuno prova ad accedere l'app senza aver fatto il login la prima cosa che spunta è la pagina di login_       | _provando a entrare nell'app senza eseguire l'accesso_                                                 | _…_              |
| NFR-03 | Usabilità (da cambiare?)   | _…_                                                                                                         | _…_                                                                                                                 | _…_                                                                                                    | _…_              |
| NFR-04 | Disponibilità/Affidabilità | _Poter essere accessibile il 99% del tempo, cercando di ridurre le interruzioni per manutenzione al minimo_ | _-_                                                                                                                 | _-_                                                                                                    | _…_              |
| NFR-06 | Supporto                   | _l'appiclazione deve funzionare sia su pc che su smartphone_                                                | _l'applicazione deve essere visualizzabile sia su pc che su smartphone (magari consentendo la modifica solo su pc)_ | _-_                                                                                                    | _…_              |
| NFR-07 | Interazione                | _il software deve essere facile da capire e responsivo_                                                     | _il software deve avere delle interazioni dove si capisce subito cosa fa una operazione_                            | _quando si fanno delle operazioni ci sono delle animazioni e nei pulsanti compaiono delle descrizioni_ | _…_              |
| NFR-08 | Conformità                 | _il GDPR per i dati personali (controllare bene Quali sono le legislazioni in questo settore)_              | _?_                                                                                                                 | _?_                                                                                                    | _…_              |

## REQUISITI IMPLICITI

| Chi avete intervistato | Cosa ha detto                     | Requisito che ne avete ricavato |
| ---------------------- | --------------------------------- | ------------------------------- |
| _nome o iniziali_      | _"Il voto non deve sparire, mai"_ | _NFR-…_                         |
|                        |                                   |                                 |

## ASSUNZIONI

| ID     | Assunzione                                   | Cosa succede se è falsa         |
| ------ | -------------------------------------------- | ------------------------------- |
| ASS-01 | _es. La scuola ha 800 studenti e 60 docenti_ | _Il dimensionamento va rifatto_ |
|        |                                              |                                 |

## VINCOLI

| ID     | Vincolo                                             | Da dove viene          |
| ------ | --------------------------------------------------- | ---------------------- |
| VIN-01 | _es. Il budget cloud è quello dei crediti studente_ | _Traccia del progetto_ |
|        |                                                     |                        |

## DIPENDENZE

| ID     | Vincolo                                             | Da dove viene          |
| ------ | --------------------------------------------------- | ---------------------- |
| VIN-01 | _es. Il budget cloud è quello dei crediti studente_ | _Traccia del progetto_ |
|        |                                                     |                        |

## UTENTI CONCORRENTI

| Situazione                      | Utenti concorrenti | Da dove viene il numero                                |
| ------------------------------- | ------------------ | ------------------------------------------------------ |
| Uso normale durante la giornata | _…_                | _…_                                                    |
| Picco delle 9:00 (verifiche)    | _500_              | _numero massimo di utenti che il software può gestire_ |
| Fine quadrimestre (voti)        | _…_                | _…_                                                    |

## PROFILO DI CARICO

| Operazione              | Frequente? | Pesante? | Critica? | Note |
| ----------------------- | ---------- | -------- | -------- | ---- |
| Login                   | _…_        | _…_      | _si_     | _…_  |
| Apertura verifica       | _…_        | _…_      | _…_      | _…_  |
| Consegna verifica       | _…_        | _…_      | _…_      | _…_  |
| Dashboard del Direttore | _…_        | _…_      | _…_      | _…_  |
| Caricamento materiale   | _…_        | _…_      | _…_      | _…_  |

## Scelte tecnologiche

| Area             | Scelta                 | Alternativa considerata | Perché avete scelto così |
| ---------------- | ---------------------- | ----------------------- | ------------------------ |
| Backend          | _C# (Asp.Net )_        | _…_                     | _…_                      |
| Frontend         | _React?_               | _…_                     | _…_                      |
| Database         | _…_                    | _…_                     | _…_                      |
| Provider cloud   | _…_                    | _…_                     | _…_                      |
| Servizi cloud    | _…_                    | _…_                     | _…_                      |
| Regione          | _verso centro europa?_ | _…_                     | _vicinanza dal veneto?_  |
| Servizio esterno | _…_                    | _…_                     | _…_                      |
