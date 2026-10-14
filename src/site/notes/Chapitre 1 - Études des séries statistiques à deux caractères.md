---
{"dg-publish":true,"permalink":"/chapitre-1-etudes-des-series-statistiques-a-deux-caracteres/","tags":["AP/S2/tq","CM","maths","AP/S2"],"ctime":"2026-01-17T23:07:46.000+01:00","mtime":"2026-10-13T17:34:02.757+02:00","dg-note-properties":{"tags":["AP/S2/tq","CM","maths","AP/S2"],"class":"[[TQ]]","sector":"[[References/AES]]","semester":"[[References/S2]]","form":"[[References/CM]]","part":null,"date created":"2026-01-17, 23 07","date modified":"2026-09-21, 23 12"}}
---


# <font color="#8064a2">Chapitre 1 - Études des séries statistiques à deux caractères</font>


## <font color="#8064a2">Introduction</font>

Les salariés d'une entreprise peuvent être étudiés à partir de caractères :
- âge
- sexe
- niveau de formation
- rémunération
- ancienneté, etc

・On notera X et Y, les deux caractères étudiés

<u>Exemple</u> : une **agence immobilière** propose des appartements à la location
- leur surface en m2 : caractère X
- leur loyer mensuel en euros : caractère Y
 
> [!tip] Remarque
> Ce sont des caractères quantitatifs et continus, les modalités vont prendre la forme de classe


Présentation des séries statistiques à 2 caractères :

- Si les observations sont **non groupées** ➞ Série individualisée
		
| x<sub>i</sub> | y<sub>i</sub> |
| ------------- | ------------- |
| x<sub>i</sub> | y<sub>i</sub> |
| x<sub>i</sub> | y<sub>i</sub> |
| …           | …           |
| x<sub>i</sub> | y<sub>i</sub> |

- Si les observations sont groupées ➞ Tableau de contingence


## <font color="#8064a2">1 - Le tableau de contingence</font>

### <font color="#8064a2">A - Présentation du tableau</font>

- **Population** dont l'effectif total est n
- **Caractères** X et Y
	
	↪︎ **modalités** de X :  
	x<sub>1</sub>, x<sub>2</sub>, …, x<sub>i</sub>, …, x<sub>k</sub>

	↪︎ **modalités** de Y :  
	y<sub>1</sub>, y<sub>2</sub>, …, y<sub>i</sub>, …, y<sub>p</sub>


<iframe src="/img/user/Attachments/AES%20Plan%20CM%20TQA%20Eco-Gestion%202%20L1%20S2%202025-2026%20(dragged).pdf" width="100%" height="900px" title="AES Plan CM TQA Eco-Gestion 2 L1 S2 2025-2026 (dragged).pdf" style="border:1px solid #ccc;"></iframe>


> [!abstract] Définition
> **Effectif croisé** : Nombre d'unités de la population vérifiant simultanément la modalité 𝑥<sub>𝑖</sub> du caractère X et la modalité 𝑦<sub>𝑖</sub> du caractère Y
> 
> **Tableau de contingence** : Tableau à k lignes et p colonnes fournissant pour chaque couple de modalités (𝑥<sub>𝑖</sub> , 𝑦<sub>𝑖</sub>) l'effectif croisé 𝑛<sub>𝑖𝑗</sub> correspondant


<u>Exemple 1</u> :
- n<sub>44</sub> = 62
- n<sub>12</sub> = 7
- n = 400

<u>Remarque</u> :
$$
\overset{k}{\underset{i=1}{\sum}}\;\cdot\;\overset{p}{\underset{j=1}{\sum}} n_{ij}=n
$$
D'où, pour l'exemple 1 :  
5 4 = 45 + 7 + … + 36 = 400


