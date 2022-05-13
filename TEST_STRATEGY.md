# TP ORGA SCRUM MASTER

## Stratégie de test

### Les différents types de test : 
Voici les différents types de test qui sont mis en place. 

#### Test unitaire 
Les tests unitaires vérifient le bon fonctionnement d'une partie précise du logiciel

##### Où ? 
- Ces tests se trouvent directement dans le code du logiciel correspondant (les tests du front sont dans le code du front...)

##### Quand ? 
- Avant de faire une pull request 
- Pendant la review de code 
- Pendant la CI/CD

##### Par qui ? 
- Le développeur du ticket
- Le reviewer de la PR


#### Test d'acceptance
Les tests d'acceptance vérifient que le système répond à ses exigences métier

##### Où ? 
- Ces tests sont définis dans le ticket correspondant 

##### Quand ? 
- Avant de faire une pull request 
- Pendant la review de code 
- Quand le ticket se trouve dans la colonne "A tester PO/QA"

##### Par qui ? 
- Le développeur du ticket
- Le reviewer de la PR
- Le PO et le QA

#### Test de charge (API)
Les tests de charge vérifient les comportements du système lorsqu'il est soumis à une charge élevée

##### Où ? 
- Sur Postman ou JMeter

##### Quand ? 
- A chaque release majeur de l'api 

##### Par qui ? 
- Le QA ou un développeur

#### Test d'acceptance
Les tests d'acceptance vérifient que le système répond à ses exigences métier

##### Où ? 
- Ces tests sont définis dans le ticket correspondant 

##### Quand ? 
- Avant de faire une pull request 
- Pendant la review de code 
- Quand le ticket se trouve dans la colonne "A tester PO/QA"

##### Par qui ? 
- Le développeur du ticket
- Le reviewer de la PR
- Le PO et le QA

#### Test de charge (API)
Les tests de charge vérifient les comportements du système lorsqu'il est soumis à une charge élevée

##### Où ? 
- Sur Postman ou JMeter

##### Quand ? 
- A chaque release majeur de l'api 

##### Par qui ? 
- Le QA ou un développeur


#### Monkey test (WEB ET MOBILE)
- Les monkey test vérifient les comportements du logiciel lors d'un comportement inhabituelle de l'utilisateur. 
- Le but de ces tests est de trouver des bugs auxquels on aurait pas pensé en testant l'application de manière répétée

##### Où ? 
- Sur les versions en production de l'application mobile et web 

##### Quand ? 
- A chaque release majeur du front de l'application web et mobile 

##### Par qui ? 
- L'équipe


