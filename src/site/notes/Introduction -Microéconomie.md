---
{"dg-publish":true,"permalink":"/introduction-microeconomie/","tags":["AES/S3/micro","CM","éco","AES/S3"],"ctime":"2026-09-09T14:17:25.480+02:00","mtime":"2026-10-13T17:34:02.174+02:00","dg-note-properties":{"tags":["AES/S3/micro","CM","éco","AES/S3"],"class":"[[References/Micro]]","sector":"[[References/AES]]","semester":"[[References/S3]]","form":"[[References/CM]]","part":"[[References/1]]","date created":"2026-09-09, 14 17","date modified":"2026-09-23, 21 15"}}
---


# I. Introduction - Microéconomie de la production

# 1. Rappels fondamentaux du marché

* **Loi de la demande** : Si le prix augmente ($p_1 > p_2$), la quantité demandée diminue ($Q_1 < Q_2$).
* **Loi de l'offre** : Si le prix augmente ($p_1' > p_2'$), la quantité offerte augmente ($Q_2' > Q_1'$).
* **Équilibre du marché** : Déterminé par le point $(p^*, Q^*)$ à l'intersection des courbes d'offre et de demande.
  
* **Monopsone** : Structure de marché où la demande détient un pouvoir de marché sur l'offre (ex. marché du travail).

# 2. Exercice d'application : Offre, demande et équilibre de marché
Les fonctions de marché initiales sont :
* **Demande** : $D(p) = 100 - p$
* **Offre** : $O(p) = \frac{1}{2}p$
## A. Fonctions inverses de la demande et de l'offre
* **Fonction inverse de la demande** $P(Q)$ :  
  $$Q = 100 - P(Q) \implies \mathbf{P(Q) = 100 - Q}$$  
  ![schema-1-demande.png\|405](/img/user/Attachments/schema-1-demande.png)
  
  
* **Fonction inverse de l'offre** $P_o(Q)$ :  
  $$Q = \frac{1}{2}P_o(Q) \implies \mathbf{P_o(Q) = 2Q}$$

![schema-2-offre.png\|421](/img/user/Attachments/schema-2-offre.png)

## B. Détermination du prix et de la quantité d'équilibre $(p^*, Q^*)$

* **Méthode 1 (Égalité des quantités $D(p^*) = O(p^*)$)** :  
  $$100 - p^* = \frac{1}{2}p^* \implies \frac{3}{2}p^* = 100 \implies \mathbf{p^* = \frac{200}{3} \approx 66{,}67}$$  
  $$\mathbf{Q^*} = D(p^*) = 100 - \frac{200}{3} = \mathbf{\frac{100}{3} \approx 33{,}33}$$

* **Méthode 2 (Égalité des prix $P(Q^*) = P_o(Q^*)$)** :  
  $$100 - Q^* = 2Q^* \implies 3Q^* = 100 \implies \mathbf{Q^* = \frac{100}{3}}$$  
  $$\mathbf{p^*} = P_o(Q^*) = 2 \times \frac{100}{3} = \mathbf{\frac{200}{3}}$$
  
![schema-3-equilibre.png\|470](/img/user/Attachments/schema-3-equilibre.png)


# 3. Fonction de profit et maximisation du producteur

## A. Formulation du profit
Le profit de l'entreprise ($\Pi$) est la différence entre les recettes et les coûts totaux :  
$$\Pi(Q) = Q \times p - C(Q)$$  
Où $C(Q)$ représente la **fonction de coût**. La fonction de profit est **concave**, présentant son maximum au sommet situé en $Q^*$.

![schema-4-profit.png\|466](/img/user/Attachments/schema-4-profit.png)

## B. Condition du Premier Ordre (CPO)
Pour maximiser le profit, la dérivée première du profit par rapport à la quantité doit être nulle :  
$$\frac{\partial \Pi}{\partial Q^*} = 0 \implies \frac{\partial (Q^* \times p - C(Q^*))}{\partial Q^*} = 0$$  
$$\frac{\partial (Q^* \times p)}{\partial Q^*} - \frac{\partial C(Q^*)}{\partial Q^*} = 0 \implies \mathbf{p - C'(Q^*) = 0} \implies \mathbf{p = C'(Q^*)}$$

* **Rappels de dérivées** :
  * Si $f(X) = aX \implies f'(X) = a$
  * Si $f(X) = X^n \implies f'(X) = nX^{n-1}$


# 4. Courbe d'offre individuelle de l'entreprise


![schema-5-cout-marginal.png\|456](/img/user/Attachments/schema-5-cout-marginal.png)

La **courbe d'offre** de l'entreprise correspond à sa fonction de **coût marginal** $C'(Q)$ :  
$$P_o(Q) = C'(Q)$$

## Exercice

Pour une fonction de coût $C(Q) = \frac{1}{2}Q^2$ :
* **Coût marginal** : $C'(Q) = \frac{1}{2} \times 2Q = Q$
* **Fonction d'offre de l'entreprise** : $\mathbf{P_o(Q) = Q}$

![Pasted image 20260920125021.png](/img/user/Attachments/Pasted%20image%2020260920125021.png)