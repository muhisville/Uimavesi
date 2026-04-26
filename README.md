# Projektin nimi ja tekijät
Uimavesien lämpötilat PK-seudulla -sovellus
tekijä: Ville Muhonen

## Verkkolinkit:
Pääset julkaistuun sovellukseen käsiksi osoitteessa [https://uimavedet.netlify.app/](https://uimavedet.netlify.app/)
Linkki projektin videoesittelyyn [youtube.com](https://youtu.be/SJ52DcYlydI)

## Työn jakautuminen 
Tein työn kokonaan itse.

## Oma arvio työstä ja oman osaamisen kehittymisestä
Mielestäni onnistuin tekemään toimivan sovelluksen, joka toimittaa sen minkä lupaa selkeässä muodossa.
Parantamista olisi siinä, että js-koodissa data haetaan apissa kahteen kertaan: ensin valikkoa muodostettaessa ja sitten dataa haettaessa. Datan haun ja parsimisen olisi voinut laittaa yhden globaalin muuttujan alle, mutta en saanut sitä toimimaan, joten annoin olla.
Sovellukseen olisi voinut lisätä esimerksiksi sinilevä- ja veden laatu -dataa muista API:sta, mutta koska tehtävänanto edellytti vain yhden API:n käyttämistä, en tällä kertaa tehnyt niin ajanpuutteen vuoksi. Ehkä kehitän sovellusta jatkossa pidemmälle.
Koen, että olen oppinut jälleen paljon JS:n kirjoittamisesta. Yllätin itsenikin sillä, että osaan aika hyvin päätellä itse, miten koodin saisi toimimaan. Yhä vähemmän tarvitsee googlailla ja käyttää tekoälyä.
Epäselväksi jäi kenties edellä mainittu globaalin muuttujan rakentaminen, kun sen pitäisi toimia funktioiden sisällä.
Antaisin itselleni pisteitä seuraavasti: 9/10 p

## Palaute opettajalle kurssista sekä itse opetuksesta tähän saakka
Kurssi on tuntunut laadukkaalta sekä mukavalta. Aihe on kiinnostava, opetus vastaa opiskelijoiden tarpeisiin, oppituntien jälkeen asiat tuntuvat selkeiltä ja opittua on helppo soveltaa käytäntöön. On hyvä, että kurssi kestää koko kevään ja projekteille on varattu paljon aikaa. Muuten yhteensovittaminen muiden kurssien ja työn kanssa voisi olla haastavaa.
Oppimistani tukisi jos voisin keskittyä kurssiin täysipainoisemmin, sillä koodaaminen kysyy paljon aikaa. Koodaaminen ja sovellusten rakentelu on myös niin mukavaa ja palkitsevaa, että olisi mukava, jos saisi opiskella vain sitä.


## Sisällysluettelo:

- [Tietoja sovelluksesta](#tietoja-sovelluksesta)
- [Tunnetut virheet/bugit](#Tunnetut virheet/bugit)
- [Kuvakaappaukset](#kuvakaappaukset)
- [Teknologiat](#teknologiat)
- [Asennus](#asennus)
- [Lähestymistapa](#lähestymistapa)
- [Kiitokset](#kiitokset)
- [Lisenssi](#lisenssi)

## Tietoja sovelluksesta
[Uimavedet] on sovellus, joka kertoo käyttäjälle reaaliaikaista dataa pääkaupunkiseudun uimarantojen vesien lämpötiloista. Tiedot päivittyvät noin 30 minuutin välein.

## Tunnetut virheet/bugit
Sovelluksen taustaväri vaihtuu sen mukaan, miten lammintä näytettävän uimarannan vesi on. Kaikki lämpömittarit eivät kuitenkaan toimita oikeaa tietoa, sillä ne voivat olla talviteloilla tai muuten väliaikaisesti pois käytöstä. Tässä tapauksessa sovellus antaa virheilmoituksen. Taustaväri kuitenkin noudattaa edellisen, onnistuneen haun tulosta. Se ei ole varsinainen virhe, mutta olisi kiva korjata jossain vaiheessa.

## Kuvakaappaukset
Lisää tähän vähintään yksi kuvakaappaus toimivasta sovelluksesta  
`![Kirjoittaminen](https://unsplash.com/photos/VBPzRgd7gfc)`

Kuva: [Kelly Sikkema](https://unsplash.com/@kellysikkema)

## Teknologiat
Kuvaa, mitä teknologioita käytettiin ja mikä oli niiden rooli projektissasi.  
Käytin seuraavia teknologioita: `html`, `css`, ...

## Asennus
Kirjoita lyhyet ohjeet sovelluksen käynnistämiseen ja käyttöön. Esimerkiksi:  
- lataa kaikki tiedostot ja avaa index.html selaimessasi  
- lataa tai kloonaa repositorio  
- suorita `npm install`  
- ...

## Kiitokset
Lista lähteistä ja esimerkeistä, joita käytit projektin aikana. Mainitse myös, jos käytit ChatGPT:tä tai muita tekoälytyökaluja koodauksen aikana ja kerro, miten ne auttoivat sinua.  
- [John Doe](johndoe.com)  
- [Beginners guide to BEM](link-goes-here.com)  

## Lisenssi
Valitse projektille lisenssi seuraamalla tätä [opasta](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository).

Esimerkki: MIT-lisenssi @ [tekijä](author.com)
