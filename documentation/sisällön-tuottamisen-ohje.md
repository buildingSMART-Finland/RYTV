# Sisällön tuottaminen

## Näin osallistut

TODO: Ylätason kuvaus osallistumisesta ja sen periaatteista.

### Jätä idea tai kehitysehdotus

TODO: Näiden tarkentaminen

Githubissa on mahdollista jättää kehitysehdotus tai idea:

1. Painamalla RYTV repon yläpalkista Issues
2. New Issue
3. Luo halutunlainen Issue ja kirjoita kuvauksesi
4. Uudesta Issuesta lähtee ilmoitus RYTV repon ylläpitäjille
5. Luodun "tiketin" tilan voit käydä tarkastamassa myöhemmin samasta Issues näkymästä. Myös tarkentavat kommentit voi jättää saman Issuen alle.

### RYTV lähdetiedostojen kopioiminen omalle työasemalle

RYTV:n sisällön editointiin voit käyttää esimerkiksi Visual Studio Codea. Internetistä löytyvät ohjeet lähdetiedostojen kopiointiin omalle koneelle ja pull requestin tekemiseen muutosten jälkeen. Päähaaraan ja development haaraan oikeudet ovat vain ylläpitäjillä. Kaikki muutokset tehdään pull requestin kautta development haaraan. Lue tarkemmin kohdasta "Julkaisun hallinta"

## RYTV rakenne

TODO: Selite näistä:

* RYTV kansiot
* README
* Aiheisiin ryhmitellyt ennakkoaineistot

## Aineistot ja kirjoitusohjeet

### Aineistojen metatieto ja luokittelu

| Metadata label            | Käytettävät arvot |
|-------------------|------|
| Toimiala           | Yleinen, Talo, Infra, Kaupunki |
| Käyttötapaus       | Linkki liittyvään käyttötapaukseen md syntaksin mukaisesti, käyttäen käyttötapauksen otsikkoa tekstinä |
| Elinkaarivaihe     | Tuotanto, Rakentaminen, Käyttö ja ylläpito, Purkaminen ja elinkaaren jälkeinen hyödyntäminen |
| Rooli              | Linkki liittyvään rooliin md syntaksin mukaisesti, käyttäen roolin otsikkoa tekstinä |
| Vaihtoehtoinen     | Vaihtoehto |
| Teksti ID          | Yksilöllinen tunniste, jolla aineiston osaan ja versioon voidaan viitata. Generoidaan julkaisun yhteydessä. |
| Vaatimuksen taso   | Lainsäädäntö, Tiedonvaihto, Liiketoiminta |

TODO: Selite mikä on tagi ja mitä sillä tavoitellaan

### Aineistokategoriat

RYTV sisältää erilaisia aineistoja. Aineistot on jaettu alla oleviin aineistokategorioihin.

#### Visio

Visio kuvaa tulevaisuuden tahtotilan, tarjoten kehityssyötteitä sidosryhmille kuten ohjelmisto- ja laitetoimittajille. Visio ei todennäköisesti ole täysin toteutettavissa tämän hetkisillä menetelmillä tai ainakin se olisi työlästä tavanomaisissa hankkeissa.

Ehdotettu nimi visolle Kehitystarve

#### Käyttötapaus

Käyttötapaus määrittelee tiiviisti tavoitteen ja tarpeen, jonka täyttämiseksi asetetaan vaatimuksia ja ohjeita. Käyttötapaus tulee olla täytettävissä nykyisillä menetelmillä. Käyttötapaus on käyttötarvetta yleisempi esim. "määrälaskenta". Koostuu käyttötapauskuvauksesta (IDM) ja Informaatiotarpvetaulukosta (LOIN). Vastaa kysymyksiin Miksi, Koska, Kuka, Mitä ja missä muodossa?

<del>

#### Käyttötarve

Käyttötarve määrittelee tiiviisti tavoitteen ja tarpeen, jonka täyttämiseksi asetetaan vaatimuksia ja ohjeita. Käyttötarpeen tulee olla täytettävissä nykyisillä menetelmillä. Käyttötarve on käyttötapausta tarkempi esim. "määrälaskenta LCA-laskennan tarpeisiin". Vastaa kysymykseen MIKSI.

</del>

#### Vaatimus

