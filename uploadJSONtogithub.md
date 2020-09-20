# JSON Guide - hosting on Github

**[Github.com](Github.com)** is an American multinational corporation that provides hosting for **software development** and **version control** using [Git](https://git-scm.com/). It offers the **distributed version control** and **source code management (SCM)** functionality of [Git](https://git-scm.com/), plus its own features.

## 1.1 Create a public repository

On **Github** you can create a **public repository** in which store your **JSON** files for free. 

![]

## 1.2 Create/Upload JSON files

After creating your **public repository**, it’s possible to upload or create a **JSON** file directly in the repository

![]

## 1.3 JSON structure

The **JSON**  files that we can use with **Devoleum** have a fixed part:

![]

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

The **JSON**  files that we can use with Devoleum have a fixed part composed of four required parameters: `name`, `description` and `thumbnail`. The **JSON**  files can be enriched with many more parameters. For example, GPS coordinates, document links, values entries (eg. quantity), links to other media, etc. Everything that the user thinks can add values to the history of their products. This is possible because using a JSON we store only the references to the **Ethereum blockchain** and not the files themself.  

As we can see looking at the example above, in that case we have enriched the **JSON**  with three additional properties: `method`, `quantity` and `date`. The `randomValue` is strongly recommended for provacy purposed.

## 1.4 Create a JSON file 

![]

To create your first **JSON**  file, you will need just to type the name of the file followed by .json and using the **JSON**  structure (indicated in the previous slide) and filled with the data that you want to notarize on the **Ethereum blockchain**.


## 1.5 JSON file templates 

![]

You can file many examples of **JSON** file structures (merchants, steps, histories) on this **Github resository: [https://github.com/Devoleum/templates-json](https://github.com/Devoleum/templates-json)**

## 1.6 JSON file link

To see the link to insert on **Devoleum**, it’s necessary to click on the RAW button and copy the url as you can see in the example below:

 ![]
 
After including the link on **Devoleum**, the **JSON**  should be displayed as a card. After that, to confirm it will be necessary just to click on the `FINISH` button. 

## 1.7 How to include a JSON file link

**Card preview**

![]




