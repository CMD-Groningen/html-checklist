PDF versie [klik hier](https://cmd-groningen.github.io/html-checklist/html-checklist.pdf)    

# HTML Checklist

## ✅ Bestanden

Zorg ervoor dat je HTML pagina 📄 **index.html** heet en geen andere naam! Plaats alle afbeeldingen netjes in een folder en noem die folder 📁 **images**! Je mag maar één CSS bestand gebruiken! Alle CSS code gaat in dit CSS bestand en alle HTML code gaat in je HTML pagina. Plaats dus geen CSS code in je HTML! Alleen in het CSS bestand!

Zorg dat je bestandsnamen alleen uit kleinletters (geen hoofdletters) bestaan, en dat er geen spaties of vreemde tekens in de bestandsnamen voorkomen (nummers ``0`` tot en met ``9`` en `–` of ``_`` mogen wel). Dus niet **"Speelgoed Auto.jpg"** maar **"speelgoed-auto.jpg"**! Dit is om te voorkomen dat verwijzingen en links naar bestanden ineens niet meer werken als je website wordt geupload naar UNIX servers.

## ✅ Content in het midden

Plaats content die je in het midden wilt van je HTML pagina in een HTML element, b.v. ``<main>`` en geef deze in je CSS bestand een bepaalde "max-width" mee in de CSS code, bijvoorbeeld: ``max-width:800px;`` Gebruik vervolgens CSS properties zoals bijvoorbeeld ``margin: 0 auto;`` om die container netjes in het midden te plaatsen (zodat de content centraal in het midden staat, en niet zomaar van links naar rechts loopt, of tegen de randen van je pagina "botst" :-)

#### In je HTML pagina:
```HTML
<main>
Hier de content van je pagina die je in het midden wilt
</main>
```
#### In je CSS bestand:
```CSS
main {
max-width: 600px; // hangt van je voorkeur af, kan ook bv 800px zijn
margin: 0 auto;
}
```

## ✅ Verschaalbare afbeeldingen

Zorg ervoor dat foto's of afbeeldingen de lay-out van je pagina niet in de war gooien: laat afbeeldingen mee verschalen met je layout door het IMG element de volgende CSS properties mee te geven in je CSS bestand: 

```CSS
   IMG {
     width:100%;
     height:auto
   }
```

## ✅ Checken op foutjes

Gebruik de **W3C Validator plug-in** voor HTML en de **CSSTree validator** voor CSS om je code op fouten te checken! Let op! Staat er wel ``<!DOCTYPE html>`` bovenaan je code in de HTML pagina? Want anders doet de Validator plugin het niet. Check ook je CSS bestand op fouten door de **CSSTree Validator** plugin dat automatisch voor je te laten doen.

## ✅ Netjes inspringende code

Zorg dat je code er niet als onleesbare gatenkaas uitziet: Gebruik de **Prettier** extensie in VS Code, om je code automatisch te formateren door het volgende te doen:

- Rechtsklik in je HTML pegina, je krijgt dan een uitklapmenu
- Kies daar voor "Format Document with..."
- Je krijgt dan de keuze (uitklapmenu) bovenin voor "Configure default formatter"
- Kies daar voor "Prettier" ("HTML Language Features" mag ook, ingeval van HTML)
- Doe bovenstaande stappen ook voor je CSS bestand
- Daarnaast: zet "Format On Save" aan in je VS Code Settings! Zie **VSCode editor tips en truuks** op Brightspace bij DIO techniek.

## ✅ Omschrijvingen in je portfolio verslag

Gebruik ook de benamingen die we tijdens de lessen gebruikt hebben en die in de powerpoints staan als je uitleg geeft over de code die je hebt geschreven. Noem de content items in je HTML bestand ook **HTML elementen** en leg aan de hand van hun **HTML attributen** uit wat ze doen, wat is het verschil bijvoorbeeld tussen een CSS **selector** en een CSS **property**? Kun je aanwijzen welke CSS properties verantwoordelijk zijn voor de lay-out, kleur en typografie? (b.v. "*ik heb dit... gedaan omdat ik dat... effect wilde bereiken in mijn design*")

<!--
Hetzelfde geldt ook voor de uitleg over je **Microbit** bedenksel. Dus **niet**: *"ik heb een spel gemaakt waarbij twee lichtpuntjes met elkaar vechten en waarbij andere lichtpuntjes bijhouden bij wat er gebeurt"*

Dat moet zo: *"ik heb een spel bedacht waarbij een speler een object moet zien te ontwijken. Ook moet het aantal keren dat het object ontweken wordt worden bijgehouden. Vandaar dat er 3 **variabelen** nodig waren: de speler, het object en de bijgehouden score. Vervolgens heb ik een **if-else statement** gemaakt, dus een **conditional** waarin 3 condities gecheckt worden in een voortdurende **loop**, om te bepalen of het spel door moest gaan of stoppen"*
-->
-----

**David van den Bor**  
CMD Team

Docent Communicatie & Multimedia Design @ Hanzehogeschool Groningen  
d.b.p.van.den.bor@pl.hanze.nl

https://github.com/CMD-Groningen  
https://github.com/davidvandenbor
