---
layout: default
title: Politique de confidentialité
---

<p align="right">
  <a href="../privacy-policy">English</a> | <strong>Français</strong>
</p>

<img src="../assets/images/icon.jpeg" alt="Beanfolio Icon" class="header-logo">

# Politique de confidentialité — Beanfolio

*Dernière mise à jour : 3 mai 2025*

Beanfolio (« l'application », « nous ») est une application iOS permettant de scanner, de collectionner et de découvrir des cafés de spécialité. Cette politique explique quelles données nous collectons, pourquoi nous les collectons et comment vous pouvez les contrôler ou les supprimer.

---

## 1. Ce que nous collectons

### Informations sur le compte
Vous pouvez vous connecter avec Apple ou Google. Lorsque vous vous connectez avec Apple, nous recevons un identifiant d'utilisateur unique et, facultativement, votre nom et votre adresse e-mail, selon l'option de partage que vous choisissez. Lorsque vous vous connectez avec Google, nous recevons votre nom de compte Google, votre adresse e-mail et l'URL de votre photo de profil. Dans les deux cas, ces informations sont stockées dans Firebase Authentication uniquement pour identifier votre compte.

### Photo de profil
Si vous choisissez de télécharger une photo de profil, l'image est stockée dans Google Firebase Cloud Storage et liée à votre compte. Elle n'est partagée avec aucun tiers et est supprimée lorsque vous supprimez votre compte.

### Données de la collection de café
Chaque café que vous scannez est enregistré dans votre collection personnelle dans Firebase Firestore. Cela inclut le nom du torréfacteur, l'origine, le niveau de torréfaction, les notes de dégustation, les scores sensoriels, votre note personnelle et toutes les notes que vous écrivez. Ces données sont privées et liées à votre compte.

### Préférences en matière de café
Lors de l'onboarding, vous pouvez indiquer vos méthodes de préparation, vos préférences de saveurs, vos préférences de torréfaction et votre style de boisson. Ces informations sont stockées dans Firestore et utilisées exclusivement pour personnaliser vos recommandations Discovery.

### Photos des sachets de café
Lorsque vous scannez un sachet de café, la photo que vous prenez est envoyée à l'**API Google Gemini** pour une extraction de données par IA. L'image est transmise via une connexion sécurisée et utilisée uniquement pour extraire les métadonnées du café. Nous ne stockons pas les photos brutes du scan sur nos serveurs — elles sont traitées en temps réel puis supprimées.

### Données Discovery et Wishlist
Les produits que vous ajoutez à votre wishlist et les torréfacteurs pour lesquels vous votez sont stockés dans Firestore sous votre compte. Les résultats Discovery (recommandations hebdomadaires) sont mis en cache dans Firestore pour éviter tout traitement redondant. Les URL des produits que vous avez déjà vus sont suivies pendant 45 jours maximum afin d'éviter de vous montrer plusieurs fois les mêmes suggestions.

### Statistiques d'utilisation
Nous collectons des événements d'utilisation anonymisés (tels que le nombre de cafés scannés ou si vous terminez l'onboarding) via Firebase Analytics. Ces événements ne comprennent pas d'informations personnelles identifiables et sont utilisés uniquement pour comprendre comment l'application est utilisée afin de l'améliorer.

### Rapports de crash
Si l'application plante, un rapport de crash est envoyé à Firebase Crashlytics. Les rapports de crash peuvent inclure le modèle de l'appareil, la version d'iOS et une trace de la pile. Ils n'incluent pas votre nom, votre e-mail ou vos données de café.

---

## 2. Comment nous utilisons vos données

| Données | Finalité |
|---|---|
| Identifiant du compte | Vous authentifier et lier vos données à votre compte |
| Photo de profil | Afficher votre avatar dans l'application |
| Collection de café | Afficher votre bibliothèque personnelle de cafés |
| Préférences en matière de café | Générer des recommandations Discovery personnalisées |
| Photos des sachets de café | Extraire des données structurées du sachet via IA (non stockées) |
| Wishlist & votes | Personnaliser et classer les résultats Discovery |
| Événements analytiques | Comprendre l'utilisation de l'application pour l'améliorer |
| Rapports de crash | Identifier et résoudre les problèmes de stabilité |

Nous ne vendons pas vos données. Nous n'utilisons pas vos données à des fins publicitaires. Nous ne partageons vos données avec aucun tiers, à l'exception des prestataires de services listés ci-dessous, qui sont nécessaires au fonctionnement de l'application.

---

## 3. Services tiers

