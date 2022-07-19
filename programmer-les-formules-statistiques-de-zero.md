# STATISTIQUES ET CALCULS

## Mesures de tendance
Estimez où tombe une distribution. Vers quelle valeur tend une distribution.

## Mesures de la variabilité
***La variabilité*** correspond simplement aux différences entre les éléments, qui peuvent être
différences dans la couleur des yeux, la couleur des cheveux, la taille, le poids, le sexe, l'intelligence,
etc.

La *variabilité* mesure la **dispersion** ou la **similarité** entre les scores et nous renseigne sur la variété des scores dans une distribution.

Plusieurs mesures de variabilité telles que
- intervalle
- somme des carrés : SUM(Xi-mean)
- écart
- écart-type.

## Mesures de dépendance
Mesure de la dépendance (liaison) entre deux ou plusieurs variables.

S'obtient grâce à :

- Corrélation
- informations mutuelles
- entropie
- entropie conditionnelle

# Définitions

## Moyenne
- la moyenne arithmétique des valeurs d'un jeu de données
- peut être affecté par des valeurs extrêmes car il utilise la valeur exacte de chaque donnée
- mesure plus précise de la tendance centrale car elle prend en compte les scores individuels
- défini comme le centre mathématique d'une distribution (c'est-à-dire les différences entre les scores et la moyenne).
- Point d'équilibre parfait, car la somme de ces différents EST zéro pour toute distribution
- xbar de l'échantillon est le meilleur estimateur sans biais de la moyenne de la population (µ).
- peut être influencé par des valeurs extrêmement grandes ou extrêmement petites (valeurs aberrantes)
- Plus précisément, des valeurs extrêmement petites tirent la moyenne vers le bas et des valeurs extrêmement grandes tirent la moyenne vers le haut
- il est bon d'utiliser la médiane comme mesure de la tendance centrale dans la distribution asymétrique

## Écart
- moyenne arithmétique des carrés des écarts à la moyenne arithmétique obtenue
- la moyenne des écarts au carré par rapport à la "moyenne". C'est ce qu'on appelle aussi la mesure de la variabilité.
- mesure de la variabilité qui tient compte à la fois de la variation des scores et du nombre de scores dans un
Distribution
- utile pour comparer deux (ou plus) moyennes
- Mesure la variabilité moyenne entre les scores d'une distribution.
- si elles sont petites, les données sont proches de la moyenne et étalées si elles sont grandes.
- pour la population (variance observée), utilisez ***n*** et pour l'échantillon (variance corrigée, variance non biaisée), utilisez ***n-1*** dans la formule

## Écart-type
- mesure de l'étalement des numéros de la ou des séries. C'est ce qu'on appelle aussi la mesure de la variabilité.
- même signification que la variance
- utile pour connaître la différence entre les valeurs d'un ensemble ou entre deux (ou plusieurs) séries de nombres.
- utile pour comparer deux moyennes (ou plus).
- si elles sont petites, les données sont proches de la moyenne et étalées si elles sont grandes.
- pour la population, utilisez ***n*** et pour l'échantillon, utilisez ***n*** dans la formule

## Médiane
- le nombre ou la valeur du milieu d'un tableau ordonné (trié) de nombres (triés du plus petit au plus grand).
- S'il y a un nombre impair de points de données, la médiane sera le nombre au milieu absolu.
- S'il y a un nombre pair de points de données, la médiane est la moyenne des deux données centrales
points, ce qui signifie que les deux valeurs centrales doivent être additionnées et divisées par 2.
- ne prend pas en compte les valeurs réelles des scores dans un ensemble de données
- Meilleure mesure de tendance centrale que le mode puisqu'il équilibre parfaitement la distribution.
- Meilleure mesure de la tendance centrale lorsque les ensembles de données sont incomplets ou que les données sont fortement faussées.


## Mode
- le score le plus fréquent. Parfois, il n'y a pas de mode, deux modes ou plus de 2 modes
- Parfois, il n'y a aucun mode, deux modes ou plus de 2 modes
- utilisé pour connaître la valeur la plus courante dans une distribution.

## Intervalle
•La valeur ou le point de données le plus élevé moins la valeur la plus faible
- fournit des informations sur la zone couverte par une distribution, MAIS ne dit rien sur les valeurs individuelles.
- On dit d'un phénomène qu'il présente une « forte dynamique » lorsque l'étendue (ou la dispersion) est grande.

