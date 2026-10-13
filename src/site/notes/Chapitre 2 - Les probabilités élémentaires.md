---
{"dg-publish":true,"permalink":"/chapitre-2-les-probabilites-elementaires/","tags":["AP/S2/tq","CM","maths","AP/S2"],"ctime":"2026-01-29T15:09:34.000+01:00","mtime":"2026-10-13T17:34:02.647+02:00","dg-note-properties":{"tags":["AP/S2/tq","CM","maths","AP/S2"],"class":"[[TQ]]","sector":"[[References/AES]]","semester":"[[S2]]","form":"[[References/CM]]","part":null,"date created":"2026-01-29, 15 09","date modified":"2026-09-21, 23 12"}}
---


# <font color="#8064a2">Chapitre 2 - Probabilités élémentaires</font>

<u>Exemple</u> :

- Considérons un ensemble de 300 lancers de dés et les résultats obtenus sont :

| Résultat | Effectif | Fréquence  observée | Fréquence théorique |
| -------- | -------- | ------------------- | ------------------- |
| 1        | 45       | 0,15                | ⅙                   |
| 2        | 52       | 0,1733              | ⅙                   |
| 3        | 51       | 0,17                | ⅙                   |
| 4        | 50       | 0,1667              | ⅙                   |
| 5        | 48       | 0,16                | ⅙                   |
| 6        | 54       | 0,18                | ⅙                   |
| total    | 300      | 1                   | 1                   |

- Les fréquences observées résultent de l'analyse a posteriori des données observées
- Les fréquences théoriques ou probabilités sont définies a priori et sans recourir aux observations


# <font color="#8064a2">1 - Expérience aléatoire</font>

> [!summary] Définition
> - Expérience dont le résultat n'est pas connue d'avance avec certitude

<u>Exemples</u> : 

 - Le lancer d'une pièce de monnaie
 - Le lancer d'un dé

## <font color="#8064a2">A - Ensemble fondamental d'une expérience aléatoire</font>

> [!summary] Définition
> - **L'ensemble fondamental**, noté Ω, est l'ensemble de tous les résultats possibles de l'expérience

<u>Exemples</u> : 

- Ω = {1, 2, 3, 4, 5, 6}
- Ω = {𝑃, 𝐹}

## <font color="#8064a2">B - Evénement d'une expérience aléatoire</font>

> [!summary] Définition
> - Un **événement** correspond à **un ou plusieurs** résultats d'une expérience
> - Mathématiquement c'est un **sous-ensemble** de l'ensemble fondamental

<u>Exemple</u> : 

- On lance *successivement* deux dés
  
	- l'ensemble fondamental :  
		Ω = {(1, 1), (1, 2), (1, 3),… , (2, 1), (2, 2),… ,(6, 5), (6, 6)}
		
	- exemples d'événements :  
		A : *"la somme des points est égale à 6"* = {(1,5), (2,4), (3,3), (2,4), (5,1)}  
		B : *"la somme des points est paire et inférieure à 6* = {(1,1), (1,3), (2,2), (3,1)}

## <font color="#8064a2">C - Evénements particuliers</font>

> [!summary] Définition
> 1. **L'événement impossible** est représenté par ∅ (ensemble vide), le sous-ensemble qui ne contient pas d'éléments
> 	- Evénement qui n'est **jamais réalisé**
> 2. **L'événement certain** est représenté par l'ensemble fondamental Ω
> 	- Evénement qui est **toujours réalisé**
> 3. L'événement **simple (ou élémentaire)** est un événement qui ne contient **qu'un seul résultat**

<u>Exemple :</u> 

1. A : *"le nombre de points irréalisable"* = {>6}
2. A : *"le nombre de points est inférieur à 7"* = {1,2,3,4,5,6} = Ω
3. A : *"le nombre de points inférieur à 2"* = {1}

## <font color="#8064a2">D - Opérations sur les événements</font>

<u>Expérience</u> : 
- Lancer d'un dé ⇒ Ω = {1,2,3,4,5,6}

### <font color="#8064a2">a - Négation</font>

Soient A et Ǡ deux événements : 

- A : *"obtenir un nombre de points pair"* 
	- A = {2,4,6}
	
- Ǡ : *"ne pas obtenir un nombre de points pair"* 
	- Ǡ = {1,3,5}

- Ǡ est appelé événement **complémentaire** de A
	- *Diagramme de Venn*

### <font color="#8064a2">b - Intersection </font>

Soient A et B deux évènements :

- A : *"obtenir un chiffre inférieur à cinq*
	- A = {1,2,3,4}
	  
- B : *"obtenir un chiffre impair"*
	- B = {1,3,5}
	  
- D'où l'événement : 
	- C : *"obtenir un chiffre inférieur à cinq **et** impair*
	- C = {1,3}
	  
- L'événement "A et B", noté A∩B, est appelé **intersection** de A et de B
	- *Diagramme de Venn* : A et B sont réalisés simultanément

### <font color="#8064a2">c - Union</font>

Soient A et B deux évènements :

- A : *"obtenir un chiffre inférieur à cinq*
	- A = {1,2,3,4}
	  
- B : *"obtenir un chiffre impair"*
	- B = {1,3,5}

- D'où l'événement : 
	- C : *"obtenir un chiffre inférieur à cinq **ou** impair*
	- C = {1,2,3,4,5}
	  
- L'événement "A ou B", noté A∪B, est appelé **union** entre A et B
	- *Diagramme de Venn* : au moins A ou B sont réalisés

### <font color="#8064a2">d - Partition</font>

Soient A, B et C trois événements :

- A, B et C forment une **partition** de Ω si : 
	- A, B et C ≠ ∅
	- A∩B = ∅, A∩C = ∅, B∩C = ∅
	- A∪B∪C = Ω

### <font color="#8064a2">e - Autre opérations - Propriétés</font>

Soient A, B et C trois événements (ou sous-ensembles de Ω) :

- Concept d'idempotence : 
	- A∪A = A A∩A = A 

- Loi d'identité : 
	- A∪∅ = A A∪Ω = Ω
	- A∩∅ = <u></u>∅ A∩Ω = A

- Complémentarité :
	- A∪Ā = Ω A∩Ā = ∅ 

- Loi commutative : 
	- A∪B = B∪A A∩B = B∩A 

- Loi associative : 
	- A∪(B∪C) = (A∪B)∪C
	- A∩(B∩C) = (A∩B)∩C 

- Distributivité : 
	- A∪(B∩C) = (A∪B)∩(A∪C)
	- A∩(B∪C) = (A∩B)∪(A∩C) 

- Loi de Morgan :
	- A∪B = A∩B A∩B = A∪B