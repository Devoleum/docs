# Devoleum
**[Devoleum](devoleum.com)** is a web platform based on **Ethereum blockchain** that allows you to notarize and track supply chains of *digital* or *physical* products, use cases can range from traditional agricultural supply chain to streaming services.

Visit Devoleum at Devoleum.com

# 1. Easy to use

On **Devoleum** you can view the product history simply by using the *product history* **link** or using a **QR code**. The consumer will simply have to scan a QR Code.

[!image]()

## 1.2 Transparency and accessibility 

**Devoleum** is an [**Open Source** project](https://github.com/Devoleum), everyone can implement it and use it in their own way. 

**Devoleum**'s aim is to offer a *transparent* and *accessible* service to consumers as well as manufacturers, using blockchain immutability as an added value to make the stored data authentic and impossible to manipulate.

## 1.3 You own your data

**Devoleum** only stores the *hash and the link relative to a JSON*.


> Example of the data stored in the smart contract on the blockchain
**Link:** https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/harvest.json
**Hash:** 25b95975cdc2b5c2d86d93de2bae687124f4f250ac02d3010cdfe8d4031dedc8

## 1.4 JSON format

The producer will be required to have the data in **JSON** format on a hosting of his preference (proprietary servers and databases, GitHub, DropBox, Drive, 
etc ..) where the producer will keep the ownership and total control of the data.
JSON is an open standard file format, and data interchange format, that uses **human-readable** text to store and transmit data objects consisting of attribute–value pairs. 

This is an example of a supply chain step in JSON format:
```
{
  "name": "Harvest",
  "description": "The harvest of Thor olives",
  "image": "https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
  "quantity": "90kg",
  "method": "by hand",
  "randomValue": "N6L!Qw@EEdXP844",
  "thumbnail" : "https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png" ,
  "date" : 1600601747
}
```

The JSON files that we can use with Devoleum have a fixed part composed of four required parameters: `name`, `description` and `thumbnail`. The JSON files can be enriched with many more parameters. For example, GPS coordinates, document links, values entries (eg. quantity), links to other media, etc. Everything that the user thinks can add values to the history of their products. This is possible because using a JSON we store only the references to the Ethereum blockchain and not the files themself.  

As we can see looking at the example above, in that case we have enriched the JSON with three additional properties: `method`, `quantity` and `date`. The `randomValue` is strongly recommended for provacy purposed.

# 2. How to notarize your supply chain using Devoleum
