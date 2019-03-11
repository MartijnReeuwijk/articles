#Css en animaties:
Met cascading style sheets (CSS) kan je veel doen waaronder animaties.
Css animaties kunnen gemaakt worden door het gebruik van keyframes en het gebruik van transities. Met keyframes kan je complexere animaties maken. Dit kan je doen door het gebruik van meerdere stappen in de animatie.

###Voorbeeld pulse
`css @keyframes pulse { 0%, 100% { font-size: 10px; } 50% { font-size: 12px; } }`
Zoals de code hierboven beschreven kan je animeren met drie stappen 0% -> 50% -> 100%.
Dit zorgt voor een een van 10px -> 12px -> 10px dit geeft het visueel effect van een pulse.
Aan deze animatie kunnen nog meer attributen toegevoegd worden zoals.
Animation-iteration-count: 10;Dit zorgt er voor dat de animatie 10x wordt gedaan / geanimeerd.

Je kan op deze manier van animeren ook meerdere soorten animaties op een element zetten door het als een attribuut mee te geven zoals hieronder.
###Voorbeeld meer animaties op een Class
`css .meer-animaties { animation: spin 2s infinite, jump 1s; }`

Op deze manier voeg je meerdere animaties toe aan een class, zo kan je snel met classes de juiste animaties toevoegen aan je elementen.

#Transitions
Je kan met Css ook transitions doen dit zijn meestal simpel en animaties deze kan je op bijvoorbeeld :hover, :active en :active met deze transitions kan je bijvoorbeeld de achtergrond kleur veranderen.

###Voorbeeld transition opzet
`css
div{
background: red;
transition: background 2s;
},
div:hover{
background: blue;
}

`
Zo verandert over de tijd van 2s de achtergrond van rood naar blauw.
transition: background 2s;
Deze transition kan je voor ieder eigenschappen van de css gebruiken zoals bijvoorbeeld, Width, height, color, background en opacity;

Zelf heb ik de transition en :hover gebruikt om een SVG te animeren wat kan leiden tot interactieve plaatjes.
