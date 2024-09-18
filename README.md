# Git-lathund
## Om du skapat ett projekt lokalt:

* **Steg 1:** Skapa ditt nya repo på github utan en readme. Spara url:en du ser när du klickar på den gröna 'clone'-knappen.

* **Steg 2:** Öppna ditt projekt i terminalen och stå i dess grundmapp där du ser projektets namn. Skriv sedan i följande i terminalen:
```git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <din-kopierade-url-här>
git push -u origin main
```

## Om du vill skapa ett projekt från Github:
* **Steg 1:** Skapa repot i Github med en readme. Du skapar en readme i första vyn bland checkboxarna där du skapar nya repon.
* **Steg 2:** Klona ner projektet genom att klicka på 'clone'-knappen och kopiera URL:en som kommer upp där.
* **Steg 3:** Gå till din terminal och ställ dig där du vill ha ditt nya projekt
* **Steg 4:** Skriv in ```git clone <din-kopierade-url-här>```
