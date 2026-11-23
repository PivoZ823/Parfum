# Parfum

 1. Descrizione del progetto

Il progetto consiste nella creazione di un sito web dedicato al mondo dei profumi, che aiuta gli utenti a trovare una fragranza in base ai propri gusti.

Gli utenti potranno cercare i profumi, visualizzare le loro caratteristiche e filtrarli per prezzo, stagione, intensità e tipo di fragranza.

Una delle funzioni principali sarà un quiz, dove l'utente risponderà ad alcune domande sui propri gusti e il sito gli consiglierà i profumi più adatti alle sue preferenze.

Sarà possibile anche registrarsi, effettuare il login, salvare i profumi preferiti e lasciare recensioni. L'amministratore potrà gestire i profumi, le recensioni e visualizzare le statistiche.

In futuro vorremmo aggiungere un sistema di abbonamento Premium, che permetterà di ricevere consigli più personalizzati e utilizzare funzioni extra.

L'obiettivo è creare un sito semplice da utilizzare, anche per le persone che non conoscono bene il mondo dei profumi.

 2. Tabella delle funzionalità

Per organizzare il lavoro abbiamo diviso le funzionalità in base alla loro importanza e al tempo necessario per realizzarle.

La priorità va da 1 a 5, dove 5 indica una funzionalità molto importante.

| Azione | Chi | Priorità | Tempo |
|---|---|---|---|
| Visualizzare homepage | Utente non loggato | 5 | 3 ore |
| Visualizzare catalogo profumi | Utente non loggato | 5 | 4 ore |
| Cercare un profumo | Utente non loggato | 4 | 3 ore |
| Filtrare per prezzo, stagione e fragranza | Utente non loggato | 4 | 5 ore |
| Visualizzare scheda profumo | Utente non loggato | 5 | 3 ore |
| Fare quiz personalizzato | Utente non loggato | 5 | 7 ore |
| Visualizzare risultati del quiz | Utente non loggato | 5 | 3 ore |
| Registrarsi | Utente non loggato | 3 | 4 ore |
| Effettuare login | Utente registrato | 3 | 3 ore |
| Salvare profumi preferiti | Utente loggato | 3 | 4 ore |
| Visualizzare preferiti | Utente loggato | 3 | 3 ore |
| Lasciare recensioni | Utente loggato | 2 | 4 ore |
| Gestire profumi e recensioni | Admin | 2 | 6 ore |
| Visualizzare statistiche | Admin | 1 | 5 ore |

**Tempo totale stimato: 57 ore.**

Abbiamo deciso di iniziare dalla homepage, dal catalogo e dalle schede dei profumi, perché sono le parti principali del sito. Successivamente realizzeremo il quiz, la ricerca e i filtri. Infine aggiungeremo la registrazione, i preferiti, le recensioni e le funzioni dell'amministratore.

 3. User Stories

Le User Stories descrivono cosa vogliono fare gli utenti attraverso il sito.

| ID | User Story |
|---|---|
| US01 | Come utente, voglio visualizzare la homepage per capire cosa offre il sito. |
| US02 | Come utente, voglio cercare un profumo per nome per trovarlo velocemente. |
| US03 | Come utente, voglio filtrare i profumi in base al prezzo, alla stagione e alla fragranza. |
| US04 | Come utente, voglio vedere le caratteristiche di un profumo prima di sceglierlo. |
| US05 | Come utente, voglio fare un quiz per trovare un profumo in base ai miei gusti. |
| US06 | Come utente, voglio vedere i risultati del quiz per conoscere i profumi consigliati. |
| US07 | Come utente, voglio registrarmi e creare un account personale. |
| US08 | Come utente registrato, voglio effettuare il login per accedere al mio account. |
| US09 | Come utente registrato, voglio salvare i profumi che mi piacciono nei preferiti. |
| US10 | Come utente registrato, voglio visualizzare i miei profumi preferiti. |
| US11 | Come utente registrato, voglio lasciare recensioni sui profumi. |
| US12 | Come utente Premium, voglio ricevere consigli più personalizzati. |
| US13 | Come amministratore, voglio aggiungere, modificare ed eliminare i profumi. |
| US14 | Come amministratore, voglio gestire le recensioni degli utenti. |
| US15 | Come amministratore, voglio visualizzare le statistiche dei profumi più cercati. |

 4. Requisiti software

I requisiti software servono a definire cosa deve fare il sito e come deve funzionare.

Si dividono in tre categorie principali: requisiti funzionali, non funzionali e di dominio.

 4.1 Requisiti funzionali

I requisiti funzionali descrivono le operazioni che il sito deve permettere di svolgere.

