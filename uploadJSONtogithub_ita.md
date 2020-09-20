# Devoleum
**[Devoleum](devoleum.com)** è una piattaforma web basata sulla **blockchain di Ethereum** che ti consente di autenticare e monitorare le catene di fornitura di prodotti *digitali* o *fisici*, i casi d'uso possono variare da filiera agricola tradizionale ai servizi di streaming.

Visita Devoleum su [Devoleum.com](Devoleum.com)

# 1.1 Facile da usare

Su **Devoleum** puoi visualizzare la cronologia del prodotto semplicemente utilizzando la *cronologia del prodotto* **link** o utilizzando un **codice QR**. Il consumatore dovrà semplicemente scansionare un codice QR.

![esempio](https://github.com/Devoleum/docs/blob/master/img/EN/easytouse_en.png?raw=true)

## 1.2 Trasparenza e accessibilità 

**Devoleum** è un progetto [**Open Source**](https://github.com/Devoleum), ognuno può implementarlo e usarlo a modo suo. 

L'**obiettivo di Devoleum** è offrire un servizio *trasparente* e *accessibile* ai consumatori e ai produttori, utilizzando l'immutabilità blockchain come valore aggiunto per rendere i dati archiviati autentici e impossibili da manipolare.

## 1.3 Sei il proprietario dei tuoi dati

**Devoleum** memorizza solo l'hash *e il collegamento relativo a un JSON*.


> Esempio dei dati memorizzati nel contratto intelligente sul
blockchain
>
>**Link:** https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/harvest.json
>
>**Hash:** 25b95975cdc2b5c2d86d93de2bae687124f4f250ac02d3010cdfe8d4031dedc8

## 1.4 Formato JSON

Al produttore sarà richiesto di avere i dati in formato **JSON** su un hosting di sua preferenza (server e database proprietari, GitHub, DropBox, Drive, ecc ..) dove il produttore avrà mantenere la proprietà e il controllo totale dei dati.

JSON è un formato di file standard aperto e un formato di interscambio di dati, che utilizza testo **leggibile dall'uomo** per memorizzare e trasmettere oggetti di dati costituiti da coppie attributo-valore. 

Questo è un esempio di un passaggio della filiera in formato JSON:
```
{
  "name": "Harvest",
  "description": "La raccolta delle olive di Thor",
  "image": "https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
  "quantity": "90 kg",
  "method": "a mano",
  "randomValue": "N6L! Qw @ EEdXP844",
  "thumbnail" : "https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png" ,
  "Data": 
1600601747}
```

I file JSON che possiamo usare con Devoleum hanno una parte fissa composta da quattro parametri richiesti:` name`, `descrizione` e` thumbnail`. I file JSON possono essere arricchiti con molti più parametri. Ad esempio, coordinate GPS, collegamenti a documenti, voci di valori (es. Quantità), collegamenti ad altri media, ecc. Tutto ciò che l'utente pensa può aggiungere valori alla cronologia dei suoi prodotti. Questo è possibile perché utilizzando un JSON memorizziamo solo i riferimenti alla blockchain di Ethereum e non i file stessi.  

Come possiamo vedere guardando l'esempio sopra, in quel caso abbiamo arricchito il JSON con tre proprietà aggiuntive: `method`,` quantity` e `date`. "randomValue" è fortemente raccomandato per scopi provacy .

# 2. Come autenticare la propria catena di approvvigionamento utilizzando Devoleum

## 2.1 Prerequisiti per inserire dati in Devoleum

* Il primo prerequisito è disporre di un browser come **Google Chrome**, **Firefox** o **Brave**. Sul tuo smartphone puoi utilizzare **Metamask Mobile**.
* Il browser deve avere l '**Metamask estensione** installata, che ti permette di interagire con la blockchain, maggiori dettagli qui: [https://metamask.io/](https://metamask.io/)

> Un bel il video tutorial su Metamask può essere trovato [qui] (https://www.youtube.com/watch?v=yWfZnjkhhhg), ricordati di impostarlo sulla **Rinkeby rete**.  

*Nota: l'Metamask estensioneè necessaria solo per l'inserimento dei dati. Tutti possono leggere i dati ed esplorare le storie con un semplice browser da qualsiasi dispositivo.*

## 2.2 Configurare Metamask

* Impostare **MetaMask rete** su **Rinkeby**, Devoleum utilizza la Rinkeby rete di test, che non utilizza criptovalute reali ma fondi fittizi, perché lo scopo è tracciare i dati senza implicare transazioni finanziarie, quindi non c'è bisogno di acquistare criptovalute.
* Per ottenere fondi sulla **Rinkeby rete**, utilizza semplicemente un rubinetto disponibile a questo link: [https://faucet.rinkeby.io/](https://faucet.rinkeby.io/)


## 2.3 Devoleum piattaforme

Vai su [Devoleum.com](https://www.devoleum.com/) e scegli di utilizzare [Simulation](https://simulation.devoleum.com/) o [Collaboration](https://collaborations.devoleum.com/Histories). 

La **piattaforma di collaborazione** viene utilizzata per le collaborazioni ufficiali e necessita di una pre-approvazione. 

**Devoleum** è composto da tre parti principali:

* Profilo del commerciante
* Cronologia del prodotto
* Passaggio della catena di fornitura

Il commerciante può creare una cronologia di un prodotto e aggiungere passaggi, seguendo una struttura gerarchica. 

### Esempio

* Il commerciante "Evoil" crea un profilo sulla Devoleum piattaforma di simulazione, nella sezione del profilo
* Il commerciante crea una storia chiamata "Evoil 2020" sulla produzione delle EVOO bottiglienel 2020
* Il commerciante aggiunge un passaggio denominato "Raccolto" nella cronologia "Evoil 2020"
* Il commerciante aggiunge un passaggio denominato "Trasporto" nella cronologia "Evoil 2020"
* Il commerciante aggiunge un passaggio denominato "Elaborazione" nella cronologia "Evoil 2020"
* E aggiungi passaggi a questo cronologia fino alla vendita del prodotto su un mercato

Questo processo risulterà in una cronologia della catena di approvvigionamento su **Devoleum:!**

[esempio](https://github.com/Devoleum/docs/blob/master/img/EN/example_en.png?raw=true)

## 2.4 Storytelling

Come è possibile vedere nell'esempio sopra, ogni singolo passaggio permette di costruire una pagina che racconta la storia del prodotto grazie a **Devoleum**. La storia viene mostrata unendo i collegamenti JSON autenticati sulla blockchain di Ethereum dal commerciante.

La **storia del prodotto** con i riferimenti notarili blockchain può essere condivisa tramite un **link** o **codice QR**.

Al consumatore finale viene così data la possibilità di consultare facilmente la storia del prodotto grazie all'utilizzo di un link o alla scansione di un codice QR.

## 2.5 Aperto e accessibile

**Devoleum** è sviluppato con **accessibilità in base alla progettazione**, è possibile accedere alla cronologia dei prodotti utilizzando da qualsiasi browser mobile o desktop.

Inoltre la natura **open source** del progetto lascia infinite possibilità per la creazione di servizi di supporto e integrazione in siti di terze parti (es. Widget su e-commerce, integrazione con robot / macchinari per l'inserimento automatizzato dei dati) grazie all'utilizzo del **Devoleum API** che possono essere create anche dagli Devoleum utenti.



