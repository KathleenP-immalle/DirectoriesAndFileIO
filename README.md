# Analyseer

Bekijk de volledige commit-geschiedenis om te bestuderen hoe dit project tot stand gekomen is.

Probeer volgende vragen te beantwoorden:

i.v.m. MSTest:

- Welke Assert-methods worden naast `Assert.AreEqual` nog allemaal gebruikt?

> Assert.False, Assert.Equals, Assert.True

- Waarom heeft `TestDirectories` een `Initialize`- en `CleanUp`-method?

> Om er zeker van te zijn dat de testfile verwijderd is en je volledig opnieuw kan beginnen.

- Zijn de attributen `[TestMethod]`, `[TestClass]`, ... noodzakelijk? (Test uit!)

> nee?

- Wat is de shortcut om alle tests uit te voeren in VS?

>Ctrl+R, A

i.v.m. Files en Directories:

- Wat is het voordeel van `Path.Combine` i.v.m. strings aan elkaar plakken?

> Het plaatst "\" tussen de delen.
 
- Wordt de return-waarde van `Directory.CreateDirectory(...)` steeds opgevangen? (TIP: gebruik `CTRL-SHIFT-F`)

- Wat is de return-waarde van `Directory.CreateDirectory(...)`?

> een string (path)

- Wanneer is het nuttig om de return-waarde van `Directory.CreateDirectory(...)` op te vangen?

i.v.m. duidelijkheid/geschiedenis van de code:

- Lukken de testen in de commit 3ffe2c86? Waarom (niet)?

>Nee, er is een fout in de Assert.AreEqual method.

- Wat lost commit d0320b6a op?

> Het draait de meegegeven strings in de Assert.AreEqual method om.

- Wat is het probleem met de files in commit 9d184949?
> 
- Wat doet commit 9b3e4065? Maakt dit de code makkelijker leesbaar? Makkelijker uitbreidbaar?
