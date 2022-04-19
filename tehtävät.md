# H3 Versionhallinta

## z) Lue ja tiivistä [artikkeli](https://commonmark.org/help/)
* Markdown on yksinkertainen tapa muotoilla tekstiä.
* Sillä ei ole mahdollista muuttaa fontin kokoa, väriä jne.
* Otsitkot risuaidoilla, tyhjällä rivillä kappalejako, sisennyksellä koodinkirjoitus.
* Viivoilla listat, haka- ja normisuluilla linkki --> huutomerkki eteen kuvalle.

## b) Pull first. Tee useita muutoksia git-varastoosi. Tee muutama muutos, jossa yksi commit koskee useampaa tiedostoa. Anna hyvä kuvaukset (commit message), yksi englanninkielinen lause imperatiivissa (määräysmuodossa) "Add top level menu to Foobar synchronizer"
Päätin lisätä muutaman satunnaisen tekstitiedoston git-varastooni. Tehtävään liittyvät tiedostot ovat satunnainen ja random.
Niiden sisälle laitoin yksinkertaiset koodinpätkät, "cd /home/nico/Demo" ja "ls /home/nico/Demo". Tämän jälkeen lisäsin kuvauksen "Add homework b)".
Sen jälkeen "git pull" ja "git push" ja ne olivat git-varastossani. ![Tehtävä](https://imgur.com/Lc1CiUV.png)

## c) Kaikki kirjataan. Näytä omalla git-varastollasi esimerkit komennoista ‘git log’, ‘git diff’ ja ‘git blame’. Selitä tulokset.
Aloitin komennosta "git log". Kyseinen komento käytössä olevan git-varaston lokihistorian.
Lokeista näkyy suoraan mikä on muutoksen tekijän nimi sekä annettu sähköpostiosoite,
muokkausaika ja päivämäärä sekä commit message. Lisäksi jokaisen commitin "hash" näkyy.
![git log](https://imgur.com/zDn1KBb.png)

Seuraava komento oli "git diff". Komento kertoo tiedostolle tapahtuneet muutokset.
 Itselläni tiedostonimi vain näkyi tyhmästi sillä se sisälsi ääkkösiä. Kuitenkin komennolla
 näkyi missä tiedostossa muutokset olivat tapahtuneet ja mitä sinne oli lisätty tai poistettu.
![git diff](https://imgur.com/DB4dlzi.png)

Viimeisenä oli komento "git blame". Se vaati kuitenkin vielä perään tiedostonimen, sillä
 sen avulla nähdään tiedostosta rivi riviltä tapahtuneet muutokset, niiden tekijät
  sekä tarkat ajankohdat. Lisäksi näkyi onko muutosta commitattu vielä.
![git blame](https://imgur.com/DcAbVUq.png)
