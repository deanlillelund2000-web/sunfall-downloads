# Sunfall

Et fantasy-eventyr med en vedvarende verden og co-op for op til fire spillere.

**[Download Sunfall til Windows](https://github.com/deanlillelund2000-web/sunfall-downloads/releases/latest/download/Sunfall-Setup.exe)**

## Installér én gang

1. Hent **Sunfall-Setup.exe** og tryk **Install**.
2. Åbn **Sunfall** fra skrivebordet eller Start-menuen.
3. Tryk **Update**, når en ny udgave er klar. Spillet henter og installerer den automatisk.
4. Tryk **Play**.

Du behøver ingen GitHub-konto, Unreal Editor eller udviklerværktøjer. Åbn Sunfall igen efter en spilsession for at finde nye opdateringer. Play bliver tilgængelig, når opdateringen er færdig.

## Spil med en ven

Co-op bruger foreløbig en direkte forbindelse. Tailscale kan forbinde to hjem:

1. Begge installerer [Tailscale](https://tailscale.com/download/windows) og logger ind med hver sin konto.
2. Værten [deler sin PC](https://tailscale.com/docs/features/sharing) med vennen, som accepterer invitationen.
3. Begge opdaterer Sunfall. Værten vælger **HOST CO-OP**.
4. Vennen vælger **JOIN FRIEND** og skriver værtens Tailscale-adresse efterfulgt af **:7777**.
5. Tillad Sunfall i Windows Firewall, hvis Windows spørger.

Værten gemmer verden og gruppens helte. Brug samme vært og profil næste gang. Værten skal være i spillet. Der er permadeath.

## Undervejs

**ESC** åbner spilmenuen. **J** viser quests, **M** åbner kortet, **E** interagerer og høster, og **I** åbner tasken. **ESC → Bug Report** gemmer en lokal rapport, som du selv kan sende til Dean.

Saves ligger separat i `%LOCALAPPDATA%\Sunfall\Saved\SaveGames`. Normal opdatering og afinstallation bevarer dem.

Dette er en Windows-testudgave. Installeren er endnu ikke digitalt signeret. Steam-invitationer og Steam-udgivelse er endnu ikke aktiveret. Forbindelsen mellem to forskellige hjem skal afprøves af spillerne.
