# BEM_exempel
Här finner ni en html-fil där jag först visar på några exempel på BEM som är felaktiga, och så jag såg hos flera av er under era presentationer. Om ni vill klara VG så får er BEM inte se ut som dessa felaktiga exempel. Därefter följer ett par exempel på hur korrekt BEM skall se ut :)

## Grundläggande regler BEM
- Dubbla understreck (ex header__menu) visar att vi har med ett element att göra. Ett element måste ALLTID innehålla det fullständiga namnet på blocket det ligger i. Du kan inte använda dubbla understreck om elementet i fråga inte ligger i ett block med samma namn som order före understrecken.
- Blocknamnet skall följa alla element inuti blocket, såvida du inte väljer att nästla ett nytt block inuti det ursprunliga blocket. Då får alla element i det nästlade blocket ärva namnet från det nästlade blocket istället.
- Du får aldrig bara använda en modifierklass på ett element. Du behöver ha både grundklassen OCH modifierklassen.
- En modifierklass markeras med dubbla bindestreck och kan användas både på block och på element (ex header--darker, eller header__menu--darker).
