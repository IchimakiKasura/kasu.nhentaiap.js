<div align="center">
<img src="https://i.redd.it/fkg9yip5yyl21.png" height="50" title="nhentai"/><h1 style="font-weight:1000">N-hentai API</h1>
<p>

[![stable version](https://img.shields.io/badge/stable%20version-3.2.1-brightgreen?style=for-the-badge)](https://github.com/IchimakiKasura/kasu.nhentaiapi.js/blob/main/CHANGELOG.md#321)
[![Build Status](https://img.shields.io/travis/IchimakiKasura/kasu.nhentaiapi.js.svg?style=for-the-badge)](https://app.travis-ci.com/IchimakiKasura/kasu.nhentaiapi.js)
![minified](https://img.shields.io/badge/-minified%20-gray?style=for-the-badge "^3.0.0 versions are now already MINIFIED!")<br/>
<img src="https://img.shields.io/badge/-Astolfo--chan%20is%20very%20happy%20that%20you%20are%20well%20cultured%20to%20use%20this-ff1100?style=for-the-badge" title="unofficial api of nhentai"/>
</div>

The "N-hentai-api" is a fast and easy to use api for connecting to [nhentai.net]("https://nhentai.net/") data.
* Fast*
* Easy to use
* Reliable* :>
* > Discord friendly?

### Install
To install "N-hentai-api" type these:
```
npm i kasu.nhentaiapi.js
```
## Examples
### How to use n-hentai-api
To get the basic info about the ID/Doujin:
```js
const Example = require('kasu.nhentaiapi.js');
const ExampleApi = new Example(); // name any you want "api, kasu, nhentai, ..." 

//          ----number | strings can do----
const ID = 228922 //or "228922" or "https://nhentai.net/g/228922"
async function json(){
    const val = await ExampleApi.getID(ID).json()
    val.url
    // OR
    ExampleApi.getID(ID).json(data=>{data.url})
    // OR
    (await ExampleApi.getID(ID).json()).url
    // result: https://nhentai.net/g/228922/
}
```
# Click here for more info
[![](https://user-images.githubusercontent.com/80595346/137633689-c34f0162-4c6c-43ed-972d-7df8d372ef47.png)](https://github.com/IchimakiKasura/kasu.nhentaiapi.js/blob/main/LICENSE)
[![](https://user-images.githubusercontent.com/80595346/137633687-421900f1-3660-408f-a716-96753f1dc32e.png)](https://github.com/IchimakiKasura/kasu.nhentaiapi.js/blob/main/CHANGELOG.md)
[![](https://user-images.githubusercontent.com/80595346/137633691-98187d07-fa4b-4c2d-91f5-8be5190a9c38.png)](https://github.com/IchimakiKasura/kasu.nhentaiapi.js/blob/main/docs/Documentation.md)
<hr>
<p align="center">
Enjoy using it! crediting me will be an appreciation!<br/>
<a href="https://github.com/IchimakiKasura/kasu.nhentaiapi.js" title="Star it!">Star</a> it if you like it!<br/>
<img src="https://raw.githubusercontent.com/IchimakiKasura/IchimakiKasura/main/astorufo.png" title="Created by Ichimaki" height="60"/>