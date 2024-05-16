<!--
author:   Tommaso Ausili, Leonardo Belli, Andrea Pomarico, Nicola Presta

email:    tommaso.ausili@savoiabenincasa.it, leonardo.belli@savoiabenincasa.it, andrea.pomarico@savoiabenincasa.it, nicola.presta@savoiabenincasa.it

version:  0.0.1

language: it

narrator: Italian Male

comment:  in questa presentazione parleremo della sicurezza in rete

-->

# WEB SECURITY

La web security si riferisce alla pratica di garantire che i vari siti e applicazioni siano protetti da varie minacce e vulnerabilità. Con il crescente affidamento che si fa su Internet per la comunicazione, il commercio e l'intrattenimento, la sicurezza quando si naviga nel web è diventata una preoccupazione critica sia per le aziende che per gli individui. In questa presentazione osserveremo alcuni degli aspetti chiave della sicurezza in rete.

Lavoro di Tommaso Ausili, Leonardo Belli, Andrea Pomarico e Nicola Presta

Visualizza su [LiaScript](https://liascript.github.io/course/?/nUjfA0wyhmi6UVbIs76yNo0C)

## 1.AUTENTICAZIONE

L'autenticazione in sicurezza informatica è un processo essenziale che serve a confermare l'identità di un utente, un dispositivo o un'altra entità in un sistema informatico, prima di concedere l'accesso a risorse, servizi o dati. Questo processo aiuta a garantire che solo gli utenti autorizzati possano accedere alle informazioni e ai servizi protetti, prevenendo così l'accesso illecito e il furto di dati. I metodi di autenticazione si possono classificare principalmente in tre categorie, che riflettono i diversi fattori di autenticazione:
1. Qualcosa che conosci: Questa categoria include tutti i metodi di autenticazione che richiedono qualcosa che l'utente sa. Un esempio comune è la password o il PIN. Altri esempi possono includere risposte a domande di sicurezza personali
2. Qualcosa che hai: Comprende metodi che richiedono qualcosa che l'utente possiede fisicamente. Ciò può includere token hardware, carte a chip, chiavi USB di sicurezza o un dispositivo mobile che può ricevere un SMS o eseguire un'app di autenticazione
3. Qualcosa che sei: Questa categoria fa riferimento ai metodi di autenticazione che sfruttano le caratteristiche biometriche dell'utente, come l'impronta digitale, il riconoscimento del viso, la scansione dell'iride o la voce

Data la crescente sofisticazione degli attacchi informatici, molti sistemi adottano l'autenticazione multifattoriale, che combina due o più metodi indipendenti di autenticazione da diverse categorie. Ad esempio, un sistema può richiedere una password e un codice OTP inviato al telefono dell'utente. L'uso di MFA aumenta significativamente la sicurezza, rendendo molto più difficile per un attaccante ottenere l'accesso non autorizzato

In sintesi: l'autenticazione è un pilastro fondamentale della sicurezza informatica, essenziale per proteggere l'accesso ai sistemi e ai dati in un ambiente digitale sempre più complesso e minacciato

Cosa verifica il processo di autenticazione in un sistema informatico?
- [(X)] L'identità di un utente, dispositivo o altra entità
- [( )] Che il sistema funzioni correttamente
- [( )] La qualità della connessione Internet
- [( )] La capacità di archiviazione del sistema

Qual è un esempio di autenticazione basata su qualcosa che l'utente possiede?
- [( )] Una password
- [( )] Una scansione dell'impronta digitale
- [( )] Una domanda di sicurezza
- [(X)] Un token hardware 

Perché è importante cambiare regolarmente la password?
- [( )] Per velocizzare il computer
- [(X)] Per evitare che diventi prevedibile con il tempo
- [( )] Per aumentare la capacità di archiviazione
- [( )] Per migliorare la qualità grafica del display

Che cos'è l'autenticazione multifattoriale?
- [( )] L'uso di una singola password complessa
- [( )] L'uso di una password e di una domanda di sicurezza
- [(X)] L'uso di due o più metodi di autenticazione indipendenti
- [( )] L'uso di due password simili

Quale opzione è un esempio di autenticazione biometrica?
- [( )] Password
- [(X)] Riconoscimento del viso
- [( )] PIN
- [( )] Token software


## 2.AUTORIZZAZIONE

L'autorizzazione è il processo mediante il quale si verifica se un utente, un programma o un dispositivo ha il permesso di eseguire una determinata azione o di accedere a specifiche risorse. Mentre l'autenticazione si assicura che l'identità dell'utente sia verificata, l'autorizzazione determina cosa quell'utente può fare o vedere una volta all'interno del sistema. Il processo di autorizzazione si attiva tipicamente dopo che un utente è stato autenticato con successo. Esso verifica i privilegi dell'utente confrontandoli con una serie di politiche o regole di sicurezza che definiscono chi può fare cosa. Ad esempio, un sistema di gestione dei database può consentire a certi utenti di leggere documenti ma non di modificarli, mentre altri potrebbero avere il permesso di eseguire entrambe le azioni. Ci sono diversi metodi e modelli utilizzati per implementare l'autorizzazione nei sistemi informatici, tra cui:
1. Controllo degli Accessi Basato sui Ruoli, RBAC: Gli accessi sono assegnati in base ai ruoli all'interno dell'organizzazione e ogni ruolo ha permessi specifici
2. Controllo degli Accessi Basato sugli Attributi, ABAC: L'accesso è concesso o negato in base a politiche che considerano gli attributi dell'utente, dell'ambiente, delle risorse e dell'azione
3. Controllo degli Accessi Basato sul Contesto, CBAC: Considera il contesto dell'accesso richiesto, come il momento della giornata o la rete dalla quale si accede
4. Liste di Controllo degli Accessi, ACL: Specificano quali utenti o sistemi sono autorizzati ad accedere a determinate risorse e le operazioni che possono eseguire su di esse

L'autorizzazione è fondamentale per la protezione dei dati sensibili e delle risorse, assicurando che solo gli utenti autorizzati possano eseguire azioni specifiche. Un efficace sistema di autorizzazione previene l'abuso di privilegi e limita il potenziale danno in caso di violazione dell'account.

Cosa fa principalmente un sistema di controllo degli accessi basato sui ruoli?
- [( )] Verifica l'identità degli utenti
- [(X)] Assegna permessi basati sui ruoli degli utenti nell'organizzazione
- [( )] Blocca tutti gli accessi non autorizzati a livello di rete
- [( )] Crittografa i dati sensibili

Nel controllo degli accessi basato sugli attributi, cosa determina se un utente può accedere a una risorsa?
- [( )] La password dell'utente
- [(X)] Gli attributi dell'utente, dell'ambiente, delle risorse e dell'azione
- [( )] La posizione fisica dell'utente
- [( )] Il ruolo dell'utente nell'organizzazione

Che cosa è una lista di controllo degli accessi?
- [( )] Un protocollo di sicurezza per crittografare i dati
- [( )] Una regola che limita l'accesso alla rete
- [(X)] Un elenco di utenti o sistemi autorizzati ad accedere a specifiche risorse
- [( )] Un software che rileva e previene gli attacchi informatici

Cosa fa il controllo degli accessi basato sul contesto?
- [( )] Protegge i dati crittografandoli
- [(X)] Determina l'accesso basandosi sul contesto operativo come il momento della giornata o la localizzazione
- [( )] Impedisce l'accesso a tutti gli utenti tranne che al proprietario delle risorse
- [( )] Richiede autenticazione biometrica per l'accesso alle risorse

Perché è importante avere un buon sistema di autorizzazione in un'organizzazione?
- [(X)] Per garantire che solo utenti autorizzati possano eseguire determinate azioni
- [( )] Per migliorare la velocità del sistema informatico
- [( )] Per aumentare la capacità di storage del sistema
- [( )] Per ridurre i costi di gestione della rete

## 3.CRITTOGRAFIA DEI DATI

La crittografia dei dati è una delle colonne portanti della sicurezza informatica. Si tratta di una tecnica matematica usata per proteggere le informazioni, trasformando i dati originali, noti come "dati in chiaro", in una forma illeggibile, chiamata "cifrato", a chiunque non possieda le chiavi di decifrazione appropriate. Questo processo è cruciale per proteggere la privacy, la confidenzialità e l'integrità dei dati mentre sono memorizzati o trasmessi attraverso reti potenzialmente insicure. Esistono principalmente due tipi di crittografia usati nella sicurezza informatica:
1. Crittografia simmetrica: utilizza la stessa chiave per cifrare e decifrare i dati. È più veloce e più efficiente dal punto di vista computazionale rispetto alla crittografia asimmetrica. Il principale svantaggio è la gestione delle chiavi, in quanto la stessa chiave deve essere tenuta segreta e condivisa tra mittente e destinatario. Esempi di algoritmi di crittografia simmetrica includono AES, Advanced Encryption Standard, e DES, Data Encryption Standard
2. Crittografia asimmetrica, o crittografia a chiave pubblica: utilizza una coppia di chiavi, una pubblica e una privata. La chiave pubblica può essere condivisa liberamente, mentre la chiave privata deve rimanere confidenziale. La chiave pubblica viene usata per cifrare i dati, e solo la corrispondente chiave privata può decifrarli. Questo tipo di crittografia è fondamentale per le operazioni di firma digitale e per stabilire connessioni sicure, come nel protocollo SSL/TLS. È generalmente più lento come metodo rispetto alla crittografia simmetrica a causa della complessità matematica. Esempi di algoritmi di crittografia asimmetrica includono RSA ed ECC, ovvero Elliptic Curve Cryptography

In informatica, ci sono vari ambiti in cui la crittografia può essere applicata:
1. Comunicazioni sicure: utilizzata in protocolli come HTTPS, SSL/TLS, per garantire connessioni sicure e protette su Internet
2. Protezione dei dati memorizzati: crittografia di database, dischi rigidi e altri supporti di memorizzazione per proteggerli da accessi non autorizzati
3. Firma digitale: assicura autenticità e integrità di un documento o messaggio, confermando che non è stato modificato dal momento della firma e validando l'identità del firmatario
4. Autenticazione: la crittografia aiuta a confermare l'identità delle parti comunicanti in molti protocolli di autenticazione

La crittografia è una tecnologia indispensabile per garantire la sicurezza e la fiducia nell'ambiente digitale moderno, proteggendo le informazioni da attacchi e accessi non autorizzati mentre vengono trasmesse o memorizzate

Quale tipo di crittografia utilizza la stessa chiave per cifrare e decifrare i dati?
- [(X)] Crittografia simmetrica
- [( )] Crittografia asimmetrica

Quale algoritmo è un esempio di crittografia asimmetrica?
- [( )] AES
- [( )] DES
- [(X)] RSA
- [( )] SHA-256

Per quale scopo è comunemente utilizzata la crittografia RSA?
- [( )] Cifrare intere reti
- [(X)] Creare una firma digitale
- [( )] Cifrare dati a velocità molto elevate
- [( )] Creare password più forti

Che cosa si intende per "chiave pubblica" nella crittografia a chiave pubblica?
- [( )] Una chiave che viene mantenuta segreta tra due utenti
- [( )] Una chiave che viene usata per accedere pubblicamente ai database crittografati
- [( )] Una chiave utilizzata per decifrare tutti i messaggi su una rete
- [(X)] Una chiave che chiunque può usare per cifrare i messaggi destinati al proprietario della chiave privata

Qual è il principale vantaggio della crittografia dei dati?
- [( )] Aumenta la velocità di trasmissione dei dati
- [( )] Riduce il costo della memorizzazione dei dati
- [(X)] Protegge i dati da accessi non autorizzati
- [( )] Semplifica la gestione dei dati


## 4.VALIDAZIONE DELL'INPUT

La validazione dell'input è un concetto fondamentale nella sicurezza informatica,mira a garantire che i dati inseriti da un utente o ricevuti da un altro sistema rispettino specifici criteri prima di essere elaborati da un'applicazione. Questo processo è cruciale per prevenire una vasta gamma di vulnerabilità e attacchi, come l'iniezione SQL, cross-site scripting XSS, e molti altri problemi di sicurezza che possono emergere quando i dati in ingresso non sono adeguatamente controllati. La validazione dell'input è essenziale per:
1. Prevenire attacchi: Molte vulnerabilità di sicurezza nascono quando un'applicazione assume che l'input ricevuto sia sicuro e ben formato senza verificarlo adeguatamente. Gli attaccanti possono sfruttare questa debolezza per inserire input malevoli che possono portare a esecuzione di codice non autorizzato, perdita di dati, e altre attività dannose
2. Mantenere l'integrità dei dati: Garantire che l'input sia corretto e appropriato per il contesto in cui verrà utilizzato aiuta a mantenere l'integrità dei dati all'interno dell'applicazione, evitando problemi di logica e di elaborazione
3. Migliorare l'esperienza utente: Una validazione efficace può anche aiutare a guidare gli utenti nel processo di immissione dati, segnalando errori in modo che possano essere corretti in tempo reale

La validazione dell'input può essere attuata attraverso vari metodi, spesso combinati per un approccio di sicurezza più robusto:
1. Convalida del tipo di dati: Assicurarsi che l'input corrisponda al tipo di dati atteso, come numeri, stringhe, date, ecc.
2. Convalida della lunghezza: Verificare che la lunghezza dell'input sia entro i limiti accettabili
3. Lista di controllo: Consentire solo valori specifici che sono considerati sicuri o appropriati
4. Uso di espressioni regolari: Utilizzare espressioni regolari per rifiutare o rimuovere caratteri non desiderati dall'input
5. Sanitizzazione: Oltre alla validazione, è importante sanificare l'input, rimuovendo o codificando i caratteri che potrebbero essere usati in attacchi, come <, >, o ", che sono significativi in contesti come l'HTML e SQL
6. Convalida lato client e server: Mentre la convalida lato client può migliorare l'esperienza utente e ridurre il carico sul server, la convalida lato server è cruciale per la sicurezza perché i controlli lato client possono essere facilmente bypassati

La validazione dell'input è una misura di sicurezza molto importante per proteggere le applicazioni dalle vulnerabilità più comuni e per assicurare che i dati siano processati correttamente e in sicurezza

Cosa si intende per validazione dell'input in sicurezza informatica?
- [( )] Il processo di assicurarsi che un software sia libero da bug.
- [( )] Il backup dei dati inseriti dagli utenti.
- [( )] L'aggiornamento automatico del software per prevenire vulnerabilità.
- [(X)] Il controllo dei dati inseriti in un'applicazione prima che vengano elaborati.

Quale tipo di validazione controlla se l'input corrisponde al tipo di dati atteso, come numeri o stringhe?
- [(X)] Convalida del tipo di dati
- [( )] Convalida della lunghezza
- [( )] Lista di controllo
- [( )] Uso di espressioni regolari

Perché è importante eseguire la validazione dell'input?
- [( )] Per velocizzare l'applicazione
- [(X)] Per prevenire attacchi come l'iniezione SQL e XSS
- [( )] Per aumentare lo spazio di archiviazione dei dati
- [( )] Per migliorare la grafica dell'applicazione

Cosa fa la "sanitizzazione" nell'ambito della validazione dell'input?
- [( )] Controlla la lunghezza dell'input
- [(X)] Rimuove o codifica i caratteri potenzialmente pericolosi
- [( )] Controlla se l'input è un numero
- [( )] Aumenta la velocità di elaborazione dei dati

Perché è importante eseguire la validazione dell'input sia lato client che lato server?
- [( )] La validazione lato client migliora la sicurezza.
- [( )] La validazione lato server è meno importante della validazione lato client.
- [(X)] La validazione lato client può essere bypassata, quindi quella lato server è cruciale.
- [( )] La validazione lato server aumenta la velocità del sito web.


## 5.INTESTAZIONI DI SICUREZZA

Le intestazioni di sicurezza HTTP sono un componente cruciale nella protezione delle applicazioni web. Queste intestazioni sono usate per comunicare al browser come deve comportarsi quando gestisce il contenuto di una pagina, potendo così prevenire e mitigare vari tipi di attacchi informatici come il cross-site scripting XSS, il clickjacking e altri tipi di exploit, ovvero tipi di programmi specializzati. Aggiungendo specifiche direttive di sicurezza attraverso queste intestazioni, gli sviluppatori possono rafforzare le difese di un'applicazione web. Queste sono alcune delle intestazioni di sicurezza HTTP più comuni e la loro funzione:
1. _Content-Security-Policy_: Questa intestazione aiuta a prevenire attacchi XSS e di iniezione di dati consentendo ai webmaster di definire da quali fonti il browser dovrebbe accettare contenuti. Può specificare, ad esempio, da quali URL è possibile caricare script, immagini, stili CSS, ecc.
2. _Strict-Transport-Security_: Questa intestazione obbliga il browser a utilizzare connessioni HTTPS per un determinato periodo di tempo, anche se l'utente digita l'URL senza il prefisso _https://_ . È fondamentale per proteggere contro gli attacchi di tipo man-in-the-middle.
3. _X-Frame-Options_: Questa intestazione è utilizzata per prevenire attacchi come il clickjacking, che possono truffare gli utenti facendoli cliccare su qualcosa di diverso da quello che vedono. Essa può impedire che la pagina sia incorniciata da siti non autorizzati.
4. _X-XSS-Protection_: Anche se ormai in disuso e rimossa in molti browser moderni a favore di CSP più robuste, questa intestazione era usata per configurare le impostazioni di protezione integrata del browser contro gli attacchi XSS.
5. _X-Content-Type-Options_: Questa intestazione impedisce al browser di interpretare erroneamente i file scaricati, un comportamento che può essere sfruttato per eseguire attacchi basati sui file MIME.
6. _Feature-Policy_: Permette ai sviluppatori di abilitare o disabilitare l'uso di varie funzionalità e API del browser per la pagina corrente o per quelle incapsulate all'interno di < iframe >.

L'uso di queste intestazioni contribuisce a creare una difesa in profondità, proteggendo gli utenti da vari attacchi e garantendo una maggiore sicurezza delle sessioni di navigazione. Integrare correttamente queste intestazioni nella risposta HTTP di un'applicazione può quindi essere un elemento determinante per la sicurezza complessiva del sito web, proteggendo sia gli utenti che i dati aziendali. Implementarle correttamente richiede una comprensione delle minacce specifiche che ogni intestazione è progettata per mitigare e un'adeguata configurazione per l'ambiente di hosting specifico dell'applicazione.

A cosa serve principalmente l'intestazione HTTP Content-Security-Policy?
- [( )] Obbligare il browser a usare HTTPS
- [( )] Bloccare tutte le richieste HTTP
- [(X)] Prevenire l'inclusione di contenuti non autorizzati come script e CSS
- [( )] Impostare cookie sicuri

Che cosa fa l'intestazione Strict-Transport-Security?
- [( )] Impedisce ai browser di eseguire script non sicuri
- [(X)] Forza il browser a utilizzare solo connessioni HTTPS per un periodo di tempo specificato
- [( )] Blocca l'accesso al sito web da determinate regioni
- [( )] Imposta politiche di sicurezza per le funzionalità del browser

Qual è lo scopo dell'intestazione X-Frame-Options?
- [(X)] Impedire che la pagina web sia incorniciata da altri siti, proteggendo contro il clickjacking
- [( )] Prevenire l'esecuzione di script da origini non fidate
- [( )] Disabilitare le funzionalità del browser come la camera e il microfono
- [( )] Forzare il browser a scaricare i file invece di visualizzarli

Cosa permette di controllare l'intestazione Feature-Policy?
- [( )] Le politiche di trasporto sicuro tramite HTTPS
- [(X)] L'accesso a determinate funzionalità e API del browser nella pagina, come l'accesso a camera e microfono
- [( )] Le policy di accesso alle informazioni di geolocalizzazione
- [( )] La policy per il controllo degli script di terze parti

Qual era lo scopo dell'intestazione X-XSS-Protection?
- [( )] Forzare il browser a caricare le pagine solo via HTTPS
- [( )] Limitare l'accesso a specifiche funzionalità del browser
- [( )] Impedire il download di contenuti di tipo MIME non corretto
- [(X)] Prevenire gli attacchi di tipo cross-site scripting XSS


## 6.AGGIORNAMENTI E PATCH REGOLARI

Gli aggiornamenti e le patch regolari sono una parte fondamentale della sicurezza informatica. Possono essere suddivisi in due categorie principali: aggiornamenti del sistema operativo e delle applicazioni, e aggiornamenti dei dispositivi di rete.
1. Aggiornamenti del sistema operativo e delle applicazioni: Sia i sistemi operativi che le applicazioni vengono costantemente aggiornati per correggere falle di sicurezza, bug e vulnerabilità scoperte. Le aziende di software rilasciano regolarmente patch per indirizzare queste vulnerabilità, quindi è essenziale tenere aggiornati sia il sistema operativo che le applicazioni installate. I sistemi operativi moderni offrono spesso opzioni per l'aggiornamento automatico, semplificando il processo.
2. Aggiornamenti dei dispositivi di rete: Questi aggiornamenti riguardano dispositivi come router, switch e firewall. Anche loro possono avere vulnerabilità che richiedono patch. Mantenere aggiornato il firmware di questi dispositivi è essenziale per garantire la sicurezza della rete.

I cyber criminali spesso sfruttano le vulnerabilità dei software per compromettere sistemi e reti. Le patch correggono queste vulnerabilità, rendendo più difficile per gli hacker sfruttarle.Oltre a correggere le vulnerabilità esistenti, le patch possono introdurre nuove funzionalità di sicurezza o migliorare le procedure di autenticazione, rendendo il sistema più resistente agli attacchi. Molte normative sulla sicurezza, come il GDPR in Europa o il CCPA in California, richiedono alle aziende di mantenere i propri sistemi aggiornati come parte dei requisiti di conformità. Gli aggiornamenti regolari riducono il rischio di violazioni dei dati, proteggendo le informazioni sensibili degli utenti e dei clienti. Tenere aggiornati i sistemi dimostra impegno per la sicurezza da parte dell'azienda, aumentando la fiducia degli utenti e dei clienti.

In sostanza, gli aggiornamenti e le patch regolari sono un elemento fondamentale di una strategia di sicurezza informatica efficace, e tutte le organizzazioni dovrebbero adottare pratiche per mantenerli costantemente aggiornati.

Perché gli aggiornamenti e le patch regolari sono importanti nella sicurezza informatica?
- [( )] Migliorano le prestazioni del sistema
- [( )] Aggiungono nuove funzionalità
- [(X)] Chiudono le vulnerabilità e i bug di sicurezza
- [( )] Aumentano il costo dei software

Cosa sono i dispositivi di rete che richiedono aggiornamenti regolari?
- [( )] Mouse e tastiere
- [(X)] Router, switch e firewall
- [( )] Stampanti e scanner
- [( )] Altoparlanti e microfoni

Qual è uno dei motivi principali per cui gli hacker sfruttano le vulnerabilità del software?
- [(X)] Per compromettere sistemi e reti
- [( )] Per rendere i sistemi più efficienti
- [( )] Per migliorare la sicurezza
- [( )] Perdonare debiti tecnici

Perché le aziende possono essere tenute a mantenere i propri sistemi aggiornati secondo alcune normative sulla sicurezza?
- [( )] Per rendere più difficile l'uso dei sistemi
- [( )] Per aumentare i costi operativi
- [( )] Per sfidare gli hacker
- [(X)] Per garantire la conformità normativa

Qual è uno dei benefici di tenere aggiornati i sistemi secondo il testo?
- [( )] Riduzione della produttività
- [( )] Aumento delle vulnerabilità
- [(X)] Aumento della fiducia degli utenti
- [( )] Nessun impatto sulla sicurezza

