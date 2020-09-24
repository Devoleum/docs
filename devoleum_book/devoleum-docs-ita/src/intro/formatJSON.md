# Formato JSON

Al produttore sarà richiesto di avere i dati in formato **JSON** su un hosting di sua preferenza (server e database proprietari, GitHub, DropBox, Drive, ecc ..) dove il produttore conserva la proprietà e il controllo totale dei dati.

JSON è un formato di file standard aperto e un formato di interscambio di dati, che utilizza testo **leggibile dall'uomo** per memorizzare e trasmettere oggetti di dati costituiti da coppie attributo-valore.

Questo è un esempio di un passaggio della filiera in formato JSON:
```
{
  "name": "Harvest",
  "description": "The harvest of Thor olives",
  "image": "https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
  "quantity": "90kg",
  "method": "by hand",
  "randomValue": "N6L!Qw@EEdXP844",
  "thumbnail": "https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png",
  "date": "11/09/2020"
}
```

I file JSON che possiamo usare con Devoleum hanno una parte fissa composta da quattro parametri richiesti:` name`, `description`, `image`, ` thumbnail` e `date`. I file JSON possono essere arricchiti con molti più parametri. Ad esempio, coordinate GPS, collegamenti a documenti, voci di valori (es. Quantità), collegamenti ad altri media, ecc. Tutto ciò che l'utente pensa può aggiungere valori alla cronologia dei suoi prodotti. Questo è possibile perché utilizzando un JSON memorizziamo solo i riferimenti alla blockchain di Ethereum e non i file stessi.  

| parametro | descrizione |
| ------ | ------ |
| name | nome che identifica l'azienda, il prodotto o il passaggio  |
| description | una descrizione |
| image | link diretto ad una immagine |
| thumbnail | versione miniaturizzata dell'immagine |
| date | data di riferimento es. 25/09/2020 |

Come possiamo vedere guardando l'esempio sopra, in quel caso abbiamo arricchito il JSON con tre proprietà aggiuntive: `method` e `quantity`. "randomValue" è fortemente raccomandato per tutelare maggiormente la privacy.
