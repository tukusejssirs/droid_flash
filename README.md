#Flashovanie ’Droidu


ZALOHUJ SI VSETKY UDAJE Z MOBILU (INTERNA AJ EXTERNA KARTA),
BO PO FLASHOVANI TAM NIC PO NICH NEZOSTANE!!!!

priprav sa na to, ze aplikacie si budes musiet znova nainstalovat,
no v google ucte mas zapisane, ktore si mal nainstalovane

samozrejme, musis mat zapnute tzv ladenie (debugging)
(chod do nastaveni > (informacie) o telefone a 7 alebo
10-krat klikaj na `Build Number` (zobrazi sa informacia,
ze si vyvojar/developer) … potom chod spat do nastaveni
a naspodku by si mal mat `nastavenia vyvojara` /
`developer options` a vyhladaj a povol moznost
`ladenie` / `debugging` …

a este jedna vec: CyanogenMod 12.1 je v podstate
Android 5.1, no je lepsi xD

subory na stiahnutie
--------------------

- [odin](http://is.gd/odin_310)
- [ovladace](http://www.mediafire.com/?uucafcnk4nxmvcc)
- [cwm](http://d-h.st/II4) (toto Ti nebude treba stiahnut,
  je to len pozn. pre mna, keby Ti daco neslo)
- [twrp](https://dl.twrp.me/s2vep/twrp-2.8.7.0-s2vep.img.tar)
- [cm12.1](http://is.gd/cm121_samsung)
- [gapps](http://is.gd/gapps_nano)
- [supersu](http://is.gd/supersu_beta)


samotny postup
--------------

1. spusti aplikaciu odin*.exe s administratorskymi pravami
(klikni pravym na odin*.exe a zvol moznost
`run as administrator` / `spustit ako administrator/spravca`)

2. spusti svoj mobil v `download mode` (vypni mobil a naraz
stlac 3 tlacidla zapnut+domov+zvuk_dole; ang.: power+home+vol_down)
… ak Ti to nepojde, stlac len power+vol_down (zapnut+zvuk_dole)
a ked Ti vyjde upozornenie (warning), stlac len vol_up (zvuk_hore)

3. pripoj telofon k pocitacu cez usb kabel (v odine by sa mal
zafabit stvorcek id-com na modro a v nom by malo byt napisane
cosi ako 0:[COM1] … cisla sa mozu lisit) … ak odin nerozpozna
mobil, mozno si budes musiet nainstalovat ovladace (drivers)
pre Tvoj mobil [treba ich nainstalovat, odpojit telefon,
zatvorit odin, (mozno i pocitac restartovat) a znova ist od
bodu 1.] … alternativa k driverom: nainstaluj si samsung kies
a spoj si usb kablom plne zapnuty mobil s pc a s kies …

4. odskrtni auto reboot (v podstate ziadne zo zaskrtavacich
policok nema byt zaskrtnute)

5. klikni na tlacidlo `PDA` (prip. `AP`) a vyhladaj si twrp

6. klikni na tlacidlo `start` (operacia bude trvat cca 20 sekund)

7. ked odin vypise/zobrazi `RES OK` (alebo `PASS!`), skopiruj
si na micro sd kartu cm12.1, supersu a gapps … vloz ju to
mobilu a restartuj ho (kedze v nom teraz nemas ziaden os, nacita
sa cwm – ak nie, vypni ho a stlac naraz power+home+vol_up /
zapnut+domov+zvuk_hore)

8. klikni na `wipe`, `advanced wipe` a nasledne zasrtni len
tieto moznosti: system, cache, dalvik cache … potiahni modru sipku,
akoby si odblokovaval iPhone xD

9. chod spat do hlavneho menu, klikni na `install`, nasledne na
`add zip file` a vyhladaj si cm12.1 na sd karte; potom znova klikni
na `add zip file` a vyhladaj gapps; a do tretice `add zip file`
a vyhladaj supersu

10. spust flashovanie pomocou potiahnutia tej casti na spodku
(ako ked otvaras iPhone napriklad xD) …

11. ak to dorobi bez chyb (teda nevypise `failed`, a vypise
`success(ful)`, chod spat do hlavneho menu a klikni na `wipe`,
`advanced wipe` a nasledne zaskrtni iba tieto moznosti:
dalvik cache, cache

12. restartuj mobil a mal operacny system by byt plne funkcny

zaloha
------

ak Ti vsetko funguje, odporucam Ti spravit si zalohu mobilu
(po obnove budes mat vsetko tak, ako bolo v case zalohy,
nastavenia, programy atd)

a. chod do twrp (z cm12.1 sa da do twrp ist pomerne jednoducho,
no musis byt najskor `vyvojar`, teda 7-krat kliknut na build number
v about phone (informacie o telefone), ist spat do hlavneho menu
nastaveni, a vyhladat `advanced reboot` a povolit to … potom uz
len dlhsie podrzat power/tlacidlo zapnutia, kliknut na reboot
a nasledne na reboot recovery a ok … btw, [hard(ware)] reboot je
uplne vypnutie a nasledne zapnutie mobilu a soft(ware) reboot je
iba restartovanie operacneho systemu)

b. klikni na backup a rob, co Ti vypise … priprav sa vsak, ze
zaloha moze mat aj vyse 3 GB, takze musis mat dostatok miesta
na externej sd karte (len na externu ju ukladaj xD) … a zaskrtni
aj `nandroid`, bo je to dolezite, keby sa cosi stalo :) … alebo
rovno zaskrtni vsetko (okrem externej karty) a mas pokoj (tak to robim ja) XD
