# KeyboardWarrior

kravlista
- hämta hem en lista med random ord
- om en bokstav skrivs fel ska den bli röd
- om en bokstav skrivs fel ska bokstäverna man skriver efter också bli röda till att man korrigerat det första felet
- om man skriver en bokstav rätt så ska bokstaven "highlightas" med förslagvis en ljusare färg
- välj en hur länge spelet ska pågå
- en användare ska kunna starta om spelet när som helst
- skapa kortkommando för att start om spelet (tab + enter)

Highscores
- ta bort alla highscores
- presentera alla highscores
- presentera alla highscores för den inloggade användare

score
- se antalet ord per minut
- se hur träffsäker man är i procent
- lagra highscores i databas

användare
- registrera sig
- logga in



// "http": {
      "commandName": "Project",
      "dotnetRunMessages": true,
      "launchBrowser": true,
      "launchUrl": "swagger",
      "applicationUrl": "http://localhost:5183",
      "environmentVariables": {
        "ASPNETCORE_ENVIRONMENT": "Development"
      }
    },
    "https": {
      "commandName": "Project",
      "dotnetRunMessages": true,
      "launchBrowser": true,
      "launchUrl": "swagger",
      "applicationUrl": "https://localhost:7220;http://localhost:5183",
      "environmentVariables": {
        "ASPNETCORE_ENVIRONMENT": "Development"
      }
    },