> [!abstract] Définition
> **Effectif marginal de X**, noté : $$𝑛_{i·}$$
> - Nombre d'unités de la population vérifiant la modalité 𝑥<sub>𝑖</sub> du caractère X (quelle que soit la modalité de Y)  
> ↪︎ Chaque effectif marginal de X est la somme des effectifs croisés pour une ligne donnée : $$𝑛_{𝑖·}=\overset{p}{\underset{j=1}{\sum}} n_{ij}$$  
> ↪︎ La somme des effectifs marginaux de X est égale à l'effectif total : $$\overset{k}{\underset{i=1}{\sum}} n_{i\cdot} \equiv n
> $$

Suite de l'exemple 1 :
- 𝑛<sub>3·</sub> = 140
- 𝑛<sub>5·</sub> = 36
- n = 400


> [!abstract] Définition
> **Effectif marginal de Y**, noté $$𝑛_{·𝑗}$$
> - Nombre d'unités de la population vérifiant la modalité y<sub>i</sub> du caractère Y (quelle que soit la modalité de X)  
> ↪︎ Chaque effectif marginal de Y est la somme des effectifs croisés pour une colonne donnée : $$𝑛_{·𝑗} = \overset{k}{\underset{i=1}{\sum}} n_{ij}$$  
> ↪︎ La somme des effectifs marginaux de X est égale à l'effectif total : $$\overset{p}{\underset{j=1}{\sum}}n_{·j} = n$$

Suite de l'exemple 1 :
- 𝑛<sub>·1</sub> = 63
- 𝑛<sub>·3</sub> = 116
- n = 400


・Définition : **Fréquence croisée** $$f_{ij}=\frac{n_{ij}}{n}$$  
・Définition : **Fréquence marginale de X** $$f_{i·} = \frac{n_{i·}}{n}\;  
ou\;\ f_{i·} = \overset{p}{\underset{j=1}{\sum}}f_{ij}$$  
・Définition : **Fréquence marginale de Y**$$f_{·j} = \frac{n_{·j}}{n}\;\ ou \;  
f_{\cdot j} = \overset{k}{\underset{i=1}{\sum}}f_{ij}$$
> [!important] ・**Propriétés** : 
> $$
> \begin{aligned}
> \overset{k}{\underset{i=1}{\sum}}\;\overset{p}{\underset{j=1}{\sum}} f_{ij} &= 1 \\
> \overset{k}{\underset{i=1}{\sum}} f_{i\cdot} &= 1 \\
> \overset{p}{\underset{j=1}{\sum}} f_{\cdot j} &= 1
> \end{aligned}
> $$

・ Exemple en terme de fréquence (tableau 3)
- 𝑓<sub>43</sub> = 0,045
- 𝑓<sub>4·</sub> = 0,21
- 𝑓<sub>·2</sub> = 0,2775

***

### <font color="#8064a2">B - Les séries marginales</font>

Toute série statistiques à deux caractères peut être décomposée en deux séries à un seul caractère appelée séries marginales :
- Série marginale de X dont les effectifs sont les effectifs marginaux de X 
- Série de marginale de Y dont les effectifs sont les effectifs marginaux de Y

	<iframe src="/img/user/Attachments/AES%20Plan%20CM%20TQA%20Eco-Gestion%202%20L1%20S2%202025-2026%20(dragged)%201.pdf" width="100%" height="900px" title="AES Plan CM TQA Eco-Gestion 2 L1 S2 2025-2026 (dragged) 1.pdf" style="border:1px solid #ccc;"></iframe>


### <font color="#8064a2">C - Les séries conditionnelles</font>

・ Au lieu de s'intéresser à l'ensemble de la population, on considère une partie seulement de la population
- Séries sous condition d'une modalité donnée  
	⤷ toute ligne (ou colonne) du tableau de contingence correspond à une série conditionnelle


