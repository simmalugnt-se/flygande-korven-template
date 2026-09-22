# Flygande Korven

En första övning i semantisk HTML, lokal utveckling och ett enkelt Git-flöde.

Du får menytexten, restaurangens logotyp och en tom CSS-fil. Din uppgift är att
göra om den rena texten till en strukturerad webbsida med HTML.

## Innan du börjar

Du behöver ha följande på datorn:

- Visual Studio Code;
- Google Chrome;
- [GitHub Desktop](https://desktop.github.com/);
- ett GitHub-konto som du kan logga in på.

Du behöver inte använda terminalen i den här övningen. Vi gör hela arbetsflödet
i GitHub, GitHub Desktop och VS Code.

GitHub Desktop har det Git-stöd som behövs för övningen. Du behöver inte
installera Git separat eller skriva några Git-kommandon i terminalen.

## 1. Skapa ditt eget repository

1. Klicka på **Use this template** ovanför fillistan på GitHub.
2. Välj **Create a new repository**.
3. Döp repositoryt till exempelvis `fornamn-efternamn-flygande-korven`.
4. Skapa repositoryt på ditt eget GitHub-konto.

Alla i klassen börjar då med samma material men arbetar i separata repositories.

## 2. Förbered GitHub Desktop

### Logga in

1. Öppna GitHub Desktop.
2. Logga in med GitHub-kontot som du nyss skapade.
3. Följ anvisningarna i webbläsaren och gå sedan tillbaka till GitHub Desktop.

### Kontrollera namn och e-postadress

Git använder namn och e-postadress för att visa vem som har skapat en commit.

1. På Mac: välj **GitHub Desktop → Settings** i menyraden. På Windows: välj
   **File → Options**.
2. Välj **Git**.
3. Skriv ditt namn i fältet **Name**.
4. Välj en e-postadress som hör till ditt GitHub-konto i listan **Email**.
5. Klicka på **Save**.

## 3. Hämta projektet med GitHub Desktop

Att klona betyder att du hämtar GitHub-projektet till din dator så att du kan
arbeta med filerna i VS Code.

1. Välj **File → Clone Repository** i GitHub Desktop.
2. Välj fliken **GitHub.com**.
3. Leta upp repositoryt som du skapade från kursens template.
4. Välj en plats på datorn där projektmappen ska sparas, exempelvis Dokument.
5. Klicka på **Clone**.
6. Klicka på **Open in Visual Studio Code** när projektet har hämtats.
7. Om frågan **Do you trust the authors of the files in this folder?** visas,
    välj att lita på projektet. Det är ditt eget repository från kursens template.

Om knappen för VS Code inte visas: öppna GitHub Desktops inställningar, välj
**Integrations** och välj Visual Studio Code som **External editor**.

Öppna **Explorer** längst upp i vänsterspalten. Där ska du nu se `README.md`,
`menu.txt`, `index.html`, `style.css` och mappen `assets`.

## 4. Uppgiften

Utgå från innehållet i [`menu.txt`](menu.txt) och bygg sidan i
[`index.html`](index.html).

- Använd semantiska HTML-element där de passar.
- Skapa en logisk rubrikstruktur.
- Presentera menyn som en lista eller en beskrivningslista.
- Märk upp telefonnummer, öppettider och kontaktuppgifter tydligt.
- Lägg till logotypen från `assets/flygande-korven-logo.png` med en användbar
  alternativtext.
- Ändra inte `menu.txt`; den är ert textunderlag.

CSS-filen är redan kopplad till HTML-dokumentet men är tom från början. När vi
kommer till CSS-momentet fortsätter du att arbeta i samma projekt.

## 5. Kör sidan i Chrome

Live Server startar en liten lokal webbserver på din dator. Den gör att du kan
se sidan i webbläsaren och uppdaterar den när du sparar.

### Installera Live Server

Det här behöver bara göras första gången du använder VS Code.

1. Klicka på **Extensions** i vänsterspalten. Ikonen ser ut som fyra rutor.
2. Sök efter `Live Server`.
3. Välj **Live Server** av **Ritwick Dey**.
4. Klicka på **Install**.

### Öppna sidan

1. Klicka på **Explorer** längst upp i vänsterspalten.
2. Klicka på `index.html` så att filen öppnas i editorn.
3. Klicka på **Go Live** längst ner till höger i VS Codes statusrad.
4. En webbläsare öppnas med en adress som börjar med `http://127.0.0.1` eller
   `http://localhost`.
5. Om sidan öppnas i en annan webbläsare kan du kopiera adressen och öppna den i
   Chrome.

Om **Go Live** inte syns kan du högerklicka på `index.html` i Explorer och välja
**Open with Live Server**.

### Prova att ändra sidan

1. Gör en liten ändring i `index.html`.
2. Spara med **Cmd + S** på Mac eller **Ctrl + S** på Windows.
3. Gå tillbaka till Chrome. Sidan ska laddas om automatiskt.

Låt Live Server vara igång medan du arbetar. Klicka på portnumret längst ner i
VS Code när du vill stänga servern.

## 6. Spara en version med GitHub Desktop

När sidan har fått sin första struktur ska du spara en version, en så kallad
commit. Det gör du i GitHub Desktop.

1. Spara `index.html`.
2. Gå till GitHub Desktop.
3. Till vänster ser du filerna som har ändrats. Kontrollera att `index.html` är
   markerad.
4. Klicka på `index.html` för att granska skillnaden mellan den gamla och den nya
   versionen.
5. Skriv `Märker upp korvmenyn` i fältet **Summary**.
6. Klicka på **Commit to main**.
7. Klicka på **Push origin** för att skicka din commit till GitHub.

Kontrollera därefter på GitHub att din commit och din uppdaterade HTML-fil finns
i ditt eget repository.

## Klart när

- sidan går att öppna med Live Server;
- allt innehåll från `menu.txt` finns med;
- rubriker och sektioner har en begriplig struktur;
- logotypen visas och har alternativtext;
- HTML-dokumentet har sparats i en commit och pushats till GitHub.
