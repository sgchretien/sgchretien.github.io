# Site académique — structure hiérarchique (version de travail)

L'accueil `index.html` présente les formations et permet de rechercher un cours.

## Arborescence
- `enseignement/licence/miashs/l1/`, `l2/`, `l3/` : séparés par année.
- `enseignement/licence/miashs/l2/statistiques-descriptives/1/` et `2/` : chaque cours a son dossier.
- `enseignement/licence/miashs/l2/statistiques-descriptives/2/td/` : TD et TP sous leur cours.
- `enseignement/master/miashs/m1/` et `m2/` : années séparées ; les sous-dossiers portent les noms des cours.
- `enseignement/autres/` : autres formations classées par programme.
- `cours/` : redirections de compatibilité avec les URLs de la première version.

## Mise en ligne

1. Dans Windows, décompresser le ZIP.
2. Faire une sauvegarde du dépôt GitHub existant (en téléchargeant son ZIP).
3. Importer **l'ensemble des dossiers `enseignement`, `assets`, `cours`** ainsi que le nouveau `index.html` à la racine du dépôt `sgchretien/sgchretien.github.io`.
4. Vérifier les chemins avant de valider le commit ; le navigateur peut être moins pratique qu'un client Git pour cette quantité de fichiers.
5. Laisser les autres fichiers du dépôt en place si vous ne savez pas à quoi ils servent.

## IMPORTANT : fidélité au site source

Cette version **améliore effectivement l'arborescence et le contenu répertorié**, mais ne reproduit **pas encore intégralement le texte** de toutes les pages de Google Sites.
Pour une copie fidèle, fournir un export Google Takeout de **Google Sites uniquement** (ou les fichiers HTML des pages). Aucun export de Google Drive n'est nécessaire.

Les PDF, Colab et autres documents restent à leur emplacement d'origine.
Le tableau `correspondance-migration.csv` permet de contrôler la migration page par page.

## Éviter les liens cassés

Les anciennes URL du premier site GitHub `/cours/...html` restent valides par le biais de redirections vers les nouveaux dossiers. Les pages Google Sites ne sont pas nécessaires à la navigation du nouveau site.
