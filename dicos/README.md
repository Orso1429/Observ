# Dictionnaires JSON pour Observ'

Ce dossier contient les dictionnaires partagés de l'application Observ', exportés au format JSON par le **Validateur Observ'** (fonction « Exporter les dicos en JSON »).

## Les 3 fichiers

Chaque fichier correspond à un dictionnaire de l'application :

| Fichier | Contenu |
|---|---|
| `dicos_signes.json` | Liste des signes cliniques |
| `dicos_pathologies.json` | Liste des pathologies / hypothèses diagnostiques |
| `dicos_problemes.json` | Liste des problèmes principaux |

## Comment les intégrer dans Observ'

1. Téléchargez les fichiers JSON depuis ce dossier (clic sur le fichier → bouton **Download** / « View raw »).
2. Placez-les dans le dossier `Download` de votre téléphone (ou laissez-les dans les téléchargements).
3. Dans Observ', ouvrez le menu → **« Importer les dicos JSON »** : l'application lit les 3 fichiers et fusionne les nouveaux signes, pathologies et problèmes avec vos dictionnaires existants (aucun doublon n'est créé).

## Contribution (projet collaboratif)

Vous avez enrichi vos dictionnaires avec de nouveaux signes ou pathologies ? Envoyez-les à la communauté :
1. Dans le **Validateur Observ'**, utilisez « Exporter les dicos en JSON » : vous recevez les 3 fichiers par mail.
2. Proposez-les par **Pull Request** sur ce dépôt, ou envoyez-les par mail au mainteneur qui les intégrera ici.

Les dictionnaires proposés ici sont le fruit des contributions des utilisateurs : chaque version intègre les ajouts de la communauté.
