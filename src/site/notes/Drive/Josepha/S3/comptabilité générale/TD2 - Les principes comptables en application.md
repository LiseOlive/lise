---
{"dg-publish":true,"permalink":"/drive/josepha/s3/comptabilite-generale/td-2-les-principes-comptables-en-application/","ctime":"2026-11-11T20:48:49.626+01:00","mtime":"2026-11-11T20:48:49.626+01:00","dg-note-properties":{"date created":"2026-11-11, 20 48","date modified":"2026-11-11, 20 48","sector":"[[References/Josepha]]","semester":"[[References/S3]]","class":"[[References/Compta]]","form":"[[References/TD]]","part":"[[References/2]]"}}
---


# TD N°2 : Application des Principes Comptables Fondamentaux

### Exercice 1 : Consultation en cabinet d'expertise comptable — Cas d'application des principes du PCG
- **Catégorie :** Analyse de conformité aux principes comptables généraux et qualification d'écritures
- **Méthode de référence :** [[Comptabilité financière#IV. Principes Comptables Fondamentaux\|Comptabilité financière (Principes Comptables Fondamentaux)]]

> [!abstract] Énoncé synthétique
> En tant que collaborateur d’un cabinet d’expertise comptable, un client soumet 15 cas concrets de gestion courante et de clôture d'exercice.  
> **Travail à faire :** Indiquer pour chacune des 15 opérations le traitement comptable à effectuer dans le strict respect des principes et règles du Plan Comptable Général (PCG).

---

#### Résolution étape par étape des 15 situations

##### Situation 1 : Dépréciation de marchandises abîmées en stock
- **Principe mobilisé :** **Principe de prudence** (art. 121-4 du PCG) et **règle des coûts historiques**.
- **Étape 1 - Identification des hypothèses :** Les marchandises ont subi une détérioration matérielle. Leur valeur actuelle (valeur vénale nette à la clôture) est devenue inférieure à leur valeur d'entrée (coût d'acquisition).
- **Étape 2 - Déroulé de l'argumentation :** Selon le principe de prudence, toute perte prévisible ou dépréciation d'actif constatée à la date d'inventaire doit obligatoirement être prise en compte pour ne pas transmettre d'incertitudes sur les exercices futurs et ne pas surévaluer l'actif.
- **Étape 3 - Résultat final et traitement comptable :** **Oui, on doit obligatoirement constater cette perte de valeur.** 
  - La valeur brute du stock au bilan reste inchangée à son coût historique.
  - On constate une dépréciation à la clôture au débit du compte `68173 Dotations aux dépréciations des stocks` par le crédit du compte `397 Dépréciations des stocks de marchandises`.

> [!check]- Remarques méthodologiques et pièges à éviter
> Ne jamais imputer directement la perte en diminuant le compte de stock brut `37` : la règle des coûts historiques impose de conserver la valeur d'origine et d'utiliser un compte d'actif soustractif de dépréciation (classe 39).

---

##### Situation 2 : Contrat de vente signé avant clôture mais livraison dans 2 mois
- **Principe mobilisé :** **Règle d'indépendance des exercices** (séparation des exercices) et **principe de réalisation du produit**.
- **Étape 1 - Identification des hypothèses :** Le contrat est signé en fin d'exercice $N$, mais le transfert physique et juridique de propriété (la livraison des biens) n'aura lieu qu'au cours de l'exercice $N+1$.
- **Étape 2 - Déroulé de l'argumentation :** Pour les ventes de biens corporels, le fait générateur comptable du produit est la **livraison** (remise de la marchandise au client) et non la conclusion de la commande. Les produits ne sont rattachés à un exercice que s'ils sont définitivement acquis au cours de cet exercice.
- **Étape 3 - Résultat final et traitement comptable :** **Non, le comptable ne peut pas enregistrer la vente sur l'exercice qui s'achève.**
  - Aucun chiffre d'affaires ne doit figurer au compte `707 Ventes de marchandises` en $N$.
  - Si une facture a déjà été établie par anticipation, il faut constater un produit constaté d'avance (PCA) à la clôture : Débit `707` par Crédit `487 Produits constatés d'avance`.
  - Si un acompte financier a été versé par le client, il s'enregistre en compte de tiers : `4191 Clients - Avances et acomptes reçus`.

> [!check]- Remarques méthodologiques et pièges à éviter
> Erreur fréquente : assimiler la signature juridique d'une promesse de vente au fait générateur comptable. En droit commercial et comptable, la vente de marchandises n'est parfaite et rattacheable au résultat que par la délivrance du bien.

---

##### Situation 3 : Acquisition d'une immobilisation hors zone euro et cours des devises
- **Principe mobilisé :** **Règle des coûts historiques** et **principe de régularité**.
- **Étape 1 - Identification des hypothèses :** Achat d'une immobilisation libellée en monnaie étrangère soumise à des fluctuations de change.
- **Étape 2 - Déroulé de l'argumentation :** Le principe de régularité impose d'enregistrer les opérations chronologiquement au jour de leur réalisation. La règle des coûts historiques impose d'inscrire l'immobilisation au bilan à sa valeur d'entrée en monnaie nationale (euros), convertie au cours de change au comptant du jour de l'acquisition. Ce coût historique est intangible.
- **Étape 3 - Résultat final et traitement comptable :** **Non, il est interdit d'attendre la clôture de l'exercice.**
  - L'immobilisation doit être enregistrée dès sa date de facturation/réception au débit de la classe 2 pour sa contre-valeur en euros au cours du jour.
  - À la clôture de l'exercice, la valeur de l'immobilisation ne bouge pas. Seule la dette résiduelle envers le fournisseur étranger (si elle n'est pas encore payée) fera l'objet d'un ajustement au cours de clôture (écart de conversion actif/passif et provision pour perte de change si perte latente).

> [!check]- Remarques méthodologiques et pièges à éviter
> L'immobilisation ne fait l'objet d'aucune réévaluation monétaire à la clôture. Seuls les comptes de tiers financiers (créances et dettes libellées en devises) sont réajustés au cours du 31 décembre.

---

##### Situation 4 : Changement de méthode d'évaluation des stocks (CUMP vers PEPS) pour accroître le résultat
- **Principe mobilisé :** **Principe de permanence des méthodes** et **principe de sincérité**.
- **Étape 1 - Identification des hypothèses :** L'entreprise souhaite substituer la méthode PEPS (FIFO) au CUMP dans le but délibéré d'augmenter le bénéfice affiché.
- **Étape 2 - Déroulé de l'argumentation :** Le principe de permanence des méthodes impose d'appliquer les mêmes règles d'évaluation d'un exercice à l'autre afin de permettre la comparabilité des comptes annuels. Une dérogation n'est autorisée qu'en cas de circonstances exceptionnelles ou d'évolution réglementaire procurant une meilleure information financière.
- **Étape 3 - Résultat final et traitement comptable :** **Non, le comptable ne peut pas changer de méthode d'évaluation.**
  - La recherche d'un meilleur résultat relève d'une manipulation des comptes et viole le principe de sincérité et d'image fidèle. L'évaluation doit continuer d'être opérée selon le Coût Moyen Unitaire Pondéré (CUMP).

> [!check]- Remarques méthodologiques et pièges à éviter
> L'optimisation fiscale ou la présentation d'un bilan plus flatteur auprès des banques ne constituent jamais un motif légitime de changement de méthode comptable.

---

##### Situation 5 : Paiement d'une contravention en espèces et non-inscription en comptabilité
- **Principe mobilisé :** **Principe de régularité**, **principe de sincérité** et **principe d'exhaustivité** (transparence comptable).
- **Étape 1 - Identification des hypothèses :** Paiement en liquide d'une amende pour infraction routière commise par un chauffeur salarié durant son service.
- **Étape 2 - Déroulé de l'argumentation :** Toute transaction financière modifiant le patrimoine ou la trésorerie de l'entité doit être fidèlement consignée sans omission volontaire. Ne pas enregistrer une dépense en espèces correspond à dissimuler une sortie de fonds (« caisse noire »), ce qui constitue un délit pénal et une fraude comptable.
- **Étape 3 - Résultat final et traitement comptable :** **La proposition est formellement illégale et doit être rejetée.**
  - L'opération doit obligatoirement être enregistrée :
    - **Débit :** `6712 Pénalités, amendes fiscales et pénales`
    - **Crédit :** `53 Caisse`
  - *Remarque fiscale :* Cette amende, bien que régulièrement enregistrée en charge, n'est pas déductible du résultat fiscal et devra faire l'objet d'une réintégration extra-comptable.

---

##### Situation 6 : Terrain acquis 25 000 € en 1998 et estimé à 45 000 €
- **Principe mobilisé :** **Règle des coûts historiques** et **principe de prudence**.
- **Étape 1 - Identification des hypothèses :** Constat d'une appréciation foncière favorable : la valeur vénale de marché ($45\,000\ \text{€}$) excède le coût d'acquisition historique ($25\,000\ \text{€}$).
- **Étape 2 - Déroulé de l'argumentation :** En vertu de la règle des coûts historiques, les biens acquis restent enregistrés à leur valeur nominale d'achat hors taxe. Selon le principe de prudence, les plus-values potentielles (latentes) ne doivent jamais être comptabilisées tant qu'elles ne sont pas définitivement réalisées par une vente effective.
- **Étape 3 - Résultat final et traitement comptable :** **On n'inscrit aucune modification en comptabilité.**
  - Le terrain demeure inscrit à l'actif du bilan pour sa valeur historique de **$25\,000\ \text{€}$** (compte `211 Terrains`).
  - La plus-value de $20\,000\ \text{€}$ ne sera reconnue qu'au moment de la cession du bien.

> [!check]- Remarques méthodologiques et pièges à éviter
> Ne pas confondre une dépréciation (perte de valeur probable, obligatoire à inscrire) et une appréciation (gain potentiel, interdit d'inscription en vertu de la dissymétrie du principe de prudence).

---

##### Situation 7 : Deux comptes bancaires (l'un débiteur de 45 000 €, l'autre créditeur de 35 000 €)
- **Principe mobilisé :** **Règle de non-compensation**.
- **Étape 1 - Identification des hypothèses :** Existence conjointe d'un compte bancaire positif ($+45\,000\ \text{€}$, solde débiteur en compta) et d'un compte à découvert ($-35\,000\ \text{€}$, solde créditeur en compta).
- **Étape 2 - Déroulé de l'argumentation :** Le PCG interdit formellement de compenser les éléments d'actif et de passif. Présenter un solde net débiteur de $10\,000\ \text{€}$ dissimulerait l'existence d'une dette à court terme et donnerait une image trompeuse de la liquidité et de l'endettement réel de l'entreprise.
- **Étape 3 - Résultat final et traitement comptable :** **La proposition du dirigeant est rejetée.**
  - **À l'Actif circulant (Disponibilités) :** inscrire **$45\,000\ \text{€}$** (compte `512 Banque`).
  - **Au Passif (Dettes financières / Concours bancaires courants) :** inscrire **$35\,000\ \text{€}$** (compte `519 Concours bancaires courants` ou compte `512` à découvert rattaché aux dettes financières).

---

##### Situation 8 : Véhicule utilitaire financé par contrat de crédit-bail
- **Principe mobilisé :** **Principe de régularité** et **primauté de la propriété juridique** en comptabilité générale française (PCG).
- **Étape 1 - Identification des hypothèses :** Utilisation d'un matériel de transport dans le cadre d'un contrat de location avec option d'achat (*crédit-bail*).
- **Étape 2 - Déroulé de l'argumentation :** En comptabilité générale française, le bilan recense le patrimoine juridique de l'entreprise. Tant que l'option d'achat n'est pas levée, la société bailleresse reste seule propriétaire légale du véhicule.
- **Étape 3 - Résultat final et traitement comptable :** **Non, le véhicule ne doit pas figurer à l'actif du bilan.**
  - Les loyers périodiques payés sont enregistrés en charges d'exploitation au compte `6122 Redevances de crédit-bail mobilier`.
  - La valeur du matériel et les engagements futurs de redevances sont obligatoirement mentionnés dans **l'annexe comptable** (engagements hors-bilan).

---

##### Situation 9 : Portefeuille de VMP (250 titres à 35 € et 200 titres à 40 € avec cours d'inventaire à 36 €)
- **Principe mobilisé :** **Principe de prudence** et **règle de non-compensation**.
- **Étape 1 - Identification des hypothèses :**
  - Lot 1 : 250 titres acquis à $35\ \text{€}$. Cours d'inventaire = $36\ \text{€} \implies$ Plus-value latente de $(36 - 35) \times 250 = +\mathbf{250\ \text{€}}$.
  - Lot 2 : 200 titres acquis à $40\ \text{€}$. Cours d'inventaire = $36\ \text{€} \implies$ Moins-value latente de $(36 - 40) \times 200 = -\mathbf{800\ \text{€}}$.
- **Étape 2 - Déroulé de l'argumentation :**
  - Selon le **principe de prudence**, la plus-value latente de $250\ \text{€}$ n'est jamais enregistrée.
  - En vertu de la **règle de non-compensation stricte**, on ne compense pas le gain virtuel du lot 1 avec la perte du lot 2 : la dépréciation doit couvrir l'intégralité de la perte latente du second lot.
  - *Précision PCG (art. 221-6) :* Le PCG prévoit une exception autorisant la compensation globale pour des titres de même nature conférant des droits identiques. Dans ce cadre toléré, la dépréciation nette globale serait de $800 - 250 = \mathbf{550\ \text{€}}$.
- **Étape 3 - Résultat final et traitement comptable :** **Oui, le comptable doit impérativement constater la perte de valeur du second lot.**
  - En application stricte : Débit `6866 Dotations aux dépréciations des éléments financiers` pour **$800\ \text{€}$**, Crédit `590 Dépréciations des VMP` pour **$800\ \text{€}$**.
  - Si l'enseignant retient la compensation admise par catégorie homogène de titres : Dépréciation de **$550\ \text{€}$**.

---

##### Situation 10 : Passage de l'amortissement linéaire à un amortissement par unités d'œuvre à conditions d'utilisation inchangées
- **Principe mobilisé :** **Principe de permanence des méthodes**.
- **Étape 1 - Identification des hypothèses :** Souhait de modifier les modalités de calcul de l'amortissement du matériel industriel alors que son rythme d'utilisation effectif reste strictement identique.
- **Étape 2 - Déroulé de l'argumentation :** Le mode d'amortissement traduit le rythme de consommation prévisible des avantages économiques attendus du bien. Un changement de plan d'amortissement ne peut être opéré qu'en cas de modification notable et objective des conditions réelles d'exploitation.
- **Étape 3 - Résultat final et traitement comptable :** **Non, le dirigeant ne peut pas modifier la méthode d'amortissement.**
  - Les conditions d'utilisation étant inchangées, l'entreprise doit obligatoirement poursuivre l'amortissement linéaire initialement retenu.

---

##### Situation 11 : Régularisation au 31 décembre de la prime d'assurance annuelle payée le 1er juin
- **Principe mobilisé :** **Règle d'indépendance des exercices** (séparation des exercices).
- **Étape 1 - Identification des hypothèses :** Paiement le 01/06/$N$ d'une prime couvrant une période de 12 mois (du 01/06/$N$ au 31/05/$N+1$).
- **Étape 2 - Déroulé de l'argumentation :** Seules les charges afférentes aux 7 mois écoulés en $N$ (du 01/06 au 31/12) doivent impacter le résultat de l'exercice $N$. La fraction correspondant aux 5 mois de l'exercice suivant (du 01/01 au 31/05/$N+1$) représente une charge payée d'avance qu'il faut neutraliser.
- **Étape 3 - Résultat final et traitement comptable :** **Oui, une régularisation est obligatoire à l'inventaire au 31 décembre $N$.**
  - Calcul de la régularisation : $\text{Montant à neutraliser} = \text{Prime annuelle} \times \frac{5}{12}$.
  - Écriture au 31/12/$N$ :
    - **Débit :** `486 Charges constatées d'avance (CCA)`
    - **Crédit :** `616 Primes d'assurances`

---

##### Situation 12 : Contrôle fiscal en cours et risque de redressement pour erreurs d'imputation
- **Principe mobilisé :** **Principe de prudence** et **principe d'indépendance des exercices**.
- **Étape 1 - Identification des hypothèses :** Contrôle fiscal intervenu au 4e trimestre; des erreurs d'imputation substantielles de charges ont été constatées avant la clôture, rendant le redressement hautement probable.
- **Étape 2 - Déroulé de l'argumentation :** Un événement né au cours de l'exercice crée une obligation de l'entreprise envers un tiers (l'administration fiscale) qui se traduira très probablement par une sortie nette de ressources sans contrepartie. Le principe de prudence oblige à anticiper cette charge future dès l'exercice où le fait générateur est apparu.
- **Étape 3 - Résultat final et traitement comptable :** **L'entreprise doit obligatoirement constituer une provision pour risques à la clôture.**
  - Le comptable doit estimer le montant probable du redressement et passer l'écriture suivante au 31/12 :
    - **Débit :** `6875 Dotations aux provisions exceptionnelles` (ou `6815`)
    - **Crédit :** `1518 Autres provisions pour risques` (ou `151 Provisions pour risques`)

