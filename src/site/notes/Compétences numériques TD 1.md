---
{"dg-publish":true,"permalink":"/competences-numeriques-td-1/","ctime":"2026-11-12T01:04:49.789+01:00","mtime":"2026-11-12T18:01:15.141+01:00","dg-note-properties":{"date created":"2026-11-12, 1 04","date modified":"2026-11-12, 18 01","sector":"[[References/AES]]","semester":"[[References/S3]]","class":"[[References/Compétences numériques]]","form":"[[References/TD]]","part":"[[References/1]]"}}
---


<iframe src="/img/user/M.ADM518-Sem09-TT.pdf" width="100%" height="900px" title="M.ADM518-Sem09-TT.pdf" style="border:1px solid #ccc;"></iframe>

# TD 1 : Traitement de texte et structuration de document (LibreOffice Writer)
**Sujet support :** *Alcool et performances scolaires* (sujet prétexte pour la mise en forme)

---

## Livrables prêts à l'emploi (Dossier `Attachments/TD1 Livrables/`)
- **Document ODT (5 pages) :** `Attachments/TD1 Livrables/Alcool_et_performances_scolaires.odt`
- **Document PDF exporté (5 pages) :** `Attachments/TD1 Livrables/Alcool_et_performances_scolaires.pdf`
- **Fichier de concordance SDI :** `Attachments/TD1 Livrables/concordance_lexicale.sdi`
- **Archive ZIP finale à déposer :** `Attachments/TD1 Livrables/TD_Competences_Numeriques_Alcool_Performances.zip`
- **Images libres de droits :** dans `Attachments/TD1 Livrables/illustrations/` (CC0 et CC BY).

---

## Résolution synthétique du TD

### Exercice 1 : Préparation du contenu et choix des images
- **Catégorie :** Cadrage documentaire et licences libres
- **Méthode de référence :** Recherche de ressources libres de droits

> [!abstract] Énoncé synthétique
> Rédiger un document neutre de 5 pages avec au moins 3 illustrations libres de droits (légende, source et licence vérifiable). Anonymat obligatoire.

#### Résolution étape par étape
1. **Étape 1 - Contenu court et direct :** Rédaction d'un texte simple en 5 parties (Introduction, Constats généraux, Corrélations avec les notes, Facteurs explicatifs, Conclusion).
2. **Étape 2 - 3 illustrations libres de droits :**
   - *Illustration 1 :* Consommation des élèves 13-15 ans (PRB / OMS, licence CC0 Domaine Public).
   - *Illustration 2 :* Part des jeunes ayant consommé dans l'année (Our World in Data, licence CC BY 4.0).
   - *Illustration 3 :* Consommation et troubles associés (Our World in Data, licence CC BY 4.0).
3. **Étape 3 - Anonymat :** Aucun nom ni numéro d'étudiant dans le texte, les en-têtes ou le nom des fichiers.

> [!check]- À retenir
> Vérifier que chaque image a bien son lien de licence affiché sous la légende.

---

### Exercice 2 : Styles personnalisés et numérotation
- **Catégorie :** Styles de paragraphes
- **Méthode de référence :** Gestion des styles dans LibreOffice Writer

> [!abstract] Énoncé synthétique
> Définir des styles personnalisés pour les paragraphes et numéroter automatiquement les titres.

#### Résolution étape par étape
1. **Étape 1 - Création des styles (`F11`) :**
   - `Titre1_Perso` : Arial 13 pt, Gras, couleur bleue, espace avant/après.
   - `Titre2_Perso` : Arial 11 pt, Gras, couleur grise.
   - `Corps_Perso` : Arial 10.5 pt, justifié, retrait de 0.5 cm, interligne 1,25.
   - `Legende_Illustration_Perso` : Arial 9 pt, Gras, centré.
   - `Source_Illustration_Perso` : Arial 8 pt, Italique, centré.
