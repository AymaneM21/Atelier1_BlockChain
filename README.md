# Atelier1_BlockChain

# Résumé des Exercices : Proof of Work, Proof of Stake et Arbres Merkle

Ce projet explore trois concepts clés utilisés dans les blockchains : **Proof of Work (PoW)**, **Proof of Stake (PoS)**, et les **arbres Merkle**.

## Exercices

1. **Implémentation des Arbres Merkle**  
   - Objectif : Créer une structure de données arborescente (arbre Merkle) pour vérifier l'intégrité des données dans un bloc.
   - Principe : Les feuilles de l'arbre représentent les hashes des transactions, et chaque nœud parent est le hash combiné des hashes de ses enfants. Cela permet une vérification rapide et efficace de l'intégrité des données.
   - Résultat : Les arbres Merkle facilitent la validation des blocs et assurent l'intégrité des transactions sans nécessiter de transmettre l'intégralité des données.

2. **Implémentation du Proof of Work (PoW)**  
   - Objectif : Mettre en place un algorithme de PoW, ajuster la difficulté du hachage et mesurer le temps d'exécution pour chaque niveau de difficulté.
   - Principe : Le PoW repose sur la résolution de problèmes de hachage dont la difficulté augmente avec le nombre de zéros requis au début du hash.
   - Résultat : Plus la difficulté augmente, plus le temps de calcul croît de manière exponentielle.

3. **Implémentation du Proof of Stake (PoS)**  
   - Objectif : Mettre en place un algorithme de PoS, permettant aux validateurs de valider des blocs en fonction de leur participation (stake).
   - Principe : Le PoS utilise des validateurs choisis en fonction de leur investissement dans le réseau, sans concept de difficulté.
   - Résultat : Le temps d'exécution est généralement rapide et stable, avec peu d'impact en fonction du nombre de validateurs.



## Conclusions

- **Proof of Stake** est généralement **plus rapide** que le **Proof of Work**, car il ne dépend pas de la difficulté du calcul, mais du choix de validateurs, qui est peu influencé par leur nombre.
- Dans le **Proof of Work**, le **temps d'exécution** augmente avec la difficulté du problème. Ainsi, plus la difficulté de calcul est élevée, plus la solution est coûteuse en temps et en énergie.
- **Comparaison** : La comparaison entre PoW et PoS dépend de la difficulté du PoW. Le PoS reste plus performant en termes de rapidité dans des conditions similaires, mais le PoW apporte une sécurité renforcée par son caractère intensif en calcul.
- **Arbres Merkle** : Ils ajoutent une couche de sécurité et d'efficacité en permettant une vérification rapide de l'intégrité des transactions dans les blocs, rendant ainsi le processus de validation plus léger.

Pour plus de détails, voir les fichiers d'exercices  de l'atelier 1.

**Université Abdelmalek Essaadi** 
- Faculté des Sciences et Techniques de Tanger
- Département Génie Informatique
- Master : IASD
- Pr. Ikram Ben abdel ouahab
