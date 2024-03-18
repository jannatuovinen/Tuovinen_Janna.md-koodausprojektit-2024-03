# Oma kotisivu
Django-pohjainen kotisivu. Olen aloittanut tämän projektin jo aiemmin, mutta se on ollut pitkään jäissä. Mulla on DigitalOceanin dropletissa ja kotona pyörivässä Raspberry Pi 5 palvelimessa aika paljon hostattu erilaisia palveluita Docker kontteina. Kun on kirjautuneena kotisivulleni tarvittavilla oikeuksilla voisi nähdä itse tehdyn dashboardin, jossa olisi linkkejä eri self-hosted palveluihin ja niiden hallintaan. Jossain vaiheessa sivulle voisi tehdä julkisen portfolion ja muuta mitä mieleen tulee... Tietoa tallennetaan PostgreSQL tietokantaan. Se on tällä hetkellä privaattirepossa, laitan ehkä myöhemmin linkin repoon.

## Tekniikat
* Ohjelmointikieli: Python, JavaScript
* Taustajärjestelmä: Django, PostgreSQL
* Käyttöliittymä: Puhdas HTML+CSS, Bootstrap, Bootstrap Studio

## Muuta?
Mulla on jo oma domaini, joka ohjaa liikenteen DigitalOceanille ja sieltä taas reverse proxyn kautta kotiini. Kotisivusta tulee Docker kontti, joka pyörii kotona RPi5:llä.
