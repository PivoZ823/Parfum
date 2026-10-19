 Parfum

 Il profumo giusto, per la persona giusta.

 1. Cos'è Parfum?

**Parfum** è una web application dedicata al mondo dei profumi, pensata per aiutare gli utenti a trovare la fragranza più adatta ai propri gusti e alle proprie esigenze.

Il sito offre un catalogo di profumi consultabile attraverso una ricerca e diversi filtri, come prezzo, stagione, categoria e intensità.

Una delle funzionalità principali è un **quiz personalizzato**, attraverso il quale l'utente può inserire le proprie preferenze e ricevere consigli sui profumi più adatti.

L'obiettivo è rendere la scelta di un profumo più semplice, anche per chi non conosce le caratteristiche delle fragranze.

 Quale problema vuole risolvere?

Scegliere un profumo non è sempre semplice, soprattutto per chi non conosce le differenze tra le varie fragranze.

Spesso gli utenti devono cercare informazioni su diversi siti, confrontare prodotti e leggere molte recensioni prima di trovare un profumo interessante.

Parfum vuole semplificare questo processo, raccogliendo le informazioni in un'unica piattaforma e aiutando l'utente attraverso un sistema di raccomandazione personalizzato.

 Obiettivi

- Rendere semplice e veloce la ricerca di un profumo.
- Permettere di filtrare i prodotti secondo le proprie preferenze.
- Consigliare profumi attraverso un quiz.
- Fornire informazioni dettagliate sulle fragranze.
- Permettere agli utenti registrati di salvare preferiti e lasciare recensioni.
- Offrire in futuro funzionalità aggiuntive attraverso un abbonamento.



 2. Funzionalità e attori

La web application prevede quattro tipologie di utenti.

| Attore | Descrizione |
|---|---|
| Utente non loggato | Può visualizzare la homepage, consultare il catalogo, cercare profumi, utilizzare filtri, consultare le schede ed effettuare il quiz. |
| Utente loggato | Può utilizzare tutte le funzionalità pubbliche e inoltre salvare preferiti e lasciare recensioni. |
| Utente abbonato | Potrà accedere a contenuti aggiuntivi, consigli personalizzati e funzionalità esclusive. |
| Admin | Può gestire profumi e recensioni e visualizzare le statistiche sui prodotti più cercati. |

3. User Stories

Le User Stories descrivono le funzionalità dal punto di vista di chi utilizza il sito.

| ID | User Story |
|---|---|
| US01 | Come visitatore, voglio visualizzare la homepage per capire immediatamente lo scopo del sito. |
| US02 | Come visitatore, voglio consultare un catalogo per scoprire i profumi disponibili. |
| US03 | Come visitatore, voglio cercare un profumo per nome per trovarlo velocemente. |
| US04 | Come visitatore, voglio filtrare i profumi per categoria, prezzo, stagione e intensità per trovare quelli adatti a me. |
| US05 | Come visitatore, voglio visualizzare la scheda dettagliata di un profumo per conoscerne le caratteristiche. |
| US06 | Come visitatore, voglio effettuare un quiz per trovare un profumo adatto alle mie preferenze. |
| US07 | Come visitatore, voglio visualizzare i risultati del quiz per conoscere i profumi consigliati. |
| US08 | Come visitatore, voglio registrarmi per accedere alle funzionalità riservate. |
| US09 | Come utente registrato, voglio effettuare il login per accedere al mio account. |
| US10 | Come utente loggato, voglio salvare un profumo nei preferiti per ritrovarlo facilmente. |
| US11 | Come utente loggato, voglio visualizzare la lista dei preferiti per consultare i profumi salvati. |
| US12 | Come utente loggato, voglio lasciare una recensione per condividere la mia opinione. |
| US13 | Come amministratore, voglio gestire profumi e recensioni per mantenere aggiornato il sito. |
| US14 | Come amministratore, voglio consultare le statistiche per scoprire i profumi più cercati. |
| US15 | Come utente abbonato, voglio accedere a funzionalità e consigli esclusivi per ottenere un'esperienza più personalizzata. |



 4. Requisiti software

I requisiti software rappresentano le caratteristiche e le funzionalità che il sistema deve possedere.

Si dividono in tre categorie principali.

4.1 Requisiti funzionali

Descrivono **cosa deve fare il sistema**, quindi le operazioni che l'utente può eseguire.