## Valeurs extrêmes ou valeurs aberrantes
Valeurs la plus petite et la plus grande.
Valeurs extrêmement petites ou extrêmement grandes dans une distribution.

## p% de moyenne tronquée
- moyenne arithmétique des observations restantes après avoir supprimé le plus petit p% et le plus grand p%.
- les observations doivent être ordonnées de la plus petite à la plus grande.
Remarque : Si p% de n (observations) n'est pas un entier, plusieurs algorithmes (informatiques) existent pour interpoler à chaque extrémité de la distribution et pour déterminer xtr(p).

## Déviation absolue
- Nous comparons toutes les valeurs à une sorte de mesure de la tendance centrale (habituellement la moyenne). Nous pouvons donc voir comment les données dans leur ensemble diffèrent ou s'écartent de cette mesure (la moyenne).

## Somme des carrés
- somme des carrés des écarts à la moyenne
- le carré de la somme de Xi moins la moyenne [SOMME(Xi-moyenne)]²
- mesure la variation totale entre les scores d'une distribution ;
- ne mesure pas la variabilité moyenne
- pourrait être égal à zéro s'il n'y a pas de variabilité et que tous les scores sont égaux
- Ne peut pas être négative (mathématiquement impossible)

## Asymétrie
- pour savoir comment les données sont faussées
- indique la présence ou l'absence de valeurs extrêmes (outliers) dans un jeu de données
- ***négativement asymétrique*** = présence de quelques petits extrêmes.
- ***positivement asymétrique*** = présence de grands extrêmes.

## score z (z-score)
Donné par la formule : **z = (x − µ)/σ**

## Quantiles

- généralisation de la notion de médiane (division en 2 parties égales d'une distribution ordonnée dans l'ordre croissant)
- quartiles (division par 4)
- déciles (division par 10)
- centiles (division par 100), encore appelé percentiles
- Les divisions donnent des parties du même effectif.

On parlera ainsi du « centile 90 » pour indiquer la valeur séparant les premiers 90 % de la population des 10 % restants. Ainsi, dans une population de jeunes enfants, un enfant dont la taille est au-delà du centile 90, ou en décà du centile 10, peut être l'objet d'un suivi particulier.

## Quartile
- Q1 (appelé le quartile inférieur)
- Q2 (appelée la médiane)
- Q3 (appelé le quartile supérieur)

Ces Q divisent la distribution en trois parties égales.

## Centiles
Pour un nombre entier **P**, où **1 ≤ P ≤ 99**, le **Pe centile** d'une distribution est une valeur telle que *P % des données se situent au niveau ou en dessous*. Ainsi, *il y a 99 percentiles*.
**Les emplacements des percentiles** sont trouvés à l'aide de la formule : LP = (n + 1)P/100

- Q1 = centile 25%
- Q2 = centile 50%
- Q3 = centile 75%

## intervalle interquartile
la distance entre Q1 et Q3
Il nous indique la propagation de la moitié médiane des données

## Intervalle de confiance (ICα)
Le théorème central limite (TCL) garantit que la moyenne estimée *xbar* est à une distance plus petite que *d* de la moyenne théorique E(X) avec une probabilité proche de P(|Y|.σ/√(n) )<d où Y convient à une loi gaussienne standard. Cela veut aussi dire que *Qα* est le quantile correspondant à *α* pour une gaussienne tel que:

- **P(E(X) ε [*Xbar-(Qα.σ/√n) ; Xbar-(Qα.σ/√n)*]) = 1-α**

**ICα** permet d'établir la **marge d'erreur** entre les échantillons d'un sondage () et les données de la population totale: **ICα=x̅ ± Za/2*σ/√( n)***
- marge d'erreur = Zα/2 x σ/√(n)
- Zα/2 est le coefficient de confiance
- α = degré de confiance
- σ = type d'écart
- n = taille de l'échantillon

## Coefficient de variation
Mesure de dispersion relative

# Étude d'une seule variable ou statistique descriptive univariée
Toutes les mesures de tendances centrales et de variabilité (dispersion/similarité) servent pour une meilleure analyse.