Vaatimus on yksiselitteiseen muotoon kirjoitettu teksti, johon voidaan viitata sopimuksissa ja joka pohjautuu tai noudattaa suoraan lakia, standardia tai vakiintuneita käytäntöjä. Vaatimusta täydennetään ohjeilla ja esimerkeillä. Vastaa kysymykseen MITÄ.

#### Ohje

Ohje kertoo, miten vaatimus täytetään tai miten jokin asia toimii käytännössä. Esimerkki kuvaa parhaan tai hyväksi havaitun toimintatavan tavoitteen saavuttamiseksi. <del> Ohjeesta poikkeaminen edellyttää toimeksisaajalta perusteluja ja tilaajan hyväksyntää. Vaihtoehtoiset ohjeet on sovittava sopimuksessa tai tarkennettava projektin alussa. </del> Ohje on kuvaus, jossa kerrotaan tarkkaan kuinka jokin asia tehdään. Voi linkkautua esimerkkeihin. Vastaa kysymykseen MITEN.

#### Esimerkki

Esimerkki havainnollistaa aineistojen käyttöä konkreettisella tavalla, ja sen kuvauksen tulee olla helposti ymmärrettävä ilman syvällistä teknistä osaamista. Esimerkki ei mene yksityiskohtiin, mutta se toimii havainnollistavana kuvauksena muiden aineistojen mukaisesta toiminnasta. Esimerkin on oltava todellinen, ja tarvittaessa voidaan käyttää useampia esimerkkejä, joita linkataan toisiinsa, jotta muodostetaan ehjä kokonaisuus aineiston käytöstä. Vastaa ylätasolla kysymykseen MITEN ja voi linkittyä tarkempiin ohjeisiin.

#### Asiakirjapohja

Asiakirjapohja, joka on vakioitu kansalliseen yhteistoiminnan käyttötarkoituksiin. Asiakirja voi olla tekstidokumentti, taulukko tai kaavio.

#### Tiedosto tai schema <del> / Tietokanta </del>

Tiedosto <del> tai tietokanta </del> tai schema, joka kuvaa jonkin tiedon rakenteen yhteistoiminnan käyttötarkoituksiin. Voi käyttää erilaisia serialisointiformaatteja, mutta kuvaa tiedonvaihdossa käytettävää tietorakennetta tai toimii esimerkkitiedostona johonkin käyttötarkoitukseen. Esimerkiksi IDS-tiedosto tai json schema jostakin tietorakenteesta <del> bsDD-tietokanta </del>.

#### Roolikuvaus [Uusi]

Määrittelee roolin ja siihen liittyviä vastuiden ja tehtävien rajauksia. Suositellaan pohjautuvan aina standardiin ja alan vakiintuineisiin käytäntöihin. Mahdollistaa viittaukset tekstistä yhteisesti sovittuun kuvaukseen roolista. Vastaa erityisesti kysymyksiin KUKA ja MITÄ samassa kuvauksessa.

#### Päätöksentekopiste [Uusi]

Määrittelee jonkin keskeisen vaiheen ja siihen liittyvät roolit (viittaus roolikuvaukseen). Mahdollistaa viittauksen tekstistä kuvaukseen.

### Kuva

TODO: Miten kuvaa käytetään

### Kaavio

TODO: Miten kaaviota käytetään

## Julkaisun hallinta

TODO: Kuvaus ylätasolla. Ylläpitäjillä on erikseen ohjeet julkaisun tekemiseksi.

RYTV:n lähdeaineistot ovat osana Github repositoryä. Lähdeaineistosta koostetaan varsinainen RYTV:n julkaisumateriaali erillisellä julkaisupipelinella, joka rakennetaan käyttämään Github Actionsiä.

### Uudet lisäykset tai jatkokehitys

TODO: Poista toisto

Uudet aineistot ja olemassa olevien aineistojen jatkokehitys tehdään erillisessä kehityshaarassa (branch). Kehityshaarasta avataan pull request **development** haaraan, jolloin RYTV:n ylläpitäjät voivat hyväksyä tai ehdottaa muutoksia pull requestiin. Keskustelu jonkin lisäyksen julkaisusta osaksi RYTV aineistoa tulee aina olla julkista ja pull requestia ei voi hylätä tai hyväksyä ilman kommenttia.

### Pull requestin luominen

### Uuden version tagays ja build, sekä release

TODO: Nämä ovat ylläpitäjän ohjeita, joten ei välttämättä tarpeen