# Miten CSS ja Javascript voivat parantaa tai heikentää saavutettavuutta?

CSS (Cascading Style Sheets) ja JavaScript ovat tärkeitä työkaluja verkkosivujen suunnittelussa ja toiminnallisuudessa. Ne voivat parantaa sivuston käyttäjäkokemusta ja saavutettavuutta, mutta ne voivat myös aiheuttaa esteitä, jos niitä käytetään väärin.

## CSS:n rooli saavutettavuudessa

**Parantaa saavutettavuutta:** CSS:n avulla voidaan luoda selkeä ja ymmärrettävä visuaalinen esitys, joka tekee sivustosta helpommin navigoitavan1. Esimerkiksi, voit valita järkeviä fonttikokoja, rivikorkeuksia, kirjainvälejä jne. tekstin loogisuuden, luettavuuden ja mukavuuden parantamiseksi1.

**Heikentää saavutettavuutta:** Jos CSS:ää käytetään väärin, se voi aiheuttaa sekaannusta ja käytettävyysongelmia kaikille, mutta erityisesti vammaisille käyttäjille. Esimerkiksi, otsikko menettää visuaalisen tarkoituksensa, jos tyylität sen niin, ettei se näytä otsikolta.

### Esimerkkejä CSS:n käytöstä saavutettavuuden parantamiseksi:**

1. **Kontrasti**: Kontrastin lisääminen tekstiin ja taustaan voi auttaa käyttäjiä, joilla on näkövamma, erottamaan tekstin helpommin. WCAG-ohjeet suosittelevat tiettyjä kontrastisääntöjä, jotka on hyvä ottaa huomioon suunnittelussa.

2. **Fonttikoot ja -tyylit**: Fonttikoot ja -tyylit voivat vaikuttaa sivuston luettavuuteen. On tärkeää käyttää riittävän suuria fonttikokoja ja helppolukuisia fontteja, jotta sivustoa on helppo lukea kaikilla laitteilla ja näytöillä.

3. **Responsiivinen suunnittelu**: CSS:llä voidaan toteuttaa responsiivinen suunnittelu, joka mahdollistaa sivuston näyttämisen optimaalisesti eri laitteilla ja näytöillä. Responsiivinen suunnittelu on tärkeä osa saavutettavuutta, koska se varmistaa, että sivusto on helppokäyttöinen kaikille käyttäjille.

4. **Visuaalinen suunnittelu**: CSS:llä voidaan toteuttaa visuaalisia elementtejä, kuten painikkeita, linkejä ja valikkoja, jotka ovat helppokäyttöisiä ja ymmärrettäviä kaikille käyttäjille. On tärkeää varmistaa, että visuaaliset elementit ovat selkeitä ja helppokäyttöisiä kaikille käyttäjille.

## JavaScriptin rooli saavutettavuudessa

JavaScript on tehokas ohjelmointikieli, jota käytetään usein interaktiivisten verkkosivujen toteuttamiseen. Se voi parantaa sivuston käyttäjäkokemusta ja saavutettavuutta monin tavoin, mutta se voi myös aiheuttaa esteitä, jos sitä käytetään väärin.

**Parantaa saavutettavuutta:** JavaScriptin avulla voidaan lisätä interaktiivisuutta ja toiminnallisuutta, mikä parantaa käyttökokemusta. Esimerkiksi, jotkut käyttäjät luottavat näppäimistöön navigoidessaan webissä. Tällöin on tärkeää, että on olemassa indikaattori, joka auttaa tunnistamaan tarkalleen, missä käyttäjät ovat verkkosivulla, aivan kuten hiiren osoitin.

**Heikentää saavutettavuutta:** Jos JavaScriptiä käytetään väärin, se voi merkittävästi vahingoittaa saavutettavuutta. Esimerkiksi, käyttöliittymäkomponentit tarvitsevat roolin, nimen ja joskus arvon, jotta avustavien teknologioiden käyttäjät voivat käyttää niitä.

Tässä on joitakin tapoja, joilla JavaScript voi parantaa saavutettavuutta:

1. **Näppäimistön saavutettavuus:** JavaScriptiä voidaan käyttää parantamaan näppäimistön saavutettavuutta. Esimerkiksi, voit luoda modaalidialogin, joka avautuu, kun käyttäjä painaa tiettyä painiketta. Tämä on erityisen tärkeää, koska monet käyttäjät luottavat näppäimistöön navigoidessaan webissä.

```html
<button id=”openModalButton”>Open Modal</button>
<div id=”modal” role=”dialog” aria-labelledby=”modalTitle”>
  <h2 id=”modalTitle”>Modal Dialog</h2>
  ...
</div>
```

2. **ARIA (Accessible Rich Internet Applications):** ARIA:n avulla voit tehdä monimutkaisia käyttöliittymäkomponentteja saavutettaviksi. Esimerkiksi, voit luoda välilehtirajapinnan, jossa
jokaisella välilehdellä on rooli, joka määrittää sen toiminnallisuuden.

```html
<div role="tablist">
  <button role="tab" id="tab1" aria-controls="panel1" aria-selected="true">Tab 1</button>
  ...
</div>
```

3. **Focuksen hallinta:** JavaScriptiä voidaan käyttää keskityksen hallintaan, joka on erityisen tärkeää näppäimistöllä navigoiville käyttäjille. Esimerkiksi, kun modaalidialogi avataan, focus voidaan siirtää dialogiin ja estää käyttäjää vuorovaikuttamasta muun sivun kanssa, kunnes dialogi suljetaan.

## Linkkejä

[CSS and JavaScript accessibility best practices](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/CSS_and_JavaScript)

[Web Accessibility in JavaScript: Designing for All Users](https://blog.carlosrojas.dev/web-accessibility-in-javascript-designing-for-all-users-2a838743a5b6)

[Writing JavaScript with accessibility in mind](https://medium.com/@matuzo/writing-javascript-with-accessibility-in-mind-a1f6a5f467b9)