| ID | Requisito |
|---|---|
| RF01 | Il sistema deve permettere agli utenti di visualizzare il catalogo dei profumi. |
| RF02 | Il sistema deve permettere di cercare i profumi per nome. |
| RF03 | Il sistema deve permettere di filtrare i profumi per prezzo, stagione, categoria e intensità. |
| RF04 | Il sistema deve mostrare le informazioni principali di ogni profumo. |
| RF05 | Il sistema deve permettere agli utenti di effettuare un quiz personalizzato. |
| RF06 | Il sistema deve consigliare alcuni profumi in base alle risposte del quiz. |
| RF07 | Il sistema deve permettere la registrazione e il login degli utenti. |
| RF08 | Il sistema deve permettere agli utenti registrati di salvare i profumi preferiti. |
| RF09 | Il sistema deve permettere di visualizzare i profumi salvati. |
| RF10 | Il sistema deve permettere agli utenti registrati di lasciare recensioni. |
| RF11 | L'amministratore deve poter aggiungere, modificare ed eliminare i profumi. |
| RF12 | L'amministratore deve poter gestire le recensioni. |
| RF13 | L'amministratore deve poter visualizzare le statistiche del sito. |

4.2 Requisiti non funzionali

I requisiti non funzionali descrivono le caratteristiche che il sito deve avere.

| ID | Requisito |
|---|---|
| RNF01 | Il sito deve essere semplice da utilizzare. |
| RNF02 | Il sito deve funzionare su computer, tablet e smartphone. |
| RNF03 | Le pagine devono caricarsi velocemente. |
| RNF04 | I dati personali degli utenti devono essere protetti. |
| RNF05 | Le password devono essere salvate in modo sicuro. |
| RNF06 | Il sito deve avere una grafica chiara e ordinata. |
| RNF07 | Il codice deve essere organizzato per facilitare le modifiche future. |
| RNF08 | Le funzioni dell'amministratore devono essere accessibili solo agli utenti autorizzati. |

 4.3 Requisiti di dominio

I requisiti di dominio sono le regole specifiche che riguardano il mondo dei profumi e il funzionamento del sito.

| ID | Requisito |
|---|---|
| RD01 | Ogni profumo deve avere un nome, una marca, un prezzo e una descrizione. |
| RD02 | I profumi devono essere divisi in categorie, come dolci, freschi, agrumati e legnosi. |
| RD03 | Ogni profumo deve avere le proprie note olfattive, quando disponibili. |
| RD04 | I profumi devono poter essere classificati in base alla stagione consigliata. |
| RD05 | Il sistema deve distinguere i profumi in base alla loro intensità. |
| RD06 | Il quiz deve considerare le preferenze inserite dall'utente. |
| RD07 | I consigli del quiz non devono essere considerati sempre perfetti, perché ogni persona ha gusti diversi. |
| RD08 | Solo gli utenti registrati possono salvare preferiti e lasciare recensioni. |
| RD09 | Le funzioni Premium dovranno essere riservate agli utenti con un abbonamento attivo, quando saranno disponibili. |

 5. Analisi SWOT

L'analisi SWOT serve a capire i punti di forza e di debolezza del progetto, ma anche le opportunità e le difficoltà che potremmo incontrare.

 Punti di forza e punti di debolezza

| Punti di forza | Punti di debolezza |
|---|---|
| Il sito è semplice da utilizzare anche per chi non conosce i profumi. | Non è possibile sentire realmente l'odore di un profumo attraverso il sito. |
| Il quiz aiuta a trovare un profumo in base ai propri gusti. | Il quiz potrebbe non consigliare sempre il profumo giusto. |
| I filtri rendono la ricerca più veloce. | Il catalogo deve essere aggiornato regolarmente. |
| Gli utenti possono salvare preferiti e lasciare recensioni. | Alcune funzionalità richiedono tempo per essere sviluppate. |

Opportunità e minacce

| Opportunità | Minacce |
|---|---|
| Possibilità di collaborare con negozi e marche di profumi. | Esistono già siti molto conosciuti dedicati ai profumi. |
| Possibilità di sviluppare un'app per smartphone. | Gli utenti potrebbero preferire andare in profumeria. |
| Introduzione dell'intelligenza artificiale per migliorare i consigli. | I prezzi e la disponibilità dei profumi possono cambiare. |
| Possibilità di introdurre abbonamenti Premium. | Gli utenti potrebbero non voler pagare per le funzioni extra. |

 6. Sviluppi futuri

In futuro vorremmo migliorare Parfum aggiungendo un'intelligenza artificiale che permetta agli utenti di descrivere direttamente il profumo che stanno cercando.

Per esempio, una persona potrebbe scrivere di volere un profumo dolce, molto persistente e adatto all'inverno. L'intelligenza artificiale potrebbe quindi consigliare alcune fragranze e spiegare perché potrebbero essere adatte.

Un'altra idea è aggiungere un sistema di confronto tra più profumi, così l'utente potrà vedere le differenze tra prezzo, durata, intensità e caratteristiche.

Vorremmo anche introdurre un abbonamento Premium, con consigli più personalizzati e alcune funzioni esclusive.

Per il momento ci concentreremo sulle funzioni principali, come il catalogo, la ricerca, i filtri e il quiz. Dopo passeremo alla gestione degli account, ai preferiti, alle recensioni e alle funzioni dell'amministratore.

In futuro vorremmo anche introdurre un abbonamento con alcune funzionalità esclusive.




