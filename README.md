# Flygande Korven

En första övning i semantisk HTML, lokal utveckling och ett enkelt Git-flöde.

Du får menytexten, restaurangens logotyp och en färdig CSS-fil. Din uppgift är
att göra om den rena texten till en strukturerad webbsida med HTML.

## 1. Skapa ditt eget repository

1. Klicka på **Use this template** ovanför fillistan på GitHub.
2. Välj **Create a new repository**.
3. Döp repositoryt till exempelvis `fornamn-efternamn-flygande-korven`.
4. Skapa repositoryt på ditt eget GitHub-konto.

Alla i klassen börjar då med samma material men arbetar i separata repositories.

## 2. Hämta projektet till VS Code

1. Öppna ditt nya repository på GitHub.
2. Klicka på **Code** och kopiera HTTPS-adressen.
3. Öppna kommandopaletten i VS Code.
4. Välj **Git: Clone**, klistra in adressen och välj var projektet ska sparas.
5. Öppna den klonade projektmappen i VS Code.

## 3. Uppgiften

Utgå från innehållet i [`menu.txt`](menu.txt) och bygg sidan i
[`index.html`](index.html).

- Använd semantiska HTML-element där de passar.
- Skapa en logisk rubrikstruktur.
- Presentera menyn som en lista eller en beskrivningslista.
- Märk upp telefonnummer, öppettider och kontaktuppgifter tydligt.
- Lägg till logotypen från `assets/flygande-korven-logo.png` med en användbar
  alternativtext.
- Ändra inte `menu.txt`; den är ert textunderlag.

CSS-filen är redan kopplad till HTML-dokumentet. Den använder huvudsakligen
elementselektorer, så sidan får mer form i takt med att innehållet märks upp.

## 4. Kör sidan i Chrome

Installera tillägget **Live Server** i VS Code om det inte redan finns.
Högerklicka sedan på `index.html` och välj **Open with Live Server**.

När du sparar filen laddas sidan om automatiskt i Chrome.

## 5. Spara en version med Git

När sidan har fått sin första struktur:

```bash
git status
git add index.html
git commit -m "Märker upp korvmenyn"
git push
```

Kontrollera därefter på GitHub att din commit och din uppdaterade HTML-fil finns
i ditt eget repository.

## Klart när

- sidan går att öppna med Live Server;
- allt innehåll från `menu.txt` finns med;
- rubriker och sektioner har en begriplig struktur;
- logotypen visas och har alternativtext;
- HTML-dokumentet har sparats i en commit och pushats till GitHub.
