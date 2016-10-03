# Analyseer

Bekijk de volledige commit-geschiedenis om te bestuderen hoe dit project tot stand gekomen is.

Probeer volgende vragen te beantwoorden:

i.v.m. MSTest:

- Welke Assert-methods worden naast `Assert.AreEqual` nog allemaal gebruikt?
 > Assert.IsTrue & Assert.IsFalse.
- Waarom heeft `TestDirectories` een `Initialize`- en `CleanUp`-method?
> Om te checken of de directory verwijderd is en of ze gecleant is.
- Zijn de attributen `[TestMethod]`, `[TestClass]`, ... noodzakelijk? (Test uit!)
> neen, als ik ze als commentaar erbij zet werkt de rest nog altijd.
- Wat is de shortcut om alle tests uit te voeren in VS?
>  CTRL R, CTRl A

i.v.m. Files en Directories:

- Wat is het voordeel van `Path.Combine` i.v.m. strings aan elkaar plakken?
> je combineert 2 paths.
- Wordt de return-waarde van `Directory.CreateDirectory(...)` steeds opgevangen? (TIP: gebruik `CTRL-SHIFT-F`)
>  ja
- Wat is de return-waarde van `Directory.CreateDirectory(...)`?
> 
- Wanneer is het nuttig om de return-waarde van `Directory.CreateDirectory(...)` op te vangen?

i.v.m. duidelijkheid/geschiedenis van de code:

- Lukken de testen in de commit 3ffe2c86? Waarom (niet)?
- Wat lost commit d0320b6a op?
- Wat is het probleem met de files in commit 9d184949?
- Wat doet commit 9b3e4065? Maakt dit de code makkelijker leesbaar? Makkelijker uitbreidbaar?


