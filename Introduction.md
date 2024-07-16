# Introduction à Python

Python est un langage de programmation simple et puissant, utilisé pour de nombreuses applications allant du développement web à la science des données. Il est apprécié pour sa syntaxe claire et lisible.

## Histoire de Python

Python a été créé par Guido van Rossum et sa première version a été publiée en 1991. Guido van Rossum a développé Python dans le but de créer un langage qui soit simple à lire et à écrire, tout en étant puissant et extensible. Voici quelques jalons importants de l'histoire de Python :

- **1980s** : Guido van Rossum commence à travailler sur un projet nommé ABC à CWI (Centrum Wiskunde & Informatica) aux Pays-Bas. ABC inspire de nombreuses idées qui seront plus tard intégrées à Python.
- **1989** : Van Rossum commence à travailler sur Python pendant les vacances de Noël.
- **1991** : La première version de Python (version 0.9.0) est publiée.
- **2000** : La Python Software Foundation (PSF) est créée pour gérer le développement du langage.
- **2008** : Python 3.0 est publié, introduisant des modifications majeures et des améliorations par rapport aux versions précédentes.
- **2020** : Python 2 atteint sa fin de vie (EOL), marquant la transition complète vers Python 3.

## Utilité de Python dans le Monde du Travail

Python est devenu un langage de programmation extrêmement populaire et est largement utilisé dans divers domaines professionnels pour les raisons suivantes :

1. **Facilité d'Apprentissage et de Lecture** : La syntaxe claire et lisible de Python le rend accessible aux débutants, facilitant ainsi l'apprentissage de la programmation.

2. **Polyvalence** : Python est un langage polyvalent qui peut être utilisé pour le développement web, l'analyse de données, l'intelligence artificielle, le machine learning, le développement de jeux, l'automatisation, et bien plus encore.

3. **Bibliothèques et Frameworks Riches** : Python dispose d'un écosystème riche avec des bibliothèques et des frameworks pour presque tous les besoins. Par exemple, Django et Flask pour le développement web, Pandas et NumPy pour l'analyse de données, TensorFlow et PyTorch pour le machine learning.

4. **Communauté Active** : Une grande communauté d'utilisateurs et de développeurs signifie une abondance de ressources, de tutoriels et de support, facilitant la résolution des problèmes et l'apprentissage de nouvelles compétences.

5. **Utilisation dans les Grandes Entreprises** : De nombreuses grandes entreprises telles que Google, Facebook, Netflix et Spotify utilisent Python pour ses capacités de développement rapide et son efficacité.

---

## Variables

Les variables sont utilisées pour stocker des informations qui peuvent être utilisées et manipulées dans votre programme. Elles peuvent contenir différents types de données comme des nombres, des chaînes de caractères, etc.

```python
# Exemple 1 : Stocker et afficher un nom
nom = "Alice"
print(nom)   # Affiche: Alice

# Exemple 2 : Stocker et afficher un âge
age = 25
print(age)   # Affiche: 25
```

## Types de Données

Python prend en charge différents types de données tels que les entiers, les flottants, les chaînes de caractères et les booléens.

```python
# Exemple 1 : Déclaration de différents types de données
nombre_entier = 10
nombre_flottant = 10.5
chaine = "Bonjour, le monde!"
vrai_ou_faux = True

print(nombre_entier)  # Affiche: 10
print(nombre_flottant)  # Affiche: 10.5
print(chaine)  # Affiche: Bonjour, le monde!
print(vrai_ou_faux)  # Affiche: True

# Exemple 2 : Conversion de types de données
age_str = "30"
age_int = int(age_str)  # Convertit une chaîne en entier
print(age_int)  # Affiche: 30
```

## Opérations de Base

Python permet d'effectuer des opérations arithmétiques et de comparaison.

```python
# Exemple 1 : Opérations arithmétiques
a = 5
b = 3

somme = a + b  # 8
difference = a - b  # 2

print(somme)  # Affiche: 8
print(difference)  # Affiche: 2

# Exemple 2 : Opérations de comparaison
x = 10
y = 20

egal = (x == y)  # False
plus_grand = (x > y)  # False

print(egal)  # Affiche: False
print(plus_grand)  # Affiche: False
```

