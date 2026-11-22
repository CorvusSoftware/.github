<div align="center">

  <a href="https://github.com/CorvusSoftware">
    <img src="https://github.com/CorvusSoftware.png" alt="Logo CorvusSoftware" width="112" height="112" />
  </a>

  <h1>CorvusSoftware</h1>

  <p><strong>Des logiciels ouverts, modulaires et indépendants.</strong></p>

  <p>Émulation rétro · Interopérabilité native · Recherche en intelligence artificielle</p>

  <p><sub>Open-source retro emulation, native interoperability & experimental AI research.</sub></p>

  <p>
    <a href="#nos-projets">Découvrir les projets</a> ·
    <a href="#notre-écosystème">Comprendre l’écosystème</a> ·
    <a href="#contribuer">Contribuer</a>
  </p>

</div>

---

## Qui sommes-nous ?

**CorvusSoftware** développe des projets open source autour de l’émulation de consoles classiques, des interfaces natives réutilisables et de la recherche en intelligence artificielle.

Notre approche privilégie la **séparation des responsabilités**, les **interfaces documentées** et le **développement ouvert**. Chaque dépôt a un rôle précis : moteur, contrat d’intégration, application, distribution ou expérimentation.

## Nos projets

### Émulation et interopérabilité

| Projet | Rôle |
| :--- | :--- |
| **[CorvusCore](https://github.com/CorvusSoftware/CorvusCore)** | Moteurs d’émulation **Game Boy, Game Boy Color et Game Boy Advance**, développés en **C++20**. Le support GBA reste expérimental. |
| **[CorvusAPI](https://github.com/CorvusSoftware/CorvusAPI)** | Contrat d’interopérabilité **C** entre cœurs natifs et frontends. L’ABI de base est encore expérimentale. |
| **[CorvusRetro](https://github.com/CorvusSoftware/CorvusRetro)** | Frontend **Android natif en C11** : bibliothèque de jeux, commandes tactiles, sauvegardes et chargement de cœurs. |
| **[CorvusRepository](https://github.com/CorvusSoftware/CorvusRepository)** | Catalogue, validation et distribution indépendante des modules d’émulation compatibles avec CorvusAPI. |

### Recherche en intelligence artificielle

**[CorvusAI](https://github.com/CorvusSoftware/CorvusAI)** explore la création d’un modèle de langage à partir d’une initialisation aléatoire, avec **Python et PyTorch** :

- **CorvusBrain** : modèle, tokenisation, entraînement et inférence locale.
- **CorvusCode** : projet d’assistant de programmation à plus long terme.

> CorvusAI est un projet de recherche **expérimental** ; il ne s’agit pas d’un assistant de programmation prêt pour la production.

## Notre écosystème

- **CorvusCore** fournit les moteurs natifs.
- **CorvusAPI** définit le contrat commun permettant aux frontends d’utiliser des cœurs compatibles.
- **CorvusRetro** exploite ce contrat dans une application Android.
- **CorvusRepository** maintient les catalogues et les archives de cœurs distribués séparément de l’application.
- **CorvusAI** constitue une branche de recherche indépendante consacrée aux modèles de langage.

Cette architecture permet de faire évoluer les moteurs, les interfaces, l’application et leur distribution sans les confondre.

## Technologies

**C11** · **C++20** · **Python** · **PyTorch** · **Android** · **CMake** · **GitHub Actions**

## Contribuer

Les retours techniques, les signalements de bugs et les propositions d’amélioration sont les bienvenus. Consultez la documentation et les consignes de contribution du dépôt concerné avant d’ouvrir une issue ou une pull request.

- [Explorer tous les dépôts](https://github.com/orgs/CorvusSoftware/repositories)
- [Contribuer à CorvusCore](https://github.com/CorvusSoftware/CorvusCore/blob/main/CONTRIBUTING.md)
- [Contribuer à CorvusAI](https://github.com/CorvusSoftware/CorvusAI/blob/main/CONTRIBUTING.md)

## Licences et transparence

Les projets sont publiés sous des licences open source propres à chaque dépôt, notamment **AGPL-3.0-only** et **MIT**. Consultez les fichiers `LICENSE` correspondants avant toute réutilisation.

**Émulation :** aucun jeu commercial, ROM ou BIOS protégé n’est fourni avec les projets. CorvusSoftware n’est pas affilié à Nintendo.

---

<div align="center">
  <sub>Conçu et développé ouvertement par <a href="https://github.com/CorvusSoftware">CorvusSoftware</a>.</sub>
</div>
