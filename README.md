# Chiffrement de messages

**Hannachi — groupe B1 — travail individuel.**

## Le projet

Un programme simple pour chiffrer et déchiffrer un message avec le chiffrement affine du TP5. Il teste plusieurs messages, explique pourquoi certaines clés sont invalides et retrouve un message en essayant les 312 clés possibles avec un mot connu.

Notions utilisées : fonctions, boucles et conditions du TP1 ; modulo et PGCD du TP2 ; lettres, inverse modulaire et chiffrement affine du TP5. Aucun module extérieur n'est nécessaire.

## Organisation et lancement

- `tp/` : les six carnets de TP, nommés `tp1.ipynb` à `tp6.ipynb`.
- `projet/projet.ipynb` : le projet complet, avec le code, les résultats et les explications.

Ouvrir `projet/projet.ipynb` dans Jupyter ou dans l'environnement de carnets du cours. Exécuter toutes les cellules dans l'ordre. Pour essayer son propre message, modifier la cellule de la partie 1 et relancer la suite. Saisir un texte sans accents. Pour l'attaque, adapter aussi le mot connu.

Résultats à observer : le message est retrouvé après déchiffrement ; 12 tests réussissent ; une clé invalide est refusée ; l'essai des 312 clés retrouve le message d'exemple avec le mot SALUT. Les limites sont expliquées à la fin du carnet.

## Sources et IA

Méthodes adaptées des [TP2](https://cours.gclab.fr/outils-fondamentaux/tp2-arithmetique/) et [TP5 de Christophe Guyeux](https://cours.gclab.fr/outils-fondamentaux/tp5-synthese/). Les six TP sont complétés à partir des corrigés du cours. Attribution : Christophe Guyeux. Licence des adaptations : [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Aucun code provenant d'un autre dépôt n'est utilisé.

Une IA a aidé à compléter les TP et à écrire le projet, les essais et les explications. L'assistant a exécuté le carnet et vérifié le chiffrement/déchiffrement de l'alphabet avec les 312 clés valides.

**Vérifications personnelles de l'étudiant : à compléter après avoir relancé et compris le carnet.** Indiquer seulement les vérifications réellement faites, par exemple essayer son propre message et expliquer pourquoi a = 2 ne convient pas.

## Rendu

Selon les [consignes](https://cours.gclab.fr/outils-fondamentaux/evaluation/), placer ce README, `tp/` et `projet/` à la racine d'un dépôt GitHub accessible à l'enseignant. Envoyer son lien à christophe.guyeux@umlp.fr avec le nom et le groupe, dans les quatorze jours après la dernière séance de TP (date exacte confirmée en séance).

Dépôt GitHub : https://github.com/00Mehdi/outils-fondamentaux

Aucun courriel n'a été envoyé.
