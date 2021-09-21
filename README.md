### @explicitHints false

## Introduksjon @unplugged
Her vil du lære å kode kule toner. 

Målet er å spille STAR WARS - a long time ago in a galaxy far far away !


## Steg 1: Lage en løkke som gjentas 4 ganger
Trykk på ``||Loops: Løkker ||`` fra blokkmenyen. klikk og dra deretter inn ``||Loops: gjenta (4) ganger ||`` og sett denne inni ``|| basic: ved start ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
    }
```
## Steg 2: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        }
```
## Steg 3: Sette inn en hviletakt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: pause (ms) (1 taktslag) ||`` og sett denne inn under forrige blokk.
Sett hviletakt til  ``|| Music: pause (ms) ( 1/8 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        }
```
## Steg 4: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        }
```
## Steg 5: Sette inn en hviletakt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: pause (ms) (1 taktslag) ||`` og sett denne inn under forrige blokk.
Sett hviletakt til  ``|| Music: pause (ms) ( 1/8 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        }
```
## Steg 6: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        }
```
## Steg 7: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre C ) i ( 1 taktslag ) ||``. Gjenta dette en gang til.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        }
```
## Steg 8: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1 taktslag ) ||``. Gjenta dette en gang til.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        }
```
## Steg 9: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre F ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        }
```
## Steg 10: Sett inn en hviletakt.
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: pause (ms) (1 taktslag) ||`` og sett denne inn under forrige blokk.
Sett hviletakt til  ``|| Music: pause (ms) ( 1/8 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        }
```
## Steg 11: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre E ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        }
```
## Steg 12: Sett inn en hviletakt.
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: pause (ms) (1 taktslag) ||`` og sett denne inn under forrige blokk.
Sett hviletakt til  ``|| Music: pause (ms) ( 1/8 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        }
```
## Steg 13: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre D ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        }
```
## Steg 14: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( High C ) i ( 1 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        }
```
## Steg 15: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( High C ) i ( 1 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        }
```
## Steg 16: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Middle G ) i ( 1 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        }
```
## Steg 17: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Middle F ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        }
```
## Steg 18: Sett inn en hviletakt.
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: pause (ms) (1 taktslag) ||`` og sett denne inn under forrige blokk.
Sett hviletakt til  ``|| Music: pause (ms) ( 1/8 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        }
```
## Steg 17: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Middle E ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        }
```
## Steg 18: Sett inn en hviletakt.
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: pause (ms) (1 taktslag) ||`` og sett denne inn under forrige blokk.
Sett hviletakt til  ``|| Music: pause (ms) ( 1/8 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        }
```
## Steg 19: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Middle F ) i ( 1/4 taktslag ) ||``.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        }
```
## Steg 20: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Loops: Løkker (4) ganger ||``.
Sett tone og takt til ``|| Music: spill tone ( Middle D ) i ( 1 taktslag ) ||``. Gjenta dette en gang til.

 ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.playTone(294, music.beat(BeatFraction.Whole))
        music.playTone(294, music.beat(BeatFraction.Whole))
        }
```
## Steg 21: Leste ned på microbiten

hvis du har en @boardname@ tilkoblet, trykk ``|last ned|``!
Prøv nå også endre farge og hvilken LED som skal lyse for så å trykke ``|last ned|`` igjen.
For hver endring vi gjør i koden må det lastes ned på nytt til @boardname@.
  ```blocks  
    for (let index = 0; index < 4; index++) {
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(392, music.beat(BeatFraction.Quarter))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(262, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(294, music.beat(BeatFraction.Quarter))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(523, music.beat(BeatFraction.Whole))
        music.playTone(392, music.beat(BeatFraction.Whole))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(330, music.beat(BeatFraction.Quarter))
        music.rest(music.beat(BeatFraction.Eighth))
        music.playTone(349, music.beat(BeatFraction.Quarter))
        music.playTone(294, music.beat(BeatFraction.Whole))
        music.playTone(294, music.beat(BeatFraction.Whole))
    }
```
