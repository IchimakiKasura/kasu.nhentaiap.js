<div align="center">
<img src="https://i.redd.it/fkg9yip5yyl21.png" height="140px" title="nhentai"/>
<h1>N-hentai API</h1>
<p>

[![stable version](https://img.shields.io/npm/v/kasu.nhentaiapi.js?color=green&label=stable%20version&style=for-the-badge)](https://ichimakikasura.github.io/kasu.nhentaiapi.js/changelogs#360)
[![Downloads](https://img.shields.io/npm/dt/kasu.nhentaiapi.js.svg?maxAge=3600&style=for-the-badge)](https://ichimakikasura.github.io/kasu.nhentaiapi.js/)
[![Build Status](https://img.shields.io/travis/IchimakiKasura/kasu.nhentaiapi.js.svg?style=for-the-badge)](https://app.travis-ci.com/IchimakiKasura/kasu.nhentaiapi.js)
![Snyk Vulnerabilities for npm package](https://img.shields.io/snyk/vulnerabilities/npm/kasu.nhentaiapi.js?style=for-the-badge)
![minified](https://img.shields.io/badge/-minified%20-gray?style=for-the-badge "^3.0.0 versions are now already MINIFIED!")<br/>
![lol](https://img.shields.io/badge/-Astolfo--chan%20is%20very%20happy%20that%20you%20are%20well%20cultured%20to%20use%20this-ff1100?style=for-the-badge "unofficial api of nhentai")<br>
[![kasu.nhentaiapi.js](https://snyk.io/advisor/npm-package/kasu.nhentaiapi.js/badge.svg)](https://snyk.io/advisor/npm-package/kasu.nhentaiapi.js "bruh")
</div>

The "N-hentai-api" is a fast and easy to use api for connecting to [nhentai.net]("https://nhentai.net/") and [nhentai.to]("https://nhentai.to/") data.
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
const Example = require('KasuNhentai'); // experimental, if it doesn't work use 'kasu.nhentaiapi.js'
const ExampleApi = new Example();
/**
 * or const ExampleApi = new Example('start', "https://nhentai.net");
 * If you don't want to add the url and connection.start() after it.
 * because it automatically start the connection.
 * 
 * Check the documentation or the homepage for more info.
*/

//          ----number | strings can do----
const ID = 228922 //or "228922" or "https://nhentai.net/g/228922"
async function json(){

    // start the connection
    ExampleApi.url = "https://nhentai.net"
    ExampleApi.connection.start()

    const val = await ExampleApi.getID(ID).json()
    val.url
    // OR
    ExampleApi.getID(ID).json(data=>{data.url})
    // OR
    (await ExampleApi.getID(ID).json()).url
    // result: https://nhentai.net/g/228922/

    // closes the connection
    ExampleApi.connection.close()
}
```
---
## For CLI `new`
run Bash

    nhentai 228922 
run batch

    nhentaibat 228922

check the changelogs for more info

---

<div align="center">

<h3> (≧▽≦*) Other Informations (≧▽≦*)</h3>

[![](https://user-images.githubusercontent.com/80595346/137737347-4585f4d6-a590-43e5-af3e-1a3b489886f6.png)](https://ichimakikasura.github.io/kasu.nhentaiapi.js/licenses "MIT Licence")<br/>
[![](https://user-images.githubusercontent.com/80595346/137737333-90ca92bc-5d01-4119-b5c4-d76a4867946d.png)](https://ichimakikasura.github.io/kasu.nhentaiapi.js/documentation "API Documentation")<br/>
[![](https://user-images.githubusercontent.com/80595346/137737338-26bd22d1-370f-4521-858e-5abd34b8fade.png)](https://ichimakikasura.github.io/kasu.nhentaiapi.js/changelogs "Update History")<br/><br/>
<a href="https://ichimakikasura.github.io/kasu.nhentaiapi.js/" title="Homepage"><img src="https://ichimakikasura.github.io/kasu.nhentaiapi.js/other/previewLink.png" width="55%" alt="embed"><br/>
<hr>
Enjoy using it! crediting me will be an appreciation!<br/>
<a href="https://github.com/IchimakiKasura/kasu.nhentaiapi.js" title="Star it!">Star</a> it if you like it!<br/>
<img src="https://raw.githubusercontent.com/IchimakiKasura/IchimakiKasura/main/astorufo.png" title="Created by Ichimaki" height="60"/>