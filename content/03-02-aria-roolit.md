# ARIA-roolit ja niiden käyttö

ARIA (Accessible Rich Internet Applications) määrittelee semantiikkaa, jota voidaan soveltaa elementteihin. Nämä on jaettu rooleihin, jotka määrittelevät tietyn tyyppisen käyttöliittymäelementin, sekä tiloihin ja ominaisuuksiin, jotka tukevat roolia.

ARIA-roolit tarjoavat semanttista merkitystä sisällölle, mahdollistaen ruudunlukuohjelmistojen ja muiden työkalujen esittää ja tukea vuorovaikutusta objektin kanssa tavalla, joka on yhdenmukainen käyttäjän odotusten kanssa. ARIA-rooleja voidaan käyttää kuvaamaan elementtejä, jotka eivät ole natiivisti olemassa HTML:ssä tai ovat olemassa, mutta eivät vielä ole täysin tuettuja selaimissa.

ARIA-roolit lisätään HTML-elementteihin käyttämällä `role="roolityyppi"`, missä roolityyppi on roolin nimi ARIA-spesifikaatiossa. Jotkut roolit vaativat liittyvien ARIA-tilojen tai -ominaisuuksien sisällyttämisen; toiset ovat voimassa vain yhdistettynä muihin rooleihin.

ARIA-rooleja tulisi käyttää, kun HTML ei ilmeisesti ilmaise elementin tai elementtiryhmän tarkoitusta[3]. On tärkeää muistaa, että ARIA:n ensimmäinen sääntö on: "Jos voit käyttää natiivia HTML-elementtiä tai -attribuuttia, jolla on jo tarvittavat semantiikka ja toiminta, sen sijaan, että uudelleenkäyttäisit elementtiä ja lisäisit ARIA-roolin, -tilan tai -ominaisuuden sen saavutettavuuden parantamiseksi, tee niin."[1].

[1]: https://www.w3.org/WAI/standards-guidelines/wcag/
[2]: https://www.w3.org/TR/wai-aria-1.1/
[3]: https://www.w3.org/TR/wai-aria-1.1/#usage_intro
