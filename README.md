# Alloy Lab

Labben kommer best� av att s�tta upp ett CI/CD fl�de (Continious Integration/Continious Deployment) f�r en f�rdig applikation med moment som kr�ver PowerShell f�r drifts�ttningen.

I labben kommer vi att anv�nda Github f�r k�llkodshantering. En tj�nst som heter AppVeyor som Continious Integration server (byggserver) och Octopus Deploy f�r Continious Deployment server. Dessa program/tj�nster �r mycket vanliga ute p� f�retagen men det finns naturligtvis andra som g�r ungef�r samma sak. Koncepten �r dock desamma.

Din utmaning blir att l�sa ett antal steg i den automatiserade drifts�ttningsprocessen med PowerShell-skript.

## F�rberedelser
�ven om PowerShell idag �r open source och finns p� fler plattformar kommer vi uteslutande att arbeta med Windows under labbarna med PowerShell. 

1) Du beh�ver en VM med Windows 10 eller Windows Server 2016 (med GUI). Windows beh�ver inte vara aktiverat s� du borde klarar dig med en trial utan skarp licens. Vi kommer inte att jobba med virtualisering och skapa upp nya maskiner s� du kan beh�lla *nix som host om du vill p� labbdatorn. Labben g�r ut p� att automatisera installationen av en webbapplikation p� din labbdator.

2) Du beh�ver skapa ett konto p� Github om du inte redan har ett konto. Acceptera inbjudan till organisationen Nackademin-DEVOPS17 genom att klicka p� inbjudningsl�nken som du har f�tt i ett separat mejl. L�gg in ditt riktiga namn och bild i profilen p� Github.

3) Skapa ett trial konto p� Appveyor (14 day free trial)

4) Skapa ett trial konto p� Octopus Deploy Cloud. Skapa en instans av servern som heter t.ex. �Nackademin-FH�.
