# Tirelire

Dépot public **dédié à la distribution** de l'application bureau **Tirelire** (suivi budgetaire personnel, données stockées localement sur votre machine).

Ce dépot **ne contient pas le code source**. Les installateurs et les fichiers associés aux mises à jour automatiques sont publies dans l'onglet **Releases**.

---

## Téléchargement de l'application

**Derniere version publiée :**

[https://github.com/Vitopya/tirelire_app/releases/latest](https://github.com/Vitopya/tirelire_app/releases/latest)

Sur la page de release, ouvrez la section **Assets** et téléchargez le fichier adapté à votre système :

| Plateforme | Fichier type |
|------------|----------------|
| Windows (64 bits) | `Tirelire-Setup-*.exe` |
| macOS | `Tirelire-*-*.dmg` (recommande) ou `Tirelire-*-*.zip` |

Choisissez l'architecture qui correspond à votre Mac (**x64** pour Intel, **arm64** pour Apple Silicon) si plusieurs paquets sont proposées.

---

## Installation (en bref)

### Windows

1. Executez l'installateur `.exe` et suivez les étapes.
2. Si **SmartScreen** affiche un avertissement : **Informations supplémentaires** puis **Executer quand meme** (l'application peut ne pas etre signee numeriquement par un certificat payant).
3. Lancez **Tirelire** depuis le menu Démarrer ou le raccourci.

### macOS

1. Ouvrez le fichier `.dmg`, glissez **Tirelire** dans **Applications**.
2. A la premiere ouverture, si macOS bloque l'app : **Reglages** - **Confidentialite et securite** - autorisez l'ouverture, ou clic droit sur l'app - **Ouvrir**.

Le détail des étapes et les informations produit figurent aussi dans la **description de chaque release** sur GitHub.

---

## Données personnelles

Tirelire utilise une base **SQLite locale**. Vos données ne sont pas envoyées sur ce dépot GitHub ni nulle part ailleurs. Pensez à utiliser la fonction de **sauvegarde** dans l'application avant un changement de machine ou une réinstallation. Même si l'accent est mis sur la qualité et la résilience du système de mise à jour de Tirelire, il est recommandé de ponctuellement effectuer une sauvegarde de vos données en locale pour prévenir tout risque.

---

## Propriété intellectuelle

**Tirelire** est une creation de **Joseph Deffayet** (designer et vibecodeur).

**Tous droits réservés.** Le logiciel, son interface et la documentation diffusée avec les installateurs sont protégés. Toute reproduction, redistribution ou usage commercial sans **autorisation ecrite préalable** est interdite.

Les conditions détaillees figurent dans le fichier [`LICENSE`](LICENSE) de ce dépot.

---

## English (short)

This repository hosts **release binaries** for **Tirelire**, a personal finance desktop app. **No source code** is published here. Download the latest build from [**Releases**](https://github.com/Vitopya/tirelire_app/releases/latest). Copyright **Joseph Deffayet**, all rights reserved. See [`LICENSE`](LICENSE).
