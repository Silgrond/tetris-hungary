---
title: "index.hu - Lehet-e a végtelenségig játszani a Tetrist?"
description: ""
date: 2022-01-21T15:49:13+01:00
lastmod: 2022-01-21T15:49:13+01:00
draft: false
images: []
menu:
  docs2:
    parent: "muzeum"
---

<div class="alert alert-info" role="alert">
  A cikk eredetije 2017.10.07.-én jelent meg Hegyeshalmi Richárd tollából az index.hu Ma is tanultam valamit <a href="https://index.hu/tudomany/til/2017/10/07/lehet-e_a_vegtelensegig_jatszani_a_tetrist/" class="alert-link">rovatában</a>.
</div><p>

A Tetrist még azok is ismerik és szeretik, akik egyébként idegenkednek a videojátékoktól. (https://hu.wikipedia.org/wiki/Alekszej_Leonyidovics_Pazsitnov) korszakalkotó logikai játéka a filléres kvarcjátéktól a komplex játéktermi gépekig mindenen futtatható. És futtatják is: az egyszerű, de végtelenségig variálható alapötletnek köszönhetően még ma, 33 évvel az alapjáték megjelenése után is ugyanolyan szórakoztató, mint új korában.

Az alapötlet igen egyszerű: föntről lefelé 4 egységből álló blokkok potyognak lefelé, a játékos pedig ezeket forgatva rakosgathat ki összefüggő sorokat. Ha a különböző elemekből összeáll egy teljes sor, az eltűnik, és a játéktér egy sornyival nagyobb lesz. Ha a sorokban hézagok képződnek, a játéktér egyre szűkebbé válik, és ha az utolsó beérkező elemnek nem marad szabad mozgástere, a játék véget ér.

{{< youtube id="keeSEJG4XzU">}}
<p>

Ezek után óhatatlanul felmerül a kérdés: lehet-e a végtelenségig játszani a Tetrist? Hiszen egy képzett játékos mindig kitalálhatja, hogyan tüntesse el az összes sort, és így a végtelenségig megőrizheti a játékteret – legalábbis addig, amíg nem kell kimennie pisilni.

John Brzustowski, a Waterloo-i Egyetem matematikusa [1992-ben publikált egy, a témával foglalkozó tanulmányt](https://circle.ubc.ca/bitstream/handle/2429/3263/ubc_1992_spring_brzustowski_john.pdf?sequence=1). Ebben levezette, hogy a válasz nem: a Tetris úgy van felépítve, hogy a játékos idővel mindenképpen veszítsen.

Hogy miért? Hát a Z és az S alakú elemek (tetriminók) miatt. Ha a gép egy ideig nem oszt más elemet, csak Z és S alakú tetriminókat, a játék felépítéséből fakadóan nem tudnak teljes sorokat kialakítani, mert mindegyikben lyukak lesznek, így a játéktér idővel a játszhatatlanságig leszűkül. Ha az elemek véletlenszerűen tűnnek fel, csak idő kérdése, hogy fellépjen ez a helyzet, és akkor még a legjobb játékosok is el fognak bukni.

A gyakorlatban a Tetris legtöbb variánsával ilyen nem fordulhat elő. Egyes verziókat úgy alakítottak ki, hogy kizárólag S és Z alakú tetriminók potyogjanak fentről; ezekkel egy ügyes játékos akár 150 elemet is elhelyezhet a fix méretű játéktéren, mire a játék véget ér. A hagyományos véletlen-generátorokkal, amik az elemek típusát szabályozzák, ilyen nem nagyon fordulhat elő: egész pontosan (2/7)<sup>150</sup>-en az esélye.

A Tetris modern verzióit viszont már szándékosan úgy tervezték meg, hogy a véletlen-generátor semmiképpen ne adjon be négynél több S vagy Z alakú elemet egymás után. Ez az egyik megszeghetetlen szabály, amit a hivatalos Tetris-kiadásoknak mindig követniük kell.

Zárásként nézzük meg, ahogy egy profi játékos Grand Master fokozatot szerez a [Tetris: The Grand Master](https://en.wikipedia.org/wiki/Tetris:_The_Grand_Master) játéktermi verziójával. Ez a világon csak hat embernek sikerült.

<div class="alert alert-info" role="alert">
  Sajnos az eredeti videó archiválásunk pillanátban már nem elérhető.</a>
</div><p>
