# too_short
The too_short in time project for IoT

Vous êtes dans un aéroport et vous vous baladez dans les boutiques pendant votre escale.

![Airport](geoloc.png)

Bien sûr l'aéroport est "gavé" de bornes wifi mais il est aussi compartimenté en zones
de sécurités. 

* Qui dit zones de sécurité dit portiques et qui dit portiques dit files d'attente.

Le problème qui se pose est le suivant : compte tenu de votre position actuelle dans l'aéroport
aurez vous le temps de rejoindre votre porte d'embarquement ?

La réponse n'est pas forcément oui ou non, ca peut être plus nuancé du vert au rouge ?

L'objet porté par le voyageur doit collaborer avec un service de l'aéroport permettant d'acceder 
aux horaires des vols et aux objets mesurant le temps d'attente aux
portiques.

Il doit aussi participer à géolocalisation grâce à la triangulation
Wifi ou à un module GPS :

https://www.instructables.com/ESP32-GPS-Tracker-With-an-OLED-Display/

https://www.google.com/search?client=ubuntu&channel=fs&ei=BycUYM-XKsysa5nKkOgG&q=triangulation+wifi+esp32&oq=triangulation+wifi+esp32&gs_lcp=CgZwc3ktYWIQAzIGCAAQCBAeOgQIABBHOgQIABANOgYIABAHEB46CAgAEAgQBxAeOgoIABAIEAcQChAeUIEwWJxCYIBGaABwAngAgAFpiAHuCJIBBDEzLjGYAQCgAQGqAQdnd3Mtd2l6yAEFwAEB&sclient=psy-ab&ved=0ahUKEwiPt7SEuMHuAhVM1hoKHRklBG0Q4dUDCAw&uact=5

Cet objet pourrait aussi indiquer le chemin "le plus court" pour atteindre la porte d'embarquement.

C'est un projet complexe ... mais pas mal de choses existent et/ou
pourraient être tester.

Je préfère qu'une partie soit bien traitée
(dans son contexte) plutôt que d'obtenir un truc sans forme !

* Donc plutôt séquentialiser le traitement des sujets.


<!--- 
Un gros travail préalable sera de le SIMPLIFIER pour essayer de garder l'esprit 
IOT du sujet SANS se perdre dans des tâches non maîtrisèes.
just --->

Thématiques  : 
* Gestion multiple AP Wifi
* Triangulation
* Modélisation (i.e graphe : noeud + arc)
* ...
