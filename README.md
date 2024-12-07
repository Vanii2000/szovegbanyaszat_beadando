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
