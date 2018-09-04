---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
list_title: Materiaali
---

<h3>A link to the English page is in the upper right corner</h3>

<h1 id="main-title">Tervetuloa Tietokone Työvälineenä -kurssin kotisivulle. </h1>

Tämä kurssi on tarkoitettu Helsingin yliopiston tietojenkäsittelytieteen ensimmäisen vuoden opiskelijoille. Kurssilla tutustutaan komentoriviin Unix-tyyppisissä järjestelmissä, opetellaan Git-versionhallintatyökalun käyttöä sekä hieman HTML ja CSS-kieliä. Tarkoituksena on oppia tietojenkäsittelytietelijän käytännön taitoja, ja käyttämään opinnoissa hyödyllisiä työvälineitä.

<h2>Kurssin suorittaminen</h2>
Kurssi suoritetaan verkkotentillä, joka tehdään [Moodle-oppimisympäristössä](https://moodle.helsinki.fi/). Moodle on yliopistolla lajaasti käytössä oleva sivusto, joka mahdollistaa sähköisen etäopetuksen järjestämisen. Kurssille on olemassa [oma kurssialue](https://moodle.helsinki.fi/course/view.php?id=22186). Moodle-alueelle pääsy vaatii kurssiavaimen, joka on <strong>lapio-on-tyovaline</strong>. Tentti perustuu pääosin tältä sivustolta löytyvään materiaaliin, joka on jaettu kolmeen osaan: Komentorivin perusteet, Git ja versionhallinta, sekä HTML ja CSS.

Jos aiheista on kokemusta aikaisemmin, materiaalin lukeminen tai tehtävien tekeminen ei ole välttämätöntä tentin läpipääsemiseksi, vaan tenttiin voi osallistua suoraan. Jos kuitenkin käsiteltävät asiat ovat vieraita, kannattaa materiaali käydä läpi huolellisesti, sillä kurssilla opeteltavia taitoja tulet varmasti tarvitsemaan tulevissa opinnoissa. Vaikka et muuten lukisi materiaalia, lue silti tältä sivulta löytyvät [ohjeet osaston IT-järjestelmiin](/osaston-jarjestelmat).

Jokaisen osan alussa on määritelty oppimistavoitteet, joiden perusteella voit määritellä itse, oletko valmis osallistumaan tenttiin.

Tehtäviä tekemällä ansaitsee laskaripisteitä, jotka lasketaan mukaan kurssipisteisiin. Laskaripisteet merkitään Moodle-alueella. Voit lukea kurssipisteistä lisää [arvostelu-sivulta](/tentti).

## Tukikanavat

Kurssilla on kaksi tukikanavaa: Syksyn 2018 ensimmäisen periodin ajan järjestetään pajaohjausta, jolloin opiskelijoiden on mahdollista tulla tekemään tehtäviä osaston tiloihin, ja saada halutessaan apua kurssin assistenteilta. Lue lisää pajasta, ja sen aikatauluista [täältä](/paja).

Kurssilla on myös sähköinen tukikanava, joka on sillattu IRCistä telegrammiin.

- #lapio2017 @IRCnet
- <a href="https://t.me/tktlapio">Liittymislinkki Telegram-ryhmään</a>
- <a href="https://riot.im/app/#/room/#_ircnet_#lapio2017:irc.snt.utwente.nl">Riot-linkki Matrixin kautta IRC-kanavalle (ei vaadi ohjelman asentamista tai kirjautumista)</a>

Tukikanavalla saa esittää mitä tahansa kurssiin liittyviä kysymksiä. Kurssikavereiden auttaminen on suotavaa.

Syrjiviä tai asiattomia kommentteja ei sallita, ja niiden esittäjä poistetaan kanavalta.

## Välineet

Tehtävät on mahdollista tehdä millä tahansa Unix-pohjaisella tietokoneella. Käytännössä tämä tarkoittaa useimmiten Linux- tai macOS-tietokoneita. Mikäli mahdollista, suosittelemme (paria tehtävää lukuunottamatta) tehtävien tekemistä osaston koneilla, joissa on yliopiston oma Linuxin jakeluversio [Cubbli](https://helpdesk.it.helsinki.fi/ohjeet/tietokone-ja-tulostaminen/tyoasemapalvelu/yleista-cubblista).

[Windows ei kuulu Unix-tyyppisten käyttöjärjestelmien perheeseen](https://en.wikipedia.org/wiki/Unix-like). Kurssin suorittamiseksi Windows-koneella on kuitenkin useita vaihtoehtoja:

### VirtualBox

Kurssin suorittaminen Windows-koneella onnistuu todennäköisesti helpoiten ajamalla Linuxia virtuaalikoneen sisällä. Tällöin Linux-kone pyörii omassa ikkunassaan.

Varmista ennen asentamista, että sinulla on vähintään 512M, mutta mieluiten 1G [RAM-muistia](https://www.computerhope.com/issues/ch000149.htm) koneellasi.

  VirtualBoxin asennus:

  1. Lataa ja asenna VirtualBox [täältä](https://www.virtualbox.org/wiki/Downloads).
  2. Lataa Ubuntu 16.04:n levykuva (.iso) [täältä](http://releases.ubuntu.com/16.04/). Jos olet koskaan asentanut käyttöjärjestelmää CD:ltä, tämä .iso-tiedosto on tavallaan sen sisältö.
  3. Seuraa [näitä ohjeita](http://www.psychocats.net/ubuntu/virtualbox) luodaksesi virtuaalikoneen
  4. Käynnistä virtuaalikone VirtualBoxista.

### Bash shell

Windows 10 -käyttöjärjestelmässä on mahdollista käyttää bash shelliä. [Täältä](https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10) löytyy ohjeet bash shellin asentamiseksi ja ajamiseksi. Tällöin pystyt ajamaan komentorivillä komentoja kuten Linux-koneella. Materiaali on tehty ajatellen Unix-järjestelmää, joten Windowsilla suorittaminen voi myös bash-shellin kanssa vaatia hieman kikkailua. Kysy rohkeasti apua, mikäli kohtaat ongelmia, ja ilmoita, mikäli voimme parantaa materiaali Windows-käyttäjiä ajatellen!


### Ubuntu-applikaatio

Windows 10 -käyttöjärjestelmässä on myös mahdollista ladata erillinen [Ubuntu-applikaatio](https://tutorials.ubuntu.com/tutorial/tutorial-ubuntu-on-windows#0), jonka avulla voit käyttää Ubuntu-terminaalia. Ubuntu tarkoittaa erästä Linux-jakeluversiota (tuttavallisemmin distro), josta eräs versio pyörii myös osaston koneilla.

Muuten Windowsilla kurssin suorittaminen on vaikeaa, eikä järin tavoitteellista, sillä tarkoitus on nimenomaan tutustua Unix-komentoriviin. Jos olet tietojenkäsittelytieteen pääaineopiskelija, kannattaa tässä tapauksessa ensimmäisen osan tehtävät tehdä osaston paja-luokkien koneilla. Mikäli sinulla ei ole käytössä muuta, kuin vanha Windows, ota yhteys kurssin järjestäjiin.

## Ennen materiaalin aloittamista

Kurssin suorittaminen vaatii muutaman ohjelman asentamista koneelle. Mikäli et suorita kurssia osaston koneilla, varmista, että sinulla on käyttämääsi järjestelmään asennusoikeus.

Jos teet tehtäviä kotikoneella, ja olet läsnäoleva yliopisto-opiskelija, asenna ensin [Eduroam](https://www.eduroam.org/what-is-eduroam/), jolla pääset internetiin Helsingin yliopiston kampusalueilla. Helpdeskillä on sille [ohjeet](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/eduroam-verkon-asennus-asetustiedoston-avulla). Suosi aina Eduroamia yliopiston toisen verkon, HUPnetin yli. Internetin käyttö Eduroamin yli on turvallisempaa, ja se on saatavilla kampusalueilla myös ulkomailla.

**Mikäli olet tietojenkäsittelytieteen pää- tai sivuaineopiskelija, aktivoi yliopiston tunnuksesi [täällä](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/kayttajatunnus/uuden-kayttajatunnuksen-aktivointi) ja CS-tunnuksesi seuraavan sivun [ohjeiden](https://www.cs.helsinki.fi/tietotekniikka/k-ytt-luvat) mukaan ennen materiaalin lukemista.**

<h2>Ohjeita materiaalin lukemiseen</h2>

Prosenttiluku tehtävän nimen jälkeen kertoo, kuinka monta prosenttia se vastaa kyseisen osan laskaripisteistä.

Materiaali on rakennettu niin, että sitä voi seurata tehden esimerkit samalla. Suosittelemme tätä vahvasti.

Mikäli löydät virheen tai typon materiaalista, forkkaa [tämä](https://github.com/tkt-lapio/tkt-lapio.github.io) projekti, korjaa virhe omaan versioosi, ja tee pull request.
