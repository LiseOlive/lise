---
{"dg-publish":true,"permalink":"/production-couts-salaries-graphes-fonctions/","ctime":"2026-10-15T22:11:14.691+02:00","mtime":"2026-10-15T22:14:27.095+02:00","dg-note-properties":{"date created":"2026-10-14, 14 53","date modified":"2026-10-15, 22 14","sector":"[[References/AES]]","semester":"[[References/S3]]","class":"[[References/Micro]]","form":"[[References/CM]]","part":"[[References/2]]"}}
---


# Production, coûts, salariés, graphes, fonctions (manque la partie 2)

## I. Analyse graphique : Relation entre Production et Coût (Exemple des Pizzas)

> [!info] Contexte de l'exemple (Document 1 - visible à `14:16`)
> Un patron produit des pizzas à l'aide de salariés.
> * **Salaire unitaire ($w$) :** $25\text{ €}$ / salarié (ou étudiant)
> * **Coût fixe de location ($CF$) :** $50\text{ €}$

### 1. Calcul des points et évolution des courbes

En observant le premier graphique (la **fonction de production** $Q(n)$) et le deuxième graphique (la **fonction de coût total** $C(q)$), on relève les points suivants :

* **Pour $n = 2$ salariés $\implies q = 10$ pizzas produites :**
  $$\text{Coût total} = (25 \times 2) + 50 = 50 + 50 = 100\text{ €}$$

* **Pour $n = 4$ salariés $\implies q = 20$ pizzas produites :**
  $$\text{Coût total} = (25 \times 4) + 50 = 100 + 50 = 150\text{ €}$$

* **Pour $n = 6$ salariés $\implies q = 25$ pizzas produites :**
  $$\text{Coût total} = (25 \times 6) + 50 = 150 + 50 = 200\text{ €}$$

* **Pour $q = 30$ pizzas produites :**
  Même sans connaître le nombre exact de salariés nécessaires sur le graphique, on observe que pour passer de $20$ à $30$ unités, le coût total sera **largement supérieur à $200\text{ €}$**.

### 2. Reproduction du support visuel (Word)

