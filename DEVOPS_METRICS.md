# TP ORGA SCRUM MASTER

## DEVOPS_METRICS 
Voici les indicateurs que nous avons décidé de mettre en place afin de suivre la mise en place du DevOps dans l'entreprise : 

### Volume de déploiement
A chaque déploiement, on mesure le nombre de stories, de demandes de features et de corrections de bugs compris dedans avec le taux de ratio.
Ex : dans ce déploiement, 1/2 du volume est dédié à des corrections de bugs

### Fréquence de déploiement
L’objectif est d’effectuer le plus souvent possible des releases. En réduisant la taille de celle-ci, on facilite les tests et la mise en service.
On distingue les releases en prod et en pprod

### Temps de déploiement et Délai de livraison
Avec le temps de déploiement, on mesure le temps que la CI/CD met à mettre l'application en production. 
Le délai de livraison est le temps mis entre le début d'une tâche et son déploiement

### % Réussite des tests automatisés et % Fuite des bugs
La réussite des tests automatisés permet de savoir à quelle fréquence les modifications de code provoquent l’interruption de vos tests.
La fuite des bugs correspond au ratio entre le nombre de bugs trouvés en production et celui détectés en test. Cette métric permet d'estimer si le passage en prod est trop rapide, besoin d'un QA ou + de tests...

### Taux d’erreur
Le taux d'erreur correspond aux bugs et aux autres différents problèmes de production.

### TTR et TTD
Le Time To Recover (TTR) est une métric importante à observer. Elle correspond au temps mis pour se remettre d'un arrêt de service en production. 
Le Time To Detect (TTD) correspond au temps mis pour trouver une faille ou un bug.
