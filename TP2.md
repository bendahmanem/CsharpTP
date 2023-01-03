### Classes et fonctions bases 
Exercice 1:

Créez une classe Voiture avec les champs suivants:

marque (string)
modele (string)
nbPortes (int)
couleur (string)
Créez également une méthode Description() qui retourne une chaîne de caractères contenant les informations sur la voiture sous la forme: "La voiture est une marque modèle avec n portes de couleur couleur."

Exercice 2:

Créez une classe Etudiant avec les champs suivants:

nom (string)
prenom (string)
age (int)
Créez une méthode Saluer() qui retourne une chaîne de caractères contenant "Bonjour, je m'appelle nom prénom et j'ai age ans."

Exercice 3:

Créez une classe CompteBancaire avec les champs suivants:

nomTitulaire (string)
solde (float)
Créez une méthode Deposer() qui permet de déposer une certaine somme d'argent sur le compte, et une méthode Retirer() qui permet de retirer une certaine somme d'argent du compte. Assurez-vous que le solde ne devient jamais négatif.

Exercice 4:

Créez une classe Calculatrice avec une méthode Additionner(a, b) qui retourne la somme de deux nombres a et b, et une méthode Multiplier(a, b) qui retourne le produit de deux nombres a et b.

Exercice 5:

Créez une classe Rectangle avec les champs suivants:

largeur (float)
hauteur (float)
Créez une méthode Aire() qui retourne l'aire du rectangle, et une méthode Perimetre() qui retourne le périmètre du rectangle.



### Classes : héritage et interface 
Exercice 1:

Créez une interface IVolant avec une méthode Voler() qui retourne une chaîne de caractères "Je suis en train de voler!".

Créez une classe Oiseau qui implémente l'interface IVolant. La classe Oiseau doit avoir un champ nom (string) et une méthode Description() qui retourne une chaîne de caractères "Je suis un oiseau de nom nom."

Créez une classe Avion qui hérite de la classe Oiseau et qui implémente également l'interface IVolant. La classe Avion doit avoir un champ nbMoteurs (int) et une méthode Description() qui retourne une chaîne de caractères "Je suis un avion avec nbMoteurs moteurs de nom nom."

Exercice 2:

Créez une interface IAnimal avec une méthode Crier() qui retourne une chaîne de caractères contenant le cri de l'animal.

Créez une classe Chat qui implémente l'interface IAnimal. La classe Chat doit avoir un champ nom (string) et une méthode Description() qui retourne une chaîne de caractères "Je suis un chat de nom nom."

Créez une classe Lion qui hérite de la classe Chat et qui implémente également l'interface IAnimal. La classe Lion doit avoir un champ poids (float) et une méthode Description() qui retourne une chaîne de caractères "Je suis un lion de nom nom et de poids poids."

Exercice 3:

Créez une classe Forme avec un champ couleur (string) et une méthode Aire() qui retourne 0 (valeur par défaut).

Créez une classe Cercle qui hérite de la classe Forme. La classe Cercle doit avoir un champ rayon (float) et une méthode Aire() qui retourne l'aire du cercle (pi x rayon^2).

Créez une classe Rectangle qui hérite de la classe Forme. La classe Rectangle doit avoir les champs largeur (float) et hauteur (float) et une méthode Aire() qui retourne l'aire du rectangle (largeur x hauteur).

Écrivez une fonction qui prend un entier en entrée et retourne son carré.


#### Studies

Écrivez une classe Etudiant qui a les propriétés nom, prenom et age. Ajoutez un constructeur qui initialise ces propriétés lorsqu'un nouvel objet Etudiant est créé.

Écrivez une méthode dans la classe Etudiant qui retourne le nom complet de l'étudiant (prénom et nom).

Écrivez une fonction qui prend en entrée une liste d'objets Etudiant et qui retourne la moyenne d'âge des étudiants.

Écrivez une classe Formation qui a une liste d'objets Etudiant et une méthode qui calcule la moyenne d'âge de tous les étudiants de la formation.

Écrivez une méthode dans la classe Formation qui prend en entrée un nom d'étudiant et qui retourne l'objet Etudiant correspondant s'il existe dans la liste, ou null sinon.

Écrivez une surcharge de la méthode de recherche dans la classe Formation qui prend en entrée un prénom et un nom d'étudiant et qui retourne l'objet Etudiant correspondant s'il existe dans la liste, ou null sinon.

Écrivez une méthode dans la classe Etudiant qui retourne true si l'étudiant est majeur et false sinon. Utilisez cette méthode dans la classe Formation pour afficher la liste des étudiants majeurs.





### Collections et Types génériques


Écrivez une fonction qui prend une liste d'entiers en entrée et qui retourne la somme de tous les éléments de la liste.

Écrivez une classe générique Pile<T> qui implémente une pile (une structure de données qui permet d'ajouter et de retirer des éléments en respectant l'ordre FIFO (premier entré, premier sorti)). La classe doit avoir une méthode Push pour ajouter un élément à la pile et une méthode Pop pour retirer et retourner le premier élément de la pile.

Écrivez une méthode dans la classe Pile<T> qui retourne le nombre d'éléments dans la pile.

Écrivez une classe générique File<T> qui implémente une file (une structure de données qui permet d'ajouter et de retirer des éléments en respectant l'ordre FIFO (premier entré, premier sorti)). La classe doit avoir une méthode Enqueue pour ajouter un élément à la file et une méthode Dequeue pour retirer et retourner le premier élément de la file.

Écrivez une méthode dans la classe File<T> qui retourne le nombre d'éléments dans la file.

Écrivez une classe générique Dictionnaire<TKey, TValue> qui implémente un dictionnaire (une structure de données qui permet de stocker des paires clé-valeur). La classe doit avoir une méthode Add pour ajouter une paire clé-valeur au dictionnaire et une méthode GetValue qui prend une clé en entrée et retourne la valeur associée.

Écrivez une méthode dans la classe Dictionnaire<TKey, TValue> qui retourne le nombre de paires clé-valeur dans le dictionnaire.

Écrivez une fonction qui prend en entrée un dictionnaire et qui retourne une liste des valeurs du dictionnaire dans l'ordre des clés.