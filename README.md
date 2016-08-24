# raspi-nodejs-www
Raspberry Pi NodeJS www server

Ensin pitää asentaa nodejs ja npm -ohjelmat jonka avulla www serveri pyörii. Myös git-versionhallinta tarvitaan jotta saadaan haettua versionhallinnasta tarvittavat tiedostot projektiin<br>
```apt-get install nodejs npm git```
<br>
Sitten pitää hakea http-serveri versionhallinnasta<br>
```git clone https://github.com/viltie/raspi-nodejs-www.git```
<br>
Nyt löydät http-palvelimen nykyisestä kansiosta.<br>
Kansioita:<br>
WWW - täällä sivuilla näkyvät tiedostot ovat, index.html on aina se sivu joka aukeaa ensimmäisenä kun palvelimelle otetaan yhteys<br>
bin - täällä sijaitsevat ohjelman tarvitsemat tiedostot, ei saa siis poistaa<br>
README.md - tämä tiedosto<br>
<br>
Nyt palvelin käynnistetään komennolla<br>
```nodejs bin/www```
