# UE MAPSI  
Aims to present the basic and advanced elements of probability and statistics for computer science.
http://dac.lip6.fr/master/enseignement/mapsi/

## Cours 1 : rappels de probas/statistiques
1. Vocabulaire, approche évènementielle : Se représenter concrètement les probabilités sur un univers Ω
2. Variable aléatoire : définition formelle : Définition de Kolmogorov
3. Caractéristiques d'une loi de probabilité : Espérance, Variances, Quantiles
4. Lois jointes sur plusieurs VA : Description d'une population sur plusieurs caractères Loi jointe, lois marginales
5. Probabilités conditionnelles, indépendance

## Cours 2 : rappels de probas/statistiques
1. Indépendance mutuelle : il s'agit d'une propriété fondamentale en apprentissage de paramètres et l'on s'appuiera sur celle-ci dans les cours 3 et 4.
2. Indépendance conditionnelle : cette propriété est l'un des deux fondements qui permettent la manipulation de probabilités de grandes tailles sur ordinateur (utilisées par exemple pour réaliser des diagnostics de panne, etc).
3. Loi de Bernoulli / Loi binomiale : Ce sont les lois suivies par des expériences de type pile ou face. Elles forment le fondement des lois multinomiales, qui sont très utilisées en intelligence artificielle.
4. Loi normale : Il s'agit probablement de la loi continue la plus importante en probas / statistiques. Dès lors que l'on s'intéresse à des sommes ou des moyennes de variables aléatoires, on aboutit inéluctablement à cette loi.
5. Loi des grands nombres : Il s'agit du principe qui justifie qu'à partir d'échantillons observés, on sera en mesure d'estimer les distributions de probabilité des variables aléatoires qui ont engendré ces échantillons. Cela nous servira, notamment, à justifier que les algorithmes d'apprentissage que l'on développera produisent des résultats sensés.
6. Théorème central-limite : Ce théorème est la justification que toute somme ou moyenne de variables aléatoires indépendantes suivant la même loi (quelle qu'elle soit) suit approximativement une loi normale.

## Cours 3 : Maximum de vraisemblance, maximum a posteriori
1. Vraisemblance pour la prise de décision : on montre ce qu'est une vraisemblance et comment elle peut être utilisée pour décider entre plusieurs alternatives laquelle paraît la meilleure.
2. Estimation de paramètre par max de vraisemblance : c'est un classique en apprentissage, particulièrement utilisé en intelligence artificielle.
3. Estimation de paramètre par maximum a posteriori : L'idée est similaire à l'estimation par max de vraisemblance, à ceci près que l'on a un apriori sur les paramètres possibles. Cette technique s'avère particulièrement utile lorsque l'on réalise des apprentissages avec de petites bases de données.

## Cours 4 : algorithme EM
1. Rappels de maths sur la convexité : quelques rappels utiles pour comprendre pourquoi l'algorithme EM fonctionne.
2. Description de EM : EM est un algorithme utile pour apprendre les paramètres de distributions à partir de base de données avec données manquantes (ce qui arrive souvent en pratique). Dans le cours, on décrit l'algorithme et on montre son fonctionnement sur quelques exemples.
3. Justification de EM : on montre pourquoi EM converge vers un maximum (local) de vraisemblance.
4. Mixtures de Gaussiennes : L'estimation de certains paramètres de lois un peu compliquées, comme les mixtures de gaussiennes, s'avère complexe à réaliser avec le maximum de vraisemblance. Dans cette partie du cours, on montre comment EM peut permettre de s'affranchir de cette dificulté.

## Cours 5 - tests d'hypothèses
1. Tests d'hypothèses : les tests d'hypothèses consistent à confronter 2 hypothèses : l'hypothèse nulle H0 et la contre-hypothèse H1. Ce type de test permet de déterminer, à partir de l'observation d'un échantillon (ou d'une base de données), laquelle des 2 hypothèses paraît la plus probable. Cela peut s'avérer très utile pour prendre des décisions.
2. Tests d'ajustement : les tests d'ajustement sont des tests d'hypothèses dans lesquels H0 représente une distribution de probabilité particulière et H1 représente toutes les autres. Autrement dit, cela permet de déterminer s'il est plus probable qu'un échantillon suive la loi décrite par H0 ou bien plutôt une autre loi (mais, dans ce cas, on ne sait pas laquelle).
3. Tests d'indépendance : les tests d'indépendance sont des tests d'ajustement particuliers : H0 correspond à la loi s'il y a effectivement indépendance et H1 aux lois s'il n'y a pas indépendance.
4. Loi du chi2 : Les tests d'ajustement et d'indépendance s'appuient sur cette loi. On montre dans le cours à quoi elle correspond.

## Cours 6 : Chaine de Markov
1. Définition d'une série temporelle
2. Modélisation par chaine de Markov
3. Exploitation des chaines de Markov
4. Apprentissage des paramètres
5. Ouverture sur le Dynamic Time Wrapping

## Cours 7 : Chaine de Markov cachées
1. Introduction sur les méthodes d'évaluation en machine learning
2. Limites des chaines de Markov
3. Modélisation par chaine de Markov cachées
4. Algorithme Forward (calcul de la vraisemblance d'une série)
5. Algorithme de Viterbi (décodage d'une séquence)
6. Algorithme de Baum-Welch (apprentissage des paramètres)

## Cours 8: échantillonnage et MCMC
1. Échantillonnage d'une loi discrète
2. Rejection sampling
3. MCMC : Metropolis-Hastings
4. MCMC : échantillonneur de Gibbs

## Cours 9: Régression
1. Définition du problème de la régression
2. Résolution analytique 1D avec des estimateurs classiques
3. Hypothèse normale sur le bruit et résolution par max de vraisemblance
4. Formulation en fonction de coût et résolution

### Binome:
* Amine Djeghri
* Yacine Allouache
