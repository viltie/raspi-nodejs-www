# raspi-nodejs-www
Raspberry Pi NodeJS www server

<br><br>
Tätä projektia varten tarvitset seuraavat:<br>
- Raspberry Pi (rev2+)<br>
- Toimiva nettiyhteys<br>
- Toimiva debian tai ubuntu käyttöjärjestelmä sd-kortille<br>
<br>
Kun sinulla on toimiva Raspberry pi, johon olet kirjautunut sisälle ja siinä on toimiva verkkoyhteys niin voit aloittaa asentamaan raspberry pi-koneeseesi www-palvelinta<br>
Ensin pitää asentaa nodejs ja npm -ohjelmat jonka avulla www serveri pyörii. Myös git-versionhallinta tarvitaan jotta saadaan haettua versionhallinnasta tarvittavat tiedostot projektiin<br>
```apt-get install nodejs npm git```
<br>
Sitten pitää hakea http-serveri versionhallinnasta<br>
```git clone https://github.com/viltie/raspi-nodejs-www.git```
<br>
Sitten sinun pitää mennä kansioon raspi-nodejs-www joka juuri luotiin git-komennon toimesta ja sinne haettiin tiedostot<br>
```cd raspi-nodejs-www```
Nyt löydät http-palvelimen nykyisestä kansiosta.<br>
Kansioita:<br>
public - täällä sivuilla näkyvät tiedostot ovat, index.html on aina se sivu joka aukeaa ensimmäisenä kun palvelimelle otetaan yhteys<br>
bin - täällä sijaitsevat ohjelman tarvitsemat tiedostot, ei saa siis poistaa<br>
lib - palvelimen tarvitsemat kirjastot<br>
README.md - tämä tiedosto<br>
<br>
Nyt palvelin käynnistetään komennolla<br>
```nodejs bin/www```