> [!camera] Capture vidéo recommandée (`14:18`)
> ![[capture_14_18_graphe_cout_pizza.png\|capture_14_18_graphe_cout_pizza.png]]
> *(Glissez ici une capture d'écran de la vidéo à **14:18**)*

#### Reproduction du graphique de la fonction de coût $C(q)$ et de ses annotations 

```text
Coût Total (C)
  ^
  |                                         /
200| - - - - - - - - - - - - - - - - - - - -/ (q=25, C=200)
  |                                       /
150| - - - - - - - - - - - - - - - - - - / (q=20, C=150)
  |                                    /
100| - - - - - - - - - - -• (q=10)   /
  |                     / |        /
 50|• (CF=50)         /   |      /
  |                 /     |    /
  +-----------------------+----+---+----+---> Quantité (q)
  0                      10   20  25   30
```

> [!quote] Reproduction des zones de texte du document Word (`14:18`)
> **Encadré à droite du graphique :**
> " Le coût marginal est croissant : Le coût de production de $30$ unités $- 150 > 150 - 100$. "
>
> **Encadré sous le graphique :**
> " Par exemple, si un salaire unitaire coûte $25\text{ euros/étudiant(e)}$, et le coût de location est de $50\text{ euros}$.
>
> Dans les $2$ graphiques, il y a besoin de $2$ employés pour une production de $10\text{ pizzas}$. Puis, le coût total de production de $10\text{ pizzas}$ est de $100\text{ euros}$. Pourquoi ? Parce que $2$ salariés coûtent $25 \times 2 = 50\text{ euros}$ et le coût de la location est de $50\text{ euros}$. Donc $50 + 50 = 100$.
>
> Puis, il y a besoin de $4$ salariés pour produire $20\text{ pizzas}$. Dans le $2\text{ème}$ graphique, la production de $20\text{ pizzas}$ est obtenue avec un coût de $150\text{ euros}$. Pourquoi ? Parce que $4$ salariés coûtent $25 \times 4 = 100\text{ euros}$ et le coût de la location est de $50\text{ euros}$. Donc $100 + 50 = 150$. "

### 3. Interprétation économique fondamentale

> [!important] Relation essentielle entre Produit Marginal et Coût Marginal
> 1. **Le produit marginal est décroissant (Fonction de production concave) :**
>    Lorsque l'on augmente le nombre de salariés par paliers identiques (de $2$ à $4$, puis de $4$ à $6$), la production totale augmente **de moins en moins vite** :
>    $$25 - 20 < 20 - 10 \quad (\text{soit } 5 < 10)$$
>    L'entreprise devient de moins en moins efficace au fur et à mesure qu'elle ajoute des heures de travail.
>
> 2. **Le coût marginal est croissant (Fonction de coût convexe) :**
>    Puisque les travailleurs supplémentaires sont moins productifs, produire la même quantité supplémentaire (passer de $10$ à $20$ pizzas, puis de $20$ à $30$ pizzas) nécessite d'embaucher proportionnellement beaucoup plus de salariés. Par conséquent, le coût total augmente **de plus en plus vite** (de manière plus que proportionnelle) :
>    $$C(30) - C(20) > C(20) - C(10) \implies C(30) - 150 > 150 - 100$$

---

## II. Exercice d'application : Étude algébrique d'une fonction de production et de coût

> [!camera] Capture vidéo recommandée (`04:08` ou `15:02`)
> ![[capture_15_02_enonce_exercice.png\|capture_15_02_enonce_exercice.png]]
> *(Glissez ici une capture d'écran de l'énoncé complet à **15:02**)*

> [!example] Énoncé de l'exercice
> **Données :**
> * Fonction de production : $Q(n) = 100 \cdot n^{1/2}$
> * Salaire unitaire : $50\text{ euros / employé}$
> * Coût fixe : $1000\text{ euros}$
>
> **Questions :**
> 1. Quel est le coût total de production si le patron utilise $n$ employés dans la production ?
> 2. Montrez que le produit total est croissant et le produit marginal est décroissant.
> 3. Trouvez la fonction inverse de la fonction de production.
> 4. Trouvez la fonction de coût de production.
> 5. Montrez que la fonction de coût est croissante et que le coût marginal est croissant également.
> 6. Trouvez la fonction de production et la fonction de coût pour $10$ salariés, $20$ salariés, $30$ salariés et $40$ salariés. Montrez les données dans un tableau et discutez le résultat.

> [!tip] Remarque de l'enseignant pour l'examen
> * À l'examen, il n'y aura pas de questions ouvertes floues du type *" discutez le résultat "* sans précision.
> * Les calculs numériques précis au centime près ne sont pas l'objectif principal, mais il faut **absolument savoir passer algébriquement de la fonction de production $Q(n)$ à la fonction de coût $C(q)$ via la fonction inverse** (par exemple pour répondre à une question du type : *" La fonction $C(q) = \frac{q^2}{200} + 1000$ peut-elle représenter la fonction de coût issue de $Q(n) = 100 \cdot n^{1/2}$ ? "*).

---

## III. Correction détaillée de l'exercice

### Question 1 : Coût total en fonction du nombre d'employés ($n$)

Le coût total dépend indirectement du nombre d'heures de travail (ou du nombre de salariés $n$) car la quantité produite $Q$ dépend elle-même de $n$ :

$$\text{Coût total} = \text{Coût des salaires} + \text{Coût fixe} = n \cdot 50 + 1000$$

$$C(Q(n)) = n \cdot 50 + 1000$$

### Question 2 : Propriétés de la fonction de production

Pour démontrer ces deux propriétés, il faut étudier le signe des dérivées première et seconde de $Q(n)$ par rapport à $n$ :

* **Produit total croissant :** La condition est d'avoir une dérivée première strictement positive :
  $$Q'(n) > 0$$

* **Produit marginal décroissant :** Le produit marginal correspond à $Q'(n)$. Sa décroissance signifie que la dérivée seconde est strictement négative (fonction concave) :
  $$Q''(n) < 0$$

> [!check]- Rappel du calcul des dérivées (Bonus)
> Soit $Q(n) = 100 \cdot n^{1/2}$ :
> * **Dérivée première (Produit marginal) :**
>   $$Q'(n) = 100 \cdot \frac{1}{2} \cdot n^{\frac{1}{2} - 1} = 50 \cdot n^{-1/2} = \frac{50}{\sqrt{n}} > 0 \quad (\forall n > 0)$$
> * **Dérivée seconde :**
>   $$Q''(n) = 50 \cdot \left(-\frac{1}{2}\right) \cdot n^{-\frac{1}{2} - 1} = -25 \cdot n^{-3/2} = -\frac{25}{n\sqrt{n}} < 0 \quad (\forall n > 0)$$

### Question 3 : Fonction inverse de la fonction de production

> [!camera] Capture vidéo recommandée (`05:25`)
> ![[capture_05_25_question_1_2_3.png\|capture_05_25_question_1_2_3.png]]
> *(Glissez ici une capture d'écran de la correction des questions 1 à 3 à **05:25**)*

On cherche la fonction inverse de $Q(n)$, notée $F(q)$, qui indique **le nombre d'heures de travail (ou de salariés) nécessaire afin de produire une quantité donnée $q$**.

1. **Changement de notation :**
   * $Q(n)$ devient une variable, notée $q$.
   * $n$ devient une fonction, notée $F(q)$.

2. **Substitution dans l'équation $Q(n) = 100 \cdot n^{1/2}$ :**
   $$q = 100 \cdot (F(q))^{1/2}$$
   *(Rappel : $n^{1/2} = \sqrt{n}$)*

3. **Passage au carré pour isoler $F(q)$ :**
   On élève toute l'équation au carré car $\left[(F(q))^{1/2}\right]^2 = (F(q))^{\frac{1}{2} \cdot 2} = (F(q))^1 = F(q)$.
   On obtient :
   $$q^2 = 100^2 \cdot F(q)$$

4. **Expression finale de la fonction inverse :**
   $$F(q) = \frac{q^2}{100^2} \quad \left(\text{soit } F(q) = \frac{q^2}{10000}\right)$$

### Question 4 : Fonction de coût de production $C(q)$

> [!camera] Capture vidéo recommandée (`12:45`)
> ![[capture_12_45_question_4.png\|capture_12_45_question_4.png]]
> *(Glissez ici une capture d'écran de la question 4 à **12:45**)*

On reprend l'expression du coût total trouvée à la question 1 :

$$C(Q(n)) = n \cdot 50 + 1000$$

1. **Application du changement de variable :**
   * $Q(n)$ devient la variable $q$.
   * $n$ devient la fonction $F(q)$.
   $$C(q) = 50 \cdot F(q) + 1000$$

2. **Remplacement de $F(q)$ par son expression $\frac{q^2}{100^2}$ :**
   $$C(q) = 50 \cdot \frac{q^2}{100^2} + 1000$$

3. **Simplification :**
   Comme $\frac{100^2}{50} = \frac{10000}{50} = 200$ *(vérifié sur Excel à `12:15` avec la saisie `100^2/50`)*, on obtient :
   $$C(q) = \frac{q^2}{200} + 1000$$

### Question 5 : Croissance du coût total et du coût marginal

* **Coût total croissant :** La dérivée première du coût total par rapport à $q$ doit être strictement positive :
  $$C'(q) > 0$$

* **Coût marginal croissant :** Le coût marginal étant $C'(q)$, sa croissance implique que la dérivée seconde soit strictement positive (fonction convexe) :
  $$C''(q) > 0$$

> [!check]- Rappel du calcul des dérivées de $C(q)$ (Bonus)
> Soit $C(q) = \frac{q^2}{200} + 1000$ :
> * **Coût marginal ($Cm$) :**
>   $$C'(q) = \frac{2q}{200} = \frac{q}{100} > 0 \quad (\forall q > 0)$$
> * **Dérivée seconde :**
>   $$C''(q) = \frac{1}{100} > 0$$

### Question 6 : Tableau de valeurs et interprétation

> [!camera] Capture vidéo recommandée (`36:00` et `45:25`)
> ![[capture_45_25_question_6_tableaux.png\|capture_45_25_question_6_tableaux.png]]
> *(Glissez ici une capture d'écran de la page finale Word à **45:25**)*

#### 1. Calculs des valeurs pour $n \in \{10, 20, 30, 40\}$

En utilisant les formules $Q(n) = 100 \cdot n^{1/2}$ et $C(q) = \frac{q^2}{200} + 1000$ :

* **Pour $n = 10$ salariés :**
  $$Q(10) = 100 \cdot 10^{1/2} \approx 316,23$$
  $$C(316,23) = \frac{316,23^2}{200} + 1000 = 500 + 1000 = 1500\text{ €}$$

* **Pour $n = 20$ salariés :**
  $$Q(20) = 100 \cdot 20^{1/2} \approx 447,21$$
  $$C(447,21) = \frac{447,21^2}{200} + 1000 = 1000 + 1000 = 2000\text{ €}$$

* **Pour $n = 30$ salariés :**
  $$Q(30) = 100 \cdot 30^{1/2} \approx 547,7$$
  $$C(547,7) = \frac{547,7^2}{200} + 1000 = 1500 + 1000 = 2500\text{ €}$$

* **Pour $n = 40$ salariés :**
  $$Q(40) = 100 \cdot 40^{1/2} \approx 632,45$$
  $$C(632,45) = \frac{632,45^2}{200} + 1000 = 2000 + 1000 = 3000\text{ €}$$

#### 2. Tableau récapitulatif n°1 (en fonction des paliers de salariés $n$)

| $n$ | $Q(n)$ | $C(q) = C(Q(n))$ | Formules Excel utilisées (`28:15` - `28:55`) |
| :---: | :---: | :---: | :--- |
| $10$ | $316,23$ | $1500$ | `100*10^(1/2)` puis `(F12^2)/200+1000` |
| $20$ | $447,21$ | $2000$ | `100*20^(1/2)` puis `(H10^2)/200+1000` |
| $30$ | $547,7$ | $2500$ | `100*30^(1/2)` puis `(J10^2)/200+1000` |
| $40$ | $632,45$ | $3000$ | `100*40^(1/2)` puis `(L10^2)/200+1000` |

#### 3. Discussion et interprétation des résultats

##### A. Relation linéaire entre le coût total et le nombre de salariés ($n$)

Si l'on compare la **1ère colonne ($n$)** et la **3ème colonne ($C$)**, l'augmentation du coût est parfaitement constante : chaque fois que l'on ajoute $10$ salariés, le coût total augmente exactement de $500\text{ €}$ ($1500 \to 2000 \to 2500 \to 3000$).

* **Explication :** Le coût total exprimé en fonction de $n$ est $C(Q(n)) = 50n + 1000$. C'est une relation **linéaire** par rapport à la masse salariale ($10\text{ salariés supplémentaires} \times 50\text{ €} = +500\text{ €}$).
* **Attention au piège :** Cela ne signifie pas que la fonction de coût $C(q)$ est linéaire ! La fonction de coût s'étudie par rapport à la **quantité produite** $q$, et elle est **convexe**.

##### B. Mise en évidence de la décroissance du produit marginal

Regardons la vitesse à laquelle augmente la production $Q(n)$ lorsque l'on ajoute $10$ salariés à chaque étape :

$$Q(20) - Q(10) = 447,21 - 316,23 = \mathbf{130,98}$$

$$Q(30) - Q(20) = 547,7 - 447,21 = \mathbf{100,5}$$

$$Q(40) - Q(30) = 632,45 - 547,7 = \mathbf{84,75}$$

On vérifie bien que :

$$Q(40) - Q(30) < Q(30) - Q(20) < Q(20) - Q(10)$$

La quantité totale augmente **de moins en moins vite** par rapport à $n$ car la fonction de production est **concave** (produit marginal décroissant).

##### C. Mise en évidence de la croissance du coût marginal (Tableau n°2)

Que se passe-t-il si l'entreprise souhaite maintenir le **même rythme d'augmentation de sa production** (c'est-à-dire augmenter à nouveau sa production de $+130,98$ unités après le palier des $20$ salariés, au lieu de se contenter de $+100,5$ unités) ?

1. **Calcul de la production cible $X$ :**
   $$X - Q(20) = 130,98$$
   $$X = 130,98 + 447,21 = \mathbf{578,19\text{ unités}}$$
   *(Pour produire $578,19$ unités au lieu de $547,7$, l'entreprise devra embaucher **plus de $30$ salariés**).*

2. **Calcul du coût total associé à $X = 578,19$ (Excel à `42:12`) :**
   $$C(578,19) = \frac{578,19^2}{200} + 1000 \approx \mathbf{2671\text{ €}}$$

3. **Tableau comparatif à variation de quantité constante ($\Delta q = +130,98$) :**

| $n$ | $Q(n)$ | $C(q) = C(Q(n))$ | Écart de quantité ($\Delta q$) | Coût marginal ($\Delta C$) |
| :---: | :---: | :---: | :---: | :---: |
| $10$ | $316,23$ | $1500$ | — | — |
| $20$ | $447,21$ | $2000$ | $+130,98$ | $2000 - 1500 = \mathbf{500\text{ €}}$ |
| $> 30$ *(env. $33,4$)* | $578,19$ | $2671$ | $+130,98$ | $2671 - 2000 = \mathbf{671\text{ €}}$ |

> [!quote] Reproduction de l'encadré récapitulatif de l'enseignant (`43:10`)
> $$\begin{aligned}
> 447,21 - 316,23 &= 578,19 - 447,21 \quad (\text{même augmentation de quantité : } +130,98) \\
> 2671 - 2000 &> 2000 - 1500 \quad (\text{le coût marginal augmente : } 671\text{ €} > 500\text{ €})
> \end{aligned}$$

> [!summary] Conclusion générale du cours
> C'est **exactement parce que la quantité produite augmente de moins en moins vite** lorsque l'on ajoute des salariés (produit marginal décroissant / fonction de production concave) que **le coût total augmente de plus en plus vite** lorsque l'on veut augmenter les quantités produites au même rythme (coût marginal croissant / fonction de coût convexe).