---

##### Situation 13 : Règlement d'une prestation de services reçue au moyen d'une livraison de marchandises
- **Principe mobilisé :** **Règle de non-compensation**.
- **Étape 1 - Identification des hypothèses :** Prestation de services effectuée par un tiers rémunérée par la remise directe de stocks de marchandises (opération de troc / dation en paiement).
- **Étape 2 - Déroulé de l'argumentation :** Il est strictement interdit d'annuler directement la dette de service par la sortie de marchandises sans enregistrer les deux composantes économiques. Chaque flux doit être tracé : un achat de prestation et une vente de marchandises.
- **Étape 3 - Résultat final et traitement comptable :** **Deux écritures distinctes doivent être constatées :**
  1. Enregistrement de la charge de service :
     - **Débit :** `6... Charges externes` et `44566 TVA déductible`
     - **Crédit :** `401 Fournisseurs`
  2. Enregistrement de la vente de marchandises :
     - **Débit :** `411 Clients`
     - **Crédit :** `707 Ventes de marchandises` et `44571 TVA collectée`
  3. Dénouement du paiement par compensation juridique :
     - **Débit :** `401 Fournisseurs` par le **Crédit :** `411 Clients`.

---

##### Situation 14 : Prêt sans intérêt de 25 000 € accordé à un salarié remboursable sur 5 ans et inflation
- **Principe mobilisé :** **Règle des coûts historiques** (nominalisme monétaire) et **principe de sincérité**.
- **Étape 1 - Identification des hypothèses :** Prêt de $25\,000\ \text{€}$ consenti à un collaborateur remboursable sur une durée moyenne de 5 ans en période d'inflation.
- **Étape 2 - Déroulé de l'argumentation :** Les créances sont enregistrées et conservées au bilan pour leur valeur nominale d'origine en euros courants. L'érosion monétaire due à l'inflation ne donne lieu à aucun réajustement de la valeur comptable de la créance.
- **Étape 3 - Résultat final et traitement comptable :**
  - Le prêt est enregistré pour son montant nominal de **$25\,000\ \text{€}$** : Débit `274 Prêts` (actif immobilisé) par Crédit `512 Banque`.
  - **Non, il est interdit de réévaluer le montant du prêt en fonction de l'inflation.**
  - Les remboursements viendront diminuer au pair la créance (au crédit du compte `274`).

