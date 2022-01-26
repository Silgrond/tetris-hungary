---
title: "Tippek"
description: ""
date: 2022-01-06T13:05:26+01:00
lastmod: 2022-01-06T13:05:26+01:00
draft: false
menu:
  docs:
    parent: "01 Kezdőknek"
    weight: 012
images: []
---

## Általános tippek

### Tetris építéséhez:

- A játéktér (mátrix) 10x22-es négyzetrács. Játékváltozattól függ, de a legalapvetőbb, legtöbb pontot hozó elemlehelyezés az <span style="color: #0F9BD7;">I-elemmel (I tetrimino)</span> történő ún. tetris, amely négy vízszintes sor törlését, eltüntetését jelenti.
- Mivel az elemek megjelenése, azok tengelye és a forgatásuk iránya balra húz (bővebben: SRS-forgatás leírás), célszerű bal oldalról az első 9 oszlopba építeni, üresen hagyva az utolsó, 10. oszlopot, ahová az <span style="color: #0F9BD7;">I-elem</span> kerül. Helyes lépésekkel az elemek lehelyezése (lásd: Finesse) kevesebb mozgatást és gombnyomást igényel.

  - A legtöbb modern variánsban a játék többletpontokkal jutalmazza az egymást követő tetriszeket (Back-to-Back, B2B), így ha ügyesen építünk, a sok extra pontot össze tudunk gyűjteni!<p>

- Próbáljuk meg az elemeket úgy elhelyezni, hogy azok nagyjából egy egybefüggő, vízszintes részt képezzenek (ún. flat stacking), ám a cél mégis az, hogy legyenek kisebb, 1-1 blokkból álló egyenetlenségek (kitüremkedések, mélyedések), hogy az <span style="color: #59B101;">S</span> és a <span style="color: #D70F37;">Z-elemeket</span> is megfelelően le tudjuk helyezni. Ez a típusú építési mód optimálisabb elemlehelyezési lehetőségeket eredményez: kevesebbet kell forgatni az elemeket és kevesebbet kell gondolkodni (szinte a helyükre csusszannak az elemek), nagymértékben felgyorsítva a stackelést.
- Ne legyél elemfüggő! Azaz építsünk úgy, hogy ne legyünk rászorulva egy adott elem következő előfordulására. Példaképp: ha az előző pontban leírtakat figyelembe vesszük, elkerüljük a 2 cellánál/blokknál nagyobb lyukakat, magasságbeli különbségeket. Ez azért fontos, mert ezeket csak egy <span style="color: #0F9BD7;">I-elem</span> lehelyezésével tudjuk betömni, eltüntetni. Ha semmiképp nem tudjuk megoldani az adott szituációt, inkább helyezzük a kérdéses elemet a játéktér közepére, maximalizálva a balra és a jobbra letehető elemek számát, amellyel ki lehet egyenlíteni a stackelést.
  -  Azt is érdemes lehet észben tartani a sztenderd 7-zsákos randomizálót (7 bag randomizer) használó játékvariáns esetében, hogy mivel egy tetrishez körülbelül 10 elem lehelyezésére van szükség, minden második tetris után marad egy szabadon felhasználható <span style="color: #0F9BD7;">I-elem</span>.<p>
- Modern változatokban próbáljuk ne nagyon cserélgetni a elrakott, tartogatott *Hold*-elemet, az ugyanis lelassít.
- Próbáljunk úgy építeni, hogy elkerüljük az olyan szituációt, amikor soft-dropot, azaz lassú lehelyezést kell használnod! A csúsztatás hibára ad lehetőséget, le is lassít. Bizonyos esetekben ez elkerülhetetlen (pl ha egy modern változatban az első két elem <span style="color: #59B101;">S</span> és <span style="color: #D70F37;">Z</span>), a soft-drop kivitelezésekor legyünk körültekintőek!

A sok gyakorlás meghozza az eredményét: egy idő után rááll az ember szeme az optimális lehelyezésre. Ha egy bonyolultabb szituáció elé kerülünk, nyugodtan álljunk meg, figyeljük meg a következő elemeket, és aszerint cselekedjünk! Érdemes más játékosokat is megfigyelni, sok mindent el lehet tőlük lesni.
