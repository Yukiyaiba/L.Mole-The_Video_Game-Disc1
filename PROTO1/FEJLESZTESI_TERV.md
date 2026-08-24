# Prototype 1 – Fejlesztési terv

A Prototype 1 célja a végleges játék alapvető rendszereinek működő demonstrációja a lehető legkisebb fejlesztési igénnyel.

Nem célja, hogy szép legyen.
Nem célja, hogy változatos legyen.
Nem célja, hogy hosszú legyen.

**A célja, hogy elkészüljön.**

---

## Technikai alapok

- [ ] Godot projekt létrehozása az `src/` könyvtárban
- [ ] Belső felbontás: **320×180**
- [ ] Full HD megjelenítés: **6× integer scaling**
- [ ] Pixelgrafikus megjelenítés
- [ ] Maximum **16 színes paletta**
- [ ] Egységes globális színpaletta
- [ ] Placeholder grafika használható
- [ ] Billentyűzetes irányítás
- [ ] Alap hangerőkezelés
- [ ] `.gitignore` beállítása
- [ ] Projekt exportálható állapotba hozása

### Grafikai korlátok

- [ ] Maximum 320×180 belső renderfelbontás
- [ ] Maximum 16 szín a játék grafikájában
- [ ] Nincs truecolor grafikai tervezés
- [ ] Nincs szükségtelenül nagy felbontású asset
- [ ] Nincs shaderes grafikai csicsa
- [ ] Nincs blur
- [ ] Nincs gradient
- [ ] Nincs komplex fényrendszer
- [ ] Nincs részecskerendszer, hacsak nem szükséges egy alapvető effekt demonstrálásához

> **Jutas:** Láttam a felbontástesztjeidet.
>
> Ne erőltesd túl magad.
>
> Jó lesz ez 1/6 HD-ban is.
>
> Úgy talán sikerül prezentálnod valamit még időben.

---

## Menü

- [ ] Főmenü
- [ ] Játék indítása
- [ ] Kilépés
- [ ] Játék címe
- [ ] Prototype/verzió megjelenítése
- [ ] `THE END` után visszatérés a főmenübe

---

## Játékos

- [ ] Játékos karakter
- [ ] Alap idle állapot
- [ ] Minimális mozgásanimáció
- [ ] Mozgás balra
- [ ] Mozgás jobbra
- [ ] Karakter megfelelő irányba fordul
- [ ] Ütés
- [ ] Egyetlen támadástípus
- [ ] Támadás hitbox
- [ ] Sebzés okozása
- [ ] Sebződés
- [ ] Életerő
- [ ] Halál
- [ ] Halál utáni újrakezdés

### Nem készül

- [ ] ~~Ugrás~~
- [ ] ~~Guggolás~~
- [ ] ~~Futás~~
- [ ] ~~Combo~~
- [ ] ~~Fegyverek~~
- [ ] ~~Inventory~~
- [ ] ~~Képességek~~

---

## Ellenfél

- [ ] Egyetlen ellenféltípus
- [ ] Minimális idle/mozgás animáció
- [ ] Játékos felismerése
- [ ] Játékos megközelítése
- [ ] Egyetlen támadás
- [ ] Támadás hitbox
- [ ] Sebzés okozása
- [ ] Sebződés
- [ ] Életerő
- [ ] Halál

Az AI működési elve:

**Megtalál → odamegy → megüt.**

Ennyi.

---

## Statikus aréna

- [ ] Egyetlen képernyőből álló aréna
- [ ] Statikus kamera
- [ ] Nincs scrolling
- [ ] Talaj
- [ ] Bal oldali pályahatár
- [ ] Jobb oldali pályahatár
- [ ] Játékos kezdőpozíció
- [ ] Ellenfél spawnpont
- [ ] Egyszerű háttér
- [ ] Pálya teljesítésének érzékelése

---

## Pálya 1

- [ ] Aréna betöltése
- [ ] Játékos megjelenése
- [ ] Ellenfelek megjelenése
- [ ] Ellenfelek legyőzése
- [ ] Pálya teljesítése
- [ ] Továbbhaladás

---

## Pálya 2

- [ ] Ugyanaz az aréna
- [ ] Ugyanaz az ellenfél
- [ ] Minimálisan módosított háttér/paletta
- [ ] Eltérő ellenfélmennyiség vagy spawn
- [ ] Pálya teljesítése
- [ ] Továbbhaladás

