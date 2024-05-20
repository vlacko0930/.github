# Specifikáció készítés alatt álló projektek
A projektek előkészítése nagyon fontos és a specifikációk elkészítésébe is lehet csatlakozni

## Gyermekvédelmi bejelentő oldal
Tervezés alatt van egy olyan honlap ami egy oldalon koordinálja sok-sok egyházi intézmény felé való gyermekvédelmi témákban való bejelentesét. Centralizált decentralizálás!

Egy oldal elkezdése amin keresztül ilyen-olyan bejelentés tehető a regisztrált szervezetek felé, de úgy hogy a honlap nem rögzíti a bejelentés tartalmát, de bárimikor ellenőrizhető hogy adott bejelentés ezen keresztül történt-e (hash alapon). Valamint rendszeresen pingeli a célt és informálja a bejelentőt, hogy hol tart a dolog, miközben szakmai segítséget is nyújt. (Szakmai háttér megvan.)

Érdeklődlés [@borazslo](https://github.com/borazslo)-nál

## Gyóntatáskereső

Shelly kütyük beszerelésével lámpakapcsolásra jelzést küldünk a szervernek, hogy gyóntatás van nálunk. Ezekből miserend id-hoz rendelve mindig friss adatbázist gyártunk.
Öt szegedi templomban akár shelly beszerelés is része lehet a programnak.

Érdeklődlés [@borazslo](https://github.com/borazslo)-nál

## Digitális Misekönyv (hardware + software)
![last commit](https://img.shields.io/github/last-commit/szentjozsefhackathon/misekonyv-spec?style=for-the-badge)
![commit activity](https://img.shields.io/github/commit-activity/y/szentjozsefhackathon/misekonyv-spec?style=for-the-badge) 
![issues](https://img.shields.io/github/issues/szentjozsefhackathon/misekonyv-spec?style=for-the-badge)
![pull requests](https://img.shields.io/github/issues-pr/szentjozsefhackathon/misekonyv-spec?style=for-the-badge)
![owner](https://img.shields.io/badge/Owner-szentjozsefhackathon-red?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2Fszentjozsefhackathon)

Bár "nem időszerű" a hivatalos szervek szerint, mégis a jövő az, hogy - külön egyedi e-ink kijelzős hardware-en - digitálisan használjuk a misekönyvet. Ennek készülget egy részletes leírása.

- Készülő specifikáció: https://github.com/szentjozsefhackathon/misekonyv-spec
- Honlap: http://misekonyv.hu/

## Plébánia honlap egyszerűen
Van olyan plébánia, aminek nincs honlapja. Egy "kifogás", amit hallottam, hogy sok az évi 20.000 Ft honlapüzemeltetés. Amit maximum domain árból ki lehetne hozni, és az max. 3000 Ft/év. Ami kevesebb, mint 10 Ft/nap. 

- A legtöbb plébánia már legalább Wordben elkészíti a hirdetését. És esetleg Excelben a miserendet.
- A Pandoc a Wordot át tudja konvertálni Markdownra, és a különböző programnyelvek (elsősorban JS és Python) tudják kezelni az Excelt, így abból is lehet Markdownt csinálni. 
- Az MKDocs Markdownból egyszerűen készít befektetésarányosan nagyszerű weboldalakat.
- Lehetne olyan bash/python/batch scriptet írni, ami a Pandocot lefuttatja, az MKDocsnak megfelelően bemásolja, legenerálja az oldalt, és feltölti GitHub Pagesre.
- Itt már csak azt kell megtanítani a plébániáknak, hogy hova mentsék a dokumentumaikat, és egy ikonra bármelyik felhasználó rá tud nyomni.
- Alternatíva lehet még a Jekyll

Érdeklódés [Vörös Lászlónál](https://github.com/vlacko0930)
