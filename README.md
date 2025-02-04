![ts bootcamp](./ts_bootcamp.png)
# 🚀 TypeScript Bootcamp 🚀

## 🧩 1a Skapa ett nytt npm-projekt. 
Installera TypeScript med npm typescript . Skapa konfigurationsfil med tsc --init . Du ska kunna skriva package.json-skript som kör "tsc" i terminalen.
Målet är att kunna omvandla en TypeScript-fil till vanlig JavaScript.

## 🧩 1b Skapa en config-fil för TypeScript. 
Ställ in outDir så att js-filer läggs i en mapp med namnet dist/. Skriv ett skript som kör tsc.
Tips: npm init -y, npm i -D typescript, npx tsc --init 

## 🧩 1c Skapa filen "src/script.ts" och gör ett skript som kör "dist/script.js". 
Skriv in:
let x: string = 42;
Vad händer? Ta reda på vad felmeddelandet betyder och lös det.

## 🧩 1d Deklarera variabler med olika datatyper
Skapa tre variabler av typen `string`, `number` och `boolean`. Tilldela dem lämpliga värden.

---

## 🧩 2. Skriv en funktion som summerar två tal
Skapa en funktion `sum` som tar två `number`-argument och returnerar deras summa.

---

## 🧩 3. Kontrollera om ett tal är udda eller jämnt
Skriv en funktion `isEven` som returnerar `true` om ett tal är jämnt och `false` om det är udda.

---

## 🧩 4. Typdeklarera en array
Skapa en variabel `numbers` av typen `number[]` och fyll den med minst tre tal.

---

## 🧩 5. Filtrera jämna tal från en array
Skriv en funktion `filterEvenNumbers` som tar en array av `number[]` och returnerar bara de jämna talen.

---

## 🧩 6. Hantera en unionstyp
Skapa en funktion `describeValue` som tar ett argument som kan vara antingen `string` eller `number` och returnerar en strängbeskrivning av värdet.

---

## 🧩 7. En enkel typalias
Skapa ett typalias `Person` som innehåller ett namn (`name: string`) och ålder (`age: number`). Skapa en variabel av den typen.

---

## 🧩 8. Objekt som funktionens argument
Skriv en funktion `printPersonInfo` som tar ett objekt av typen `Person` och skriver ut namn och ålder.

---

## 🧩 9. Enum-övning
Definiera en `enum` för veckodagar och skriv en funktion `isWeekend` som returnerar `true` för helgdagar.

---

## 🧩 10. Kontrollera längden på en sträng
Skriv en funktion `isLongString` som returnerar `true` om en sträng har mer än 10 tecken.

---

## 🧩 11. Sortera en array av tal
Skriv en funktion `sortNumbers` som tar en array av `number[]` och returnerar den sorterad i stigande ordning.

---

## 🧩 12. En enkel tuple
Skapa en tuple `coordinate` som innehåller två värden: latitud och longitud (`number` båda). Skriv ut värdena.

---

## 🧩 13. Typvakt med `typeof`
Skriv en funktion `isString` som returnerar `true` om argumentet är en sträng och `false` annars.

---

## 🧩 14. Omvandla array till sträng
Skriv en funktion `joinStrings` som tar en array av `string[]` och returnerar en enda sammanslagen sträng.

---

## 🧩 15. Defaultvärde i en funktion
Skapa en funktion `greet` som tar ett valfritt namn och returnerar `"Hello, Guest"` om inget namn ges.

---

## 🧩 16. Returnera en funktion
Skriv en funktion `createMultiplier` som tar ett tal som argument och returnerar en funktion som multiplicerar sina argument med det talet.

---

## 🧩 17. Hantera `null` och `undefined`
Skriv en funktion `printValue` som skriver ut värdet om det inte är `null` eller `undefined`. Skriv `"No value"` annars.

---

## 🧩 18. Skapa en enkel interface
Definiera ett `interface` för ett `Book`-objekt med `title`, `author` och `year`. Skapa ett objekt som följer interfacet.

---

## 🧩 19. Implementera logik med if/else
Skriv en funktion `gradeEvaluator` som returnerar `"Pass"` om betyget är minst 50 och `"Fail"` annars.

---

## 🧩 20. Rekursion: räkna ner
Skapa en funktion `countdown` som tar ett heltal och skriver ut en nedräkning till noll.

---

