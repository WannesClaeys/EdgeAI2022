# Documentatie

|||
| ----------- | ----------- |
| Studenten | Luca van Laer, Tamm Birk, Quie David, Wannes Claeys, Mano Mares |
| Docenten | Hassan Haddouchi & Geer Vanhulle |
| Periode | semester 1 van academiejaar 2022/23 |

## Inleiding

AI (Artificiële Intelligentie) en ML (Machine Learning) nemen een steeds prominentere plaats in binnen de IT wereld. Door velen worden deze technologieën gezien als de toekomst. Veel processen kunnen geautomatiseerd, versneld of op andere manieren verbeterd worden met deze technologieën. Dit resulteert in een grote vraag naar implementaties en veel onderzoek. De projecten waarin AI of ML gebruikt word, worden dan ook steeds groter en complexer.

Complexere algoritmes vragen om meer en betere rekenkracht van de machines die ze draaien. Om dit proces te versnellen word er dan ook constant onderzoek gedaan naar nieuwe hardware. Deze nieuwe hardware moet specifiek de noden van de AI en ML wereld invullen, en zo ruimte geven aan de evolutie die nu bezig is binnen de IT.

Eén van de resultaten die gekomen is uit dit onderzoek, is de TPU (Tensor Processing Unit). TPU is een chip die specifiek bedoeld is om ML algoritmes te verwerken. Door een ML algoritme op een TPU te draaien in plaats van een CPU of GPU kan men enorm veel tijd winnen. Toch neemt dit niet weg dat er ruimte is voor verbetering.

Verschillende schaling problemen lost men binnen de IT op door clusters op te zetten. Deze clusters bestaan uit hardware dat in een bepaalde architectuur opgesteld word, en met speciale software aangestuurd word. Afhankelijk van de gekozen architectuur (en bijhorende software) verkrijgt men verschillende soorten clusters. Eén soort cluster is de Beowulf cluster.

De Beowulf cluster word gebruikt om de rekenkracht van verschillende identieke computers parallel aan elkaar te gebruiken. Op deze manier kan men zware algoritmes sneller en makkelijker uitvoeren.

Binnen dit project willen we een Beowulf-cluster opstellen van identieke TPU's. Door TPU's in Beowulf-cluster architectuur te schakelen, zouden we zeer complexe en zware ML algoritmes snel moeten kunnen uitvoeren.

In dit project onderzoeken we of het mogelijk is om een Beowulf-cluster op te stellen van TPU's, meer bepaald coral dev boards. Online is er weinig tot niets terug te vinden over reeds gemaakte clusters van TPU's. Alleen bij Google is er sprake van een TPU cluster, onder de naam "pods". Het is weliswaar onduidelijk in de beschikbare documentatie welk type cluster dit precies is. Wel lijkt het er sterk op dat dit geen Beowulf cluster is.