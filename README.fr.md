<p align="center">
  <img src="https://hievents-public.s3.us-west-1.amazonaws.com/website/hi-events-rainbow.png?v=1" alt="Logo de Hi.Events" width="200px">
</p>
<h3 align="center">Hi.Events</h3>
<p align="center">
<a href="https://demo.hi.events/event/1/dog-conf-2030">Événement Démo 🌟</a> <a href="https://hi.events?utm_source=gh-readme">Site Web 🌎</a>  <a href="https://hi.events/docs">Documentation 📄</a>  <a href="https://hi.events/docs/getting-started?utm_source=gh-readme">Installation ⚙️</a>
</p>

<h3 align="center">
 Gérez facilement vos événements et vendez des billets en ligne.
</h3>

<div align="center">

[![Documentation de Hi.Events](https://img.shields.io/badge/docs-hi.events-blue)](https://hi.events/docs)
[![Licence : AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://github.com/HiEventsDev/hi.events/LICENCE)
[![Version GitHub](https://img.shields.io/github/v/release/HiEventsDev/hi.events?include_prereleases)](https://github.com/HiEventsDev/hi.events/releases)
[![Exécuter les tests unitaires](https://github.com/HiEventsDev/hi.events/actions/workflows/unit-tests.yml/badge.svg?event=push)](https://github.com/HiEventsDev/hi.events/actions/workflows/unit-tests.yml)
[![Téléchargements Docker](https://img.shields.io/docker/pulls/daveearley/hi.events-all-in-one)](https://hub.docker.com/r/daveearley/hi.events-all-in-one)

</div>

<div align="center">
 🌟 Une étoile serait très appréciée ! 🌟
</div>

<hr/>

## Table des Matières

- [Introduction](#-introduction)
- [Fonctionnalités](#-fonctionnalités)
- [Démarrage Rapide](#-démarrage-rapide)
- [Journal des Modifications](#-journal-des-modifications)
- [Contributions](#-contributions)
- [FAQ](#-faq)

## 📚 Introduction

<a href="https://hi.events">Hi.Events</a> est une plateforme de gestion d'événements et de billetterie auto-hébergée, riche en fonctionnalités. Des conférences aux soirées en club, Hi.Events est conçu pour vous aider à créer, gérer et vendre des billets pour des événements de toutes tailles.

<img alt="Tableau de bord de vente de billets auto-hébergé de Hi.Events" src="https://hievents-public.s3.us-west-1.amazonaws.com/website/dashboard-screenshot.png"/>

## 🌟 Fonctionnalités

<a href="https://hi.events">Hi.Events</a> est doté de fonctionnalités pour simplifier la gestion de vos événements et la vente de billets :

- 📊 **Analytique des Événements :** Obtenez des informations approfondies sur les performances de l'événement et les ventes de billets.
- 🎟 **Widget de Billetterie Intégrable :** Intégrez facilement la vente de billets sur n'importe quel site web.
- 🖥 **Pages d'Événements Personnalisables :** Créez des pages d'événements attrayantes avec des options de conception flexibles.
- 🔑 **Outils de Check-In Intuitifs :** Enregistrez facilement les participants à l'entrée avec l'outil de check-in par QR code de Hi.Events.
- 💬 **Outils de Messagerie pour Événements :** Envoyez des messages importants et des rappels aux participants.
- 📝 **Formulaires de Commande Personnalisés :** Collectez des informations sur les participants avec des questions personnalisées lors de la commande.
- 🎫 **Types de Billets Multiples :** Billets gratuits, payants, de donation ou échelonnés.
- 💸 **Codes Promo Polyvalents :** Codes de réduction très polyvalents. Accès en prévente, multiples options de réduction.
- 💰 **Paiements Instantanés :** Profitez de paiements instantanés avec une intégration Stripe transparente.
- 🧾 **Configuration des Taxes et Frais :** Ajoutez des taxes et frais par billet.
- 📦 **Exportations de Données :** Exportez les données des participants et des commandes en XLSX ou CSV.
- 💻 **API REST :** API REST complète pour des intégrations personnalisées.
- 🔍 **Outils de SEO :** Personnalisez les paramètres de SEO pour chaque événement.
- 🛒 **Processus de Paiement Magnifique :** Assurez une expérience de paiement fluide et agréable.
- 🔐 **Accès Basé sur les Rôles :** Support pour plusieurs rôles d'utilisateurs.
- 💻 **Support pour Événements en Ligne :** Offrez des instructions et des liens pour les événements en ligne.
- ⏪ **Support pour Remboursements Complets et Partiels :** Gérez facilement les remboursements complets et partiels.
- 📧 **Notifications par E-mail :** Tenez les participants informés avec des notifications automatiques par e-mail.
- 📱 **Adapté aux Mobiles :** Profitez d'une expérience sans faille sur tous les appareils.
- 🌐 **Support Multilingue :** Support pour plusieurs langues.
- 🎉 **Et bien plus encore !**

## 🚀 Démarrage Rapide

Pour des instructions d'installation détaillées, veuillez consulter notre [documentation](https://hi.events/docs/getting-started). Pour
un démarrage rapide, suivez ces étapes :

### Déploiements en Un Clic

[![Déployer sur DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://github.com/HiEventsDev/hi.events-digitalocean)

[![Déployer sur Render](https://render.com/images/deploy-to-render-button.svg)](https://github.com/HiEventsDev/hi.events-render.com)

[![Déployer sur Railway](https://railway.app/button.svg)](https://railway.app/template/8CGKmu?referralCode=KvSr11)

[![Déployer sur Zeabur](https://zeabur.com/button.svg)](https://zeabur.com/templates/8DIRY6)

### 🐳 Démarrage Rapide avec Docker

> [!IMPORTANT]  
> Veuillez vous assurer que Docker et Docker Compose sont installés sur votre système. Sinon, vous pouvez les télécharger depuis le site officiel de Docker : [Docker](https://www.docker.com/get-started).

1. **Cloner le Répertoire :**
   ```bash
   git clone git@github.com:HiEventsDev/hi.events.git
   ```

2. **Naviguer vers le Répertoire Docker :**
   ```bash
   cd hi.events/docker/all-in-one
   ```

3. **Démarrer les Conteneurs Docker :**
   ```bash
   docker compose up -d
   ```
4. **Créer un compte :**
   ```bash
   Ouvrez votre navigateur et allez à http://localhost:8123/auth/register.
   ```

ℹ️ Veuillez consulter le [guide de démarrage rapide](https://hi.events/docs/getting-started) pour d'autres méthodes d'installation et
pour configurer un environnement de production ou de développement local.

## 📝 Journal des Modifications

Restez à jour avec nos améliorations et ajouts de fonctionnalités sur notre [page de versions GitHub](https://github.com/HiEventsDev/hi.events/releases).

## 🤝 Contributions

Nous accueillons les contributions, suggestions et rapports de bugs ! Avant de proposer une nouvelle fonctionnalité ou extension,
veuillez ouvrir une issue pour en discuter.

## ❓ FAQ

Vous avez des questions ? Notre [documentation](https://hi.events/docs) a des réponses. Si vous ne trouvez pas ce que vous cherchez, n'hésitez pas à
nous contacter à [support@garbagroove.com](mailto:support@garbagroove.com).

## 📜 Licence

Hi.Events est licencié sous les termes de la licence [AGPL-3.0](https://github.com/HiEventsDev/hi.events/blob/main/LICENCE).

Pour plus d'informations sur les licences, y compris les options de licences commerciales, veuillez visiter notre page de licences [ici](https://hi.events/licensing).
