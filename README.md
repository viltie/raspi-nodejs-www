# raspi-nodejs-www
Raspberry Pi NodeJS www server

Ensin pitää asentaa nodejs ja npm -ohjelmat jonka avulla www serveri pyörii. Myös git-versionhallinta tarvitaan jotta saadaan haettua versionhallinnasta tarvittavat tiedostot projektiin
```apt-get install nodejs npm git```

Sitten pitää hakea http-serveri versionhallinnasta
```git clone https://github.com/viltie/raspi-nodejs-www.git```

Nyt löydät http-palvelimen nykyisestä kansiosta.
Kansioita:
WWW - täällä sivuilla näkyvät tiedostot ovat, index.html on aina se sivu joka aukeaa ensimmäisenä kun palvelimelle otetaan yhteys
bin - täällä sijaitsevat ohjelman tarvitsemat tiedostot, ei saa siis poistaa
README.md - tämä tiedosto

Nyt palvelin käynnistetään komennolla
```nodejs bin/www```
