# Saavutettavuuden parantaminen oikeiden HTML-elementtien käytöllä

HTML-elementtien oikea käyttö on keskeinen osa verkkosivustojen saavutettavuuden parantamista. Tässä on joitakin tapoja, joilla HTML-elementtien käyttö voi parantaa saavutettavuutta:

1. **Semanttinen HTML**: Semanttisen HTML:n käyttö tarkoittaa oikeiden HTML-elementtien käyttämistä niiden tarkoitetulla tavalla mahdollisimman paljon. Esimerkiksi, jos tarvitset painiketta, käytä `<button>`-elementtiä (eikä `<div>`-elementtiä). Semanttiset elementit ovat elementtejä, joilla on merkitys.

2. **Otsikot**: Hakukoneet käyttävät otsikoita indeksoidakseen sivuston rakenteen ja sisällön. Käyttäjät silmäilevät sivuja otsikoiden perusteella. On tärkeää käyttää otsikoita näyttämään dokumentin rakenne ja eri osioiden väliset suhteet.

3. **Alt-tekstit**: Alt-attribuutti tarjoaa vaihtoehtoisen tekstin kuvan tilalle, jos käyttäjä ei jostain syystä voi nähdä sitä (esimerkiksi hitaan yhteyden, virheen `src`-attribuutissa tai jos käyttäjä käyttää näytönlukuohjelmaa).

4. **HTML:n `lang`-attribuutti**: Sinun tulisi aina sisällyttää `lang`-attribuutti `<html>`-tagiin, jotta voit ilmoittaa verkkosivun kielen. Tämä on tarkoitettu avustamaan hakukoneita ja selaimia.

5. **Selkeä kieli**: Käytä aina selkeää kieltä, joka on helppo ymmärtää. Yritä myös välttää merkkejä, joita ei voida lukea selkeästi näytönlukuohjelmalla.

[HTML: A good basis for accessibility - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
[HTML Accessibility - W3Schools](https://www.w3schools.com/html/html_accessibility.asp)