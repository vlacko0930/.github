# Érdeklődésünkbe tartozó néhány projekt

## Diatár
![last commit](https://img.shields.io/github/last-commit/diatar/diatar-lazarus?style=for-the-badge)
![commit activity](https://img.shields.io/github/commit-activity/y/diatar/diatar-lazarus?style=for-the-badge) 
![issues](https://img.shields.io/github/issues/diatar/diatar-lazarus?style=for-the-badge)
![pull requests](https://img.shields.io/github/issues-pr/diatar/diatar-lazarus?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-polyJoe-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2FpolyJoe)

Rengeteg templomban használt kivetítőrendszer, amivel már nem csak énekeket lehet kivetíteni.
- Kulcsszavak: *lazarus, mqtt, websocket, tcp/ip*
- Platformok: *Windows, Linux, Rasperrby Pi, Android*
- Forráskód: [github.com/diatar/diatar-android](https://github.com/diatar/diatar-android), [diatar/diatar-lazarus](https://github.com/diatar/diatar-lazarus), [diatar/diatar-dtxs](https://github.com/diatar/diatar-dtxs), [diatar/diatar-web](https://github.com/diatar/diatar-web)
- Honlap: [diatar.eu](https://diatar.eu)

**A fejlesztő Hozé is itt lesz a II. Szent József Hackathonon**

### Legérdekesebb fejlesztési irányok, amire szükség lenne:
- **A diatárba meg előkészíthetnénk az igenaptár alapján minden olvasmányt jó előre. Ezek egyszerű szövegfájlok speciál formátumban.**
- Bibliával betanított SpeechToText dia gyártásával könnyen feliratozni lehetne még a prédikációt is, ami sokaknak hasnzos.
- TCP/IP csomagok helyett [websocketre átállással](https://github.com/diatar/diatar-lazarus/issues/1) több vetítő rendszer is működhet egyszerre, és mobilon is követni lehetne a kivetítést.

## NapiPakk 
![](https://img.shields.io/github/last-commit/szentjozsefhackathon/napi-lelki-batyu?style=for-the-badge)
![](https://img.shields.io/github/commit-activity/y/szentjozsefhackathon/napi-lelki-batyu?style=for-the-badge) 
![](https://img.shields.io/github/issues/szentjozsefhackathon/napi-lelki-batyu?style=for-the-badge)
![](https://img.shields.io/github/issues-pr/szentjozsefhackathon/napi-lelki-batyu?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-borazslo-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2Fborazslo)

A KAPP+ alkalmazást kiszolgáló igenaptár, direktórium, napi szent főként JSON formátumban.
- Kulcsszavak: *json, python, javascript, szöveggondozás*
- Forráskód: [github.com/szentjozsefhackathon/napi-lelki-batyu](https://github.com/szentjozsefhackathon/napi-lelki-batyu)
- Honlap: [github page](https://szentjozsefhackathon.github.io/napi-lelki-batyu/)

### Fontosabb tennivalók és lehetőségek:
- Az örök igenaptár és direktórium új kis honlapjának tovább csinosítása.
- A json fáljokból összeállító python kód fejlesztésével, meg a frontend összekaparásával.
- Ennek része programozás nélküli szövegkorrektúrázás.

## Gyóntatáskereső
![owner](https://img.shields.io/badge/Owner-borazslo-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2Fborazslo)

Ha a gyóntatószékben épp felkapcsolják a lámpát, megy a jelzés a szervernek, hogy megkezdődött a gyóntatás.

Shelly kütyük beszerelésével lámpakapcsolásra jelzést küldünk a szervernek, hogy gyóntatás van nálunk. Ezekből miserend id-hoz rendelve mindig friss adatbázist gyártunk. Lásd: https://github.com/borazslo/miserend.hu/issues/206

- Kulcsszavak: *terv, API, hardware*
  
### Következő lépés:
- **Öt szegedi templomban akár shelly beszerelés is része lehet a programnak.**

## Miserend.hu
![](https://img.shields.io/github/last-commit/borazslo/miserend.hu?style=for-the-badge)
![](https://img.shields.io/github/commit-activity/y/borazslo/miserend.hu?style=for-the-badge) 
![](https://img.shields.io/github/issues/borazslo/miserend.hu?style=for-the-badge)
![](https://img.shields.io/github/issues-pr/borazslo/miserend.hu?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-borazslo-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2Fborazslo)

Mintegy 5000 magyar nyelvű misézőhely összefogása és frissentartása nem kis feladat.
- Kulcsszavak: *API, symphony, php, mysql, cdi*
- Platformok: *web, android, ios*
- Forráskód: [github.com/borazslo/miserend.hu](https://github.com/borazslo/miserend.hu)
- Honlap: [miserend.hu](https://miserend.hu)

### Néhány teendő
- Amíg a kód portolása és újrarendezése nem teljes, addig csak nagyon körülhatárolt fejlesztéseket lehet végrehajtani. Lásd: https://github.com/borazslo/miserend.hu/issues/177 Portolás fővezére: [@connorhu](https://github.com/connorhu)
- **Komplex miserend felviteléhez új és egyszerű beviteli forma a frontenden. Lásd: https://github.com/borazslo/miserend.hu/issues/144**

## OSM: Katolikus Templomok

Az Open Street Map nyílt térképadatbázisba folyamatosan visszük fel és frissítjük a katolikus templomok és egyházigazgatási határok adatait. A miserend.hu nagyon erősen építkezik erre.
- Kulszavak: *OSM, térkép*
- Projekt oldala: https://wiki.openstreetmap.org/wiki/Hungary/Katolikus_Templomok

### Lehetséges fejleszések:
- **Városi miserendek térképes előkészítése nyomtatása (OSM + miserend.hu)**
- **(Szeged) városi puzzle katolikus helyekkel kiemelve**
- A [maradék 53](https://miserend.hu/josm) (főként) erdélyi templom megtalálása a térképen.
- Budapesti plébániák már [megrajzolt határainak](https://www.google.com/maps/d/u/0/viewer?ll=47.48244397989413%2C19.081137596252695&z=14&mid=170dTG1OAQBJjuEN_3fFPXtFrrQwY93D4) felvitele az OSM-be.
- Szlováikai és romániai katolikus egyházmegyék határainak felrajzolása
- A miserend.hu adatainak áttöltéséhez katolikus key:value párok meghatározása.

## MisEnapló
![last commit](https://img.shields.io/github/last-commit/misenaplo/misenaplo?style=for-the-badge)
![commit activity](https://img.shields.io/github/commit-activity/y/misenaplo/misenaplo?style=for-the-badge) 
![issues](https://img.shields.io/github/issues/misenaplo/misenaplo?style=for-the-badge)
![pull requests](https://img.shields.io/github/issues-pr/misenaplo/misenaplo?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-vlacko0930-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2Fvlacko0930)

A nyílt forráskódú pont és pecsétgyűjtő misenapló digitális változata sok lehetséges fejlesztéssel. Tavaly is tettünk hozzá, hátha most is.
- Kulcsszavak: *Vuejs, NodeJS-ExpressJS, Sequelize ORM*
- Forráskód: [github.com/misenaplo/misenaplo](https://github.com/misenaplo/misenaplo)
- Honlap: [misenaplo.hu](https://misenaplo.hu)

**A fejlesztő Vörös László is itt lesz a II. Szent József Hackathonon**

## Zsolozsma
![last commit](https://img.shields.io/github/last-commit/breviar-sk/Liturgia-hodin-online?style=for-the-badge)
![commit activity](https://img.shields.io/github/commit-activity/y/breviar-sk/Liturgia-hodin-online?style=for-the-badge) 
![issues](https://img.shields.io/github/issues/breviar-sk/Liturgia-hodin-online?style=for-the-badge)
![pull requests](https://img.shields.io/github/issues-pr/breviar-sk/Liturgia-hodin-online?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-JurayVidéky-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2Fbreviar-sk)

A digitális zsolozsma szinte minden platformon elérhető már. 
- Kulcsszavak: *c++, osx, android, cgi, stb.*
- Platformok: *web, windows, iOS, android, kindle*
- Forráskód: https://github.com/breviar-sk/Liturgia-hodin-online , de a konkrét szövegek külön git repoban.
- Honlap: [breviar.sk](https://breviar.sk/hu/)

### Feladatok és fejlesztések:
- A felületen főként a beállítások környékén nagyon sok minden elég magyartalan. Ezeket lehetne javítani.
- [@vlacko0930](https://github.com/vlacko0930) vezetésével a HTML fájlokban lehet rabszolgamunkában átalakításokat végezni pl. a nyomtathatóság érdekében. Lásd: https://github.com/breviar-sk/Liturgia-hodin-online/issues/11
- Egyszer majd: a projekt alkalmassá tétetel hanganyagok fogadására és összeállítására #hangoszsolozsma jeligére.

## AndroKat
![last commit](https://img.shields.io/github/last-commit/agu5a/androkat?style=for-the-badge)
![commit activity](https://img.shields.io/github/commit-activity/y/agu5a/androkat?style=for-the-badge) 
![issues](https://img.shields.io/github/issues/agu5a/androkat?style=for-the-badge)
![pull requests](https://img.shields.io/github/issues-pr/agu5a/androkat?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-agu5a-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2Fagu5a)

Android és katolikus. Összefogja a legtöbb elérhető magyar katolikus anyagot az interneten egy alkalmazásba és honlapba.

- Kulcsszavak: *NET 7 MAUI*
- Platformok: *android, web*
- Forráskód: https://github.com/agu5a/androkat és hozzá Wiki: https://github.com/agu5a/androkat/wiki
- Honlap: https://androkat.hu/

**A fejlesztő Gulyás Arnold is itt lesz a II. Szent József Hackathonon**

  
# Ami még érdekes lehet

## LiturgicalCalendarAPI
![last commit](https://img.shields.io/github/last-commit/Liturgical-Calendar/LiturgicalCalendarAPI?style=for-the-badge)
![commit activity](https://img.shields.io/github/commit-activity/y/Liturgical-Calendar/LiturgicalCalendarAPI?style=for-the-badge) 
![issues](https://img.shields.io/github/issues/Liturgical-Calendar/LiturgicalCalendarAPI?style=for-the-badge)
![pull requests](https://img.shields.io/github/issues-pr/Liturgical-Calendar/LiturgicalCalendarAPI?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-JohnRDOrazio-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2FJohnRDOrazio)

Nyílt liturgikus naptár. Bár a zsolozsma naptárja mindent visz jelenleg, de érdemes lehet erre figyelni és a fordításba akár besegíteni: https://translate.johnromanodorazio.com/engage/liturgical-calendar/
- Forráskód: https://github.com/Liturgical-Calendar/LiturgicalCalendarAPI
- Honlap: https://litcal.johnromanodorazio.com/
