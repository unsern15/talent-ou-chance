# Talent ou chance ?

Une simulation jouable sur le rôle de la chance dans la réussite.

**Jouer :** https://unsern15.github.io/talent-ou-chance/

## Ce qu'on cherche à savoir

Quand quelqu'un réussit très bien, est-ce surtout grâce à son talent, ou surtout grâce à la chance ? La simulation ne donne pas la réponse : elle montre ce qui se passe avec des règles simples et visibles, et chacun juge par lui-même.

## Le modèle (version 1)

Cette version reprend le modèle de A. Pluchino, A. E. Biondo et A. Rapisarda, « Talent vs Luck: the role of randomness in success and failure », *Advances in Complex Systems*, 2018 ([lire l'article](https://arxiv.org/abs/1802.07068)).

| Règle | Valeur | Origine |
|---|---|---|
| Nombre de personnes | 1 000 | Article |
| Talent | Courbe en cloche, moyenne 0,6, écart type 0,1, fixe toute la vie | Article |
| Capital de départ | 10 pour tout le monde | Article |
| Événements | 500, moitié coups de chance, moitié coups durs | Article |
| Durée | 40 ans, un tour tous les 6 mois | Article |
| Coup dur | Capital divisé par 2 | Article |
| Coup de chance | Saisi avec une probabilité égale au talent ; s'il est saisi, capital multiplié par 2 | Article |
| Déplacement des événements | 2 cases par tour | **Notre choix**, l'article ne le précise pas |
| Portée d'une rencontre | 1 case | **Notre choix**, réglée pour retrouver les résultats de l'article (les 20 % les plus riches détiennent environ 80 % du capital) |

Chaque règle est réglable dans la page, pour isoler un facteur à la fois. Un même « numéro de monde » donne toujours exactement la même histoire.

## Ce que la page propose

- Un pari en 3 questions avant de lancer, vérifié ensuite sur 100 mondes.
- Le monde animé, et une personne à suivre avec son histoire.
- Un onglet « D'où viennent les chiffres » avec toutes les sources.

Les chiffres affichés sont les résultats de ce modèle simplifié, pas une mesure du monde réel.

## Ce que le modèle ne dit pas

- Le talent est un seul chiffre, fixe toute la vie.
- Tout le monde part avec le même capital : pas d'héritage, pas de milieu d'origine.
- Un coup dur frappe pareil un riche et un pauvre.
- Personne ne s'entraide ni ne se relève.

## La suite, avec vous

Cet outil est construit avec une vision, la mienne. Avec la vôtre, il sera bien meilleur.

Prochaine étape : remplacer les coups durs abstraits par de vrais coups durs (perte d'emploi, séparation, cancer, invalidité, perte d'un parent), avec leurs fréquences en France, et comparer un monde avec et sans protection sociale, en comptant son coût autant que son bénéfice. Les données réunies, avec leurs sources, sont dans [donnees-coups-durs.md](donnees-coups-durs.md).

Vous pouvez aider dès maintenant :
- signaler une erreur, ou une source plus fiable ;
- proposer un coup dur, un coup de chance ou une règle à tester ;
- dire ce que vous n'avez pas compris.

Pour ça, [ouvrez une « issue »](https://github.com/unsern15/talent-ou-chance/issues) sur ce dépôt. Bientôt : un vote pour choisir le prochain facteur à ajouter. Les valeurs, elles, resteront fixées par des sources, pas par le vote.

## Inspiration

Le format s'inspire des simulations jouables de Nicky Case.