| ID | Requisito funzionale |
|---|---|
| RF01 | Il sistema deve mostrare una homepage con le informazioni principali. |
| RF02 | Il sistema deve permettere di visualizzare il catalogo dei profumi. |
| RF03 | Il sistema deve consentire la ricerca dei profumi. |
| RF04 | Il sistema deve permettere di filtrare i prodotti per categoria, prezzo, stagione e intensità. |
| RF05 | Il sistema deve mostrare la scheda dettagliata dei profumi. |
| RF06 | Il sistema deve permettere all'utente di completare un quiz personalizzato. |
| RF07 | Il sistema deve mostrare i profumi consigliati in base alle risposte del quiz. |
| RF08 | Il sistema deve consentire registrazione e login. |
| RF09 | Il sistema deve permettere agli utenti autenticati di salvare e visualizzare i preferiti. |
| RF10 | Il sistema deve consentire agli utenti autenticati di lasciare recensioni. |
| RF11 | Il sistema deve permettere all'admin di gestire profumi e recensioni. |
| RF12 | Il sistema deve permettere all'admin di consultare le statistiche sui profumi più cercati. |

Le funzionalità relative agli abbonamenti sono previste come possibile estensione e richiedono una successiva definizione tecnica.

 4.2 Requisiti non funzionali

Descrivono **come deve funzionare il sistema**, quindi aspetti come prestazioni, sicurezza e facilità di utilizzo.

| ID | Requisito non funzionale |
|---|---|
| RNF01 | Il sito deve avere un'interfaccia semplice e intuitiva. |
| RNF02 | Il sito deve essere responsive e adattarsi a computer, tablet e smartphone. |
| RNF03 | Le pagine e i risultati di ricerca devono caricarsi in tempi ragionevoli. |
| RNF04 | Le password e i dati degli utenti devono essere protetti. |
| RNF05 | Il sistema deve gestire eventuali errori senza interrompere completamente il servizio. |
| RNF06 | Il codice deve essere ordinato e facilmente modificabile. |
| RNF07 | I testi e i pulsanti devono essere leggibili e facilmente utilizzabili. |
| RNF08 | Le funzioni amministrative devono essere accessibili soltanto agli utenti autorizzati. |

 4.3 Requisiti di dominio

Descrivono **le regole specifiche del settore della profumeria** che il sistema deve conoscere e rispettare.

| ID | Requisito di dominio |
|---|---|
| RD01 | I profumi devono essere organizzati in categorie olfattive. |
| RD02 | Ogni profumo deve avere informazioni come nome, marca, prezzo e caratteristiche. |
| RD03 | I profumi devono poter essere associati alle stagioni consigliate. |
| RD04 | Deve essere possibile distinguere i profumi in base alla loro intensità. |
| RD05 | Il quiz deve utilizzare le preferenze dell'utente per individuare i profumi compatibili. |
| RD06 | Le schede possono riportare le note olfattive di testa, cuore e fondo, quando disponibili. |
| RD07 | Le raccomandazioni devono essere considerate suggerimenti e non garanzie, perché la percezione delle fragranze è soggettiva. |



 5. Analisi delle funzionalità e delle priorità

Per organizzare lo sviluppo vengono utilizzati due criteri:

- **Tempo di realizzazione:** stima delle ore necessarie a completare la funzionalità.
- **Priorità:** valore da 1 a 5, dove 5 indica la massima importanza.

La seguente tabella riporta le funzionalità e le stime definite nel foglio Excel di progetto.

| # | Funzionalità | Attore | Tempo | Priorità |
|---|---|---|---|---|
| 1 | Visualizzare homepage / landing page | Non loggato | 3 h | 5 |
| 2 | Visualizzare catalogo profumi | Non loggato | 4 h | 5 |
| 3 | Cercare un profumo | Non loggato | 3 h | 4 |
| 4 | Filtrare per categoria, prezzo, stagione e intensità | Non loggato | 5 h | 4 |
| 5 | Visualizzare scheda profumo | Non loggato | 3 h | 5 |
| 6 | Fare il quiz personalizzato | Non loggato | 7 h | 5 |
| 7 | Visualizzare risultato quiz | Non loggato | 3 h | 5 |
| 8 | Creare un account | Non loggato | 4 h | 3 |
| 9 | Effettuare login | Non loggato | 3 h | 3 |
| 10 | Salvare un profumo nei preferiti | Loggato | 4 h | 3 |
| 11 | Visualizzare preferiti | Loggato | 3 h | 3 |
| 12 | Lasciare una recensione | Loggato | 4 h | 2 |
| 13 | Gestire profumi e recensioni | Admin | 6 h | 2 |
| 14 | Visualizzare statistiche | Admin | 5 h | 1 |

**Tempo totale stimato: 57 ore.**

