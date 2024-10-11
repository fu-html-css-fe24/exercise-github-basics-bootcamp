# Github Basics Bootcamp

I denna övning kommer ni att få träna på de mest grundläggande sakerna som vi kommer att använda Github till i denna kurs. Ju längre fram i utbildningen vi kommer, så kommer vi också att fördjupa våra kunskaper, men än så länge räcker de grunder ni kommer få praktisera i denna bootcamp.

## Steg 1 - Skapa ett repo på Github

1. För att skapa ditt repo så behöver du först logga in på ditt Github-konto, ta dig till "Repositories", och klicka på "Add new". 
2. Namnge ditt repo till någonting rimligt (Inga mellanslag! Istället använder vi oss av camelCase eller snake-case för att tydliggöra orden i namnet).
3. Välj om ditt repo skall vara "public" (alla kommer kunna se ditt innehåll) eller "private" (ingen kommer kunna se ditt innehåll).
4. Bocka i att du vill ha en README-fil.

## Steg 2 - Initiera ett lokalt repo på din dator

1. Skapa upp en ny mapp på din dator där du kommer kunna lägga in alla dina skolprojekt. Vill du skapa eventuella undermappar för varje kurs så går det alldele utmärkt.
2. Högerklicka på din skolprojektsmapp och öppna upp terminalen i den mappen (dubbelkolla adressen i terminalen så att du verkligen hamnade rätt).
3. I terminalen kör du nu kommandot ```git init```

## Steg 3 - Klona hem ditt remote repo lokalt till din dator

1. Gå tillbaks till ditt repo på Github. Klicka på den gröna knappen där det står "Code" och kopera https-adressen (SSH går ochså bra om du har konfigurerat för detta).
2. Gå till din skolprojektsmapp, och öppna terminalen i den eventuella undermapp där du önskar att lägga ditt repo.
3. I terminalen kör du kommandot ```git clone <din-repo-url>```.

## Steg 4 - Gör en ändring lokalt på din dator

1. Stanna kvar i terminalen, men hoppa in i ditt hämtade repo genom att köra kommandot ```cd <ditt-repo-namn>```.
2. När du i terminalen bekräftat att du hoppat in i önskad mapp kör du kommandot ```code .``` (notera att det är ett mellanslag före punkten). Detta kommer öppna upp ditt repo i VSCode.
3. Gå in i din README-fil och skriv någonting kul. Spara.
4. Gå tillbaks tll terminalen och kör kommandot ```git status``` (viktigt att terminalen står i din repo-mapp). Om allt lyckats bör du nu se vilken/vilka filer i ditt repo som ändrats.

## Steg 5 - Stagea, Committa och Pusha dina ändringar till Github

1. Se till så att du står i din repo-mapp i terminalen.
2. Kör först kommandot ```git add .``` (notera att det är ett mellanslag innan punkten. Punkten indikerar att vi vill stagea ALLA ändringar som gjort. Vill du bara stagea en enstaka ändring så ersätter du punkten med den filens namn).
3. För att committa så kör du kommandot ```git commit -m "<ditt-commit--meddelande>"``` (glöm för guds skull inte den senare delen med "-m osv...", isåfall hamnar du i en fruktansvärd editor där det nästan inte går ta sig ut).
4. Kontrollera om din ändrig syns på Github

## Steg 6 - Hantera konflikter

1. Gör en ändring i din README-fil lokalt på VSCode. Spara, stagea och committa. PUSHA INTE!
2. Gå till din README-fil på Github och gör en ändring eller lägg till någonting.


<details>
  <summary>Klicka här för att visa de kommandon som ni bör lära er</summary>

</details>