| Service | Prestataire | Finalité | Politique de confidentialité |
|---|---|---|---|
| Firebase Authentication | Google | Connexion au compte | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Firestore | Google | Stockage de votre collection et de vos préférences | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Cloud Storage | Google | Stockage de votre photo de profil | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Analytics | Google | Statistiques d'utilisation anonymisées | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Crashlytics | Google | Rapports de crash | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| API Gemini | Google | Extraction par IA des photos de sachets de café | [ai.google.dev/gemini-api/terms](https://ai.google.dev/gemini-api/terms) |
| Sign in with Apple | Apple | Authentification du compte | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |
| Sign in with Google | Google | Authentification du compte | [policies.google.com/privacy](https://policies.google.com/privacy) |

Toutes les données transmises entre l'application et ces services sont chiffrées en transit via HTTPS/TLS.

---

## 4. Conservation des données

Vos données sont conservées tant que votre compte existe. Vous pouvez supprimer votre compte à tout moment depuis **Profil → Supprimer le compte**. La suppression de votre compte supprime définitivement :

- Votre enregistrement Firebase Authentication
- L'intégralité de votre collection de café
- Votre wishlist et vos votes de torréfacteurs
- Vos préférences de café et le cache Discovery
- Votre photo de profil de Cloud Storage

Cette action est irréversible.

---

## 5. Vie privée des enfants

Beanfolio ne s'adresse pas aux enfants de moins de 13 ans. Nous ne collectons pas sciemment d'informations personnelles auprès d'enfants. Si vous pensez qu'un enfant nous a fourni des informations personnelles, veuillez nous contacter et nous les supprimerons rapidement.

---

## 6. Vos droits

Selon l'endroit où vous résidez, vous pouvez avoir le droit d'accéder à vos données personnelles, de les corriger ou de les supprimer. Comme toutes les données sont liées à votre compte, vous pouvez :

- **Accéder à vos données** — elles sont toutes visibles dans l'application.
- **Corriger vos données** — modifiez les détails des cafés, vos préférences et votre profil à tout moment.
- **Supprimer vos données** — utilisez la fonction de suppression de compte intégrée à l'application (Profil → Supprimer le compte).

Pour toute autre demande, contactez-nous à l'adresse ci-dessous.

---

## 7. Choix en matière de confidentialité pour l'utilisateur

Nous pensons que vous devez avoir le contrôle sur vos données. Vous pouvez gérer votre confidentialité via les choix suivants :

### Choix d'authentification
- **Sign in with Apple :** Lors de la création de votre compte, vous pouvez choisir de « Partager mon e-mail » ou de « Masquer mon e-mail ». Si vous choisissez de le masquer, Apple créera une adresse e-mail unique et aléatoire qui sera transférée vers votre e-mail personnel, gardant votre véritable adresse privée pour nous.
- **Sign in with Google :** Vous pouvez gérer ou révoquer l'accès pour Beanfolio à tout moment via les paramètres de sécurité de votre compte Google.

### Autorisations de l'appareil
- **Accès à la caméra :** Nous demandons l'accès à la caméra uniquement pour scanner les sachets de café. Vous pouvez accorder ou révoquer cette autorisation à tout moment dans vos **Réglages iOS → Beanfolio → Appareil photo**. En cas de révocation, vous pourrez toujours utiliser l'application mais vous devrez saisir les données du café manuellement.
- **Notifications :** Nous pouvons vous demander l'autorisation de vous envoyer des notifications concernant les nouvelles découvertes hebdomadaires ou les étapes franchies. Vous pouvez les gérer dans **Réglages iOS → Notifications → Beanfolio**.

### Gestion des données
- **Suppression du compte :** Vous pouvez supprimer définitivement votre compte et toutes les données associées à tout moment via **Profil → Supprimer le compte**, comme détaillé dans la Section 4.
- **Analyses anonymisées :** Nos analyses sont conçues pour être respectueuses de la vie privée et anonymisées. Nous ne vous suivons pas sur d'autres applications ou sites web.

---

## 8. Modifications de cette politique

Nous pouvons mettre à jour cette politique au fur et à mesure de l'évolution de l'application. Dans ce cas, nous mettrons à jour la date de « Dernière mise à jour » en haut de la page. L'utilisation continue de l'application après les modifications constitue l'acceptation de la politique mise à jour.

---

## 9. Contact

Si vous avez des questions sur cette politique de confidentialité ou sur la manière dont vos données sont traitées, veuillez nous contacter à l'adresse suivante :

**barista@beanfolio.app**
