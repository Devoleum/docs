# JSON Struttura Multilingua

Questo è un esempio dello stesso passaggio della filiera presentato nel precedente paragrafo in un formato JSON **Multilingua**:

```
{
   "multi_lang":true,
   "section": "step",
   "en":{
      "name":"Harvest",
      "description":"The harvest of Thor olives",
      "image":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
      "quantity":"90kg",
      "method":"by hand",
      "thumbnail":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png",
      "date":"11/09/2020"
   },
   "it":{
      "name":"Raccolta",
      "description":"Raccolta olive Thor",
      "image":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
      "quantità":"90kg",
      "metodo":"a mano",
      "thumbnail":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png",
      "date":"11/09/2020"
   }
}
```

In questo caso la struttura del JSON di prima è ripetuta per ogni lingua (**multilingua**) con la quale si desidera presentare la storia. In questo esempio i dati del passaggio della filiera sono immessi in inglese ("en") ed italiano ("it").

Parametri lingue più comuni:

| acronimo | lingua   |
| -------- | -------- |
| en       | inglese  |
| it       | italiano |
| fr       | francese |
| es       | spagnolo |
| de       | tedesco  |