---

## Pálya 3

- [ ] Ugyanaz az aréna megint
- [ ] Ugyanaz az ellenfél megint
- [ ] Maximum minimális vizuális eltérés
- [ ] Nincs új játékmechanika
- [ ] Pálya teljesítése
- [ ] Boss betöltése

> **Jutas:** Más háttér.
>
> Új pálya.
>
> Ne vitatkozz.

---

## Boss

- [ ] Boss megjelenése
- [ ] A normál ellenfél rendszerének újrahasznosítása
- [ ] Eltérő boss sprite
- [ ] Több életerő
- [ ] Maximum egyszerű paramétermódosítás
- [ ] Boss életerő kijelzése
- [ ] Boss sebződik
- [ ] Boss támad
- [ ] Boss meghal
- [ ] Boss halála aktiválja a játék végét

### Nem készül

- [ ] ~~Boss phase-ek~~
- [ ] ~~Egyedi bossmechanika~~
- [ ] ~~Külön boss-aréna~~
- [ ] ~~Komplex támadási pattern~~

**Onnan tudod, hogy főellenség, hogy tovább tart megölni.**

---

## Játék vége

- [ ] Boss legyőzésének érzékelése
- [ ] Játékmenet leállítása
- [ ] `THE END` megjelenítése
- [ ] Rövid várakozás
- [ ] Visszatérés a főmenübe

Nincs ending cinematic.

Nincs epilógus.

Nincs következő pálya.

**Vége.**

---

## Hang

- [ ] Alap ütés hang
- [ ] Alap sebződés hang
- [ ] Ellenfél halálhang
- [ ] Boss halálhang
- [ ] Menü visszajelző hang
- [ ] Egyszerű háttérzene vagy loop

Ha valamelyik hiánya nem akadályozza a végigjátszást, **nem release blocker**.

---

## Prototype 1 scope freeze

A Prototype 1-be nem kerül:

- [ ] ~~Ugrás~~
- [ ] ~~Platforming~~
- [ ] ~~Scrolling pálya~~
- [ ] ~~Több normál ellenféltípus~~
- [ ] ~~Több boss~~
- [ ] ~~Több támadástípus~~
- [ ] ~~Fegyverrendszer~~
- [ ] ~~Inventory~~
- [ ] ~~Fejlődési rendszer~~
- [ ] ~~Procedural generation~~
- [ ] ~~Multiplayer~~
- [ ] ~~Co-op~~
- [ ] ~~Videóeditor~~
- [ ] ~~Point & click HUB~~
- [ ] ~~Időutazás~~
- [ ] ~~24 órás időmenedzsment-rendszer~~
- [ ] ~~Animés succubus minijáték~~

> **Jutas:** Nem.

---

# Release

## Játszhatóság

- [ ] A játék főmenüből elindítható
- [ ] A játékos irányítható
- [ ] A játékos tud támadni
- [ ] Az ellenfelek működnek
- [ ] A játékos meghalhat
- [ ] A pályák sorban teljesíthetők
- [ ] A boss elérhető
- [ ] A boss legyőzhető
- [ ] A játék végigjátszható elejétől a végéig
- [ ] `THE END` után visszatér a főmenü

## Technikai

- [ ] Windows build elkészül
- [ ] Tiszta gépen elindul
- [ ] Nincs progression-blocking bug
- [ ] Nincs reprodukálható crash normál végigjátszás során
- [ ] A 320×180 → 1920×1080 skálázás megfelelő
- [ ] A pixelgrafika nem mosódik el
- [ ] A release build verziószáma megfelelő

---

# Kész definíciója

A Prototype 1 akkor kész, ha:

1. Elindítod.
2. Mozogsz.
3. Ütsz.
4. Megölsz valamit.
5. Ugyanezt megcsinálod ugyanazon a pályán még párszor.
6. Megölöd ugyanezt főellenségnek öltöztetve.
7. Kiírja, hogy `THE END`.
8. Visszakerülsz a menübe.

Ha mindez működik:

# KÉSZ.

Ne optimalizáld.

Ne tervezz hozzá új rendszert.

Ne rajzold újra harmadszor.

Ne találj ki még egy játékmódot.

**Ne írj bele videóeditort.**
