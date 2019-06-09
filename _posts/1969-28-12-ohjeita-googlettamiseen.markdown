---
layout: material
title: "Ohjeita tehokkaaseen googlettamiseen"
date: 1969-12-28 00:05:00 +0200
permalink: "/ohjeita-googlettamiseen/"
tag: info
---

Tällä kurssilla tulee monta kertaa vastaan tehtävä, jossa kehotetaan selvittämään itse, miten jonkin asian voi tehdä. Tiedon hakeminen itsenäisesti Internetistä on olennainen osa ohjelmoijan työtä: keneltäkään harvoin odotetaan, että tietyn komennon parametrien tai metodien nimet muistettaisiin ulkoa. Oleellista on kyetä etsimään tarvittaessa luotettavaa tietoa Internetistä.

Seuraavassa joitain ohjeita, miten hakea parhaiten apua ohjelmointiongelmiin:

## Hae tietoa englanniksi.

Englanti on ohjelmointiyhteisön pääasiallinen kieli, ja sillä löytyy eniten hakutuloksia, jolloin todennäköisesti suurempi osa on luotettavia.

## Voit käyttää haussa myös vain avainsanoja.

Nykyään erityisesti Google ymmärtää varsin hyvin kokonaisia lauseita. Joskus kokonainen lause voi kuitenkin sekoittaa tuloksia, kun hakukone keskittyy väärin sanoihin. Voit käyttää haussa myös vain avainsanoja, kuten: "Ubuntu command line move to folder" lauseen "How to move to a folder in Ubuntu command line" sijaan. 

## Käytä kontekstia.

Jos etsit ratkaisua ohjelmointiongelmaan, kannattaa aloittaa kielen nimellä. Jos tarvitset apua tietyn ohjelman kanssa, aloita ohjelman nimella. Lapio-kurssilla on erityisesti ensimmäisellä viikolla parasta aloittaa ympäristön nimellä: Unix. Osaston koneilla kannattaa käyttää sanaa "Linux" tai "Ubuntu". 

## Käy mahdollisuuksien mukaan läpi monta lähdettä.

Ohjelmoinnissa apua saa usein kanssakoodareilta, eikä niinkään virallisilta lähteiltä. Tällöin lähteen luotettavuutta on useimmiten vähintäänkin vaikea arvioida. Yksi tapa varmistaa vastauksen oikeellisuus on yksinkertaisesti käydä läpi niin monta vastausta kuin mahdollista -- vaikka toki usein sama tieto lipuu Internetissä eri muodoissa, eli kaikki nämä lähteet ovat voineet saada tietonsa samasta (virheellisestä) paikasta.

## Opettele käyttämään <a href="https://stackoverflow.com/">StackOverflow:ta</a>.

Harmillisen virheviestin mukaan nimensä saanut foorumi on luotu ohjelmoijien keskinäiseksi tukikanavaksi. Se onkin erittäin suosittu, ja ilmestyy varmasti usein hakutuloksissa. Et tarvitse käyttäjätunnusta selataksesi muiden vastauksia. Sivulla kannattaa kiinnittää huomiota pariin asiaan: käyttäjät voivat äänestää toisten vastauksia yös tai alaspäin. Mitä enemmän ääniä vastauksella on ylos, sitä ylempänä se näkyy sivulla. Lisäksi kysymyksen kysyjä voi merkata jonkin vastauksen toimivaksi. Tällöin vastauksessa näkyy vihreä oikein-merkki, ja se näkyy heti ensimmäisenä kysymyksen jälkeen. Kumpikaan näistä ei takaa, että vastaus on oikein, mutta erottavat usein hyödyttömimmät vastaukset pois.

<figure class="stackoverflow-example">
<img alt="Stackoverflow-esimerkki" src="/assets/exit_vim.png">
<figcatpion>Eräs pidetty ja hyväksytty vastaus Stack Overflow:ssa.</figcatpion>
</figure>


## Käytä Googlen hakusyntaksia.

Käytä merkkiä "-" sanan edessä poistaaksesi hausta epärelevantteja sanoja. Jos esimerkiksi haluaa etsiä tietoa Python-ohjelmointikielestä (eikä hakuhistoria ole vielä täynnä ohjelmointiin littyivä hakuja), voisi kirjoittaa hakusanaksi "python -snake". Jos haluat hakea sivuja, joissa esiintyy täsmälleen jokin lause, kirjoita se lainausmerkkien sisään. Löydät operaattorit esimerkiksi [täältä](https://support.google.com/websearch/answer/2466433).

## Käytä virheviestejä hyödyksi.

Mikäli ongelmasi liittyy jonkin tietyn ohjelman käyttöön, auttaa ohjelma todennäköisesti sinua virheviestillä. Virheviestit ovan kullanarvioisa debuggaamisessa, sillä ne on suunniteltu sisältämään oikeasti hyödyllistä tietoa ongelmasta. Ensinnäkin virheviesti kannattaa lukea itse läpi huolellisesti, sillä ohjelmasta riippuen ne saattavat olla hyvinkin yleistajuisia. Mikäli et kuitenkaan ymmärrä ongelmaa, usein kannattaa yksinkertaisesti googlettaa virheviesti suoraan -- yleensä se johtaa GitHubiin, jossa joku on tehnyt issuen samasta ongelmasta. Muista kuitenkin varmistaa, ettei virheviestissä ole omaa henkilökohtaista tietoa, esimerkiksi kotihakemistosi osoitetta. Pyri valitsemaan virheviestistä oleellisin osio, jota mahdollisimman moni muukin olisi Googlettanut. Virheviesti kannattaa antaa myös, kun pyytää apua vaikka kurssin tukikanavalla.

## Etsi samantyyppisiä ongelmia.

Joskus netistä ei löydy suoraan vastausta juuri tiettyyn ongelmaan. Tällöin tulee miettiä, voiko ongelman jakaa jotenkin osiin, ja etsiä jokaiselle niistä vastaus erikseen. Lisäksi ratkaisu ongelmaan voi löytyä vastauksesta, joka oikeasti käsittelee toista ongelmaa. Esimerkiksi Stack Overflow:n vastauksia selatessa kannattaa siis ensin lukea kysymys, ja miettiä, vastaako oma tilanteesi kysyjän tilannetta, eli voisiko tämän kysymyksen vastauksista olla juuri tässä tilanteessa hyötyä.
