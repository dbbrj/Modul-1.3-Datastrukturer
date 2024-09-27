## 11 Arrays
# 11.3 Type af Indhold vs Type af Array
Hvad er sammenhængen mellem typen af et array og de data som det kan indeholde?
## 11.4 Størst i Array
Skriv et program, der finder det største tal i et array af typen int[], og udskriver indeks for dette tal. 
Find selv på noget passende indhold til dette array.
## 11.5 Erklæring af Størrelse
Hvilken syntaks bruges ved oprettelse af et array til at erklære hvor mange (data) elementer der skal være plads til?
## 11.7 Sudoku Plade
Hvordan ville du repræsentere en sudoku13 plade i Java?
Hvordan hænger denne datastruktur sammen i hukommelsen?
## 11.8 Areal af Cirkler
Skriv et program der udregner og udskriver arealet (π · r2) af tre forskellige cirkler med radius 1, 3, og 5.

**Bemærk:** Dette er en gentagelse af øvelse 10.4. 
I mellemtiden har vi dog fået nye (og bedre egnede) værktøjer til at løse den.
## 11.12 Kalender
Skriv et program, hvori
1. En variabel initialiseres til at være et array der indeholder antallet af dage i hver af de 12 måneder i et normalt år. 
   Det første element vil da indeholde antallet af dage i Januar. 
   * Hvad skal typen af denne variabel være?
2. En anden variabel initialiseres til at være et array der indeholder antallet af dage i hver af de 12 måneder i et skudår. 
   * Hvad skal typen af denne variabel være?
3. Gennemløb årene 2000 til 2020:
   * (a) Brug en ny variabel kaldet pointer til at pege på dét af de to arrays der er korrekt for det aktuelle år.
     * Hvad skal typen af denne variabel være? 
     * Hvor meget data bliver der kopieret her? 
     * **Hint:** Vi kan i denne opgave tillade os at forsimple skudårsreglerne til at det er skudår hvis 4 går op i årstallet. 
   * (b) For hvert år udskrives indholdet af det array som pointer peger på.
## 11.14 Sudoku Checker
Skriv et program, hvori 
*   En variabel initialiseres til at indeholde en udfyldt sudoku15 plade.
  * Hvordan skal vi repræsentere et felt der ikke er udfyldt? 
  * Hvad skal typen af denne variabel være? 
  * Hvordan erklæres den?
  * Hvordan kan vi initialisere den?
  * **Hint:** Find selv en udfyldt (aka: løst) sudoku plade online.

Skriv kode der vurderer om pladen representerer en korrekt løsning.
* **Hint 1:** Dette er tilfældet når alle følgende ting er sande:
  * Samtlige felter er udfyldte. 
  * Der er ingen række med to ens felter. Alternativt: Alle tallene 1-9 eksisterer i samtlige rækker. 
  * Der er ingen søjle med to ens felter. Alternativt: Alle tallene 1-9 eksisterer i samtlige søjler. 
  * Der er ingen 3x3 gruppe med to ens felter. Alternativt: Alle tallene 1-9 eksisterer i samtlige 3x3 grupper. 
* **Hint 2:** Hvis man skal undersøge om tallene 1-9 eksisterer kunne man jo oprette et boolean[9] array
    der repræsenterer om tallene er fundet, initialisere dette til kun at indeholde false værdier, gennemløbe alle tal 
    som er i et felt og sætte indekset med dette nummer (minus 1) til true. 
Er der nogen false værdier tilbage er der et manglende tal og sudokuen er ikke korrekt løst.

* Udskriv resultatet af denne vurdering.
  * Giver programmet også det korrekte resultat hvis man giver det en forkert udfyldt sudoku plade?

# 12 Struct
## 12.1 Person
I denne øvelse skal vi definere en struct som kan representere en person. 
Hvilke felter skal vi have? 
Det kunne være at personer i vores program har behov for at have et navn og en alder. 
Et navn kan gemmes i en string. 
Prøv at definere en sådan type og demonstrer at du kan bruge den.

# 13 Enum
## 13.1 Retning 
Definer en enum som repræsenterer en retning, der enten kan være nord, syd, øst eller vest.
Besvar følgende spørgsmål, skriv koden, og sørg for at den oversætter:
1. Hvad ville være et godt navn for denne enum?
2. Hvordan bør de forskellige værdier navngives?