---

##### Situation 15 : Indemnisation probable de 5 000 € d'un client suite à un litige (jugement non encore rendu)
- **Principe mobilisé :** **Principe de prudence** et **principe d'indépendance des exercices**.
- **Étape 1 - Identification des hypothèses :** Litige engagé contre un client lors de l'exercice. L'estimation d'un tiers qualifié (l'avocat de l'entreprise) chiffre le risque d'indemnisation à $5\,000\ \text{€}$.
- **Étape 2 - Déroulé de l'argumentation :** Selon le principe de prudence, une charge probable dont le montant ou l'échéance ne sont pas connus avec exactitude doit faire l'objet d'une provision dès que l'événement générateur a eu lieu durant l'exercice. L'absence de prononcé du jugement ne fait pas obstacle à la comptabilisation de la provision.
- **Étape 3 - Résultat final et traitement comptable :** **Oui, il faut impérativement enregistrer cette somme à la clôture de l'exercice.**
  - Constatation d'une provision pour litiges au 31/12 :
    - **Débit :** `6815 Dotations aux provisions pour risques et charges d'exploitation` pour **$5\,000\ \text{€}$**
    - **Crédit :** `1511 Provisions pour litiges` pour **$5\,000\ \text{€}$**

---

## Synthèse transversale des principes du PCG mobilisés

