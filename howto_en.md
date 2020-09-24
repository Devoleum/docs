# Devoleum
**[Devoleum](devoleum.com)** is a web platform based on **Ethereum blockchain** that allows you to notarize and track supply chains of *digital* or *physical* products, use cases can range from traditional agricultural supply chain to streaming services.

Visit Devoleum at [Devoleum.com](Devoleum.com)

# 1.1 Easy to use

On **Devoleum** you can view the product history simply by using the *product history* **link** or using a **QR code**. The consumer will simply have to scan a QR Code.

![example](https://github.com/Devoleum/docs/blob/master/img/EN/easytouse_en.png?raw=true)

## 1.2 Transparency and accessibility 

**Devoleum** is an [**Open Source** project](https://github.com/Devoleum), everyone can implement it and use it in their own way. 

**Devoleum**'s aim is to offer a *transparent* and *accessible* service to consumers as well as manufacturers, using blockchain immutability as an added value to make the stored data authentic and impossible to manipulate.

## 1.3 You own your data

**Devoleum** only stores the *hash and the link relative to a JSON*.


> Example of the data stored in the smart contract on the blockchain
>
> **Link:** https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/harvest.json
>
> **Hash:** 25b95975cdc2b5c2d86d93de2bae687124f4f250ac02d3010cdfe8d4031dedc8

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

The JSON files that we can use with Devoleum have a fixed part composed of four required parameters: `name`, `description`, `image`, `thumbnail` and ´date`. The JSON files can be enriched with many more parameters. For example, GPS coordinates, document links, values entries (eg. quantity), links to other media, etc. Everything that the user thinks can add values to the history of their products. This is possible because using a JSON we store only the references to the Ethereum blockchain and not the files themself.  

| key | description |
| ------ | ------ |
| name | name that idenfies a merchant, product or a supply chain step |
| description | a description |
| image | image direct link |
| thumbnail | thumbnail direct link |
| date | a date es. 25/09/2020 |

As we can see looking at the example above, in that case we have enriched the JSON with three additional properties: `method`, `quantity` and `date`. The `randomValue` is strongly recommended for provacy purposed.

## 1.5 JSON format Multilanguage

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
      "date":"20/10/2019"
   },
   "it":{
      "name":"Raccolta",
      "description":"Raccolta olive Thor",
      "image":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/harvest.png",
      "quantità":"90kg",
      "metodo":"a mano",
      "randomValue":"N6L!Qw@EEdXP844",
      "thumbnail":"https://raw.githubusercontent.com/Devoleum/templates-json/master/steps/imgs/thumbnails/small_harvest.png",
      "date":"20/10/2019"
   }
}
```

In this case, the structure of the first JSON is repeated for each language (**multilanguage**) with which you want to present the story. In this example, the supply chain step data is entered in English ("en") and Italian ("it").

Common language parameters:

| key | language |
| ------ | ------ |
| en | english  |
| it | italian |
| fr | franch |
| es | spanish |
| de | german |

# 2. How to notarize your supply chain using Devoleum

## 2.1 Prerequisites to insert data into Devoleum

* The first prerequisite is to have a browser like **Google Chrome**, **Firefox** or **Brave**. On your smarthone you can use **Metamask Mobile**.
* The browser must have the **Metamask extension** installed, which allows you to interact with the blockchain, more details here: [https://metamask.io/](https://metamask.io/)

> A nice video tutorial about Metamask can be found [here](https://www.youtube.com/watch?v=yWfZnjkhhhg), remember to set it to the **Rinkeby network**.  

*Note: Metamask extension is only needed for data insertion. Everyone can read the data and explore histories with a simple browser from any device.*

## 2.2 Configure Metamask

* Set **MetaMask network** to **Rinkeby**, Devoleum uses the Rinkeby test network, which does not use real cryptocurrencies but fictitious funds, because the purpose is to track the data without implying financial transactions, so no need to buy cryptocurrencies.
* To get funds on the **Rinkeby network**, simply use a faucet available at this link: [https://faucet.rinkeby.io/](https://faucet.rinkeby.io/)


## 2.3 Devoleum platforms

Go on [Devoleum.com](https://www.devoleum.com/) and chose to use the [Simulation](https://simulation.devoleum.com/) or the [Collaboration](https://collaborations.devoleum.com/Histories) platform. 

The **Collaboration platform** is used for official collaborations and needs a pre approval. 

**Devoleum** is composed by three main parts:

* Merchant profile
* Product history
* Supply chain’s step

The merchant can create a history about a product and add steps into it, following a hierarchy structure. 

### Example

* The merchant “Evoil” creates a profile on Devoleum simulation platform, in the profile section
* The merchant creates an history called “Evoil 2020” about the production of the EVOO bottles in the 2020
* The merchant add a step named “Harvest” in the history “Evoil 2020”
* The merchant add a step named “Transport” in the history “Evoil 2020”
* The merchant add a step named “Processing” in the history “Evoil 2020”
* And add steps to this history until the product is sold in a market

This process will result in a supply chain history on **Devoleum**:

![example](https://github.com/Devoleum/docs/blob/master/img/EN/example_en.png?raw=true)

## 2.4 Storytelling

As it's possible to see in the example above, every single step allows you to build a page that tells the story of the product thanks to **Devoleum**. The story is shown by merging the JSON links notarized on the Ethereum blockchain by the merchant.

The **history of the product** with the blockchain notarization references can be shared via a **link** or **QR code**.

The final consumer is thus given the opportunity to easily consult the history of the product thanks to the use of a link or the scan of a QR code.

## 2.5 Open and Accessible

**Devoleum** is developed with **accessibility by design**, the history of the products can be access using from any mobile or desktop browser.

Furthermore, the **open source** nature of the project leaves infinite possibilities for creating support services and integration in third party sites (eg widgets on e-commerce, integration with robots / machinery for automated data entry) thanks to the use of the **Devoleum APIs** which they can also be created by Devoleum users.


