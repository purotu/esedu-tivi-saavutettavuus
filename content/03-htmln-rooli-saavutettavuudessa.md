# HTML:n rooli saavutettavuudessa

HTML (Hypertext Markup Language) on keskeinen tekijä verkkosivujen saavutettavuudessa. Tässä on joitakin tärkeitä seikkoja:

1. **Semanttinen HTML**: Semanttisen HTML:n käyttö on yksi tärkeimmistä tavoista parantaa sivuston saavutettavuutta[^1^][1]. Semanttinen HTML tarkoittaa oikeiden HTML-elementtien käyttämistä niiden tarkoitetulla tavalla. Esimerkiksi, käyttämällä `<button>` -elementtiä painikkeille, saamme joitakin saavutettavuusominaisuuksia ilmaiseksi, kuten näppäimistöllä navigoinnin[^1^][1].

Huono esimerkki:

```html
<div onclick="doSomething()">Click me</div>
```
Hyvä esimerkki:

```html
<button onclick="doSomething()">Click me</button>
```

```html
<a href="https://example.com">Click me</a>
```
taikka

2. **ARIA-roolit**: ARIA-roolit voidaan lisätä HTML-elementteihin tarjoamaan semanttista merkitystä sisällölle. Ne auttavat ruudunlukuohjelmistoja ja muita työkaluja esittämään ja tukemaan vuorovaikutusta objektin kanssa tavalla, joka on yhdenmukainen käyttäjän odotusten kanssa.

[Lue lisää ARIA-roolirn käytöstä](./03-02-aria-roolit.md)

3. **Saavutettavuuden parantaminen**: Monet verkkosisällöt voidaan tehdä saavutettaviksi vain varmistamalla, että oikeita HTML-elementtejä käytetään oikeaan tarkoitukseen kaikkina aikoina.

[Lue lisää oikeiden elementtien käytöstä](./03-03-oikeiden-html-elementtien-kaytto.md)

4. **HTML ja avustavat teknologiat**: HTML:n semanttiset elementit, kuten otsikot (`<h1>` - `<h6>`), linkit (`<a>`), kuvat (`<img>`), listat (`<ul>`, `<ol>`, `<li>`) ja muut, tarjoavat tärkeää tietoa avustaville teknologioille, kuten näytönlukuohjelmistoille.

5. **HTML:n rooli SEO:ssa**: Hakukoneet arvostavat semanttista HTML:ää, joten saavutettavuuden parantaminen HTML:n avulla voi myös parantaa sivustosi näkyvyyttä hakukoneissa.
