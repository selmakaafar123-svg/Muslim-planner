# NOOR V3 — Planner quotidien, spirituel et financier

NOOR V3 conserve le style doux beige / vert sauge de la première version et rassemble les fonctionnalités dans six espaces : Accueil, Planner, Habit Tracker, Budget, Spiritualité et Achats.

## Fonctionnalités
- Accueil : liste quotidienne heure par heure avec cases à cocher pour les prières, adhkar, lecture, habitudes et tâches personnelles. Aya du jour et explication simplifiée.
- Planner : calendrier annuel, mensuel, hebdomadaire et journalier. Tâches personnelles datées et horaires.
- Habit Tracker : habitudes personnalisables, historique sur 30 jours et taux de réalisation du jour, de la semaine et du mois.
- Budget : revenus, dépenses, solde/épargne, objectif mensuel, calendrier des dépenses quotidiennes, répartition par catégorie et historique.
- Spiritualité : lecteur des 114 sourates (texte arabe et traduction FR/EN téléchargés à la demande), douas, adhkar matin/soir/après prière avec compteur, et hadiths avec références.
- Achats : liste de courses à cocher, supprimer et nettoyer.
- Interface FR/EN/AR avec direction RTL en arabe.
- Enregistrement local dans le navigateur et export JSON.

## Lancer sur Windows
1. Extraire le ZIP.
2. Ouvrir le dossier `NOOR_V3`.
3. Lancer `python -m http.server 8000`.
4. Ouvrir `http://localhost:8000`.

Ne pas ouvrir directement le fichier via `file://`. L'installation PWA et le cache hors ligne nécessitent localhost ou HTTPS.

## Installer sur téléphone
Héberger le dossier sur un service HTTPS (GitHub Pages, Netlify ou Vercel).
- Android : Chrome → menu → Installer l'application / Ajouter à l'écran d'accueil.
- iPhone : Safari → Partager → Sur l'écran d'accueil.

## Données et limites
Les tâches, habitudes, coches, transactions et listes sont stockées localement sur cet appareil. Exporter régulièrement le fichier JSON depuis le pied de page.
Le lecteur du Coran télécharge le texte et les traductions depuis AlQuran.cloud à la demande. Les sourates déjà consultées peuvent être mises en cache dans le stockage local, selon l'espace disponible. Une connexion est nécessaire pour le premier téléchargement.
L'aya du jour utilise une petite sélection de versets avec une explication pédagogique résumée, et non un tafsir exhaustif. Les douas, adhkar et hadiths fournis constituent une sélection initiale ; les références sont indiquées lorsque disponibles. Pour l'étude religieuse approfondie, se référer aux sources et commentaires reconnus.
Les horaires de prières dans le programme quotidien sont des horaires indicatifs personnalisables dans une future version ; cette version ne calcule pas encore les horaires selon la ville ou la méthode.
Le budget utilise une devise sélectionnée globalement (TND, EUR, USD) et n'effectue pas de conversion de devises.
