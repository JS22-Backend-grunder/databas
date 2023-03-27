# Databas

## Övningar

#### NeDB

1. Skapa en mapp och i den mappen skapa en package.json med `npm init -y`.
2. Installera NeDB med `npm install nedb-promise`.
3. Skapa en index.js.
4. Skapa en ny databas som heter **database.db** och sedan följande:
    * Lägg in fem objekt, varje objekt ska ha egenskaperna **firstname**, **lastname**, **age**. Se till att minst två personer har efternamnet Svensson. Två åldrar ska vara under 30 resten över 30. `Använd insert() här`
    * Hämta alla personer med efternamnet Svensson från databasen.
    * Hämta ett valfritt förnamn.
    * Hämta alla personer som är över 30. Tips! Kolla in operatorer som `$gt` under `find` i dokumentationen.
    * Byt förnamn och ålder på ett av namnen.
    * Ta bort en valfri person från databasen (hela objektet).
    * Level up: Lägg till ett objekt med en array alltså `{ names: [] }` och pusha sedan in namn i den arrayen.

#### NeDB med API-övningar

Ändra om Sinus webshop och Todo API så de nu använder sig av NeDB för att spara och hämta data.

#### Login page

I övningen för **logga in / skapa konto** så lägg två API-endpoints där den ena är för att 
hämta en användares e-postadress. Det är enbart e-posten som ska returneras till frontend.

Den andra endpoint:en ska ta bort ett användarkonto.