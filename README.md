# Tirelire

Depot public **dedie a la distribution** de l'application de bureau **Tirelire** (suivi budgetaire personnel, donnees stockees localement sur votre machine).

Ce depot **ne contient pas le code source**. Les installateurs et les fichiers associes aux mises a jour automatiques sont publies dans l'onglet **Releases**.

---

## Telechargement

**Derniere version publiee :**

[https://github.com/Vitopya/tirelire_app/releases/latest](https://github.com/Vitopya/tirelire_app/releases/latest)

Sur la page de release, ouvrez la section **Assets** et telechargez le fichier adapte a votre systeme :

| Plateforme | Fichier type |
|------------|----------------|
| Windows (64 bits) | `Tirelire-Setup-*.exe` |
| macOS | `Tirelire-*-*.dmg` (recommande) ou `Tirelire-*-*.zip` |

Choisissez l'architecture qui correspond a votre Mac (**x64** pour Intel, **arm64** pour Apple Silicon) si plusieurs paquets sont proposes.

---

## Installation (resume)

### Windows

1. Executez l'installateur `.exe` et suivez les etapes.
2. Si **SmartScreen** affiche un avertissement : **Informations supplementaires** puis **Executer quand meme** (l'application peut ne pas etre signee numeriquement par un certificat payant).
3. Lancez **Tirelire** depuis le menu Demarrer ou le raccourci.

### macOS

1. Ouvrez le fichier `.dmg`, glissez **Tirelire** dans **Applications**.
2. A la premiere ouverture, si macOS bloque l'app : **Reglages** - **Confidentialite et securite** - autorisez l'ouverture, ou clic droit sur l'app - **Ouvrir**.

Le detail des etapes et les informations produit figurent aussi dans la **description de chaque release** sur GitHub.

---

## Donnees personnelles

Tirelire utilise une base **SQLite locale**. Vos donnees ne sont pas envoyees sur ce depot GitHub. Pensez a utiliser la fonction de **sauvegarde** dans l'application avant un changement de machine ou une reinstallation.

---

## Propriete intellectuelle

**Tirelire** est une creation de **Joseph Deffayet** (designer et developpeur).

**Tous droits reserves.** Le logiciel, son interface et la documentation diffusee avec les installateurs sont proteges. Toute reproduction, redistribution ou usage commercial sans **autorisation ecrite prealable** est interdite.

Les conditions detaillees figurent dans le fichier [`LICENSE`](LICENSE) de ce depot.

---

## English (short)

This repository hosts **release binaries** for **Tirelire**, a personal finance desktop app. **No source code** is published here. Download the latest build from [**Releases**](https://github.com/Vitopya/tirelire_app/releases/latest). Copyright **Joseph Deffayet**, all rights reserved. See [`LICENSE`](LICENSE).