2. **Étape 2 - Numérotation automatique :**
   - Menu `Outils > Numérotation des chapitres` : lier le Niveau 1 à `Titre1_Perso` et le Niveau 2 à `Titre2_Perso`.

> [!check]- À retenir
> Toujours passer par les styles (`F11`) au lieu de modifier la taille de police manuellement.

---

### Exercice 3 : Pagination et en-têtes conditionnels
- **Catégorie :** Styles de page
- **Méthode de référence :** Saut manuel avec bascule de style de page

> [!abstract] Énoncé synthétique
> Page 1 sans en-tête ni pied de page. Pages 2 et suivantes avec en-tête (titre court) et pied de page (numérotation).

#### Résolution étape par étape
1. **Étape 1 - Page 1 :** Style de page `Première page` (en-tête et pied de page désactivés).
2. **Étape 2 - Saut de page :** En bas de la page 1, faire `Insertion > Autres sauts > Saut manuel` > choisir *Style par défaut* (ou style de corps).
3. **Étape 3 - Pages 2 à 5 :**
   - *En-tête :* `Alcool et performances scolaires — Document d'étude` (aligné à droite).
   - *Pied de page :* `Page ` + Champ Numéro de page + ` sur ` + Champ Total de pages.

> [!check]- À retenir
> Ne pas faire un simple `Ctrl + Entrée`, sinon l'en-tête s'affiche aussi sur la page 1.

---

### Exercice 4 : Table des matières et table des illustrations
- **Catégorie :** Index automatiques
- **Méthode de référence :** Génération de tables automatiques

> [!abstract] Énoncé synthétique
> Insérer une table des matières automatique en page 1 et une table des illustrations en fin de document.

#### Résolution étape par étape
1. **Étape 1 - Table des matières (Page 1) :** Menu `Insertion > Table des matières et index > Table des matières…`.
2. **Étape 2 - Légendes d'images :** Clic droit sur chaque image > `Insérer une légende…` > Catégorie *Illustration*.
3. **Étape 3 - Table des illustrations (Page 5) :** `Insertion > Table des matières et index…` > Type : *Index des illustrations*.

---

### Exercice 5 : Index lexical et fichier SDI
- **Catégorie :** Indexation par fichier de concordance
- **Méthode de référence :** Fichier de concordance SDI

> [!abstract] Énoncé synthétique
> Créer un index alphabétique groupé par catégories à partir d'un fichier `.sdi` à rendre avec le document.

#### Résolution étape par étape
1. **Étape 1 - Fichier SDI simplifié (`concordance_lexicale.sdi`) :**
   - 17 termes clés classés par catégories simples (*Scolarité*, *Comportements*, *Santé*, *Organismes*, *Périodes*).
   - Format : `Mot;Entrée alternative;Catégorie;;0;1`
2. **Étape 2 - Insertion dans LibreOffice (Page 5) :**
   - `Insertion > Table des matières et index…` > Type : *Index lexical*.
   - Cocher *Fichier de concordance* > ouvrir `concordance_lexicale.sdi`.

---

### Exercice 6 : Finalisation et rendu ZIP
- **Catégorie :** Dépôt des livrables
- **Méthode de référence :** Export PDF et archivage ZIP

#### Résolution étape par étape
1. **Étape 1 - Export PDF :** Dans LibreOffice, faire `Fichier > Exporter au format PDF…` > enregistrer le PDF de 5 pages.
2. **Étape 2 - Archive ZIP :** Mettre dans `TD_Competences_Numeriques_Alcool_Performances.zip` :
   - Le fichier `.odt`
   - Le fichier `.pdf`
   - Le fichier `.sdi`
   - Le dossier `illustrations/`

---

## Méthodes mobilisées
- Recherche de ressources libres de droits : Exercice 1
- Gestion des styles dans LibreOffice Writer : Exercice 2
- Saut manuel avec bascule de style de page : Exercice 3
- Génération de tables automatiques : Exercice 4
- Fichier de concordance SDI : Exercice 5
- Export PDF et archivage ZIP : Exercice 6
