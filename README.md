# Szövegbányászat beadandó
## Feladat leírása:
    1. Adatgyűjtés és előkészítés: Termékértékelési adatok letöltése egy nyílt adatforrásból (pl. Kaggle vagy Amazon API), és előfeldolgozás (szövegbeli zajok eltávolítása, tokenizálás stb.).

    2. Szöveg-feldolgozás:
        Szógyakoriság elemzése (word frequency) és szófelhő készítése a leggyakoribb szavakból.
        N-gramok készítése a gyakran együtt előforduló szókapcsolatok azonosítására.

    3. Szövegelemzés:
        Sentiment analysis: Polaritás (pozitív, negatív vagy semleges) meghatározása a szövegelemzés alapján.
        Témamodellezés (topic modeling): A leggyakoribb témák azonosítása a véleményekben LDA modellel.

    4. Vizualizáció:
        A sentiment elemzés és a témamodellezés eredményeinek vizualizálása, pl. grafikonokkal vagy interaktív dashboarddal (Power BI vagy Tableau használatával).

    5. Összegzés és ajánlások: A kapott eredmények alapján javaslatok megfogalmazása a termék vagy szolgáltatás fejlesztésére.
## Feladat felosztása:
  Tőke Vanessza: Adatgyűjtés és előkészítés, Szövegelemzés
  
  Szabó-Tóth Regina: Szöveg-feldolgozás, Vizualizáció

  Összegzés és ajánlások közösen

## Felhasznált adathalmaz
  Amazon értékeléseket tartalmazó adathalmazt választottunk a Kaggle oldalról. Két fájl állt rendelkezésünkre: egy tanuló és egy teszt halmaz.

  Mindkét csv fájl 3 oszlopot tartalmazott: 
  
    polarity - 1 a negatív és 2 a pozitív
    
    title - értékelés fejléce
    
    text - értékelés szövege
    

  Adathalmaz elérési link: https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews?resource=download
  
## Összegzés és ajánlások
A felhasznált adatbázis körülbelül 3.5 millió tanító és 1.5 teszt rekordot tartalmazott. Ezt mi technikai limitációk miatt lecsökkentettük 1 milló tanító és 150000 teszt adathalmazra a könnyebb kezelhetőség érdekében.
Az adathalmazon adattisztítást végeztünk (pl. tokenizálás, különleges karakterek eltávolítása stb.), majd további felhasználásra és elemzésre eltároltuk őket csv fájlokban.

A termékértékelések alapján a felhasználók 50.6%-a pozitívan értékelte a terméket, míg 49.4%-a negatívan. Ez az egyensúly azt jelzi, hogy a vásárlók véleménye megoszlik, és bár sokan elégedettek a termék vagy szolgáltatás teljesítményével, ugyanakkor számos kritikát is megfogalmaztak.

Mivel mindkét típusú visszajelzés jelen van, érdemes folyamatosan monitorozni a felhasználói véleményeket, hogy észrevegyük a jövőbeli trendeket, és ennek megfelelően alakítsuk a termék jellemzőit és a szolgáltatási folyamatokat.
