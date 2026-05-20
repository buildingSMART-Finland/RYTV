# RYTV – Rakennetun Ympäristön Tietomalli Vaatimukset

RYTV on buildingSMART Finlandin ylläpitämä kansallinen tietomallivaatimuskokoelma, joka määrittelee yhteiset vaatimukset, ohjeet ja esimerkit rakennushankkeiden tietomallintamiselle Suomessa. Aineisto kattaa talonrakentamisen, infrarakentamisen sekä yleiset tietomallintamisen periaatteet.

## Sisältö

| Hakemisto | Kuvaus |
|---|---|
| `markdown/` | RYTV-aineistojen lähdetiedostot markdown-muodossa (yleinen, talo, infra) |
| `documentation/` | Työskentelyohjeet, esimerkit ja linkit ulkoisiin lähteisiin |
| `templates/` | Vakioidut asiakirjapohjat yhteistoiminnan käyttötarkoituksiin |
| `resources/` | Kuvat, kaaviot, taulukot ja muut resurssit |

## Aineistokategoriat ja metadata

Erilaiset RYTV aineistot on jaettu aineistokategorioihin ja niiden luokittelussa käytetään metadatana ns. tagejä. Löydät niiden kuvaukset [täältä](documentation/sisällön-tuottamisen-ohje.md).

## Osallistuminen

### Ideat ja kehitysehdotukset

Voit jättää idean tai kehitysehdotuksen GitHub Issues -toiminnon kautta:

1. Avaa repositoryn **Issues**-välilehti
2. Valitse **New Issue**
3. Täytä kuvaus ja lähetä — ylläpitäjille lähetetään automaattinen ilmoitus
4. Voit seurata tikettisi tilaa ja lisätä tarkentavia kommentteja samaan issueen

### Muutosten tekeminen

1. Haarauta (fork) tai luo uusi kehityshaara omille muutoksillesi
2. Tee muutokset markdown-tiedostoihin
3. Avaa **pull request** `development`-haaraan
4. Ylläpitäjät arvioivat muutokset ja antavat palautetta — kaikki keskustelu on julkista

> Päähaaraan (`main`) ja kehityshaaraan (`development`) kirjoitusoikeudet ovat vain ylläpitäjillä.

## Julkaisuprosessi

RYTV-lähdeaineistot ovat osa tätä GitHub-repositoryä. Lähdeaineistoista koostetaan varsinainen julkaisumateriaali erillisellä julkaisupipelinella (GitHub Actions).

## Lisätietoja

- [Sisällön tuottamisen ohje](documentation/sisällön-tuottamisen-ohje.md)
- [buildingSMART Finland](https://buildingsmart.fi)
