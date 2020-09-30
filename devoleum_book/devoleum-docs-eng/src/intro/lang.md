# JSON format Multilanguage

This is an example of a supply chain step in a **Multilanguage**: JSON format 

```
{
   "multi_lang":true,
   "en":{
      "name":"Harvest",
      "description":"The harvest of Thor olives",
      "image":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
      "quantity":"90kg",
      "method":"by hand",
      "randomValue":"N6L!Qw@EEdXP844",
      "thumbnail":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png",
      "date":"11/09/2020"
   },
   "it":{
      "name":"Raccolta",
      "description":"Raccolta olive Thor",
      "image":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
      "quantità":"90kg",
      "metodo":"a mano",
      "randomValue":"N6L!Qw@EEdXP844",
      "thumbnail":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png",
      "date":"11/09/2020"
   }
}
```

In this case, the structure of the first JSON is repeated for each language (**multilanguage**) with which you want to present the story. In this example, the supply chain step data is entered in English ("en") and Italian ("it").

Common language parameters:

| key | language |
| ------ | ------ |
| en | english  |
| it | italian |
| fr | french |
| es | spanish |
| de | german |