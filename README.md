# Projektin nimi ja tekijät
Uimavesien lämpötilat PK-seudulla -sovellus
tekijä: Ville Muhonen

## Verkkolinkit:
Pääset julkaistuun sovellukseen käsiksi osoitteessa [https://uimavedet.netlify.app/](https://uimavedet.netlify.app/)
Linkki projektin videoesittelyyn [google.com](https://google.com)

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
`![Sovellus](https://raw.githubusercontent.com/muhisville/Uimavesi/refs/heads/main/kuvat/uimavedet.png)`

Kuva: [Ville Muhonen]

## Teknologiat
Kuvaa, mitä teknologioita käytettiin ja mikä oli niiden rooli projektissasi.  
Käytin seuraavia teknologioita: `html`, `css`, `Java Script`

## Asennus
Kirjoita lyhyet ohjeet sovelluksen käynnistämiseen ja käyttöön. Esimerkiksi:  
- mene osoitteeseen https://uimavedet.netlify.app/
- valitse alasvetovalikosta haluamasi uimaranta ja katso veden lämpötila 

## Kiitokset
- [Opettajan materiaali ja luentotallenteet](https://mika-stenberg.gitbook.io/web-sovelluksia-javascriptin-avulla)  
- [W3schools.com](https://www.w3schools.com/)  
- [Copilot](https://copilot.microsoft.com/) Tekoälyä on käytetty apuna koodin tarkistamisessa sekä spvelluksen ulkoasuun liittyvien ongelmien ratkaisussa.
- Kiitos myös opiskelijatoveri Iina Karhulle avusta, vertaistuesta ja sparrauksesta.


## Lisenssi
MIT-lisenssi @ [Ville Muhonen]
