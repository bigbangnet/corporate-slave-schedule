# 🕒 Calcul d'heures

Petite application pour calculer ses heures de travail de la semaine et voir s'il atteint son objectif. Elle fonctionne **sans Internet** et s'installe sur le téléphone comme une vraie app.

## Fonctionnalités

- Saisie de l'heure de début, de fin et du temps de dîner pour chaque jour
- Total de la semaine, avec ce qu'il manque (ou le surplus) par rapport à l'objectif hebdomadaire (40 h par défaut, modifiable)
- Calcul automatique de l'heure de fin d'une journée pour atteindre l'objectif
- Possibilité de désactiver les jours non travaillés
- Enregistrement de la semaine et historique des semaines passées
- Mode sombre automatique
- Fonctionne hors ligne une fois installée

## Installation (Android)

1. Ouvre le lien de l'app dans Chrome
2. Menu ⋮ → **Installer l'application**
3. L'icône apparaît sur l'écran d'accueil

Après la première ouverture, plus besoin d'Internet.

## Données

Tout est sauvegardé localement sur l'appareil. Rien n'est envoyé sur un serveur.
Attention : vider les données de Chrome ou désinstaller l'app efface l'historique.

## Technologie

HTML, CSS et JavaScript, sans dépendance. Une PWA (manifest + service worker).

## Licence

MIT, voir le fichier `LICENSE`.
