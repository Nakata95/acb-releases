# AniCard Battle — Téléchargements

**AniCard Battle** est un jeu de cartes à collectionner inspiré de Shadowverse, basé sur des univers et des personnages
d'anime. Ce dépôt contient uniquement les **versions jouables** du jeu (Windows et Android). Le jeu est gratuit, sans achat
en argent réel : les Gemmes et les Panneaux se gagnent en jouant.

## Télécharger

Rendez-vous sur la page **[Releases](../../releases/latest)** et téléchargez le fichier de votre appareil :

| Appareil | Fichier |
|---|---|
| Windows | `AniCardBattle.exe` |
| Android | `AniCardBattle.apk` |

Chaque fichier est accompagné de sa somme de contrôle (`.sha256`) pour vérifier qu'il n'a pas été modifié.

## Installer

**Windows**
1. Téléchargez `AniCardBattle.exe`.
2. Double-cliquez pour lancer le jeu. Aucune installation n'est nécessaire.
3. Windows peut afficher un avertissement à la première ouverture, parce que l'application n'est pas distribuée par un
   éditeur connu : choisissez « Informations complémentaires », puis « Exécuter quand même ».

**Android**
1. Téléchargez `AniCardBattle.apk` sur votre téléphone.
2. Ouvrez le fichier. Android vous demandera d'autoriser l'installation d'applications depuis cette source : acceptez
   (réglage « Sources inconnues » ou « Installer des applis inconnues »).
3. Lancez AniCard Battle depuis votre liste d'applications.

## Vérifier le fichier (facultatif)

Comparez la somme SHA-256 du fichier téléchargé avec celle du fichier `.sha256` de la release.

Sous Windows (PowerShell) :

```powershell
Get-FileHash .\AniCardBattle.exe -Algorithm SHA256
```

Les deux valeurs doivent être identiques. Sinon, retéléchargez le fichier.

## Mises à jour

Le jeu vérifie lui-même s'il existe une nouvelle version et vous propose de la télécharger quand il y en a une. Avant
d'installer une mise à jour, il contrôle sa somme SHA-256. Vous pouvez aussi télécharger la dernière version à la main depuis
la page Releases.

## Compte

La connexion se fait avec votre compte **Discord**. Un compte ne peut être connecté que sur **un seul appareil à la fois** :
la connexion sur un second appareil est refusée tant que le premier est ouvert. Votre collection, vos decks, vos
favoris et votre progression sont rattachés au compte et suivent votre connexion d'un appareil à l'autre.

## Ce que contient le jeu

- **Combats contre l'IA** avec des adversaires au choix, et **multijoueur en ligne** (salon par code, chronomètre de tour).
- **Donjons** avec boss et récompenses, et **puzzles** de difficulté croissante.
- **Tutoriels** guidés et un **Lexique** qui explique chaque mécanique.
- **Éditeur de deck** : plusieurs emplacements nommés, leader, dos de carte, favoris.
- **Boosters** à ouvrir en animation, et une collection à compléter.
- **Compte** : niveau et expérience, Gemmes, Panneaux, quêtes, succès, amis, profil, cadeaux.
- **Voix** des cartes et répliques des Leaders, musiques, journal de partie détaillé.

### Les règles en deux mots

Un deck compte 40 cartes, avec 3 exemplaires maximum d'une même carte. On joue avec le **Nekketsu** (la ressource du tour), on
gagne des **Points Zenkai** pour faire **évoluer** ses Combattants, et certaines cartes ont un **Dernier Souffle** ou un
effet à **compteur** (les Tactiques). Tout est expliqué dans les tutoriels et le Lexique du jeu.

## Problèmes connus

- L'IA ne joue pas le Surrégime, et ses choix de cibles restent simples.
- Il n'existe pas encore de reprise d'une partie en cours : fermer le jeu pendant un combat l'interrompt.
- La version Android et le multijoueur ont été moins testés en conditions réelles que la version PC.

## Signaler un problème ou donner un avis

Ouvrez une *issue* sur ce dépôt, ou contactez l'auteur : **Nakata95**.

## À propos

AniCard Battle est un projet de fan non commercial. Les noms, personnages et univers cités appartiennent à leurs ayants
droit respectifs.
