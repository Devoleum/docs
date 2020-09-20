# Guida JSON - hosting su Github

**[Github.com] (Github.com)** è una multinazionale americana che fornisce hosting per **sviluppo software** e **controllo versione** utilizzando [Git](https: //git-scm.com/). Offre la funzionalità **controllo della versione distribuita** e **gestione del codice sorgente (SCM)** di [Git](https://git-scm.com/), oltre alle proprie funzionalità.

## 1.1 Creare un repository pubblico

Su **Github** puoi creare un **repository pubblico** in cui archiviare i tuoi file **JSON** gratuitamente. 

![newrepo](https://github.com/Devoleum/docs/blob/master/img/EN/newrepogithub_en.png?raw=true)

## 1.2 Crea/carica file JSON

dopo aver creato il tuo **repository pubblico** , è possibile caricare o creare un file **JSON** direttamente nel repository

![createoruploadJSON](https://github.com/Devoleum/docs/blob/master/img/EN/createoruploadJSON_en.png?raw=true )

## 1.3 Struttura JSON

I file **JSON** che possiamo usare con **Devoleum** hanno una parte fissa:

```
{
  " name ":" Harvest ",
  " description ":" The harvest of Thor olives ",
  " image ":" https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png ",
  " quantity ":" 90kg ",
  " method ":" a mano " ,
  "randomValue": "N6L! Qw @ EEdXP844",
  "thumbnail": "https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png",
  "date" : 1600601747
}
```

I file **JSON** che possiamo usare con Devoleum hanno una parte fissa composta da quattro parametri obbligatori: `name`, `description` e `thumbnail`. I file **JSON** possono essere arricchiti con molti più parametri. Ad esempio, coordinate GPS, collegamenti a documenti, voci di valori (es. Quantità), collegamenti ad altri media, ecc. Tutto ciò che l'utente pensa può aggiungere valori alla storia dei suoi prodotti. Questo è possibile perché utilizzando un JSON memorizziamo solo i riferimenti alla **blockchain di Ethereum** e non i file stessi.  

Come possiamo vedere guardando l'esempio precedente, in quel caso abbiamo arricchito il **JSON** con tre proprietà aggiuntive: `method`, `quantity` e `date`. "RandomValue" è fortemente raccomandato per scopi privacy.

## 1.4 Crea un file JSON 

![JSONname](https://github.com/Devoleum/docs/blob/master/img/EN/JSONnamegithub_en.png?raw=true)

Per creare il tuo primo file **JSON** , dovrai solo digitare il nome del file seguito da .json e utilizzando la struttura **JSON** (indicata nella diapositiva precedente) e riempito con i dati che vuoi autenticare sulla **blockchain di Ethereum**.


## 1.5 Modelli di file JSON 

![JSONtemplatesrepo](https://github.com/Devoleum/docs/blob/master/img/EN/JSONtemplatesrepo_en.png?raw=true)

Puoi archiviare molti esempi di **JSON** strutture di file (commercianti, passaggi, storie) in questo **archivio Github: [https://github.com/Devoleum/templates-json](https://github.com/Devoleum/templates-json)**

## 1.6 Link al file JSON

Per vedere il link da inserire su **Devoleum**, è necessario cliccare sul pulsante RAW e copiare l'URL come puoi vedere nell'esempio qui sotto

 :![JSONlinkgithub](https://github.com/Devoleum/docs/blob/master/img/EN/JSONlinkgithub_en.png?raw=true)
 
 ![JSONlinkdevoleum](https://github.com/Devoleum/docs/blob/master/img/EN/JSONlinkonDevoleum_en.png?raw=true)

 
Dopo aver incluso il collegamento su **Devoleum**, il **JSON** dovrebbe essere visualizzato come una scheda. Dopodiché, per confermare sarà sufficiente fare clic sul pulsante "FINISH". 

## 1.7 Come includere un collegamento a un file JSON

**Anteprima scheda**

![Cardpreview](https://github.com/Devoleum/docs/blob/master/img/EN/cardpreviewdevoleum_en.png?raw=true)