## Conditions

Les structures conditionnelles permettent d'exécuter du code en fonction de certaines conditions.

```python
# Exemple 1 : Structure if-else
age = 18

if age >= 18:
    print("Vous êtes majeur.")
else:
    print("Vous êtes mineur.")

# Exemple 2 : Structure if-elif-else
note = 75

if note >= 90:
    print("Excellent")
elif note >= 70:
    print("Bien")
else:
    print("Passable")
```

## Boucles

Les boucles permettent de répéter des blocs de code plusieurs fois.

### Boucle `for`

```python
# Exemple 1 : Boucle for avec range
for i in range(5):
    print(i)  # Affiche de 0 à 4

# Exemple 2 : Boucle for pour parcourir une liste
fruits = ["pomme", "banane", "cerise"]
for fruit in fruits:
    print(fruit)  # Affiche chaque fruit
```

### Boucle `while`

```python
# Exemple 1 : Boucle while avec compteur
compteur = 0
while compteur < 5:
    print(compteur)
    compteur += 1  # Incrémente le compteur

# Exemple 2 : Boucle while avec condition
mot_de_passe = ""
while mot_de_passe != "python123":
    mot_de_passe = input("Entrez le mot de passe: ")

print("Accès accordé!")
```

## Fonctions

Les fonctions sont des blocs de code réutilisables qui effectuent une tâche spécifique.

```python
# Exemple 1 : Fonction sans retour de valeur
def saluer(nom):
    print(f"Bonjour, {nom}!")

saluer("Alice")  # Affiche: Bonjour, Alice!

# Exemple 2 : Fonction avec retour de valeur
def additionner(a, b):
    return a + b

resultat = additionner(3, 4)  # 7
print(resultat)  # Affiche: 7
```

## Listes

Les listes sont des collections ordonnées d'éléments.

```python
# Exemple 1 : Manipulation de listes
nombres = [1, 2, 3, 4, 5]

# Accès aux éléments
print(nombres[0])  # 1

# Ajouter un élément
nombres.append(6)
print(nombres)  # Affiche: [1, 2, 3, 4, 5, 6]

# Exemple 2 : Suppression d'éléments
nombres.remove(3)
print(nombres)  # Affiche: [1, 2, 4, 5, 6]

# Parcourir la liste
for nombre in nombres:
    print(nombre)
```

## Dictionnaires

Les dictionnaires sont des collections de paires clé-valeur.

```python
# Exemple 1 : Accès et modification des valeurs
personne = {"nom": "Alice", "age": 25, "ville": "Paris"}

print(personne["nom"])  # Alice

# Ajouter une paire clé-valeur
personne["profession"] = "Ingénieur"
print(personne)  # {'nom': 'Alice', 'age': 25, 'ville': 'Paris', 'profession': 'Ingénieur'}

# Exemple 2 : Suppression de paires clé-valeur
del personne["age"]
print(personne)  # {'nom': 'Alice', 'ville': 'Paris', 'profession': 'Ingénieur'}

# Parcourir le dictionnaire
for cle, valeur in personne.items():
    print(f"{cle}: {valeur}")
```

## Modules

Les modules sont des fichiers Python qui contiennent du code utilisable dans d'autres fichiers Python.

```python
# Exemple 1 : Importation et utilisation de modules standard
import math

# Utilisation d'une fonction du module math
print(math.sqrt(16))  # 4.0

# Exemple 2 : Importation de fonctions spécifiques d'un module
from math import pi, cos

print(pi)  # 3.141592653589793
print(cos(pi))  # -1.0
```

Voici un tableau des modules Python les plus couramment utilisés :

| Module | Description |
| --- | --- |
| `math` | Fonctions mathématiques |
| `os` | Fonctions liées au système d'exploitation |
| `random` | Génération de nombres aléatoires |
| `datetime` | Manipulation de dates et d'heures |
| `json` | Encodage et décodage JSON |
| `requests` | Envoi de requêtes HTTP |
| `numpy` | Calculs numériques avancés |
| `pandas` | Manipulation de données tabulaires |
| `matplotlib` | Visualisation de données |

