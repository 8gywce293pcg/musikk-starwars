### @explicitHints false

## Introduksjon @unplugged
Her vil du lære å kode kule toner. 

Målet er å spille temaet fra STAR WARS - så la oss reise i tid og rom til a long time ago in a galaxy far far away!


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
For hver endring vi gjør i koden må det lastes ned på nytt til @boardname@. Dersom du ikke har en @boardname@ tilkoblet, må du gjøre de neste stegene også.
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

## Steg 22: Koble til micro:biten
For å kunne laste ned koden din til micro:biten med et klikk må du først få MakeCode til å skjønne at alle filer skal lastes ned direkte til den.
Det krever bare noen få, enkle steg.

## Steg 23: Prikkene ved siden av Last Ned-knappen

Start med å sjekke at micro:biten du skal bruke er koblet til PCen. Når den er koblet til, klikker du på de tre prikkene ved siden av ``|last ned|``-knappen

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect1.jpg)

## Steg 24: Connect-menyen @unplugged
Når du klikker på de tre prikkene dukker det oppe en liten meny. Dersom det står "Koble Fra" eller "Disconnect" på den øverste linjen, trenger du ikke å gjøre mer.
Da kjenner PCen og MakeCode igjen micro:biten fra tidligere, og du kan klikke ved siden av menyen og laste ned koden din ved å klikke på den store ``|last ned|``-knappen.

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect2b.jpg)


## Steg 25: Dersom MakeCode ikke kjenner micro:biten fra før
Dersom MakeCode ikke kjenner micro:biten fra før vil det stå "Connect device" eller "Koble til" på den øverste linjen.
Klikk i så fall på den øverste linjen i menyen.

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect2.jpg)


## Steg 26: Veiledningsvindu

Når du klikker på den øverste linjen dukker det opp et par veiledningsvinduer som tar deg gjennom tilkoblingsprosessen. De to første kan du bare trykke "Next" eller "Fortsett" på:

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect3.jpg)

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect4.jpg)


## Steg 27: Velg micro:biten

Etter at du har klikket "Next" to ganger dukker det opp en liste over tilgjengelige micro:biter. Det skal bare være én micro:bit på lista.
Klikk først på navnet til micro:biten så det blir merket med blått, og så på "Koble til".

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect5.jpg)

## Steg 28: Ferdig!

I det siste veiledningsvinduet klikker du på "Done" eller "Ferdig" om det står på norsk.
Etter det kan du laste ned kode direkte til micro:biten ved å klikke på den store, lilla ``|last ned|``-knappen nederst til venstre på skjermen i MakeCode:

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect6.jpg)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
