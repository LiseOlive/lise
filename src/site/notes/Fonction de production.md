---
{"dg-publish":true,"permalink":"/fonction-de-production/","tags":["AES/S3/micro","CM","éco","AES/S3"],"ctime":"2026-09-16T14:54:32.110+02:00","mtime":"2026-10-15T11:17:47.814+02:00","dg-note-properties":{"tags":["AES/S3/micro","CM","éco","AES/S3"],"class":"[[References/Micro]]","sector":"[[References/AES]]","semester":"[[References/S3]]","form":"[[References/CM]]","part":"[[References/2]]","date created":"2026-09-16, 14 54","date modified":"2026-10-15, 11 17"}}
---


# II. Fonction de production

# 1. Cadre général et représentation discrète
## A. Relation travail-production et structure des coûts
La fonction de production $Q(n)$ exprime la quantité produite (output) en fonction de la quantité de facteur travail $n$ (input).

| Travail ($n$) | Production $Q(n)$ | Gain marginal ($\Delta Q$) |
| :---: | :---: | :---: |
| **1** | 10 | — |
| **2** | 18 | +8 |
| **3** | 25 | +7 |

* **Coûts des facteurs** :
  * **Facteur travail** : $s = 30\text{€}$ par unité de travail (coût total du travail : $s \times n$).
  * **Facteur capital (fixe)** : $50\text{€}$ la location.
* **Représentation graphique** :
  * **Axe des ordonnées (Y)** : Production $Q(n)$
  * **Axe des abscisses (X)** : Facteur travail $n$


![Schéma discret Q(n)](/img/user/Attachments/schema-q-n-discrete.png)


# 2. Étude de la fonction continue $Q(n) = 2\sqrt{n}$

## A. Démonstration des deux propriétés fondamentales

*Rappel de dérivation* : $\frac{d}{dX}(a X^b) = a \cdot b X^{b-1}$

1. **Croissance de la production totale ($Q'(n) > 0$)** :  
   $$Q'(n) = 2 \times \frac{1}{2} n^{-\frac{1}{2}} = n^{-\frac{1}{2}} = \frac{1}{\sqrt{n}}$$  
   Comme $n > 0$, on a $n^{-\frac{1}{2}} > 0$. La quantité totale produite augmente donc avec la quantité de travail utilisée.

2. **Propriété du produit marginal décroissant ($Q''(n) < 0$)** :  
   $$Q''(n) = (Q'(n))' = \left(n^{-\frac{1}{2}}\right)' = -\frac{1}{2} n^{-\frac{3}{2}} = -\frac{1}{2\sqrt{n^3}}$$  
   Comme $n > 0$, la dérivée seconde est négative ($Q''(n) < 0$), ce qui démontre la décroissance du produit marginal.

## B. Tableau de valeurs et interprétation

| Travail ($n$) | Production $Q(n) = 2\sqrt{n}$ | Produit marginal $Q'(n) = \frac{1}{\sqrt{n}}$ |
| :---: | :---: | :---: |
| **1** | $2$ | $1{,}00$ |
| **2** | $2\sqrt{2} \approx 2{,}83$ | $\frac{1}{\sqrt{2}} \approx 0{,}71$ |
| **3** | $2\sqrt{3} \approx 3{,}46$ | $\frac{1}{\sqrt{3}} \approx 0{,}58$ |
| **4** | $4$ | $0{,}50$ |

> [!important] Interprétation économique
> * **Rendements marginaux décroissants** : La quantité supplémentaire produite devient de plus en plus faible à mesure que $n$ augmente.
> * **Signification de la dérivée** : La dérivée $Q'(n)$ indique la valeur apportée par la dernière unité de production marginale.

![Schéma Q(n) = 2sqrt(n)](/img/user/Attachments/schema-q-2sqrt-n.png)


# 3. Exercice $Q(n) = 10\sqrt{n}$

## A. Énoncé
Soit la fonction de production $Q(n) = 10\sqrt{n}$ :
1. Montrer que la quantité totale produite augmente avec la quantité de travail utilisée.
2. Montrer que le produit marginal est décroissant.
3. Représenter la fonction graphiquement.
4. Calculer la production totale et le produit marginal pour $n=2$, $n=4$ et $n=6$. Montrer par cet exemple les propriétés démontrées aux deux premiers points.

## B. Exo 1
$$Q'(n) = 10 \times \frac{1}{2} n^{-\frac{1}{2}} = \frac{5}{\sqrt{n}}$$  
Pour tout $n > 0$, $Q'(n) > 0$. La production totale augmente donc de façon continue avec le travail.

> [!success] Si on travail plus, on produit plus
> 

$$Q''(n) = \left(\frac{5}{\sqrt{n}}\right)' = 5 \times \left(-\frac{1}{2}\right) n^{-\frac{3}{2}} = -\frac{5}{2\sqrt{n^3}}$$  
Pour tout $n > 0$, $Q''(n) < 0$. Le produit marginal est donc strictement décroissant. 

> [!success] La productivité marginale du travail diminue.
> 


![Fonction de production concave Q(n) = 10sqrt(n)](/img/user/Attachments/fonction-production-concave.png)

| Travail<br>($n$) | Production totale $Q(n) = 10\sqrt{n}$ | Produit marginal $Q'(n) = \frac{5}{\sqrt{n}}$ |
| :--------------: | :-----------------------------------: | :-------------------------------------------: |
|   **$n = 2$**    | $10\sqrt{2} \approx \mathbf{14{,}14}$ | $\frac{5}{\sqrt{2}} \approx \mathbf{3{,}54}$  |
|   **$n = 4$**    |    $10\sqrt{4} = \mathbf{20{,}00}$    |        $\frac{5}{2} = \mathbf{2{,}50}$        |
|   **$n = 6$**    | $10\sqrt{6} \approx \mathbf{24{,}49}$ |    $5\sqrt{6}-10 \approx \mathbf{2{,}04}$     |

**Vérification des propriétés** :
* **Propriété 1 vérifiée** : Lorsque $n$ passe de 2 à 4 puis à 6, la production $Q(n)$ augmente ($0 < 14{,}14 < 20{,}00 < 24{,}49$).
* **Propriété 2 vérifiée** : Lorsque $n$ augmente, le produit marginal $Q'(n)$ diminue ($3{,}54 > 2{,}50 > 2{,}04$).

## C. Exo 2
$Q(n) = 100 \times n - 10n^2$, avec $n < 4$

1) Montrer que la production totale augmente avec la Q de travail utilisé
2) Montrer que le produit marginal est décroissant
3) Calculer le produit marginal pour n=1, n=2, n=3
4) Montrer le résultat graphiquement
---
1) Q'(n) > 0
2) Q''(n) < 0

> [!info] Suite du cours dans carnet
> 
