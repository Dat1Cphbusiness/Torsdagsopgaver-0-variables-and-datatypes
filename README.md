### Exercises with Variables and control structures

Velkommen til den første opgave-torsdag. 

Øvelserne skal afleveres inden dagen er omme. Man afleverer ved at indsætte et link til sit eget repository.
Et repository er som en mappe du har i skyen (GitHub) med din besvarelse i. Hver torsdag skal du starte med at lave et nyt repository til dagens besvarelse, og hver torsdag skal du aflevere linket til det nye repository.

Hvis du ikke allerede har en, skal du idag starte med at lave en GitHub konto og dernæst et repository til dagens aflevering (se Task 1). 

Det forventes at alle opgaver laves i Processing. 

Alle opgaverne skal laves individuelt, men I opfordres til at hjælpe hinanden.

For hver af øvelserne (Task 1 undtaget), skal du lave en ny sketch i processing og gemme den med navnet "Task" efterfulgt af tallet på opgaven skrevet med bogstaver, i.e. "TaskTwo".

## Task 1: 
Opret et github repository til at lægge dine øvelser i. 
- Lav en bruger på https://github.com
- Lav et nyt repository med en readme fil. 
- Installér Github Desktop og log ind -> https://desktop.github.com/  
- Vend tilbage til dit nye repository og klik på den grønne knap "Code" -> "Open with Github Desktop"
- I app'en er der nu et pop-up med titlen "Clone a repository". Vælg et local path, hvor den skal gemme filerne i dit repository. 
- Tryk "Clone". 
- Find mappen med dit repository på din maskine, som du lige har clonet. (Kan findes ved at trykke i toppen på Repository -> Show in explorer).
- Åben readme.md i din yndlings text editor og Tilføj dit navn og studiemail. 
- Gå ind i Github Desktop igen. Skriv et Summary og tryk "Commit to Master" og derefter tryk Push. 


Brug for hjælp til Github, kig her: 
https://docs.github.com/en/github/getting-started-with-github/create-a-repo 
https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/committing-and-reviewing-changes-to-your-project


## Task 2: Initialiseringer
I denne opgave skal du lave initialiseringer. En initialisering er en linje som består af en datatype efterfulgt af et variabelnavn med tildeling af en værdi.
- åbn koden som ligger i mappen TaskTwo. For hver linje du ser i koden, skal du ændre linjen så det bliver til en initialisering. Du skal selv finde på et passende navn datatype.

## Task 3: Erklæring
I denne opgave skal du erklære variable. En erklæring er en linje i koden hvor vi fortæller at der findes en variabel, men hvor vi ikke giver den nogen værdi.
 - 3.a start en ny Processing sketch og kald den Task3
 - 3.b I det globale scope, erklær en variabel af typen <code>String</code> med navnet <code>address</code>.
 - 3.c tilføj erklæring af en varibel som gemmer summen af to heltal. Find selv på passende navn og datatype
 - 3.d gør det samme med en variabel som gemmer resultatet af en division.
 - 3.e gør det samme med en variabel som gemmer en besked til brugeren.

## Task 4: Tildeling
I denne opgave skal du arbejde med at tilføje værdier til variable som er erklæret et andet sted i koden
 - 4.a tag fat i sketchen fra Task 3 og tilføj en setup metode.
 - 4.b I setup metoden, tildel værdier til de variable du har erklæret i det globale scope.
 - 4.c Med printLn kommandoen, udskriv alle variablene, med et label foran. Fx. sådan her for variablen address: <code>println("Adresse: "+address);</code>
 - 4.d Tildel helt nye værdier til variablene, og udskriv dem igen. Genbrug evt dine println kommandoer.
 - 4.e Tildel nye værdier til variablene, men som tilføjelser - dvs. uden at overskrive det der allerede er gemt i variablene. Udskriv dem igen. Genbrug evt dine println kommandoer.
 - 4.f Tæl alle de numeriske variable op med 1. Udskriv.
 - 4.g Tæl alle de numeriske variable op med 3. Udskriv.
 - 4.h Tæl alle de numeriske variable ned med 1. Udskriv.

## Task 5: Scope
In this assignment you will work on the sketch in the folder TaskFive.
- 5.a declare variable circleSize used in the setup method.
int circleSize;
- 5.b declare numberOfCircles variable used in both setup and draw method
- 5.c declare x and y variables used in the draw method
- 5.d initialize the two counter variables used in draw method, with the value 0.

## Task 6: Conditional assignement
We will continue working on the sketch in TaskFive. We will change the code to draw each row of circles in a different random color.
- 6.a  declare three int variables in the global scope, one for each of the color channels red, green and blue.
- 6.b in the setup method assign values to the three variables that combined represents the color white.
- 6.c in the draw method use conditional assignment to change the color variables but only if we are about to draw the first circle in a line.
<details>
  <summary>Hjælp</summary>
  <p>  
    Generate new random color if <code>counter == 0</code>, otherwise let it remain the same value.
  
<details>
  <summary>Mere hjælp</summary>
  <p>
    <code>
    red = counter==0 ? (int)random(255):red;  
</code>
</details>

</details>

