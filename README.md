# Adatbázis-kezelés I. – Northwind-adatbázis segédlet

Ez a segédlet bemutatja, hogyan telepítheted a Northwind-adatbázist, amelyen a későbbiekben SQL-lekérdezéseket gyakorolhatsz. Ha a phpMyAdmin felületén még nem található `northwind` nevű adatbázis, kövesd az alábbi lépéseket!

## 1. A Northwind-adatbázis letöltése

Nyiss meg egy keresőt, és írd be a következőt:

```text
northwind database for mysql github
```

A találatok közül nyisd meg az első GitHub-hivatkozást!
https://github.com/busynovadad/northwind-MySQL

## 2. A repository letöltése

A GitHub-oldalon kattints a zöld **Code** gombra, majd válaszd a ZIP-formátumú letöltést (**Download ZIP**).

## 3. A ZIP-fájl kicsomagolása

Csomagold ki a letöltött ZIP-fájlt egy tetszőleges mappába! Jegyezd meg a mappa helyét, mert a következő lépésekben szükséged lesz a benne található SQL-fájlok elérési útjára.

## 4. A phpMyAdmin megnyitása

Nyisd meg a phpMyAdmin felületét!

## 5. Az első SQL-fájl importálása

Kattints a phpMyAdmin bal felső részén található **phpMyAdmin logóra**, majd a felső menüsorban válaszd az **Importálás** lehetőséget.

A fájlkiválasztó gomb segítségével keresd meg a kicsomagolt mappában a `northwind.sql` nevű fájlt, és jelöld ki!

Görgess az oldal aljára, majd kattints az **Indítás** gombra az importálás elvégzéséhez.

## 6. A második SQL-fájl importálása

Az első fájl importálása után ismét kattints az **Importálás** menüpontra!

Válaszd ki a kicsomagolt mappából a `northwind-data.sql` nevű fájlt.

Görgess az oldal aljára, majd kattints az **Indítás** gombra!

## 7. Az adatbázis ellenőrzése

Az importálás befejezése után ellenőrizd, hogy a `northwind` adatbázis megjelent-e a phpMyAdmin bal oldali adatbázislistájában, és hogy a táblák is elérhetők-e.

Ha minden sikeresen lefutott, a Northwind-adatbázis készen áll az SQL-lekérdezések gyakorlására!

---

**Megjegyzés:** A második fájl neve a leírás alapján `northwind-data.sql` lehet. Ellenőrizd a kicsomagolt mappában, hogy pontosan hogyan szerepel a fájlnév.
