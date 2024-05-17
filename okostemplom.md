# OkosTemplom projekt elemei
A szegedi Szent József jezsuita templomban sokféle automatika működik. A Szent József Hackathon résztvevői ezekbe is besegíthetnek. Itt van néhány példa.

## OkosTemplomProjekt
Automatizált fűtés és fények és egyebek. 

Kulcsszavak: *OpenHab, mqtt, gCalendar, ESPHome, stb.*

- Például OpenHab finomhangolása, hogy naptár bejegyzés előtt fél órával fűtést kapcsoljon.
- Továbbá OpenHab dashboard szépítés.
- Templomi klíma megvarázslása Modbus over IP eszközökön keresztül
- A kamerakép alapján működő fűtés program finomhangolása
- Kamerakép alapján gázóra leolvasás, számmá alakítás, fénykép csatolás.

## OH MideaAC binding	

Kulcsszavak: *Java*

Az [OpenHab egy moduljának](https://community.openhab.org/t/new-oh3-binding-midea-air-conditioning-lan/116613) javítgatása, hogy tudjon kapcsolódni jól a templomi MideaAC klímákhoz. Az AC hexa üzenetek binárissá alakítása után az üzenetek tartalmának kitalálása. Hardware van. A build process kipróbálva. [github](https://github.com/borazslo/openhab-mideaac-addon/releases/)

## Könyvolvasó mint hirdető felület
Akár programozói tudás nélküli alkalmazás összeollózás és beállítás

- Könyvolvasó féle e-Ink kijelző használata templomi hirdetőtáblának (pl. heti miserendhez) dinamikusan frissülve.
- [Kindle mókolása](https://mpetroff.net/2012/09/kindle-weather-display/), hogy a netről bárhonnan lehúzzon egy képet / pdf-t / adatot. (Hardware van.) Vagy
- Androidos e-ink tablet (Onyx Boox) mókolása, hogy például dinamikus képernyővédővel hozza be a netről a képet / pdf-t / bármit. (Hardware van.)

## E-ink price tags hírek	

Kulcsszavak: *C, hardware*

- Olcsó kisebb-nagyobb e-ink alapú bolti árcédulák arduino alapú meghekkelése, hogy saját információkat lehessen megjeleníteni [például így](https://www.youtube.com/watch?v=BvOkOANCmMk). (Hardware nincs.)
- [Lilygo](https://www.lilygo.cc/products/t5-4-7-inch-e-paper-v2-3) mini e-ink kijelzőre google naptár alapján misézők megjelenítése. (Hardware is van.)

