# Equena — V4.24.1

Prototype de suivi des équidés, publié sous forme de site statique avec GitHub Pages.

## Base conservée

La version publiée utilise `index.html` et conserve le fonctionnement de la V4.24.1, notamment les dépenses multi-équidés, leur répartition au centime près et les montants individuels.

Deux ajustements de préparation uniquement : un exemple de nom a été remplacé par un nom fictif et une ancienne référence à une image externe manquante utilise désormais le symbole SVG déjà intégré. La V4.24.1 d’origine est conservée séparément hors du dépôt.

## Fichiers utiles

- `index.html` : application, styles, scripts, icônes et polices intégrés.
- `.nojekyll` : publication directe des fichiers statiques.
- `.gitignore` : seuls les fichiers de publication sont autorisés par défaut.
- `OFL-Baloo2.txt` : licence des polices Baloo 2 intégrées.

Aucune installation ni compilation n’est nécessaire. Les images, documents, exports JSON/PDF, captures de validation et jeux de test des utilisateurs ne doivent pas être ajoutés au dépôt.

## Données et sauvegardes

Les données sont enregistrées dans le navigateur utilisé, sous la clé `equiV3`. Aucun backend, compte applicatif, service d’analyse ou système de synchronisation cloud n’est ajouté. Une nouvelle installation démarre vide.

Le site publié et le fichier HTML local ont des stockages distincts. Le PC et l’iPhone ne se synchronisent pas. Pour transférer des données, exporter une sauvegarde JSON depuis les paramètres de l’ancienne version, puis l’importer dans la version publiée. Cette sauvegarde reste privée et ne doit jamais être déposée sur GitHub.

Conserver régulièrement une sauvegarde JSON : effacer les données du navigateur peut supprimer les données locales. Ne pas utiliser la navigation privée pour un suivi durable. Les éventuelles photos distantes présentes dans une sauvegarde importée peuvent être chargées depuis leur adresse d’origine.

## Publication GitHub Pages

Dans Settings → Pages, choisir **Deploy from a branch**, branche **main**, dossier **/(root)**, puis Save. Attendre le succès du déploiement et utiliser l’URL affichée par GitHub. Le site GitHub Pages est public.

## Essai sur iPhone

Ouvrir l’URL publiée dans Safari. Le menu Partager permet de choisir « Sur l’écran d’accueil ». Aucune prise en charge hors ligne garantie n’est ajoutée à cette version.

Vérifier sur l’appareil : création d’un équidé, dépense simple, répartition globale de 100 € sur trois équidés, montants individuels et total, budget par équidé et global, modification/suppression d’une seule dépense, export/import JSON, puis conservation des données après fermeture et réouverture.
