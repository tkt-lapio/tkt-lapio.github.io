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

Kurssi suoritetaan verkkotentillä, joka tehdään Moodle-oppimisympäristössä. Tentti perustuu pääosin tältä sivustolta löytyvään materiaaliin, joka on jaettu kolmeen osaan: Komentorivin perusteet, Git ja versionhallinta, sekä HTML ja CSS.

Jos aiheista on kokemusta aikaisemmin, materiaalin lukeminen tai tehtävien tekeminen ei ole välttämätöntä tentin läpipääsemiseksi, vaan tenttiin voi osallistua suoraan. Jos kuitenkin käsiteltävät asiat ovat vieraita, kannattaa materiaali käydä läpi huolellisesti, sillä kurssilla opeteltavia taitoja tulet varmasti tarvitsemaan tulevissa opinnoissa.

Jokaisen osan alussa on määritelty oppimistavoitteet, joiden perusteella voit määritellä itse, oletko valmis osallistumaan tenttiin.

Tehtäviä tekemällä ansaitsee laskaripisteitä, jotka lasketaan mukaan kurssipisteisiin. Voit lukea kurssipisteistä lisää arvostelu-sivulta.

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

[Windows ei kuulu Unix-tyyppisten käyttöjärjestelmien perheeseen](https://en.wikipedia.org/wiki/Unix-like). Nykyään Windows 10 mahdollistaa kuitenkin Unix-tyyppisen komentorivin käytön melko vähällä vaivalla. Jos sinulla on pääsy vain Windows-koneeseen, jonka käyttöjärjestelmänä on Windows 10, käy ennen osan aloittamista läpi [nämä](https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10) ohjeet. Tällöin pystyt ajamaan komentorivillä komentoja kuten Linux-koneella.

Muuten Windowsilla kurssin suorittaminen on vaikeaa, eikä järin tavoitteellista, sillä tarkoitus on nimenomaan tutustua Unix-komentoriviin. Jos olet tietojenkäsittelytieteen pääaineopiskelija, kannattaa tässä tapauksessa ensimmäisen viikon tehtävät tehdä osaston paja-luokkien koneilla. Mikäli sinulla ei ole käytössä muuta, kuin vanha Windows, ota yhteys kurssin järjestäjiin.

Kurssin suorittaminen vaatii muutaman ohjelman asentamista koneelle. Mikäli et suorita kurssia osaston koneilla, varmista, että sinulla on käyttämääsi järjestelmään asennusoikeus.

Jos teet tehtäviä kotikoneella, ja olet läsnäoleva yliopisto-opiskelija, asenna ensin [Eduroam](https://www.eduroam.org/what-is-eduroam/), jolla pääset internetiin Helsingin yliopiston kampusalueilla. Helpdeskillä on sille [ohjeet](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/eduroam-verkon-asennus-asetustiedoston-avulla). Suosi aina Eduroamia yliopiston toisen verkon, HUPnetin yli. Internetin käyttö Eduroamin yli on turvallisempaa, ja se on saatavilla kampusalueilla myös ulkomailla.

**Mikäli olet tietojenkäsittelytieteen pää- tai sivuaineopiskelija, aktivoi CS-tunnuksesi seuraavan sivun [ohjeiden](https://www.cs.helsinki.fi/tietotekniikka/k-ytt-luvat) mukaan ennen materiaalin lukemista.**

<h2>Ohjeita materiaalin lukemiseen</h2>

Prosenttiluku tehtävän nimen edessä kertoo, kuinka monta prosenttia se vastaa kyseisen osan laskaripisteistä.

Materiaali on rakennettu niin, että sitä voi seurata tehden esimerkit samalla. Suosittelemme tätä vahvasti.

Mikäli löydät virheen tai typon materiaalista, forkkaa tämä projekti, korjaa virhe omaan versioosi, ja tee pull request.
