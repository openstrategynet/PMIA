# A3 · Le planning · marche 3 : Faire calculer

## A3-e1 · Expérience · le calcul de tête

```
Sans utiliser d'outil de calcul ni exécuter de code, calcule de tête la moyenne
PERT = (O + 4P + Pe) / 6 de ces 6 tâches, puis la somme des 6 moyennes.
Durées en jours ouvrés (optimiste / probable / pessimiste) :
- Cloisons du plateau 2 : 15 / 20 / 32
- Électricité des plateaux : 8 / 10 / 16
- Climatisation : 12 / 15 / 27
- Câblage réseau : 6 / 8 / 13
- Salle serveur : 4 / 5 / 9
- Wi-Fi : 3 / 4 / 8
```

## A3-e2 · Expérience · le calcul par le code

```
Refais exactement le même calcul en exécutant du code. Montre le code, puis
compare ligne par ligne avec tes résultats précédents.
```

## A3-a · Estimations et chemin critique

```
Rôle : tu es un planificateur de projet.

Contexte : voici le dossier projet HORIZON.
[coller la charte et la WBS validées]

Ce que je veux comprendre : explique en 5 lignes l'estimation à 3 points et la
notion de chemin critique, avec un exemple chiffré simple.

Tâche : pour les lots de travail des lots [1, 2 et 4], estime les durées, puis
calcule le planning et le chemin critique.

Contraintes :
- pour chaque lot de travail : durée optimiste, probable et pessimiste en jours
  ouvrés, et l'hypothèse qui la justifie ;
- indique les prédécesseurs de chaque tâche ;
- fais TOUS les calculs (moyennes PERT, dates au plus tôt, marges, chemin
  critique) en exécutant du code, pas de tête ; si tu ne peux pas exécuter de
  code, dis-le clairement ;
- le déménagement a lieu le week-end de la semaine 24.

Format : UN SEUL tableau copiable dans Excel : code WBS · tâche · prédécesseurs ·
O · P · Pe · moyenne PERT · début au plus tôt (semaine) · marge · hypothèse.
Puis le chemin critique en une ligne, et la marge totale avant S24.

Contrôle : montre le code utilisé, et recalcule à la main 2 moyennes PERT pour
vérifier.
```

## A3-b · Le Gantt interactif

```
À partir du tableau de planning ci-dessus, construis un petit outil interactif
(un artifact, ou un canvas selon ton outil) :
- un diagramme de Gantt par semaine, de S1 à S25, avec une couleur par lot ;
- les tâches du chemin critique en rouge ;
- un curseur qui permet d'ajouter un retard (de 0 à 4 semaines) à une tâche
  choisie dans une liste, et qui montre aussitôt si le déménagement de S24 tient
  encore ;
- tout en français, sans aucune donnée qui n'est pas dans le tableau.
```
