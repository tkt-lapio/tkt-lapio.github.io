---
layout: material
title: 'Osaston järjestelmät'
date: 1969-12-28 00:00:00 +0200
permalink: /osaston-jarjestelmat/
tag: info
---

- Mikäli olet tietojenkäsittelytieteen pää- tai sivuaineopiskelija, aktivoi CS-tunnuksesi seuraavan sivun [ohjeiden](https://www.cs.helsinki.fi/tietotekniikka/k-ytt-luvat) mukaan.

- Yliopisto tarjoaa opiskelijoilleen kaksi langatonta verkkoa: HUPnetin ja Eduroamin. Näistä HUPnettiin on myös mahdollsita saada vierailijatunnuksia. Eduroamin käyttö on turvallisempaa (HUPnet on suojaamaton) ja suositeltavaa aina kun mahdollista. Eduroam-yhteys on tarjolla myös ulkomaisilla kampuksilla. Katso Helpdeskistä [ohjeet](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/eduroam-verkon-asennus-asetustiedoston-avulla)  Eduroamin asentamiseen. Löydät Helpdeskistä myös ohjeet Eduroamin asentamiseksi esimerkiksi [Androidille](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/eduroam-android-laitteissa) ja [iPhonelle ja iPadille](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/ipad-ja-iphone-langattomat-yhteydet). Lisätietoa Eduroamista löytyy [täältä](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/langattomat-yhteydet-yliopistolla) tai [täältä](https://www.eduroam.org/).

- Tietojenkäsittelytieteen osasto tarjoaa neljä eri palvelinta osaston koneisiin SSH-etäyhteyden luomiseksi. Näihin palvelimiin on pääsy opiskelijoilla, joilla on tietojenkäsittelytieteen osaston tunnus:

  - melkki.cs.helsinki.fi
  - melkinpaasi.cs.helsinki.fi
  - shell.cs.helsinki.fi
  - melkinkari.cs.helsinki.fi

Kaikki nämä palvelimet ohjaavat siis samaan käyttäjäkohtaiseen yliopiston ad-kotihakemistoon, johon pääsee kaikilta osaston koneilta. Kirjautuminen tapahtuu osaston käyttäjätunnuksilla.

<div class="warning">
Mikäli käytät yliopoiston palvelimia SSH-yhteyden yli, ja lisäät yksityisen avaimen SSH-agentille, on yksityinen avain yliopiston sääntöjen mukaan suojattava salasanalla. 
</div>

- Osaston tunnuksen myötä saa yliopiston ad-kotihakemiston lisäksi cs-kotihakemiston. CS-kotihakemisto sijaitsee polussa `/cs/home/<käyttäjätunnus>`. Tämän avulla on esimerkiksi mahdollista luoda itselleen laitoksen kotisivu osoitteeseen `https://www.cs.helsinki.fi/u/omatunnus/`. HTML-sivu luodaan polkuun `/cs/home/tunnus/public_html/index.html` (saatat joutua luomaan kansion `public_html`).

- Osastolla on myös laskentaklusteri nimeltään [Ukko](https://www.cs.helsinki.fi/tietotekniikka/laskentaklusteri-ukko).

- Älä aja laitoksen järjestelmissä sudo-komentoja. Siitä lähtee ylläpidolle väärinkäyttöilmoitus.