> [!abstract] ・Définition :
> - **On appelle Fréquence de la modalité x<sub>i</sub> de X conditionnelle à la modalité y<sub>j</sub> de Y** :  
> $$\frac{f_{xi}}{Y} = 𝑦_{j} = \frac{n_{ij}}{n_{\cdot j}}$$
> 
> ⤷ Proportion des observations présentant la modalité x<sub>i</sub> dans l'ensemble des observations présentant la modalité y<sub>i</sub>
> 
> - Exemple - Tableau : $$\frac{f_{x_{3}}}{Y} = 𝑦_{2} = \frac{36}{111} = 0,324$$  
> ⤷ Interprétation : dans les appartements dont le loyer est compris entre 300 et 400€, 32,4% ont une surface comprise entre 50 et 70m<sup>2</sup>


> [!abstract] ・Définition : 
> - **On appelle "fréquence de la modalité yi de Y conditionnelle à la modalité xi de X** :  
> $$\frac {f_{y_j}}{X} = x_{i} = \frac{n_{ij}}{n_{i\cdot}}$$  
> ⤷ Proportion des observations présentant la modalité yj dans l'ensemble des observations présentant la modalité xi 
> - Exemple - Tableau : $$\frac{f_{y_{3}}}{X} = x_{2} = 0,091$$  
> ⤷ Interprétation : Parmi les appartements dont la surface est comprise entre 30 et 50m<sup>2</sup>, 9,1% ont un loyer compris entre 400 et 600€


***


### <font color="#8064a2">A - Caractéristiques des séries marginales</font>

#### <font color="#8064a2">a - Moyennes arithmétiques marginales</font>

> [!abstract] Définition 
> **Moyenne Arithmétique Pondérée** : Somme pondérée des observations sur l'effectif total


**Moyenne marginale de X** :  
$$\overline{x} = \frac{1}{n} \overset{k}{\underset{i=1}{\sum}} n_{i\cdot}\;x_{i}$$  
**Moyenne marginale de Y : $$\overline{y} = \frac{1}{n}\overset{p}{\underset{j=1}{\sum}} n_{\cdot j}\;y_{j}$$**  
<u>Exemple :</u> agence immobilière

