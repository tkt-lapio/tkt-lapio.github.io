---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
list_title: Materiaali
---
{%- assign course = site.data.data.course -%}

<h3>A link to the English page is in the upper right corner</h3>

<h1 id="main-title">Tervetuloa Tietokone Työvälineenä -kurssin kotisivulle. </h1>

Tämä kurssi on tarkoitettu Helsingin yliopiston tietojenkäsittelytieteen ensimmäisen vuoden opiskelijoille. Kurssilla tutustutaan komentoriviin Unix-tyyppisissä järjestelmissä, opetellaan Git-versionhallintatyökalun käyttöä sekä hieman HTML ja CSS-kieliä. Tarkoituksena on oppia tietojenkäsittelytietelijän käytännön taitoja, ja käyttämään opinnoissa hyödyllisiä työvälineitä. Kurssilla harjoitellaan myös tiedon itsenäistä hakemista internetistä.

<h2>Kurssin suorittaminen</h2>
Kurssi suoritetaan verkkotentillä, joka tehdään [Moodle-oppimisympäristössä](https://moodle.helsinki.fi/). Moodle on yliopistolla lajaasti käytössä oleva sivusto, joka mahdollistaa sähköisen etäopetuksen järjestämisen. Kurssille on olemassa [oma kurssialue]({{course.moodle}}). Moodle-alueelle pääsy vaatii kurssiavaimen, joka on <strong>lapio-on-tyovaline</strong>. Tentti perustuu pääosin tältä sivustolta löytyvään materiaaliin, joka on jaettu kolmeen osaan: Komentorivin perusteet, Git ja versionhallinta, sekä HTML ja CSS.

Jos aiheista on kokemusta aikaisemmin, materiaalin lukeminen tai tehtävien tekeminen ei ole välttämätöntä tentin läpipääsemiseksi, vaan tenttiin voi osallistua suoraan. Jos kuitenkin käsiteltävät asiat ovat vieraita, kannattaa materiaali käydä läpi huolellisesti, sillä kurssilla opeteltavia taitoja tulet varmasti tarvitsemaan tulevissa opinnoissa. Vaikka et muuten lukisi materiaalia, lue silti tältä sivulta löytyvät [ohjeet osaston IT-järjestelmiin](/osaston-jarjestelmat).

Jokaisen osan alussa on määritelty oppimistavoitteet, joiden perusteella voit määritellä itse, oletko valmis osallistumaan tenttiin.

Tehtäviä tekemällä ansaitsee laskaripisteitä, jotka lasketaan mukaan kurssipisteisiin. Laskaripisteet merkitään Moodle-alueella. Voit lukea kurssipisteistä lisää [arvostelu-sivulta](/tentti).

## Tukikanavat

Kurssilla on käytössä sähköinen tukikanava, joka sijaitsee Telegramissa.
- <a href="https://t.me/tktlapio">Liittymislinkki Telegram-ryhmään</a>

Tukikanavalla saa esittää mitä tahansa kurssiin liittyviä kysymyksiä. Kurssikavereiden auttaminen on suotavaa.

Syrjiviä tai asiattomia kommentteja ei sallita, ja niiden esittäjä poistetaan kanavalta.

Lisäksi kurssille järjestetään johonkin toteutukseen pajaohjaus, jolloin on mahdollista tulla tekemään tehtäviä osaston tiloihin, ja saada halutessaan apua kurssin assistenteilta. Kesällä pajaohjausta ei järjestetä. <!---Lue lisää pajasta, ja sen aikatauluista [täältä](/paja). --->

## Välineet

Tehtävät on mahdollista tehdä millä tahansa Unix-tyyppisellä käyttöjärjestelmällä. Käytännössä tämä tarkoittaa useimmiten Linux- tai macOS-tietokoneita. Mikäli mahdollista, suosittelemme SSH-tehtävää lukuunottamatta tehtävien tekemistä osaston koneilla, joissa on yliopiston oma Linuxin jakeluversio [Cubbli](https://helpdesk.it.helsinki.fi/ohjeet/tietokone-ja-tulostaminen/tyoasemapalvelu/yleista-cubblista).

[Windows ei kuulu Unix-tyyppisten käyttöjärjestelmien perheeseen](https://en.wikipedia.org/wiki/Unix-like). Kurssin suorittamiseksi Windows-koneella on kuitenkin useita vaihtoehtoja:



### **Windows Subsystem for Linux**

Windows 10 -käyttöjärjestelmässä voit asentaa Ubuntun Windowsiin ohjelmistona. Tällöin saat käyttöösi kurssin suorittamiseen soveltuvan Linux-ympäristön ilman suurempia säätöjä. Ubuntu on yksi lukuisista Linux-jakeluversioista (tuttavallisemmin distro), josta muokattua versiota käytetään myös osaston koneilla.

Windows Subsystem for Linuxin asennus:

1. Avaa [Powershell järjestelmänvalvojana](https://www.thewindowsclub.com/how-to-open-an-elevated-powershell-prompt-in-windows-10) ja kopioi ilmestyvään tekstikenttään 
<br>*Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux*
<br>(Koodi asentaa ominaisuuden mikäli sitä ei ole asennettu. **Älä KOSKAAN suorita vierasta koodia koneellasi, jos et tiedä mitä se tekee**)
2. Asenna 'Ubuntu'-sovellus [Microsoft Storesta](https://www.microsoft.com/fi-fi/p/ubuntu/9nblggh4msv6?activetab=pivot%3Aoverviewtab).
3. Käynnistä Ubuntu-sovellus ja luo käyttäjä Ubuntua varten.

![opasvideo asennuksesta](/assets/wsl_v1.mp4)

Tarkat ohjeet asentamiseen löydät [tästä linkistä](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

Jos pelkkä tekstipohjainen käyttöliittymä vaikuttaa pelottavalta voit myös asentaa Ubuntun virtualisoituun ympäristöön käyttäen esimerkiksi alla esiteltyä VirtualBox-ohjelmistoa.

### **VirtualBox**

Varmista ennen asentamista, että sinulla on vähintään 512 Mt, mutta mieluiten 1 Gt [RAM-muistia](https://www.computerhope.com/issues/ch000149.htm) vapaana koneellasi.

VirtualBoxin asennus:

1. Lataa ja asenna VirtualBox [täältä](https://www.virtualbox.org/wiki/Downloads).
2. Lataa Ubuntu 22.04:n levykuva (.iso) [täältä](http://releases.ubuntu.com/22.04/). Jos olet koskaan asentanut käyttöjärjestelmää CD:ltä, tämä .iso-tiedosto on tavallaan sen sisältö.
3. Seuraa [näitä ohjeita](http://www.psychocats.net/ubuntu/virtualbox) luodaksesi virtuaalikoneen.
4. Käynnistä virtuaalikone VirtualBoxista.

Kysy rohkeasti apua, mikäli kohtaat ongelmia, ja ilmoita, mikäli voimme parantaa materiaalia Windows-käyttäjiä ajatellen!

## Ennen materiaalin aloittamista

Kurssin suorittaminen vaatii muutaman ohjelman asentamista koneelle. Mikäli et suorita kurssia osaston koneilla, varmista, että sinulla on käyttämääsi järjestelmään asennusoikeus.

Jos teet tehtäviä omalla kannettavalla, ja olet läsnäoleva yliopisto-opiskelija, asenna ensin [Eduroam](https://www.eduroam.org/what-is-eduroam/), jolla pääset internetiin Helsingin yliopiston kampusalueilla. Helpdeskillä on sille [ohjeet](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/eduroam-verkon-asennus-asetustiedoston-avulla). Suosi aina Eduroamia yliopiston toisen verkon, HUPnetin yli. Internetin käyttö Eduroamin yli on turvallisempaa, ja se on saatavilla kampusalueilla myös ulkomailla.

## Ohjeita materiaalin lukemiseen

Prosenttiluku tehtävän nimen jälkeen kertoo, kuinka monta prosenttia se vastaa kyseisen osan laskaripisteistä.

Materiaali on rakennettu niin, että sitä voi seurata tehden esimerkit samalla. Suosittelemme tätä vahvasti.

Mikäli löydät virheen tai typon materiaalista, forkkaa [tämä](https://github.com/tkt-lapio/tkt-lapio.github.io) projekti, korjaa virhe omaan versioosi, ja tee pull request (tästä puhutaan toisessa osassa).