Questa stima riguarda esclusivamente le 14 funzionalità indicate e non comprende eventuali attività aggiuntive, come test approfonditi, documentazione e abbonamenti.

 Ordine di sviluppo

Fase 1 – Struttura principale**

Realizzazione della homepage, del catalogo e delle schede dettagliate dei profumi.

Fase 2 – Ricerca e personalizzazione**

Sviluppo del quiz, della visualizzazione dei risultati, della ricerca e dei filtri.

Fase 3 – Gestione utenti**

Implementazione della registrazione, del login e dei preferiti.

Fase 4 – Funzionalità aggiuntive**

Sviluppo delle recensioni, degli strumenti amministrativi e delle statistiche.

Fase 5 – Sviluppi futuri**

Possibile integrazione degli abbonamenti, dei contenuti esclusivi e dei consigli più avanzati basati sull'intelligenza artificiale.



 6. Analisi SWOT

L'analisi SWOT serve a identificare i punti di forza, le debolezze, le opportunità e le minacce del progetto.

 Strengths – Punti di forza

- Interfaccia semplice, comprensibile anche per utenti poco esperti.
- Quiz che facilita la ricerca di un profumo.
- Possibilità di utilizzare più filtri.
- Catalogo con informazioni raccolte in un'unica piattaforma.
- Preferiti e recensioni per gli utenti registrati.
- Possibilità di integrare funzionalità IA.

 Weaknesses – Punti di debolezza

- Necessità di aggiornare regolarmente il catalogo.
- Dipendenza dalla correttezza delle informazioni sui profumi.
- Impossibilità di provare fisicamente una fragranza attraverso il sito.
- Tempo necessario per sviluppare e mantenere le varie funzionalità.

Opportunities – Opportunità

- Crescente interesse verso il mondo della profumeria.
- Possibilità di collaborare con negozi e marchi.
- Introduzione di abbonamenti e contenuti premium.
- Sviluppo di un'applicazione mobile.
- Utilizzo dell'intelligenza artificiale per migliorare i consigli.

 Threats – Minacce

- Presenza di siti di profumeria già conosciuti.
- Concorrenza di grandi piattaforme e negozi online.
- Variazioni nei prezzi e nella disponibilità dei profumi.
- Costi di gestione ed eventuali servizi IA.
- Possibile diffidenza degli utenti verso i consigli automatici.

Conclusione SWOT

Parfum ha come principale punto di forza la semplicità di utilizzo, unita alla possibilità di ricevere suggerimenti personalizzati.

La difficoltà principale è rappresentata dalla natura soggettiva dei profumi: una fragranza consigliata potrebbe non piacere dopo essere stata provata.

Il sito vuole quindi aiutare l'utente a restringere la scelta, senza sostituire completamente la prova fisica del prodotto.



 7. UML – Diagramma dei casi d'uso

Il diagramma dei casi d'uso rappresenta le interazioni tra gli utenti e il sistema Parfum.

### Attori

**Utente non loggato:** accede alle funzionalità pubbliche del sito.

**Utente loggato:** può utilizzare anche i preferiti e le recensioni.

**Utente abbonato:** rappresenta un'estensione prevista con funzionalità esclusive.

**Admin:** gestisce i contenuti del sito e consulta le statistiche.

 Principali casi d'uso

| Attore | Casi d'uso |
|---|---|
| Utente non loggato | Visualizzare homepage, catalogo e schede, cercare, filtrare, fare quiz, vedere risultati, registrarsi, effettuare login |
| Utente loggato | Tutte le funzionalità pubbliche, salvare preferiti, visualizzare preferiti, lasciare recensioni |
| Utente abbonato | Funzionalità di utente loggato e, in futuro, contenuti esclusivi |
| Admin | Gestire profumi, gestire recensioni, visualizzare statistiche |

 Relazioni tra i casi d'uso

- L'utente loggato può eseguire tutte le operazioni dell'utente non loggato.
- L'utente abbonato può eseguire tutte le operazioni dell'utente loggato.
- Il quiz porta alla visualizzazione dei risultati.
- La gestione dei contenuti è riservata all'admin.
- Il salvataggio dei preferiti e la pubblicazione delle recensioni richiedono l'autenticazione.



 8. Possibili sviluppi futuri

Una volta completate le funzionalità principali, Parfum potrebbe essere ampliato con:

- Abbonamenti con vantaggi esclusivi.
- Assistente virtuale basato sull'intelligenza artificiale.
- Consigli personalizzati sulla base dei profumi già apprezzati.
- Confronto diretto tra più fragranze.
- Collegamenti ai negozi dove acquistare i prodotti.
- Notifiche sulle novità.
- Applicazione mobile dedicata.



