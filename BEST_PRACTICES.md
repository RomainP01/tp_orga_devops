
# TP ORGA SCRUM MASTER

## Bonnes Pratiques de code
Quand vous codez, tâchez d'appliquer au maximum les principes énoncées par Robert C Martin dans son livre Clean Code.

### Les principes SOLID 

#### S pour Single responsibility principle (Responsabilité unique) 
- Principe : une classe, une fonction ou une méthode doit avoir une et une seule responsabilité.
- Exemple : si on souhaite faire une fonction qui doit lire et créer des informations, on la scinde en deux fonctions. Une qui lit des informations et une qui crée des informations.

#### O pour Open/closed principle (Ouvert/fermé)
- Principe : une classe, une fonction ou une méthode doit être ouverte à l'extension mais fermé à la modification.
- Exemple : si on crée une classe, on s'assure que celle-ci utilise correctement l'abstraction. Ainsi, lors d'une US qui nécessite cette classe, le developpeur pourra ajouter sa fonction ou autre sans devoir modifier les existantes ou la classe en elle-même.

#### L pour Liskov substitution principle (Substitution de Liskov)
- Principe : une instance de type T doit pouvoir être remplacée par une instance de type G, tel que G sous-type de T, sans que cela ne modifie la cohérence du programme.
- Exemple : si on crée une crée une classe qui est une sous-classe d'une autre, le programme doit fonctionner parfaitement que ce soit la sous classe ou la classe dont elle hérite.

#### I pour Interface segregation principle (Ségrégation des interfaces)
- Principe : une instance de type T doit pouvoir être remplacée par une instance de type G, tel que G sous-type de T, sans que cela ne modifie la cohérence du programme.
- Exemple : si on crée une crée une classe qui est une sous-classe d'une autre, le programme doit fonctionner parfaitement que ce soit la sous classe ou la classe dont elle hérite.

#### D pour Dependency inversion principle (Inversion des dépendances)
- Principe : il faut dépendre des abstractions, pas des implémentations.
- Exemple : Lorsque l'on met des dépendances entre deux entités, il faut le faire via le biais des classes abstraites.

### Design Pattern 
- Dès que des design patterns peuvent être utilisés, cela doit être fait. 
- Pour apprendre les design pattern vous pouvez vous référer à cette série de vidéos : https://www.youtube.com/watch?v=v9ejT8FO-7I&list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc




