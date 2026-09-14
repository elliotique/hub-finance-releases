# Hub Finance — publications

Ce dépôt ne contient **aucun code source**. Il ne sert qu'à héberger les
installateurs de l'application de bureau Hub Finance.

## Pourquoi un dépôt séparé

Pour qu'une application se mette à jour toute seule, elle doit pouvoir
télécharger son installateur **sans identifiants**. Si les publications
vivaient dans un dépôt privé, il faudrait embarquer un jeton d'accès dans
l'exécutable — et le donner de fait à quiconque récupère le fichier.

Séparer les deux résout le problème : le code reste privé, seuls les binaires
sont publics.

## Installer

Les installateurs sont dans [Releases](../../releases). Prends le `.exe` le
plus récent.

Le fichier n'est pas signé numériquement : Windows SmartScreen affichera
« Éditeur inconnu » au premier lancement. Informations complémentaires →
Exécuter quand même.

## Mettre à jour

Une fois installée, l'application vérifie elle-même les nouvelles versions au
démarrage et les télécharge en fond. Rien ne s'installe sans confirmation —
le remplacement attend un clic dans Réglages → Mise à jour.