|               | C<sub>j</sub> | 225        | 350        | 500        | 800         |       |
| ------------- | ------------- | ---------- | ---------- | ---------- | ----------- | ----- |
| C<sub>i</sub> | X / Y         | [150, 300[ | [300, 400[ | [400, 600[ | [600, 1000[ | Total |
| 20            | [10, 30[      | 45         | 7          | 0          | 0           | 52    |
| 40            | [30, 50[      | 16         | 64         | 8          | 0           | 88    |
| 60            | [50, 70[      | 2          | 36         | 90         | 12          | 140   |
| 90            | [70, 110[     | 0          | 4          | 18         | 62          | 84    |
| 130           | [110, 150[    | 0          | 0          | 0          | 36          | 36    |
|               | Total         | 63         | 111        | 116        | 110         | 400   |

**Calculer la surface**

$$\overline{x} = \frac{1}{n} \overset{5}{\underset{i=1}{\sum}} n_{i\cdot}C_{i}
= \frac{1}{400}(52 \times 20+\dots+36\times 130) = 63m^{2}$$
$$\overline{y} = \frac{1}{n} \overset{4}{\underset{j=1}{\sum}} n_{\cdot j}C_{j}=\frac{1}{400}(63\times 225+\dots+110\times 800) = 497,5625e $$


#### <font color="#8064a2">b - Écarts-type marginaux</font>

*Permet de mesurer la dispersion d'une série autour de sa moyenne*

> [!abstract]
> **Écart-type marginal de X** :
> $$\sigma (X) = \sqrt{V(X)} $$
> Avec V(X) variance de X :
> $$ V(X)=\frac{1}{n}\overset{k}{\underset{i=1}{\sum}} n_{i\cdot}(x_{i}-\overline{x})^{2} \;\;\;\;\; ou\;\;\;\;\;\;  
V(X)=\frac{1}{n}\sum_{i=1}^{k} n_{i\cdot}\,x_i^{2}-\bar{x}^{2}
$$

Rappel (S1) : 
- **La variance d'une variable statistique de X** est la moyenne arithmétique des carrés des écarts des observations à la moyenne arithmétique
$$\begin{gathered} V(X)=(\frac{1}{n}\overset{5}{\underset{i=1}{\sum}} n_{i\cdot}C^2_{i})-\overline{x}^{2}\\
\\ (\frac{1}{400}(52\times 20^{2}+\dots+36 \times 130^{2}))-63^{2} = 917 \\
 \\ \Rightarrow \sigma(X)=\sqrt{917} = 30,282m\end{gathered}$$


> [!abstract]
> **Écart-type marginal de Y** :
> $$\sigma (Y) = \sqrt{V(Y)} $$
> Avec V(Y) variance de Y :
> $$ V(Y)=\frac{1}{n}\overset{p}{\underset{j=1}{\sum}} n_{\cdot j}\;(y_{j}-\overline{y})^{2} 
 \;\;\;\;\; ou\;\;\;\;\;\;  V(Y)=\frac{1}{n}\sum_{j=1}^{p} n_{\cdot j}\,y_j^{2}-\bar{y}^{2}
$$

<u>Exemple</u> : Calculer l'écart-type de Y
 $$\begin{gathered} V(Y)=\frac{1}{n}\overset{4}{\underset{j=1}{\sum}} n_{\cdot j}\;(C^{2}_{j})-\overline{y}^{2} \\
 
\\=(\frac{1}{400}(63\times 225^{2}+\dots+110\times 800^{2})) - 497,5625^{2} = \\ 
\\42 898,75 \Rightarrow \sigma(Y) = 207,12 euros \end{gathered}$$

***


### <font color="#8064a2">B - Caractéristiques des séries conditionnelles</font>

#### <font color="#8064a2">a - Série de X conditionnelles à Y</font>

|               | C<sub>j</sub> | 225        | 350        | 500        | 800         |       |
| ------------- | ------------- | ---------- | ---------- | ---------- | ----------- | ----- |
| C<sub>i</sub> | X / Y         | [150, 300[ | [300, 400[ | [400, 600[ | [600, 1000[ | Total |
| 20            | [10, 30[      | 45         | 7          | 0          | 0           | 52    |
| 40            | [30, 50[      | 16         | 64         | 8          | 0           | 88    |
| 60            | [50, 70[      | 2          | 36         | 90         | 12          | 140   |
| 90            | [70, 110[     | 0          | 4          | 18         | 62          | 84    |
| 130           | [110, 150[    | 0          | 0          | 0          | 36          | 36    |
|               | Total         | 63         | 111        | 116        | 110         | 400   |


**Moyenne de X conditionnelle à Y = y<sub>j</sub>**

$$\overline{x}_{Y=y_{j}} = \frac{1}{n_{\cdot j}}\sum_{i=1}^k n_{ij}\;x_{i}$$
$$\overline{x}_{Y=y_{1}} = \frac{1}{63}(45*20+16*40+2*60) = 26,35m^{2}$$
$$\overline{x}_{Y=y2} = 47,03$$
$$\overline{x}_{Y=y_{3}} = 63,27$$
$$\overline{x}_{Y=y4} = 99,82$$


**Moyenne de Y conditionnelle à X = x<sub>i</sub>**
$$\overline{y}_{X=xi} = \frac{1}n_{i\cdot }\sum_{j=1}^pn_{ij}\;C_{j}$$

|               | C<sub>j</sub> | 225        | 350        | 500        | 800         |       |
| ------------- | ------------- | ---------- | ---------- | ---------- | ----------- | ----- |
| C<sub>i</sub> | X / Y         | [150, 300[ | [300, 400[ | [400, 600[ | [600, 1000[ | Total |
| 20            | [10, 30[      | 45         | 7          | 0          | 0           | 52    |
| 40            | [30, 50[      | 16         | 64         | 8          | 0           | 88    |
| 60            | [50, 70[      | 2          | 36         | 90         | 12          | 140   |
| 90            | [70, 110[     | 0          | 4          | 18         | 62          | 84    |
| 130           | [110, 150[    | 0          | 0          | 0          | 36          | 36    |
|               | Total         | 63         | 111        | 116        | 110         | 400   |

$$\overline{y}_{X=x_{1}} \frac{1}{52}(45*225+7*350) = 241,83$$
$$\overline{y}_{X=x_{2}} = 340,91$$
$$\overline{y}_{X=3} = 483,21$$
$$\overline{y}_{X=4}= 714,29$$
$$\overline{y}_{X=5} = 800$$

> [!Analyse des résultats]
> - **On observe des liens croissants entre surface et loyer**


***


### <font color="#8064a2">C - Liens entre moyennes marginale et moyennes conditionnelles</font>


> [!summary]
> La moyenne marginale est une **moyenne pondérée** des moyennes conditionnelles $$\overline{x} = \frac{1}{n}\overset{p}{\underset{j=1}{\sum}} n_{\cdot j}\;\overline{x}_{Y=y_{j}}$$
> $$\overline{y} = \frac{1}{n}\overset{k}{\underset{i=1}{\sum}} n_{i\cdot }\;\overline{y}_{X=x_{i}}$$


<u>Exemple</u>

- Pour retrouver la moyenne marginale à partir de : $$\overline{x}_{Y=y_{j}}$$
- On utilise la formule en remplaçant par le total des effectifs * les moyennes conditionnelles :
$$ \bar{x}
=\frac{1}{400}\left(63\cdot 26{,}03 + 111\cdot 46{,}31 + 116\cdot 63{,}10 + 110\cdot 100{,}36\right)
$$
$$
\bar{x}
=\frac{1}{400}\left(1640 + 5140 + 7320 + 11040\right)
=\frac{25140}{400}
=62{,}85
\approx 63 $$


- Même processus pour y : $$\bar{y}_{X=x_i}$$$$ \bar{y}
=\frac{1}{400}\left(52\cdot 241{,}83 + 88\cdot 340{,}91 + 140\cdot 483{,}21 + 84\cdot 714{,}29 + 36\cdot 800\right)
$$$$
\bar{y}  
=\frac{1}{400}\left(12575 + 30000 + 67650 + 60000 + 28800\right)  
=\frac{199025}{400}  
=497{,}56\text{ €}
$$

***



## <font color="#8064a2">Section 3 - Liaison statistique entre deux caractères : l'ajustement linéaire</font>


### <font color="#8064a2">A - Le problème posé</font>

> [!Ajustement: ]
>- Rechercher une écriture fonctionnelle du lien entre les deux variables : **Y=𝑓(X)**
>- On va rechercher la relation linéaire
>	⤷ **Quelle droite va être la meilleure possible parmi le nuage de point ?**

[[Ajustement des points.png\|Ajustement des points.png]]

[[Représentation graphique de l'évolution des ventes.jpeg\|Représentation graphique de l'évolution des ventes.jpeg]]


### <font color="#8064a2">B - Le principe des moindres carrés ordinaires</font>

・**Principe des moindres carrés ordinaires (MCO)** : La droite la meilleure est celle qui rend minimale la somme des carrés de quarts entre points du nuage et droite

> [!tip]
> **Droite d'ajustement de Y en X** : $$Y = a\;X + b$$


## <font color="#8064a2">C - Détermination de la droite d'ajustement</font>

### <font color="#8064a2">a - Covariance</font>

> [!summary] Définition
> **Covariance de X et Y :** Moyenne des produits des écarts à la moyenne de X et de Y


- **Pour des données non-groupées** :
$$Cov(X,Y) = \frac{1}{n}\sum_{i=1}^n(x_{i}-\overline{x})(y_{i}-\overline{y})$$
$$
Cov(X,Y)=\left[\frac{1}{n}\sum_{i=1}^{n}x_i y_i\right]-\left[\overline{x}\,\overline{y}\right]
$$

- **Pour des données groupées :** $$
Cov(X,Y)=\frac{1}{n}\sum_{i=1}^{k}\sum_{j=1}^{p}n_{ij}(x_i-\overline{x})(y_j-\overline{y})
$$
$$
Cov(X,Y)
=\left[\frac{1}{n}\sum_{i=1}^{k}\sum_{j=1}^{p} n_{ij}\,x_i\,y_j\right]
-\overline{x}\,\overline{y}
$$

$$
Cov(X,Y)
=\left[\frac{1}{400}\sum_{i=1}^{k}\sum_{j=1}^{p} n_{ij}\,C_i\,C_j\right]
-\overline{x}\,\overline{y}
$$

<u>Exemple</u> :

|               | C<sub>j</sub> | 225        | 350        | 500        | 800         |       |
| ------------- | ------------- | ---------- | ---------- | ---------- | ----------- | ----- |
| C<sub>i</sub> | X / Y         | [150, 300[ | [300, 400[ | [400, 600[ | [600, 1000[ | Total |
| 20            | [10, 30[      | 45         | 7          | 0          | 0           | 52    |
| 40            | [30, 50[      | 16         | 64         | 8          | 0           | 88    |
| 60            | [50, 70[      | 2          | 36         | 90         | 12          | 140   |
| 90            | [70, 110[     | 0          | 4          | 18         | 62          | 84    |
| 130           | [110, 150[    | 0          | 0          | 0          | 36          | 36    |
|               | Total         | 63         | 111        | 116        | 110         | 400   |

$$Cov(X,Y)
=\overset{5}{\underset{i=1}{\sum}} \overset{4}{\underset{j=1}{\sum}} n_{ij}\;Ci\;Cj$$
$$= (45*20*225)+(7*20*350)+(16*40*225)+\dots+ (36*130*800)=14654500$$$$Cov(X,Y) = \frac{14654500}{400}-63*497,5625=5289,8125$$
> [!tip]
> - Si la covariance est positive la liaison est croissante
> - Si la covariance est négative la liaison est décroissante


### <font color="#8064a2">b - Paramètres de la droite d'ajustement de Y en X</font>

<u>Résultat</u> : 
- Les paramètres a et b de la droite d'ajustement de Y en X : $$Y = aX + b$$
- sont données par : $$a = \frac{Cov(X,Y)}{V(X)}$$ $$ b = \overline y - a\overline{x}$$
***

<u>Exemple 1</u> : agence immobilière (**données groupées**)

- On sait que : 
	- ẋ = 63
	- ȳ = 497,5625
	- V(X) = 917
	- Cov(X,Y) = 5289,8125

- Coefficients a et b de la droite d'ajustement de Y en X : 
	- $a = \frac{Cov(X,Y)}{V(X)} = 5,7686$
	- $b = \overline y - a\overline{x} = 134,1407$  
	- $\Rightarrow \; Y = 5,77\; X + 134,14$

***

Exemple 2 : publicité et ventes (**données non-groupées**)

| Mois      | Dépenses de publicité i x | Ventes i y |
| --------- | ------------------------- | ---------- |
| Janvier   | 2,4                       | 38         |
| Février   | 3                         | 42         |
| Mars      | 3                         | 42         |
| Avril     | 2,5                       | 39         |
| Mai       | 3,2                       | 40         |
| Juin      | 3,5                       | 45         |
| Juillet   | 2                         | 35         |
| Août      | 1,8                       | 24         |
| Septembre | 3                         | 38         |
| Octobre   | 3,2                       | 40         |
| Novembre  | 3,8                       | 44         |
| Décembre  | 4,6                       | 53         |

- Équation de la droite d'ajustement de Y en X ?
	- **n = 12**

- Série individualisée : 
  
	- $\overline{x}=\frac{1}{n}\sum_{i=1}^nx_{i} \Rightarrow \overline{x}=\frac{1}{12}\sum_{i=1}^{12}x_{i}=\frac{36}{12}=3$
  
	- $\overline{y}=\frac{1}{n}\sum_{i=1}^ny_{i} \Rightarrow \overline{y}=\frac{1}{12}\sum_{i=1}^{12}y_{i}=\frac{480}{12}=40$
	  
	- $\begin{cases} V(X)= (\frac{1}{n}\sum_{i=1}^nx^2_{i} )-\overline{x}^2 \\ V(X)= (\frac{1}{12}\sum_{i=1}^{12}x^2_{i} )-\overline{x}^2 \\ =(\frac{1}{12}(2,4^2+\dots+4,6^2))-3^2 \\ = (\frac{1}{12}=114,58)-3^2)=0,54833\end{cases}$
	  
	- $\begin{cases} Cov(X,Y) = (\frac{1}{n}\sum_{i=1}^n(x_{i}*y_{i}))-(\overline{x}*\overline{y}) \\ Cov(X,Y) = (\frac{1}{12}\sum_{i=1}^{12}(x_{i}*y_{i}))-(\overline{x}*\overline{y}) \\ = (\frac{1}{12}(2,4 * 38+\dots+4,6*53))-(3*40) \\ = (\frac{1}{12}1492,4)-(3*40)=4,3667\end{cases}$
	  
	-   $\begin{cases} a = \frac{Cov(X,Y)}{V(X)}=7,96 \\b = \overline{y} - a \overline{x} \\ = 40 - 7,96\times{3} = 16,1 \\ \Rightarrow\; Y = 7,96\;X + 16,1\end{cases}$
	  
***

## <font color="#8064a2">D - La qualité de l'ajustement</font>

### <font color="#8064a2">a - Le coefficient de corrélation linéaire</font>

- Lien de dépendance linéaire faible ? Fort ? Significatif


> [!abstract] Définition
> On appelle **coefficient de corrélation linéaire de X et Y**, noté r(X,Y), le nombre tel que : 
> - $r\;(X,Y) = \frac {Cov(X,Y)}{\sigma (X)\sigma (Y)}$
> - *avec -1 ≤ r(X,Y) ≤ 1*


<u>Remarques</u> : 

1. r(X,Y) positif : corrélation linéaire positive (a > 0)
2. r(X,Y) négatif : corrélation linéaire négative (a < 0)

- Plus r(X,Y) est proche de 1 ou -1 : 
	- Plus la dépendance linéaire est forte
- Plus r(X,Y) est proche de 0 : 
	- Plus la dépendance linéaire est faible


### <font color="#8064a2">b - Interpréter le coefficient de corrélation linéaire</font>

<u>Résultat</u> : 

- Le lien de dépendance **linéaire** entre X et Y est significatif si : $$|\;r(X,Y)\:|≥ 0,87$$
<u>Exemple 1</u> : publicité et ventes

- On sait que : 
	- V(X) = 0,54833 ⇒ 𝜎(X) = 0,7405
	- V(Y) = $\frac{1}{12} ∑^{12}_{i=1} y^2_{i} - ȳ^2 = 42,333 ⇒ 𝜎(Y) = 6,506$
	- Cov(X,Y) = 4,3667 
	  
	 $\Rightarrow r\;(X,Y)= \frac {Cov(X,Y)}{\sigma (X)\sigma (Y)} = 0,906 > 0,87$
  
- Le lien de dépendance **linéaire** entre dépenses de publicité et ventes est **significatif** :
	- Prévisions à l'aide de la droite d'ajustement

***

<u>Exemple 2</u> : agence immobilière

- On sait que : 
	- 𝜎(X) = 30,282
	- 𝜎(Y) = 207,12
	- Cov(X,Y) = 5289,8125 
	  
	  $\Rightarrow r\;(X,Y)= \frac {Cov(X,Y)}{\sigma (X)\sigma (Y)} = 0,84 < 0,87$
	  
- Le lien de dépendance **linéaire** entre surface et loyer n'est pas **significatif** :
	- *Autre lien à l'aide d'un ajustement non-linéaire* ?