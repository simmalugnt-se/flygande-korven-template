# Flygande Korven

En första övning i semantisk HTML, lokal utveckling och ett enkelt Git-flöde.

Du får menytexten, restaurangens logotyp och en tom CSS-fil. Din uppgift är att
göra om den rena texten till en strukturerad webbsida med HTML.

## Innan du börjar

Du behöver ha följande på datorn:

- Visual Studio Code;
- Google Chrome;
- Git;
- ett GitHub-konto som du kan logga in på.

Du behöver inte använda terminalen i den här övningen. Vi gör hela arbetsflödet
i GitHub och VS Codes gränssnitt.

## 1. Skapa ditt eget repository

1. Klicka på **Use this template** ovanför fillistan på GitHub.
2. Välj **Create a new repository**.
3. Döp repositoryt till exempelvis `fornamn-efternamn-flygande-korven`.
4. Skapa repositoryt på ditt eget GitHub-konto.

Alla i klassen börjar då med samma material men arbetar i separata repositories.

## 2. Hämta projektet till VS Code

Att klona betyder att du hämtar GitHub-projektet till din dator så att du kan
arbeta med filerna i VS Code.

1. Öppna ditt nya repository på GitHub.
2. Klicka på den gröna knappen **Code**.
3. Kontrollera att fliken **Local** och alternativet **HTTPS** är valda.
4. Kopiera adressen som visas.
5. Öppna VS Code.
6. Klicka på **Source Control** i vänsterspalten. Ikonen ser ut som en förgrenad
   linje med cirklar.
7. Klicka på **Clone Repository**.
8. Klistra in HTTPS-adressen och tryck på Enter.
9. Välj en plats på datorn där projektmappen ska sparas, exempelvis Dokument.
10. Klicka på **Open** när VS Code frågar om du vill öppna projektet.
11. Om frågan **Do you trust the authors of the files in this folder?** visas,
    välj att lita på projektet. Det är ditt eget repository från kursens template.

Öppna **Explorer** längst upp i vänsterspalten. Där ska du nu se `README.md`,
`menu.txt`, `index.html`, `style.css` och mappen `assets`.

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

CSS-filen är redan kopplad till HTML-dokumentet men är tom från början. När vi
kommer till CSS-momentet fortsätter du att arbeta i samma projekt.

## 4. Kör sidan i Chrome

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

## 5. Spara en version med Git

När sidan har fått sin första struktur ska du spara en version, en så kallad
commit. Det gör du också i VS Codes gränssnitt.

1. Spara `index.html`.
2. Klicka på **Source Control** i vänsterspalten.
3. Under **Changes** ser du filerna som har ändrats. Klicka på `index.html` om du
   vill granska skillnaden mellan den gamla och den nya versionen.
4. För muspekaren över `index.html` under **Changes** och klicka på plustecknet.
   Filen flyttas till **Staged Changes**. Det betyder att den ska ingå i nästa
   sparade version.
5. Skriv `Märker upp korvmenyn` i fältet **Message**.
6. Klicka på **Commit**.
7. Klicka på **Sync Changes** för att skicka din commit till GitHub.
8. Om VS Code ber dig logga in på GitHub, följ länken och godkänn inloggningen i
   webbläsaren.

Kontrollera därefter på GitHub att din commit och din uppdaterade HTML-fil finns
i ditt eget repository.

Om VS Code visar ett fel om Git, `user.name` eller `user.email`: stanna där och
be om hjälp. Det är en engångsinställning och inte en del av själva HTML-övningen.

## Klart när

- sidan går att öppna med Live Server;
- allt innehåll från `menu.txt` finns med;
- rubriker och sektioner har en begriplig struktur;
- logotypen visas och har alternativtext;
- HTML-dokumentet har sparats i en commit och pushats till GitHub.