| Principe comptable | Situations concernées | Règle d'application essentielle |
| :--- | :---: | :--- |
| **Principe de prudence** | 1, 6, 9, 12, 15 | Anticipation obligatoire des pertes et dépréciations probables ; interdiction absolue d'inscrire des gains latents. |
| **Règle de non-compensation** | 7, 9, 13 | Interdiction de fusionner les actifs et passifs, ou charges et produits (les flux bruts doivent apparaître). |
| **Règle d'indépendance des exercices** | 2, 11, 12, 15 | Rattachement des produits et charges à l'exercice de leur fait générateur économique, indépendamment des flux monétaires. |
| **Règle des coûts historiques** | 1, 3, 6, 14 | Maintien des éléments d'actif et créances à leur valeur nominale d'entrée en euros, sans indexation sur le marché ou l'inflation. |
| **Principe de permanence des méthodes** | 4, 10 | Continuité obligatoire des méthodes d'évaluation et d'amortissement d'une année sur l'autre pour assurer la comparabilité. |
| **Principe de régularité et sincérité** | 3, 5, 8 | Conformité stricte aux lois et arrêtés du PCG, traduction de bonne foi de la réalité sans dissimulation ni omission. |

---

## Méthodes et fiches mobilisées
- [[Comptabilité financière#IV. Principes Comptables Fondamentaux\|Comptabilité financière]] : Exercice 1 (Situations 1 à 15)
- [[Drive/Josepha/S3/comptabilité générale/chap 1 - introduction à la comptabilité/cours/Chapitre 1 - introduction à la comptabilité\|Chapitre 1 - introduction à la comptabilité]] : Exercice 1 (Cadre général et principes)
