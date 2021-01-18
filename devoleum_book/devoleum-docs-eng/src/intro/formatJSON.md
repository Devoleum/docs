# JSON format

The producer will be required to have the data in **JSON** format on a hosting of his preference (proprietary servers and databases, GitHub, DropBox, Drive, 
etc ..) where the producer will keep the ownership and total control of the data.
JSON is an open standard file format, and data interchange format, that uses **human-readable** text to store and transmit data objects consisting of attribute–value pairs. 

This is an example of a supply chain step in a **Multilanguage**: JSON format

```
{
   "multi_lang": true,
   "section": "step",
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
| --- | -------- |
| en  | english  |
| it  | italian  |
| fr  | french   |
| es  | spanish  |
| de  | german   |

The JSON files that we can use with Devoleum have a fixed part composed of four required parameters: `name`, `description`, `image`, `thumbnail` and ´date`. The JSON files can be enriched with many more parameters. For example, GPS coordinates, document links, values entries (eg. quantity), links to other media, etc. Everything that the user thinks can add values to the history of their products. This is possible because using a JSON we store only the anonymized hash into the Ethereum blockchain and not the files themself.  

| key | description |
| ------ | ------ |
| name | name that idenfies a merchant, product or a supply chain step |
| section | identifies the section of the JSON, it can take only one of these three values:: merchant_profile history step . The user profile will have the "merchant_profile" section value, the history of a product we'll have "history", a step will have a "step" section value|
| description | a description |
| image | image direct link |
| thumbnail | thumbnail direct link |
| date | a date es. 25/09/2020 |