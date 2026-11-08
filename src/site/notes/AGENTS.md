---
{"dg-publish":true,"permalink":"/agents/","ctime":"2026-11-07T22:40:51.214+01:00","mtime":"2026-11-07T22:50:48.213+01:00","dg-note-properties":{"date created":"2026-11-07, 22 40","date modified":"2026-11-07, 22 50","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null}}
---


# Instructions pour la gestion des notes Obsidian

## 1. Syntaxe et gestion des liens internes (Wikilinks)
- **Format obligatoire :** Utilise exclusivement la syntaxe des wikilinks Obsidian : `[[Nom de la note]]` ou `[[Nom de la note|Texte d'ancrage]]`.
- **Prodiction des liens Markdown :** N'utilise JAMAIS la syntaxe `[texte](chemin/note.md)` pour lier des notes entre elles.
- **Interdiction des pages fantômes :** 
  - Ne crée JAMAIS de lien vers une note qui n'existe pas encore dans le coffre, sauf si tu crées le fichier correspondant dans la même action.
  - Vérifie systématiquement l'arborescence avant de lier une note. Si le concept mentionné n'a pas de note dédiée existante, laisse le texte en clair sans crochets.

## 2. Périmètre et restrictions de sécurité
- **Répertoire protégé `.obsidian/` :** 
  - Il est strictement interdit de modifier, renommer, créer ou supprimer des fichiers ou des dossiers situés dans `.obsidian/`.
  - Ce dossier est réservé au système d'Obsidian et doit être totalement ignoré lors des opérations de tri, de nettoyage ou de restructuration.
- **Fichiers éligibles :** Tes actions doivent s'appliquer exclusivement aux fichiers de contenu utilisateur (Markdown `.md`, images et pièces jointes).
  
## 3. Standardisation du Frontmatter YAML (Propriétés)
Chaque note créée ou modifiée doit obligatoirement commencer par un en-tête YAML respectant scrupuleusement la structure ci-dessous :

```yaml
---
date created: "YYYY-MM-DD, HH mm"
date modified: "YYYY-MM-DD, HH mm"
sector: 
semester: 
class: 
form: 
part: 
dg-publish: true
---