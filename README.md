# Calculateur d’Intérêt Simple

Ce dépôt contient un calculateur d’intérêt simple avec toutes les informations dans un seul fichier.

Intérêt = Capital × Taux × Durée

Le code complet :

def interet_simple(capital, taux, duree):
    return capital * taux * duree

print("=== Calculateur d'Intérêt Simple ===")
capital = float(input("Entrez le capital : "))
taux = float(input("Entrez le taux (ex : 0.05 pour 5%) : "))
duree = float(input("Entrez la durée en années : "))

interet = interet_simple(capital, taux, duree)
print("Intérêt simple :", interet)

Exemple :
Capital = 1000
Taux = 0.05
Durée = 3 ans
Résultat → 150

Auteur : Projet démonstratif d’un calculateur d’intérêt simple.
