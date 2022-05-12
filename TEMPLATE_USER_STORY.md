# TP ORGA SCRUM MASTER


## Comment rédiger une bonne US ?
Une user story doit contenir un titre composé en trois parties :

### Première partie : En tant que 
- La première partie de la user story fait référence au persona concerné. 
- Il est important de se demander pour qui développons-nous cette fonctionnalité ? Il faut également prendre en compte comment ce persona travaille, comment elle pense et ce qu'elle ressent. Le persona de Louise est différent de celui de Tom.

### Deuxième partie : Souhaite que
- Cette partie décrit l'intention du persona citée précédemment. Attention, ce ne sont pas les fonctionnalités. 
- Il faut l'objectif de l'utilisateur et non pas une composante de l'interface
- exemple : je souhaite me connecter et non pas je souhaite avoir un bouton pour me connecter

### Troisième partie : Afin de
- Cette partie décrit quel avantage global le persona essaie d'obtenir ? 
- Quel est le principal problème à résoudre ?

### Exemple d'une bonne user story 
- En tant que Timothée, je souhaite inviter mes amis afin de pouvoir partager les frais de location du véhicule.


## Composition d'un ticket sur Jira
Les tickets doivent être réalisé sur Jira. 

### Titre : User Story
- Le titre du ticket doit être la User Story 

### Contenu du ticket : Explication détaillé
- Le contenu du ticket doit essayer de détailler au mieux les actions à faire
- Si possible mettre des sources ou des pistes de travail (par exemple : ou peut on trouver telles ou telles informations, qui a potentiellement une solution au problème). 
- Si possible mettre des captures d'écrans

### Contenu du ticket : Tests d'acceptance
- Le rapporteur du ticket doit rédiger les tests permettant à celui qui le prend de savoir quand le ticket est fini. 
- Attention : S'il n'y a pas de tests d'acceptances, le développement du ticket **ne peut et ne doit pas commencer** 

### Story points 
- Lors du sprint planning, le story point du ticket doit être renseigné.
- Cela correspond au point d'effort. Plus le nombre est élevé, plus on estime que le ticket est long/dur à compléter.

### Type de ticket 
- Un ticket peut être une amélioration, une correction de bugs, une amélioration technique etc... il est important de bien typer son ticket.

### Epic 
Pour rappel, les epics sont des corpus de tâches importantes qui peuvent être divisé en stories.
- Si une story appartient à une epic, il faut renseigner l'epic dans le ticket. 

## Template : 

- Titre : En tant que [persona], je souhaite [objectif] afin de [raisons]
- Contenu du ticket : Il est important de prendre en compte [contraintes], 
- il est possible de contacter [aide] qui est la personne en charge de l'accès à cette donnée
- Tests d'acceptance : 
- Test 1 : Je peux facilement accéder au bouton
- Test 2 : L'affichage est adapté au mobile
- Test 3 : Si la connexion s'interrompt je suis averti 