# Étude de deux ou plusieurs variables (statistique bivariée / multivariée)
Le principe est le même que pour une seule variable, sauf que toutes les caractéristiques (moyenne, mode, type d'écart, etc) sont bivariées (des vecteurs).

Il y a d'autre part une caractéristique supplémentaire: la **corrélation**. Elle est une mesure linéaire de la dépendance entre les différentes caractéristiques de la variable multivariée.

Il existe d'autres **mesures de dépendance** entre deux variables, comme l'**information mutuelle** (ou l'**entropie conditionnelle**).



# Distribution normale

Pour mieux comprendre comment les écarts-types sont utilisés comme mesures de dispersion, nous considérons ensuite les distributions normales. Le graphique d'une distribution normale est appelé une courbe normale ou une courbe en forme de cloche. La courbe a
les propriétés suivantes :

1. La courbe est en forme de cloche avec le point le plus élevé au-dessus de la moyenne µ.
2. Elle est symétrique par rapport à la droite passant par µ.
3. La courbe s'approche de l'axe horizontal mais ne le touche ni ne le traverse jamais.
4. Les points où la courbe change de concavité se trouvent à µ+σ et µ−σ.
5. L'aire totale sous la courbe est supposée être de 1.(0,5 à gauche de la moyenne et 0,5 à droite).

Les données d'une distribution normale sont réparties selon les règles suivantes :

- Environ 68 % des valeurs de données se situeront à moins d'un écart type de la moyenne.
- Environ 95 % des valeurs de données se situeront à moins de deux écarts-types de la moyenne.
- Environ 99,7 % des valeurs de données se situeront à moins de trois écarts-types de la moyenne.

Ce résultat est parfois appelé la règle empirique, car les pourcentages donnés sont observés dans la pratique.

``` démarque
# Pour les variables quantitatives (discrètes)
utilisez MEAN , MEDIAN ou MODE

# échelle d'intervalle ou de rapport
utiliser la MOYENNE

# Pour les variables ordinales
utilisez MEDIAN ou MODE

# Pour les variables nominales
utiliser uniquement MODE

# ASSYMETRIE (SKEWNESS)
si l'asymétrie est ENTRE -2 et +2, il n'y a PAS d'extrêmes dans les données. Si la
l'asymétrie est inférieure à -2 ou supérieure à +2, il y a des extrêmes dans les données.
**Lorsqu'il y a des extrêmes dans les données, la moyenne est une moins bonne mesure de la tendance. Alors ne l'utilisez pas !**

```

# Formules pour les données quantitatives


Mode ###



Données groupées

Mo ≈ L + (c · dL)/(dL + dH)

- L = limite inférieure de la classe modale
- c =
- dL= différence de fréquences entre la classe modale et la classe immédiatement inférieure
- dH= différence de fréquences entre la classe modale et la classe immédiatement supérieure



















# Formules pour les données binaires

```
- n désigne la taille de l'ensemble de données
- somme(xi) = count_of_1 = count(xi=1) = total de 1 = N(xi=1)
- moyenne(xi) = μ = somme(xi)/n = N/n = la proportion (p) d'un échantillon qui est égale à 1
- variance(xi) = p*q = p(1-p)
- p = proportion(xi=1) = probabilité(xi=1) = moyenne en %
- la valeur moyenne de la population pour une variable binaire est la proportion de fois où la variable binaire est égale à 1 ou la probabilité que xi=1 ==> moyenne(%) = proportion

- mode = max(N(x=0),N(x=1)) , si N(xi=0) < N(xi=1) donc mo = N(xi=1) sinon mo = N(xi= 0)
- médiane = proportion_of_1_arrondi = rond (moyenne)
- variance = p*q = p(1-p) = moyenne(1-moyenne)
- écart-type = σ = poe(variance,2) = (variance)²
 
 ** μ signifie ; σ sd

EXEMPLE:

Étant donné ces données:

personne1, 1 0 0 0 0
personne2, 1 0 0 0 0
personne3, 1 1 0 0 0
personne4, 1 1 1 0 0
personne5, 1 1 1 1 0
personne6, 1 1 1 1 1

----------- calcul ------------
somme(personne1)= N(x=1) = 1+0+0+0+0 = 1
somme(personne2)= N(x=1) = 1+0+0+0+0 = 1
somme(personne3)= N(x=1) = 1+1+0+0+0 = 2
somme(personne4)= N(x=1) = 1+1+1+0+0 = 3
somme(personne5)= N(x=1) = 1+1+1+1+0 = 4
somme(personne6)= N(x=1) = 1+1+1+1+1 = 5


moyenne(personne1)= N(x=1)/n = (1+0+0+0+0)/n = 1/5 ~ 0,2
moyenne(personne2)= N(x=1)/n = (1+0+0+0+0)/n = 1/5 ~ 0,2
moyenne(personne3)= N(x=1)/n = (1+1+0+0+0)/n = 2/5 ~ 0,4
moyenne(personne4)= N(x=1)/n = (1+1+1+0+0)/n = 3/5 ~ 0,6
moyenne(personne5)= N(x=1)/n = (1+1+1+1+0)/n = 4/5 ~ 0,8
moyenne(personne6)= N(x=1)/n = (1+1+1+1+1)/n = 5/5 ~ 1,0


proportion(personne1)=moyenne(%) = 0,2 ~ 20%
proportion(personne2)=moyenne(%) = 0.2 ~ 20%
proportion (personne3) = moyenne (%) = 0,4 ~ 40%
proportion(personne4)=moyenne(%) = 0,6 ~ 60%
proportion (personne5) = moyenne (%) = 0,8 ~ 80%
proportion(personne6)=moyenne(%) = 1.0 ~ 100%


mode(personne1)= max(N(x=0),N(x=1)) = max(4,5) = 5
mode(personne2)= max(N(x=0),N(x=1)) = max(4,5) = 5
mode(personne3)= max(N(x=0),N(x=1)) = max(3,2) = 3
mode(personne4)= max(N(x=0),N(x=1)) = max(2,3) = 3
mode(personne5)= max(N(x=0),N(x=1)) = max(1,4) = 4
mode(personne6)= max(N(x=0),N(x=1)) = max(0,5) = 5

médian(personne1)= proportion = rond(0.2) ~ 0
médian(personne2)= proportion = rond(0.2) ~ 0
médian(personne3)= proportion = rond(0.4) ~ 0
médian(personne4)= proportion = rond(0.6) ~ 1
médiane (personne5) = proportion = ronde (0,8) ~ 1
médian(personne6)= proportion = rond(1.0) ~ 1

variance(personne1)= p*q = 0,2*(1-0,2) ~ 0,16
variance(personne2)= p*q = 0,2*(1-0,2) ~ 0,16
variance(personne3)= p*q = 0,4*(1-0,4) ~ 0,24
variance(personne4)= p*q = 0,6*(1-0,6) ~ 0,24
variance(personne5)= p*q = 0,8*(1-0,8) ~ 0,16
variance(personne6)= p*q = 1.0*(1-1.0) ~ 0

écart_type(personne1)= pow(variance,2) = 0,16² = 0,256
écart_type(personne2)= pow(variance,2) = 0,16² = 0,256
écart_type(personne3)= pow(variance,2) = 0,24² = 0,0576
écart_type(personne4)= pow(variance,2) = 0,24² = 0,0576
écart_type(personne5)= pow(variance,2) = 0,16² = 0,256
standard_deviation(person6)= pow(variance,2) = 0² = 0



```
NB : Pour estimer une **probabilité** qu'un événement se produise, on peut utiliser des méthodes statistiques standard utilisant une variable de résultat binaire.

# ENTROPIE
**H = - SUM(pi.log(pi))**, où **pi** est la ***probabilité d'un état i d'un système***, et **H** est le symbole traditionnel pour **entropie**.

Un exemple de système est un ensemble de variables muettes.

Dans le cas particulier d'une variable fictive : **H = - (p log p + (1-p) log (1-p))**.



# ALGORITHMES

### écart

```
Soit n ← 0, Somme ← 0, SommeSq ← 0
Pour chaque donnée x :
n ← n + 1
Somme ← Somme + x
SommeCarré ← SommeCarré + x × x
Var = (SommeSq − (Somme × Somme) / n) / (n − 1)

Cet algorithme peut facilement être adapté pour calculer la variance d'une population finie : il suffit de diviser par n au lieu de n − 1 sur la dernière ligne.

```





















# SOURCES

- [https://blog.u-bourgogne.fr/licence-geographie/wp-content/uploads/sites/23/2015/06/seance_4.pdf](https://blog.u-bourgogne.fr/licence-geographie/wp-content/uploads/sites/23/2015/06/seance_4.pdf)
- [https://murraylax.org/rtutorials/binprop.html](https://murraylax.org/rtutorials/binprop.html)
- [https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf](https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf)
- [https://mylittleneuron.com/2021/01/12/traitement-des-donnees-incompletes-ou-imputation/](https://mylittleneuron.com/2021/01/12/traitement-des-donnees-incompletes-ou-imputation/)


