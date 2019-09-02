---
layout: material
title: 'Osaston järjestelmät'
date: 1969-12-28 00:00:00 +0200
permalink: /osaston-jarjestelmat/
tag: info
---
<div class="warning">
    Materiaaleissa puhutaan CS-tunnuksista, jotka ovat todennäköisesti poistumassa jossain vaiheessa. Materiaaleja päivitetään, kun CS-tunnusten tilanne varmistuu. Tehtävien tekemiseen CS-tunnuksia ei tarvita.
</div>

- Mikäli olet tietojenkäsittelytieteen pää- tai sivuaineopiskelija, aktivoi yliopiston tunnuksesi [täällä](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/kayttajatunnus/uuden-kayttajatunnuksen-aktivointi) ja CS-tunnuksesi seuraavan sivun [ohjeiden](https://www.cs.helsinki.fi/tietotekniikka/k-ytt-luvat) mukaan.

- Yliopisto tarjoaa opiskelijoilleen kaksi langatonta verkkoa: HUPnetin ja Eduroamin. Näistä HUPnettiin on myös mahdollsita saada vierailijatunnuksia. Eduroamin käyttö on turvallisempaa (HUPnet on suojaamaton) ja suositeltavaa aina kun mahdollista. Eduroam-yhteys on tarjolla myös ulkomaisilla kampuksilla. Katso Helpdeskistä [ohjeet](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/eduroam-verkon-asennus-asetustiedoston-avulla)  Eduroamin asentamiseen. Löydät Helpdeskistä myös ohjeet Eduroamin asentamiseksi esimerkiksi [Androidille](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/eduroam-android-laitteissa) ja [iPhonelle ja iPadille](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/ipad-ja-iphone-langattomat-yhteydet). Lisätietoa Eduroamista löytyy [täältä](https://helpdesk.it.helsinki.fi/ohjeet/kirjautuminen-ja-yhteydet/verkkoyhteydet/langattomat-yhteydet-yliopistolla) tai [täältä](https://www.eduroam.org/).

- Tietojenkäsittelytieteen osasto tarjoaa neljä eri palvelinta osaston koneisiin SSH-etäyhteyden luomiseksi. Kirjautuminen tapahtuu yliopiston tunnuksilla.

  - melkki.cs.helsinki.fi
  - melkinpaasi.cs.helsinki.fi
  - shell.cs.helsinki.fi
  - melkinkari.cs.helsinki.fi

Kaikki nämä palvelimet ohjaavat siis samaan käyttäjäkohtaiseen yliopiston ad-kotihakemistoon, johon pääsee kaikilta osaston koneilta. Kirjautuminen tapahtuu osaston käyttäjätunnuksilla.

<div class="warning">
Mikäli käytät yliopiston palvelimia SSH-yhteyden yli, on yksityinen avain yliopiston sääntöjen mukaan suojattava salasanalla.
</div>

- Osaston tunnuksen myötä saa yliopiston ad-kotihakemiston lisäksi CS-kotihakemiston. CS-kotihakemisto sijaitsee polussa `/cs/home/<käyttäjätunnus>`. Pääset CS-kotihakemistoon samasta järjestelmästä, jossa ad-kotihakemisto sijaitsee. CS-kotihakemiston avulla on esimerkiksi mahdollista luoda itselleen laitoksen kotisivu osoitteeseen `https://www.cs.helsinki.fi/u/omatunnus/`. HTML-sivu luodaan polkuun `/cs/home/tunnus/public_html/index.html` (saatat joutua luomaan kansion `public_html`).

- Osastolla on myös laskentaklusterit nimeltään [Ukko2](https://wiki.helsinki.fi/display/it4sci/Ukko2+User+Guide) sekä [Kale](https://wiki.helsinki.fi/display/it4sci/Kale+User+Guide). Pääsy klustereille on rajoitettu henkilökunnalle sekä erillisiä käyttöoikeuksia pyytäneille.

- Älä aja laitoksen järjestelmissä sudo-komentoja. Siitä lähtee ylläpidolle väärinkäyttöilmoitus.

- Tietojenkäsittelytieteen pääaineopioskelijat saavat yliopiston kautta käyttöösi `cs.helsinki.fi` ja `helsinki.fi` -sähköpostit. TKO-älyn fuksiwikissä on [ohjeet](https://fuksiwiki.tko-aly.fi/S%C3%A4hk%C3%B6postitilit) siihen liittyen. Office 365 -järjestelmässä on myös kalenteri, jonka kautta voi varata erilaisia kokoustiloja esimerkiksi Kaisa-talosta.

  **Käytännössä kannattaa valita yksi sähköposti jota käyttää, ja varmuuden vuoksi uudelleenohjata liikenne esimerkiksi helsinki.fi -sähköpostista cs.helsinki.fi -sähköpostiin ([ohjeet](https://helpdesk.it.helsinki.fi/ohjeet/yhteydenpito-ja-julkaiseminen/sahkoposti/postin-ohjaus-pois-office-365sta)) tai toisin päin.**
