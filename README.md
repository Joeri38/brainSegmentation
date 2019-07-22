# Brain segmentation

In deze repository staat de code voor een 3D U-net. Dit netwerk is beschreven in de volgende paper <a href="https://www.mdpi.com/2076-3417/9/3/404" target='_blank'>paper</a>. Deze paper komt met een implementatie op <a href="https://github.com/mrkolarik/3D-brain-segmentation" target='_blank'>git</a>. 

Tot nu toe maakt het programma de architectuur van het netwerk en laadt het de data in. De data zijn 60 beelden in de Train map en 14 beelden in de Test map. Deze zijn opgeslagen als .npy bestanden. Het netwerk dat ik nu gevonden heb is een binaire segmentatie machine, daarom laat ik alleen de masks van de grijze stof in. In mijn uiteindelijke programma zou ik ook masks van witte stof en csf moeten kunnen voorspellen. Het programma neemt al de rekenkracht van mijn computer op als ik het probeer te runnen en zorgt ervoor dat mijn computer vastloopt. 
