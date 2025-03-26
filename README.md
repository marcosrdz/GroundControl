# Ground Control

`````````````````````````````````````````````````````````````````
///::---......```````````````````````````````` ``````````````````````````````````````...............
::::---.....```````````````````````````````` .-.-`-```..```````````````````````````````.............
:::---....````````````````````````.-.``--```.///////:/+/:/---....``````````````````````.............
::---....``````````````````````````://::/:..//////////+++++++++++:--..``````````````````............
:---...````````````````````````.///////////////////////+++++++++++ooo+:-```````````````````.........
---...``````````````````````.-////////////////////////+//+++++++++oooo/-.```````````````````........
--...````````````````````.-////////////////////////////+/++++++++oooooo++/.````````````````````.....
-...````````````````````-:/+//////////////////////////+++++++++++oooooooooo:````````````````````....
...````````````````````:++++///////////////////////////++++++++++ooooooooooo+-```````````````````...
..```````````````````-/+++++//////////////////////////+++++++++++ooooooooooooo:````````````````````.
.``````````````````./+++++++//////////////////////////+++++++++++oooooooooooooo/````````````````````
.`````````````````./+++++++++++////////////////////////+++++++++++oooooooooooooo.``````````````````.
``````````````````.+++++++++++/////////////////////////++++++++++++ooooooooooooo-```````````````````
```````````````````-++++++++++//////////////////////////++++++++++++oooooooooooo/```````````````````
````````````````````/++++//++//////////////////////////////://++/-++oooooooooooo:```````````````````
````````````````````-/+//////////////////////////////////:-.`../..++oooooooooooo-```````````````````
`````````````````````//+///////////::::::::::://///////////-.`````/++ooooooooooo:```````````````````
``````````````````  `:////////:-.````````````.://////////+++///:-``-://+oooooooo:```````````````````
``````````````````   -/////:.``            `-////////////+++++:-``````:+oooooooo-```````````````````
```````````````````  :++/:``             `-//////////////++/:.````````.+oooooooo.```````````````````
```````````````````` .++/.              .:////////////////-``   ```````.++ooooo+````````````````````
`````````````````````.++/`            `-///////////////:.`      ````````-+ooooo/````````````````````
`````````````````````.++:            `://////////////:.`         ````````/++ooo:````````````````````
`````````````````````.++-           `://///////////-.`            ```````-+++oo-````````````````````
`````````````````````-++.          `/////////////:`               ```````.+++oo.````````````````````
`````````````````````:++.         `:////////////.`  ````           ```````+++oo.````````````````````
`````````````````````/o+.``       `--:////////:``.--.````````      ```````++++o-````````````````````
`````````````````````/oo.```  `...:-::.-://///-://-``--:::://:-.` ````````++++o:````````````````````
`````````````````````/oo-`````.-``-.-:```://////-` `.`````--:/:::. ``````.++++o-````````````````````
`````````````````````:oo:``````---.--.-:://///:`      `````----:-` ``````-+++++`````````````````````
`````````````````````:oo+```````:++/:-://////-`         ``...-.``  ``````/+++++.````````````````````
``````````````````````:+o-`````:+/-``-//////.                     ```````+++++/`````````````````````
```````````````````````:+/````-:.` `-++++//.                      ``````.//+/+:`````````````````````
````````````````````````.+:````````-+++++:`                       `````````.::``````````````````````
`````````````````````````.:.``````.++++/-`                     `````````````/.``````````````````````
```````````````````````````:``````/+++/.   ..    .:.       ````````````````:/```````````````````````
```````````````````````````/`````.+++:`    ``    ```    `````````````````.:+-```````````````````````
```````````````````````````/-````/++-```             ````````````````-//++++````````````````````````
```````````````````````````/-````+o:````           `````````````````.++++++/````````````````````````
```````````````````````````/:```.++```````.--.``..``````````````````/+o++++:````````````````````````
```````````````````````````//```.o:````.://///:::/:::-.````````````-+++++++/````````````````````````
```````````````````````````+o-``-o-````..``.......````````````````-/+ooooo++````````````````````````
``````````````````````````-oo+.`:o.`````....`````````````````````::.+ooooo++.```````````````````````
`````````````````````````.+ooo+.:+.`````````......`````````````.:-``+ooooo+:-```````````````````````
`````````````````````````/ooooo-/+````````````````````````````--```.+oooooo/````````````````````````
````````````````````````/oooooo./+`````````````````````````````````.oooooo/+````````````````````````
```````````````````````:ooo++o+`/+`````````````````````````````````.oooo+/:`````````````````````````
``````````````````````.:+/:-//-`++`````````````````````````````````.oooo-`.`````````````````````````
....````````````````````````.```+/``````````````````````````````````+oo:````````````````````````````
.....``````````````````````````.+/``````````````````````````````````:+-`````````````````````````````
......`````````````````````````.+:````````````````````````````````````````````````````````````````..
.........``````````````````````-+:``````````````````````````````````````````````````````````````....
...........````````````````````-o-`````````````````````````````````````````````````````````````.....
.............``````````````````:o-```````````````````````````````````````````````````````````.......
...............````````````````:o-`````````````````````````````````````````````````````````.........
................```````````````/o.```````````````````````````````````````````````````````...........
....................``..```````/+.``````````````````````````````````````````````````.`..............
...........................````:/``````````````````````````````````````.``..........................
.............................`.//````````````````````````````````````...............................
----..........................`..``````````````````````````````.....................................
`````````````````````````````````````````````````````````````````

## Can you hear me, Major Tom?

Push notifications server for bitcoin wallets. Processes blocks & mempool in search of subscribed onchain addresses.
Built with typescript, expressjs, mariadb & [openapi](https://editor.swagger.io/?url=https://raw.githubusercontent.com/BlueWallet/GroundControl/master/openapi.yaml).

In memory of David Bowie

### Installation

```shell script
npm i
npm start
npm run worker-blockprocessor
npm run worker-processmempool
npm run worker-sender
```

Works well on Heroku (you'll need `JawsDB Maria` addon)

### Environment variables

Set them as env variables or put them into `.env` file in project root dir.

- `JAWSDB_MARIA_URL` for example `mysql://username:password@host:port/database`
- ~~`FCM_SERVER_KEY` hex encoded~~ deprecated (in favor of json key file) after FCM XMPP and HTTP legacy APIs was deprecated; the new one is HTTP v1 API; theres also a new uri to post payload
- `APNS_P8` hex encoded
- `APNS_P8_KID` issuer key which is "key ID" of your p8 file
- `APPLE_TEAM_ID` "team ID" of your developer account
- `BITCOIN_RPC` for example `http://username:password@host:8332`
- `APNS_TOPIC` for example `io.bluewallet.bluewallet`
- `GOOGLE_KEY_FILE` - json file with Google key for FCM, in hex
- `GOOGLE_PROJECT_ID` - acquired with the key file


### Getting certificates

- outdated https://dev.to/jakubkoci/react-native-push-notifications-313i
- https://stackoverflow.com/questions/44631803/ios-swift-how-to-create-p8-file/67533665#67533665
- get P8 hex `xxd -p file.p8 | tr -d '\n'` (google key file as well)
- https://firebase.google.com/docs/cloud-messaging/migrate-v1

### License

MIT
