# La bibliothèque IA de l'équipe

Ce dépôt garde les **skills**, les **prompts** et les **templates** de l'équipe projet. Chaque modification est enregistrée comme une **version** :
on voit qui a changé quoi, quand, et on peut toujours revenir en arrière.

| Dossier | Ce qu'il contient |
|---|---|
| `skills/pmia-gestion-projet/` | Le skill « gestion de projet » du kit PMIA (12 livrables, leurs règles et leurs checklists) |
| `skills/horizon-analyse-impact/` | Le skill d'analyse d'impact créé en atelier A6 (v1), enrichi en A9 (v2) |
| `skills/version-portable/` | Les mêmes consignes, à coller dans un GPT, un Gem ou un agent Copilot |
| `prompts/` | Les prompts testés de la formation, atelier par atelier |
| `templates/` | Les templates T1 à T11 (Word et Excel) |

## Publier ce dépôt sur GitHub (sans ligne de commande)
1. Sur github.com, cliquez sur **New repository**. Donnez-lui un nom (par exemple `bibliotheque-ia-projets`), choisissez **Private** (seule votre équipe y aura accès) ou **Public**, puis **Create repository**.
2. Sur la page du dépôt vide, cliquez sur **uploading an existing file**, glissez le contenu de ce dossier, écrivez un message (« Version initiale »), puis **Commit changes**.
3. Dans **Settings → Collaborators**, invitez les membres de l'équipe.

## Les gestes du quotidien
| Je veux… | Sur github.com |
|---|---|
| Modifier un skill | Ouvrir le fichier `SKILL.md`, cliquer sur le **crayon**, modifier, écrire un message qui dit ce qui change, **Commit changes** |
| Voir l'historique | Ouvrir le fichier, puis **History** : chaque version, son auteur, sa date |
| Voir ce qui a changé | Dans l'historique, cliquer sur une version : les lignes ajoutées en vert, les lignes retirées en rouge |
| Revenir en arrière | Ouvrir l'ancienne version du fichier (**History**, puis **…** → **View file**), copier son contenu, et l'enregistrer comme nouvelle version |
| Installer un skill dans Claude | Télécharger le dossier du skill en .zip (**Code → Download ZIP**, ou le fichier fourni dans le kit), puis Paramètres → Skills → Importer |

## Les règles de l'équipe
- On **lit un skill avant de l'installer**, surtout s'il vient d'un autre dépôt : que demande-t-il à l'IA ? envoie-t-il des données quelque part ?
- Chaque version a un message clair : « v2 : leçons du projet HORIZON (M7) ».
- Les données réelles des projets (noms, montants, contrats) ne vont **jamais** dans ce dépôt.
