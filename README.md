# HTML Checklist

## Bestanden
Zorg ervoor dat je HTML pagina index.html heet en geen andere naam! Plaats alle afbeeldingen netjes in een folder en noem die folder images! Zorg dat je maar één CSS bestand hebt! Alle CSS code gaat in dit CSS bestand en alle HTML code gaat in je HTML pagina.
  
Zorg dat je bestandsnamen alleen uit kleinletters (geen hoofdletters) bestaan, en dat er geen spaties of vreemde tekens in de bestandsnamen voorkomen (nummers 0 tot en met 9 en – of _ mogen wel). Dus niet "Speelgoed Auto.jpg" maar "speelgoed-auto.jpg"!

## Content in het midden
Plaats je content in het midden van je HTML pagina in een HTML element, b.v. main en geef deze een bepaalde "max-width" mee in de CSS code: ``max-width:600px;`` Gebruik vervolgens CSS properties zoals bijv.margin: 0 auto; om content netjes in het midden te plaatsen (zodat de content centraal in het midden staat, en niet zomaar van links naar rechts loopt, of tegen de linkerrand van je pagina "botst" :-)

#### In je HTML pagina:
```HTML
<main>
Hier de content van je pagina die je in het midden wilt
</main>
```
#### In je CSS bestand:
```CSS
main {
max-width: 600px;
margin: 0 auto;
}
```
## Verschaalbare afbeeldingen
Zorg ervoor dat foto's of afbeeldingen de lay-out van je pagina niet in de war gooien: laat afbeeldingen mee verschalen met je layout door het IMG element de volgende CSS eigenschap mee te geven in je CSS bestand: width:100%; height:auto;
   ```CSS
      IMG {
        width:100%;
        height:auto
      }
   ```
## Checken op foutjes
Gebruik de **W3C Validator plug-in** voor HTML en de **CSSTree validator** voor CSS om je code op fouten te checken! Let op! Staat er wel ``<!DOCTYPE html>`` bovenaan je code in de HTML pagina? Want anders doet de Validator plugin het niet.
  
## Netjes uitziende code
Zorg dat je code er niet als onleesbare gatenkaas uitziet: Gebruik de **Prettier** extensie om je code te formateren door in je VS Code settings Prettier als standaard formateerder in te stellen en Format On Save aan te zetten! Zie Tips & Trucks PDF over VS Code op Blackboard.
  
## Terminologie
Gebruik ook de benamingen die we tijdens de lessen gebruikt hebben en die in de powerpoints staan. HTML elementen, HTML attributen, wat is het verschil bijvoorbeeld tussen een CSS selector en een CSS property? Kun je aanwijzen welke CSS properties verantwoordelijk zijn voor de lay-out, kleur en typografie? (b.v. ik heb dit... gedaan omdat ik dat... effect wilde bereiken in mijn design)
