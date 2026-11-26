# spiekbriefje Git en Github

## 1. Clone, commit, push en pull
Met clone haal je voor het eerst een kopie van een remote repository van GitHub naar je eigen computer. Met commit leg je je lokale wijzigingen vast als een momentopname in je lokale Git-geschiedenis. Met push stuur je je gecommitte wijzigingen van je lokale computer naar de remote repository op GitHub. Met pull haal je nieuwe wijzigingen uit de remote repository op GitHub naar je lokale repository op je computer.

## 2. Een goed commitbericht

Goed voorbeeld: Spiekbrief: voorbeelden van goede en slechte commitberichten toegevoegd`
Slecht voorbeeld: Spiekbrief: fix of Spiekbrief: dingetjes aangepast
Waarom het goede voorbeeld beter is: Het geeft meteen duidelijk aan welk onderdeel is aangepast, zodat jij en anderen in de geschiedenis snel kunnen zien wat er is veranderd zonder eerst het hele bestand te moeten openen. Een vaag bericht zegt niets over de inhoud van de wijziging.

## 3. Gitignore

Een .gitignore-bestand zorgt ervoor dat Git opgegeven tijdelijke, systeem- of gegenereerde bestanden negeert en niet mee opneemt in commits of pushes.

## 4. Pull

Met een pull haalden we de nieuwste wijzigingen vanuit de remote repository op GitHub naar onze lokale map op de computer. Door aan het begin van elke les eerst te pullen voorkom je dat je werkt op een verouderde versie en verminder je de kans op merge-conflicten.

## 5. Terugdraaien

Bij het terugdraaien van een commit (zoals met git revert) wordt een foutieve commit niet uit de geschiedenis verwijderd, maar maakt Git een nieuwe commit aan die de wijzigingen van die commit ongedaan maakt. Zo blijft de volledige commitgeschiedenis behouden en duidelijk zichtbaar wat er is gebeurd, wat vooral belangrijk is wanneer er al is gepusht of met anderen wordt samengewerkt.